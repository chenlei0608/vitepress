# Последнее обновление {#last-updated}

Время последнего обновления содержимого будет отображаться в правом нижнем углу страницы. Чтобы включить его, добавьте опцию `lastUpdated` в свой конфиг.

::: tip Совет
Чтобы увидеть обновленное время, необходимо зафиксировать файл Markdown.
:::

## Настройка в файле конфигурации {#site-level-config}

```js
export default {
  lastUpdated: true
}
```

## Настройка в метаданных {#frontmatter-config}

Эту информацию можно отключить на конкретной странице с помощью опции `lastUpdated` в метаданных:

```yaml
---
lastUpdated: false
---
```

Также смотрите [Тема по умолчанию: `lastUpdated`](./default-theme-config#lastupdated) для получения более подробной информации. Любое истинное значение на уровне темы также включит функцию, если только она не будет явно отключена на уровне сайта или страницы.