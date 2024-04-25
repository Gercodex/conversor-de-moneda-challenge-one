# Conversor De Moneda Challenge One Alura Latam
![Imagen del menú de opciones en la consola](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/dcb9b19a-9880-4137-9a03-b1e134f308cd)

## Descripción de Proyecto

Convertidor de monedas para el challenge ONE y Alura Latam.

## Funcionalidades

* Se conecta a la api de exchangerate para obtener los datos de conversión de monedas.
* Menú de opciones para conversión de moneda.
* Lee la entrada del usuario para elegir opciones del menú.
* Lee la entrada del usuario para convertir la moneda que elija del menú.
* Convierte valores de una moneda en el valor equivalente de otro tipo de moneda.
* Muestra nuevamente el menú para que el usuario elija una nueva conversión.

## Ejemplo de funcionalidad

https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/64702b94-155b-421a-99e5-892ba97356a6

## Resultado de conversion

![Screenshot_20240424_193703](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/d884ad5f-f55f-48ed-a95b-4d23cf709ca7)

## Estado del proyecto

Completado.

## Errores

Sin feedback hasta el momento.

## Dependencias

gson-2.10.1
Ver enlace: https://mvnrepository.com/artifact/com.google.code.gson/gson

Api del sitio: https://v6.exchangerate-api.com

Testeado en openJDK-17 y openJDK-21

## Compilación y ejecución

Compilar desde carpeta que contiene a /src

$ javac -d classes src/com/cursoalura/conversor/modulos/ *.java src/com/cursoalura/conversor/principal/ *.java -classpath /home/usuario.../proyecto/gson-2.10.1.jar

$ mv apiKey.txt classes

Ejecutar dentro de la carpeta /classes

$ java -classpath "/home/usuario.../proyecto/gson-2.10.1.jar": com.cursoalura.conversor.principal.Principal

Las rutas del classpath son ficticias, sustituir por la ruta donde se encuentre el paquete gson.

En intellij: Descargar el paquete, descomprimir, crear nuevo proyecto java, copiar la carpeta src dentro del nuevo proyecto, copiar apiKey.txt en la carpeta raíz de proyecto

## Nota:

El archivo apiKey.txt deberá crearse o moverse dentro de la carpeta classes después de la compilación, dentro deberá contener la clave de la api del usuario y puedan realizarse las consultas. Puede optar por asignarla directamente dentro del código y eliminando la funcionalidad de lectura de archivo.

## Para probar en Itellij

* Descargar y descomprimir archivo zip.
* Crear nuevo proyecto Java.

![Creando proyecto en Itelij](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/02d8b39a-4073-4ea0-bb5e-ac4f0664c1f7)

* Copiar la carpeta src ó desde /com/... a src del nuevo proyecto.
* Copiar o crear archivo apiKey en la raíz del proyecto y guardar la apiKey en el archivo apiKey.txt. Ver enlace para apikey: https://v6.exchangerate-api.com.
  
![image](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/9ddd6661-f410-432d-85d4-5e35be1135b8)

* Descargar gson-2.10.1.jar y agregar la ruta del paquete.

![image](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/3c98f916-5f8b-4d16-be40-62cacc9db98e)

* Click en Run o presionar Crtl+Shift+F10 en la clase Principal.


## Sobre el autor

https://www.linkedin.com/in/gerardo-gutierrez-rodriguez-37629a196/



  
