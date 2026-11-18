# 🚁 Diagnostic Moteur par IA Hybride (Mistral, RAG, CNN & LSTM)
**Contexte :** Mission R&D Data & IA — Airbus Helicopters (04/2026 – 10/2026)

## 📌 Problématique & Impact
Conception d'un système d'aide à la décision pour le diagnostic technique des moteurs d'hélicoptères à partir de données capteurs (séries temporelles) et de documentation technique.
- **Robustesse du diagnostic :** Améliorée de **60 % à 90 %**.
- **Gain de temps :** Réduction du temps d'analyse de **8 h à 1 h** par diagnostic.
- **Impact financier :** Économie estimée à **1 200 € par intervention d'expert**.

## 🛠️ Architecture Technique
- **Data Engineering :** Pipelines distribués sur **Databricks** (SQL, format **Parquet**) pour l'ingestion et la fiabilisation des logs ERP et fichiers techniques.
- **Analyse des signaux (Deep Learning) :** Modèles **CNN** et **LSTM** pour l'extraction de signatures vibratoires/temporelles et la détection d'anomalies.
- **IA Générative (RAG) :** Pipeline **Retrieval-Augmented Generation** propulsé par **Mistral** pour croiser les anomalies détectées avec les manuels de maintenance.

