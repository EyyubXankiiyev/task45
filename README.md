#task 1

print('1.Daxil edilen a,b tereflerine gore duzbucaqlinin sahesini tapin')

a = int(input('a-ni daxil et:'))
b = int(input('b-ni daxil et:'))

print(f'sahe[]={a*b}')


#task 2

print('2.Daxil edilen 1 ci eded 2 ci ededden boyukdurse true kicikdirse false cixartsin (if istifade etmek olmaz)')

c = int(input('c-ni daxil et:'))
d = int(input('d-ni daxil et:'))

print(c>d)

#task 3

print('3.İstifadəçi flaş drive-ın gigabayt ilə ölçüsünü daxil edir. 760 Megabaytlıq kinonun həmin flaşa neçə dəfə yerləşəcəyini tapan program yazın.')


gb = int(input('gb-ni daxil et:'))
print(round(gb*1024/760))

#task 4

print('4.İstifadəçi a və b-ni daxil edir, ax+b=0 tənliyini hesablayıb x-i tapan proqram yazın.')


e = int(input('a-ni daxil et:'))
f = int(input('b-ni daxil et:'))
d = int(0-f)
g = int(d/e)
print(f'{e}x+{f}=0  0-{f}={d} x={e}/{d} x={g} ')


#task 5

print('5.İki rəqəm daxil edilir, onların ədədi ortasını tapan proqram yazın.')


x = int(input('a-ni daxil et:'))
y = int(input('b-ni daxil et:'))
z =int((x+y)/2)

print(f'{x} ve {y} ededlerinin ortasi {z}-dir ')

# bonus task 6

print('6.Istifadəçi 5 rəqəmli num daxil edir, onun polindrom olub olmamasını yoxlayan proqram yazın Polindrom odur ki tərsi və düzü eyni olsun məsələn 12321 1234321')



import math

t = int(input('eded daxil et:'))
u = len(str(t))
if u == 5:
    k= t % 10
    k2= t//10 %10
    k3= t//100 %10
    k4= t//1000 %10
    k5= t//10000

    if k==k5 and k2 == k4 :
        print (' eded plidrom dur')
    

else:
    print ('5 reqemle deyil')




