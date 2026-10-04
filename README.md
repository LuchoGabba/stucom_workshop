# Clonar Repositorio y Preparar Entorno

## Clonar Repositorio

Para obtener los archivos necesarios para el workshop, sigue estos pasos:

1.  Abre una terminal en tu computadora.
2.	Navega al directorio donde deseas clonar el repositorio:\
    `cd /ruta/deseada/`
3.	Clona el repositorio usando el siguiente comando:\
    `git clone https://github.com/LuchoGabba/stucom_workshop.git`
4.	Cambia al directorio del repositorio:
    `cd stucom_workshop`
5. Sería ideal que crees una rama propia donde trabajar tu código.

Alternativamente, puedes descargar el repositorio como un **ZIP File**:

1.  Accede al GitHub del repositorio:\
    https://github.com/LuchoGabba/stucom_workshop
2.	Presiona el botón verde `<> Code`
3.  Selecciona `Download ZIP`


## Instalar Dependencias

Los paquetes de Python que usan todos los notebooks del taller están en el archivo `requirements.txt`. Necesitas Python 3.10 o superior.

1.  Abre una terminal en la carpeta del repositorio (`stucom_workshop`).
2.  Crea un entorno virtual y actívalo (recomendado, para no mezclar estos paquetes con los de otros proyectos):
    - macOS / Linux:\
      `python3 -m venv .venv`\
      `source .venv/bin/activate`
    - Windows (PowerShell):\
      `python -m venv .venv`\
      `.venv\Scripts\Activate.ps1`
    - Si usas conda:\
      `conda create -n taller python=3.11`\
      `conda activate taller`
3.  Instala las dependencias:\
    `pip install -r requirements.txt`
4.  Abre los notebooks con `jupyter lab`, o desde VS Code eligiendo como kernel el entorno que acabas de crear.

Cada vez que vuelvas a trabajar, activa de nuevo el entorno (paso 2, solo la línea de activación) antes de abrir los notebooks.


## Slides

https://docs.google.com/presentation/d/1pKs0polgyAhmPKmPYP6BcTqH6Aqe-amQFfXJ4HLvq9s/edit?usp=sharing

**Nos vemos en el Paso a Paso para Realizar Análisis Geoespaciales.**


## Contacto

Si tienes dudas puedes consultarlas con http://www.linkedin.com/in/luciano-gabbanelli.
