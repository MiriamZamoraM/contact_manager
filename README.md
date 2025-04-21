# 📒 Contact Manager API

Una API REST construida con Django REST Framework que permite gestionar una agenda de contactos: crear, visualizar, actualizar y eliminar información de contactos personales.

## 📚 Tecnologías utilizadas
- Python 3.x
- Django 4.x
- Django REST Framework

## 🚀 Instalación

1. Clona el repositorio:

~~~
git clone https://github.com/tu_usuario/contact_manager.git
~~~

2. Entra al directorio:

~~~
cd contact_manager
~~~

3. Crea un entorno virtual y activalo: (Sugerencia personal: Usa virtualenv "venv")

~~~
python -m venv venv
source venv/bin/activate  o  venv\Scripts\activate en Windows
~~~

4. Instala las dependencias necesarias:

~~~
pip install -r requirements.txt
~~~

5. Realiza las migraciones de la base de datos:

~~~
python manage.py migrate
~~~

6. Inicia el servidor de desarrollo:

~~~
python manage.py runserver
~~~


## 📋 Endpoints principales

| Método | Endpoint | Acción |
|----------|----------|----------|
| GET  | url  | Listar todos los contactos  |
| POST    | url   | Crear un nuevo contacto   |
| GET-ID   | url   | Obtener un contacto específico   |
| UPDATE  | url  | Actualizar un contacto   |
| DELETE   | url  | Eliminar un contacto   |

## Modelo de Contacto
- Nombre (name)
- Email (email)
- Teléfono (phone)
- Dirección (address) (opcional)

## 🛡 Autenticación
Actualmente no requiere autenticación.

## 🏗 Futuras mejoras
- Implementar autenticación de usuarios.
- Agregar filtros de búsqueda.
- Añadir validaciones más estrictas en el registro de contactos.


### ✨ Autor
[Miriam Zamora](https://github.com/MiriamZamoraM)
