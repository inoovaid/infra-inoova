
# Virtualização com Proxmox

A camada de virtualização da infraestrutura Inoova é baseada no **Proxmox VE (Virtual Environment)**, uma plataforma open source para gerenciamento de máquinas virtuais e containers.

O Proxmox permite consolidar diversos serviços em uma infraestrutura centralizada, oferecendo recursos avançados de gerenciamento, alta disponibilidade e escalabilidade.

---

# Visão Geral da Virtualização

A virtualização permite executar múltiplos sistemas operacionais e aplicações em um único conjunto de servidores físicos.

Na infraestrutura Inoova, o Proxmox é responsável por:

- Hospedar máquinas virtuais
- Executar containers
- Gerenciar recursos computacionais
- Centralizar o gerenciamento da infraestrutura

---

# Arquitetura da Virtualização

O ambiente de virtualização é composto por:

- Hypervisor Proxmox
- Máquinas Virtuais (VMs)
- Containers
- Armazenamento para discos virtuais
- Rede virtual

Cada serviço da infraestrutura é executado em uma máquina virtual ou container dentro do ambiente Proxmox.

---

# Principais Serviços Hospedados

Dentro do ambiente virtualizado são executados diversos serviços essenciais para a infraestrutura.

Exemplos:

- Zabbix (monitoramento)
- Grafana (dashboards)
- Metabase (análise de dados)
- Odoo (CRM)
- GLPI (ITSM)
- Web Server
- n8n (automação)

Essa abordagem permite maior flexibilidade e isolamento entre os serviços.

---

# Gerenciamento de Recursos

O Proxmox permite controlar e distribuir recursos entre as máquinas virtuais.

Principais recursos gerenciados:

- CPU
- Memória RAM
- Armazenamento
- Interfaces de rede

Esse gerenciamento garante que cada serviço tenha os recursos necessários para operar corretamente.

---

# Rede Virtual

A rede virtual dentro do Proxmox conecta as máquinas virtuais e permite comunicação entre os serviços da infraestrutura.

Principais componentes:

- Bridges de rede
- Interfaces virtuais
- Segmentação de rede

Essa estrutura permite integrar as máquinas virtuais com a rede física da infraestrutura.

---

# Benefícios da Virtualização

A utilização do Proxmox traz diversas vantagens para a infraestrutura:

- Melhor utilização de recursos de hardware
- Isolamento entre serviços
- Facilidade de gerenciamento
- Escalabilidade da infraestrutura
- Criação rápida de novos serviços

---

# Uso no Projeto Infra Inoova

No contexto do projeto Infra Inoova, o Proxmox é utilizado como a base da **Cloud Inoova**, permitindo executar todos os serviços da infraestrutura em um ambiente virtualizado e centralizado.

Essa abordagem simula um ambiente corporativo real, onde diversos serviços são executados em clusters de virtualização.

---

# Referências

Proxmox VE Official Website

https://www.proxmox.com
