#Calculadora Basica

Nombre = input("Nombre : ") # Declaramos una variable Nombre para ingresar un nombre.
print ("********","Hola ",Nombre, "*********") # Imprimimos el nombre.

# Menu realizado con print. 
print ("Ingrese un numero para seleccionar un literal")
print ()
print ("1. Sumar")
print ("2. Restar")
print("3. Multiplicar")
print ("4. Dividir")

# Declaramos una variable de tipo entero para seleccionar un literal.
opcion = int (input ("Ingrese el literal : "))
print()

#Usamos una condicion para identificar el literal y a si pueda llenar los valores A y B para realiazar su operacion selecionada.
while(opcion > 0 and opcion <5 ):
    A = float (input("Ingresa un numero para A : "))
    B = float (input("Ingresa un numero para B : "))
    
    #Usamos una condicion If para realizar la suma. 
    if(opcion == 1):
        print("La suma Total es : ", A + B)
        opcion = int (input("Selecione otra opcion : ")) 
   
    #Usamos una condicion If para realizar la resta.     
    if(opcion == 2):
        print("La resta Total es : ", A - B)
        opcion = int (input("Selecione otra opcion : ")) 
   
    #Usamos una condicion If para realizar la multiplicacion.    
    if(opcion == 3):
        print("La maltiplicacion es : ", A * B )
        opcion = int (input("Selecione otra opcion : "))  
  
    #Usamos una condicion If para realizar la divicion.
    if(opcion == 4):
        print("La divicion es : ", A / B)
        opcion = int (input("Selecione otra opcion"))
       
