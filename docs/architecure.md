+---------------------------------------------------------------+
|                         Interface Utilisateur                 |
|---------------------------------------------------------------|
| - Création, configuration et gestion des workflows            |
| - Visualisation des états, logs et erreurs                    |
| - Personnalisation du branding (logo, nom, thème)             |
+------------------------------+--------------------------------+
                               |
                               v
+------------------------------+--------------------------------+
|                     Moteur d’Automatisation                   |
|---------------------------------------------------------------|
| - Orchestrateur : déclenche les modules selon le workflow     |
| - Moteur de règles : applique les règles configurables        |
| - Gestionnaire d’erreurs : surveillance et redémarrage auto   |
| - Logger : enregistre les événements et états                 |
+--------------------+-----------------------+------------------+
                     |                       |
                     v                       v
    +---------------------+          +------------------------+
    | Modules Métier 1     |          | Modules Métier 2       |
    | (logique purement    |          | (logique purement      |
    | fonctionnelle, sans  |          | fonctionnelle, sans    |
    | état ni mutation)    |          | état ni mutation)      |
    +---------------------+          +------------------------+
                              
+---------------------------------------------------------------+
|                       Sécurité                                |
|---------------------------------------------------------------|
| - Chiffrement des communications                              |
| - Authentification et contrôle d’accès                        |
| - Gestion sécurisée des variables sensibles                   |
+---------------------------------------------------------------+

+---------------------------------------------------------------+
|                     Stockage des Configurations               |
|---------------------------------------------------------------|
| - Règles workflow (JSON/YAML)                                 |
| - Définitions de workflows complets (JSON/YAML)               |
+---------------------------------------------------------------+

+---------------------------------------------------------------+
|                       Tests & Validation                      |
|---------------------------------------------------------------|
| - Tests unitaires des modules métiers                         |
| - Tests d’intégration des workflows complets                  |
+---------------------------------------------------------------+

+---------------------------------------------------------------+
|                      Documentation                            |
|---------------------------------------------------------------|
| - Architecture, manuel utilisateur, rapports post-déploiement|
+---------------------------------------------------------------+
