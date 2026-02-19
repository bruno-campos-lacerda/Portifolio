# Portifolio

## Cronometro BandG

[![Acessar Projeto](https://img.shields.io/badge/Acessar%20Projeto-181717?style=for-the-badge&logo=github)](https://github.com/bruno-campos-lacerda/BandG/tree/master)
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

[![Acessar Projeto](https://img.shields.io/badge/Acessar%20Projeto-181717?style=for-the-badge&logo=github)](https://github.com/bruno-campos-lacerda/Comparador-de-imagens)
[![JAVA](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java)]()

> Projeto de Ciencias da Computacao no quarto periodo, realiza conexão com uma API publica e solicita fotos tiradas via satelite para que o usuario possa visualizar

### Objetivo do projeto
- Aprimorar habilidades com banco de dados e orientacao a objetos
- Criar uma conexão com uma API e realizar uma requisicao
- Trabalhar com armazenamento de imagens
- Trabalhar com algoritmos de ordenacao

![Comparador de imagens](images/CompMain.png)

### 📁 Estrutura do projeto

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
[![Acessar Projeto](https://img.shields.io/badge/Acessar%20Projeto-181717?style=for-the-badge&logo=github)](https://github.com/bruno-campos-lacerda/outer_space/tree/master)
[![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)]()

![Outer Space](images/OuterSpace_1.png)

> Projeto de grupo independente, feito com Unity, realizado durante a finalização do ensino médio. Conciste em um plataforma 2D de ação com sistema de gravidade e inimigos com comportamentos unicos

![Outer Space](images/OuterSpace_2.png)

> HUD, recebe atributos do personagem e traduz para uma interface, e possui botões funcionais para o mobile que permite o jogador de celular aproveitar a experiencia da mesma forma como os de computador. A HUD tem posição variada, que se adapta com a resolução da tela.

|  |  |
|--|--|
| ![Outer Space](images/OuterSpace_3.png) | ![Outer Space](images/OuterSpace_4.png) |
| ![Outer Space](images/OuterSpace_5.png) | ![Outer Space](images/OuterSpace_6.png) |
| ![Outer Space](images/OuterSpace_7.png) | ![Outer Space](images/OuterSpace_9.png) |

> Sistema de combate, com cada inimigo possuindo um comportamento próprio para lidar com o jogador, que também possui suas mêcanicas de combate que conversa com o sistema de estados do jogador.

|  |  |  |
|--|--|--|
| ![Outer Space](images/OuterSpace_8.png) | ![Outer Space](images/OuterSpace_10.png) | ![Outer Space](images/OuterSpace_11.png) |

> Sistema de movimentação simples, porém funcional, que se adapta com o ambiente, podendo mudar a grávidade para que fique centrada em um ponto, mantendo a jogabilidade, mas mudando a orientação

![Outer Space](images/OuterSpace_12.png)

> Fases que estão ligadas somente com a fase seguinte, formando um game loop 

[![Itch.io](https://img.shields.io/badge/Download%20do%20Jogo-%23FF0B34.svg?style=for-the-badge&logo=Itch.io&logoColor=white)](https://br-camp.itch.io/outer-space)

🔗 Página com dowload do projeto acima

## Castle Board

[![Acessar Projeto](https://img.shields.io/badge/Acessar%20Projeto-181717?style=for-the-badge&logo=github)](https://github.com/bruno-campos-lacerda/castle_board/tree/master)
[![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)]()

![Castle Board](images/CastleBoard_1.png)

> Projeto feito durante maratona de desenvolvimento de jogos(game jam) ao longo de 50 horas, com uma equipe indenpendente

<div>
    <img src="images/CastleBoard_2.png" width=45%>
    <img src="images/CastleBoard_3.png" width=45%>
</div>

> Para o confronto entre peças de xadrez com peças de damas, foi criado um grid isometrico onde o jogador deve posicionar suas peças estrategicamente para cobrir o espaço por onde ira passar as peças adversárias. O jogador tem um limite de peças, e auxilios visuais para ver onde está posicionando suas peças, e qual área está sendo coberta.

[![Itch.io](https://img.shields.io/badge/Download%20do%20Jogo-%23FF0B34.svg?style=for-the-badge&logo=Itch.io&logoColor=white)](https://agentetitan.itch.io/castle-board)

🔗 Página com dowload do projeto acima

## Macabra

[![Acessar projeto](https://img.shields.io/badge/Acessar%20projeto-181717?style=for-the-badge&logo=github)](https://github.com/bruno-campos-lacerda/Macabra/tree/master)
[![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)]()

![Macabra](images/Macabra_1.png)
![Macabra](images/Macabra_2.png)
![Macabra](images/Macabra_3.png)

> Projeto de game jam, feito durante 50 horas, com uma equipe indenpendente e mais madura

|  |  |
|--|--|
| ![Macabra](images/Macabra_4.png) | ![Macabra](images/Macabra_5.png) |
| ![Macabra](images/Macabra_6.png) | ![Macabra](images/Macabra_7.png) |

> Jogo de terror baseado em slender man, com um perseguidor que usa algoritmo path finder para se locomover pelo mapa, o jogador se movimenta livremente e pode agarrar itens, que tem sua posição ancorada com o do jogador caso coletadas. O progresso se dá pela coleta desses itens, que irá ativar o evento que possibilita prosseguir.

[![Itch.io](https://img.shields.io/badge/Download%20do%20Jogo-%23FF0B34.svg?style=for-the-badge&logo=Itch.io&logoColor=white)](https://pedrolimamedrado.itch.io/macabra)

🔗 Página com dowload do projeto acima

## Spiegel Wasser

## Dark Circles
- Em producao