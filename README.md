<!-- Profile README @filou337 — octobre 2026 — lisible en 10 secondes, détails repliables -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:574A24,100:C99A2E&height=190&section=header&text=Philippe%20Roumbo&fontSize=46&fontColor=FDF6E2&fontAlignY=36&desc=Analytics%20Engineer%20%C2%B7%20Data%20Engineer&descSize=18&descAlignY=58&animation=fadeIn" alt="Philippe Roumbo, Analytics Engineer et Data Engineer" />
</p>

<p align="center">
  <b>Je transforme des données brutes en modèles fiables, testés et documentés, prêts pour la décision.</b>
</p>

<p align="center">
  <img alt="Disponible maintenant, CDI ou CDD" src="https://img.shields.io/badge/%E2%97%8F%20Disponible-CDI%20%2F%20CDD-3E8E4E?style=for-the-badge">
  <a href="mailto:roumbop@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-roumbop%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/philippe-roumbo-69b42a2ab/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Philippe%20Roumbo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://filou337.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-filou337.github.io-574A24?style=for-the-badge&logo=githubpages&logoColor=white"></a>
</p>

<p align="center">
  <a href="#-en-bref">En bref</a> ·
  <a href="#-comment-je-travaille-la-donnée">Pipeline</a> ·
  <a href="#-stack">Stack</a> ·
  <a href="#-expérience">Expérience</a> ·
  <a href="#-projets">Projets</a> ·
  <a href="#-ce-que-je-recherche">Recherche</a>
</p>

---

## 👋 En bref

| | |
|---|---|
| **Rôles visés** | Analytics Engineer · Data Engineer · Consultant Data · Data / Business Analyst |
| **Contrat** | CDI ou CDD, disponible dès maintenant |
| **Lieu** | Île-de-France, hybride ou sur site |
| **Formation** | Master Big Data & Business Intelligence, Université Sorbonne Paris Nord (2026) |
| **Cœur de stack** | Azure Data Factory · Databricks · PySpark · SQL · Power BI · Azure DevOps |
| **Langues** | Français (C2) · Anglais (B2) · Espagnol (A2) |

---

## 🧱 Comment je travaille la donnée

```mermaid
flowchart LR
    S["Sources<br/>ERP · CSV · API"] --> B["Bronze<br/>brut ingéré"]
    B --> SI["Silver<br/>nettoyé · contrôlé"]
    SI --> G["Gold<br/>modèles en étoile"]
    G --> D["Décision<br/>Power BI · KPI"]
    classDef bronze fill:#9C6630,color:#FDF6E2,stroke:#9C6630
    classDef silver fill:#A8A491,color:#2E2712,stroke:#A8A491
    classDef gold fill:#C99A2E,color:#2E2712,stroke:#C99A2E
    classDef base fill:#574A24,color:#FDF6E2,stroke:#574A24
    class S,D base
    class B bronze
    class SI silver
    class G gold
```

À chaque couche : **tests de qualité**, **documentation** et **versioning** (Git, CI/CD).

---

## 🧰 Stack

| Étape | Outils |
|---|---|
| **Ingestion** | ![ADF](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?logo=microsoftazure&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white) |
| **Transformation** | ![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white) ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white) ![Scala](https://img.shields.io/badge/Scala-DC322F?logo=scala&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4) |
| **Modélisation & BI** | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=000) ![DAX](https://img.shields.io/badge/DAX%20%2F%20Power%20Query-574A24) ![Measure Killer](https://img.shields.io/badge/Measure%20Killer-2E2712) |
| **Qualité & livraison** | ![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?logo=azuredevops&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![CI/CD](https://img.shields.io/badge/CI%2FCD-2E2712) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) |

---

## 💼 Expérience

**Data Analyst (stage)** · Colas Digital Solutions · *mars – sept. 2026*
> Ingestion et transformation en architecture Bronze / Silver / Gold, modèles en étoile et dashboards Power BI, gouvernance et qualité des données, CI/CD sous Azure DevOps, conduite d'un projet d'IA agentique.

<details>
<summary>Voir le détail</summary>

- Recueil des besoins métier et traduction en règles de gestion, modèles de données et reporting
- Ingestion, nettoyage et transformation avec ADF, Databricks, PySpark et Scala
- Contrôles de cohérence et de complétude, documentation, suivi des évolutions dans Azure DevOps
- Gouvernance des données : règles de qualité, référentiels et documentation
- Modèles en étoile et dashboards Power BI (Power Query, DAX), audits Measure Killer
- Travail en sprints Agile avec les équipes métier et techniques

</details>

**Consultant Data (stage)** · DrNIKO / TECHNIKO · *nov. 2025 – févr. 2026*
> Cadrage des besoins clients, benchmarks et grilles de notation de solutions d'IA médicale, recommandations et supports de synthèse.

---

## 📌 Projets

> 🛠️ **Refonte en cours.** Mes dépôts sont en train d'être reconstruits autour de l'**analytics engineering** : transformations modélisées, tests de qualité, documentation des modèles et couches prêtes pour la BI.

<!-- Quand les dépôts sont prêts, remplacer l'encart par ce tableau :
| Projet | Ce qu'il montre | Stack |
|---|---|---|
| [nom-du-repo](https://github.com/filou337/nom-du-repo) | Une phrase sur le résultat | `SQL` `PySpark` `Power BI` |
-->

---

## 🏆 Réalisations

- 🎓 **Master Big Data & Business Intelligence**, Université Sorbonne Paris Nord (2026)
- 🥇 **Coach au Hackathon Colas** (mai 2026) : l'équipe ESTP / EFREI accompagnée a remporté la **1re place**
- 🤝 **Bénévole chez Linkee** : actions solidaires contre la précarité alimentaire

---

## 🎯 Ce que je recherche

Un poste où je peux **construire les modèles de données entre l'ingestion et la BI**, sur une stack cloud (Azure, Databricks) avec de vraies pratiques de **CI/CD**, et transformer des besoins métier en **indicateurs fiables**.

<details>
<summary>Ma façon de travailler</summary>

- **Business first** : comprendre le contexte, clarifier le problème, définir des KPI simples
- **Qualité dès la conception** : tests, contrôles de cohérence et documentation intégrés aux modèles
- **Reproductibilité** : Git, CI/CD, structure de projet propre, README détaillés
- **Pédagogie** : des résultats compréhensibles et des recommandations actionnables
- **Éthique** : attention aux sources, aux biais et à l'usage responsable de l'IA

</details>

<details>
<summary>Stats GitHub</summary>
<br>
<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=filou337&layout=compact&langs_count=8&theme=github_dark&bg_color=00000000">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=filou337&layout=compact&langs_count=8&bg_color=00000000" height="150" alt="Langages les plus utilisés">
</picture>
</p>
</details>

---

<p align="center">
  <sub>Mis à jour en octobre 2026 · Bobigny, Île-de-France</sub>
</p>
