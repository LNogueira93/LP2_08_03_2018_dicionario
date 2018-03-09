agenda = {
    'Lucas':'5555-4444',
    'Ronaldo': 33334444,
    4: 'teste'
}

tam = len(agenda)

print(tam)

existe1 = 'Lucas' in agenda
existe2 = 33334444 in agenda
existe3 = 4 in agenda

print(existe1)
print(existe2)
print(existe3)

valores = agenda.values()
print(valores)

chaves = agenda.keys()
print(chaves)

items = agenda.items()
print(items)

for chave, valor in agenda.items():
    print('Nome: ', chave)
    print('Telefone: ', valor)

tel = agenda.get('Camila','Chave não existe\n')
print(tel)


#removendo
'''remover = input('Digite o nome para remover: ')
del agenda[remover]
print(agenda)
agenda.clear()
print(agenda)
'''
# agenda.get resumo as linhas a seguir
'''existe = 'Camila' in agenda
if existe:
    print(agenda['Camila'])
else:
    print('None')'''


# inserindo mais um telefone a um contato já existente
novoTel = input('Digite o telefone: ')

listaTel = agenda['Lucas']
listaTel.append(novoTel)
print(agenda)
