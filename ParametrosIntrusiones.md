# Parametros Intrusiones
La información que recogen estos 9 parámetros (se pueden añadir más a posteriori) nos permite mediante Inteligencia Artificial(IA) conocer si el dispositivo está siendo atacado o no. Esto se consigue realizando un gráfico en coordenadas polares (aunque podría ser cualquier otro tipo de gráfico) que la IA sea capaz de reconocer. Una vez el modelo esta entrenado la IA es capaz de reconocer si un gráfico de un instante (o varios instantes) corresponde al gráfico de una intrusión o no.

Para hacer este texto inicial mas claro y sencillo de entender se muestran a continuación las imagenes que la Inteligencia Artificial usa para determinar si estamos ante una intrusión o no.

Gráfico de un solo instante:

![Grafico](Grafico.png)

Gráfico de varios instantes:

![Grafico varios instantes](GraficoInstantes.png)

Gráfico limpio:

![Grafico limpio](Graficolimpio.png)

Los nueve parametros a determinar inicialmente son los siguientes:

1.- Destino de url desconocido o no autorizado

2.- Comunicación no cifrada (https)

3.- Traspaso de datos locales a otro almacenamiento

4.- Uso o conexión a BSSID no permitida o desconocida

5.- Uso o conexión a Puerto Bluetooh no permitida o desconocida

6.- Uso o conexión a GPS no permitida o no autorizada

7.- Uso o conexión a cámara no permitido o desconocido

8.- Uso de dispositivo de audio (micro / altavoz) no permitido o desconocido

9.- Monitorización de parámetros físicos (velocidad, temperatura, batería) con resultado anormal



