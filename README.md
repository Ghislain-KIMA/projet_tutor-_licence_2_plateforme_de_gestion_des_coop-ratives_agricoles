# 🌱 Plateforme de gestion des coopératives agricoles

Une brève description du projet, ce qu’il fait et pourquoi il est utile.

## Membres

- Ghislain KIMA
- Aïssatou DICKO

## Structure du projet

```
.
├── .env
├── doc
│   ├── architectures
│   │   ├── architecture_logiciel
│   │   └── database
│   │       ├── 00_mcd.drawio
│   │       ├── 00_mcd.drawio.pdf
│   │       ├── 01_mld.drawio
│   │       ├── 01_mld.drawio.pdf
│   │       ├── 02_mpd.drawio
│   │       └── 02_mpd.drawio.pdf
│   ├── cahier_de_charges.docx
│   ├── diagrams
│   │   ├── 00_diagramme_de_contexte.drawio
│   │   ├── 01_diagramme_de_cas_d_utilisation.drawio
│   │   ├── 02_diagramme_de_composants.drawio
│   │   ├── 03_diagramme_de_classes.drawio
│   │   ├── diagramme_d_activites.drawio
│   │   └── diagramme_de_sequences.drawio
│   ├── Les problèmes majeurs de gestion des coopératives agricoles au Burkina Faso se résument en.docx
│   ├── README.md
│   └── user_interface_mockups
|
├── README.md
├── requirements.txt
└── src
    ├── apps
    │   ├── account
    │   │   ├── admin.py
    │   │   ├── apps.py
    │   │   ├── __init__.py
    │   │   ├── models.py
    │   │   ├── static
    │   │   │   └── account
    │   │   │       └── css
    │   │   │           ├── background.jpg
    │   │   │           └── style.css
    │   │   ├── templates
    │   │   │   └── account
    │   │   │       └── index.html
    │   │   ├── tests.py
    │   │   ├── urls.py
    │   │   └── views.py
    │   ├── customer
    │   │   ├── admin.py
    │   │   ├── apps.py
    │   │   ├── __init__.py
    │   │   ├── migrations
    │   │   │   ├── __init__.py
    │   │   │   └── __pycache__
    │   │   │       └── __init__.cpython-312.pyc
    │   │   ├── models.py
    │   │   ├── __pycache__
    │   │   │   ├── admin.cpython-312.pyc
    │   │   │   ├── apps.cpython-312.pyc
    │   │   │   ├── __init__.cpython-312.pyc
    │   │   │   ├── models.cpython-312.pyc
    │   │   │   ├── urls.cpython-312.pyc
    │   │   │   └── views.cpython-312.pyc
    │   │   ├── tests.py
    │   │   ├── urls.py
    │   │   └── views.py
    │   ├── manager
    │   │   ├── admin.py
    │   │   ├── apps.py
    │   │   ├── __init__.py
    │   │   ├── migrations
    │   │   │   ├── __init__.py
    │   │   │   └── __pycache__
    │   │   │       └── __init__.cpython-312.pyc
    │   │   ├── models.py
    │   │   ├── __pycache__
    │   │   │   ├── admin.cpython-312.pyc
    │   │   │   ├── apps.cpython-312.pyc
    │   │   │   ├── __init__.cpython-312.pyc
    │   │   │   ├── models.cpython-312.pyc
    │   │   │   ├── urls.cpython-312.pyc
    │   │   │   └── views.cpython-312.pyc
    │   │   ├── tests.py
    │   │   ├── urls.py
    │   │   └── views.py
    │   └── member
    │       ├── admin.py
    │       ├── apps.py
    │       ├── __init__.py
    │       ├── migrations
    │       │   ├── __init__.py
    │       │   └── __pycache__
    │       │       └── __init__.cpython-312.pyc
    │       ├── models.py
    │       ├── __pycache__
    │       │   ├── admin.cpython-312.pyc
    │       │   ├── apps.cpython-312.pyc
    │       │   ├── __init__.cpython-312.pyc
    │       │   ├── models.cpython-312.pyc
    │       │   ├── urls.cpython-312.pyc
    │       │   └── views.cpython-312.pyc
    │       ├── tests.py
    │       ├── urls.py
    │       └── views.py
    ├── db.sqlite3
    ├── manage.py
    ├── media
    ├── pgca
    │   ├── asgi.py
    │   ├── __init__.py
    │   ├── settings.py
    │   ├── templates
    │   │   └── index.html
    │   ├── urls.py
    │   ├── views.py
    │   └── wsgi.py
    └── static
        └── bootstrap-5.3.8-dist
            ├── css
            │   └── bootstrap.min.css
            └── js
                └── bootstrap.bundle.min.js
```

## 🚀 Objectifs

## 👥 Public cible

## 🛠️ Fonctionnalités

## Dépendances du projet

## 📦 Installation

```bash
# Clone le dépôt
git clone https://github.com/ton-utilisateur/ton-projet.git

# Accède au dossier
cd ton-projet

# Installe les dépendances
pip install -r requirements.txt
