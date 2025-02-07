# Conjuntos Numéricos 📏

Este programa implementa conjuntos numéricos utilizando a classe `Conjunto`, permitindo a inserção e verificação de números pertencentes aos conjuntos dos **Naturais $\mathbb{N}$**, **Inteiros $\mathbb{Z}$** e **Racionais $\mathbb{Q}$**.

## 📌 Funcionalidades
- Criar conjuntos de números.
- Inserir elementos nos conjuntos.
- Verificar se um número pertence a um conjunto específico.
- Imprimir os conjuntos no formato adequado.

### Conjunto $\mathbb{N}$
$\mathbb{N}$ = {0, 1, 2, 3, 4, 5, ...}

A cardinalidade do conjunto dos números naturais é $\aleph_0$ (alef-zero), indicando que é um conjunto infinito contável.

#### Pertinência
$1 \in \mathbb{N}$  
$-20 \notin \mathbb{N}$

---

### Conjunto $\mathbb{Z}$
$\mathbb{Z}$ = {..., -3, -2, -1, 0, 1, 2, 3, ...}

A cardinalidade do conjunto dos números inteiros $\mathbb{Z}$ é $\aleph_0$, pois ele pode ser enumerado de forma bijetora com os números naturais.

#### Pertinência
$-3 \in \mathbb{Z}$  
$5.9 \notin \mathbb{Z}$

---

### Conjunto $\mathbb{Q}$
$\mathbb{Q}$ = {..., -3/2, -1, 0, 1/2, 2, 3.5, ...}

O conjunto dos números racionais $\mathbb{Q}$ tem cardinalidade $\aleph_0$, pois pode ser enumerado de forma bijetora com $\mathbb{N}$, apesar de parecer maior que $\mathbb{Z}.$

#### Pertinência
$0 \in \mathbb{Z}$  
$1.4142 \notin \mathbb{Z}$ ou $\sqrt{2}\notin \mathbb{Z}$$

---

### Saída
Números Naturais  
N = {0,1,2,3,4,5,...}  

N -> 1 | True  
N -> -5 | False  

Números Inteiros  
Z = {...,-3,-2,-1,0,1,2,3,...}  

Z -> -3 | True  
Z -> 5.9 | False  

Números Racionais  
Q = {...,-1.5,-1,0,0.5,2,3.5,...}  

Q -> 0 | True  
Q -> 1.4142 | False  
