# CALCULADORA BÁSICA CON MENU

Una calculadora básica se puede realizar con condiciones. Se desea realizar alguna de las operaciones básicas con dos números `x, y`. Además se desea calcular la potencia y el logaritmo. Se deben de considerar los casos donde `y= 0` donde la división `x/y` NO se puede realizar y cuando `x<= 0` donde NO se puede calcular el `log(x)`. Se desea generar un menú para que el usuario pueda seleccionar la operación a realizar. Una manera de hacerlo es la siguiente:

1. Se reciben los dos números `x, y` para realizar la operación.
2. Se  recibe la operación a realizar mediante la variable `opción` la que selecciona en el menú qué operación ejecuta el algoritmo.
3. Se inicializa la variable lógica `bandera = False`. Si la división o el logaritmo no se pueden calcular, se hace `bandera = True`.
4. Mediante condiciones se realiza la operación deseada.
      * En el caso de la divión, si `y = 0` NO se puede realizar hace `bandera = True`.
      *En el caso del logaritmo, si `x <= 0`, NO se puede calcular el logaritmo, se muestra un mensaje y se hace `bandera = True`.
 5. Se muestra el resultado en el caso en que `bandera = False`.

 *Tomado de: Python con aplicaciones a las matemáticas, ingeniería y fianzas. Cervantes 0, Baez D.*