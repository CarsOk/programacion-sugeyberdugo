# Clase de programación

## Septiembre 13 del 2021

En esta última clase tratamos una temática nueva llamada "estructuras condicionales". El profesor planteó un ejemplo en visual basic, se realizó el respectivo diagrama de flujo, y se hizo la muestra en dart. 

A continuación se muestran los ejemplos dados en clase, y se muestra la actividad que fue asignada para poner en práctica lo aprendido:



### Ejercicio ejemplo Visual Basic

```
Sub ejemplo()
    n = Int(Inputbox("Escriba un numero"))
    If ( n > 10) Then

        MsgBox "El numero " & n & es mayor que 10"
    Else

    MsgBox "El numero" & n & es menor o igual a 10"

    End If
End Sub
```


### Ejercicio ejemplo Dart

```
void main(){
    int n = 4;

    if {n >10}{
        print{"el numero $n es mayor que 10"}
     }else{
         print{"el numero $n es menor que 10"}
}
```


### Algoritmo

```
Inicio
    Lea "Escriba un numero", n
    si n > 10 entonces
        escriba "El numero ", n, " Es mayor que 10"
    sino
        escriba "El numero ", n, "es menor o igual a 10"
    fin si
Fin
```

### Actividad práctica

Hacer un programa que calcule el promedio de 5 notas y le muestre un mensaje
al usuario indicando si el estudiante gano o no la asignatura. En el colegio se califica hasta 10 y se aprueba con un 7.

```
Sub calculanota()
    m = Int(InputBox("Por favor escriba primera nota"))
    p = Int(InputBox("Por favor escriba segunda nota"))
    g = Int(InputBox("Por favor escriba tercera nota"))
    h = Int(InputBox("Por favor escriba cuarta nota"))
    x = Int(InputBox("Por favor escriba quinta nota"))
    t = m + p + g + h + x
    k = t / 5
    If (k < 7) Then
        MsgBox "El estudiante reprobó con " & k & " como nota final "
    Else
        MsgBox "El estudiante aprobó con " & k & " como nota final "
    End If
```

### Diagrama de flujo

<img src="img/Diagrama 3.JPG" width="500">

