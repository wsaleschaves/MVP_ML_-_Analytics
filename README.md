# Projeto de Modelagem Preditiva

Este projeto foi desenvolvido no **Google Colab** e tem como objetivo aplicar técnicas de **Machine Learning** para problemas de **classificação** e **regressão**, avaliando a performance dos modelos com métricas apropriadas.

---

## Tecnologias Utilizadas
- Python 3
- Pandas & Numpy
- Scikit-learn
- Matplotlib & Seaborn
- Google Colab

---

## Estrutura do Projeto
- `notebooks/` → Jupyter/Colab notebooks com os experimentos.
- `data/` → Bases de dados utilizadas (se públicas ou mockadas).
- `src/` → Scripts auxiliares de pré-processamento e modelagem.
- `README.md` → Este arquivo.

---

## Descrição
O fluxo de trabalho realizado inclui:

1. **Exploração dos dados**  
   - Verificação de formato, tipos e valores ausentes.  
   - Análise estatística e exploratória inicial.  

2. **Pré-processamento**  
   - Tratamento de valores nulos.  
   - Codificação de variáveis categóricas.  
   - Normalização/Padronização quando necessário.  

3. **Modelagem**  
   - Algoritmos aplicados:
     - Random Forest (Classificação e Regressão)
     - Ridge Regression
   - Estratégias de validação:
     - `StratifiedKFold` para classificação  
     - `KFold` para regressão  

4. **Avaliação**  
   - Métricas utilizadas:
     - Classificação: `F1-Weighted`
     - Regressão: `MAE`, `RMSE`, `R²`

---

## Resultados
Exemplo de avaliação em regressão:
```python
{'mae': 0.02, 'rmse': 0.833, 'r2': 0.836}
