# Zygo Kotlin Challenge

Desafio de Kotlin usado nos processos seletivos da Zygo.

## Instruções gerais

- O desafio deve ser entregue em no máximo 2 horas após o recebimento do mesmo
- Deve ser utilizada a linguagem kotlin
- Código da solução final deve ser mandado por email.
- A solução deve satisfazer todos os testes descritos abaixo, e ser o mais otimizada que o candidato conseguir chegar.

## O que será avaliado

- Legibilidade do código
- Otimização e complexidade do algoritmo
- [Bônus] Testes automatizados para o algoritmo

# Desafio

## Sum zero

### Instruções

Dado uma lista ordenada de inteiros distintos, implementar uma função que encontra o primeiro par onde a soma é igual a 0. Retornar o par incluindo os dois valores da lista que somam 0, ou retornar nulo caso não exista nenhum par que satisfaça a condição.

### Exemplos

```
sumZero(listOf(1, 2)) // null

sumZero(listOf(-3, -2, 0, 1, 2)) // Pair(-2, 2)
```

### Inputs de testes e retornos esperados

- Input: lista vazia / Retorno: null
- Input: 1, 2 / Retorno: null
- Input: 1, 2, 4, 7 / Retorno: null
- Input: -4, -3, -2, 1, 2, 3, 5 / Retorno: -3, 3
- Input: -4, -3, -2, 1, 2, 5 / Retorno: -2, 2
