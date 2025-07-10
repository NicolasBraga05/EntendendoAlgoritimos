# 📘 Entendendo Algoritmos

> Anotações e destaques pessoais do livro _Grokking Algorithms_ (Entendendo Algoritmos) de **Aditya Bhargava**.

Este repositório é uma coletânea dos principais conceitos apresentados no livro, com explicações claras e exemplos práticos. Ideal para revisão rápida ou como complemento ao estudo de algoritmos.  

---

## 🧠 Conteúdo

- [📏 Notação Big O](#-notação-big-o)
- [🔍 Busca Binária](#-busca-binária)
- [📦 Estruturas de Dados](#-estruturas-de-dados)
- [🔁 Recursão](#-recursão)
- [📊 Algoritmos de Ordenação](#-algoritmos-de-ordenação)
- [🧮 Programação Dinâmica](#-programação-dinâmica)
- [🕸️ Grafos e Caminhos](#-grafos-e-caminhos)
- [🧭 Algoritmos Gulosos](#-algoritmos-gulosos)
- [📚 Referências](#-referências)

---

## 📏 Notação Big O

A **notação Big O** descreve a eficiência de algoritmos em termos de tempo ou espaço.  
Ela nos ajuda a entender como o tempo de execução cresce conforme o tamanho da entrada aumenta.

> Exemplo: Um algoritmo de busca linear tem complexidade O(n), enquanto a busca binária tem O(log n).

---

## 🔍 Busca Binária

A busca binária é um algoritmo eficiente para encontrar um elemento em uma lista ordenada. Em vez de verificar item por item, ela reduz pela metade o espaço de busca a cada passo, tornando o processo muito mais rápido.

> Exemplo: Imagine uma lista com 100 nomes em ordem alfabética.
Se fizermos uma busca tradicional (linear), e o nome estiver no final da lista, poderíamos levar até 99 tentativas para encontrá-lo.
Já com a busca binária, começamos examinando o elemento do meio da lista.

Se for o nome desejado, terminamos.

Se não for, decidimos se buscamos na metade anterior (caso o nome seja "menor") ou na metade posterior (caso seja "maior").
Repetimos esse processo até encontrar o nome ou esgotar as possibilidades.

Com isso, em vez de até 99 comparações, no pior caso seriam apenas 7 (pois 
log
⁡
2
100
≈
6.64
log 
2
​
 100≈6.64).

---

## 📦 Estruturas de Dados

> *(Em construção)*

---

## 📚 Referências

- Livro: [_Grokking Algorithms_](https://www.manning.com/books/grokking-algorithms)
- Documentação complementar e artigos diversos sobre algoritmos

---

## 🚧 Em andamento...

Este repositório está em constante atualização à medida que avanço na leitura.  
Fique à vontade para acompanhar ou contribuir com sugestões!

