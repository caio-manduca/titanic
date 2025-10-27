# titanic

## Visão geral
Projeto de exemplo para previsão de sobrevivência no desastre do Titanic usando notebook Jupyter. O notebook carrega os conjuntos de dados, realiza engenharia de features, pré-processamento e compara modelos (XGBoost e Decision Tree) com validação cruzada estratificada.

## Conteúdo do repositório
- [main.ipynb](main.ipynb) — Notebook principal com todo o pipeline (carregamento, EDA, Feature Engineering, treinamento e geração de submissão).
- [train.csv](train.csv) — Dados de treino (inclui a variável alvo `Survived`).
- [test.csv](test.csv) — Dados de teste para geração da submissão.
- [README.md](README.md) — Este arquivo.

## Como usar
1. Abra o notebook: [main.ipynb](main.ipynb) (recomendado executar no VS Code ou Jupyter).
2. Instale as dependências principais:
```sh
pip install pandas numpy scikit-learn xgboost seaborn matplotlib