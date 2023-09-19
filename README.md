# Projeto em MongoDB

Este é um repositório que contém um Docker Compose file e um conjunto de scripts para criar e configurar um ambiente MongoDB para desenvolvimento local.

## O que este projeto faz

Este projeto tem como objetivo simplificar a configuração de um ambiente de desenvolvimento MongoDB local. Ele cria um contêiner Docker com o MongoDB e configura um banco de dados com um usuário com permissões de leitura e gravação.

## Como usar

Siga estas etapas para configurar e executar o ambiente:

1. Clone este repositório para o seu sistema:

   ```bash
   git clone https://github.com/seu-usuario/meu-projeto-mongodb.git

## Navegue até o diretório do projeto:

cd meu-projeto-mongodb

## Crie um arquivo .env no diretório raiz do projeto para definir as variáveis de ambiente necessárias:

cp example.env .env

## Abra o arquivo .env e defina os valores apropriados para MONGO_INITDB_ROOT_USERNAME, MONGO_INITDB_ROOT_PASSWORD e MONGO_INITDB_ROOT_DATABASE.
## Inicie o ambiente MongoDB usando o Docker Compose:

docker-compose up -d

## Após a inicialização bem-sucedida, você pode usar o mongo shell para se conectar ao banco de dados:

mongo

 Agora você pode executar consultas, inserções e outras operações no MongoDB.

## Quando você terminar de usar o ambiente, você pode parar e remover os contêineres usando:

 docker-compose down

## Configurações personalizadas
Você pode personalizar as configurações do ambiente MongoDB no arquivo docker-compose.yml. Por exemplo, você pode alterar a porta de exposição ou o volume de armazenamento.


