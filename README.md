# Informe Trabajo Extra Construcción de un Circuito Dimmer para el control de la intensidad de un foco de 110v

1. OBJETIVO GENERAL 

* Formar un circuito el cual me permita la regulacion de la variacion de potencia en una bombilla.
* Construir un circuito optimizado para tener el control de iluminacion de la bombilla.

1.2. OBJETIVO ESPECIFICO 

* Realizar el circuito con la menor cantidad de elementos posibles y hacerlode una manera efectiva y que cumpla con nuestro objetivo general.

2. MARCO TEÓRICO 

![My First Board (2)](https://user-images.githubusercontent.com/93899720/150909133-316acfdb-be84-4013-988a-2408d8121bd5.jpg)


3. EXPLICACIÓN DEL PROCEDIMIENTO

MATERIALES: 

![image](https://user-images.githubusercontent.com/93899720/151389100-80dd7494-a7d6-4911-957f-a10f5628f35e.png)

Armamos el circuito dimmer que se muestra en la siguiente imagen: 

![image](https://user-images.githubusercontent.com/93899720/151257861-dfd83d22-b76c-4dfe-b9e2-5d6a8132469d.png)


La linea superior e inferior seran las lineas para la corriente alterna. Utilizamos nuestra resistencia de 1 kilo ohmio y conectamos un extremo en un punto de la linea para corriente alterna y el otro extremo en un punto de la protoboard.Guiandonos en nustro diagrama puenteamos con un cable hacie el pin 2 del potenciometro.

![image](https://user-images.githubusercontent.com/93899720/151250101-e3a29f50-d9e9-42d6-ae7d-09047bda5ab7.png)

![image](https://user-images.githubusercontent.com/93899720/151250115-bee5a83c-7c7d-459a-97b9-2a637840610b.png)

Con ayuda de un cable puenteamos el pin 3 del potenciometro ala parte derecha para tener mas espacio en la protoboard. Ahora muestro condensador ceramico colocamos un extremo en la linea nferior de corriente alterna y lo puenteamos con el cable que conecta con el pin 3 del potenciometro.

![image](https://user-images.githubusercontent.com/93899720/151249034-45462999-8546-43dd-bc84-2ada6cccbe1d.png)

![image](https://user-images.githubusercontent.com/93899720/151249053-4c1ff8ba-c718-4bc2-9adb-726e099e4df8.png)

Con nuestro DIAC puenteamos de igual manera con el condensador y el puente que conecta hacia el pin numero 3 del potenciometro como se muetsra en la imagen. Con nuestra resistencia de 100 ohmios la conectamos en la misma linea que el otro extremo del DIAC como se muestra en la imagen.

![image](https://user-images.githubusercontent.com/93899720/151247105-033ff071-45cc-4f6c-af7e-a2b6c76ad1a5.png)

![image](https://user-images.githubusercontent.com/93899720/151247190-b32ff358-cc10-4789-b878-a81f4f2ae972.png)

Con ayuda de un cable puenteamos desde la linea del DIAC hacia la partede arriba de la protoboard conectando asi con el numero pin tres del TRIAC. Ahora con un cable de igual manera puenteamos dede el pin numero 1 del triac hacia la linea inferior de corriente alterna.Por ultimo puenteamos nuestro pin numero dos del TRIAC con nuestra linea superior de corriente alterna quedando el circuito final como se muestra en la imagen.

![image](https://user-images.githubusercontent.com/93899720/151245123-0fa5c709-3cfc-401a-aa87-361bec5c47b0.png)

![image](https://user-images.githubusercontent.com/93899720/151245156-dab6bd6b-1847-451d-aefd-02455eaee771.png)


Comprobamos que haya continuidad en todo el circuito.

![image](https://user-images.githubusercontent.com/93899720/151433677-f4a5cfb4-22d6-438c-86b1-7cfd8aa27fdf.png)

![image](https://user-images.githubusercontent.com/93899720/151433741-0ef7b68e-4aaa-4d53-9cd6-86cf7c9bf6cf.png)

![image](https://user-images.githubusercontent.com/93899720/151433789-e3634a9f-f209-46da-90ba-9110669b8938.png)

![image](https://user-images.githubusercontent.com/93899720/151433868-83814d67-5a5c-4823-b265-ac02bc3fc927.png)

![image](https://user-images.githubusercontent.com/93899720/151433940-d3c918a9-484e-4afe-ac97-dff2a3e63ad6.png)

![image](https://user-images.githubusercontent.com/93899720/151434073-eac09600-cbb7-4003-b394-a56af6f0c9b4.png)

![image](https://user-images.githubusercontent.com/93899720/151434164-a2787cd4-f02d-4393-83ea-1e9fce602945.png)

Con la ayuda de un socket y un foco de 110V mostradoS en la siguiente imagen haremos las debidas preubas con nuetro circuito. Conectamos el cable que viene desde la lampara en la linea superior de corriente alterna del protoboard y el cable que viene directo desde el enchufe para la corriente alterna lo conectamos en la linea inferior de alterna de nuestro protoboard quedando nuestro circuito de la siguiente manera.

![image](https://user-images.githubusercontent.com/93899720/151253394-cda46947-649e-4a87-bb4a-4009809b8643.png)

![image](https://user-images.githubusercontent.com/93899720/151253364-6b2df9c1-9aab-4927-99cc-ee10043088a9.png)

![image](https://user-images.githubusercontent.com/93899720/151253381-44114386-5528-4d31-ac9a-c611ca008719.png)


4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Después de haber comprobado que todas las conexiones en nuestro protoboard estén de la manera correcta procedemos a conectar los extremos del socket a nuestro protoboard la conexión de hace de la siguiente manera . El cable que proviene de nuestro foco de 110 V se conecta en el extremos superior de corriente alterna de nuestro protoboard mientras que el cable que vendrá directo de la corriente alterna va conectado a la línea inferior de alterna del protoboard osea en la misma línea del condensador 

Después de realizar la conexión de socket con nuestro circuito en el protoboard procedemos a conectar el enchufe en el toma corriente para verificar el funcionamiento de nuestro circuito lo conectamos con las debidas precauciones del caso para evitar cualquier accidente. Comprobamos que nuestro circuito funciona de manera de manera óptima y cumple con los objetivos planteados inicialmente por lo que podemos concluir en el siguiente paso.


5. VIDEO


6. CONCLUSIONES


7. BIBLIOGRAFÍA

Espinoza, I. (2022). Como hacer un Dimmer Electrónico con TRIAC y DIAC | Muy fácil paso a paso. Retrieved 26 January 2022, from http://www.electronicaivanespinoza.com/2018/12/como-hacer-un-dimmer-electronico-con.html

Como hacer un dimmer electronico con DIAC y TRIAC, Paso a Paso en Protoboard. (2022). Retrieved 26 January 2022, from https://www.youtube.com/watch?v=-Q6ZaH_hCBc&t=725s

ELECTRÓNICA PARA TODOS. (2022). Retrieved 26 January 2022, from https://www.electronicworld.com.mx/uncategorized/regulador-de-intensidad-dimmer-con-triac-y-diac/#:~:text=Un%20dimmer%20es%20un%20circuito,corriente%20alterna%2C%20ya%20sea%20de
