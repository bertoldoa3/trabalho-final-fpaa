# 📘 Trabalho Final – Fundamentos de Projeto e Análise de Algoritmos (FPAA)

Este repositório contém a solução para o trabalho final da disciplina **Fundamentos de Projeto e Análise de Algoritmos (FPAA)**. O projeto tem como objetivo resolver um problema utilizando **programação dinâmica** e **backtracking**, aplicando os conceitos estudados em aula.

## Descrição da Solução

Este programa tem como objetivo encontrar **todas as subsequências comuns mais longas (LCS)** entre duas sequências de letras minúsculas. 
A solução combina **programação dinâmica** para construir a matriz de comparação entre as strings e **backtracking** para recuperar todas as LCS possíveis de forma eficiente.

A aplicação é feita em C#, via console, e permite processar múltiplos conjuntos de entrada.

## Perguntas

### 1. Como a programação dinâmica foi aplicada na solução?

A programação dinâmica é usada para construir uma **matriz 'dp[i][j]'**, onde cada célula armazena o **comprimento da maior subsequência comum** entre os prefixos 
's1[0..i-1]' e 's2[0..j-1]'.
Essa matriz é preenchida de forma **bottom-up**, utilizando a seguinte lógica:

- Se 's1[i-1] == s2[j-1]', então 'dp[i][j] = dp[i-1][j-1] + 1'.
- Caso contrário, 'dp[i][j] = max(dp[i-1][j], dp[i][j-1])'.

Esse processo permite **reaproveitar resultados anteriores**, evitando recomputações redundantes.


### 2. Por que o uso de backtracking é necessário neste problema?

_Resposta aqui._

---

### 3. Houve desafios na implementação? Quais? Como foram superados?

_Resposta aqui._

---

### 4. Qual é a complexidade da solução proposta?

#### a) Versão utilizando apenas programação dinâmica:

_Resposta aqui._

#### b) Versão que combina programação dinâmica com backtracking:

_Resposta aqui._

---

### 5. O que o grupo aprendeu ao resolver esse problema?

_Resposta aqui._
