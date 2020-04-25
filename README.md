# Документация к Cronbox

## Как собрать

1. Подтягиваем актуальную версию темы

```shell script
git clone git@github.com:tinyops-ru/tinydocs-zola-theme.git themes/tinydocs
```

2. Собираем

```shell script
zola build --output-dir docs --base-url https://docs.cronbox.ru
```

3. Результат будет в каталоге `docs`.
