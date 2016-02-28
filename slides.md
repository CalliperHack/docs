% CalliperHack
% Ictiómetro digital
% Vigo 28 de febrero 2016 #HackSB

# CalliperHack

## Problema

Medidor longitud de peces (*ictiómetro*) para ámbito oceanográfico.

----

![](images/external/800px-Ictiometer_Alburnus.jpg)

<small>
By Retama, CC BY-SA 4.0, via Wikimedia Commons.
https://commons.wikimedia.org/wiki/File:Ictiometer_Alburnus.jpg
</small>

## Opciones

- Ictiómetros convencionales
- Ictiómetro digitales magnéticos
- Procesado de imagen
- Bandeja pulsadores

## Requisitos

- Barato
- Precisión milimétrica

## Nuestra solución

- Calibre digital
- Udoo/Arduino: driver
- Udoo/Linux: adquisición de datos publicación en broker MQTT

----

![](images/components.png)

----

![](images/2016-02-28 10.54.30.jpg)

# Desarrollo

## Dificultades calibre

- Problemas eléctricos calibre digital
- Decodificar señal del calibre

## Arduino

- Interrupciones

## Linux

- Comunicación UART.

## Equipo

- ![](https://avatars1.githubusercontent.com/u/969061?v=3&s=64)
  Rafa Couto (@caligari_pub)
- ![](https://avatars1.githubusercontent.com/u/3344634?v=3&s=64)
  Luigi Pirelli (@Ginetto)
- ![](https://avatars1.githubusercontent.com/u/928566?v=3&s=64)
  Miguel González (@migonzalvar)
- ![](https://avatars0.githubusercontent.com/u/4236093?v=3&s=64)
  Jorge Tornero (@jtornero)

## Enlaces

- https://github.com/CalliperHack
- https://www.hackster.io/calliperhack/digital-ictiometer-based-on-a-accurate-calliper-0e5369
- ![CC BY-SA](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)
  ![GPLv3](http://www.gnu.org/graphics/gplv3-88x31.png)
  
# Gracias

# Anexos

## Fuentes

- YVODIC by Jorgue Tornero (@imasdemase) Ictiómetro digital usando pulsación de teclas: https://github.com/jtornero/YVODIc


## Screenshots

![](screenshots/95_logic_analyzer.png)

Primera captura de los datos emitidos por el calibre.

----

![](screenshots/96_timing.png)

Timing de los paquetes enviados por el calibre.

----

![](screenshots/97_bits.png)

Correspondencia en bits de los paquetes enviados por el calibre.

----

![](screenshots/98_sniffer.png)

Sniffer creado en arduino pare descifrar los paquetes.

----

![](screenshots/99_decoding.png)

Varias decodificaciones de los paquetes para buscar los datos de la medición.

## Fotos

![](images/2016-02-27 09.43.06.jpg)

----

![](images/2016-02-27 12.15.46.jpg)

----

![](images/2016-02-27 14.11.15.jpg)

----

![](images/2016-02-27 15.35.18.jpg)

----

![](images/2016-02-27 16.42.18.jpg)

----

![](images/2016-02-27 16.46.36.jpg)

----

![](images/2016-02-27 16.47.42.jpg)

----

![](images/2016-02-27 18.26.16.jpg)

----

![](images/2016-02-28 10.54.30.jpg)

----

![](images/2016-02-28 11.36.59.jpg)

----

![](images/2016-02-28 18.46.45.jpg)
