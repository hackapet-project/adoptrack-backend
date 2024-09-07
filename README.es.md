
# AdopTrack

[English](README.md) | [Español](README.es.md)

AdopTrack es una aplicación web basada en Django para gestionar adopciones de mascotas.

## Comenzando

Estas instrucciones te ayudarán a configurar el proyecto en tu máquina local para desarrollo y pruebas.

### Prerrequisitos

- Python (3.8 o superior)
- pip (gestor de paquetes de Python)
- virtualenv
- Git

### Instalación

1. Clona el repositorio:
   ```
   git clone https://github.com/tuusuario/adoptrack.git
   cd adoptrack
   ```

2. Crea un entorno virtual:
   ```
   python3 -m venv venv
   ```

3. Activa el entorno virtual:
   - En macOS y Linux:
     ```
     source venv/bin/activate
     ```
   - En Windows:
     ```
     venv\Scripts\activate
     ```

4. Instala los paquetes requeridos:
   ```
   pip install -r requirements.txt
   ```

5. Ejecuta las migraciones:
   ```
   python manage.py migrate
   ```

6. Inicia el servidor de desarrollo:
   ```
   python manage.py runserver
   ```

Visita `http://127.0.0.1:8000` en tu navegador web para ver la aplicación en funcionamiento.

## Características

- Listado y búsqueda de mascotas
- Proceso de solicitud de adopción
- Autenticación de usuarios y perfiles
- Panel de administración para gestionar mascotas y solicitudes

## Contribuir

Por favor, lee [CONTRIBUTING.md](CONTRIBUTING.md) para obtener detalles sobre nuestro código de conducta y el proceso para enviar solicitudes de pull.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.
