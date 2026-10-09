# Classifier Comparison

Я сравнил шесть моделей классификации: Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting и SVM.

## Запуск

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook ml.ipynb
```

## Устройство проекта

Для запуска положите исходные `train.csv` и `test.csv` рядом с ноутбуком. Данные и прежние выводы ячеек исключены. Ноутбук показывает подготовку признаков, обучение и сравнение по accuracy; значения метрик требуют повторного запуска.

Я публикую исходный код без локальных паролей, окружений, баз и журналов. Для воспроизведения анализа я указываю необходимые данные и зависимости.

## Автор

Антон Никитин — [anton-nikitin21](https://github.com/anton-nikitin21).
