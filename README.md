# HinergoGym
A business case with demo data
# 🏋️‍♂️ HinergoGym – Business Case & Demo Dataset

**A complete fictional dataset and business case for data modeling, DAX training, and Power BI storytelling.**

## 📘 Description

HinergoGym is a demo scenario centered around a mid-sized Italian company that designs, produces, and distributes modular gym and fitness equipment.  
The dataset includes 3 full years of sales data (2023–2025), complete dimensional modeling, and simulated customer behavior (B2C + B2B).

---

## 🗂️ Data model structure

### 🔸 Fact Tables
- `FactSales`: line-level sales (order, product, qty, discount, margin, campaign)
- `FactOrderSatisfaction`: order-level satisfaction score (1–5)

### 🔹 Dimension Tables
- `DimDate`: full calendar table
- `DimCustomer`: B2B and B2C customers (region, industry, segment)
- `DimProduct`, `DimSubcategory`, `DimCategory`
- `DimLocation`: sales/production/logistics sites (Italy, EU, US)
- `DimCompany`: legal entity structure
- `DimChannel`: Online vs Retail
- `DimCampaign`: promotional campaigns (with discount %)
- `DimOrder`: one row per order
- `DimCurrencyRate`: daily conversion rates (EUR-based)

---

## 🎯 Use cases
- Data modeling & star schema
- DAX formula challenges (basic to guru level)
- Storytelling on customer behavior, satisfaction, campaigns, and profitability
- Training on multivalued currencies and decile-based customer analysis
- Predictive logic and Power BI visuals

---

## 👤 Author / Contatti

**David Bianconi**  
✉️ davidbianconi@outlook.it

---

## 🇮🇹 Versione Italiana

**Caso aziendale completo e dataset fittizio per esercizi su Power BI, DAX e modelli dimensionali.**

### 📖 Descrizione
HinergoGym è un’azienda italiana del settore fitness, con sedi produttive e commerciali in Europa e Nord America. Il modello include vendite B2C e B2B, campagne marketing, canali, segmenti cliente e indicatori di soddisfazione.

### 📚 Obiettivi didattici
- Modellazione a stella e gestione currency
- Misure DAX a vari livelli di difficoltà
- Visual storytelling con stagionalità, margini e performance
- Segmentazione avanzata clienti (decili, churn, retention)

---

## 📄 Licenza / License

Il presente materiale è concesso in licenza per:
- uso **individuale e personale**, anche commerciale,
- **NON è consentito l’utilizzo per attività didattiche a terzi a scopo di lucro**, come corsi a pagamento o formazione aziendale.

In tali casi è necessaria **autorizzazione scritta dell’autore**.

This material is licensed for:
- **individual and personal use**, including commercial purposes.
- It is **NOT permitted to use this for teaching third parties for profit** (e.g., paid training, consulting bootcamps).

**Explicit written permission from the author is required** in such cases.
