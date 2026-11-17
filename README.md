for i in range (1, 4):
    nota = float(input(str("Digite a nota do aluno: ")))
    if (nota >= 7):
        print("Aprovado")
    elif (nota >= 5):
        print("Recuparação")
    else:
        print("Reprovado")
