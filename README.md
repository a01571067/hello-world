## hello-world
# Luis Alberto Padrón Gómez
## Laboratorio - branch - commmit - pull request - merge - markdown

**BOLD TEXT**

*Italic*

1. Github
2. Metodo de calcular las frecuencias
3. Descargar los nuevos archivos de Series y Episodios

- First item
- Second item
- Third item

 `
#include <iostream>
#include <math.h>

using namespace std;

int main()
{
    // Comentario de una línea
   std::cout << "Hello Michele, Diego\nHola"  << endl; 
   //Declaración de variables
   int numero, contador;
   string palabra; // delimitado con " "
   
   cout << "Division entera 1/2 = " << 1 / 2 << endl;
   cout << "Division con decimales 1/2" << 1.0/ 2 << endl;
   
   // usar la funcion de la libreria math
   cout << "pow(5,3) = " << pow(5,3) << endl;
   
   // Operadores lógicos y relacionales
   cout << "5 != 5 = " << (5 != 5) << endl;
   cout << "5 == 5 = " << (5 == 5) << endl;
   cout << "(5 >= 1) && (5 <= 10) = " << ((5 >= 1) && (5 <= 10)) << endl;
   cout << "(5 >= 1) || (5 <= 10) = " << ((5 >= 1) || (5 <= 10)) << endl;

   
   //Leer los datos de entrada
   cout << "\nDame un número: ";
   cin >> numero;
   cout << "\nDame una palabra: ";
   cin >> palabra;
   
   //Desplegar los datos de salida
   cout << "\nEl numero es " << numero << 
   " y la palabra es " << palabra << endl;
   
   //Condicionales
    if (numero < 0)
        cout << "El numero es negativo" << endl;
    else if (numero == 0)
        cout << "El número es cero" << endl;
    else 
        cout << "El número es positivo" << endl;
        
    //Ciclo For - ciclo contador - creciente 1:10
    for(int contador = 1; contador <= 10; contador++){
        cout << "contador = " << contador << endl;
        cout << "Iván, Dan, Eduardo, Alejandro\n";
    }
    // Ciclo for deccreciente
    for(int contador = 10; contador >= 1; contador--){
        cout << "contador = " << contador << endl;
        cout << "Iván, Dan, Eduardo, Alejandro\n";
    }
    // Ciclo while
    contador = 1;
    while (contador <= 10){
        cout << contador << endl;
        contador ++;
    }
   return 0;
}`
  
---
[Never gonna give you up](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
![Rick Astley](image.jpg)
