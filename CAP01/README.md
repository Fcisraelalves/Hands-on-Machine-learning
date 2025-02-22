# 📌 **Machine Learning: Panorama Geral** 

## 📌 **Definição** 
> *Machine learning* é um campo da inteligência artificial que estuda a criação e execução de técnicas que permitam aos computadores aprenderem com os dados sem serem explicitamente programados.

---

## 🤖 **Por que usar o Machine Learning?**  

### 🔄 **Adaptabilidade**
Imagine que precisamos construir um programa para detectar *spam* em e-mails. Na programação clássica, criaríamos uma longa lista de regras, que precisaria ser atualizada toda vez que os *spammers* mudassem de estratégia.  

✅ **No Machine Learning**, o modelo aprende padrões automaticamente e se adapta a novas táticas apenas sendo re-treinado com novos dados.  

### 📌 **Solução para problemas complexos**
Exemplo: Como usar programação tradicional para detectar lesões cerebrais em tomografias?  
❌ **Abordagem tradicional**: Exigiria um algoritmo altamente complexo e rígido.  
✅ **Com Machine Learning**: Basta fornecer ao modelo exemplos de cérebros lesionados e saudáveis, e ele aprende automaticamente os padrões que identificam cada um.  

Além disso, o *machine learning* pode ajudar os seres humanos a aprenderem novos padrões ao inspecionar os modelos treinados.

---

## 📊 **Dados de treino e teste**  

### 📌 **Dados de treino**
Os dados de treino são usados para ensinar o modelo, contendo *features* e possivelmente *labels*.  
💡 Às vezes, técnicas de pré-processamento são necessárias para melhorar a generalização do modelo.

### 📌 **Dados de teste**
Os dados de teste avaliam a **capacidade de generalização** do modelo.  
💡 Também chamada de fase de *validação*, essa etapa identifica possíveis problemas de desempenho.

---

## 🔍 **Principais conceitos**  

### 📌 **Features**
As *features* são as características utilizadas pelo modelo para aprender padrões.  
- Também chamadas de **variáveis independentes** (não possuem relação de dependência entre si).

### 📌 **Labels**
Os *labels* são os rótulos fornecidos ao modelo em **aprendizado supervisionado** e representam a saída esperada.  
- Também chamados de **variáveis dependentes** ou *target*.

---

# 📌 **Tipos de aprendizado de máquina**  

Os modelos podem ser classificados de diferentes formas:  

1️⃣ **Pelo nível de supervisão humana**  
2️⃣ **Pelo modelo de predição**  
3️⃣ **Pela capacidade de aprender em tempo real**  

---

## 🏆 **Classificação conforme o nível de supervisão**  

### 🎓 **Aprendizado supervisionado**  
Os dados de treino incluem as *features* e os *labels*. O modelo aprende a relação entre as características e a saída esperada para fazer previsões futuras.  

#### 🔹 **Tarefas supervisionadas**  
- **Classificação**: As saídas são classes pré-determinadas (*ex:* "spam" ou "não spam").  
- **Regressão**: As saídas são valores contínuos (*ex:* prever preço de um imóvel).  

### 🔍 **Aprendizado não supervisionado**  
Os dados de treino incluem apenas as *features*, sem rótulos. O objetivo é encontrar padrões ocultos.  

#### 🔹 **Tarefas não supervisionadas**  
- **Clusterização**: Agrupamento de dados semelhantes.  
- **Detecção de anomalias**: Identificação de padrões fora do comum.  
- **Visualização**: Representação de dados multidimensionais.  
- **Redução de dimensionalidade**: Evita problemas como a "maldição da dimensionalidade".  
- **Detecção de novidades**: Encontrar amostras inéditas no conjunto de dados.  
- **Regras de associação**: Descobrir relações implícitas nos dados.  

### ⚖️ **Aprendizado semi-supervisionado**  
Combina técnicas de aprendizado supervisionado e não supervisionado para obter melhores resultados.

### 🕹️ **Aprendizado por reforço**  
O modelo interage com um ambiente, recebendo **recompensas** ou **penalidades** para aprender a melhor estratégia de ação (*política*).  

---

## 🤖 **Classificação conforme o modelo de predição**  

### 🏗️ **Aprendizado baseado em instâncias**  
- Armazena **todos os dados de treinamento**.  
- Faz previsões comparando **novas amostras** com as amostras já conhecidas.  

### 🔢 **Aprendizado baseado em modelos**  
- O modelo aprende padrões nos dados e armazena apenas o modelo preditivo.  
- Faz previsões usando a **relação matemática aprendida**.  

---

## 🤖 **Classificação conforme a capacidade de aprendizado em tempo real**  

### 📌 **Aprendizado em batch**  
✅ Processa **todo o conjunto de dados de uma vez**.  
❌ Não aprende em tempo real.  

### 📌 **Aprendizado online**  
✅ Processa os dados **de forma incremental**.  
✅ Aprende **em tempo real**.  

---


