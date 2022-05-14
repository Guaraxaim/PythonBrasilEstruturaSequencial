## Exercício 1
###  Faça um Programa que mostre a mensagem "Alo mundo" na tela.

def ola(nome):
    return f'Alo Mundo, {nome}!'

print(1, ola('João'))

## Exercício 2
### Faça um Programa que peça um número e então mostre a mensagem O número informado foi [número].
numero = input('Digite um número:')

print(2, f'O numero informado foi {numero}')

## Exercício 3
### Faça um Programa que peça dois números e imprima a soma.

def soma(a, b):
    return a + b

print(3, soma(1,2))

numero_1 = int(input('Digite um numero:'))
numero_2 = int(input('Digite outro numero:'))
soma = numero_1 + numero_2

print(4, f'A soma é igual a {soma}')

## Exercício 4
### Faça um Programa que peça as 4 notas bimestrais e mostre a média.

nota_1 = int(input('digite a nota do 1º bimestre:'))
nota_2 = int(input('digite a nota do 2º bimestre:'))
nota_3 = int(input('digite a nota do 3º bimestre:'))
nota_4 = int(input('digite a nota do 4º bimestre:'))

total = nota_1 + nota_2 + nota_3 + nota_4
media = total / 4

print(5, f'A media final foi {media}')

## Exercício 5
### Faça um Programa que converta metros para centímetros.

valor_metros = int(input('digite um valor em metros:'))

valor_centimetros = valor_metros * 1000

print(6, f'O valor em centímetros é {valor_centimetros}')

## Exercício 6
### Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.

raio = int(input('Digite um raio:'))

area = 3.14 * (raio * raio)

print(7, f'A área é igual a {area}')

## Exercício 7
### Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.

lado_quadrado = int(input('Quer saber o dobro da area de uma quadrado qualquer? então digite um lado:'))

dobro_area = 2* (lado_quadrado * lado_quadrado)

print(8, f'O dobro da área do seu quadrado é {dobro_area}')

## Exercício 8
### Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.

valor_hora = int(input('Quanto você ganha por hora?'))

horas_mes = int(input('Quantas horas você trabalha por mês?'))

salario = valor_hora * horas_mes
print(9, f'O salário neste mês é {salario}')

## Exercício 9
### Faça um Programa que peça a temperatura em graus Fahrenheit, transforme e mostre a temperatura em graus Celsius
### C = 5 * ((F-32) / 9)

far = int(input('Digite a temperatura em Fahrenheit:'))

celcius = 5 * ((far - 32) / 9)

print(10, f'A temperatura em celcius é {celcius}')

## Exercício 10
### Faça um Programa que peça a temperatura em graus Celsius, transforme e mostre em graus Fahrenheit.

celcius_1  = int(input('Informe a temperatura em celcius:'))

far = 1.8 * celcius_1 + 32

print(11, f'A temperatura em Fahrenheit é {far}')

## Exercício 11
### Faça um Programa que peça 2 números inteiros e um número real. Calcule e mostre:
#### a o produto do dobro do primeiro com metade do segundo .
#### b soma do triplo do primeiro com o terceiro.
#### c o terceiro elevado ao cubo.

inteiro_1 = int(input('Digite um número inteiro:'))
inteiro_2 = int(input('Digite outro número inteiro:'))
real = int(input('Digite um número real:'))

conta_1 = inteiro_1 * 2 * (inteiro_2)/2
conta_2 = (3 * inteiro_1) + real
conta_3 = real ** 3

print(12, f'O produto do dobro do primeiro com metade do segundo é {conta_1}')
print(13, f'Soma do triplo do primeiro com o terceiro é {conta_2}')
print(14, f'O terceiro elevado ao cubo. é {conta_3}')

## Exercício 12
## Tendo como dados de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, usando a seguinte fórmula:
### (72.7*altura) - 58

altura =float(input('Digite sua altura:'))

peso_ideal= (72.7 * altura) - 58

print(15, f'O peso ideal para sua altura é {peso_ideal}')

## Exercício 13
## Tendo como dado de entrada a altura (h) de uma pessoa, construa um algoritmo que calcule seu peso ideal, utilizando as seguintes fórmulas:
### Para homens: (72.7*h) - 58
### Para mulheres: (62.1*h) - 44.7


sexo = input('Informe seu sexo(M/F)')
h = float(input('Digite sua altura(em metros):'))

if (sexo == 'M' ):
    peso_homem = (72.7 * h) - 58
    print(16, f'Seu peso ideal é {peso_homem}')
else:
    peso_mulher = (62.1 * h) - 44.7
    print(17, f'Seu peso ideal é {peso_mulher}')

## Exercício 14
# João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de seu trabalho.
# Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado
# de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente.
# João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso.
# Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar.
# Imprima os dados do programa com as mensagens adequadas.

peso = int(input('Quantos quilos de peixe pegou? '))
peso_excedente = peso - 50
multa = 4 * (peso_excedente)
if peso > 50:
    print(18,f'Você pagará uma multa no valor de {multa} reais')
