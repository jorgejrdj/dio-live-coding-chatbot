<p align="center">
    <a href="https://github.com/jorgejrdj"><img src="https://i.ibb.co/XjZXHLj/logo-sm-white.png" alt="logo-sm-white" border="0" style="zoom:50%;" alt="Digital Innovation One"></a> </p>

# Construindo um ChatbotFit no Telegram com JavaScript e NodeJS

## Chatbot para recomendação de de exercícios físicos realizado durante *Lab* na Digital Innovation One

Nesse *Lab* aprendi a desenvolver um projeto, ao qual apliquei conceitos de integração e buscas de vídeos de exercícios físicos no YouTube utilizando uma plataforma de entendimento de linguagem natural chamada DialogFlow. 

Nesse projeto, oferecido como desafio de *Bootcamp* promovida pela [Digital Innovation One](https://web.digitalinnovation.one/), pude aprender:

- Utilização da Linguagem NodeJs;
- Integração com Telegram API;
- Treinamento do Bot;
- Integração com Youtube API;
- Utilização de Linguagem Natural DialogFlow;

<p align="center">Este projeto será aprimorado em breve. Clique em "star" para acompanhar.</p>

<br />

<br />

## :information_source: Sobre a Configuração do DialogFlow

Para obter seu arquivo de configuração do DialogFlow:

Acesse: https://dialogflow.cloud.google.com/;

Faça o login com uma conta google;

Opcional: Leia sobre os termos de serviço do Google;

1. Crie um novo agente;
2. Na criação do novo agente, selecione a lingua a ser tratada e crie um novo projeto;
3. Com o agente criado, clique na engrenagem para acessar as configurações do agente;
4. Na página geral, clique no link do service accout. Se ele não existir, clique no botão atualizar no final da caixa;
5. Na nova página aberta, clique no E-mail correspondente a service account;
6. Vá até a parte de chaves, e clique em adicionar nova chave, do tipo JSON;
7. O site irá gerar um pop-up com o download da chave gerada, salve o arquivo na pasta do projeto;
8. Copie o conteúdo do arquivo baixado para o arquivo "configs-dialogflow.json" ou preencha os campos do arquivo manualmente.

Para aprender a gerar sua chave da API do YouTube, acesse:
https://developers.google.com/youtube/v3/quickstart/nodejs

Para maiores informações sobre a criação de credenciais, acesse:

1. [Youtube](https://console.developers.google.com/start/api?id=youtube)
2. [Dialogflow](https://console.cloud.google.com/iam-admin/serviceaccounts) 

*Recordar que é necessário ir à conta de serviço criada pelo Dialogflow e gerar seu arquivo JSON com as credenciais*

<br />

<br />

## :information_source: Criação do Bot

	- Se inscreva no Telegram (Você pode usar o cliente web, desktop ou mobile)
	- Abra o aplicativo ou acesse o website
	- Pesquise por @BotFather e inicie a conversa
	- Envie o comanndo /newbot e execute as instruções
	- Armazene o token enviado pelo @BotFather (Vamos usá-lo no código)



## :information_source: Como Usar?

### Bibliotecas utilizadas no projeto

- [Buscas do Youtube](https://www.npmjs.com/package/youtube-node) 
- [Comunicação com o Dialogflow](https://www.npmjs.com/package/dialogflow) 
- [Comunicação com o Telegram](https://www.npmjs.com/package/node-telegram-bot-api)

Para clonar esta aplicação e rodar em sua máquina, será necessário possuir [Git](https://git-scm.com) e [nodeJs](https://nodejs.org/en/) instalado em seu computador. Além disso, para utilização da API, é necessário ter conta ativo no [Telegram](https://telegram.org/) e [Google](https://www.google.com/). 

Em seu terminal, digite:

<br />

```bash
# Para Clonar
$ git clone https://github.com/jorgejrdj/netflix-clone

# No Repositório
$ cd netflix-clone

# Após clonado, executar o comando
$ cd npm install

# Para rodar
$ cd npm start
```

<br />

<br />

###### Made with ♥ by Jorge de Souza :wave: [Get in touch!](https://www.linkedin.com/in/jorgejrdj/)

