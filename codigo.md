# Proyecto de programacion
--- 
    def longitud():
    while True:
        print("\n*** Conversión de Longitud ***")
        print("1. Metros a Centímetros y Pulgadas")
        print("2. Centímetros a Metros y Pulgadas")
        print("3. Pulgadas a Metros y Centímetros")
        print("4. Volver al menú principal")
        
        opcion = input("\nSeleccione una opción: ")

        if opcion == '1':
            metros = float(input("Ingrese la longitud en metros: "))
            print("Centímetros:", metros * 100)
            print("Pulgadas:", metros * 39.3701)
        elif opcion == '2':
            centimetros = float(input("Ingrese la longitud en centímetros: "))
            print("Metros:", centimetros / 100)
            print("Pulgadas:", centimetros / 2.54)
        elif opcion == '3':
            pulgadas = float(input("Ingrese la longitud en pulgadas: "))
            print("Metros:", pulgadas * 0.0254)
            print("Centímetros:", pulgadas * 2.54)
        elif opcion == '4':
            break
        else:
            print("Opción no válida. Por favor, seleccione una opción válida.")

    def volumen():
    while True:
        print("\n*** Conversión de Volumen ***")
        print("1. Litros a Mililitros")
        print("2. Mililitros a Litros")
        print("3. Galones a Litros")
        print("4. Litros a Galones")
        print("5. Volver al menú principal")
        
        opcion = input("\nSeleccione una opción: ")

        if opcion == '1':
            litros = float(input("Ingrese el volumen en litros: "))
            print("Mililitros:", litros * 1000)
        elif opcion == '2':
            mililitros = float(input("Ingrese el volumen en mililitros: "))
            print("Litros:", mililitros / 1000)
        elif opcion == '3':
            galones = float(input("Ingrese el volumen en galones: "))
            print("Litros:", galones * 3.78541)
        elif opcion == '4':
            litros = float(input("Ingrese el volumen en litros: "))
            print("Galones:", litros / 3.78541)
        elif opcion == '5':
            break
        else:
            print("Opción no válida. Por favor, seleccione una opción válida.")

    def temperatura():
    while True:
        print("\n*** Conversión de Temperatura ***")
        print("1. Celsius a Fahrenheit y Kelvin")
        print("2. Fahrenheit a Celsius y Kelvin")
        print("3. Kelvin a Celsius y Fahrenheit")
        print("4. Volver al menú principal")
        
        opcion = input("\nSeleccione una opción: ")

        if opcion == '1':
            celsius = float(input("Ingrese la temperatura en Celsius: "))
            print("Fahrenheit:", celsius * 9/5 + 32)
            print("Kelvin:", celsius + 273.15)
        elif opcion == '2':
            fahrenheit = float(input("Ingrese la temperatura en Fahrenheit: "))
            print("Celsius:", (fahrenheit - 32) * 5/9)
            print("Kelvin:", (fahrenheit + 459.67) * 5/9)
        elif opcion == '3':
            kelvin = float(input("Ingrese la temperatura en Kelvin: "))
            print("Celsius:", kelvin - 273.15)
            print("Fahrenheit:", kelvin * 9/5 - 459.67)
        elif opcion == '4':
            break
        else:
            print("Opción no válida. Por favor, seleccione una opción válida.")

    def velocidad():
    while True:
        print("\n*** Conversión de Velocidad ***")
        print("1. Kilómetros por hora a Metros por segundo")
        print("2. Metros por segundo a Kilómetros por hora")
        print("3. Millas por hora a Kilómetros por hora")
        print("4. Kilómetros por hora a Millas por hora")
        print("5. Volver al menú principal")
        
        opcion = input("\nSeleccione una opción: ")

        if opcion == '1':
            kph = float(input("Ingrese la velocidad en kilómetros por hora: "))
            print("Metros por segundo:", kph / 3.6)
        elif opcion == '2':
            mps = float(input("Ingrese la velocidad en metros por segundo: "))
            print("Kilómetros por hora:", mps * 3.6)
        elif opcion == '3':
            mph = float(input("Ingrese la velocidad en millas por hora: "))
            print("Kilómetros por hora:", mph * 1.60934)
        elif opcion == '4':
            kph = float(input("Ingrese la velocidad en kilómetros por hora: "))
            print("Millas por hora:", kph / 1.60934)
        elif opcion == '5':
            break
        else:
            print("Opción no válida. Por favor, seleccione una opción válida.")

    def masa():
    while True:
        print("\n*** Conversión de Masa ***")
        print("1. Kilogramos a Gramos")
        print("2. Gramos a Kilogramos")
        print("3. Libras a Kilogramos")
        print("4. Kilogramos a Libras")
        print("5. Volver al menú principal")
        
        opcion = input("\nSeleccione una opción: ")

        if opcion == '1':
            kg = float(input("Ingrese la masa en kilogramos: "))
            print("Gramos:", kg * 1000)
        elif opcion == '2':
            gramos = float(input("Ingrese la masa en gramos: "))
            print("Kilogramos:", gramos / 1000)
        elif opcion == '3':
            libras = float(input("Ingrese la masa en libras: "))
            print("Kilogramos:", libras * 0.453592)
        elif opcion == '4':
            kg = float(input("Ingrese la masa en kilogramos: "))
            print("Libras:", kg / 0.453592)
        elif opcion == '5':
            break
        else:
            print("Opción no válida. Por favor, seleccione una opción válida.")

    def area():
    while True:
        print("\n*** Conversión de Área ***")
        print("1. Metros cuadrados a Pies cuadrados")
        print("2. Pies cuadrados a Metros cuadrados")
        print("3. Acres a Metros cuadrados")
        print("4. Metros cuadrados a Acres")
        print("5. Volver al menú principal")
        
        opcion = input("\nSeleccione una opción: ")

        if opcion == '1':
            metros_cuadrados = float(input("Ingrese el área en metros cuadrados: "))
            print("Pies cuadrados:", metros_cuadrados * 10.7639)
        elif opcion == '2':
            pies_cuadrados = float(input("Ingrese el área en pies cuadrados: "))
            print("Metros cuadrados:", pies_cuadrados / 10.7639)
        elif opcion == '3':
            acres = float(input("Ingrese el área en acres: "))
            print("Metros cuadrados:", acres * 4046.86)
        elif opcion == '4':
            metros_cuadrados = float(input("Ingrese el área en metros cuadrados: "))
            print("Acres:", metros_cuadrados / 4046.86)
        elif opcion == '5':
            break
        else:
            print("Opción no válida. Por favor, seleccione una opción válida.")

    def main():
    while True:
        print("\n*** Menú Principal ***")
        print("1. Conversión de Longitud")
        print("2. Conversión de Volumen")
        print("3. Conversión de Temperatura")
        print("4. Conversión de Velocidad")
        print("5. Conversión de Masa")
        print("6. Conversión de Área")
        print("7. Salir")
        
        opcion = input("\nSeleccione una opción: ")

        if opcion == '1':
            longitud()
        elif opcion == '2':
            volumen()
        elif opcion == '3':
            temperatura()
        elif opcion == '4':
            velocidad()
        elif opcion == '5':
            masa()
        elif opcion == '6':
            area()
        elif opcion == '7':
            print("¡Hasta luego!")
            break
        else:
            print("Opción no válida. Por favor, seleccione una opción válida.")

     if __name__ == "__main__":
    main()









