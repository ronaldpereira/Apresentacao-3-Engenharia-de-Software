# Unit Test Quiz - Apresentação 3

# Unit Test Quiz - Apresentação 3

# O que é o CMMI

O CMMI (Capability Maturity Model Integration ou Modelo Integrado de Maturidade em Capacitação) trata-se de um modelo (atualmente na versão 1.3), com um enfoque voltado para a medição da capacidade de maturidade de processos de software.

Um processo representa, dentro da área de software, um conjunto de atividades cujo objetivo é atingir uma meta previamente estipulada. Já por capacidade e maturidade de um processo, deve-se ter a noção do grau de qualidade com o qual um processo atinge um resultado esperado.

Ao todo, são 5 níveis de maturidade que atestam, por sua vez, o grau de evolução que uma organização se encontra num determinado momento. O objetivo maior, considerando o CMMI e seus diferentes conceitos, está justamente na produção de software com maior qualidade e menos propenso a erros.

Porém, nessa apresentação, iremos tratar mais especificamente de somente um dos níveis de maturidade.

# Nível 2 de Maturidade - Gerenciado / Gerido

O nível 2 de maturidade do CMMI é definido ,principalmente, pelo gerenciamento dos requisitos de seus projetos, bem como o planejamento, a medição e o controle dos diferentes processos envolvendo o desenvolvimento de um software. Basicamente, ele é sobre planejar a execução e confrontar o executado contra o que foi planejado inicialmente.

Entre abril de 2002 e junho de 2006 foram conduzidas 1581 avaliações em 1337 organizações.

- 18,2%: nível 5 (Em otimização)
- 4,4%: nível 4 (Quantitativamente gerenciado / Gerido quantitativamente)
- 33,8%: nível 3 (Definido)
- **33,3%: nível 2 (Gerenciado / Gerido)**
- 1,9%: nível 1 (Inicial / Ad-hoc)
- 8,4%: sem qualificação (Não fornecido)

# Processo

## Requisitos

### Reserva de Requisitos

- Tela inicial
    - Design da tela
- Lista de tópicos disponíveis no aplicativo
- Estatísticas do jogo
    - Performance ao final de cada jogo
- Desbloquear módulos de atividades mais avançados
- Melhorar interface visual
- Implementar fluxos para todos casos de uso
- Estatísticas de jogo


### Requisitos das iterações

- Iteração 1 (dias 1 a 15)
    - Criação do banco de questões
        - Foi desenvolvido um Crawler para encontrar essas respostas automaticamente de forma automática e rápida
    - Implementação utilizando _parser_ para carregamento dos arquivos e construção de objetos de transferência de dados


- Iteração 2 (dias 16 a 30)
    - Implementação inicial do aplicativo
        - Jogo em processo
            - Desenvolvimento das questões
            - Interação com o usuário

- Iteração 3 (dias 31 a 45)
    - Tela inicial
        - Lista de seções de conteúdo
    - Tela de questão
        - Navegação entre as questões
        - Exibir o número de questões respondidas corretamente
        - Progresso por atividades
            - Ícone de progresso ao lado de cada atividade
        - Mudar questão para questão não respondida após acerto
        - Indicar se questão já foi respondida corretamente (dando highlight na resposta)


## Projeto

### Visão

A visão desse trabalho é, em suma, a criação de um "jogo sério" na área de engenharia de software, de forma que ele possa ser utilizado como uma forma alternativa de estudo com a finalidade de estimular o aprendizado dos estudantes sobre os conceitos da área, mais especificamente sobre a área de testes unitários de software.

### Próximas iterações

Nas próximas iterações vamos trabalhar na tela inicial, acrescentando uma lista com ranking das maiores pontuações. Além disso, vamos desenvolver a tela de questão, implementando a progressão para uma questão ainda não respondida após um acerto, e indicar se uma questão já foi respondida corretamente.


### Gestão de configuração

- Aprimoramento do banco de questões
- Criação do modelo de jogo em progresso
- Implementar funcionalidades do jogo

## Organização e Contribuições do grupo

- Dono do Produto: Vitor Menezello
- Mestre Scrum: Luiz Otávio
- Desenvolvedores:
    - Desenvolvimento do aplicativo:
        - Breno Rodrigues
        - Gabriel Oliveira
        - Ivan Soares
        - Marina Moreira
        - Pedro Brum
        - Rafael Grandsire
        - Ronald Pereira
    - Busca de conteúdo:
        - Breno Rodrigues
        - Gabriel Oliveira
        - Ronald Pereira
    - Desenvolvimento da base de dados:
        - Pedro Dalla
    - Desenvolvimento do site:
        - Ronald Pereira

## Decisões da iteração

- Aproximar o conceito do jogo à ideia do Duolingo

À medida que o projeto progrediu, dada a proximidade do jogo desenvolvido com o aplicativo Duolingo, decidimos aproximar ainda mais os requisitos finais à interface do Duolingo, visto que este é uma ferramenta de ensino muito bem sucedida.

- Adicionar explicações

Além de responder às questões, o jogador terá acesso a um "tutorial", algumas dicas e notas a respeito do conteúdo que o ajudarão a progredir e conseguir mais acertos no jogo.

- Adicionar sistema de pontuação

- Separar as questões por módulos

- Indicar progresso em cada módulo através da pontuação


## Desafios encontrados

- Banco de perguntas
    - selecionar as questões mais relevantes para cada um dos módulos
        - Conceitos Gerais
        - Testes

- Desenvolvimento para Android
    - Utilização da ferramenta Android Studio
    - Implementação de funcionalidades no jogo

- Coordenar membros do grupo


## Produto

Todo o código do produto será posteriormente disponibilizado (atualmente ele está sendo hospedado no GitHub em um repositório privado para evitar problemas de autoria e/ou possíveis interferências externas) nesse link:

[Unit Test Quiz](https://github.com/ronaldpereira/unit-test-quiz)
