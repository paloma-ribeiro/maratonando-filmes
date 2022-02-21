# Maratonando Filmes

### Desafio realizado na plataforma [HackerRank](https://www.hackerrank.com/).

### **Versão Python:** 2.7

## Descrição
#### Uma amiga da Alex deu uma coleção de filmes para ela de presente, e Alex está animada para assistir todos eles o mais rápido possível.
#### A duração dos filmes é dada em um vetor duracoes[n], onde n é o número do filme, e cada filme dura entre 1.01 e 3.00 horas (até duas casas decimais).
#### Alex quer gastar no máximo 3.00 horas assistindo filmes por dia, mas também quer assistir a coleção completa no mínimo número de dias possível.
#### Alex nunca para de assistir um filme na metade. Isso é, se Alex escolheu um filme, assite ele por completo no mesmo dia.
#### Ache o número mínimo de dias necessários para assistir a coleção de filme completa.
### Exemplo:
#### n = 5
#### duracoes = [1.90, 1.04, 1.25, 2.5, 1.75]
#### Considerando um passo a passo de 1 em 1, Alex consegue assistir os filmes em um mínimo de 3 dias:
* Dia 1: primeiro e segundo filmes: 1.90 + 1.04 = 2.94 <= 3
* Dia 2: quarto filme: 2.5 <= 3.00
* Dia 3: terceiro e quinto filmes: 1.25 + 1.75 = 3.00 <= 3.00
#### Descrição da Função:
* Complete a função acharMinimoDeDias, que possui o parâmetro: float duracoes[n]: a duração de cada filme.
* Retorna int: o mínimo de número de dias necessário para assistir todos os filmes.
#### Restrições
* 1 <= n <= 1000
* 1.01 <= durancoes[n] <= 3.0