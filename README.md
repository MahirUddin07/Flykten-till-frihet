# Flykten-till-frihet
Text spel.
print('Välkommen till våran textspel!')
name = input('Vad vill du ha för username?: ')
age = int(input('Hur gammal är du?: '))

if age >= 16:
    print('Du får börja spela!')
elif age < 16:
    print('Tyvärr kan ej spelas! ')

with open('Rum.txt', 'r') as file:
    lista = file.read().splitlines()

resmål = input('Vart vill du resa?: ')

if resmål == 'Rum1':
    for Rum1 in lista:
        print(Rum1)
else:
    print('Resmålet är inte känt.')



