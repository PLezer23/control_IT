# Currency Converter / Конвертер Валют

**English version below.**

## Описание / Description

Это учебное приложение для конвертации валют с поддержкой истории операций.  
Проект написан на Python и демонстрирует использование различных концепций программирования:  
- Декораторы  
- Анонимные функции (lambda)  
- Работа с JSON  
- Модуль `datetime`, `time`

---

## Особенности / Features

- Конвертация между несколькими валютами (USD, RUB, EUR, GBR, CNY)
- Расчёт комиссии (2% от суммы)
- Бонус +10, если сумма превышает 1000
- Хранение истории операций в файле `history.json`
- Измерение времени выполнения операции

---

## Требования / Requirements

- Python 3.x
- Стандартные библиотеки: `json`, `time`, `datetime`

---

## Как использовать / How to Use

1. Запустите файл `main.py`
2. Выберите действие:
   - `1` — конвертировать валюту
   - `2` — посмотреть историю операций
3. Следуйте инструкциям в консоли

---

## Пример / Example
Выберите действие
Перевести валюту
История операций
1
Сколько USD вы хотите конвертировать?
100
Выберите валюту В КОТУРУЮ конвертировать (цифру):
USD
RUB
EUR
GBR
CNY
2
Время выполнения расчета: 1.00012 сек.
Результат: 7700.0 RUB
Комиссия: 154.0 RUB
Операция сохранена в историю.


---

## Структура проекта / Project Structure

├── main.py # Основной файл
├── history.json # Файл истории (создаётся автоматически)
└── README.md # Этот файл



---

# Currency Converter / Конвертер Валют

This is an educational currency converter application with transaction history support.  
The project demonstrates various Python concepts:  
- Decorators  
- Anonymous functions (lambda)  
- Working with JSON  
- Using `datetime`, `time` modules

---

## Features

- Conversion between multiple currencies (USD, RUB, EUR, GBR, CNY)
- Tax calculation (2% of the amount)
- Bonus +10 if the amount exceeds 1000
- Saving operation history to `history.json`
- Execution time measurement

---

## Requirements

- Python 3.x
- Standard libraries: `json`, `time`, `datetime`

---

## How to Use

1. Run `main.py`
2. Choose action:
   - `1` — convert currency
   - `2` — view history
3. Follow the prompts in the console

---

## Example
Choose an action
Convert currency
View history
1
How many USD do you want to convert?
100
Select the target currency (number):
USD
RUB
EUR
GBR
CNY
2
Execution time: 1.00012 sec.
Result: 7700.0 RUB
Tax: 154.0 RUB
Operation saved to history.


---

## Project Structure
├── main.py # Main file
├── history.json # History file (auto-generated)
└── README.md # This file
