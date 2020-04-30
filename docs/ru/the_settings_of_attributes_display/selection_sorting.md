## Сортировка для выборки допустимых значений

```
Применяется для атрибутов типа «Ссылка», "Коллекция".
```
Условие задается в мете класса в поле `«Сортировка выбора»` и представляет собой фильтр, который задает способ сортировки для объектов по ссылке атрибута. 

Доступные типы сортировки:
* Сортировка по возрастанию ("mode": 0)
* Сортировка по убыванию ("mode": 1)

*пример:*
```
"selSorting": [
    {
        "property": "atr1",
         "mode": 0
    }
]
```