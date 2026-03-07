# EVE-NG – Network Lab

O **EVE-NG (Emulated Virtual Environment – Next Generation)** é uma plataforma utilizada para criação de laboratórios virtuais de redes, permitindo simular ambientes complexos de infraestrutura e telecomunicações.

Ele possibilita executar diferentes sistemas de rede virtualizados dentro de um único ambiente, permitindo testes, validação de arquiteturas e estudo de tecnologias utilizadas em provedores e ambientes corporativos.

No projeto **Infra Inoova**, o EVE-NG é utilizado para construir laboratórios avançados de rede, incluindo simulações de provedores de internet (ISP) e ambientes multivendor.

---

# Uso no Projeto Infra Inoova

Dentro da arquitetura da Infra Inoova, o **EVE-NG** é utilizado como plataforma de laboratório para simulação de infraestrutura de rede.

Através dele é possível:

- Simular ambientes de **provedores de internet (ISP)**
- Testar **protocolos de roteamento**
- Construir topologias **multivendor**
- Validar arquiteturas de rede antes da implementação
- Estudar cenários de alta disponibilidade e redundância

O laboratório é executado dentro da infraestrutura virtualizada da Inoova, permitindo integração com outras ferramentas da plataforma.

---

# ISP Lab – Ambiente Multivendor

Um dos principais laboratórios implementados no EVE-NG é o **ISP Lab**, que simula um ambiente de provedor de internet com diferentes fabricantes de equipamentos.

Este ambiente permite estudar e testar protocolos de rede em cenários reais de operação.

Tecnologias utilizadas no laboratório:

- **Mikrotik RouterOS**
- **Cisco IOL**
- **Huawei AR1000v**
- **Linux Clients**
- **Fortinet**

A topologia inclui componentes típicos de um provedor:

- Roteadores de **Core**
- Roteadores de **Borda**
- **Upstreams**
- **Clientes simulados**
- Interconexões redundantes

---

# Protocolos e Tecnologias Testadas

Dentro do laboratório são explorados diversos protocolos utilizados em redes corporativas e provedores:

- **OSPF**
- **BGP**
- **VLAN**
- **NAT**
- **Policy Routing**
- **High Availability**
- **Load Balancing**

Isso permite simular cenários reais de operação de redes.

---

# Integração com a Infra Inoova

O laboratório de redes roda integrado com a infraestrutura principal da Inoova, permitindo interação com outras plataformas do ambiente.

Entre elas:

- **Monitoramento via Zabbix**
- **Dashboards via Grafana**
- **Análise de dados via Metabase**
- **Automação via n8n**
- **Serviços rodando em containers Docker**

Essa integração transforma o laboratório em um ambiente completo de experimentação de infraestrutura.

---

# Objetivo do Laboratório

O objetivo do laboratório EVE-NG dentro do projeto Infra Inoova é:

- Estudar arquiteturas de rede
- Simular ambientes corporativos e de provedores
- Validar configurações antes de implementação
- Aprender novas tecnologias
- Construir um portfólio técnico de infraestrutura

Esse laboratório faz parte do ecossistema da **Infra Inoova**, que combina virtualização, automação, monitoramento e serviços corporativos em uma única arquitetura integrada.
As tecnologias utilizadas neste laboratório foram estudadas a partir de documentações oficiais e boas práticas da indústria de infraestrutura e redes.

---

# Referências

Documentação oficial e materiais utilizados como base para estudo e implementação do laboratório.

- **EVE-NG Official Website**  
  https://www.eve-ng.net/

- **EVE-NG Documentation**  
  https://www.eve-ng.net/index.php/documentation/

- **Mikrotik RouterOS Documentation**  
  https://help.mikrotik.com/docs/

- **Cisco Networking Documentation**  
  https://www.cisco.com/c/en/us/support/index.html

- **Huawei Enterprise Support**  
  https://support.huawei.com/enterprise/

- **Zabbix Documentation**  
  https://www.zabbix.com/documentation

- **Grafana Documentation**  
  https://grafana.com/docs/

- **Metabase Documentation**  
  https://www.metabase.com/docs/latest/

- **n8n Documentation**  
  https://docs.n8n.io/

- **Docker Documentation**  
  https://docs.docker.com/
