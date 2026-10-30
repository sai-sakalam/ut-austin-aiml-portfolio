# AI & Machine Learning Portfolio

Projects I completed in the **UT Austin (Texas Executive Education) Post Graduate Program in Artificial Intelligence and Machine Learning: Business Applications** – from exploratory analysis and classical ML to deep learning, LLM/RAG systems and model deployment.

**Author:** Sai Gavaskar Sakalam

**Program result:** GPA **4.33 / 4.33** – A+ in all 7 courses ([verify grade sheet](https://www.mygreatlearning.com/certificate/FSXIFKVZ))

## Projects

| Project | Course | Key result | Tools |
|---|---|---|---|
| [FoodHub – Food Delivery Order Analysis](01-foodhub-eda/) | Python Foundations | 38.7% of orders unrated; weekday delivery 6 min slower | Python, pandas, matplotlib, seaborn |
| [Personal Loan Campaign – Customer Conversion Model](02-personal-loan-classification/) | Machine Learning | Recall **0.965** (post-pruned decision tree) | Python, scikit-learn, Logistic Regression, Decision Trees |
| [EasyVisa – Visa Approval Prediction](03-easyvisa-visa-approval/) | Advanced Machine Learning | F1 **0.819**, recall 0.875 (tuned Gradient Boosting) | Python, scikit-learn, imbalanced-learn (SMOTE, undersampling), Bagging, Random Forest, AdaBoost, Gradient Boosting |
| [ReneWind – Wind Turbine Failure Prediction](04-renewind-predictive-maintenance/) | Introduction to Neural Networks | Test recall **0.883**, F1 0.899 (neural network) | Python, TensorFlow/Keras, scikit-learn |
| [Medical Assistant – RAG over a Clinical Manual](05-medical-assistant-rag/) | NLP with Generative AI | Grounded answers over a 4,114-page manual on one T4 GPU | Python, LangChain, ChromaDB, sentence-transformers, llama-cpp (Mistral 7B), Hugging Face Hub |
| [HelmNet – Safety Helmet Detection](06-helmnet-helmet-detection/) | Introduction to Computer Vision | "Without helmet" recall **0.90** on test (VGG-16) | Python, TensorFlow/Keras, VGG-16, OpenCV |
| [SuperKart – Sales Forecasting and Model Deployment](07-superkart-sales-forecasting/) | Model Deployment | R² **0.932**, MAPE 3.8%; deployed as API + web app | Python, scikit-learn, Flask, Streamlit, Docker, Hugging Face Spaces |

## Skills shown
- **Data analysis:** EDA, data cleaning, feature engineering, business insights
- **Machine learning:** Logistic Regression, Decision Trees (pre/post pruning), Bagging, Random Forest, AdaBoost, Gradient Boosting, SMOTE / undersampling, hyperparameter tuning, handling class imbalance
- **Deep learning:** Neural networks, CNNs, transfer learning (VGG-16), data augmentation
- **NLP / GenAI:** LLM prompt engineering, RAG with LangChain + ChromaDB, embeddings, LLM-as-judge evaluation
- **MLOps:** scikit-learn pipelines, model serialisation, Flask API, Streamlit app, Docker, Hugging Face Spaces

## Repo layout
Each project folder has a `README.md` (problem, approach, results), the notebook, a `requirements.txt`, and a `data/README.md` that explains which data files are needed. Data files are not pushed.
