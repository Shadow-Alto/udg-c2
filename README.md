# udg-c2


saldo = input("Cuanto es el saldo disponible?")
Transporte = 100
Comida = 150
Material_Escolar = 200
print("Tu gasto total es de", Transporte + Comida + Material_Escolar)
total = Transporte + Comida + Material_Escolar
Saldo_Resultante = int(saldo) - total
print("Tu saldo restante es de", Saldo_Resultante)

if Saldo_Resultante < 0:
    print("Ahorra mas en transporte camina mas ahorra mas. ")
elif Saldo_Resultante == 0:
    print("Tu saldo es justo, no te queda nada de dinero. ")
else:
    print("Tu saldo es suficiente, puedes gastar un poco mas. ")
