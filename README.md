# Cahier de vacances Machine Learnia 2026 — mes solutions

**Auteur des solutions :** Sita KABA ([@SitaKaba](https://github.com/SitaKaba))

Ce dépôt contient mes solutions aux 7 mini-projets du **cahier de vacances 2026 de [Machine Learnia](https://github.com/MachineLearnia/Cahier-Vacances-2026)**. Un projet était publié chaque dimanche de l'été, de l'analyse de données au deep learning, aux RAG et aux agents IA.

> **Crédits.** Les énoncés, les données, les fonctions de test (`utils.py`) et les illustrations sont l'œuvre de Machine Learnia ([dépôt d'origine](https://github.com/MachineLearnia/Cahier-Vacances-2026)). Mon travail correspond au code écrit dans les blocs `### START CODE HERE ###` / `### END CODE HERE ###` des notebooks, ainsi qu'à `Projet_07/agent.py` et aux modifications de `Projet_07/app.py`.

## Les projets

| # | Thème | Sujet | Notebook |
|---|---|---|---|
| 01 | SQL | Interroger une base de réservations de vols | [projet_01.ipynb](Projet_01/projet_01.ipynb) |
| 02 | Machine learning | Qui gagnera la Coupe du monde 2026 ? | [projet_02.ipynb](Projet_02/projet_02.ipynb) |
| 03 | Clustering et algorithmes | Dessiner le Tour de France 2027 | [projet_03.ipynb](Projet_03/projet_03.ipynb) |
| 04 | RAG et LLM | L'assistant virtuel de l'Hôtel Le Belvédère | [projet_04.ipynb](Projet_04/projet_04.ipynb) |
| 05 | Deep learning et vision | Encadrer et nommer les poissons de l'aquarium | [projet_05.ipynb](Projet_05/projet_05.ipynb) |
| 06 | Séries temporelles | Combien de glaces préparer demain ? | [Projet_06.ipynb](Projet_06/Projet_06.ipynb) |
| 07 | IA agentique | Un agent IA qui planifie tes vacances (avec une interface Streamlit) | [projet_07.ipynb](Projet_07/projet_07.ipynb) |

## Lancer les notebooks

L'environnement Python se gère avec [`uv`](https://docs.astral.sh/uv/) (Python ≥ 3.13) :

```shell
git clone https://github.com/SitaKaba/cahier-vacances-2026.git
cd cahier-vacances-2026
uv sync
```

Ouvre ensuite les notebooks dans VS Code ou Jupyter, avec l'environnement `.venv` créé par `uv`.

- **Projet 05 :** le jeu de données ([Fish Detection, Roboflow](https://universe.roboflow.com/zehra-acer/fish-detection-fztlb), environ 400 Mo) n'est pas inclus dans le dépôt. Le notebook le télécharge dans `Projet_05/data/`.
- **Projet 07 :** l'interface se lance avec `uv run streamlit run Projet_07/app.py`.

## Structure

```
Projet_01/ … Projet_07/   # un dossier par projet : notebook, données, images, utils.py
pyproject.toml            # dépendances (uv)
```
