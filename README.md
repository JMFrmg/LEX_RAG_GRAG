# LEX_RAG_GRAG
Démonstration d'un RAG pour la formation DevIA


## Initialisation

### Créer et charger un environnement vituel avec Python

Dans le terminal, se placer à la racine du projet.

```bash
python -m venv .venv
```

```bash
source .venv/bin/activate
```

### Installations

```bash
pip install jupyterlab
```

### Lancement de jupyter

```bash
jupyter lab
```
## Clé d'API

Il est nécessaire de créer une clé d'API Mistral.
Aller sur le site de Mistral. Créer un compte. Puis créer une clé d'API.

Pour utiliser la clé d'API dans le projet :

 - Créer un fichier .env à la racine du projet
 - Entrer la ligne suivante dans le fichier : MISTRAL_API_KEY=<ma_clé_d_api>
 - Remplacer <ma_clé_d_api> par votre clé d'API
