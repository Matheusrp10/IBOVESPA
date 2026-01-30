# Tech Challenge - Fase 2: Machine Learning em Finanças 📈

Este projeto compõe a entrega da Fase 2 do Tech Challenge. O objetivo principal é desenvolver um modelo preditivo de Machine Learning capaz de prever a tendência (alta ou baixa) do índice Ibovespa (IBOV) para o dia seguinte, auxiliando na tomada de decisão de investimentos.

## 🗂 Estrutura do Projeto

O repositório está organizado da seguinte forma:

* `tech_challenge_fase2.ipynb`: Notebook principal contendo toda a análise exploratória (EDA), pré-processamento, treinamento e avaliação dos modelos.
* `ibov_dados_processados.csv`: Dataset histórico processado com indicadores técnicos.
* `models/`: (Idealmente, mova os arquivos .joblib para uma pasta)
    * `model_gb.joblib`: Modelo Gradient Boosting treinado.
    * `model_rf.joblib`: Modelo Random Forest treinado.
    * `model_lr.joblib`: Modelo de Regressão Logística (Baseline).
    * `scaler.joblib`: Objeto escalador (StandardScaler) para normalização dos dados.
* `requirements.txt`: Lista de dependências para rodar o projeto.

## 🛠 Instalação e Configuração

Para reproduzir este projeto, recomenda-se criar um ambiente virtual e instalar as dependências.

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPO.git](https://github.com/SEU_USUARIO/NOME_DO_REPO.git)
   cd NOME_DO_REPO