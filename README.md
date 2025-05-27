# 7 Questions : Construire un agent Text-to-SQL avec GPT-4.1

Ce projet vous guide pour construire un agent capable de transformer des questions en langage naturel en requêtes SQL, d'exécuter ces requêtes et de visualiser les résultats.

## Prérequis
- Python 3.11 (recommandé)
- Une clé API OpenAI (GPT-4.1 ou GPT-4o)
- Le fichier `catalogue.csv` dans le dossier racine

## Installation rapide

1. **Clonez le repo et placez-vous dans le dossier**

```bash
cd /chemin/vers/le/projet
```

2. **Créez un environnement virtuel**

**Sur macOS/Linux :**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Sur Windows :**
```bat
python -m venv .venv
.venv\Scripts\activate
```

3. **Installez les dépendances**

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

4. **Configurez votre clé OpenAI**

Créez un fichier `.env` à la racine du projet :

```
OPENAI_API_KEY=sk-votre-cle-ici
```

5. **Lancez le notebook**

```bash
pip install notebook  # si besoin
jupyter notebook 7_questions_text_to_sql_workshop.ipynb
```

## Dépendances principales
- openai>=1.0.0
- pandas
- python-dotenv
- matplotlib
- ipython-sql
- pydantic
- openai-agents

## Notes
- Le notebook fonctionne avec Python 3.11 (testé sur 3.11.8).
- Assurez-vous que `catalogue.csv` est bien présent.
- Pour toute question, ouvrez une issue ou contactez l'auteur.
