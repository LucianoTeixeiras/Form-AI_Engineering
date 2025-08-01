# Formação AI Engineering

Repositório dedicado à organização de estudos, projetos práticos e referências desenvolvidos ao longo da trilha de formação em **AI Engineering**. Os materiais contemplam desde fundamentos de Data Science até práticas avançadas de produção e operacionalização de modelos de IA em ambientes corporativos.

## Estrutura dos Módulos

### 1. Mercado de Data Science e Inteligência Artificial

- Histórico das áreas de ciência de dados e inteligência artificial (IA)
- Semelhanças e diferenças entre as áreas
- Evolução e tendências recentes da IA
- Definição e escopo de projetos de ciência de dados
- Uso de Feature Store para disponibilização de dados
- Versionamento e ambientes dev/prod para projetos
- Desenvolvimento e avaliação de modelos com **MLflow Tracking**
- Deploy de modelos com **MLflow Models** (lote e real time)
- Monitoramento de modelos em produção
- Execuções automatizadas com **Databricks Asset Bundles**

---

### 2. Fundamentos do Databricks para IA

- Introdução à interface e recursos do Databricks para machine learning
- Fundamentos de computação distribuída (**Apache Spark**)
- Integração com Python, Scala e SQL para projetos de IA

---

### 3. Machine Learning Operations com Databricks

- Estruturação de projetos de ciência de dados no Databricks
- Versionamento e ambientes dev/prod
- Desenvolvimento, avaliação e deploy de modelos com **MLflow**
- Execuções automatizadas usando **Databricks Asset Bundles**

---

### 4. Processamento de Linguagem Natural (NLP)

- Tópicos em processamento de linguagem natural
- Limpeza e análise de dados textuais
- Tokenização e vetorização
- Análise de sentimentos
- Modelagem de tópicos

---

### 5. Fundamentos de Redes Neurais Tradicionais

- Conceitos e aplicações de redes neurais
    - Perceptron, MLP, funções de ativação, backpropagation, cost function, inicialização de parâmetros
- Introdução a **Recurrent Neural Networks (RNN)**
    - Vanilla RNN, processamento em batches, problema de vanishing gradients, LSTM, GRU
- Implementação de mecanismos de atenção

---

### 6. Modelos de Linguagem Pré-treinados e LLMOps

- Principais modelos pré-treinados disponíveis no mercado e no Databricks
- **Prompt Engineering**
- **Retrieval-Augmented Generation (RAG)**
- Implementação de agentes
- Práticas de **LLMOps** para produção

---

## Sobre este repositório

Cada módulo possui anotações, notebooks, scripts, experimentos e projetos práticos. O objetivo é consolidar e demonstrar conhecimento aplicado em Engenharia de IA, com exemplos relevantes para ambientes corporativos e demandas do mercado.

Sinta-se à vontade para explorar os conteúdos e contribuir com sugestões.

---

## Estrutura Sugerida de Pastas e Protótipos

Para facilitar a organização e a navegação dos notebooks de protótipos desenvolvidos, recomenda-se a seguinte estrutura:

```
notebooks/
├── 01-feature-store/
│   └── Feature_Store_Demo.ipynb
├── 02-custom-model/
│   └── Custom_Model_Demo.ipynb
├── 03-mlflow/
│   └── MLflow_Demo.ipynb
├── 04-spark/
│   └── Spark_Demo.ipynb
├── 05-languages/
│   └── Languages_Demo.ipynb
├── data/         # (Opcional: dados de exemplo para os notebooks)
├── scripts/      # (Opcional: scripts auxiliares)
```

### Protótipos Disponíveis

- [Feature Store Demo](notebooks/01-feature-store/Feature_Store_Demo.ipynb)
- [Custom Model Demo](notebooks/02-custom-model/Custom_Model_Demo.ipynb)
- [MLflow Demo](notebooks/03-mlflow/MLflow_Demo.ipynb)
- [Spark Demo](notebooks/04-spark/Spark_Demo.ipynb)
- [Languages Demo](notebooks/05-languages/Languages_Demo.ipynb)

> **Como navegar:**  
> - Cada subpasta de `notebooks/` contém um notebook principal e um `README.md` explicativo.
> - Siga as instruções dos READMEs para rodar localmente ou em ambiente cloud.
> - Utilize a pasta `data/` para conjuntos de dados auxiliares (se necessário).

---
