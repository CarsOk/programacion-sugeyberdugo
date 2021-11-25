# Clase 18 de Noviembre

Hacer un programa que permita sumar, restar, multiplicar y dividir, teniendo en cuenta la opción seleccionada por el usuario.


## Programa

```
void main(){
    // Entrada por teclado. 1-Sumar 2-Restar 3-div 4-mul
    int respuestaUsuario = 1;

    // Entrada con números;
    double num 1 = 3;
    double num 2 = 5;

    if (respuestaUsuario == 1){
        double suma = num 1 + num 2;
        print('La respuesta es $suma');
    }else{
        if (respuestaUsuario == 2){
        double resta = num 1 - num 2;
        print('La respuesta es $resta');
    }else{
    if (respuestaUsuario == 3){
        double div = num 1 / num 2;
        print('La respuesta es $div');
    }else{
    if (respuestaUsuario == 4){
        double mul = num 1 * num 2;
        print('La respuesta es $mul');
    }else{
        print('La opción $respuestaUsuario no es la correcta');
        print("Seleccione opciones 1, 2, 3, o 4");
        }
    }
}
```


## Switch

Usar switch ayuda a simplificar el código y evita confusiones, ya que organiza en varias ramas el código que va a ser ejecutado.

Un ejemplo de como se escribe la sentencia switch sería el siguiente:

```
switch (variable)
{
    case valor1:
        instruccion1;
        break;
    case valor2:
        instruccion2;
        break;
    [default:]
    instruccion_default;
}
```
