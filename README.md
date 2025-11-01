# 🏅 Notas dos Atletas

Este projeto tem como objetivo calcular a **média válida** das notas obtidas por cada atleta em uma competição.  
A ideia é: Cada atleta recebe cinco notas dos juízes, e a maior e a menor nota são desconsideradas antes de calcular a média.

---

## 📋 Como funciona

O código percorre uma lista de atletas, onde cada um possui um nome e um conjunto de notas.  
Para cada atleta, são realizadas as seguintes etapas:

1. **Ordenação das notas**  
   As notas são organizadas em ordem decrescente (da maior para a menor) para facilitar a remoção dos extremos.

2. **Eliminação da maior e da menor nota**  
   Após ordenar, a primeira e a última nota são removidas.  
   Exemplo: `[10, 9.34, 8.42, 10, 7.88]` → notas válidas: `[10, 9.34, 8.42]`

3. **Cálculo da média**  
   As notas restantes são somadas e divididas pela quantidade de notas válidas.

4. **Exibição dos resultados**  
   O nome do atleta, suas notas originais e a média válida são exibidos no console.

---

## 🧠 O que eu aprendi

Durante o desenvolvimento deste projeto, pude praticar:

- Uso de **loops** (`for`) para percorrer arrays;  
- Manipulação de **arrays** com métodos como `.sort()`, `.slice()` e `.reduce()`;  
- Organização e exibição de informações no **console**;  
- Entendimento da **lógica de cálculo de médias**, removendo valores extremos.

---

## 🚀 Como executar

1. Copie o código para um arquivo chamado `notas-atletas.js`;  
2. Execute o arquivo com o Node.js:

```bash
node notas-atletas.js
