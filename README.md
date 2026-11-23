# Rémi Verhaeghe

Développeur logiciel. J'aime résoudre des problèmes concrets et concevoir des applications
propres, testées et maintenables. Je travaille sur plusieurs écosystèmes (Python, Java, PHP,
Vue.js) pour avoir une vision complète du développement, du back-end à l'interface.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat&logo=symfony&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## Compétences

| Domaine | Technologies |
|---|---|
| Back-end | Python, FastAPI, Java, PHP, Symfony |
| Front-end | HTML, CSS, JavaScript, Vue.js 3, Jinja2, HTMX |
| Mobile | Flutter / Dart |
| Données | SQL, PostgreSQL, MySQL, SQLite, pandas |
| Qualité | PHPUnit, Infection, PHPStan, pytest, Playwright, pylint, Black, bandit, CI GitHub Actions |
| Outils | Git, GitHub, VS Code, Docker |

## Projets

### [tremplin](https://github.com/Remiverhaeghe/tremplin)

Tableau de bord de recherche d'emploi : collecte d'offres publiques, suivi des candidatures et
des relances, préparation des entretiens. Architecture découpée en couches (HTTP, parsing,
extraction, métier, stockage).

- Tableau de bord web FastAPI (Jinja2, HTMX) et interface de bureau PySide6
- Relances groupées un jour de la semaine, récapitulatif mensuel des démarches à imprimer pour France Travail
- Application mobile Flutter compagnon, hors ligne d'abord : 944 questions livrées pour réviser sans le PC, synchronisation par une API à jeton, connexion par un code à 6 chiffres
- Révision dans l'univers de la piscine : profondeur de chaque thème, bilan du plongeon, carnet de la semaine, révision à la voix, widget « 5 min »
- Version web installable sur l'iPhone, le code propre à Android séparé par plate-forme
- Stockage SQLite, analyse avec pandas
- Tests pytest et Playwright, CI avec analyse statique, audit de sécurité et des dépendances

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

<p><img src="https://raw.githubusercontent.com/Remiverhaeghe/tremplin/main/docs/captures/tableau-de-bord.png" alt="Tableau de bord, sur des données fictives" width="260"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/tremplin/main/docs/captures/offres.png" alt="Liste des offres, sur des données fictives" width="260"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/tremplin/main/docs/captures/marche.png" alt="Mon marché, sur des données fictives" width="260"></p>

### [nas-monitor](https://github.com/Remiverhaeghe/nas-monitor)

Supervision d'un NAS auto-hébergé : les sauvegardes et tâches planifiées signalent leur
exécution, l'application contrôle aussi des sites, ports, certificats TLS, DNS et pings, et
envoie une alerte par e-mail ou ntfy quand quelque chose manque.

- Page de statut publique, courbes de tendance, API à jeton pour une application mobile
- Santé des disques du NAS (SMART) : température, secteurs réalloués, usure NVMe, alerte avant la panne
- Double authentification TOTP, jetons hachés, journal des actions, recherche de secrets en CI
- 285 tests (unitaires, fonctionnels, navigateur), 99 % de couverture, tests de mutation (98 %)
- Symfony 8, PostgreSQL, FrankenPHP, Docker

