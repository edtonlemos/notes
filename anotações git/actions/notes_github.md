#GIT E GITHUB ACTIONS

- Composto por 3 elementos
    * Fluxo de Trabalho (Workflows): verificar qualidade, automação de builds. 
        Ativado a partir de eventos: coisas que tocam objetos do repo ou eventos temporais.
    * Jobs: define o ambiente de execução (runner). deve ser em um ambiente gerenciável.
    * Passos (Steps): executa um script de linha de comando ou uma ação. 

- Vinculado a um repositório de código. Cria 1 ou mais workflows, cada workflow possui 1 ou mais jobs, cada job tem 1 ou mais passos.

- O workflow é um código em uma linguagem de marcação .yml e criado em um repositório específico. 