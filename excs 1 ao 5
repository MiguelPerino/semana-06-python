def gravar_frase(frases: list):
    with open('frases.txt', 'w') as arquivo:
        for i in range(len(frases)):
            arquivo.write(frases[i] + '\n')
frase = []

while True: 
    r = input()
    if r == "sair":
        break
    else:
        frase.append(r)

gravar_frase(frase)

frase = input('Digite uma frase: ')

################################
def gravar_matriz(mat: list):
    with open('matriz.txt', 'w') as arquivo:
        for i in range(len(mat)):
            for j in range(len(mat[0])):
                arquivo.write(str(mat[i][j]) + "; ")
            arquivo.write("\n")

def mat_ident(matriz: list) -> list:
    lista = []
    for i in range(len(matriz)):
        lista.append(matriz[i][i])
    return lista

mat = [[1, 2, 3], [4,5,6], [7,8,9]]

print(mat_ident(mat))
gravar_matriz(mat)
######################################

with open('frases.txt', 'r') as arquivo:
    conteudo = arquivo.read()
    print(f'Conteúdo do arquivo:\n{conteudo}')

with open('frases.txt', 'r') as arquivo:
    linhas = arquivo.readlines()
    total_linhas = len(linhas)
    print(f'Total de linhas {total_linhas}')

with open('frases.txt', 'r') as arquivo:
    conteudo = arquivo.read()
    palavra = input('Digite uma palavra para procurar no arquivo: ')
    if palavra in conteudo:
        print(f'"\033[31m{palavra}\033[0m" aparece no arquivo')
    else:
        print('Palavra não encontrada!')

with open('frases.txt', 'r+') as arquivo:
    linhas = arquivo.readlines()

with open('frases2.txt', 'w') as frase2:
    for i in range(len(linhas)):
        if linhas[i].strip():
            frase2.write(linhas[i])

            
