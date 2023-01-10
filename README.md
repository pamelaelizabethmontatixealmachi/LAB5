# LAB5
LAB 5

Integrantes:

Jose Joaquin Silva Escobar


Pamela Elizabeth Montatixe Almachi


Mauricio Joseph Taco Cabrera


OBJETIVOS


Definir el Teorema de Thevenin


Aplicar el Teorema de Thevenin al circuito presentado.


Reconocer como ayuda este Teorema al análisis de circuitos


MARCO TEÓRICO


TEOREMA DE THEVENIN


La forma Thevenin equivalente de cualquier circuito resistivo de dos terminales consta de una fuente de voltaje equivalente (VTH) y una resistencia equivalente (RTH), dispuestas como indica la figura 8-30. Los valores del voltaje y de la resistencia equivalentes dependen de los valores del circuito original. Cualquier circuito resistivo puede ser simplificado, pese a su complejidad, con respecto a dos terminales de salida. El voltaje equivalente, VTH, es una parte del circuito equivalente de Thevenin completo. La otra parte es RTH.


![image](https://user-images.githubusercontent.com/116780506/211618030-4e4acb59-7004-43f9-93d8-e871450f49ee.png)


El voltaje Thevenin se expresa como sigue en este ejemplo particular:



![image](https://user-images.githubusercontent.com/116780506/211618093-1bfa81bb-3d80-4a3b-abd8-ba43021078de.png)



Para encontrar el equivalente de Thevenin de cualquier circuito, se determina el voltaje equivalente, VTH, y la resistencia equivalente, RTH, vistos desde las terminales de salida. Como un ejemplo, el equivalente de Thevenin para el circuito ubicado entre las terminales A y B se desarrolló en la figura 8-32.

![image](https://user-images.githubusercontent.com/116780506/211618151-0a42b4ed-e5b0-4173-b8f9-cf010077a014.png)


Thevenización de un circuito puente



La utilidad del teorema de Thevenin tal vez se ilustra mejor cuando se aplica a un circuito puente Wheatstone. Por ejemplo, cuando se conecta un resistor de carga a las terminales de salida de un puente Wheatstone, como indica la figura 8-38, el circuito resulta difícil de analizar porque no es una configuración en serie-paralelo directa. No hay resistores que estén en serie o en paralelo con otro resistor.

![image](https://user-images.githubusercontent.com/116780506/211618244-153c370e-1f1b-494d-821f-d8c4d5a81ad1.png)


El siguiente es un resumen de los pasos a seguir para aplicar el teorema de Thevenin:


Paso 1. Abrir las dos terminales (eliminar cualquier carga) entre las que se desea encontrar el circuito equivalente de Thevenin.


Paso 2. Determinar el voltaje (VTH) entre las dos terminales abiertas.


Paso 3. Determinar la resistencia (RTH) entre las dos terminales abiertas con todas las fuentes reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito y fuentes de corriente ideales abiertas). 

Paso 4. Conectar VTH y RTH en serie para producir el equivalente de Thevenin completo del circuito original.

Paso 5. Reemplazar la carga eliminada en el paso 1 entre las terminales del circuito equivalente de Thevenin. Ahora se pueden calcular la corriente y el voltaje que haya en la carga utilizando solamente la ley de Ohm. Tienen el mismo valor que la corriente y el voltaje presentes en la carga del circuito original.

EXPLICACIÓN DEL PROCEDIMIENTO

3.1 MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/116780506/211618437-2562c154-825f-4e22-b0e5-18c5aebb76f2.png)


3.2 Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/116780506/211618514-53eb8d36-4b32-4139-bddc-ed392c1e103f.png)


3.3 Mida el voltaje y la corriente en el resistor R5

![image](https://user-images.githubusercontent.com/116780506/211618572-c7110ccc-98d6-4f91-8679-a6ba1096d785.png)


![image](https://user-images.githubusercontent.com/116780506/211618592-fa5232f8-4985-43d6-ad04-bb743d754e7c.png)


3.4 Desconecte el resistor R5 y mida el voltaje en el circuito abierto.

![image](https://user-images.githubusercontent.com/116780506/211618634-27d0ed43-b89e-493f-a554-d789aa46ddd3.png)


3.5 Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente.

![image](https://user-images.githubusercontent.com/116780506/211618683-a6f05b0f-2a55-4ad0-9e38-9bc914c1b316.png)


3.6 Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo

![image](https://user-images.githubusercontent.com/116780506/211618735-8fd24cbb-307a-4971-bfee-a0642ca77b19.png)


RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

4.1 Valores del Circuito Equivalente de Thévenin

![image](https://user-images.githubusercontent.com/116780506/211618846-3f5926c4-3b60-46c5-bc20-a911240488ae.png)


4.2 Comprobación del Teorema de Thévenin.

![image](https://user-images.githubusercontent.com/116780506/211618897-295c1a0b-23ef-4e8f-b4d0-33f9273f8271.png)


4.3 Calculo de Error

![image](https://user-images.githubusercontent.com/116780506/211618945-98e584be-97b7-4cb3-8ce3-c37d72d32541.png)


![image](https://user-images.githubusercontent.com/116780506/211619064-13ad64cb-9582-49d9-9398-e1760bc22c50.png)


VIDEO

https://drive.google.com/file/d/1JVDtcWO2Zxs532KbZcoJ3sblLh5Oz7GI/view?usp=sharing

CONCLUSIONES

El Theorema de Thevenin en un teorema que nos permite facilitar el análisis de circuitos ya que permite que este se simplifique.
Para aplicar el teorema es importante conocer definiciones como Ley de Ohm, LVK y LCK.
BIBLIOGRAFÍA
Laboratorio de Física, I. I., & Skigin, D. Ley de Ohm y de Kirchhoff.

Floyd (8va Ed)(2007). Principios de circuitos electricos. Pearson Education


