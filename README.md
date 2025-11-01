# Шашки

## О проекте

Игра в шашки на Python с использованием библиотеки Pygame. Проект реализует классические правила шашек для игры двух игроков на одном компьютере. Разработан в учебных целях для демонстрации навыков программирования и работы с графическими интерфейсами.

## Функциональность

* Игровая доска с визуализацией
* Ходы шашек и дамок
* Взятие фигур противника
* Превращение в дамку
* Проверка корректности ходов
* Определение победителя

## Требования

* Python 3.8+
* Зависимости: `pygame`, `numpy`, `pytest` (см. requirements.txt)

## Установка

```bash
git clone https://github.com/FentanyllTester/FentanyllTester.git
cd your-username
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

## Запуск
bash
python main.py

├── checkers/
│   ├── constants.py    # Настройки и константы
│   ├── piece.py        # Класс шашки
│   ├── board.py        # Игровая доска
│   └── game.py         # Логика игры
├── main.py             # Точка входа
└── requirements.txt    # Зависимости
