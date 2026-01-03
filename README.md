# Planejamento de Experimentos (CE213) - UFPR

Este repositório contém a aplicação prática de métodos estatísticos voltados ao planejamento, condução e análise de experimentos. O foco é extrair o máximo de informação com o menor número de ensaios, garantindo a validade estatística das conclusões.

---

## 🛠️ Conteúdo Técnico

Os trabalhos documentam a evolução desde os conceitos fundamentais até a otimização de sistemas complexos:

### 1. Fundamentos e Experimentos Fatoriais $2^k$ (Trabalho 1)
* **Princípios Básicos:** Aleatorização, repetição e blocagem.
* **Fatoriais Completos:** Análise de experimentos $2^k$ para identificação de efeitos principais e interações.

### 2. Blocagem e Comparação de Médias (Trabalho 2)
* **Delineamento em Blocos Completos Casualizados (DBC):** Controle de variabilidade externa.
* **ANOVA e Testes de Comparação:** Identificação de diferenças significativas entre tratamentos (Tukey, Duncan).

### 3. Experimentos Fracionados e Triagem (Trabalho 3)
* **Fatoriais Fracionados $2^{k-p}$:** Estratégias de triagem (screening) quando o número de fatores é elevado.
* **Análise de Resolução e Aliasing:** Entendimento das estruturas de confusão entre efeitos.

### 4. Metodologia de Superfície de Resposta - RSM (Trabalho 4)
* **Modelagem de Segunda Ordem:** Ajuste de modelos quadráticos para encontrar curvaturas na resposta.
* **Otimização de Processos:** Localização de pontos ótimos (máximos, mínimos ou sela) e uso de funções de desejabilidade.



---

## 🚀 Tecnologias e Implementação

* **Linguagem:** R.
* **Pacotes Chave:** `DoE.base`, `FrF2`, `rsm`, `ggplot2`.
* **Relatórios:** R Markdown com diagnósticos de resíduos e validação de pressupostos (Normalidade e Homocedasticidade).

---

## 📂 Estrutura de Arquivos

* `Trabalho1` a `Trabalho4`: Cada pasta contém o arquivo `.Rmd` (código) e o relatório final em `.pdf`.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
