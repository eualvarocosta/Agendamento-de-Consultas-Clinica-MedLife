# 🏥 Sistema Inteligente de Agendamento de Consultas via WhatsApp

Este repositório apresenta a arquitetura de processos, modelagem analítica em notação BPMN e a especificação técnica de requisitos para um sistema inteligente de agendamento de consultas médicas via WhatsApp, utilizando um Agente de IA para automatizar o atendimento da Clínica MedLife.

---

## 🎯 O Problema Resolvido

O projeto foi desenvolvido para solucionar gargalos identificados no processo de agendamento manual da clínica, tais como:

- Elevado tempo de atendimento (aproximadamente 10 minutos por agendamento);
- Dependência da secretária durante o horário comercial;
- Impossibilidade de agendamento fora do expediente (zonas de sombra);
- Alto índice de desistências durante o processo de marcação;
- Taxa significativa de absenteísmo (No-Show) por falta de lembretes.

Como solução, foi modelado um fluxo automatizado utilizando um Agente de IA integrado ao WhatsApp, capaz de realizar o agendamento de consultas 24 horas por dia, 7 dias por semana, além de enviar lembretes automáticos antes da consulta e encaminhar solicitações para outros serviços quando necessário.

---

## 🗺️ Modelagem do Processo (BPMN)

Abaixo está a representação visual do fluxo principal de agendamento automatizado.

### Fluxo Principal

<p align="center">
    <img src="images/diagrama-01.png" width="100%">
</p>

---

### Subprocesso de Lembretes de Consulta

O processo principal possui um subprocesso responsável pelo agendamento e envio automático das notificações de proximidade da consulta (24h, 12h, 4h e 1h antes do atendimento).

<p align="center">
    <img src="images/subtarefa-02.png" width="75%">
</p>

---

## 📊 Business Analytics

Durante a análise foram definidos indicadores de desempenho (KPIs) para mensurar os resultados da solução proposta.

### Resultados Esperados

- ⏱️ Redução do tempo médio de agendamento de **10 minutos para 3 minutos**;
- 📉 Redução da taxa de desistência via WhatsApp de **44% para menos de 15%**;
- 📅 Redução do índice de No-Show de **17% para menos de 4%**;
- 🌙 Atendimento disponível **24 horas por dia, 7 dias por semana**;
- 💰 Aumento da eficiência operacional e redução dos custos administrativos.

---

## 📑 Documentação Técnica Completa

A documentação foi organizada em artefatos separados para facilitar a leitura e consulta.

### 📄 Documento de Engenharia de Requisitos (PDF)

Contém:

- Business Analytics;
- Cenário AS-IS e TO-BE;
- KPIs do projeto;
- ROI estimado;
- Modelagem BPMN;
- Matriz de Requisitos Funcionais;
- Matriz de Requisitos Não Funcionais;
- Histórias de Usuário;
- Critérios de Aceite utilizando Gherkin (Dado / Quando / Então).

➡️ **Baixar Documento Completo (engenharia-requisitos-clinica-medlife.pdf)**

---


## 🛠️ Ferramentas Utilizadas

- BPMN 2.0
- Bizagi Modeler
- Engenharia de Requisitos
- Business Analysis
- Business Analytics
- Gherkin
- WhatsApp Business
- Modelagem de Processos

---

## 👨‍💻 Autor

**Álvaro Costa**

Analista de Sistemas | Analista de Negócios e Requisitos

Especializado em:

- Engenharia de Requisitos
- BPMN
- Business Analysis
- Modelagem de Processos
- Levantamento e Especificação de RequisitosD
