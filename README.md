# Научиться учиться

Учебный проект для изучения возможностей `HTML` и `CSS`.

## Используемые технологии
* Флексбокс-вёрстка
* Позиционирование элементов
* iframe
* Кейфреймы
* Анимации и трансформации
* Организация файлов по БЭМ (nested)


## Подробнее
Страница представляет собой общий блок **page**, содержащий шапку сайта **header** основное содержимое страницы **main** и подвал блок **footer**.
Шапка содержит заголовок первого уровня _h1_. Реализована анимация: квадрат совершает поворот с равномерной скоростью по часовой стрелке при помощи кейфреймов и анимации.
В блоке **main** используется флексбокс-вёрстка для управления положением содержимого. Также для вставки видео используется тег:
```html
<iframe></iframe>
```
Проблема переполнения блоков решена при помощи свойства _overflow_ со значением _hidden_. Для анимации треугольника переиспользуется блок rotation.
В подвале сайта используется тег объединяющий элементы навигации по сайту:
```html
<nav></nav>
```
Блоки, которые являются общими для различных секций макета, переиспользуются где это возможно. Все ссылки при наведении мыши плавно становятся прозрачными.
