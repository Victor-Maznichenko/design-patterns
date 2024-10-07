# Паттерны проектирования

Паттерн - это повторяющийся шаблон или решение, которое помогает решить конкретную проблему в программировании. Это "лучшая практика" или "опытный совет" от опытных разработчиков.

<img src="./_assets/dance.gif" width="400" height="300" alt="alt text">
<img src="./_assets/dance2.gif" width="300" height="300" alt="alt text">

## Зачем знать паттерны?

- **Проверенные решения.** Вы тратите меньше времени, используя готовые решения, вместо повторного изобретения велосипеда. До некоторых решений вы смогли бы додуматься и сами, но многие могут быть для вас открытием.
- **Стандартизация кода.** Вы делаете меньше просчётов при проектировании, используя типовые унифицированные решения, так как все скрытые проблемы в них уже давно найдены.
- **Общий программистский словарь.** Вы произносите название паттерна, вместо того, чтобы час объяснять другим программистам, какой крутой дизайн вы придумали и какие классы для этого нужны.
  <br>
  <br>

## Почему паттерны могут стать проблемой?

### Неэффективные решения

Паттерны пытаются стандартизировать подходы, которые и так уже широко используются. Эта стандартизация кажется некоторым людям догмой и они реализуют паттерны «как в книжке», не приспосабливая паттерны к реалиям проекта.
<br>

### Неоправданное применение

«Если у тебя в руках молоток, то все предметы вокруг начинают напоминать гвозди.»<br>
Похожая проблема возникает у новичков, которые только-только познакомились с паттернами. Вникнув в паттерны, человек пытается применить свои знания везде. Даже там, где можно было бы обойтись кодом попроще.
<br>
<br>

## Классификация паттернов

### По использованию:

Низкоуровневые и простые паттерны — *идиомы*. Применимы только в рамках одного языка программирования.

Универсальные — *архитектурные паттерны*, можно реализовать практически на любом языке. Они нужны для проектирования всей программы, а не отдельных её элементов.

### По предназначению:

1. **Порождающие паттерны:** беспокоятся о гибком создании объектов без внесения в программу лишних зависимостей.

   - Фабричный метод
   - Абстрактная фабрика
   - Строитель
   - Прототип
   - Одиночка

2. **Структурные паттерны**: показывают различные способы построения связей между объектами.

   - Адаптер
   - Мост
   - Компоновщик
   - Декоратор
   - Фасад
   - Прокси

3. **Поведенческие паттерны**: заботятся об эффективной коммуникации между объектами.
   - Цепочка обязанностей
   - Команда
   - Итератор
   - Снимок
   - Состояние
   - Наблюдатель
     <br>
     <br>

### Полезный ресурс

https://refactoring.guru/design-patterns/typescript
