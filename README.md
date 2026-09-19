# Market Making Backtest - Avellaneda-Stoikov

Implémentation du modèle classique pour optimiser les spreads en market making.

## Notebook

📊 **market_making_backtest.ipynb** - Simulation complète avec graphiques

## Concept

**Avellaneda-Stoikov (2008)**: formule optimale pour pricing des spreads
spread = (2/γ) × log(1 + γ/λ) + γ × inventory

- γ = aversion au risque d'inventaire
- λ = intensité des arrivées d'ordres  
- inventory = position courante

## Résultats

Le backtest démontre:
- ✅ Adaptation dynamique des spreads selon l'inventaire
- ✅ Gestion du risque par ajustement des spreads
- ✅ P&L positif grâce au bid-ask spread

## Exécution

Ouvre le notebook dans Jupyter ou Google Colab et exécute les cellules.
