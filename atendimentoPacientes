nome = input("Insira o nome: ")
idade = int(input("Insira a idade: "))
sexo=input("Insira o sexo: ").upper()
while sexo!="FEMININO" and sexo!="MASCULINO":
    print("Responda obrigatóriamente com MASCULINO ou FEMININO...")
    sexo=input("Insira o sexo: ").upper()
doenca_infectocontagiosa = input("Possui doença infectocontagiosa? - ").upper()
while doenca_infectocontagiosa != "SIM" and doenca_infectocontagiosa != "NAO":
    print("Responda a suspeita de doença apenas com SIM ou NAO!")
    doenca_infectocontagiosa = input("Possui doença infectocontagiosa? - ").upper()
if doenca_infectocontagiosa=="SIM":
    print("Encaminhar para a sala de quarentena imediatamente!")
    exit()
else:
    print("Encaminhar para a sala de espera!")
if idade>=65:
    print("Encaminhar para a sala prioritária!")
    exit()
if sexo=="MASCULINO" or idade<10:
    print("Pacinte não possui prioridade de atendimento!")
else:
    gravidez=input("Está grávida? - ").upper()
    while gravidez!="SIM" and gravidez!="NAO":
        print("Responda apenas com SIM ou NAO...")
        gravidez = input("Está grávida? - ").upper()
    if gravidez=="SIM":
        print("Pacinte possui prioridade de atendimento!")
    else:
        print("Pacinte não possui prioridade de atendimento!")
