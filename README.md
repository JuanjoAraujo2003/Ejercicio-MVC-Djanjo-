# Tarea Ejercicio MVC ejercicio Semestre Pasado 

## Framework MVC Utilizado: Django

### Pasos para poder Ejecutar el proyecto

1) Configuración del Virtual Environment
   ```sh
    python -m venv env
    source env/bin/activate  # Si se intenta en Windows se debe usar el siguiente comando: `env\Scripts\activate`
    pip install -r requirements.txt
    ```
2) Ejecutar las Migraciones de la base de datos
   ```sh
    python manage.py migrate
    ```
3) Ejecutar el programa
   ```sh
    python manage.py runserver
    ```
