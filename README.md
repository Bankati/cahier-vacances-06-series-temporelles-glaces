# Séries temporelles — Prévoir des ventes de glaces (ARMA)

> 🚧 **Travail en cours** — certaines cellules du notebook sont encore incomplètes. Dépôt publié tel quel pour suivre la progression.

Prévision des ventes journalières d'un marchand de glaces à partir de quatre étés d'historique, avec des modèles de la famille ARMA (AutoRegressive Moving Average).

Issu du [Cahier de vacances Machine Learnia 2026](https://github.com/MachineLearnia/Cahier-Vacances-2026) (template et énoncé), réponses en cours par [Mabibè Bankati](https://github.com/Bankati).

## Ce qui est couvert (une fois terminé)

- Découpage train/test chronologique (jamais de mélange aléatoire sur une série temporelle)
- Autocorrélation (ACF/PACF) pour diagnostiquer la mémoire d'une série
- Modèles **MA(q)** puis **ARMA(p,q)** (`statsmodels`), comparaison par AIC et test de Ljung-Box sur les résidus
- Prévision glissante à horizon 1 jour, puis à 7 jours

## Stack

Python, pandas, numpy, statsmodels, matplotlib

## Installation

```bash
pip install pandas numpy statsmodels matplotlib ipykernel
jupyter notebook Projet_06.ipynb
```
