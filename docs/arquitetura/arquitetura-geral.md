# Arquitetura Geral da Infraestrutura Inoova

A infraestrutura da Inoova foi projetada para simular um ambiente corporativo moderno, utilizando conceitos de cloud privada, virtualização, automação e monitoramento.

O objetivo deste projeto é demonstrar a arquitetura e os serviços que compõem uma infraestrutura de TI completa, documentando todos os componentes utilizados.

---

# Visão Geral da Infraestrutura

A infraestrutura é composta por diferentes camadas que trabalham em conjunto para fornecer serviços corporativos, alta disponibilidade e facilidade de gerenciamento.

Principais componentes:

- Virtualização com Proxmox
- Containers com Docker
- Automação com n8n
- Monitoramento com Zabbix
- Dashboards com Grafana
- Business Intelligence com Metabase
- CRM com Odoo
- ITSM com GLPI
- Web Server
- Firewall em alta disponibilidade

---

# Topologia da Infraestrutura

A arquitetura da infraestrutura é baseada em um modelo de cloud privada hospedada em ambiente virtualizado.

![Topologia da Infraestrutura](../../diagrams/infra-topology.png)

A topologia apresenta:

- Conectividade com internet
- Camada de segurança
- Ambiente de virtualização
- Cluster de serviços
- Monitoramento e automação

---

# Cloud Inoova

A Cloud Inoova representa o ambiente virtualizado onde todos os serviços da infraestrutura são executados.

![Cloud Inoova](../../diagrams/infra-cloud-inoova.png)

Dentro da cloud são executados diversos serviços responsáveis por suportar as operações da organização.

---

# Camadas da Arquitetura

A infraestrutura foi dividida em camadas para facilitar o gerenciamento e a escalabilidade.

## Camada de Rede

Responsável pela conectividade da infraestrutura.

Componentes:

- Internet
- Links ISP
- Firewall
- Switch Core
- Segmentação de rede

---

## Camada de Virtualização

Responsável pela execução das máquinas virtuais e containers.

Tecnologia utilizada:

- Proxmox VE

Funções principais:

- Hospedagem de máquinas virtuais
- Execução de containers
- Gerenciamento de recursos
- Alta disponibilidade

---

## Camada de Serviços

Nesta camada são executados os serviços corporativos da infraestrutura.

Principais serviços:

- CRM (Odoo)
- ITSM (GLPI)
- Web Server
- Automação (n8n)
- Dashboards (Metabase)

---

## Camada de Monitoramento

Responsável por monitorar toda a infraestrutura.

Ferramentas utilizadas:

- Zabbix
- Grafana

Funções:

- Monitoramento de servidores
- Monitoramento de serviços
- Alertas
- Visualização de métricas

---

## Camada de Automação

A automação permite reduzir tarefas manuais e melhorar a eficiência operacional.

Ferramentas utilizadas:

- n8n
- Scripts administrativos
- Containers Docker

---

# Objetivos do Projeto

Este projeto tem como objetivo:

- Documentar a arquitetura da infraestrutura Inoova
- Demonstrar conhecimentos em infraestrutura, cloud e programação
- Servir como laboratório de estudo
- Criar um portfólio técnico documentado

---

# Tecnologias Utilizadas

Infraestrutura:

- Proxmox
- Docker
- Linux
- Windows Server

Monitoramento:

- Zabbix
- Grafana

Automação:

- n8n
- Scripts

Aplicações:

- Odoo
- GLPI
- Metabase

---

# Próximos Passos

A documentação detalhada de cada componente da infraestrutura pode ser encontrada nos seguintes diretórios:

- Virtualização
- Automação
- Monitoramento
- Dados
- Web
- CRM
- ITSM
