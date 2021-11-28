# Assignment 20 - DEX - DNC

# 1. Contextualizado o Problema

## 1.1 Contexto Geral

- O CEO da Amazon contratou um time de cientistas de dados para trabalhar em diferentes vertentes da empresa, e você ficou encarregado de fazer um sistema de recomendação para os clientes Amazon. Para isso, te deram acesso à uma base de dados não muito estruturada em Json: um arquivo de metadata com informações dos produtos e outro com as avaliações.

- O CEO deseja que seu algoritmo de recomendação seja exclusivamente em cima de avaliações verificadas (campo `verified`=True no arquivo de avaliações). Contudo, há uma base sem classificação e que o CEO faz questão de que seja
adicionada no sistema de recomendação (valores com missing value na coluna `verified`). 

- Para isso, você precisará classificar se estas avaliações são verificadas ou não, e no caso positivo, adicioná-los no sistema de recomendação.

- Adicionalmente, o CEO tam bém deseja saber de possíveis associações e/ou correlações nesta base de dados que você vai trabalhar.

## 1.2 Objetivos

- Carregar, limpar e fazer análises exploratórias no banco de dados fornecido;

- Classificar a base sem informação para incluir as observações das avaliações verificadas no sistema de recomendação;

- Desenvolver e entregar um sistema de recomendação, com exemplos de aplicação.

- O desenvolvimento e a decisão do modelo é totalmente sua, portanto se achar que deve utilizar um valor/ procedimento diferente, sinta-se livre para fazer os testes e validar suas hipóteses para achar o resultado coerente.

- LIMPEZA DOS DADOS: Aqui você deve limpar e explorar os dados para decidir variáveis que possam ser úteis para classificação de avaliações verificadas. Você também deve levantar associações e/ou correlação para apresentar ao CEO


- EDA Realize uma EDA da forma como preferir, explore os dados, levante ideias, avalie correlações.

  - 1° ETAPA CLASSIFICAÇÃO: Aqui você deve utilizar as variáveis estudadas na primeira parte para classificar as avaliações sem label. Deve-se avaliar os modelos criados, tunar ao menos um modelo selecionado e utilizá-lo na classificação. Após classificação, não se esqueça de remover as avaliações
não verificadas.

  - 2° ETAPA RECOMENDAÇÃO: Aqui você deve desenvolver um sistema de recomendação e mostrá-lo na prática para o CEO. Tente prever possíveis erros
para evitá-los de antemão. Por exemplo, caso o produto requisitado não esteja na matriz/base, aponte os 10 mais vendidos.
