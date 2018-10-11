<table>
    <tr>
        <td> Read these guidelines in </td>
        <td><a href="/CONTRIBUTING.md"> English </a></td>
        <td><a href="/docs/chinese/CONTRIBUTING.md"> 中文 </a></td>
        <td><a href="/docs/russian/CONTRIBUTING.md"> русский </a></td>
        <td><a href="/docs/arabic/CONTRIBUTING.md"> عربى </a></td>
        <td><a href="/docs/spanish/CONTRIBUTING.md"> Español </a></td>
        <td><a href="/docs/portuguese/CONTRIBUTING.md"> Português </a></td>
    </tr>
</table>
# Как работать с задачами

### Изменение на GitHub

Каждая задача хранится в собственном .md файле. Это упрощает редактирование задач прямо из GitHub.

Вы можете внести изменения без каких-либо действий в вашей локальной системе.

После того, как вы найдете файл, который хотите изменить в интерфейсе GitHub, щелкните значок карандаша, чтобы начать редактирование файла. Это автоматически создаст fork проекта, если у вас ее еще нет.

Вы также можете клонировать проект и редактировать локально на своем компьютере. Для получения справки прочтите этот основной [гайд](/CONTRIBUTING.md).

### Шаблон задач

Вот шаблон того, как выглядят .md файлы задачи.

````md
---
id: Уникальный идентификатор (буквенно-цифровой, MongoDB _id)
title: Название задачи
challengeType: 0
guideUrl: 'url на гайд'
videoUrl: 'url на видео обьяснение'
---

## Описание
<section id='description'>
Описание задачи и того, что требуется для прохождения
</section>

## Инструкции
<section id='instructions'>
Инструкции о том, что именно нужно сделать.
</section>
## Тесты
<section id='tests'>

``` yml
- text: Должен возращать "foo".
  testString: 'Строгая функция с использованием Chai утверждает'
```

</section>

<div id='js-seed'>

```js
Код который отображается в редакторе по умолчанию.
```

</div>

### Перед тестом
<div id='js-setup'>

```js
Тестовый начальный код.
```

</div>

</section>

### После испытания
<div id='js-teardown'>

```js
Проверить ваш код.
```

</div>

</section>

## Решение
<section id='solution'>

```js
Код решения проблемы.
```

</section>
````

### Полезные ссылки

Создание и редактирование задач:

1. [Руководство по стилю задач](style-guide-for-curriclum-challenges.md) - как создавать и редактировать задачи.

2. [Типы задач](https://github.com/freeCodeCamp/learn/blob/a5cb25704168aa37f59a582f0bb5a19b7bd89b46/utils/challengeTypes.js) - что означают цифровые значения типа задач (перечисление).

3. [Разработка в FreeCodeCamp - написание ES6 тестовых задач ](https://www.youtube.com/watch?v=iOdD84OSfAE#t=2h49m55s) - видео от [Этана Arrowood](https://twitter.com/ArrowoodTech), как он вносит свой вклад в старую версию учебного плана.
