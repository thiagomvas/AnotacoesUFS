#PF
Imutabilidade se refere à propriedade de um objeto ou estrutura de dados que mantem seu estado sem permitir que seja modificado como resultado de alguma ação por parte de expressões ou funções. Isso protege o código de alterações indesejadas ou que passaram despercebidas causando efeitos colaterais.

Um exemplo de dado mutável são ``arrays``.

```js
// Exemplo do modulo 4
// Elementos da lista são mutáveis, apesar do uso do const
const lista1 = [3, 1, 7, 9, 4, 6]
console.log(`Mutavel lista: ${lista1}`)

const lista2 = lista1.sort((a,b)=>a-b)
console.log(`lista (ordenada): ${lista2}`)

console.log(`lista (original): ${lista1}`)

// Corrigindo com cópia do elemento
const lista3 = [3, 1, 7, 9, 4, 6]
console.log(`Imutavel lista: ${lista3}`)

const lista4 = [...lista3].sort((a,b)=>a-b)
console.log(`lista ordenada: ${lista4}`)

console.log(`lista (original): ${lista3}`)
```

**OBS: Operações com `map`, `filter ` e `reduce` não causam problemas com o princípio da Imutabilidade pois essas operações geram cópias da lista original como resultado.**