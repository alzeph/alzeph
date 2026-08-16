# Cédric Hervé Youan

Ingénieur logiciel, concentré sur l'écosystème Python/Django : bibliothèques
réutilisables, fiabilité, et outillage développeur. Depuis quelques mois, je
publie une série de projets open source pensés pour combler des faiblesses
concrètes du framework Django — audit trail manquant, authentification à
reconfigurer à chaque projet, génération de tests répétitive, et plus
récemment l'absence d'orchestrateur de concurrence digne de ce nom.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat&logo=django&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

## Bibliothèques open source

| Projet | Description | PyPI |
|---|---|---|
| [django-goroutine](https://github.com/alzeph/django-goroutine) | Orchestrateur structuré de tâches concurrentes pour Django, inspiré du modèle de concurrence de Go — `group()`/`cpu_map()` au-dessus d'`asyncio.TaskGroup`, erreurs en `pycatch.Result`. | [![PyPI](https://img.shields.io/pypi/v/django-goroutine.svg)](https://pypi.org/project/django-goroutine/) |
| [django-forge-log](https://github.com/alzeph/django-forge-log) | Audit trail léger et automatique (Qui/Quoi/Quand/Où/Diff) pour les vues Django, DRF et l'Admin. | [![PyPI](https://img.shields.io/pypi/v/django-forge-log.svg)](https://pypi.org/project/django-forge-log/) |
| [django-forge-auth](https://github.com/alzeph/django-forge-auth) | Application Django réutilisable d'authentification (JWT + OTP), préconfigurée pour DRF. | [![PyPI](https://img.shields.io/pypi/v/django-forge-auth.svg)](https://pypi.org/project/django-forge-auth/) |
| [django-forge-cli](https://github.com/alzeph/django-forge-cli) | Génère rapidement la structure d'un projet Django, pour réduire le temps de mise en place. | [![PyPI](https://img.shields.io/pypi/v/django-forge-cli.svg)](https://pypi.org/project/django-forge-cli/) |
| [django-forge-test](https://github.com/alzeph/django-forge-test) | Génération automatique de fixtures et de tests d'API pour Django. | [![PyPI](https://img.shields.io/pypi/v/django-forge-test.svg)](https://pypi.org/project/django-forge-test/) |
| [django-signals-all](https://github.com/alzeph/django-signals-all) | Signaux Django garantis pour les opérations bulk (`bulk_create`/`bulk_update`) et le SQL brut, que Django n'émet pas nativement. | [![PyPI](https://img.shields.io/pypi/v/django-signals-all.svg)](https://pypi.org/project/django-signals-all/) |
| [pycatch](https://github.com/alzeph/pycatch) | Gestion d'erreurs fluide pour Python, inspirée du type `Result` de Rust — `Ok`, `Err`, et un décorateur `catch` pour éviter les `try/except` imbriqués. | [![PyPI](https://img.shields.io/pypi/v/pycatch-safe.svg)](https://pypi.org/project/pycatch-safe/) |
| [local-fake](https://github.com/alzeph/local-fake) | Générateur de fausses données localisées pour l'Afrique (Mobile Money, adresses textuelles, numérotations locales, KYC), avec génération de fichiers de test. | [![PyPI](https://img.shields.io/pypi/v/local-fake.svg)](https://pypi.org/project/local-fake/) |

Plusieurs de ces projets sont encore en *release candidate* : l'API est
considérée figée mais pas encore éprouvée par un usage réel en dehors de
leur propre dépôt — retours, issues et contributions sont bienvenus sur
n'importe lequel d'entre eux.

## En chiffres

![Stats GitHub](https://github-readme-stats.vercel.app/api?username=alzeph&show_icons=true&hide_title=true&count_private=true)
![Langages les plus utilisés](https://github-readme-stats.vercel.app/api/top-langs/?username=alzeph&layout=compact&hide_title=true)

## Autres dépôts

<details>
<summary>Expérimentations, projets clients et scripts (18)</summary>

| Dépôt | Description |
|---|---|
| [django-utility](https://github.com/alzeph/django-utility) | Ensemble de classes et utilitaires réutilisables pour accélérer le développement Django. |
| [Django-Auto-Test](https://github.com/alzeph/Django-Auto-Test) | Automatise la génération de tests Django (vues, modèles...). |
| [linkedin](https://github.com/alzeph/linkedin) | Petit utilitaire Python pour le bien de tous. |
| [django-scb-auth](https://github.com/alzeph/django-scb-auth) | — |
| [django-scb-app](https://github.com/alzeph/django-scb-app) | — |
| [scb-scan-gsm-api](https://github.com/alzeph/scb-scan-gsm-api) | — |
| [scb-scan-gsm-front](https://github.com/alzeph/scb-scan-gsm-front) | — |
| [scb-scan-gsm](https://github.com/alzeph/scb-scan-gsm) | — |
| [drone-data-viewer](https://github.com/alzeph/drone-data-viewer) | — |
| [ecouture_front](https://github.com/alzeph/ecouture_front) | — |
| [app-sed-back](https://github.com/alzeph/app-sed-back) | — |
| [scrapping-word-for-tanares](https://github.com/alzeph/scrapping-word-for-tanares) | — |
| [converter-webp](https://github.com/alzeph/converter-webp) | — |
| [django_factory_all](https://github.com/alzeph/django_factory_all) | — |
| [portfolio](https://github.com/alzeph/portfolio) / [mon-portfolio](https://github.com/alzeph/mon-portfolio) | Site portfolio personnel. |
| [aib_dev](https://github.com/alzeph/aib_dev) | — |
| [blogs](https://github.com/alzeph/blogs) | — |
| [PAR](https://github.com/alzeph/PAR) / [PAPCollect](https://github.com/alzeph/PAPCollect) | — |

</details>

## Contact

[hervecedricyouan@gmail.com](mailto:hervecedricyouan@gmail.com)
