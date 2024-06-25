#  3º HACKATHON – DEVOPS – IT TALENT 2024 

Este projeto foi desenvolvido para o terceiro hackathon, tivemos a oportunidade de aplicar os conhecimentos adquiridos ao longo do curso. 

## Objetivo
Demonstrar a integração prática de Docker, SonarQube, GitHub Actions e AWS S3, automatizando a construção e implantação de uma aplicação React em um bucket S3 da AWS, com análises de qualidade de código via SonarQube.

## Pré-requisitos 
Para realizar as atividades, era necessário ter:

- Docker instalado
- Conta no GitHub
- Conta na AWS

## Desafio
###  Etapa 1: Criação de um projeto SonarQube como contêiner e execução local
- Para essa atividade, iremos criar um projeto do Sonarqube, utilizando como projeto base o nosso repositório de backend: [moisesAlc/Backend- ITTalent](https://github.com/moisesAlc/Backend-IT_Talent). Faça um clone do repositório para o seu computador.
- Em seguida, precisaremos entender como utilizar o Sonarqube na versão de contêiner. Podemos ter uma visão inicial sobre qualquer projeto que esteja no DockerHub, dando uma olhada na página do projeto (assim, obteremos mais detalhes específicos sobre como executar a imagem): [sonarqube - Official Image | Docker Hub](https://hub.docker.com/_/sonarqube)
- Você não usará o SonarQube em produção, então, poderá se utilizar desse passo-a-passo para executar a versão de contêiner local: [Try out SonarQube](https://docs.sonarsource.com/sonarqube/latest/try-out-sonarqube/)
- Deverá baixar o SonarScanner CLI também [SonarScanner CLI](https://docs.sonarsource.com/sonarqube/10.5/analyzing-source-code/scanners/sonarscanner/)
  
### Etapa 2: CI/CD com GitHub Actions e AWS
- Para essa atividade você deverá criar um workflow do Github Actions que irá realizar o build de uma aplicação React [moisesAlc/ReactBasic: Repo CreateReactApp p/ CI/CD IT Talent](https://github.com/moisesAlc/ReactBasic) e, em seguida, subir o conteúdo desse build (que estará na pasta /build) para um bucket S3 da AWS que seja acessível publicamente.
  
## Resultados
### SonarQube
- Configurei e executei um projeto SonarQube utilizando um contêiner Docker.
- Analisei o código do repositório moisesAlc/Backend-IT_Talent com o SonarQube.
- Utilizei o SonarScanner CLI para realizar a análise do código e visualizei os resultados na interface do SonarQube.

### CI/CD com GitHub Actions e AWS
- Criei um workflow do GitHub Actions para buildar a aplicação React com sucesso.
- Configurei o GitHub Actions para enviar o build da aplicação para um bucket S3 na AWS.
- Verifiquei que o conteúdo do bucket S3 estava acessível publicamente.

## Imagens
###  Etapa 1: Criação de um projeto SonarQube como contêiner e execução local

![Imagem1](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/1.png?raw=true)
![Imagem2](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/2.png?raw=true)
![Imagem3](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/3.png?raw=true)
![Imagem4](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/4.png?raw=true)
![Imagem5](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/5.png?raw=true)
![Imagem6](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/6.png?raw=true)
![Imagem7](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/7.png?raw=true)
![Imagem8](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/8.png?raw=true)

### Etapa 2: CI/CD com GitHub Actions e AWS
![Imagem9](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/9.png?raw=true)
![Imagem10](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/10.png?raw=true)
![Imagem11](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/11.png?raw=true)
![Imagem12](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/12.png?raw=true)
![Imagem13](https://github.com/ingridmoitinho/IT_Talent_Hackathon_3/blob/master/prints/13.png?raw=true)

## Conclusão
Participar deste hackathon foi uma experiência enriquecedora que permitiu aplicar na prática os conceitos e ferramentas que aprendemos ao longo do curso. A criação do projeto SonarQube e a configuração do pipeline CI/CD com GitHub Actions e AWS foram desafiadoras, mas extremamente gratificantes. Estou ansiosa para continuar aprimorando minhas habilidades em DevOps e enfrentar novos desafios.

### Nome: Ingrid Moitinho de Souza

