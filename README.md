🛡️ Obfuscate - Obfuscador de Scripts en PHP, Python2 y Bash
Obfuscate es una herramienta simple y funcional diseñada para ofuscar código fuente escrito en PHP, Python2 y Bash. Su objetivo es dificultar la lectura del código por parte de terceros, protegiendo la lógica de tus scripts frente a ingeniería inversa, análisis estático o copias no autorizadas.

⚙️ Lenguajes Soportados
🐘 PHP

🐍 Python 2

🐚 Bash

🚀 ¿Qué hace?
Este script toma como entrada un archivo de código fuente y lo transforma en una versión ofuscada mediante técnicas como:

Eliminación de formato legible

Codificación base64 u otros métodos (dependiendo del lenguaje)

Reempaque del script para que se siga ejecutando correctamente, pero sea difícil de entender

🧩 Uso

>> python obfuscate.py ruta/del/script.py

El script detecta el tipo de archivo según su extensión (.php, .py, .sh) y aplica el método de ofuscación correspondiente.

✅ Ejemplo
Entrada (original.py)

>> print("Hola mundo")

Salida (obfuscated.py)

>> exec("cHJpbnQoIkhvbGEgbXVuZG8iKQ==".decode("base64"))

📥 Instalación
Clona este repositorio:

>> git clone https://github.com/Kimura-IV/Obfuscate.git
>> cd Obfuscate

Asegúrate de tener Python 2.x instalado (solo para ejecutar este script).

📌 Requisitos
Python 2.x

Acceso al intérprete de PHP o Bash si deseas probar los scripts resultantes

⚠️ Advertencia
Esta herramienta no garantiza seguridad absoluta. La ofuscación solo complica la lectura del código, pero no lo hace imposible de revertir. Es útil como una capa adicional de protección.

📄 Licencia
Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo LICENSE para más información.
