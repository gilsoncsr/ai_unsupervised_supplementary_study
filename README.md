# Detecção de Anomalias com LOF - Churn de Clientes de Telecom

Este projeto utiliza o algoritmo **Local Outlier Factor (LOF)** para identificar padrões anômalos em uma base de dados de clientes de uma empresa de telecomunicações. A detecção de anomalias é realizada com o objetivo de prever comportamentos relacionados ao cancelamento de contrato (churn).

## 🔧 Tecnologias e Bibliotecas Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn

## 📊 Descrição do Projeto

1. **Carregamento da base de dados** com informações de clientes.
2. **Análise exploratória inicial** e preparação da base.
3. **Pré-processamento dos dados** com uso de `ColumnTransformer` para tratar variáveis numéricas, categóricas e binárias.
4. **Aplicação do algoritmo LOF** para identificação de outliers (clientes com maior probabilidade de churn).
5. **Avaliação dos resultados** utilizando a métrica de **Recall**, focando em maximizar a taxa de verdadeiros positivos.

## 📁 Estrutura dos Dados

A base de dados inclui atributos como:

- Tempo de contrato (`tenure`)
- Cobranças mensais (`MonthlyCharges`)
- Tipo de serviço, suporte, pagamento, etc.
- Variável alvo: `Churn` (Yes/No)

## ✅ Resultados

O modelo foi capaz de identificar padrões fora do comum na base, permitindo que a empresa possa focar seus esforços em reter clientes com maior propensão ao churn.

## 🚀 Como Executar

1. Instale as dependências:
   ```bash
   pip install pandas scikit-learn
   ```

---

### 📁 Projeto 2 – Clusterização de Empresas com GMM + Otimização via Optuna

# Clusterização de Empresas com GMM e Interface Gradio

Este projeto aplica **Gaussian Mixture Models (GMM)** para realizar a clusterização de empresas a partir de atributos como faturamento, localização, inovação e número de funcionários. O projeto também utiliza **Optuna** para otimização dos hiperparâmetros e disponibiliza uma interface em Gradio para uso interativo.

## 🔧 Tecnologias e Bibliotecas Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Optuna
- Plotly
- Gradio
- Joblib

## 📊 Descrição do Projeto

1. **Carregamento da base de dados** com informações de empresas.
2. **Pré-processamento** com `ColumnTransformer` aplicando escalonamento, one-hot encoding e ordinal encoding conforme o tipo de variável.
3. **Treinamento do GMM** com otimização de parâmetros (`n_components`, `covariance_type`) via **Optuna**.
4. **Visualização interativa dos clusters** com gráficos Plotly.
5. **Exportação de modelo e pipeline** para reuso.
6. **Criação de uma aplicação em Gradio** que permite:
   - Upload de um novo arquivo `.csv`
   - Aplicação do modelo treinado
   - Download de um novo arquivo com os clusters identificados

## 📁 Estrutura dos Dados

A base de dados inclui colunas como:

- `faturamento_mensal`
- `numero_de_funcionarios`
- `idade`
- `localizacao`
- `atividade_economica`
- `inovacao`

## 🧪 Otimização com Optuna

- Avaliação de até 32 combinações de parâmetros com **BIC (Bayesian Information Criterion)** como métrica de desempenho.
- Parâmetros otimizados:
  - Número de componentes (clusters)
  - Tipo de covariância

## 🚀 Como Executar

1. Instale as dependências:
   ```bash
   pip install pandas numpy scikit-learn optuna plotly gradio joblib
   ```

---

# Anomaly Detection with LOF - Telecom Customer Churn

This project uses the **Local Outlier Factor (LOF)** algorithm to identify anomalous patterns in a telecom company's customer database. The anomaly detection is performed with the goal of predicting behaviors related to contract cancellation (churn).

## 🔧 Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn

## 📊 Project Description

1. **Loading the dataset** with customer information.
2. **Initial exploratory analysis** and data preparation.
3. **Data preprocessing** using `ColumnTransformer` to handle numerical, categorical, and binary variables.
4. **Application of the LOF algorithm** to detect outliers (customers with a higher likelihood of churn).
5. **Evaluation of results** using the **Recall** metric, focusing on maximizing the true positive rate.

## 📁 Data Structure

The dataset includes attributes such as:

- Contract tenure (`tenure`)
- Monthly charges (`MonthlyCharges`)
- Type of service, support, payment, etc.
- Target variable: `Churn` (Yes/No)

## ✅ Results

The model successfully identified unusual patterns in the data, allowing the company to focus its efforts on retaining customers with a higher risk of churn.

## 🚀 How to Run

1. Install the dependencies:
   ```bash
   pip install pandas scikit-learn
   ```

---

### 📁 Project 2 – Company Clustering with GMM + Optimization via Optuna

# Company Clustering with GMM and Gradio Interface

This project applies **Gaussian Mixture Models (GMM)** to cluster companies based on attributes such as revenue, location, innovation, and number of employees. The project also uses **Optuna** for hyperparameter optimization and provides a Gradio interface for interactive use.

