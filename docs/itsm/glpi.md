# ITSM com GLPI

A infraestrutura Inoova utiliza o **GLPI** como plataforma de ITSM (IT Service Management), permitindo gerenciar chamados, ativos de TI e processos operacionais da infraestrutura.

O GLPI é uma solução open source amplamente utilizada para gestão de serviços de TI, oferecendo funcionalidades para controle de incidentes, requisições, inventário de ativos e organização de processos de suporte.

---

# Objetivo do ITSM na Infraestrutura

A implementação de um sistema ITSM permite organizar e estruturar os processos de suporte e gestão da infraestrutura.

Principais objetivos:

- Gerenciar chamados de suporte
- Organizar incidentes e requisições
- Controlar ativos de TI
- Centralizar informações operacionais
- Estruturar processos de atendimento

---

# Arquitetura do Sistema

O GLPI é executado dentro da **Cloud Inoova**, hospedado em uma máquina virtual ou container dentro do ambiente virtualizado.

Arquitetura simplificada:

Usuários  
↓  
Interface Web do GLPI  
↓  
Aplicação GLPI  
↓  
Banco de Dados  

Essa arquitetura permite acesso ao sistema através de interface web, facilitando o gerenciamento dos serviços de TI.

---

# Funcionalidades do GLPI

O GLPI oferece diversas funcionalidades para gestão da infraestrutura de TI.

Principais recursos:

### Gestão de Chamados

- Registro de incidentes
- Controle de requisições
- Acompanhamento de tickets
- Histórico de atendimento

---

### Gestão de Ativos

- Inventário de equipamentos
- Controle de dispositivos
- Organização de ativos de TI
- Relacionamento entre equipamentos e serviços

---

### Gestão de Usuários

- Controle de acesso
- Organização de equipes
- Registro de atividades

---

# Integração com Automação

O GLPI está integrado com a camada de automação da infraestrutura através do **n8n**.

Essa integração permite automatizar diversos processos relacionados à gestão de chamados e eventos operacionais.

Exemplos de automação:

- Criação automática de tickets
- Atualização de status de chamados
- Notificações automatizadas
- Integração com eventos de monitoramento

Essa integração melhora a eficiência operacional e reduz tarefas manuais.

---

# Integração com Inteligência Artificial

A infraestrutura Inoova também está em desenvolvimento para integrar o GLPI com **serviços de inteligência artificial baseados em LLM (Large Language Models)** hospedados localmente.

Esses modelos são executados em containers Docker e podem ser utilizados para ampliar as capacidades do sistema ITSM.

Possíveis aplicações incluem:

- Classificação automática de chamados
- Sugestão de soluções para incidentes
- Análise de descrições de problemas
- Assistentes inteligentes para suporte técnico

Essa abordagem permite evoluir o sistema de gestão de serviços de TI para um modelo mais inteligente e automatizado.

---

# Benefícios do Uso do GLPI

A utilização do GLPI traz diversas vantagens para a gestão da infraestrutura.

Principais benefícios:

- Organização dos processos de suporte
- Centralização das informações operacionais
- Melhor controle de ativos de TI
- Integração com automação
- Possibilidade de expansão com inteligência artificial

---

# Uso no Projeto Infra Inoova

No contexto do projeto Infra Inoova, o GLPI representa a camada de **gestão de serviços de TI**, permitindo organizar processos de suporte, registrar incidentes e acompanhar demandas relacionadas à infraestrutura.

O sistema está integrado com a plataforma de automação **n8n**, permitindo automatizar processos relacionados à abertura e tratamento de chamados. Essa integração possibilita a criação de workflows automatizados que podem:

- abrir chamados automaticamente a partir de eventos
- atualizar status de tickets
- enviar notificações
- executar rotinas de tratamento de incidentes
- integrar dados com outros sistemas da infraestrutura

Além disso, está em desenvolvimento uma **integração com serviços de inteligência artificial baseados em LLM (Large Language Models)** hospedados localmente na infraestrutura.

Essa integração tem como objetivo ampliar as capacidades do sistema ITSM, permitindo funcionalidades como:

- análise automática de chamados
- classificação inteligente de incidentes
- sugestão de soluções para problemas
- apoio automatizado ao suporte técnico
- automação de tarefas operacionais

Essa frente de desenvolvimento faz parte da evolução da infraestrutura Inoova, explorando o uso de **automação e inteligência artificial aplicada à gestão de serviços de TI**, aproximando o ambiente de práticas modernas utilizadas em operações de infraestrutura e suporte técnico.

---

# Referências

GLPI Official Website

https://glpi-project.org
