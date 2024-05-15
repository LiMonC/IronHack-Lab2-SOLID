# IronHack-Lab2-SOLID

What the issue was.
Which SOLID principle it violated.
How your change addresses this violation.
The benefits your changes bring to the system’s architecture.


1. What the issue was.
   El problema deriva de la modificación de la función si se requiere un nuevo tipo de orden
   ![tipo de orden](screens/1.png)
    
2. Which SOLID principle it violated.
   Open/close
3. How your change addresses this violation.
  Se crean enums de los orden types y se modifica la función para procesar orden la cual implementa varios metodos en función del tipo de orden.
 ![imagen](screens/2.png)
 ![imagen](screens/3.png)
4. The benefits your changes bring to the system’s architecture.
   Menos dependencia y desacoplamiento
