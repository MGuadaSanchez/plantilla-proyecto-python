# Plantilla de Proyecto Python Backend

Este repositorio es una plantilla base para proyectos de desarrollo backend con Python.  
Contiene una estructura inicial y documentación que podés reutilizar para tus futuros proyectos.

## Tecnologías utilizadas
- Python 3.x
- Entorno virtual para manejo de dependencias
- [Flask / FastAPI / Django] (elegí según el proyecto)
- Base de datos: SQLite / PostgreSQL / otra (según corresponda)

## Estructura recomendada del proyecto

```
/nombre-del-proyecto
│
├── README.md           # Documentación del proyecto
├── .gitignore          # Archivos y carpetas a ignorar por Git
├── requirements.txt    # Lista de dependencias
├── venv/               # Entorno virtual (no subir al repo)
├── main.py             # Archivo principal de ejecución
└── app/                # Carpeta con el código fuente
    ├── __init__.py
    ├── routes.py
    └── models.py
```

## Instrucciones básicas

### Clonar el repositorio

```bash
git clone https://github.com/MGuadaSanchez/plantilla-proyecto-python.git
cd plantilla-proyecto-python
```

### Crear y activar entorno virtual

```bash
python -m venv venv
# Linux/macOS
source venv/bin/activate
# Windows
venv\Scripts\activate
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

### Ejecutar el proyecto

```bash
python main.py
```

## Cómo usar esta plantilla

- Copiá este repositorio para iniciar un nuevo proyecto backend en Python.  
- Adaptá la estructura y documentación según las necesidades de cada proyecto.

## Autor

Guadalupe Sanchez — [Tu GitHub](https://github.com/MGuadaSanchez) | [Tu LinkedIn](https://linkedin.com/in/guadalupesanchez/)
