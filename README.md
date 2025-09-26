# 🗣️ Sistema Inteligente para el Tratamiento del Habla en Infantes con Problemas de Pronunciación

## 👨‍💻 Autor
- **Nombre:** Navía Condori Eddy  
- **Carrera:** Ing. en Ciencias de la Computación
- **Universidad:** San Francisco Xavier de Chuquisaca  
- **Año:** 2024  

---

## 📖 Descripción del Proyecto
Este sistema tiene como objetivo apoyar a infantes con dificultades en la pronunciación mediante un entorno tecnológico que combina modelos de inteligencia artificial y una interfaz móvil interactiva.  
El sistema analiza la voz del usuario, detecta posibles errores de pronunciación y ofrece recomendaciones personalizadas para mejorar sus habilidades de habla a través de ejercicios adaptados.

---

## ✨ Características del Proyecto
- 🎤 **Transcripción de voz a texto** utilizando **Whisper**.  
- 📝 **Corrección gramatical** de las oraciones transcritas con **mT5**.  
- 🔍 **Clasificación de errores de pronunciación** mediante el modelo **BETO**.  
- 🤖 **Retroalimentación personalizada** de ejercicios sugeridos a través de la **API de GPT-4**.  
- 📱 **Aplicación móvil multiplataforma** desarrollada en **Flutter/Dart**.  
- 🌐 **Servidor backend con FastAPI (Python)** que administra los modelos y expone servicios vía **API REST**.  
- 🗄️ **Almacenamiento y gestión de datos** centralizado en el servidor.  

---

## 🛠️ Tecnologías Utilizadas
### Modelos de IA:
- **OpenAI Whisper** → Transcripción de voz a texto.  
- **mT5** → Corrección gramatical en español.  
- **BETO (BERT en español)** → Clasificación de errores de pronunciación.  
- **GPT-4** → Generación de retroalimentación adaptativa.  

### Desarrollo:
- **Flutter / Dart** → Desarrollo de la aplicación móvil.  
- **Python / FastAPI** → Backend y gestión de modelos.  
- **API REST** → Comunicación entre la app y el servidor.  

---

## 🖼️ Imágenes del Sistema
### 📱 Aplicación Móvil
![Interfaz Principal](./assets/app_home.png)  
*Pantalla inicial de la aplicación móvil desarrollada en Flutter.*

![Ejercicio de Pronunciación](./assets/app_exercise.png)  
*Ejemplo de ejercicios sugeridos al usuario para mejorar su pronunciación.*

### 💻 Backend
![Arquitectura del Sistema](./assets/system_architecture.png)  
*Esquema de la arquitectura con FastAPI y los modelos de IA.*

---


## 📌 Estado del Proyecto
✅ Prototipo funcional con integración de modelos de IA, backend y aplicación móvil.  
🔜 Próximas mejoras: optimización de modelos, refuerzo en UX/UI, y pruebas con usuarios.  

---

> [!IMPORTANT]
> Por motivos de confidencialidad, no es posible compartir el codigo fuente del proyecto, pero estare dispuesto a discutir sobre el proceso de desarrollo.
