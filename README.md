# Hi, I'm Patrick Jastia 👋

**Data analyst and machine learning practitioner based in the Philippines.** I spent 15+ years in IT helpdesk and technical support, keeping software and systems running for global customers. Now I build Python models that turn messy operational data into decisions.

Support work taught me two things that carry straight into data science: **find the root cause before you fix anything**, and **explain the answer so a non-technical person can act on it**. Every project below ends with a recommendation for the people who would use it, and an honest list of what the model can't do yet.

---

### 🔭 Featured projects

| Project | Question | Approach | Result |
|---|---|---|---|
| [**When Does an LLM Earn Its Cost?**](https://github.com/Funkchini/Airline-Sentiment-Classic-NLP-vs-LLM) | Is a free rule-based tool good enough for customer-tweet sentiment, or is an LLM worth paying for? | VADER & TextBlob → NLTK Naive Bayes with negation handling → zero-shot Claude API | Naive Bayes 0.77 accuracy; Claude 0.87 accuracy / 0.82 macro-F1 with no training data |
| [**Who Will Buy Again?**](https://github.com/Funkchini/Retail-Repeat-Purchase-Prediction) | Which customers will purchase again in the next 3 months? | RFM feature engineering on 541K transactions, time-based cutoff to prevent leakage, Random Forest | ROC-AUC 0.72; flags 61% of customers who won't return |
| [**What Should an AI Professional Be Paid?**](https://github.com/Funkchini/AI-Salary-Prediction) | What salary should a hiring team expect for an AI role? | Log-target regression, leakage removal, `Pipeline` + `GridSearchCV` Random Forest vs linear baseline | Test MAE ≈ $29K on a $142K median market |
| [**Mapping the Philippines' Seismic Zones**](https://github.com/Funkchini/Philippine-Earthquake-Seismic-Zones) | What distinct seismic zones exist, to support disaster preparedness? | Unsupervised K-Means vs DBSCAN on 26,609 USGS earthquakes (location + depth) | 3 zones, silhouette 0.60; one zone holds 70% of events and 228 of 319 M6+ quakes |
| [**Why Don't Passengers Recommend PAL?**](https://github.com/Funkchini/Philippine-Airlines-Review-Analysis) | Which service areas decide whether a passenger recommends Philippine Airlines? | Data cleaning + exploratory analysis of 891 reviews | Value for money (r = 0.77) and ground service (r = 0.71) matter more than cabin crew |

---

### 🛠️ Toolkit

**Languages & data:** Python · SQL · pandas · NumPy  
**Machine learning:** scikit-learn (pipelines, cross-validation, grid search) · classification · regression · clustering · feature engineering · model evaluation  
**NLP & AI:** NLTK · VADER · TextBlob · Anthropic Claude API · prompt design for classification  
**Visualisation & apps:** Matplotlib · Seaborn · Streamlit  
**Workflow:** Jupyter · Git & GitHub · `.env`-based secrets handling

### 📚 Currently

Building on the Uplift Code Camp **Python for Data & AI** program: SQL for analytics, APIs, AI applications and agentic AI.

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/patrick-jastia/) · patrickjastia@gmail.com
