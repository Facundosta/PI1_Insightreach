# 🎯 InsightReach — Análisis 360° de Clientes

**Proyecto Integrador M1 - Data Science**  
*Facundo Acosta - Científico de Datos Junior*

Análisis integral de datos de clientes y negocios para optimizar estrategias de marketing segmentado mediante EDA, integración con API Yelp y modelado predictivo.

---

## 📊 Resultados Destacados

- **📈 Modelo Predictivo**: XGBoost con R² = 0.89 para predecir gasto de clientes
- **🔍 Brechas de Mercado**: Identificación de +25.3% de demanda insatisfecha en mariscos
- **🎯 Segmentación**: 3,186 clientes analizados por estrato socioeconómico y preferencias
- **🤖 Recomendaciones**: Sistema de recomendación personalizada con 85% de precisión

## 🏗️ Estructura del Proyecto
```bash
PI1_Insightreach/
Notebooks:
- Avance_1_EDA_Facundo_Acosta_v11.ipynb
- Avance_2_API_YELP_Facundo_Acosta_v11.ipynb
- Avance_3_Analisis_Final_Facundo_Acosta_v11.ipynb

Datasets:
Input:
- base_datos_restaurantes_USA_v2.csv
Output (Auto-generados):
- clientes_miami_clean.csv - Datos por ciudad (Avance_1_EDA_Facundo_Acosta_v11)
- yelp_miami_limpio_[timestamp].csv - Datos limpios de API (Avance_2_API_YELP_Facundo_Acosta_v11)
  
Docs:
- README_Facundo_Acosta.pdf
- Recommendations_Facundo_Acosta.pdf
- requirements.txt
- .env.example
- README.md
```

## ⚙️ Instalación Rápida

```bash
# Clonar repositorio
git clone https://github.com/Facundosta/InsightReach-360.git
cd InsightReach-360

# Crear entorno virtual
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate  # Windows

# Instalar dependencias
pip install -r requirements.txt

# Configurar variables de entorno
cp .env.example .env
# Editar .env con tus credenciales API
```

🛠️ Stack Tecnológico
```bash
- Lenguaje: Python 3.9+
- Análisis de Datos: Pandas, NumPy
- Visualización: Matplotlib, Seaborn
- ML & Modelado: Scikit-learn, XGBoost
- APIs: Requests, Yelp Fusion API
- Entorno: Jupyter Notebook
```

📋 Metodología
```
- EDA Completo: Limpieza y análisis exploratorio de datos de clientes
- Integración API Yelp: Obtención de 200 negocios de Miami
- Modelado Predictivo: Regresión para predecir gasto promedio
- Sistema de Recomendación: Cosine similarity basado en preferencias
- Análisis Estratégico: Brechas oferta-demanda y segmentación
```

🚀 Próximos Pasos
```
- Despliegue del modelo como API (FastAPI)
- Integración con sistema CRM existente
- Dashboard interactivo para monitoreo
- Expansión a otras ciudades (NY, LA)
```

👨‍💻 Autor
**Facundo Acosta**  
Científico de Datos Junior  
[🔗 LinkedIn](https://www.linkedin.com/in/facundo-acosta-marketing/)  

*Proyecto desarrollado como parte del Bootcamp de Data Science de Henry*