else:
    print(19, 'Você não pagará multa')

## Exercício 15
# Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês.
# Calcule e mostre o total do seu salário no referido mês, sabendo-se que são descontados 11% para
# o Imposto de Renda, 8% para o INSS e 5% para o sindicato, faça um programa que nos dê:
# salário bruto.
# quanto pagou ao INSS.
# quanto pagou ao sindicato.
# o salário líquido.
# calcule os descontos e o salário líquido, conforme a tabela abaixo:
# + Salário Bruto : R$
# - IR (11%) : R$
# - INSS (8%) : R$
# - Sindicato ( 5%) : R$
# = Salário Liquido : R$
# Obs.: Salário Bruto - Descontos = Salário Líquido.

valor_por_hora = int(input('Quanto você ganha por hora?'))
horas_no_mes = int(input('Quantas horas você trabalha por mês?'))
salario_bruto = valor_por_hora * horas_no_mes
ir = salario_bruto * 0.11
inss = salario_bruto * 0.08
sindicato = salario_bruto * 0.05
salario_liquido = salario_bruto - ir -inss - sindicato
print(20, f'Seu salário bruto é {salario_bruto} reais')
print(21, f'Você pagou ao inss {inss} reais')
print(22, f'Você pagou ao sindicato {sindicato} reais')
print(23, f'Seu salário liquido é {salario_liquido} reais')

## Exercício 16
# Faça um programa para uma loja de tintas.
# O programa deverá pedir o tamanho em metros quadrados da área a ser pintada.
# Considere que a cobertura da tinta é de 1 litro para cada 3 metros quadrados e
# que a tinta é vendida em latas de 18 litros, que custam R$ 80,00.
# Informe ao usuário a quantidades de latas de tinta a serem compradas e o preço total.
import math

area = int(input('Qual o tamanho em m2 da área a ser pintada?'))
litros_usado = area / 3
lata = 18
preco_lata = 80
lata_compradas = math.ceil(litros_usado / lata)
total = preco_lata * lata_compradas
print(24, f'Você usará {lata_compradas} lata(s) de tinta e gastará no total {total} reais')

## Exercício 17
# Faça um Programa para uma loja de tintas.
# O programa deverá pedir o tamanho em metros quadrados da área a ser pintada.
# Considere que a cobertura da tinta é de 1 litro para cada 6 metros quadrados e
# que a tinta é vendida em latas de 18 litros, que custam R$ 80,00 ou em galões de 3,6 litros,
# que custam R$ 25,00.

# Informe ao usuário as quantidades de tinta a serem compradas e os respectivos preços em 3 situações:
# comprar apenas latas de 18 litros;
# comprar apenas galões de 3,6 litros;
# misturar latas e galões, de forma que o desperdício de tinta seja menor.
# Acrescente 10% de folga e sempre arredonde os valores para cima, isto é, considere latas cheias.

import math

area_pintada = float(input('Qual o tamanho em m2 da área a ser pintada?'))
rendimento_por_litro = area_pintada / 6 * 1.1
lata_tinta = 18
galao = 3.6
preco_lata_tinta = 80
preco_galao = 25
quantia_latas = math.ceil( rendimento_por_litro / lata_tinta)
valor_em_latas = quantia_latas * preco_lata_tinta
print(25, f'Se você usar apenas latas de tinta, vai usar {quantia_latas} lata(s) e gastará {valor_em_latas} reais')

quantia_galao = math.ceil(rendimento_por_litro / galao)
valor_em_galoes = quantia_galao * preco_galao

print(26, f'Se você usar apenas galões de tinta, irá usar {quantia_galao} galão(galões) e gastará {valor_em_galoes} reais')

sobra_lata = rendimento_por_litro % lata_tinta
galoes_mistura = int(sobra_lata % galao  != 0)
lata_mistura = math.floor(rendimento_por_litro / lata_tinta) # uso do import math
gasto_latas = lata_mistura * preco_lata_tinta
gasto_galoes = galoes_mistura * preco_galao

gasto_total = gasto_latas + gasto_galoes

print(27, f'Para economia é recomendado comprar {lata_mistura} lata(s) e {galoes_mistura} galão(galões), no valor total de {gasto_total} reais')

## Exercício 18
# Faça um programa que peça o tamanho de um arquivo para download (em MB) e
# a velocidade de um link de Internet (em Mbps),
# calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos).

tamanho_arquivo = float(input("Qual o tamanho do arquivo para download?(em MB)"))
velocidade_link = float(input('Qual a velocidade do link da Internet?(em Mbps)'))
tamanho_bits = tamanho_arquivo * 1024 * 1024 * 8
tempo_download = tamanho_arquivo / ( velocidade_link * 1024 * 1024)
tempo_minutos = tempo_download / 60

print(28, f'O tempo de download é de {tempo_minutos} minutos')







