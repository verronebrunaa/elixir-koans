# Listas em Elixir

## Inserção em Listas

Quando trabalhamos com listas em Elixir, a função `List.insert_at/3` tem um comportamento especial. Considere o seguinte exemplo:

```elixir
List.insert_at([1, 2, 3], 10, 4) == [1, 2, 3, 4]
```

### Comportamento

Quando tentamos inserir um elemento em uma posição que está fora dos limites da lista (como no caso da posição 10 em uma lista com apenas 3 elementos), o Elixir automaticamente adiciona o item ao final da lista, em vez de gerar um erro.

## Diferenças entre Listas e Tuplas

### Sintaxe
- Listas são delimitadas por colchetes `[]`
- Tuplas são delimitadas por chaves `{}`

Por exemplo:
```elixir
# Lista
[1, 2, 3]

# Tupla
{1, 2, 3}
```

-----------------------

# Lists in Elixir

## List Insertion

When working with lists in Elixir, the `List.insert_at/3` function has a special behavior. Consider the following example:

```elixir
List.insert_at([1, 2, 3], 10, 4) == [1, 2, 3, 4]
```

### Behavior

When we try to insert an element at a position that is outside the list boundaries (like position 10 in a list with only 3 elements), Elixir automatically adds the item to the end of the list instead of raising an error.

## Differences between Lists and Tuples

### Syntax
- Lists are enclosed with square brackets `[]`
- Tuples are enclosed with curly braces `{}`

For example:
```elixir
# List
[1, 2, 3]

# Tuple
{1, 2, 3}
```