# Exercicio020.py
#Faça um programa que leia o nome dos quatro alunos e mostre a ordem sorteada.

import random
n1 = input('digite um nome: ')
n2 = input('digite um nome: ')
n3 = input('digite um nome: ')
n4 = input('digite um nome: ')
lista = [n1, n2, n3, n4]
random.shuffle(lista)
print('A ordem de apresentação sera: ')
print(lista)
