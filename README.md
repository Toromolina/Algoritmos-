# Algoritmos-
Tareas de diseño y análisis de algoritmos 
 
Programa 1 


function printTable(n) {
  for (let i = 1; i <= 10; i++) {
    console.log(`${n} x ${i} = ${n * i}`);
  }
}

printTable(5);

PROGRAMA 2

def calcularPi(n):
    pi = 0
    signo = 1
    numerador = 1
    denominador = 1

    for i in range(n):
        pi = pi + signo * (numerador / denominador)
        denominador = denominador + 2
        signo = signo * -1

    return pi * 4


n = int(input("Número de términos: "))

pi = calcularPi(n)

print("El valor aproximado de PI es:", pi)