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
