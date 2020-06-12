# Zygo Kotlin Challenge

Desafio de Kotlin usado nos processos seletivos da Zygo.

## Instruções gerais

- O desafio deve ser entregue em no máximo 2 horas após o recebimento do mesmo
- Deve ser utilizada a linguagem kotlin
- Código da solução final deve ser mandado por email, podendo mandar somente o código da função em si, sem os testes incluídos nesse repositório.
- A solução deve satisfazer todos os testes incluídos aqui no repositório, e ser o mais otimizada que o candidato conseguir chegar.

# Desafio

## Sum zero

### Instruções

Dado uma lista ordenada de inteiros, implementar uma função que encontra o primeiro par onde a soma é igual a 0. Retornar o par incluindo os dois valores da lista que somam 0, ou retornar nulo caso não exista nenhum par que satisfaça a condição.

[Puzzle](SumZero.kt)

### Exemplos

```
sumZero(listOf(1, 2)) // null

sumZero(listOf(-3, -2, 0, 1, 2)) // Pair(-2, 2)
```
