# Конвертер чисел в слова

Данный проект преобразует целое число в его текстовое представление на русском языке.

## Содержание
- [Описание](#описание)
- [Установка](#установка)
- [Использование](#использование)
- [Тестирование](#тестирование)

## Описание

- Конвертер преобразует положительные и отрицательные числа в слова на русском языке.
- Поддерживаются числа от -999 999 999 до 999 999 999.
- Корректно обрабатываются падежи чисел, таких как "миллион", "тысяча" и их формы.

## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/yourusername/Num_In_Word.git

2. Перейдите в папку проекта:
    ```bash
    cd number_to_words

## Использование

- Для запуска конвертера выполните следующую команду:
    python number_to_words.py
- Введите число, и программа преобразует его в текст на русском языке.

## Тестирование

- Чтобы запустить тесты, выполните:
    python -m unittest test_number_to_words.py
- Тесты проверяют работу программы на различных числовых диапазонах — от единиц до миллионов, а также на крайних значениях, таких как ноль и отрицательные числа.
