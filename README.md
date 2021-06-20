# comparacao_de_frases
Compara se em uma frase ou conjunto de char possui uma palavra ou letra

cidade = str(input('Em qual cidade voce nasceu? ')).strip()
# Variável cidade recebe str (string). o final a função strip para eliminar os possíveis espaços vazios.

print(cidade[:5].upper() == 'SANTO')
# variavel cidade com a cadeia de caracters com início desconhecido até o 5 co upper para alterar tudo para maísculo
# com isso comapara com o caracter maísculo para tratar erros ao entrar com maísculos oou minúsculos.