## 🔧 Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Optuna
- Plotly
- Gradio
- Joblib

## 📊 Project Description

1. **Loading the dataset** with company information.
2. **Preprocessing** using `ColumnTransformer` to apply scaling, one-hot encoding, and ordinal encoding depending on the variable type.
3. **Training the GMM** with parameter optimization (`n_components`, `covariance_type`) via **Optuna**.
4. **Interactive cluster visualization** with Plotly charts.
5. **Model and pipeline export** for reuse.
6. **Development of a Gradio application** that allows:
   - Uploading a new `.csv` file
   - Applying the trained model
   - Downloading a new file with the identified clusters

## 📁 Data Structure

The dataset includes columns such as:

- `faturamento_mensal` (monthly revenue)
- `numero_de_funcionarios` (number of employees)
- `idade` (age)
- `localizacao` (location)
- `atividade_economica` (economic activity)
- `inovacao` (innovation)

## 🧪 Optimization with Optuna

- Evaluation of up to 32 parameter combinations using **BIC (Bayesian Information Criterion)** as the performance metric.
- Optimized parameters:
  - Number of components (clusters)
  - Covariance type

## 🚀 How to Run

1. Install the dependencies:
   ```bash
   pip install pandas numpy scikit-learn optuna plotly gradio joblib
   ```

---

# Detección de Anomalías con LOF - Churn de Clientes de Telecomunicaciones

Este proyecto utiliza el algoritmo **Local Outlier Factor (LOF)** para identificar patrones anómalos en una base de datos de clientes de una empresa de telecomunicaciones. La detección de anomalías se realiza con el objetivo de predecir comportamientos relacionados con la cancelación de contratos (churn).

## 🔧 Tecnologías y Bibliotecas Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn

## 📊 Descripción del Proyecto

1. **Carga de la base de datos** con información de clientes.
2. **Análisis exploratorio inicial** y preparación de los datos.
3. **Preprocesamiento de los datos** utilizando `ColumnTransformer` para tratar variables numéricas, categóricas y binarias.
4. **Aplicación del algoritmo LOF** para identificar valores atípicos (clientes con mayor probabilidad de churn).
5. **Evaluación de los resultados** utilizando la métrica de **Recall**, enfocándose en maximizar la tasa de verdaderos positivos.

## 📁 Estructura de los Datos

La base de datos incluye atributos como:

- Tiempo de contrato (`tenure`)
- Cargos mensuales (`MonthlyCharges`)
- Tipo de servicio, soporte, método de pago, etc.
- Variable objetivo: `Churn` (Yes/No)

## ✅ Resultados

El modelo fue capaz de identificar patrones inusuales en la base de datos, lo que permite que la empresa enfoque sus esfuerzos en retener a los clientes con mayor probabilidad de churn.

## 🚀 Cómo Ejecutar

1. Instala las dependencias:
   ```bash
   pip install pandas scikit-learn
   ```

---

### 📁 Proyecto 2 – Clusterización de Empresas con GMM + Optimización vía Optuna

# Clusterización de Empresas con GMM e Interfaz Gradio

Este proyecto aplica **Gaussian Mixture Models (GMM)** para realizar la clusterización de empresas a partir de atributos como ingresos, ubicación, innovación y número de empleados. También utiliza **Optuna** para la optimización de hiperparámetros y proporciona una interfaz con Gradio para su uso interactivo.

## 🔧 Tecnologías y Bibliotecas Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Optuna
- Plotly
- Gradio
- Joblib

## 📊 Descripción del Proyecto

1. **Carga de la base de datos** con información de empresas.
2. **Preprocesamiento** con `ColumnTransformer`, aplicando escalado, one-hot encoding y codificación ordinal según el tipo de variable.
3. **Entrenamiento del GMM** con optimización de parámetros (`n_components`, `covariance_type`) utilizando **Optuna**.
4. **Visualización interactiva de los clusters** con gráficos de Plotly.
5. **Exportación del modelo y pipeline** para reutilización.
6. **Creación de una aplicación en Gradio** que permite:
   - Subir un nuevo archivo `.csv`
   - Aplicar el modelo entrenado
   - Descargar un nuevo archivo con los clusters identificados

## 📁 Estructura de los Datos

La base de datos incluye columnas como:

- `faturamento_mensal` (ingresos mensuales)
- `numero_de_funcionarios` (número de empleados)
- `idade` (edad)
- `localizacao` (ubicación)
- `atividade_economica` (actividad económica)
- `inovacao` (innovación)

## 🧪 Optimización con Optuna

- Evaluación de hasta 32 combinaciones de parámetros utilizando **BIC (Bayesian Information Criterion)** como métrica de rendimiento.
- Parámetros optimizados:
  - Número de componentes (clusters)
  - Tipo de covarianza

## 🚀 Cómo Ejecutar

1. Instala las dependencias:
   ```bash
   pip install pandas numpy scikit-learn optuna plotly gradio joblib
   ```
