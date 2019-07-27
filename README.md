import random
d=random.uniform(0, 100)
print(d)
n=input('Это ваше число?: ')
if n == 'Нет':
    v=input('Оно больше или меньше?: ')
    if v == 'Больше':
        i=random.uniform(d, 100)
    if v == 'Меньше':
        i=random.uniform(0, d)
else n == 'Да':
    print('Хех, это было изи!!')
