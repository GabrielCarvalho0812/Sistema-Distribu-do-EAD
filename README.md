 # Sistema-Distribuido-ead 
**(o Projeto ainda está sendo desenvolvido)**

Repositório principal do Sistema Distribuído EAD, uma aplicação educacional construída com base em arquitetura de microservices. Este repositório centraliza a documentação geral do projeto e os links para os repositórios individuais de cada microserviço, organizando os serviços de negócio e infraestrutura que compõem o sistema.

# Sistema Distribuído EAD

Este projeto é uma aplicação educacional baseada em arquitetura de microservices. Cada serviço é mantido em um repositório separado.

## 🔧 Microservices de Negócios

| Serviço         | Descrição                            | Repositório                                              |
|----------------|----------------------------------------|----------------------------------------------------------|
| User Service    | Gerenciamento de usuários             | [user-service](https://github.com/GabrielCarvalho0812/Authuser-ead) |
| Course Service  | Gerenciamento de cursos               | [course-service](https://github.com/GabrielCarvalho0812/Course-ead) |
| Notification    | Envio de notificações                 | [notification-service](https://github.com/GabrielCarvalho0812/notification-ead) |
| Payment         | Processamento de pagamentos           | [payment-service](https://github.com/GabrielCarvalho0812/payment-ead) |

## ⚙️ Microsservices de Configuraçoẽs

| Serviço          | Função                             | Repositório                                                |
|------------------|------------------------------------|------------------------------------------------------------|
| Config Server     | Central de configuração            | []() |
| Discovery Server  | Registro e descoberta de serviços  | [discovery-server](https://github.com/GabrielCarvalho0812/Service-Registry-ead) |
| API Gateway       | Roteamento de requisições          | []() |

---

## ℹ️ Sobre o projeto

O **Sistema Distribuído EAD** é composto por microserviços que simulam uma plataforma de ensino online, com funcionalidades separadas por domínio de negócio e serviços de infraestrutura. O objetivo do projeto é aplicar conceitos reais de arquitetura distribuída, como:
- Separação de responsabilidades por serviço
- Comunicação entre serviços
- Escalabilidade e modularidade

