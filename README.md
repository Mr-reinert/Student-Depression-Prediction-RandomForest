# Student Depression Prediction using Random Forest

Este projeto tem como objetivo prever a depressão em estudantes com base em dados demográficos, acadêmicos e de estilo de vida. Utilizamos técnicas de **Machine Learning** para identificar os principais fatores que contribuem para a depressão e desenvolver um modelo preditivo.

---

## 📋 Sobre o Projeto

O dataset utilizado contém 27.901 registros com informações como:
- **Variáveis demográficas**: Idade, gênero, cidade.
- **Variáveis acadêmicas**: Pressão acadêmica, CGPA, satisfação com os estudos.
- **Variáveis de estilo de vida**: Hábitos alimentares, horas de sono, estresse financeiro.
- **Variável alvo**: Depressão (0 = Não, 1 = Sim).

O modelo de **Random Forest** foi escolhido para a tarefa de classificação, alcançando uma acurácia de **84%**.

---

## 🎫 Como Executar o Projeto

### Pré-requisitos
- Python 3.8+
- Bibliotecas listadas no arquivo `requirements.txt`.

### Passos para Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/Mr-reinert/Student-Depression-Prediction-RandomForest.git

2. Navegue até o diretório do projeto:

   ```bash
   cd Student-Depression-Prediction-RandomForest
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt

4. Execute os notebooks na pasta notebooks/:

- 01_Exploratory_Analysis.ipynb: Análise exploratória dos dados.
- 02_Data_Cleansing.ipynb: Limpeza e pré-processamento dos dados.
- 03_Modeling.ipynb: Treinamento e avaliação do modelo.

---

## 📂 Estrutura do Projeto

![image](https://github.com/user-attachments/assets/4b91e241-dd31-48f8-9f90-1094b0969349)


--- 

## 📊 Resultados
- Acurácia do Modelo: 84%

- Features Mais Importantes:

   1. Pressão acadêmica
   2. CGPA
   3. Satisfação com os estudos
   4. Estresse financeiro

- Matriz de Confusão:

![image](https://github.com/user-attachments/assets/d26b8ecf-0a5b-4260-9ee3-f426017b4f8d)

 
Curva ROC:

![image](https://github.com/user-attachments/assets/6171b4d0-484e-45d9-bd51-a8adeff58e4e)


## 🛠 Tecnologias e Ferramentas
- Linguagem: Python

## Bibliotecas:

- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost
- Imbalanced-learn (SMOTE)

## Ferramentas:

- VS Code
- Git e GitHub


