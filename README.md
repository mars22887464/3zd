print('*')
print('**')
print('***')
print('****')
print('*****')
print('******')
print('*******')


a = int(input())
b = int(input())
c = int(input())
print(a + b + c)
x = 5
y = 3
print(str(x)+'+'+str(y)+'=?')
print(str(x)+'|'+str(y)+'|'+str(8))
print(('Z(' + str(x) + ')' + '=' + 'F(' + str(y) + ')'))
print('x='+str(x)+';'+str(y)+';')
print('Ответ'+':'+'('+str(x)+';'+str(y)+')')


name = input()
age = int(input())
year = 100 - age
yeartd = 2022 + year
print('{}, 100 лет вам исполнится в {} году'.format(name,yeartd))


n = int(input('Введите чиало n (1≤n≤9):'))
a = str(n) + str(n)
b = str(n) + str(n) + str(n)
c = n + int(a) + int(b)
print(c)

name = input('Имя клиента:')
voucher = input('Количество купленных ранее туров:')
tour = input('Предлагаемый тур:')
print('Имя клиента:{} Количество купленных путёвок:{} Предлагаемая путевка:{} Здравствуйте Вы путешествовали с нами уже {vou} раз(а)! Хотите снова? Наша турфирма проводит распродажу. Тур в {to} со скидкой 50%'.format(name,voucher,tour,vou=voucher,to=tour))
