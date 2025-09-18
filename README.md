# InsightReach — 360° Customer Analysis

**Module 1 Capstone Project - Data Science**
*Facundo Acosta - Junior Data Scientist*

Comprehensive analysis of customer and business data to optimize targeted marketing strategies through EDA, Yelp API integration, and predictive modeling.

---

## Key Results

- **Predictive Model**: XGBoost with R² = 0.89 for predicting customer spending
- **Market Gaps**: Identification of +25.3% unmet demand in seafood
- **Segmentation**: 3,186 customers analyzed by socioeconomic stratum and preferences
- **Recommendations**: Personalized recommendation system with 85% accuracy

## 🏗Project Structure
```bash
PI1_Insightreach/
Notebooks:
- Avance_1_EDA_Facundo_Acosta_v11.ipynb
- Avance_2_API_YELP_Facundo_Acosta_v11.ipynb
- Avance_3_Analisis_Final_Facundo_Acosta_v11.ipynb

Datasets:
Input:
- base_datos_restaurantes_USA_v2.csv
Output (Auto-generated):
- clientes_miami_clean.csv - Data by city (Avance_1_EDA_Facundo_Acosta_v11)
- yelp_miami_limpio_[timestamp].csv - Cleaned API data (Avance_2_API_YELP_Facundo_Acosta_v11)
  
Docs:
- README_Facundo_Acosta.pdf
- Recommendations_Facundo_Acosta.pdf
- requirements.txt
- .env.example
- README.md
```

## Quick Installation

```bash
# Clone repository
git clone https://github.com/Facundosta/InsightReach-360.git
cd InsightReach-360

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Configure environment variables
cp .env.example .env
# Edit .env with your API credentials
```

## Tech Stack
```bash
- Language: Python 3.9+
- Data Analysis: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- ML & Modeling: Scikit-learn, XGBoost
- APIs: Requests, Yelp Fusion API
- Environment: Jupyter Notebook
```

## Methodology
```
- Complete EDA: Cleaning and exploratory analysis of customer data
- Yelp API Integration: Obtained 200 businesses from Miami
- Predictive Modeling: Regression to predict average spending
- Recommendation System: Cosine similarity based on preferences
- Strategic Analysis: Supply-demand gaps and segmentation
```

## Next Steps
```
- Model deployment as an API (FastAPI)
- Integration with existing CRM system
- Interactive monitoring dashboard
- Expansion to other cities (NY, LA)
```

👨‍💻 Author
**Facundo Acosta**  
Junior Data Scientist 
[🔗 LinkedIn](https://www.linkedin.com/in/facundo-acosta-marketing/)  

*Project developed as part of the Henry Data Science Bootcamp*
