# data-engineering-clientes
Análisis de datos de clientes utilizando Python y Pandas

## Data Engineering: Análisis de Clientes
Este proyecto es un análisis de datos de clientes utilizando Python y Pandas. Puedes ver el proyecto en acción en [GitHub Pages](https://banbak.github.io/data-engineering-clientes/).

### Tecnologías utilizadas
- Python
- Pandas
- Matplotlib

### Cómo ejecutar el proyecto

Requisitos previos:

Python: Asegúrate de tener Python 3.x instalado en tu sistema.
Instalar Anaconda (opcional): Si prefieres trabajar en un entorno Jupyter Notebook.
Alternativa: También puedes usar Jupyter Lab o Jupyter Notebook fuera de Anaconda.

1. Clonar el repositorio
Primero, clona este repositorio en tu máquina local usando Git o descarga el archivo ZIP:

git clone https://github.com/banbak/data-engineering-clientes.git
cd data-engineering-clientes

2. Crear un entorno virtual (opcional pero recomendado)
# Crear el entorno virtual
python -m venv venv

# Activar el entorno virtual
# En Windows:
venv\Scripts\activate
# En Mac/Linux:
source venv/bin/activate

3. Instalar las dependencias
Instala las dependencias necesarias desde el archivo requirements.txt. Si no lo tienes, puedes crear uno con los paquetes usados.

pip install -r requirements.txt
Si no tienes un archivo requirements.txt, puedes crear uno con los siguientes paquetes:

# Crear un requirements.txt con los paquetes necesarios
pip freeze > requirements.txt
Para este proyecto, asegúrate de que las siguientes bibliotecas estén instaladas:

pip install pandas openpyxl matplotlib jupyter

4. Ejecutar el proyecto
Si estás usando Jupyter Notebook o Jupyter Lab, puedes abrir el archivo .ipynb del proyecto:

Opción A: Con Jupyter Lab
jupyter lab

Opción B: Con Jupyter Notebook
jupyter notebook

Luego, abre el archivo Clientes.ipynb y ejecuta las celdas.

5. Archivos utilizados
El proyecto utiliza un archivo de Excel llamado clientes.xlsx. Asegúrate de que el archivo esté en la misma carpeta que el notebook o en la ubicación correcta si estás cargando archivos adicionales.

Si necesitas cargar tus propios datos, asegúrate de modificar la ruta del archivo en el código:
df = pd.read_excel('ruta-al-archivo/clientes.xlsx')

6. Explorar los resultados
Una vez que ejecutes todas las celdas del notebook, podrás ver los análisis de datos y las visualizaciones generadas en función de la base de datos de clientes.

Opcional: Ejecutar directamente desde Python
Si prefieres no usar Jupyter y quieres ejecutar el análisis directamente desde un script de Python, puedes modificar el notebook y convertirlo en un script .py.

# Convertir notebook a script de Python
jupyter nbconvert --to script Clientes.ipynb

Luego, puedes ejecutar el script desde la terminal con:
python Clientes.py
