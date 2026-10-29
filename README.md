<div align="center">

<img alt="Hatim Adnane" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1f3a,100:c9a227&height=170&section=header&text=Hatim%20Adnane&fontSize=46&fontColor=f5f1e8&fontAlignY=38&desc=Data%20Engineer%20%C2%B7%20Sant%C3%A9%20publique%20%C2%B7%20Web%20%26%20IA%20locale&descAlignY=60&descSize=16&animation=fadeIn" width="100%"/>

[![Portfolio](https://img.shields.io/badge/Portfolio-hatimadnane.fr-0b1f3a?style=for-the-badge)](https://hatimadnane.fr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hatim--adnane-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hatim-adnane/)
[![Email](https://img.shields.io/badge/Email-hatimadnanepro%40gmail.com-c9a227?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hatimadnanepro@gmail.com)

![](https://img.shields.io/badge/Bordeaux-France-0b1f3a?style=flat-square)
![](https://img.shields.io/badge/M1-Data%20Engineering%20%26%20IA%20·%20EFREI-0b1f3a?style=flat-square)
![](https://img.shields.io/badge/Microsoft-PL--300%20certifié-c9a227?style=flat-square&logo=powerbi&logoColor=white)

</div>

---

### En deux phrases

Le jour, je construis les pipelines qui alimentent le pilotage financier des **~150 établissements de santé de Nouvelle-Aquitaine**. Le soir, je livre des **sites en production pour de vrais clients**, de Brie-Comte-Robert à Madagascar, et j'expérimente l'**IA qui tourne en local**.

---

### 🏥 En alternance — ARS Nouvelle-Aquitaine

Apprenti Data Engineer au Pôle Études et Statistiques. Ce que ça veut dire concrètement :

- **Pipeline TDB Financement** : `SAS → R → SharePoint → Power BI`, de la donnée brute des Comptes Financiers, EPRD et RIA jusqu'au tableau de bord utilisé par les équipes de financement
- **Indicateurs hospitaliers 2019–2025** : endettement, résultat, marge brute, CAF, matrices d'évolution par établissement (FINESS) en Python/Plotly
- **Mesures DAX avancées** (dont rendu HTML) pour masse salariale, ETP et comptes financiers
- **Rapports et apps Quarto / Shiny** : dépistage du cancer du sein, soins palliatifs, observatoire de santé
- **IA souveraine** : OCR + RAG sur des contrats avec l'API Albert, outil de tri de CV en Python

`SAS` `R` `Python` `SQL` `Power BI / DAX` `Quarto` `Shiny` `PMSI` `FINESS` `SNDS`

---

### 🚀 En production

| Projet | Pour qui | Ce qu'il y a sous le capot |
|---|---|---|
| **[Kabana Pizz](https://kabanapizz.fr)** · [repo](https://github.com/hatim381/KabanaPizz) | Pizzeria à Brie-Comte-Robert, commandes réelles chaque jour | Front vanilla JS + Node.js serverless (Vercel), PostgreSQL Neon, emails Resend, rate limiter en base, détection d'allergènes, **PWA installable** (136/136 tests), migration DNS sans coupure ni perte de mail |
| **[Sambi Basket](https://sambi-basket.vercel.app)** · [repo](https://github.com/hatim381/Sambi-Basket) | Commerce à Ambanja, Madagascar | E-commerce bilingue **malgache / français**, catalogue piloté par Google Sheets : le client met à jour sa boutique sans toucher au code |
| **Quincaillerie Vao2 Sanfily** · [repo](https://github.com/hatim381/quincaillerie-vao2-sanfily-tulear) | Quincaillerie à Tuléar, Madagascar | React, catalogue réel depuis Google Sheets, panier et commande via WhatsApp / Messenger, pensé pour un marché sans paiement en ligne |
| **[La Colombe Madagascar](https://lacolombemadagascar.com)** | Marque produit | React + Vite + TypeScript, GA4, endpoint serverless pour les avis Google, SEO |
| **[SAFINA](https://safina-five.vercel.app)** | Mon studio | Expérience 3D scrollée : une pirogue traverse vers le Pain de Sucre. React Three Fiber, GSAP, Lenis, océan Gerstner |

---

### 🧪 Data engineering & IA

**KiVendTout** — plateforme e-commerce en architecture médaillon, ~20 services Docker.

```
 Sources ─► Kafka ─► Bronze ─► Silver ─► Gold ─► Dashboards · Telegram
            stream    MinIO     Spark     Spark
              │
              └──► Flink (temps réel)

 Orchestration : Airflow        Automatisations : n8n
```

**RetailVision** — dashboard BI génératif : navigation vocale, KPIs commentés par LLM, chatbot analytique **100 % local** (Ollama + gemma3). Évalué sur WER, latence et exactitude des commandes.

**Veille automatisée (n8n)** — Google News, TLDR Data et scores de foot → extraction → résumé par LLM local ou Gemini → Notion, Telegram, WhatsApp Cloud API.

**Projets académiques** — NLP sur les radios F1 d'Aston Martin (TF-IDF, LDA, sentiment RoBERTa, corrélation FastF1) · classification des retards de vols US (XGBoost + Streamlit) · **Datathon** : détection d'allergènes alimentaires, recall > 99 % (Hugging Face).

---

### 🎲 Les projets pour le plaisir

| | |
|---|---|
| **Pétanque Royale** | Simulateur 3D de pétanque en un seul fichier HTML (Three.js), contre l'IA ou à deux |
| **il_est_16h** | Une blague du bureau devenue émulateur de terminal avec compte à rebours |
| **Carte** | Invitation numérique interactive, réponses enregistrées dans Google Sheets via Apps Script |
| **Polysecours** | Jeu pour apprendre les premiers secours aux personnes en situation de handicap |
| **RuView** | POC de détection de présence par WiFi (CSI) avec un ESP32-S3 |

---

### 🛠️ Ma boîte à outils, rangée par problème

| Quand il faut… | J'utilise |
|---|---|
| Traiter et fiabiliser de la donnée | `Python` `R` `SAS` `SQL` `Spark` |
| Faire circuler la donnée | `Kafka` `Flink` `Airflow` `n8n` `Microsoft Fabric` |
| La rendre lisible | `Power BI / DAX` `Quarto + OJS` `Shiny` `Streamlit` `Plotly` |
| La stocker | `PostgreSQL` `MongoDB` `MinIO` |
| Construire un produit web | `React` `Vite` `TypeScript` `Node.js` `Three.js` |
| Déployer | `Docker` `Vercel` `GitHub Pages` |
| Faire de l'IA | `scikit-learn` `TensorFlow` `Hugging Face` `Ollama` `API Albert` |

---

### 📌 En ce moment

- 🎓 M1 à l'EFREI Bordeaux : Microsoft Fabric (DP-700), sécurité des données
- 📄 Un analyseur de PDF local : OCR, recherche hybride, réponses citées à la page près
- 📱 Kabana Pizz : validation des commandes directement depuis Telegram
- 🎥 [@360bordeaux](https://www.tiktok.com/@360bordeaux) : balades à vélo filmées à l'Insta360 X5

---

<div align="center">

Un projet qui demande à la fois de la rigueur et de l'imagination ? **[Écris-moi](mailto:hatimadnanepro@gmail.com)**.

<img alt="" src="https://capsule-render.vercel.app/api?type=waving&color=0:c9a227,100:0b1f3a&height=90&section=footer" width="100%"/>

</div>
