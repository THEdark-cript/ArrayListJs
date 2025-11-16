# ArrayListJs
ESSE É UM TUTORIAL DE COMO MANIPULAR COLEÇÕES/LIST EM JS

---

## 🎯 Objetivo do Projeto
Ajudar vocês a compreender como manipular coleções de dados em JavaScript de forma simples e pratica.

---

## 📚 Conteúdo Teórico

### O que é um ArrayList?
Um ArrayList é uma estrutura de dados dinâmica usada principalmente em Java para armazenar coleções de elementos, semelhante a um array, mas com a vantagem de poder crescer ou diminuir de tamanho automaticamente.  
Em JavaScript, usamos arrays que já são dinâmicos:

```javascript
const lista = [10, 20, 30];
lista.push(40);
console.log(lista[0]);
lista.pop();
console.log(lista);
```
---
**OQUE E MAP🗺️ ?:**
---
O map percorre cada item de uma lista e cria uma nova lista transformada. Pense como: pegar cada elemento e mudar ele.
```
const numeros = [1, 2, 3];
const dobrados = numeros.map(n => n * 2);
console.log(dobrados); // [2, 4, 6]
```

---
**OQUE E FILTER🧹 ?:**
---
O filter percorre a lista e mantém apenas os elementos que passam em uma condição. Pense como: filtrar o que eu quero.
```
const numeros = [1, 2, 3, 4];
const pares = numeros.filter(n => n % 2 === 0);
console.log(pares); // [2, 4]
```
---
**OQUE E REDUCE➕ ?:**
---
O reduce pega todos os elementos da lista e reduz a um único valor (como somar tudo). Pense como: juntar tudo em um resultado só.
```
const numeros = [1, 2, 3];
const soma = numeros.reduce((acc, n) => acc + n, 0);
console.log(soma); // 6
```

---
##**📚CONTEUDO PRATICO**
---
---
**MAP🗺️**
---
```
const numeros = [1, 2, 3, 4];
const dobrados = numeros.map(num => num * 2);
console.log(dobrados);

```
---
**FILTER🧹**
---
```
const numeros = [1, 2, 3, 4, 5, 6];
const pares = numeros.filter(num => num % 2 === 0);
console.log(pares);

```

---
**REDUCE➕**
---
```
const numeros = [1, 2, 3, 4];
const soma = numeros.reduce((acumulador, num) => acumulador + num, 0);
console.log(soma);

```
---
**AUTOR**
--
**NOME:ANTHONY KISS**
--
**EMAIL:anthony.ryan@academico.ifpb.edu.br**





