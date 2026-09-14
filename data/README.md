# data/

Исходный датасет — **CEFR Levelled English Texts** (Kaggle, автор amontgomerie):
https://www.kaggle.com/datasets/amontgomerie/cefr-levelled-english-texts

Датасет **не хранится в репозитории** — он скачивается в ноутбуке через `kagglehub`:

```python
import kagglehub
path = kagglehub.dataset_download("amontgomerie/cefr-levelled-english-texts")
```

Структура папки после запуска ноутбука:

- `raw/` — оригинальные файлы, как они пришли с Kaggle (в git не попадают, см. `.gitignore`);
- `processed/` — очищенные и разбитые на train / val / test выборки;
- `sample.csv` — небольшой фрагмент датасета (первые 50 строк), чтобы структуру данных было видно прямо на GitHub без скачивания.
