# Portifolio

## Cronometro BandG

[![Acessar Projeto](https://img.shields.io/badge/Acessar%20Projeto-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/bruno-campos-lacerda/BandG/tree/master)
[![JAVA](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java)]()

>Projeto do terceiro periodo de Ciencias da Computacao, se trata de um sistema que registra equipes, membros e tempo de voltas em um banco de dados, tendo sua interface construida com a biblioteca AWT

### Objetivo do projeto
- Desenvolver habilidades de programação orientada a objetos
- Entender a plataforma GitHub para armazenamento e versionamento de projeto
- Desenvolver o uso e conexão com banco de dados
- Criar uma interface simples e intuitiva para o usuario final

![BandG](images/BandG.png)

### 📁Estrutura do projeto

```bash
BYG/
├── src/byg/
│   ├── AtualizadorTela.java # interface com atualizar tempo
│   ├── Cronometro.java # Interface para usuario
│   ├── TeamLogin.java # Objeto Equipe
│   └── Temporizador.java # Cronometro funcional
├── mysql-connector-j-9.3.0/
│   └── mysql-connector-j-9.3.0.jar # conetor com banco de dados
└── byg.sql # banco de dados
```

### ▶️ Como executar o programa
- Clonar repositorio e abrir no netBeans
- importar byg.sql
- Adicionar mysql-connector no Services/Databases e configurar conexao para byg
- executar Cronometro.java


## Comparador de imagens

[![Acessar Projeto](https://img.shields.io/badge/Acessar%20Projeto-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/bruno-campos-lacerda/Comparador-de-imagens)
[![JAVA](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java)]()

> Projeto de Ciencias da Computacao no quarto periodo, realiza conexão com uma API publica e solicita fotos tiradas via satelite para que o usuario possa visualizar

### Objetivo do projeto
- Aprimorar habilidades com banco de dados e orientacao a objetos
- Criar uma conexão com uma API e realizar uma requisicao
- Trabalhar com armazenamento de imagens
- Trabalhar com algoritmos de ordenacao

![Comparador de imagens](images/CompMain.png)

## 📁 Estrutura do projeto

```bash
Comparador-de-imagens/
├── Img/
│   ├── FundoLogin (2).jpg # Imagem de fundo
│   └── lightning_snake.png # Icone
├── Program/
│   ├── GetImages.form 
│   ├── GetImages.java # Programa principal
│   ├── Register.form 
│   ├── Register.java # Interface do login de usuario
│   ├── RegisterLogin.form
│   └── RegisterLogin.java # Interface do registro de usuario
├── dao/
│   ├── ConnectionDAO.java # Conexao com o banco de dados
│   ├── ImagesDAO.java # Armazena e le imagens no banco de dados
│   └── LoginUserDAO.java # Armazena e le usuarios no banco de dados
├── model/
│   ├── Images.java # Objeto imagens
│   └── LoginUser.java # Registro e login de usuarios
├── service/
│   └── GetImages.java # Faz a requisicao de imagens
├── jacson-core-2.20.0.jar # Suporte para arquivos Json
├── json-20240303.jar # Manipulacao de arquivos Json
├── loginuser_userpassword.sql # Banco de dados 
└── mysql-connector-java-8.0.18.jar # Mysql connector
```

### ▶️Como executar o progrma
- Clonar repositorio
- Criar pasta lib/ e adicionar arquivos .jar, e então ao classpath
- Importar, ou replicar, o banco de dados
- Configurar conexão com o banco de dados
- Executar o programa service/GetImages.java até ele finalizar
- Executar Program/GetImages.java

## Outer Space

## Castle Board

## Macabra

## Spiegel Wasser

## Dark Circles
- Em producao