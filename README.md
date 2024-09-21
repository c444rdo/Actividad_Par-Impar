# Actividad_Par-Impar
# Martínez Estrada Ricardo

print("Martínez Estrada Ricardo")
print("Programa que calcula si un número es par, impar o equivalente a 0")
print(" ")

# Solicitar al usuario el valor del número y conversión del valor del número 1, caracter a entero.
numero1 = input("Ingrese un número del 1 al 10: ")
num1 = int(numero1)

# Asignar valores para par, impar o equivalencias.
a = [2, 4, 6, 8, 10]   
b = [1, 3, 5, 7, 9]   
c = 0  

# Verificar si es par, impar o equivalente a 0.
if num1 in a:
    print("El número es par")
elif num1 in b:
    print("El número es impar")
elif num1 == c:
    print("El número es equivalente a 0")
else:
    print("El número está fuera del rango permitido.")

![image](https://github.com/user-attachments/assets/9009f15c-1ac6-4230-bfe3-f5dbddbe175e)
