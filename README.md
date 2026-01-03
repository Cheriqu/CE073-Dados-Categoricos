# Análise de Dados Categoricos (CE073) - UFPR

Este repositório reúne os trabalhos práticos da disciplina de Análise de Dados Categoricos. O foco central é a modelagem de dados discretos, onde a suposição de normalidade não é atendida, exigindo o uso de **Modelos Lineares Generalizados (GLMs)**.



## 🛠️ Conteúdo Técnico

Os projetos demonstram a progressão da análise exploratória até a modelagem avançada:

### 1. Associação e Tabelas de Contingência (Trabalho 1)
* **Testes de Independência:** Qui-Quadrado de Pearson e Teste Exato de Fisher.
* **Medidas de Efeito:** Cálculo e interpretação de Razão de Chances (Odds Ratio) e Risco Relativo.
* **Análise Estratificada:** Controle de variáveis de confusão (Paradoxo de Simpson).

### 2. Regressão Logística Binária (Trabalho 2)
* **Modelagem GLM:** Ajuste de modelos para respostas binárias (Sucesso/Fracasso) utilizando a função de ligação *logit*.
* **Interpretação:** Análise dos coeficientes em termos de log-odds.
* **Seleção de Variáveis:** Métodos de Stepwise e análise de deviance (AIC/BIC).

### 3. Extensões do Modelo Logístico (Trabalho 3)
* **Diagnóstico de Ajuste:** Análise de resíduos (Deviance, Pearson) e pontos de alavanca.
* **Curva ROC e Acurácia:** Avaliação do poder preditivo do modelo classificador.
* **Regressão Multinomial/Ordinal:** Tratamento de respostas com mais de duas categorias.

### 4. Dados de Contagem e Poisson (Trabalho 4)
* **Regressão de Poisson:** Modelagem de taxas e contagens de eventos raros.
* **Superdispersão:** Identificação e tratamento de variância excessiva (uso de quase-verossimilhança ou Binomial Negativa).

---

## 🚀 Tecnologias e Implementação

* **Linguagem:** R.
* **Pacotes Principais:** `stats` (glm), `car`, `pROC`.
* **Relatórios:** Documentação completa em R Markdown, combinando teoria estatística com interpretação prática dos outputs.

---

## 📂 Estrutura de Arquivos

* `Trabalho1` a `Trabalho4`: Pares de arquivos `.Rmd` (código reprodutível) e `.pdf` (relatório final) cobrindo desde a análise descritiva até a modelagem complexa.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
