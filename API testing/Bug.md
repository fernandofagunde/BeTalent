# Bug Report: Endpoint "Buscar Reservas por Nome"

## Descrição do Problema
O endpoint **"Buscar Reservas por Nome"** está retornando uma lista vazia mesmo quando existem reservas cadastradas no sistema que correspondem ao nome fornecido como parâmetro.

---

## Passos para Reproduzir o Problema
1. Certifique-se de que existem reservas cadastradas no sistema com o nome de teste.
2. Faça uma requisição para o endpoint **Buscar Reservas por Nome** usando o nome correspondente como parâmetro.
3. Observe que a resposta é uma lista vazia, mesmo que haja registros compatíveis.

---

## Comportamento Esperado
O endpoint deve retornar uma lista contendo as reservas cujo nome do cliente corresponda parcial ou totalmente ao nome fornecido.

---

## Comportamento Atual
O endpoint está retornando uma lista vazia, indicando que nenhum registro foi encontrado.


