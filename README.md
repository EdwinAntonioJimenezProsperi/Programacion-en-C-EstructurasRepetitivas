# Programacion-en-C-EstructurasRepetitivas
Aprenderás los 3 tipos de ciclos repetitivos en el lenguaje C
 
#include <stdio.h>
#include <stdlib.h>

int main()
{ 
    int x,i=1;//definimos el tipo de dato de las variables a utilizar
    La cual son de tipo entero ya que manipular numeros enteros.
    printf("ingrese un numero entero: ");//le pido un numero al usuario 
    scanf("%d",&x);//lo almacenó en la dirección de memoria de la variable x con el tipo
    //tipo de dato entero
    while(i<=x){ //este ciclo es conocido como mientras hacer porque se ejecuta
      printf("%d\t",i);//siempre y cuando la condición sea verdadera
      i++;//siempre debemos asegurarnos que el ciclo termine y no sea infinito 
    }//el cual lo hacemos mediante un acumulador que nos da el numero de veces a repetirse
     //y este siempre ira cambiando su valor en el ciclo.
    return 0;
}
