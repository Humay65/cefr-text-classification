# data/

**Датасет:** [CEFR Levelled English Texts](https://www.kaggle.com/datasets/amontgomerie/cefr-levelled-english-texts) (Kaggle, автор amontgomerie) — 1494 английских текста с разметкой уровня CEFR от A1 до C2.

**Колонки:** `text` — текст, `label` — уровень.

В ноутбуке шесть уровней укрупнены до трёх классов: A — 560 текстов, B — 491, C — 443.

В этой папке лежит копия исходного файла. Отдельно скачивать его не нужно — в коде датасет загружается автоматически:

```python
import kagglehub
path = kagglehub.dataset_download("amontgomerie/cefr-levelled-english-texts")
```

Лицензия и условия использования — на странице датасета на Kaggle.