Este script de Python implementa un sistema simple de Control de Acceso basado en Dispositivo e Identidad utilizando la librería ipywidgets. Está diseñado para ejecutarse en entornos interactivos como Jupyter Notebooks o JupyterLab.

✨ Características Principales
Verificación de Identidad: Comprueba si un Usuario es parte de la lista de usuarios aprobados (approved_users).

Validación de Dispositivo: Si el usuario está aprobado, verifica si el Dispositivo ingresado coincide con el dispositivo que tiene asignado en la lista (approved_devices).

Control de Acceso Básico: Sirve como una demostración de un mecanismo de autenticación de doble componente (algo que tienes, el dispositivo, y algo que eres, el usuario) para restringir el acceso al sistema.

Interfaz Interactiva: Utiliza widgets (Text, Button, Output) para una interacción sencilla y clara.

⚙️ Requisitos
Para ejecutar este código, necesitas tener instalado:

Bash

pip install ipywidgets
🚀 Uso
Copia y pega el código en una celda de un Jupyter Notebook.

Ejecuta la celda.

Ingresa el Nombre de Usuario y el ID del Dispositivo en los campos de texto.

Haz clic en el botón "Verificar acceso" para validar la combinación de acceso.
