# Árvores BST – Inserção e Remoção (Java)

Este projeto apresenta uma implementação simples de uma **Árvore Binária de Busca (BST)** em Java, contendo as operações principais:

- Inserção de nós
- Remoção de nós (3 casos: nó folha, nó com 1 filho e nó com 2 filhos)
- Impressão da árvore em ordem (in-order)

O código foi feito de forma didática, com comentários para facilitar o entendimento, ideal para quem está estudando árvores binárias.

---

## Conteúdo Explicado no Vídeo

No vídeo, são explicados:

### ✔ O que é uma BST
- Estrutura de árvore onde cada nó tem até dois filhos.
- Valores menores ficam à esquerda, valores maiores à direita.

### ✔ Inserção
- O algoritmo desce pela árvore comparando valores.
- Quando encontra um espaço vazio, insere o novo nó.

### ✔ Remoção
A remoção trata três situações:

1. **Nó sem filhos** → remove direto  
2. **Nó com 1 filho** → substitui pelo filho  
3. **Nó com 2 filhos** → encontra o sucessor, copia o valor e remove o sucessor

---


---
# ▶ COMO EXECUTAR O CÓDIGO
## Código (Main.java)

> O código deve ser salvo em um arquivo chamado **Main.java**

Este arquivo contém:
- Classe `Node`  
- Classe `BST`  
- Classe `Main` para testar  

---
## Verificar se o Java está instalado

Abra o terminal/cmd e execute:

```bash
java -version


