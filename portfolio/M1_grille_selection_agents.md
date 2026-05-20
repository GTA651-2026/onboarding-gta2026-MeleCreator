# M1 — Grille de sélection et évaluation de solutions IA

> Comparez **Brex** (CFO virtuel), **Salesforce Einstein** (aide à la décision commerciale)
> et **Microsoft Copilot 365** (productivité) sur 5 critères, pour **deux contextes** :
> une PME de 50 employés et une grande entreprise de 500+ employés.
> Concluez par une **recommandation argumentée par contexte**.
>
> Exportez en PDF et déposez `M1_grille_selection_agents.pdf` dans ce dossier.
> Mettez à jour `ai-usage.md` à la racine du dépôt (obligatoire, même si « Aucun »).

---

## Contexte 1 — PME de 50 employés

_PME québécoise de services professionnels ou commerce en ligne, maturité numérique moyenne, budget IA limité à 30-50 k€ annuels, équipe IT légère (1-2 personnes, externalisation partielle)._

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** _(nommez le spécialiste que l'agent remplace/augmente)_ | Augmente le contrôleur/trésorier en fournissant une visibilité de trésorerie et des recommandations de cash management. | Augmente le responsable commercial/CRM pour prioriser les opportunités et calibrer les prévisions. | Augmente l’équipe opérationnelle en agissant comme assistant numérique pour rédaction, réunion et suivi de tâches. |
| **2. Impact d'affaires** _(1-5 + justification en 1 phrase)_ | 4 — améliore la gestion de la trésorerie et réduit le besoin d’expertise financière externe. | 3 — utile si la PME a déjà un CRM, mais le ROI est plus long et dépend du volume commercial. | 4 — fort levier de productivité pour des équipes polyvalentes dans un contexte ressource limité. |
| **3. Faisabilité PME** _(1-5 + données, compétences, intégration)_ | 4 — déploiement rapide pour PME avec account-based finance, mais nécessite une connexion bancaire et un minimum de discipline financière. | 2 — exige une base Salesforce ou CRM mature, intégration de données et compétences en configuration IA. | 4 — compatible avec Microsoft 365 déjà présent dans la majorité des PME et nécessite surtout de la formation utilisateur. |
| **4. Coût estimé** _(ordre de grandeur annuel + TCO si pertinent)_ | 15-25 k€ par an, avec coût additionnel pour connecteurs bancaires et support financier. | 20-35 k€ par an + frais d’intégration et de personnalisation CRM. | 8-15 k€ par an en licence Copilot 365, plus formation et accompagnement pour adoption. |
| **5. Risque principal** _(et mitigation concrète)_ | Risque de confidentialité des données financières locales ; atténuer par des contrats clairs avec le fournisseur et la mise en place de contrôles d’accès conformes Loi 25. | Risque d’une solution trop lourde pour la PME ; atténuer en commençant par un pilote interne sur un segment de clients. | Risque d’adoption faible et de sur-surcharge d’informations ; atténuer par un plan de formation ciblé et des guides internes en français. |

### Recommandation pour la PME

Pour une PME de 50 employés, Microsoft Copilot 365 est la meilleure solution à déployer en premier. Sa valeur business est plus immédiate, sa faisabilité est élevée dans un environnement déjà Microsoft, et elle répond bien aux priorités d’efficacité des petites équipes québécoises, tout en limitant les barrières liées à la Loi 25 et à l’usabilité en français.

---

## Contexte 2 — Grande entreprise de 500+ employés

_Grande entreprise québécoise de services financiers ou manufacturing avec ERP/CRM existants (SAP ou Oracle, Salesforce possible), gouvernance solide, sponsor métier (DAF ou CTO) et exigence de conformité. Budget IA plus important, capable de financer des intégrations sophistiquées._

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** | Augmente le directeur financier / trésorier corporate avec une vue consolidée de cash et un soutien à la planification des liquidités. | Augmente le directeur commercial et le CRM en fournissant des recommandations sur le pipeline et l’engagement client. | Augmente le centre de services partagés, le support interne et les collaborateurs en tant qu’assistant de productivité intégré au digital workplace. |
| **2. Impact d'affaires** _(1-5 + justification)_ | 4 — utile si l’entreprise gère des flux de trésorerie complexes, mais l’impact dépend du périmètre financier global. | 5 — fort impact si le CRM est déjà central, car il améliore les ventes, le marketing et le service client à large échelle. | 4 — impact élevé sur l’efficacité et la collaboration, mais moins transformateur que des usages métier ciblés. |
| **3. Faisabilité grande entreprise** _(1-5 + intégration systèmes, gouvernance)_ | 3 — intégration possible avec les systèmes financiers, mais nécessite audit de sécurité, gouvernance et localisations des données. | 5 — très faisable si l’entreprise utilise Salesforce ; le levier est maximal avec une gouvernance IA déjà en place. | 4 — élevée pour les structures déjà sur Microsoft 365, mais demande un sponsor DSI et un plan d’adoption global. |
| **4. Coût estimé** _(licences + intégration + formation)_ | 80-120 k€ TCO, incluant licences, intégration aux ERP bancaires et support financier. | 120-180 k€ TCO selon le périmètre CRM, l’intégration de données et la formation des équipes commerciales. | 60-100 k€ TTC pour licences, formation et accompagnement à l’adoption d’une digital workplace. |
| **5. Risque principal** _(et mitigation)_ | Risque de fragmentation des données financières et de gouvernance ; atténuer par des règles de segmentation, un centre d’excellence finance et un audit régulier. | Risque de dépendance à un seul écosystème CRM ; atténuer par une stratégie de gouvernance de données IA et des tableaux de bord de performance. | Risque de shadow IT et mauvaise utilisation ; atténuer par une politique de sécurité Microsoft, des formations en français et un support interne dédié. |

### Recommandation pour la grande entreprise

Pour une grande entreprise de 500+ employés, Salesforce Einstein est la meilleure solution si la stratégie métier repose sur le CRM et le commerce client. Sa capacité d’intégration avec un écosystème Salesforce existant et son impact sur les ventes en font un choix plus stratégique que Brex ou Copilot 365, même si Copilot 365 reste un excellent second choix pour la productivité digitale.

---

## Synthèse — ce que la grille révèle

Le critère décisif est l’alignement entre l’agent et la valeur métier existante : productivité et simplicité pour la PME, intégration CRM/ERP et gouvernance pour la grande entreprise. En pratique, un choix IA pertinent ne se fait pas sur la technologie seule, mais sur la maturité des systèmes, la présence d’un sponsor et la capacité à gérer les données de façon conforme à la Loi 25 au Québec.

Ce que cela enseigne : pour un petit acteur, privilégier une solution à fort effet de levier et faible friction ; pour un grand groupe, privilégier une solution qui s’insère dans l’écosystème existant et peut être gouvernée de bout en bout.

---

## Liste de contrôle de remise

- [x] Les 3 agents sont comparés sur les mêmes 5 critères dans les deux contextes
- [x] Le rôle spécialisé orchestré est nommé précisément pour chaque agent
- [x] Les scores sont justifiés (pas juste des chiffres)
- [x] La recommandation diffère — ou est explicitement justifiée comme identique — entre PME et grande entreprise
- [x] Le contexte d'une organisation québécoise est pris en compte (Loi 25, marché local, talent)
- [x] `ai-usage.md` mis à jour à la racine du dépôt

> **Crédit :** Jalon M1 — pass/fail (1,5 % du cours). Préparation directe à l'**Examen-cas 1** (S05, 25 %).
