# Запуск тестов в Allure
Настраиваем Allure зависимости (см. коммит)
1. В терминале: ./gradlew clean test
2. В терминале: ./gradlew allureserve
3. Открываем хром. ВСЁ!
4. Смотрим всю нужную информацию по тестам

[Документация по Allure](https://docs.qameta.io/allure-report/)

# Домашнее задание к занятию «4.1. Репортинг»

## Задача №1: проснулись (Allure)

В одном из предыдущих проектов [Patterns](https://github.com/netology-code/aqa-homeworks/tree/master/patterns) вы тестировали функциональности заказа карт.

Ваше руководство узнало на конференции про такой замечательный инструмент, как Allure, который позволяет делать репортинг более наглядным и требует от вас интегрировать его в ваши тесты.

Начать решили именно с функции доставки карт:

Вам нужно: взять ваш проект (см. «Как сдавать задачи») и прикрутить туда Allure, интегрированный с Selenide. Удостоверьтесь, что при локальном запуске всё работает, отчёты генерируются, скриншоты прикрепляются, и вы можете их посмотреть через Allure.
