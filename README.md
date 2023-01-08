# wd-code-editor
un champ éditeur de code  pour vos projet WinDev / a code editor control for your WinDev projects

Génère un composant qui peut être utilisé dans d'autres projets

# Copie d'écran

![hc1](https://github.com/maitrebitcoin/wd-code-editor/blob/main/hc1.png)]

# Exemple d'utilisation
## Intégrer le champ
Ajouter un champ feneêtre interne, lui mettre comme source `Champ_editeur_de_code`
## Ajouter ce code a l'initialisation
```
param est Champ_editeur_de_code.ParametreEditeur
param.avec_numéro_de_ligne = Vrai
param.nom_langage = "js"
CHAMP_ED_CODE.init_editeur(param)
```
