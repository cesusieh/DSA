# Estrutura de dados e algoritmos

## Big O
É a métrica referente a escalabilidade de um algoritmo levando em consideração seu input.

- Complexidade temporal > Referente ao runtime de um algoritmo.
- Complexidade espacial > Referente a quantidade de memória de um algoritmo.
- - - 
## Principais notações
### O(1)
Tempo/memória constante. Independente do tamanho do input o algoritmo performa o mesmo tempo/memória.

**Exemplo:** Encontrado o primeiro elemento um array.

### O(Log N)
 Tempo/memória performam de maneira linear mesmo com seu input aumentando exponencialmente. 

**Exemplo:** Binary search.

### O(N)
Tempo/memória escalam junto com o tamanho do input.

**Exemplo:** Buscar todos os elemento de um array.

### O(N Log N)
O algoritmo lê o array O(N) e opera O(Log N) para cada valor. Algoritmos de Sorting e Divide and Conquer.

**Exemplo:** Quicksort, mergesort.

### O(N²)
Tempo/memória escalam de forma exponencial conforme o input.

**Exemplo:** Um loop aninhado.

- - -

## Estruturas de dados
### Array
Uma estrutura de dado que reversa um espaço contínuo na memória.

`const arr = new ArrayBuffer(8)` 

reserva 8 espaços sequenciais na memória para nosso array.

### Linked list
