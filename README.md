# 📌 Prevendo Vendas de Sorvete com Machine Learning 🍦📊

## 🚀 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio "**Prevendo Vendas de Sorvete com Machine Learning**" da DIO.  
O objetivo foi criar um modelo de regressão preditiva capaz de prever o número de sorvetes vendidos com base na temperatura do dia, ajudando donos de sorveterias a otimizarem sua produção, reduzindo desperdícios e maximizando os lucros.

---

## 🧩 Cenário

Imagine a sorveteria **Gelato Mágico**, localizada em uma charmosa cidade litorânea.  
A relação entre temperatura e vendas de sorvete é clara: quanto mais quente, maior a demanda! ☀️🍦

Sem um modelo de previsão, a produção acaba sendo feita "no chute", o que pode gerar:

- ❌ Excesso de produção → Prejuízo por desperdício.
- ❌ Produção insuficiente → Perda de vendas.

Para resolver isso, decidi usar **Machine Learning** para criar um modelo preditivo de vendas. 🎯

---

## 🎯 Objetivos do Projeto

✅ Treinar um modelo de **regressão preditiva** para prever vendas com base na temperatura.

✅ Utilizar **MLflow** para registrar e gerenciar os experimentos de Machine Learning.

✅ Implementar o modelo em um ambiente de **cloud computing** para fazer previsões em tempo real.

✅ Construir um **pipeline estruturado** para garantir a reprodutibilidade do processo de treinamento e teste.

---

## 🗂️ Estrutura do Repositório

```bash
📁 inputs
    ↳ Dataset/texto com sentenças utilizadas no projeto.
📁 src
    ↳ Scripts de preparação de dados, treinamento, avaliação e deployment.
📄 README.md
    ↳ Este documento.
```

---

## 🔥 Processo de Desenvolvimento

1. **Análise Exploratória dos Dados (EDA)**  
   - Entendimento do dataset.
   - Verificação de correlação entre temperatura e vendas.
   
2. **Preparação dos Dados**  
   - Tratamento de dados faltantes.
   - Separação entre treino e teste.

3. **Criação e Treinamento do Modelo**  
   - Modelagem usando **regressão linear** simples.
   - Avaliação do modelo com métricas como MAE, MSE e R².

4. **Gerenciamento de Experimentos**  
   - Registro de modelos, parâmetros e métricas usando **MLflow**.

5. **Deploy Simulado em Cloud**  
   - Simulação de endpoint para previsões em tempo real (foco no conceito de deploy em cloud).

---

## 📸 Prints do Projeto

### 🔵 Avançando no Projeto

![Avançando](https://satreinamentoazureblob1.blob.core.windows.net/apps/Avancando.JPG)

### 🟠 Deploy do Modelo

![Deploy](https://satreinamentoazureblob1.blob.core.windows.net/apps/Deploy.JPG)

### 🟣 Deploy Avançado

![Deploy Avançado](https://satreinamentoazureblob1.blob.core.windows.net/apps/Deploy_2.JPG)

---

## ✨ Insights e Aprendizados

- A correlação entre temperatura e venda de sorvetes é muito forte — o que torna o problema ideal para uma regressão linear.
- O uso do **MLflow** foi essencial para manter o rastreio de experimentos e facilitar o versionamento dos modelos.
- Deploy em cloud aumenta o potencial de usar esse modelo em aplicações reais, como sistemas de gestão para sorveterias.
- Garantir pipelines reprodutíveis deixa o projeto mais profissional e escalável para novos dados.

---

## 📈 Possibilidades de Melhoria

- Testar modelos mais complexos como **Random Forest Regression** para melhorar a acurácia.
- Criar uma interface simples (ex: com Streamlit) para entrada de temperatura e previsão de vendas em tempo real.
- Realizar deploy real usando serviços como **Azure Machine Learning**, **AWS SageMaker** ou **Google Vertex AI**.
- Incrementar o dataset com novas variáveis, como umidade, dia da semana, feriados, etc.

---

## 🛠️ Tecnologias Utilizadas

- Python 🐍
- Pandas
- Scikit-learn
- MLflow
- Jupyter Notebook
- [Sugestão de Cloud: Azure, AWS ou GCP]

---

## 🎯 Resultado

Com este projeto, mostrei na prática como aplicar técnicas fundamentais de **Machine Learning** para resolver um problema de **negócio real**.  
Esse tipo de projeto agrega muito valor ao portfólio e demonstra habilidades de ponta a ponta no ciclo de vida de Machine Learning!

---

**Bons estudos e sucesso nas suas jornadas de dados! 😉🚀**
