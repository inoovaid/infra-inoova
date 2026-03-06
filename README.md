# [Infra Inoova](https://infra.dnn.lat)

![Website](https://img.shields.io/badge/Website-infra.dnn.lat-blue)

Arquitetura de infraestrutura e cloud privada da Inoova com virtualização, automação, monitoramento e serviços corporativos.

Este projeto documenta a arquitetura de uma infraestrutura moderna baseada em tecnologias open source, incluindo virtualização, containers, automação, observabilidade e gestão de serviços.

O objetivo deste repositório é demonstrar uma arquitetura completa de infraestrutura corporativa, servindo como laboratório de estudo, experimentação de tecnologias e portfólio técnico.

---

# Tecnologias Utilizadas

![Proxmox](https://img.shields.io/badge/Proxmox-Virtualization-orange)
![Docker](https://img.shields.io/badge/Docker-Containers-blue)
![n8n](https://img.shields.io/badge/n8n-Automation-red)
![Zabbix](https://img.shields.io/badge/Zabbix-Monitoring-darkgreen)
![Grafana](https://img.shields.io/badge/Grafana-Dashboards-orange)
![Metabase](https://img.shields.io/badge/Metabase-Analytics-purple)
![Odoo](https://img.shields.io/badge/Odoo-CRM-pink)
![GLPI](https://img.shields.io/badge/GLPI-ITSM-blue)
![pfSense](https://img.shields.io/badge/pfSense-Firewall-red)

---

# Visão Geral da Infraestrutura

A infraestrutura Inoova foi projetada para simular um ambiente corporativo completo com múltiplas camadas tecnológicas.

Principais componentes da arquitetura:

- Virtualização de servidores
- Containers para serviços e aplicações
- Automação de processos operacionais
- Monitoramento da infraestrutura
- Observabilidade e dashboards
- Análise de dados operacionais
- Sistemas corporativos
- Gestão de serviços de TI
- Segurança e controle de rede

A arquitetura combina diferentes tecnologias para criar um ambiente modular, escalável e facilmente gerenciável.

---

# Topologia da Infraestrutura

A topologia da infraestrutura representa a organização dos principais componentes da Cloud Inoova.

![Infraestrutura](diagrams/infra-topology.png)

---

# Cloud Inoova

A Cloud Inoova representa o ambiente virtualizado onde todos os serviços da infraestrutura são executados.

![Cloud Inoova](diagrams/infra-cloud-inoova.png)

Dentro desse ambiente são executados diversos serviços responsáveis por suportar a operação da infraestrutura.

---

# Camadas da Infraestrutura

A arquitetura foi dividida em camadas para facilitar organização e escalabilidade.

## Virtualização

Base da infraestrutura utilizando:

- Proxmox VE

Responsável por hospedar máquinas virtuais e containers que executam os serviços da Cloud Inoova.

---

## Containers

Utilização de containers com:

- Docker

Permite executar serviços de forma isolada e padronizada.

Containers também são utilizados para hospedar serviços de **LLM (Large Language Models)** utilizados em automações inteligentes.

---

## Automação

A automação da infraestrutura é realizada utilizando:

- n8n
- scripts administrativos
- containers Docker

Essas ferramentas permitem integrar sistemas, automatizar processos e executar tarefas operacionais.

---

## Inteligência Artificial

A infraestrutura também integra **modelos de inteligência artificial hospedados localmente (LLM hosted)**.

Esses modelos são executados em containers e podem ser utilizados em automações através do n8n.

Possíveis aplicações:

- processamento de linguagem natural
- automação inteligente
- análise de incidentes
- assistentes internos

---

## Monitoramento

O monitoramento da infraestrutura é realizado utilizando:

- Zabbix
- Grafana

O Zabbix coleta métricas da infraestrutura enquanto o Grafana fornece dashboards e visualização de dados operacionais.

---

## Análise de Dados

A análise de dados da infraestrutura é realizada utilizando:

- Metabase

A plataforma permite criar dashboards e indicadores a partir de diferentes fontes de dados.

Dashboards criados incluem:

- dashboard de monitoramento
- dashboard executivo (CEO da infraestrutura)

---

## Sistemas Corporativos

A infraestrutura também suporta sistemas corporativos importantes.

### CRM

- Odoo

Utilizado para gestão de relacionamento com clientes e organização de oportunidades.

---

### ITSM

- GLPI

Utilizado para gestão de serviços de TI, controle de incidentes e gestão de ativos.

O GLPI está integrado com **n8n** para automação de abertura e tratamento de chamados.

Também está em desenvolvimento uma integração com **LLMs hospedados localmente** para análise inteligente de tickets e automação de suporte.

---

## Web Services

A camada web da infraestrutura permite disponibilizar interfaces e APIs para diferentes serviços.

Esse ambiente também é utilizado para:

- desenvolvimento de novos projetos
- testes de tecnologias
- experimentação de integrações
- prototipagem de soluções

---

## Segurança

A segurança da infraestrutura é implementada utilizando:

- pfSense

O pfSense é executado virtualmente dentro da Cloud Inoova e fornece:

- firewall
- DHCP
- DNS
- NAT
- controle de acesso à rede

Essa camada protege os serviços e controla o tráfego da infraestrutura.

---

# Estrutura do Repositório

infra-inoova
│
├── diagrams
│
├── docs
│ ├── arquitetura
│ ├── virtualizacao
│ ├── automacao
│ ├── monitoramento
│ ├── dados
│ ├── web
│ ├── crm
│ └── itsm
│
└── security

Cada diretório contém documentação detalhada sobre os componentes da infraestrutura.

---

# Objetivo do Projeto

Este projeto tem como objetivos:

- documentar uma arquitetura completa de infraestrutura
- servir como laboratório de estudo
- testar novas tecnologias
- experimentar automações
- integrar diferentes sistemas
- construir um portfólio técnico

---

# Roadmap

Evoluções planejadas para a infraestrutura:

- expansão das automações com n8n
- maior integração com LLMs hospedados localmente
- automação inteligente de ITSM
- novos dashboards de observabilidade
- integração com novos serviços

---

# Autor

Projeto desenvolvido como laboratório de infraestrutura e portfólio técnico.

[![Website](https://img.shields.io/badge/Website-infra.dnn.lat-blue)](https://infra.dnn.lat)

Veja mais em # [Infra Inoova](https://infra.dnn.lat)

