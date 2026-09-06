# RACIO training-data (public mirror)

Публічний mirror довідників навчань RACIO. Автоматично синхронізується з приватним репозиторієм `ratiy/zayavki-na-navchannya` через GitHub Action при кожному push у робочу гілку.

**Не редагувати цей репозиторій вручну** — зміни будуть перезаписані наступним sync.

## Файли

| Файл | Опис |
|---|---|
| `Rules.csv` | Правила / НПАОП — 289 позицій |
| `MatchingCourses.csv` | Маппінг rule → категорія + назви для центрів |
| `Categories.csv` | Категорії (ОП, ПБ, електро, ЦЗ, проф) |
| `Centers.csv` | Навчальні центри |
| `RuleCenterMap.csv` | Ціни `rule × center` |
| `RuleAliases.csv` | Аліаси/синоніми правил для autocomplete |
| `Applications.csv` | (порожня) — schema збережених заявок |
| `MarkupConfig.csv` | Конфіг націнок |

## Використання

Raw URLs для fetch у зовнішніх додатках (kp.racio.ua тощо):

```
https://raw.githubusercontent.com/ratiy/racio-training-data-public/main/Rules.csv
https://raw.githubusercontent.com/ratiy/racio-training-data-public/main/MatchingCourses.csv
```
