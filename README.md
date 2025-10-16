🛒 Urban Grocers – Automatización de pruebas API

📌 Descripción del proyecto
Urban Grocers es una aplicación de comercio electrónico enfocada en la venta de productos comestibles mediante kits prediseñados o personalizados. Este proyecto se centra en la automatización de pruebas para validar el correcto funcionamiento del endpoint de creación de kits, con énfasis en el campo “nombre”.

🧩 Problema que resuelve
El objetivo principal es garantizar que el campo “nombre” cumpla con los criterios de validación establecidos, asegurando la integridad de los datos y la estabilidad del sistema ante entradas válidas e inválidas. Esto permite detectar errores de forma temprana y mejorar la calidad del backend.

🛠️ Tecnologías utilizadas
Python - Pytest - Requests - Venv - GitHub

▶️ Cómo ejecutar el proyecto

Clona el repositorio:
git clone https://github.com/Saracalle1234/qa-project-Urban-Grocers-app-es.git

Crea y activa un entorno virtual:
python -m venv venv  
source venv/bin/activate  # En Linux/Mac  
venv\Scripts\activate      # En Windows

Instala las dependencias:
pip install -r requirements.txt

Ejecuta las pruebas:
pytest Create_kit_name_kit_test.py
