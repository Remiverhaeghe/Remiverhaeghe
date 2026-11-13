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

### [nas-monitor](https://github.com/Remiverhaeghe/nas-monitor)

Supervision d'un NAS auto-hébergé : les sauvegardes et tâches planifiées signalent leur
exécution, l'application contrôle aussi des sites, ports, certificats TLS, DNS et pings, et
envoie une alerte par e-mail ou ntfy quand quelque chose manque.

- Page de statut publique, courbes de tendance, API à jeton pour une application mobile
- Double authentification TOTP, jetons hachés, journal des actions, recherche de secrets en CI
- Plus de 270 tests (unitaires, fonctionnels, navigateur), 99 % de couverture, tests de mutation (96 %)
- Symfony 8, PostgreSQL, FrankenPHP, Docker

`PHP 8.5` `Symfony` `PostgreSQL` `Docker` `PHPUnit` `Infection`

### [scraper-data-python](https://github.com/Remiverhaeghe/scraper-data-python)

Collecte et analyse d'offres d'emploi publiques, avec une architecture découpée en couches
(HTTP, parsing, extraction, métier, stockage).

- Tableau de bord web FastAPI (Jinja2, HTMX) et interface de bureau PySide6
- Application mobile Flutter compagnon, hors ligne d'abord, synchronisée via une API à jeton
- Stockage SQLite, analyse avec pandas
- Tests pytest et Playwright, CI avec analyse statique, audit de sécurité et des dépendances

`Python` `FastAPI` `Flutter` `SQLite` `pandas` `pytest`

### [secrets-audit](https://github.com/Remiverhaeghe/secrets-audit)

Audit d'hygiène des secrets dans les dépôts git d'un dossier : fichiers sensibles suivis ou
restés dans l'historique, clés privées, jetons et mots de passe en clair. Il n'affiche jamais
une valeur en entier.

- Python sans dépendance externe, rapport texte ou JSON, code de sortie utilisable en CI
- Règles qui limitent les faux positifs (valeurs d'exemple, code, chemins de test)
- 47 tests sur de vrais dépôts git temporaires, 100 % de couverture, CI avec black, pylint et bandit

`Python` `Git` `unittest`

### [kalkul](https://github.com/Remiverhaeghe/kalkul)

Calculatrice de bureau en Java : calcul scientifique, financier et graphique (tracé de
fonctions, dérivée, intégrale), matrices, systèmes, régression et tests statistiques.

`Java` `Maven` `JUnit`

### [portefolio-vue](https://github.com/Remiverhaeghe/portefolio-vue)

Portfolio présentant mon parcours et mes projets, publié sur [GitHub Pages](https://remiverhaeghe.github.io/portefolio-vue/).

`Vue.js 3` `Vite` `Vitest` `GitHub Actions`

## En ce moment

- J'approfondis l'architecture des API REST et les tests automatisés
- Je cherche un poste de développeur web ou logiciel

## Contact

[LinkedIn](https://www.linkedin.com/in/remi-verhaeghe-99a532121) · [Email](mailto:remi.v_59@hotmail.fr)
