# 📊 Habit Tracker con Pixela API

Este es un **habit tracker** en Python que utiliza la API de [Pixela](https://pixe.la) para registrar y visualizar hábitos diarios, como la cantidad de páginas leídas en un día.  

## 🚀 Instalación y Configuración

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
```

### 2️⃣ Crear un entorno virtual (opcional pero recomendado)
```bash
python -m venv venv
source venv/bin/activate  # En Windows usa: venv\Scripts\activate
```

### 3️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

### 4️⃣ Configurar las variables de entorno
Crea un archivo `.env` en la raíz del proyecto y añade tus credenciales de Pixela:

```ini
TOKEN=tu_token
USERNAME=tu_usuario
GRAPH_ID=graph1
```

Asegúrate de que el archivo `.env` esté en el `.gitignore` para no subirlo a GitHub.

### 5️⃣ Ejecutar el script
```bash
python main.py
```

## 📌 Funcionalidades
- **Añadir datos** (hoy o en una fecha específica).
- **Actualizar datos** de un día concreto.
- **Eliminar datos** registrados previamente.
- **Interfaz simple en consola**.

## 🛠 Tecnologías utilizadas
- Python
- Requests (para interactuar con la API)
- Dotenv (para gestionar variables de entorno)
- Pixela API

## 🐜 Licencia
Este proyecto está bajo la licencia MIT.

---

💡 _Proyecto desarrollado para aprender a integrar Python con APIs y mejorar hábitos personales._ 🚀

