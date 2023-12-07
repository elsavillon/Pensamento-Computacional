# Pensamento-Computacional
Projeto criado para a discicplina de Pensamento Computacional, ministrada por Guilherme Felitti pelo curso de Jornalismo de Dados, Automação e Data Storytelling pelo Insper. Turma de 2024.

## Proposta:
Criar uma função que desse acesso a todas as páginas de despesas dos deputados federais pela API da Camara dos Deputados com base no ID e Legislatura.

## Bibliotecas utilizadas:
- Requests;
- Pandas;
- Json.

## Resultados propostos para o exercício:
Foram selecionados os quatro deputados fedderais eleitos mais votados em São Paulo no ano de 2022. São eles: Guilherme Boulos (PSOL); Carla Zambelli (PL), Eduardo Bolsonaro (PL) e Ricardo Salles (PL).

## Metodologia:
Para acessar as páginas de despesas, com base na função criada, é necessária a requisição do ID do candidato pela API. Com base na pesquisa do nome e sobrenome, é possível descobrir o ID e legislatura e trocar as informações dentro da função para obter os resultados.
Na sequência, foi desenvolvido um DataFrame com a relação de despesas obtidas e exportada numa planilha em formato CSV.

## Replicação:
Ambas requisições funcionam com qualquer candidato e em qualquer legislatura, basta trocar os valores das variáveis, sem alteração de parâmetros.

Desenvolvido por: Elsa Villon, dezembro/2023.
