# TALLER_WEB_SCRAPING

*🎄 INTEGRANTES: Sara Valentina Beltrán Rodríguez - Luis Guillermo Vaca Rincón 🎄*

**Información básica para ejecutar el programa:**

  -El programa requiere de las siguientes librerias para ejecutarse:
  
    -beautifulsoup4 == 4.9.3
    
    -urllib3 == 1.26.2 
    
    
  -Ejecutar los siguientes comandos para instalar las librerias
  
    -pip install beautifulsoup4
    
    -pip install urllib3
   
**Funcionamiento:**

  -El algoritmo adjunto tiene el propósito de realizar webscraping a la página **https://www.espinof.com/listas/peliculas-estreno-esperadas-2021**
   para obtener la información contenida alli, en este caso  nombre de las películas,fecha de estreno e imagen de las mismas, así mismo esta información se 
   procesa removiendo etiquetas propias del html.
   
   Esta información es almacenada en un archivo txt para un posterior uso en la interfaz gráfica del proyecto ("PYFLIX"  https://github.com/sabeltranr/ENTREGA_2) funcionando como un canal de estrenos próximos.

![TALLER-TKINTER](https://github.com/sabeltranr/TALLER_WEB_SCRAPING/blob/main/FUNCIONAMIENTO.png)
 
_**Nota:** se adjunta un archivo txt (https://github.com/sabeltranr/TALLER_WEB_SCRAPING/blob/main/taller-webscraping.txt) con el codigo html en caso de que la página no permita mas solicitudes, en este se debera cambuar el URL y agregar el enrutamineto hacia el archivo y la ubicación del mismo._
