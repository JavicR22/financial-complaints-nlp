📌 Clasificación de Quejas Financieras con NLP
Este proyecto tiene como objetivo construir un sistema inteligente capaz de clasificar automáticamente quejas de clientes en el sector financiero, utilizando técnicas de Procesamiento de Lenguaje Natural (NLP) y Machine Learning, para luego redirigirlas automáticamente al área responsable dentro de una organización bancaria o financiera.

El sistema está diseñado para funcionar como una solución de backend escalable, integrando modelos de clasificación con un servidor RESTful construido en Spring Boot, y desplegable en contenedores Docker para facilitar su integración en entornos empresariales.

🎯 Objetivo del sistema
🧠 Clasificar automáticamente el tipo de queja (Ej: Tarjeta de crédito, Fraude, Préstamos, Cobros indebidos, etc.) a partir de su descripción en lenguaje natural.

🔄 Simular la redirección de la queja al departamento correspondiente en función de la categoría predicha.

🚀 Desplegar la solución como un servicio REST, integrable en plataformas existentes de atención al cliente o CRM.

🛠️ Tecnologías utilizadas
  - Componente	Herramienta / Framework
  - Lenguaje de backend	Java + Spring Boot
  - Modelo de Machine Learning	Python (Scikit-learn, TensorFlow o PyTorch)
  - Procesamiento de texto	NLP con HuggingFace Transformers / spaCy
  - Interfaz REST para inferencia	FastAPI o Flask (microservicio Python)
  - Despliegue y contenedores	Docker
  - Base de datos: PostgreSQL o MongoDB
