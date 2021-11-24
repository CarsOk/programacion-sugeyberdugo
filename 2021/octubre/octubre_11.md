# Clase Octubre 11 del 2021

## Ciclos 

###  For

Se realiza revisión de programa que corre palabra diagonalmente. Se da la explicación de ambos códigos presentados por aprendices.

#### Código

```
Sub diag()
        b = "Hola"
     
        For u = 1 To 10
        
            ms.Cells(u, u) = b
            ms.Cells(u, u) = ""
        
            For cy = 1 To 20000000
            Next cy
            
         Next u
    
        For x = 9 To 1 Step -1
            ms.Cells(x + 1, 10) = ""
            ms.Cells(x, 10) = b
         
            For j = 1 To 10000000
            Next j
             
        Next x
    
        For t = 10 To 1 Step -1
         
            ms.Cells(1, t + 1) = ""
            ms.Cells(1, t) = b
        
            For thend = 1 To 10000000
            Next thend
                     
        Next t
        ms.Cells(1, 1) = ""
End Sub
````
           
En la próxima sesión se presentarán las opciones de otros aprendices faltantes. Y el nuevo tema acerca de "While". 

