# Hi, I'm Patrick Jastia 👋

**Data analyst and machine learning practitioner based in the Philippines.** I spent 15+ years in IT helpdesk and technical support, keeping software and systems running for global customers. Now I build Python models that turn messy operational data into decisions.

Support work taught me two things that carry straight into data science: **find the root cause before you fix anything**, and **explain the answer so a non-technical person can act on it**. Every project below ends with a recommendation for the people who would use it, and an honest list of what the model can't do yet.

---

### 🔭 Featured projects

| Project | Question | Approach | Result | Recommendation to Stakeholders |
|---|---|---|---|---|
| [**Airline Sentiment: Classic NLP vs LLM**](https://github.com/Funkchini/Airline-Sentiment-Classic-NLP-vs-LLM) | Is a free rule-based tool good enough for customer-tweet sentiment, or is an LLM worth paying for? | Lexicons vs Naive Bayes vs zero-shot Claude | Naive Bayes 0.77 accuracy; Claude 0.87 accuracy / 0.82 macro-F1 with no training data | **Customer experience teams:** use the near-free Naive Bayes model for high-volume sentiment dashboards, and pay for the LLM only where nuance matters, such as routing complaints vs neutral enquiries. |
| [**Retail Repeat Purchase Prediction**](https://github.com/Funkchini/Retail-Repeat-Purchase-Prediction) | Which customers will purchase again in the next 3 months? | RFM features + Random Forest, leakage-safe split | ROC-AUC 0.72; flags 61% of customers who won't return | **Marketing / CRM:** score customers monthly and target win-back offers at those least likely to return, instead of blanket discounts. Launch retention campaigns before the Q4 peak. |
| [**AI Salary Prediction**](https://github.com/Funkchini/AI-Salary-Prediction) | What salary should a hiring team expect for an AI role? | Tuned Random Forest, log-salary target | Test MAE ≈ $29K on a $142K median market | **HR & finance:** set pay bands from medians by level and country rather than market averages, and budget new roles with the model. Promoting mid-level staff is far cheaper than hiring seniors. |
| [**Philippine Earthquake Seismic Zones**](https://github.com/Funkchini/Philippine-Earthquake-Seismic-Zones) | What distinct seismic zones exist, to support disaster preparedness? | K-Means vs DBSCAN clustering | 3 zones, silhouette 0.60; one zone holds 70% of events and 228 of 319 M6+ quakes | **Disaster-risk agencies & LGUs:** prioritise preparedness funding and early warning for Eastern Visayas and Mindanao. Enforce stricter building standards in shallow-quake zones. |
| [**Philippine Airlines Review Analysis**](https://github.com/Funkchini/Philippine-Airlines-Review-Analysis) | Which service areas decide whether a passenger recommends Philippine Airlines? | Data cleaning + EDA | Value for money (r = 0.77) and ground service (r = 0.71) matter more than cabin crew | **Airline management:** fix value perception and ground service first, promote cabin crew as a strength, and track recommendation rate by route and seat class. |

---

### 🛠️ Toolkit

**Languages & data:** Python · SQL · pandas · NumPy  
**Machine learning:** scikit-learn (pipelines, cross-validation, grid search) · classification · regression · clustering · feature engineering · model evaluation  
**NLP & AI:** NLTK · VADER · TextBlob · Anthropic Claude API · prompt design for classification  
**Visualisation & apps:** Matplotlib · Seaborn · Tableau · Power BI · Streamlit  
**Workflow:** Jupyter · Git & GitHub

### 📚 Currently

Building on the Uplift Code Camp **Python for Data & AI** program: SQL for analytics, APIs, AI applications and agentic AI.

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/patrick-jastia/) · patrickjastia@gmail.com
