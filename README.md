# TPE-FundamentosCienciaDatos
Para la realizacion del TP Especial de la materia. Grupo 7, integrantes: Antúnez, Buralli, Todesco.

En caso de que deseen ver el informe en otro formato dejamos el enlace al documento de Google [aquí](https://docs.google.com/document/d/1aVamo6SerRPkJcXAzxWECUq-hLxOv-9-4qwl7Utd7oY/edit?usp=sharing).



## Instrucciones de ejecucion
Pre-requisitos: 
- Instalar [Python](https://www.python.org/downloads/) (version 3.8 o superior) 

> [!NOTE]
> Si falla la instalación de los requirements, utilizar la versión de 3.12.5, la cual fue utilizada para el desarrollo del trabajo.

> [!TIP]
> Para ver que version de Python estás utilizando, usa el comando ```python --version```, teniendo el ambiente activado.

- Instalar [Git](https://git-scm.com/downloads) 
- Tener un IDE instalado para el uso de Python con Jupyter Notebooks 
(por ej. [Visual Studio Code](https://code.visualstudio.com) o [Pycharm](https://www.jetbrains.com/es-es/pycharm/)) 

### Pasos recomendados para Visual Studio Code

(nosotros usamos Pycharm pero tuvimos problemas al hacer la replicación porque no nos reconocía el ambiente)

1. Crear una carpeta en el lugar que desee de su explorador de archivos.
2. Abra la carpeta con el IDE de su preferencia.
3. Abra una nueva terminal para realizar la creacion del ambiente donde se instalaran las librerias necesarias.

    3.1. Utilice el comando para crear el ambiente: ```python -m venv <nombre_a_eleccion>```
  
    3.2. Luego utilice el comando para activarlo: ```<nombre_elegido>\Scripts\activate```, si utilizas Mac o Linux: ```source <nombre_elegido>/bin/activate```

4. Ahora vamos a crear un repositorio local y clonar este repositorio remoto en el mismo.
  
    4.1. Colocar el comando en la terminal para crear el repositorio local: ```git init```
  
    4.2. Comando para clonar el repositorio remoto: ```git clone https://github.com/Arimochin/TPE-FundamentosCienciaDatos.git```

5. Ahora vamos a instalar las librerias necesarias para la ejecución del código. <br>
    
    5.1. Probablemente necesites pararte en la carpeta donde se encuentra el archivo requirements,
puedes hacerlo con el comando en la terminal: ```cd TPE-FundamentosCienciaDatos```
 
    5.2. Coloca el siguiente comando en la terminal para la instalación de las librerias: 
```pip install -r requirements.txt```

6. Ahora ya podrías abrir el archivo tpesp.ipynb y ejecutar sin ningún problema.

   6.1. (En VSC) Cuando quieras ejecutar algo te aparecerá que tienes que elegir un kernel, seleccionar *Python Enviroments...* y luego elegir la opción que tenga el nombre del ambiente (tiene una estrellita y aparece como recomendada). 
