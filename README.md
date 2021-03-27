# PRACTICA2.1
#nombre:mario jimenez arreola
#carrera:ing informatica
#materia: desarrollo de aplicaciones web 
#ejercicio o practica:2.1 votos

print("elige un candidato entre A,B,C")
candidato=input("CANDIDATO ELEGIDO: ")
if candidato.upper()=="A":
    print("Usted a votado por el partido amarillo")
elif candidato.upper()=="B":
    print("Usted a votado por el partido morado")
elif candidato.upper()=="C": 
    print("Usted a votado por el partido rojo")
else:
    print("opcion erronea")  
