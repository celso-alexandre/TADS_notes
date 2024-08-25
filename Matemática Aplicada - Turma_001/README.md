# Conjuntos/Sets
Sets are labeled using Latin single capitalized letter, eg.: A, B, C  
set values are defined using: 
- Citação (extensão) dos elementos: `M = { value1, value2 }`  
- Por propriedade comum: `M = {x|x é nota musical}`
- Por diagramas. Eg.: Diagrama de Venn-Euler

## Relações
### Pertencimento
Indica se um elemento pertence ou não à um conjunto

Pertence ao conjunto: ∈
Não pertence: ∉

Conjunto de vogais: `A = { a, e, i, o, u }`  

- A letra i pertence ao conjunto A: que é formado pelas vogais do alfabeto latino: ou seja: i ∈ A  
- A letra f não pertence ao conjunto A, ou seja: f ∉ A

## Inclusão
Indica de um conjunto se relaciona (inclui/não inclui) em relação à outro conjunto
![alt text](image.png)  
- `A ⊆ B ⇔ (∀x) [x ∈ A → x ∈ B]`
  - A ⊆ B: Set A is a subset of set B, meaning every element of A is also an element of B.
  - ⇔: If and only if.
  - ∀x: For all x (universal quantifier).
  - x ∈ A: x is an element of A.
  - →: Implies.
  - x ∈ B: x is an element of B.

- `B = { 0,1,2,3,4,5,6,7,8,9 }` and `A = { 1,3,5,7,9 }`
   - `A ⊆ B`: Whatever be elemento de A, também pertence à B

## Disjuntos (inner join without a match lol)
Não é elementos em comum entre ambos conjuntos  
![alt text](image-2.png)

## Operação entre conjuntos
### União (full outer join / union)
Agrega os elementos de ambos conjuntos  
![alt text](image-1.png)
- `A = {a, b, c, d}` and `B = {d, f}`
   - A ∪ B = {a, b, c, d, f}

### Intersecção (inner join)
Indica que parte dos elementos existe em ambos conjuntos
![alt text](image-3.png)  
intersecção encontrada no elemento d: {a,b,c,d} ∩ {d,e} = {d}
intersecção conjunto vazio: {1,2} ∩ {3,8} = {0} ou ∅  

### Diferença entre conjuntos (Complementar)
Complementar indica os elementos que não intercedem entre dois conjuntos  
![alt text](image-4.png)  
`A={2,4,6,8}` and `C={4,5,6,7}`
`A{2,*4*,*6*,8}-C{*4*,5,*6*,7} = {2,8}`
`C{*4*,5,*6*,7}-A{2,*4*,*6*,8} = {5,7}`

Complementar  
![alt text](image-5.png)

## Intervalos
### Intervalo Fechado
1......2  
`[a,b] = {X ∈ R | a ≲ x ≳ b}`  
X pertence aos números Reais, onde x <= a e x >= b (between inclusive)
Nesse caso, inclui todos números entre a e b, incluindo a e b

### Intervalo Aberto
`(a,b) = {X ∈ R | a < x < b}`  
X pertence aos números Reais, onde x > a e x < b (between exclusive)
Nesse caso, inclui todos números entre a e b, exceto a e b

### Intervalo Misto
![](image-6.png)  
Eu acho que tem um typo aqui... deve ser (a,b] para o segundo, ou esse tipo de notação é bem relaxada e tem sinônimos
