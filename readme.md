# Pruebas para el parámetro firstName al crear un/a usuario/a en [urban groser]
- Necesitas tener instalados los paquetes pytest y request para ejecutar las pruebas.
- Ejecuta todas las pruebas con el comando pytest.
# Este proyecto tiene como objetivo realizar pruebas automatizadas exhaustivas para la aplicación Urban Groser, centrándose en la validación del campo name durante la creación y actualización de usuarios. La estrategia de prueba implementada incluye tanto casos de prueba positivos como negativos.

# Pruebas positivas: Verifican la funcionalidad correcta del campo name con datos de entrada válidos.
# Pruebas negativas: Identifican vulnerabilidades y aseguran la robustez del campo con datos inválidos o maliciosos.
# Tecnologías Utilizadas:

- Pytest: Framework de pruebas para Python.
- Requests: Biblioteca para realizar solicitudes HTTP.
# Ejecución de Pruebas
- Para ejecutar las pruebas, se requiere tener Python instalado y los paquetes pytest y requests instalados. Luego, se puede ejecutar el siguiente comando desde la línea de comandos en el directorio raíz del proyecto:

pytest
# Estructura del Proyecto:
- tests.py: Contiene los casos de prueba específicos para el campo name.
data.py: Define los datos de prueba utilizados en las pruebas.
sender_stand_request.py: Realiza las solicitudes a la API de Urban Groser.
create_user_tests.py: Combina los otros archivos para ejecutar las pruebas.
# Contribuciones:
- Las contribuciones al proyecto son bienvenidas. Si estás interesado en contribuir, puedes seguir los siguientes pasos:

- Forkea el repositorio en GitHub.
- Clona el repositorio forkeado en tu máquina local.
- Haz tus cambios.
- Haz un commit y un push de tus cambios al repositorio forkeado.
- Envía una solicitud de extracción (pull request) al repositorio original.