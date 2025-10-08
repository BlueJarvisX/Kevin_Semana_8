# Kevin_Semana_8
Es una aplicación simple para mostrar un mapa de google maps con la localización

## Funcionalidad principal
- Visualización en tiempo real de la ubicacíón exacta del usuario
- Marcar ubicaciones en el mapa manteniendo pulsado un botón en el lugar deseado.
- Capturar y Descargar imágenes en un activity usando hilos y sensores extras(threads).

## Cómo ejecutar la aplicación

1. Clona este repositorio. En simple palabras descarga mi proyecto en zip de mi respositorio, después extraer y dezplazarlo a Android Studio
2. Abre el proyecto en Android Studio.
3. Configura tu clave API de Google Maps en el archivo correspondiente. En este caso API 26
4. Esperamos que se importe el proyecto y lo de index. 
5. Conecta un dispositivo Android o configura un emulador.
6. Haz clic en el botón "Run" (Ejecutar) en Android Studio para compilar y lanzar la app.
7. Ahora aparecera la pantalla de activity_main.xml con las opciones de 2 botones que serían uno de Google Maps y Otro de Hilos.
8. Seleccionar el botón de Google Maps para ver tu ubicación y puedes agregar marcadores en diferentes sitios.

## Implemetanción
Implementamos 2 dependecias una de maps y otra de location con sus versiones correspondientes
Utilizamos una api key valida de google console
Implementamos ViewMap que sin ella no podriamos ver el mapa
Damos permisos necesarios como el permiso de Internet, etc.
