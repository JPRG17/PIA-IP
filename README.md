# PIA-IP
PRODUCTO INTEGRADOR IP

📂 Estructura del Proyecto  

    🔹   Scripts Principales    
-  main.py  → Script de control principal que ejecuta las diferentes funciones del proyecto.  
-  requirements.txt  → Archivo con las dependencias necesarias para ejecutar los scripts.  

    🔹   Funciones Disponibles    
| Opción | Descripción |
|--------|------------|
|   A - Web Scraping   | Extrae información de una página web dada. |

|   B - API Hunter   | Realiza consultas a APIs públicas usando una clave de API. |

|   C - Envío de Imagen   | Automatiza el envío de imágenes según los parámetros ingresados. |

|   D - Hash Obtainer   | Obtiene hashes de archivos dentro de una ruta especificada. |

|   E - PowerShell Scripts   | Ejecuta comandos en PowerShell mediante un menú interactivo. |

|   F - Servidor-Cliente   | Inicia una conexión entre un servidor y un cliente mediante sockets. |

|   G - WhatsApp Automation   | Automatiza el envío de mensajes a través de WhatsApp Web. |

------------------------------------------------------------------------------------------------------


INSTRUCCIONES EJECUCION
1.	Abrimos CMD.
2.	Nos dirigimos a la carpeta donde están todos los scripts.
3.	Desde el CMD instalaremos todos los módulos con el comando pip install requirements.
4.	Ejecutamos el comando: Py main.py -h, para que despliegue la información de ayuda.
5.	Luego pasamos a ejecutar cada uno de los scripts.
6.	El primero llamado WebScraping, se ejecuta con el siguiente comando: py main.py A -U https://www.uanl.mx -C Webscraping. Este comando ejecuta primero el script principal, luego seguido con la opción A, que es la de WebScraping, luego -U que significa la url, y en seguido colocamos la url con la cual haremos la prueba, por último, ponemos -C que es para crear la carpeta y seguido de esto el nombre que se le asignará a esta misma.
7.	La segunda opción es APIhunter, se ejecuta: py main.py B -D hola.com, seguido de ingresar este comando se imprime un mensaje “ingrese su api key”, la ingresamos y se ejecuta el programa. Primero se ejecuta el script principal luego colocamos B, que se refiere a la opción de APIhunter, seguido -D que se refiere al dominio y al último colocamos los dominios que se quieren buscar.
8.	Opción C, se ejecuta con el comando: py main.py C. Luego ya te pedirá todos los datos para poder enviar la imagen.
9.	La opción D es la de HashObteiner, se ejecuta: py main.py D -R C:\Users\juanp\Downloads\PIA -C Hashes. Primero ejecutamos el script principal, luego colocamos la opción D, y el argumento -R para especificar la ruta de los que se obtendrán los hashes, luego el argumento -C para crear la carpeta y al último el nombre que se le asignará a esta.
10.	La antepenúltima opción es la de PowerShell con la letra E, se ejecuta de la siguiente manera: py main.py E. Luego despliega un menú y ahí solo colocas la letra que quieres que ejecute el código (a, b,c,d,e,f,g,h).
11.	La penúltima opción con letra F, es la de conexión Servidor-Cliente, se ejecuta: py main.py F. Luego abres otra terminal para ejecutar el siguiente comando: py Cliente.py. Para poder tener conexión entre el cliente y el servidor.
12.	La ultima opción se ejecuta Py main.py G esta abre de forma automática https://web.whatsapp.com y envía el mensaje indicado por defecto
