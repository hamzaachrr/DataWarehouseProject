📊 Projet Data Warehouse et Analytics avec SQL Server

Ce projet illustre le développement complet d’une solution de data warehouse et d’analyse de données, visant à centraliser et transformer des données provenant de multiples sources pour fournir des insights métiers pertinents. Il démontre l’application des bonnes pratiques de l’industrie en ingénierie des données et en business intelligence.
🧱 Architecture des données

La solution est conçue selon le modèle Medallion Architecture, structurée en trois couches successives :

    Couche Bronze : couche d’ingestion des données brutes où les fichiers sources (CSV) sont chargés dans SQL Server dans leur format d’origine.

    Couche Silver : couche de nettoyage et de normalisation des données pour améliorer leur qualité et leur cohérence.

    Couche Gold : couche finale orientée métier, où les données sont modélisées en schéma en étoile (star schema), optimisées pour les requêtes analytiques et la visualisation.

✨ Points clés du projet

Le projet inclut :

    La conception d’une architecture data warehouse moderne et multi-couches.

    Le développement de pipelines ETL robustes pour extraire, transformer et charger les données entre les couches.

    La création de tables de faits et tables de dimensions optimisées pour l’analyse.

    La génération de rapports SQL et de dashboards analytiques pour faciliter la prise de décision.
