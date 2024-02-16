# Projeto 1 de Programação e Sistemas de Informação

Objetivo: Criar um **Jogo do Galo** como aplicação de consola em C#.

## Passo 1: Jogo do Galo funcional (10v)

- Jogo deve ser **PvP** (2 jogadores)
- Programa deve iniciar num menu principal com as seguintes opções:
  1. Jogar (Inicia o jogo)
  2. Estatísticas (Mostra um ecrã com várias estatísticas)
  3. Sair (Termina a aplicação)
- Após selecionar a opção "Jogar", e em cada ciclo do jogo, devem estar presentes os seguintes elementos:
  1. Um tabuleiro de 3x3 colunas, atualizado em cada ciclo com as jogadas executadas
  2. Uma mensagem a pedir ao jogador atual para efetuar uma jogada

## Passo 2: Seguir o padrão MVC (5v)

- Preferível seguir este padrão desde o início do desenvolvimento do projeto
- Resolver o exercício 4 da aula 10 para praticar

## Passo 3: Estatísticas e tratamento de erros (5v)

- Quando o programa é corrido pela primeira vez, deve ser criado um ficheiro de texto com algumas estatísticas do jogo:
  1. Nº de vitórias de cada jogador
  3. Nº total de jogadas efetuadas por cada jogador
  4. Nº de vezes em que o tabuleiro foi completamente preenchido
- No fim de cada jogo, este ficheiro deve ser atualizado com o resultado
- Sempre que o programa é reaberto, as informações deste ficheiro devem ser lidas.
- Deve ser realizado o tratamento adequado de erros possíveis na leitura/escrita de ficheiros

## Passo 4: Diagrama UML e relatório (5v)

- UML completo (classes com variáveis de instância, propriedades e métodos)
- Relatório deve conter o diagrama, assim como *links* para referências usadas

## Entrega

- Repositório no GitHub
  - Meter link na tabela 'Entrega de fichas / projetos' na pasta de PSI
- Conteúdo:
  - Ficheiro .gitignore
  - Pasta com ficheiros do projeto
  - Ficheiro README.md com identificação dos alunos e relatório
  - Imagem com diagrama UML do projeto
- Data limite: 23/02/2024
