# Prueba de tester
1.  Línea 41(index original): se finaliza el body </body>, lo cual esta mal ya que este se debe cerrar al finalizar todo el script.
2.  Línea 44(index original): Se modifico la función para elegir el número aleatorio (Math.random() * 10;), se modifico por             
    (Math.floor(Math.random() * 100) + 1;) donde se agregaron los parametros establecidos.
3.  Línea 46(index original): Se modifico la constante ATTEMPS, el cual tiene el número máximo de intentos, anteriormente tenía 5, 
    se modifico a 10 (ATTEMPS = 10);
4.  Línea 58(index original): Se modificaron los parametros que recibe userGuess, ya que este primero se debe convertir a un numero, por lo tanto       se utilizo let userGuess = Number(guessField.value);
5.  En la línea 61 del index modificado se agrego una condicional la cual al momento de ser verdadera, muestra una alerta indicando que el número
    ingresado esta fuera de los parametros establecidos
6.  Línea 64-81(index original): Se analizaron las condicionales y se encontraron deficiencias, ya que no estaban bien estructuradas por lo cual no     funcionaban correctamente, se modificaron los if con los parametros establecidos en las instrucciones.
7.  Línea 64-81(index original): mostraba los colores especificados de manera incorrecta, y ya con las condicionales funcionando correctamente se       agregaron los colores requeridos correctamente.
8.  Línea 77 y 79(index original): se modificaron los mensajes que se mostraban ya que estos pueden llegar a confundir a los usuarios.
9.  Línea 88(index modificado): Se añadio una condicional para incrementar el "guessCount" ya que si el usuario ingresa un número fuera de los          parametros requeridos este no se debe incrementar.
    
    if (userGuess > 0 && userGuess < 101) {
        guessCount++;
      }
      
10. Línea 98(index modificado): Se agregó la función alerta_numb la cual contiene el mensaje de alerta a mostrar cuando no se cumplan los               parametros establecidos.
11. Línea 94(index original): Se modifico el appendChild por append ya que este se utiliza para agregar un elemento en forma de objeto.
12. Línea 114(index original): se modifico la función para elegir el número aleatorio (Math.random() * 10;), se modifico                                por(Math.floor(Math.random() * 100) + 1;) donde se agregaron los parametros establecidos.
13. Línea 132 (index modificado): se cerró el body correctamente.
