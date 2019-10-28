# calculator
from colorama import init
from colorama import Fore, Back, Style
init()
print(Back.GREEN)
print(Fore.BLACK)
what = input('Что делаем? (+,-,/,*,**):')
print(Back.CYAN)
print(Fore.BLACK)
a = float(input('Введите первое число: '))
b = float(input('Введите второе число: '))
print(Back.RED)
print(Fore.BLACK)
if what == '+':
    c = a + b
    print('Результат:' + str(c))
elif what == '-':
    c = a - b
    print('Результат:' + str(c))
elif what == '/':
    c = a / b
    print('Результат:' + str(c))
elif what == '*':
    c = a * b
    print('Результат:' + str(c))
elif what == '**':
    c = a * b
    print('Результат:' + str(c))
else:
    print('Выбрана неверная операция!')
input()
