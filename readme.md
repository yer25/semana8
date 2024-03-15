
<!-- CONCEPTO  -->

1. el Js MODERNO (ES6) es el que daremos uso.
2. Con un 'console.log' desde el visual o la misma consola del navegador podemos escribir un 'holamundo'.

<!-- VARIABLES (var, let, const)-->

2. las variables con var se pueden volver a declarar o modificar. Ademas permite crear una variable sin definirse.
3. las variables con let se pueden modificar pero no se puede volver a declarar. Tambien permite crear una variable sin definirse.
4. las variables const no permiten modificarse, ni declararse, tampoco permite crear una variable sin definirse.

<!-- STRING -->


1.  La diferencia entre propiedad y metodo es que, la propiedad lleva un (.length). Mientras que el metodo se compone de un parentesis (.trim()).


2. La propiedad length permite contar cuantos caracteres existe incluyendo los espacios.

3.  cuando aplicamos el metodo trim cuenta solo los caracteres y ya no cuenta los espacios que existen al inicio y al final de los caracteres.

4. el metodo (trim().toUpperCase) permite convertir a los caracteres en letras mayusculas.


5. el metodo (trim().toLowerCase()) permite convertir los caracteres en letras minusculas.

<!-- NUMBERS (+ - * / %)  --> 
Los operadores matematicos se hacen presentes y son 
suma, resta, multiplicacion, division. 
Ademas el (%) se usa para hallar el residuo de una division. 

El JS respeta el proceso jerarjico de las matematicas. 

1. en las aproximaciones de numeros tenemos a las siguientes propiedades
   1.1 result = Math.round(2.4);
       Con esta propiedad podemos redondear como usualmente lo hacemos, redondeo humano.
        2.5= 3
        3.7 = 4
   
   1.2 result = Math.floor(2.9);
        Con esta propiedad podemos redondear de esta manera.
         2.9 = 2
         7.8 = 7
   
   1.3 result = Math.ceil(2.1);

        4.2= 5
        5.1= 6
   1.4  result = Math.random();
         Esta propiedad te da un valor entre el 0 y el 1.



   <!-- PARSEO NUMBERS-->

    El parseInt convierte en numero entero.
     
   El (+) en js puede sumar y/concatenar.

   DATO: Solo se puede parsear a los string que pueden ser numeros
      ejemplo
       const = number1 = 30;
       const = number2 = '50';
       const = number3 = 'ten';

       console.log(number1 + Number.parseInt(number2));

<!-- INCREMENTO Y DECREMENTO -->
Incremento= ++;
Decremento= --;
 
 Para aumentar por ejemplo de 5 en 5 realizamos:
  result += 5;
  result += 5;
  result += 5;


  <!-- COMPARACIONES -->
  Usamos >,<, ==, ===
 console.log(10 > 5);
 console.log(10 < 3);
 console.log(10 >= 50);

  console.log(50 == '50'); En esta comparacion se obtendria 'true' ya que ambos tienen el mismo valor de 50.
  
  console.log(50 === '50'); Pero en esta ocacion se estaria igualando el tipo de dato entre un numero y un string por lo tanto nos estari dando un 'false'.











