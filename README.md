# InsightReach — Conociendo al Cliente 360°

**Facundo Acosta — Científico de Datos Junior**

🚀 *InsightReach integra datos propios y externos (ej. API de Yelp) para segmentar clientes y generar recomendaciones accionables que optimizan campañas de marketing local.*

![demo](assets/demo.gif)  <!-- opcional: captura de notebook o gif corto -->

---

## 📌 Contenido
- ⚙️ [Instalación](#instalación)
- 📂 [Estructura del Proyecto](#estructura-del-proyecto)
- 🧪 [Reproducibilidad](#reproducibilidad)
- 📈 [Resultados Clave](#resultados-clave)
- 🚀 [Próximos Pasos](#próximos-pasos)
- 👤 [Autor](#autor)

---

#⚙Instalación

  1. Clonar el repositorio:
     ```bash
     git clone https://github.com/tu_usuario/insightreach.git
     cd insightreach
  2. Crear entorno virtual e instalar dependencias:
     python -m venv .venv
        # Activar entorno:
        # macOS/Linux
        source .venv/bin/activate
        # Windows (PowerShell)
        .venv\Scripts\Activate.ps1
    
        pip install -r requirements.txt
  
  3. Configurar variables de entorno:
      Copiar el archivo .env.example y renombrarlo como .env.
      Completar con tus credenciales (ejemplo: API Key de Yelp).
  
  4. Abrir los notebooks:
       jupyter notebook
   
## 📂 Estructura del Proyecto

.
├── notebooks/          # Jupyter Notebooks (EDA, modelado, tests)
├── src/                # Scripts Python (módulos de funciones/clases)
├── data/               # Datos locales (ignorado por git)
├── assets/             # Gráficos, capturas y demo.gif
├── requirements.txt    # Dependencias del proyecto
├── .env.example        # Variables de entorno de ejemplo
├── .gitignore          # Archivos ignorados por git
└── README.md           # Documentación principal

## 🧪 Reproducibilidad
    Todos los notebooks tienen semillas aleatorias fijadas para garantizar resultados consistentes.
    Librerías utilizadas están versionadas en requirements.txt.
    Variables sensibles están gestionadas mediante .env (no se suben al repo).

## 📈 Resultados Clave
    Limpieza y transformación de datos provenientes de múltiples fuentes.
    Conexión a la API de Yelp para enriquecer el dataset.
    Análisis exploratorio de datos (EDA) con gráficos y estadísticas.
    Modelado predictivo para estimar gasto promedio por cliente.
    Sistema de recomendación basado en similitud de preferencias.

## 🚀 Próximos Pasos
    Despliegue del modelo en API (Flask/FastAPI).
    Integración con CRM para automatización de campañas.
    Sistema de feedback para mejorar recomendaciones.
    Monitoreo continuo de desempeño del modelo.
    Expansión a otras ciudades.

## 👤 Autor
    Facundo Acosta
    Científico de Datos Junior
    LinkedIn: https://www.linkedin.com/in/facundo-acosta-marketing/