![PHP 8.5](https://img.shields.io/badge/PHP_8.5-777BB4?style=flat&logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat&logo=symfony&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PHPUnit](https://img.shields.io/badge/PHPUnit-3C9CD7?style=flat)
![Infection](https://img.shields.io/badge/Infection-6D2077?style=flat)

### [cursus](https://github.com/Remiverhaeghe/cursus)

Suivi des compétences d'apprentis, partagé entre l'école, l'entreprise d'accueil et l'apprenti.
Réécriture personnelle, de zéro, d'un projet d'équipe de formation. La démo n'utilise que des
données fictives.

- Référentiels de formation, promotions, évaluations datées de 0 à 4, progression par bloc et par compétence
- Accès contrôlé par voters (un test par couple profil et donnée), double authentification TOTP, CSP avec nonce
- 261 tests, 96 % de couverture, tests de mutation (99 %)
- Symfony 8, PostgreSQL, FrankenPHP, Docker
- Visuel propre, celui d'un livret d'apprentissage : papier craie, encre verte, niveaux en tampons

<p><img src="https://raw.githubusercontent.com/Remiverhaeghe/cursus/main/docs/captures/cursus-02-progression.png" alt="Progression d'un apprenti par bloc et par compétence" width="270"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/cursus/main/docs/captures/cursus-07-ecole.png" alt="Tableau de bord de l'école" width="270"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/cursus/main/docs/captures/cursus-04-echanges.png" alt="Échanges entre tuteur et apprenti sur les compétences" width="270"></p>

![PHP 8.5](https://img.shields.io/badge/PHP_8.5-777BB4?style=flat&logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat&logo=symfony&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PHPUnit](https://img.shields.io/badge/PHPUnit-3C9CD7?style=flat)
![Infection](https://img.shields.io/badge/Infection-6D2077?style=flat)

### [atelier](https://github.com/Remiverhaeghe/atelier)

Application Android pour préparer ses travaux sans erreur : chaque pièce est saisie mur par
mur, l'application en tire le plan, les coupes, les quantités, le budget et la liste de
courses. Elle n'a pas la permission Internet, tout reste sur le téléphone.

- Parquet rangée par rangée, plinthes optimisées par barre, peinture, carrelage, placo, électricité, plomberie
- Pièce dessinée d'après une forme (rectangle, L, T) : murs non mesurés déduits et rappelés sur le chantier, angles par la diagonale, fiche PDF de la pièce
- Relevés d'un thermo-hygromètre suivis jour par jour, avant et après travaux
- Version web installable sur l'iPhone, hors ligne
- Petites structures bois (étagères, mezzanine, pergola, escaliers) prédimensionnées d'après l'Eurocode 5
- Sauvegarde chiffrée en AES-256-GCM, mot de passe dérivé par PBKDF2
- Règles de calcul en Dart pur, couvertes à plus de 95 % en CI
- Plus de 400 tests, parcours sur émulateur Android, captures générées sur un chantier fictif, APK signées

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

Habillée comme un carnet de chantier : croquis cotés et schémas en relief dessinés par le code.
Captures faites par la CI sur un chantier fictif, à voir aussi dans la [section Croquis du portfolio](https://remiverhaeghe.github.io/portefolio-vue/#croquis).

<p><img src="https://raw.githubusercontent.com/Remiverhaeghe/atelier/main/docs/captures/15-rampants.png" alt="Pièce sous rampants" width="160"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/atelier/main/docs/captures/16-fenetre-bois.png" alt="Fenêtre bois sur mesure" width="160"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/atelier/main/docs/captures/23-placard-rampant.png" alt="Placard sous rampant" width="160"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/atelier/main/docs/captures/24-geste-scier.png" alt="Geste : scier droit" width="160"></p>

### [secrets-audit](https://github.com/Remiverhaeghe/secrets-audit)

Audit d'hygiène des secrets dans les dépôts git d'un dossier : fichiers sensibles suivis ou
restés dans l'historique, clés privées, jetons et mots de passe en clair. Il n'affiche jamais
une valeur en entier.

- Python sans dépendance externe, rapport texte ou JSON, code de sortie utilisable en CI
- Règles qui limitent les faux positifs (valeurs d'exemple, code, chemins de test)
- 47 tests sur de vrais dépôts git temporaires, 100 % de couverture, CI avec black, pylint et bandit

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![unittest](https://img.shields.io/badge/unittest-3776AB?style=flat&logo=python&logoColor=white)

### [kalkul](https://github.com/Remiverhaeghe/kalkul)

Calculatrice de bureau en Java : calcul scientifique, financier et graphique (tracé de
fonctions, dérivée, intégrale), matrices, systèmes, régression et tests statistiques.

- Onglets Programmeur (bases 2 à 16, opérations bit à bit) et Chantier (béton, pente, revêtement)
- Historique des calculs cherchable et exportable en CSV, formules enregistrées et réutilisées d'un onglet à l'autre
- Devises hors ligne : taux tapés ou importés du fichier de la BCE, toujours datés
- Habillage Swing dessiné à la main, façon calculatrice de bureau des années 70 : touches rondes en relief, écran à cristaux liquides aux chiffres en sept segments, thème clair ou sombre selon Windows

<p><img src="https://raw.githubusercontent.com/Remiverhaeghe/kalkul/main/docs/calculatrice.png" alt="Onglet Base : touches rondes et écran à sept segments" width="200"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/kalkul/main/docs/scientifique.png" alt="Onglet Scientifique" width="200"> <img src="https://raw.githubusercontent.com/Remiverhaeghe/kalkul/main/docs/theme-clair.png" alt="Thème clair" width="200"></p>

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat&logo=junit5&logoColor=white)

### [portefolio-vue](https://github.com/Remiverhaeghe/portefolio-vue)

Portfolio présentant mon parcours et mes projets, publié sur [GitHub Pages](https://remiverhaeghe.github.io/portefolio-vue/).

![Vue.js 3](https://img.shields.io/badge/Vue.js_3-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## En ce moment

- J'approfondis l'architecture des API REST et les tests automatisés
- Je cherche un poste de développeur web ou logiciel

## Contact

[LinkedIn](https://www.linkedin.com/in/remi-verhaeghe-99a532121) · [Email](mailto:remi.verhaeghe59@gmail.com)
