# 🐾 Clasificador de Perros y Gatos en Tiempo Real

<div align="center">
  <img src="https://img.icons8.com/color/96/000000/dog--v1.png" width="50">
  <img src="https://img.icons8.com/color/96/000000/cat--v1.png" width="50">
</div>

Proyecto de **clasificación en tiempo real** de perros 🐕 y gatos 🐈 con imágenes a color. ¡Funciona directamente en tu navegador!  

✨ **Características principales:**  
- 📱 Compatible con móviles (apunta tu cámara)  
- 🖥️ Funciona con imágenes de computadora  
- ⚡ Procesamiento 100% en el navegador con TensorFlow.js  
- 🧠 Modelo pre-entrenado con Python/TensorFlow  

---

## 🌐 Demo en Vivo  
¡Pruébalo ahora mismo! 👉 [Demo Online](https://ringa-tech.com/exportacion/perros-gatos/)  

---

## 🛠 Cómo Usarlo

##### 📥 Instalación Local
```bash
# 1. Clona el repositorio
git clone https://github.com/GabooMedina/petVision.git

# 2. Ve al directorio
cd perros-gatos

# 3. Inicia el servidor (Python 3+)
python -m http.server 8000
```

##### 🌍 Accede desde:
http://localhost:8000

##### 📱 Uso en Móvil (via ngrok)

 1. Descarga ngrok (https://ngrok.com/download)
 2. Ejecuta (en otra terminal)
 ```bash
ngrok http 8000
```
🔗 Copia la URL HTTPS que aparece en la terminal de ngrok y ábrela en tu móvil.

### 🎮 Modo de Uso
Permite el acceso a la cámara 📷

Apunta a un perro/gato (¡o usa una foto!)

Mira la predicción en tiempo real �

Cambia entre cámaras con el botón 🔄


### 🧠 Tecnologías Usadas
<p align=""> <img src="https://img.shields.io/badge/TensorFlow.js-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow.js"> <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript"> </p>