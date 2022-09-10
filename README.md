# valorcortecabelo

# Valores de cortes femininos no --Salão da Betinha--

print('- - - - - Bem-vinda(o) ao Salão da Betinha - - - - -')
tamanho = input('Qual o tamanho do teu cabelo?')

tamanho = 37
if tamanho <= 20:
    print('O valor do corte é R$50,00.')

elif tamanho >= 21 and tamanho <= 30:
    print('O valor do corte é R$70,00.')

elif tamanho >= 31 and tamanho <= 50:
    print('O valor do corte é R$100,00.')

else:
    print('Favor consultar na recepção.')
