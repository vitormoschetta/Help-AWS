# Help-AWS


## **Amplify AWS*

#### Implantar SPA e Sites estáticos

Implantar um site estático / Single Page App é muito fácil com **Amplify AWS**.

Levando em consideraço que o seu código fonte está publicado em algum dos repositórios suportados (GitHub, Bitbucket, GitLab, 
AWS CodeCommit), basta seguir a orientação de CD do App [Aqui](https://console.aws.amazon.com/amplify/) (necessário registrar conta na AWS).

<br>

## Elastic Beanstalk
#### Implantar qualquer aplicativos .NET, Go, Java, Node, PHP, Python, Ruby ou em container Docker

<br>

## Elastic Compute Cloud (EC2)
É o serviço da AWS responsável por gerenciar e escalar aplicações criadas através do **Elastic Beanstalk**.  
Ele cria novas instancias de servidores caso necessário.

<br>

## Simple Storage Service (S3)
É um serviço de armazenamento de objetos. Um repositório em nuvem.
O S3 também é utilizado ao se criar um serviço de app **Elastic Beanstalk**, uma vez que precisamos subir o código fonte ou docker image para a AWS, e são nestes repositórios S3 que esses arquivos são armazenados.

## Route 53
É um serviço de registro de Domínios e configuração de DNS da AWS.

## Elastic Container Registry
Repositório de imagens Docker da AWS, semelhante ao Docker-HUB

## Elastic MapReduce (Amazon EMR)
Serviço de gerenciamento de Clusters para computação de Big Data.
