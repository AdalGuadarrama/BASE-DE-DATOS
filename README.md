# BASE-DE-DATOS
En este repositorio se demuestra como funciona el esquema phpMyadmin con el método de programación  del ESP32 con el sensor DHT11, el sensor ultrasonico, además los datos obtenidos se reflejan en el programa Node-RED mediante una conexión WIFI.
## INTRODUCCION 
Usaremos el programa phpMyadmin para colocar una tabla de datos y con ayuda de la interfaz Esp32, el sensor DTH11y ultrasonico para recolectar la temperatura, humedad y idstancia del ambiente, también usaremos el programa Node-red para visualizar y programar esquemáticamente el flujo de información. Los resultados se pueden observar en la interfaz Node-Red.
### MATERIAL
* Programa PhpMyadmin
* Programa Wokwi
* Progrma Node-red
* Interfaz ESP32
* Sensor DHT11
* Sensor Ultrasonico
#### INSTRUCCIONES
1. Entrar a la pagina https://www.apachefriends.org/  . Descargar XAMPP for Windows (8.2.4).

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/F1.png)

2. Debemos abrir el programa llamado XAMPP, dentro de la interfaz nos vamos a la fila llamada Mysql y Le damos doble click al boton Admin.

![,](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f2.png)

3. Creamos una tabla con los siguientes criterios.
![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f3.png)

4. Abrir el programa Node-red y colocamos dos bloques uno de funtion y mysql.
![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/s0.0.png)

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/s5..png)

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f4.png)

5. Damos doble click derecho en el bloque de funtion y colocamos el siguiente codigo, alterminar damos click en done.

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f5.png)

6. A continuacion el bloque de mysql damos doble click derecho y seleccionamos la opccion Database (lapiz).

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f6.png)

7. Llenamos de forma correcta los datos corresondientes, click en update y salimos (done).

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f7.png)

8. Finalmante le damos en Deploy como se muestra en la imangen.

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f8.png)

9. Con la ayuda de nuestro repositorio llamodo: " NODE-RED DHT22 Y ULTRASONICO " comprobamos que nuestro programa funcione correctamente.

![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/u7.png)

### RESULTADOS
   * Visualizamos la interfaz y podremos manilular nuestro resltulados con el programa WOKWI.
   * Podras observar los valores dentro del monitor serial y la interfaz como se muestra en la siguiente imagen.
![.](https://github.com/AdalGuadarrama/BASE-DE-DATOS/blob/main/f.png)

### CREDITOS
Ing. Guadarrama Lome Adalberto
