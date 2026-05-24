# Inventory-management-system-

Markdown
# 📦 Sistema de Gestión de Inventario con Python y Tkinter 🚀

¡Bienvenido! Este proyecto es una aplicación de escritorio intuitiva y ligera desarrollada en **Python** que utiliza la interfaz gráfica de usuario (**Tkinter**) para la administración y control de stock de productos. 

Lo mejor de este sistema es su simplicidad: **no requiere la configuración de bases de datos tradicionales**. Toda la información se almacena, lee y actualiza automáticamente en un archivo de texto plano (`.txt`) local. Si el archivo no existe en el sistema, la aplicación lo creará por ti al iniciar. 

---

## ✨ Características Principales

* 🖥️ **Interfaz Gráfica Limpia:** Ventana interactiva y amigable estructurada con formularios y tablas visuales.
* 💾 **Persistencia de Datos Local:** Guardado automático y directo en un archivo de texto integrado.
* 🔄 **Operaciones CRUD Completas:** Permite registrar, visualizar, actualizar y eliminar productos del inventario de forma inmediata.
* 🎨 **Código Personalizable:** Estructura flexible que permite modificar fácilmente los colores, la plantilla y el tamaño de la ventana según tus necesidades.

---

## 🛠️ Requisitos e Instalación

Para ejecutar este proyecto en tu entorno local, asegúrate de cumplir con los siguientes requisitos desde tu línea de comandos:

### 1. Instalar Python 🐍
Asegúrate de tener Python instalado en el sistema. Puedes verificar tu versión actual ejecutando:
```bash
python --version
2. Instalar la Biblioteca Tkinter 📦
Tkinter suele venir preinstalado junto con Python en entornos de Windows. Si te encuentras en un sistema Linux donde no esté disponible, puedes instalarlo ejecutando:

Bash
sudo apt-get install python3-tk
3. Organización de Archivos 📂
El diseño del proyecto requiere mantener el archivo ejecutable de Python y el archivo de texto generador dentro de un mismo directorio aparte para asegurar un entorno limpio:

Plaintext
📂 mi-proyecto-inventario/
├── 📄 inventory.py          # Archivo ejecutable del proyecto (.py)
└── 📄 inventario_datos.txt  # Archivo de texto creado automáticamente para almacenar los datos
💻 Cómo Ejecutar el Proyecto
Abre tu terminal favorita o la terminal integrada de Visual Studio Code.

Asegúrate de estar ubicado dentro de la carpeta del proyecto.

Ejecuta el archivo principal con el comando correspondiente a tu sistema operativo:

En Windows:

Bash
  python inventory.py
En Mac / Linux:

Bash
  python3 inventory.py
🎓 Objetivo del Taller
Este repositorio fue desarrollado con la finalidad de consolidar habilidades técnicas esenciales en el desarrollo de software:

🛠️ Aprender a trabajar con proyectos existentes usando Git y GitHub (clonar, configurar remotos y subir cambios).

📂 Dominar la manipulación y persistencia de flujos de archivos de texto en Python.

🎨 Construir e interactuar con aplicaciones de escritorio guiadas por eventos (GUI).

✨ Proyecto educativo desarrollado para el control de versiones y prácticas de desarrollo. ✨