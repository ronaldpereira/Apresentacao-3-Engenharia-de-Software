# Unit Test Quiz - Apresentação 4

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

- Iteração 4 (dias 46 a 60)
    - Categorização das perguntas em módulos
    - Tela inicial: apresentar lista de módulos de perguntas
    - Navegação entre questões
        - Botões: anterior, próxima, dicas
    - Destacar acertos e erros
    - Adicionar mais questões no jogo
    - Organização da equipe em times


## Projeto

### Visão

A visão desse trabalho é, em suma, a criação de um "jogo sério" na área de engenharia de software, de forma que ele possa ser utilizado como uma forma alternativa de estudo com a finalidade de estimular o aprendizado dos estudantes sobre os conceitos da área, mais especificamente sobre a área de testes unitários de software.


### Gestão de configuração

- Especificação dos casos de uso
- Versionamento com GitHub
- Controle de tarefas a cada iteração com ZenHub
- Testes de regressão

## Organização e Contribuições do grupo

- Dono do Produto: Vitor Menezello
- Mestre Scrum: Luiz Otávio
- Desenvolvedores:
    - Aspectos visuais:
        - Marina Moreira
        - Pedro Brum
        - Vitor Menezello
    - Busca de conteúdo:
        - Breno Rodrigues
        - Gabriel Oliveira
        - Ronald Pereira
    - Desenvolvimento:
        - Ivan Soares
        - Rafael Grandsire
        - Pedro Dalla
        - Luiz Otavio
    - Desenvolvimento do site:
        - Ronald Pereira

Nessa iteração, o time de conteúdo foi responsável por incluir mais questões no banco, revisar as quetões já presentes, e finalmente organizá-las em módulos. O time de aspectos visuais foi encarregado dos layouts, apresentação e página web. Por fim, o time de desenvolvimento foi incubido de desbloquear módulos avançados e realizar testes de software.


## Decisões da iteração

- Sistema sem servidor

A equipe concluiu que a presença de um servidor não beneficiaria o projeto, pois sua função no jogo não seria notável o suficiente para compensar o trabalho de implementá-lo.

- Melhoria na definição de subtarefas

- Revisão de conteúdo


## Desafios encontrados

- Banco de perguntas
    - Revisão e categorização
- Design das telas
    - Utilização da ferramenta Android Studio
- Versionamento do repositório de GitHub
- Coordenar membros do grupo


## Produto

Todo o código do produto será posteriormente disponibilizado (atualmente ele está sendo hospedado no GitHub em um repositório privado para evitar problemas de autoria e/ou possíveis interferências externas) nesse link:

[Unit Test Quiz](https://github.com/ronaldpereira/unit-test-quiz)
