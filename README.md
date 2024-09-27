# Resumo do Lab - Introdução à Computação em Nuvem na DIO

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na plataforma DIO, focado no uso da computação em nuvem com o **Microsoft Azure**.

---

## O que eu aprendi no Primeiro Módulo - Introdução à Computação em Nuvem - Azure

No primeiro módulo, aprendi sobre as várias ferramentas disponíveis no Azure, desde máquinas virtuais até redes, além da flexibilidade de custos baseada no uso. Por exemplo, se eu iniciar um projeto com 30 máquinas e, após 15 dias, perceber que precisarei apenas de 15 máquinas, o custo será proporcional ao tempo de uso dessas 15 máquinas.

Também aprendi sobre os tipos de servidores:
- **Servidores Privados**: Acessados exclusivamente por organizações.
- **Servidores Públicos**: Acessíveis por qualquer pessoa.
- **Servidores Híbridos**: Combinação dos servidores públicos e privados.

Dentro desse contexto, foi apresentada a diferença entre **CapEx** (Capital Expenditure) e **OpEx** (Operational Expenditure):
- **CapEx**: Custo inicial maior em infraestrutura física, com redução de custos ao longo do tempo.
- **OpEx**: Custos operacionais baseados no uso, comuns em soluções de nuvem.

---

## O que eu aprendi no Segundo Módulo - Benefícios da Computação em Nuvem - Azure

### Benefícios da Nuvem e Como São Aplicados

A computação em nuvem traz diversas vantagens, como alta disponibilidade, escalabilidade e segurança. Abaixo, uma explicação detalhada dos principais benefícios:

### 1) Alta Disponibilidade
Os recursos na nuvem têm acordos de nível de serviço (SLA) que garantem uma disponibilidade de 99% a 99,9%. Caso o tempo offline exceda esse limite, o provedor geralmente oferece compensações financeiras.

### 2) Escalabilidade e Elasticidade
A nuvem permite ajustar os recursos automaticamente ou manualmente conforme a demanda. Isso garante que os recursos aumentem ou diminuam, conforme necessário, economizando custos em períodos de baixa demanda.

### 3) Confiabilidade, Previsibilidade e Segurança
A infraestrutura distribuída globalmente proporciona alta confiabilidade e resiliência. Além disso, ferramentas como o **Microsoft Azure Well-Architected Framework** ajudam a garantir previsibilidade tanto no desempenho quanto nos custos.

### 4) Governança e Gerenciabilidade
A nuvem oferece ferramentas para auditoria contínua e conformidade com as políticas corporativas. Além disso, possibilita o gerenciamento de recursos por meio de APIs e **PowerShell**, oferecendo flexibilidade e controle.

---

## O que eu aprendi no Terceiro Módulo - Tipos de Serviço em Nuvem - Azure

### Tipos de Serviço de Nuvem

Existem três principais tipos de serviço na nuvem:

### 1) IaaS (Infraestrutura como Serviço)
Permite alugar infraestrutura, como servidores virtuais, armazenamento e redes, sem a necessidade de gerenciar hardware físico.
- **Exemplo**: Microsoft Azure, AWS EC2.

### 2) PaaS (Plataforma como Serviço)
Além da infraestrutura, oferece ferramentas de desenvolvimento e bancos de dados para criar, testar e implantar aplicativos sem gerenciar os detalhes da infraestrutura.
- **Exemplo**: Microsoft Azure App Services, Google App Engine.

### 3) SaaS (Software como Serviço)
Oferece aplicativos completos hospedados na nuvem, acessíveis via navegador ou aplicativo.
- **Exemplo**: Microsoft Office 365, Gmail, Salesforce.

---

## Modelo de Responsabilidade Compartilhada

O modelo de responsabilidade compartilhada distribui as responsabilidades de segurança e gerenciamento entre o provedor de nuvem e o cliente, variando conforme o tipo de serviço:

### IaaS (Infraestrutura como Serviço)
- **Provedor de Nuvem**: Infraestrutura física (servidores, rede, armazenamento).
- **Cliente**: Gerenciamento do sistema operacional, aplicativos, dados e segurança.

### PaaS (Plataforma como Serviço)
- **Provedor de Nuvem**: Infraestrutura, sistemas operacionais, middleware.
- **Cliente**: Dados e aplicativos implantados.

### SaaS (Software como Serviço)
- **Provedor de Nuvem**: Infraestrutura, software, segurança do sistema.
- **Cliente**: Configuração de usuários, segurança de dados e permissões.


