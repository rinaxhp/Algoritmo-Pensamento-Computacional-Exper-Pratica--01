# Monitoramento da Cesta Básica

Projeto desenvolvido para realizar o monitoramento dos preços de produtos da cesta básica.

## Objetivo

O algoritmo recebe os dados de três produtos, compara o preço do mês anterior com o preço atual e calcula a variação percentual.

Após o cálculo, o sistema classifica a situação do produto como:

- AUMENTO ABUSIVO
- AUMENTO
- QUEDA
- ESTÁVEL

## Funcionamento

Para cada um dos três produtos, o sistema solicita:

1. Nome do produto;
2. Preço do mês anterior;
3. Preço do mês atual.

Em seguida, calcula a variação percentual utilizando a fórmula:

```text
variacao = ((preco_atual - preco_anterior) / preco_anterior) * 100
