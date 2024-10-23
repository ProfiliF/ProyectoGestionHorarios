# ProyectoGestionHorarios
# Gestión de Horarios para Restaurantes y Bares

Este es un proyecto final realizado como parte del curso de Python, desarrollado para la gestión de horarios laborales en el sector de restaurantes y bares. La aplicación fue diseñada para **El Chiringuito Bar**, pero puede adaptarse a otros restaurantes que requieran una herramienta para la planificación de turnos y la generación de informes.

## Funcionalidades

- Crear horarios para los empleados.
- Visualización del horario semanal.
- Importar fichajes desde un archivo CSV del reloj de fichajes.
- Generar informes en formato Excel.
- Integración con bases de datos SQLite utilizando SQLAlchemy.
- Gráficos de barras para visualizar la carga horaria de los empleados.

## Tecnologías utilizadas

- **Lenguaje de programación:** Python 3
- **Interfaz gráfica:** Tkinter
- **Base de datos:** SQLite3
- **Librerías adicionales:** SQLAlchemy, Matplotlib, PIL
- **Entorno de desarrollo:** JetBrains PyCharm
- **Otros:** Virtualenv para la gestión de entornos virtuales

## Instalación y ejecución

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/ProfiliF/ProyectoGestionHorarios.git

cd ProyectoGestionHorarios
python3 -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt
