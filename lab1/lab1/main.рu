# Личная визитка
# Платформонезависимая программа (Python 3)

import sys

def main():
    # Текущий год для расчёта возраста (можно заменить на системный)
    CURRENT_YEAR = 2026

    # Ввод данных
    name = input("Введите ваше имя: ")
    surname = input("Введите вашу фамилию: ")

    # Ввод года рождения с обработкой ошибок
    try:
        birth_year = int(input("Введите год рождения: "))
    except ValueError:
        print("Ошибка: нужно ввести целое число. Завершение программы.")
        sys.exit(1)

    # Ввод роста с обработкой ошибок
    try:
        height = float(input("Введите ваш рост (см): "))
    except ValueError:
        print("Ошибка: нужно ввести число. Завершение программы.")
        sys.exit(1)

    # Расчёт возраста
    age = CURRENT_YEAR - birth_year

    # Функция для вывода рамки
    def print_separator():
        print("*" * 42)

    # Вывод визитки
    print_separator()
    print("*{:*^40}*".format(" ЛИЧНАЯ ВИЗИТКА "))
    print_separator()
    print(f"* Имя: {name:<34}*")
    print(f"* Фамилия: {surname:<31}*")
    print(f"* Год рождения: {birth_year:<26}*")
    print(f"* Возраст: {age:<31}*")
    print(f"* Рост: {height:<34}*")
    print_separator()

if __name__ == "__main__":
    main()
