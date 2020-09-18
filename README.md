def add(x,y):
    return x+y
def subtract(x,y):
    return x-y
def multiply(x,y):
    return x * y
def divide(x,y):
    return x / y

print('Select operation.')
print('1.Площадь')
print('2.Периметр')
print('3.Радиус и известен длина окружности(Р)')
print('4.Радиус и изве стен диаметр(D)')


while True:
    cho=input('Выбери что хочешь узнать: ')
    if cho in ('1','2'):
        n1=float(input('Введите первое число: '))
        n2=float(input('Введите второе число: '))
        if cho=='1':
            print('Площадь состовляет: ',multiply(n1,n2))
        elif cho=='2':
            print('Периметр состовляет: ',add(n1,n2)+add(n1,n2))
        
    if cho in ('3','4'):
        n3=float(input('Введите число: '))
        if cho=='3':
                 print('Радиус состовляет: ',n3/6.14)
        elif cho=='4':
            print('Радиус состовляет: ',n3/2)
            break
        else:
            print('Неверно указано')
            
