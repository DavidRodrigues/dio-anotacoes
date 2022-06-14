
# Posicionando Elementos com Flexbox em CSS

## Flexbox

Propriedades do CSS que tem como intuito permitir a criação de um modelo de layout unidimensional, possibilitando oferecer distribuição de espaço entre itens em uma interface e recurso de alinhamentos.

## Principais Comandos

| Comandos       | Descrição                                                                                              |
|----------------|--------------------------------------------------------------------------------------------------------|
| flex-container | Tag que envolve os itens. Tag que recebe a propriedade `display: flex`                                 |
| flex-items     | Elementos filhos diretos do flex-container.<br/><sub>(Os filhos também podem ser flex-container)</sub> |

### Propriedades relacionadas ao Flex Container

| Comandos           | Descrição                                                                                          |
|--------------------|----------------------------------------------------------------------------------------------------|
| display            | Inicializador do flex-container                                                                    |
| flex-direction     | Define o direcionamento `[row | column]` do item dentro do flex-container                          |
| flex-wrap          | Define a quebra de linha dos itens distribuidos dentro do flex-container                           |
| flex-flow          | Abreviação para as propriedades flex-direction e flex-wrap                                         |
| justify-content    | Alinha os itens do flex-container de acordo com a direção                                          |
| align-items        | Alinha os itens do flex-container de acordo com o eixo do container                                |
| align-content      | Alinha as linhas do flex-container                                                                 |

### Propriedades relacionadas ao Flex Item

| Comandos           | Descrição                                                                                          |
|--------------------|----------------------------------------------------------------------------------------------------|
| flex-grow          | Define o fator de crescimento do elemento                                                          |
| flex-basis         | Define o tamanho inicial do elemento antes da distribuição no flex-container                       |
| flex-shrink        | Define a capacidade de redução do elemento                                                         |
| flex               | Abreviação para as propriedades flex-grow, flex-basis e flex-shrink                                |
| order              | Ordem de distribuição e listagem dos itens dentro do flex-container                                |
| align-self         | Define o alinhamento de um item específico dentro do flex-container                                |



[Voltar ao Índice](https://github.com/DavidRodrigues/dio-anotacoes)
