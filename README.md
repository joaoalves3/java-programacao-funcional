# Programação Funcional em Java

Exercícios de **programação funcional** com Java: Streams, expressões lambda, `Predicate` e `record`. Desenvolvidos no curso de Sistemas de Informação da **FIAP**.

## Exercícios

| Pasta | O que faz | Conceitos |
| --- | --- | --- |
| `exercicios01` | Filtra os nomes que começam com "A" e coloca em maiúsculas | `filter`, `map`, `toList` |
| `exercicios02` | Reajusta salários: 20% para quem tem 5 anos ou mais de experiência, 10% para os demais, em ordem alfabética | `map`, `sorted`, `Comparator`, `record` |
| `exercicios03` | Lista eletrônicos acima de R$ 1.000 com 10% de desconto | `filter`, `map`, `String.format` |
| `exercicios04` | Filtra produtos em estoque e bem avaliados, aplica desconto por categoria, agrupa por categoria e mostra os 2 mais caros | `Predicate`, `groupingBy`, `sorted`, `limit` |

## Tecnologias

- Java 25 (usa o `main` simplificado, sem `public` e sem `String[] args`)
- IntelliJ IDEA

## Como rodar

Abra a pasta no IntelliJ e rode a classe `ExercicioXX` que quiser.
