# Домашнее задание к лекции 1. «Import. Module. Package»

1. Разработать **структуру** программы «Бухгалтерия»:
- main.py;  
- application/salary.py;  
- application/db/people.py.

Main.py — основной модуль для запуска программы.  
В модуле salary.py функция calculate_salary.  
В модуле people.py функция get_employees.  

2. Импортировать функции в модуль main.py и вызывать эти функции в конструкции.
```
if __name__ == '__main__':
```
**Сами функции реализовывать не нужно**. Достаточно добавить туда какой-либо вывод.

3. Познакомиться с модулем [datetime](https://pythonworld.ru/moduli/modul-datetime.html). 
При вызове функций модуля main.py выводить текущую дату.

4. Найти интересный для себя пакет на [pypi](https://pypi.org/) и в файле requirements.txt указать его с актуальной версией. Установили pandas==2.2.0


