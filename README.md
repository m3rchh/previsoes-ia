# 💡 Projeto de Inteligência Artificial e Previsões no Python

Este projeto tem como objetivo analisar uma base robusta de clientes de um banco, a fim de identificar o score de crédito desses clientes a partir de um modelo de Inteligência Artificial.  
A análise foi feita em **Python** utilizando **Jupyter Notebook**.

---

## 🛠️ Instalação das dependências

Para rodar o projeto, instale as bibliotecas necessárias:
pip install pandas scikit-learn

---


## 🚀 Passo a Passo do Desafio

### 🔶 Entender o desafio da empresa 🔶  
Prever a nota de crédito com o máximo de precisão


### 🔹 Passo 1: Importar a base de dados
- Importação da biblioteca Pandas para ler o arquivo csv 'clientes'

---

### 🔹 Passo 2: Preparar a base de dados para inteligência artificial
- Objetivos:
  - Entender as informações contidas
  - Encontrar possíveis problemas nos dados, como tipo de dado 
  - Transformar os textos (object) em números inteiros usando #LabelEncoder
  - Separar as informações para IA em dados de treino e de teste, onde teremos:
	- Y -> quem eu quero prever (coluna score_credito) 
	- X -> as outras colunas (as que serão usadas para fazer a previsão)

---

### 🔹 Passo 3: Criar o modelo de inteligência artificial
  - Passos para criação de modelo de IA:
	- Importar o modelo
	- Criar o modelo
	- Treinar o modelo

  - Tipos de modelo de IA que serão usados:
	- Árvore de Decisão -> #RandomForest
	- Vizinhos Próximos -> #KNN 

---

### 🔹 Passo 4: Escolher o melhor modelo a partir da acurácia das previsões
- Acurácia modelo Árvore de Decisão: 82,82%
- Acurácia modelo Vizinho Próximo (KNN): 74,06%

---

### 🔹 Passo 5:  Implementar o modelo
- Conclusão: o melhor modelo é o de Árvore de Decisão pois apresentou maior acurácia
- Usamos uma nova base de dados .csv 'novos_clientes' para testar na prática
	- RESULTADO: ['Poor', 'Good', 'Standard']

---

### ✅ Conclusão

O projeto mostrou que entre os dois modelos testados, para o caso do desafio a Árvore de Decisão apresentou maior precisão.
