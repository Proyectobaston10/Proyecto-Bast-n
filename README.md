# Proyecto-Bastón
Proyecto Bastón por alumnos del 5B

*****PROYECTO BASTÓN*****

**Descripción General:**

El proyecto de bastón servirá para guiar a las personas, para poder ayudarlos en la vida cotidiana con desplazamientos deseados, gracias al sensor ultrasónico le permite trasladarse con mayor seguridad, ¿Cuántas veces no hemos visto una persona ciega tratando de cruzar la calle con mucha dificultad sin poder conseguir ayuda? Es por eso que hemos decidido realizar este proyecto con funciones distintas que han existido.


**Propósito:**

El propósito de nuestro proyecto es ayudar a las personas invidentes a que se trasladen a un lugar con mayor seguridad durante la vida cotidiana y tengan una mejor calidad de vida.


**Proceso:**

Para la construcción del prototipo, todo basado en el bastón se complementa con la parte electrónica, siendo la mejora del dispositivo, empleando los requerimientos por lo que se eligieron los siguientes componentes:
- Placa Arduino
- Sensor ultrasónico (HC-SR04)
- Sensor de Obstáculos
- Zumbador
- Leds
- Mini motor vibrador
- NODEMCU
De forma general son los dispositivos que le darán funcionamiento al bastón.


**Resultado:**

Bridarle una mejor calidad de vida al invidente, en el cual le ayude a poder agilizar sus desplazamientos hacia lugares deseados, se toma en cuenta que este dispositivo de igual forma evite accidentes y sobre todo ayude la economía ya que no se necesita de un gasto excesivo.

**Diagrama de flujo:**

![ExamenBIGDATA](https://user-images.githubusercontent.com/78035184/105901408-f43fc680-5fe2-11eb-977b-9a69cca02367.png)
1. Inicio.
2. Alimentar los dispositivos.
3. Probar el funcionamiento.
4. Si funciona ir al paso 5, si no regresar al paso 3.
5. Enviar información al NODEMCU.
6. ¿El NODEMCU se conecta a la base de datos?
7. Si se conecta, envia información a la base de datos.
8. Si no se conecta, entonces rechazar información.
9. Gráficar la información en una tabla, para mejor visualización.
10. Fin.

**5 V's del Big Data:**
1. Volumen
2. Variedad
3. Velocidad
4. Veracidad
5. Valor

**Identificación de los 5´v:**

1.- Volumen: En este punto se presenta los datos que se van almacenando de los sensores hacia la base de datos, ya que recaudan una gran información masivo de datos, en un determinado tiempo para guardar información.
 
2.- Variedad: En nuestro proyecto este apartado funciona con base a las tablas con sus respectivos campos que almacenan datos como por ejemplo una tabla de empleados, requiere un id de empleado, nombre, apellido, etc.

3.- Velocidad: Este punto es primordial para el proyecto ya que refleja el tiempo en el cual se debe visualizar la información en los campos asignados que se encuentran en la base de datos.

4.- Veracidad: En este caso nuestros sensores al enviar datos primero pasan por una validación para comprobar que sea correcto el dato que se requiere enviar  en la base de datos.

5.- Valor: los datos en este caso son del sensor ultrasónico y sensor de obstáculos, al enviar la información a la base de datos aportan un valor para saber la proximidad de un obstáculo que cada invidente posee.


**Diagrama ETL:**

![etc](https://user-images.githubusercontent.com/78035004/105899971-07ea2d80-5fe1-11eb-918c-f1840dcaa42d.png)


**Extracción de información**

La extracción de información se obtendra por medio de un servicio API, de una Base de Datos, información de los sensores, por medio de Consultas en la Página Web.

**Transformación**

Este proceso de transformación buscara de la Base de Datos tomar información en el cual generara un apartado de gráfica, poder garantizar que funcione adecuadamente el dispositivo de invidente y sobre todo tener seguridad en el tráfico de datos.

**Carga de Datos (Load)**

En este punto de Carga, los datos se logran visualizar en gráficas para un mejor control de los datos e información, de esta forma se genera una gráfica de la distancia que existe entre un invidente y un obstáculo.


**Integrantes**

- Adolfo Ángel Leo Cámara

- Sergio Antonio Tziu Cetz
