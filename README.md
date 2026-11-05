
<div align="center">

# 📦 LogiAI
### Inteligência que movimenta a logística.

**Automação • Inteligência Artificial • IoT • Gestão Inteligente**

Uma plataforma inteligente que conecta o mundo físico ao digital, automatizando processos logísticos e transformando dados em decisões estratégicas.

<br>

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-Backend-blue?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![IoT](https://img.shields.io/badge/IoT-Automação-green?style=for-the-badge)

</div>

---

## 🌐 Sobre o Projeto

O **LogiAI** é um ecossistema de inteligência logística desenvolvido para modernizar operações de armazenamento, distribuição e gerenciamento de mercadorias.

A solução combina Internet das Coisas (IoT), Inteligência Artificial e desenvolvimento web para criar um ambiente integrado, capaz de automatizar a separação de produtos, acompanhar movimentações em tempo real e antecipar possíveis problemas de estoque.

Mais do que monitorar operações, o LogiAI busca tornar a logística **mais inteligente, eficiente e previsível**.

## 🚨 O Problema

Os processos logísticos tradicionais ainda enfrentam desafios que comprometem a produtividade e aumentam os custos operacionais.

| Problema | Consequência |
|---|---|
| 📉 Falta de produtos | Rupturas de estoque e perda de oportunidades |
| 📦 Triagem manual | Lentidão e erros na separação |
| 📊 Falta de monitoramento | Dificuldade para acompanhar operações |
| 🔮 Ausência de previsão | Compras desnecessárias ou insuficientes |

O LogiAI surge para enfrentar esses desafios por meio da integração entre automação física e inteligência digital.

## 💡 Nossa Solução

O sistema é dividido em três pilares principais:

### 01. 🤖 Automação Física — IoT

Uma esteira automatizada utiliza microcontroladores, sensores e mecanismos eletrônicos para identificar e direcionar mercadorias.

- Identificação automática de objetos.
- Leitura de sensores em tempo real.
- Separação automatizada por categorias.
- Registro das movimentações.

### 02. 🧠 Inteligência Artificial — Data Science

Um backend desenvolvido em Python processa os dados coletados e utiliza modelos analíticos para auxiliar na gestão logística.

- Análise de movimentação de produtos.
- Previsão de demanda.
- Identificação de possíveis rupturas.
- Recomendações inteligentes de reposição.

### 03. 📊 Dashboard Inteligente — Gestão

Uma interface web centraliza as informações e permite acompanhar o funcionamento do sistema.

- Monitoramento da esteira em tempo real.
- Visualização de estoque.
- Indicadores de desempenho (KPIs).
- Alertas e notificações.
- Histórico de movimentações.

---

## 🏗️ Arquitetura do Sistema

O LogiAI funciona por meio da comunicação entre hardware, backend, banco de dados e interface web.

```text
       📦 CAMADA FÍSICA
    ┌──────────────────────┐
    │    Esteira IoT       │
    │ ESP32 + Sensores     │
    │ Servomotores         │
    └──────────┬───────────┘
               │
          MQTT / HTTP
               │
               ▼
    ┌──────────────────────┐
    │   BACKEND INTELIGENTE│
    │       Python         │
    │       FastAPI        │
    │    Motor de IA       │
    └──────────┬───────────┘
               │
               ▼
    ┌──────────────────────┐
    │     SUPABASE         │
    │     PostgreSQL       │
    │  Armazenamento       │
    └──────────┬───────────┘
               │
         Realtime API
               │
               ▼
    ┌──────────────────────┐
    │   DASHBOARD WEB      │
    │       React          │
    │    Tailwind CSS      │
    │   Monitoramento      │
    └──────────────────────┘
```

## 🛠️ Tecnologias

| Camada | Tecnologias |
|---|---|
| Frontend | React, Tailwind CSS, Lucide Icons |
| Backend | Python, FastAPI |
| Banco de dados | Supabase, PostgreSQL |
| Inteligência Artificial | Scikit-learn, Prophet, Pandas |
| Comunicação | REST API, MQTT, WebSockets |
| Hardware | ESP32, Arduino, C++ |
| Versionamento | Git, GitHub |

## 📊 Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| Monitoramento em tempo real | Acompanhamento das operações |
| Triagem automatizada | Separação inteligente de mercadorias |
| Controle de estoque | Registro de entradas e saídas |
| Previsão de demanda | Estimativa de necessidades futuras |
| Alertas inteligentes | Identificação de possíveis problemas |
| Indicadores logísticos | Análise de produtividade e desempenho |

## 🖥️ Interface do Sistema

O dashboard será desenvolvido para oferecer uma visão centralizada da operação logística.

**Principais áreas previstas:**

- Dashboard geral.
- Monitoramento da esteira.
- Gestão de estoque.
- Análise de dados.
- Previsões de demanda.
- Configurações do sistema.

> As interfaces serão implementadas e evoluídas durante o desenvolvimento do projeto.

## 📁 Estrutura do Projeto

```text
logiai/
│
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── core/
│   │   ├── models/
│   │   └── services/
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.jsx
│   │   └── index.css
│   └── package.json
│
├── hardware/
│   └── esp32_logiai.ino
│
├── .gitignore
├── LICENSE
└── README.md
```

## 🚀 Como Executar

### Pré-requisitos

- Node.js 18+
- Python 3.10+
- Git
- ESP32 ou Arduino (opcional)

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/logiai.git
cd logiai
```

### 2. Backend

```bash
cd backend

python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

Instalar dependências:

```bash
pip install -r requirements.txt
```

Executar:

```bash
uvicorn main:app --reload --port 8000
```

API:

Documentação:

### 3. Frontend

Em outro terminal:

```bash
cd frontend

npm install
npm run dev
```

Acesse:

### 4. Hardware

1. Abra `hardware/esp32_logiai.ino` na Arduino IDE.
2. Configure as credenciais da rede Wi-Fi.
3. Configure o endereço do backend.
4. Conecte o ESP32.
5. Faça o upload do firmware.

## 📡 Comunicação entre Hardware e Backend

Exemplo de evento enviado pelo ESP32:

```json
{
  "sensor_id": "ESTEIRA_01",
  "categoria_detectada": "eletronicos",
  "peso_gramas": 450,
  "timestamp": "2026-03-30T14:22:10Z"
}
```

Exemplo de resposta:

```json
{
  "status": "sucesso",
  "acao_separador": "ROTA_SETOR_A1",
  "estoque_atualizado": 143,
  "alerta_ia": null
}
```

## 🎯 Objetivo e Impacto

O LogiAI busca contribuir para a transformação digital da logística, oferecendo:

- Maior eficiência operacional.
- Redução de falhas nos processos.
- Melhor controle de mercadorias.
- Decisões orientadas por dados.
- Planejamento inteligente de estoque.

**Nossa visão é transformar operações logísticas tradicionais em processos conectados, automatizados e inteligentes.**

## 👥 Equipe — Hack Brasil

| Integrante | Responsabilidade |
|---|---|
| Thiago da Silva | Full-stack, arquitetura e integração |
| Integrante 2 | Hardware, embarcados e IoT |
| Integrante 3 | Data Science e Inteligência Artificial |
| Integrante 4 | Design, produto e apresentação |

## 📜 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

---

<div align="center">

### 📦 LogiAI
**O futuro da logística é inteligente.**

*Desenvolvido para o Hack Brasil.*

</div>
