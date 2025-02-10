# Chatbot con BlenderBot y Transformers  

Este proyecto implementa un **chatbot conversacional** en la terminal utilizando el modelo [`facebook/blenderbot-400M-distill`](https://huggingface.co/facebook/blenderbot-400M-distill) de **Facebook AI**.  

El chatbot mantiene un **historial de conversación** para mejorar la coherencia en los diálogos y permite una interacción fluida a través de la consola.  

![Chatbot](./chatbot.webp)

## 🚀 Características  

✔ Basado en **Transformers** para generación de respuestas avanzadas.  
✔ Uso del modelo **BlenderBot 400M** para conversaciones naturales.  
✔ **Historial de conversación** para mejorar la coherencia de las respuestas.  
✔ Interfaz en línea de comandos simple y funcional.  

## 🛠 Tecnologías Utilizadas  

- **Python**: Lenguaje principal para el desarrollo del chatbot.  
- **Transformers**: Biblioteca de Hugging Face para modelos de lenguaje avanzado.  
- **BlenderBot 400M**: Modelo de Facebook AI especializado en diálogo.  

## 📂 Estructura del Proyecto  

```
📦 chatbot-console
├── 📜 chatbot.py           # Código principal del chatbot
└── 📜 README.md            # Documentación del proyecto
```

## 🔧 Instalación y Uso  

1️⃣ **Clona el repositorio**  
```bash
git clone https://github.com/tu_usuario/chatbot-console.git
cd chatbot-console
```

2️⃣ **Crea un entorno virtual e instala las dependencias**  
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3️⃣ **Ejecuta el chatbot**  
```bash
python chatbot.py
```

4️⃣ **Chatea con el chatbot**  
Escribe mensajes en la terminal y el chatbot responderá. Para salir, usa:  
```
exit
```

## 📌 Futuras Mejoras  

- **Optimización del historial de conversación** para mayor coherencia.  
- **Implementación de una interfaz gráfica (GUI)** para una mejor experiencia de usuario.  
- **Integración con API de voz** para interacción por audio.  
