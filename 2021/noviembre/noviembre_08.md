# Clase 08 de Noviembre

## While

El ciclo While o "mientras" tiene como propósito repetir un bloque de código mientras su condición sea "verdadera", de lo contrario, se detiene.

### Ejemplo

```
i = 1
While 1 <= 10
    MsgBox "Entró al ciclo"
    i = i + 1 
Wend
```

### Ejemplo 2

```
Sub prueba_ciclo()

    opcion = "S"
    While opcion = "S"

        a = Int(InputBox("Numero a sumar"))
        b = Int(InputBox("Segundo numero a sumar"))

        suma = a + b 
        MsgBox ("La suma es " & suma)

        option = InputBox("¿Quiere continuar S/N?")

    Wend

End Sub
```
#### Actividades 

1. Hacer suma que se detenga cuando sea menor a 1000
2. Flipgrid Ciclo While 01