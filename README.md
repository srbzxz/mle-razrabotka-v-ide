# mle-razrabotka-v-ide

Инструмент для быстрого анализа табличных данных: класс `DataFrameReporter`
выводит размер датафрейма, количество и долю дубликатов, сводную статистику
(`describe`) и информацию о пропущенных значениях — без необходимости писать
эти проверки вручную для каждого нового датасета.

## Установка окружения

```bash
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Запуск

```bash
python3 main.py
```

Отчёт строится по датасету `data/payments.csv` и выводится в консоль.
