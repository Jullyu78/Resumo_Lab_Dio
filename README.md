# Resumo_Lab_Dio
Resumo do lab na DIO.

Tipos de Serviços em Nuvem: IaaS, PaaS e SaaS - Definição e Funcionamento.

1. IaaS (Infrastructure as a Service) 
- O que é: Serviço de infraestrutura em nuvem (servidores virtuais, redes, armazenamento).  
- Como funciona:  
  - O provedor (AWS, Azure, Google Cloud) oferece hardware virtualizado.  
  - Você aluga esses recursos e gerencia SO, aplicativos e dados.  
- Exemplo: Criar uma VM (máquina virtual) na AWS para hospedar um banco de dados.  

2. PaaS (Platform as a Service)  
- O que é: Plataforma pronta para desenvolver e publicar aplicativos.  
- Como funciona:  
  - O provedor (Heroku, Google App Engine) cuida da infraestrutura e ferramentas (banco de dados, APIs).  
  - Você só se preocupa com o código do aplicativo.  
- Exemplo: Publicar um app web no Heroku sem configurar servidores.  

3. SaaS (Software as a Service)  
- O que é: Software completo acessado online, sem instalação.  
- Como funciona:  
  - O provedor (Google, Microsoft) hospeda e mantém o software.  
  - Você só usa (via navegador/app) e paga por assinatura.  
- Exemplo: Usar o Gmail ou Netflix sem se preocupar com atualizações ou servidores.  

Comparação Prática

| **Modelo** | **Controle do Usuário** | **Gerenciado pelo Provedor** | **Exemplo** |  
|------------|-------------------------|------------------------------|-------------|  
| **IaaS**   | SO, apps, dados         | Hardware, virtualização      | AWS EC2     |  
| **PaaS**   | Apenas código           | Infra, SO, runtime           | Heroku      |  
| **SaaS**   | Configurações           | Tudo (software e infra)      | Zoom        |  

Como Escolher?  
- IaaS: Para times de TI que precisam de personalização total.  
- PaaS: Para devs que querem velocidade no desenvolvimento.  
- SaaS: Para usuários que buscam soluções prontas.  

Resumo Visual: 
- IaaS = "Alugo um terreno e construo minha casa."  
- PaaS = "Alugo uma casa e decoro por dentro." 
- SaaS = "Alugo um quarto em um hotel."  

Esses modelos formam a base da **computação em nuvem**, atendendo desde empresas até usuários finais.
