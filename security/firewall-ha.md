# Firewall em Alta Disponibilidade (HA)

A infraestrutura Inoova possui uma camada dedicada de segurança responsável por proteger os serviços da Cloud Inoova e controlar o acesso à rede.

Essa camada é composta por um **firewall configurado em alta disponibilidade (High Availability - HA)**, garantindo maior segurança, redundância e continuidade operacional.

O firewall utilizado na infraestrutura é baseado no **pfSense**, executado em ambiente virtualizado dentro da Cloud Inoova.

---

# Objetivo da Camada de Segurança

A camada de firewall tem como objetivo proteger a infraestrutura contra acessos não autorizados e controlar o tráfego entre diferentes redes.

Principais funções:

- Controle de acesso à infraestrutura
- Filtragem de tráfego de rede
- Segmentação de redes internas
- Proteção de serviços expostos
- Monitoramento de tráfego

---

# pfSense na Infraestrutura

O **pfSense** é uma plataforma open source amplamente utilizada para segurança de redes e gerenciamento de tráfego.

Na Infra Inoova, o pfSense é utilizado como componente central da camada de segurança e serviços de rede.

Principais funções utilizadas:

- Firewall
- DHCP Server
- DNS Resolver
- NAT
- Controle de acesso à rede
- Gerenciamento de regras de segurança

A utilização do pfSense permite centralizar diferentes funções de rede em um único ponto de controle.

---

# Arquitetura do Firewall

O firewall é executado dentro do ambiente virtualizado da **Cloud Inoova**, normalmente hospedado em máquinas virtuais gerenciadas pelo Proxmox.

Arquitetura simplificada:

Internet  
↓  
Firewall pfSense (HA)  
↓  
Rede Interna  
↓  
Serviços da Cloud Inoova

Essa estrutura permite controlar o tráfego entre redes externas e internas da infraestrutura.

---

# Alta Disponibilidade (HA)

Para garantir maior confiabilidade, o firewall pode ser configurado em modo de **alta disponibilidade**, permitindo que múltiplas instâncias do firewall operem de forma redundante.

Benefícios da alta disponibilidade:

- Continuidade dos serviços
- Redução de pontos únicos de falha
- Maior resiliência da infraestrutura
- Manutenção sem interrupção de serviços

---

# Serviços de Rede

Além da proteção da infraestrutura, o pfSense também fornece serviços essenciais de rede.

Principais serviços utilizados:

### DHCP

Responsável por distribuir endereços IP automaticamente para dispositivos da rede.

---

### DNS

Permite resolver nomes de domínio para endereços IP dentro da infraestrutura.

Esse serviço facilita a comunicação entre sistemas e aplicações.

---

### NAT

Responsável por traduzir endereços de rede internos para acesso à internet.

---

# Integração com a Infraestrutura

O firewall atua como ponto central de controle de rede e se integra com diversos componentes da infraestrutura.

Exemplos de integração:

- Proxmox (virtualização)
- Servidores da infraestrutura
- Serviços web
- Monitoramento com Zabbix
- Automação com n8n

Essa integração permite que o firewall faça parte do ecossistema operacional da infraestrutura.

---

# Uso no Projeto Infra Inoova

No contexto do projeto Infra Inoova, o pfSense representa a camada de segurança e gerenciamento de rede da infraestrutura.

A utilização de um firewall virtualizado demonstra como ambientes modernos podem utilizar soluções open source para implementar controle de acesso, segmentação de rede e serviços essenciais de infraestrutura.

Essa abordagem simula arquiteturas utilizadas em ambientes corporativos e laboratórios de infraestrutura.

---

# Referências

pfSense Official Website

https://www.pfsense.org
