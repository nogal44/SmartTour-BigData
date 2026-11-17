SmartTour Big Data

Proyecto académico de análisis Big Data aplicado al turismo.

SmartTour es una empresa ficticia que quiere analizar datos turísticos para tomar mejores decisiones. En esta primera práctica he preparado el entorno de trabajo con GitHub, Docker y JupyterLab.

Objetivo

Crear una plataforma para analizar datos turísticos y más adelante hacer cuadros de mando.

Tecnologías
Python
Docker
Docker Compose
JupyterLab
GitHub
Estructura
SmartTour-BigData/
├── docker-compose.yml
├── datasets/
├── scripts/
├── notebooks/
├── docs/
└── README.md
datasets: datos utilizados en el proyecto.
scripts: programas Python.
notebooks: análisis realizados.
docs: documentación.
Instalación

Hace falta tener instalado Git y Docker Desktop.

Clonar el repositorio:

bash
git clone https://github.com/tu-usuario/SmartTour-BigData.git
cd SmartTour-BigData
Ejecución

Arrancar el contenedor:

bash
docker compose up

Después abrir en el navegador:

http://localhost:8888

Para comprobar que funciona, abrir el notebook 01_comprobacion_entorno.ipynb y ejecutarlo. Tiene que salir:

Entorno SmartTour funcionando

Para pararlo:

bash
docker compose down
