# Patrimoine

**Votre patrimoine complet, clair et sous contrôle.**

Application de bureau Windows qui rassemble **tout votre patrimoine au même endroit** et vous aide à le piloter : actions, ETF, ETC, crypto, obligations, SCPI, épargne, liquidités, immobilier et loyers locatifs. Cours de bourse automatiques, analyses claires, **fiscalité belge intégrée** — le tout 100 % local, sur votre ordinateur.

## Téléchargement

| Fichier | Description |
|---|---|
| **[⬇️ Patrimoine-Setup.exe](../../raw/main/Patrimoine-Setup.exe)** | Installateur de l'application (Windows 64 bits) |
| [⬇️ Patrimoine-v1.0.zip](../../raw/main/Patrimoine-v1.0.zip) | Archive complète : installateur + README + modèle d'import |
| [⬇️ Exemple-import.xlsx](../../raw/main/Exemple-import.xlsx) | Modèle Excel prêt à remplir pour importer votre portefeuille |

## Ce que fait Patrimoine

- **Vue d'ensemble** — portefeuille consolidé, répartition par classe d'actif, par région et par établissement, heatmap de performance, valorisation en temps quasi réel.
- **Indicateurs de marché** — tendances des marchés, stratégie d'allocation et prévisions d'analystes pour vos positions.
- **Diagnostic & analyses** — analyse et diagnostic du portefeuille, analyse des frais par établissement (TER, droits de garde, courtage), analyse de risque, corrélations, comparateur d'ETF et analyse d'actions intégrée (score + plan de sortie).
- **Fiscalité belge** — précompte mobilier, plus-values, taxe sur les opérations de bourse (TOB), exonérations paramétrables.
- **Suivi & pilotage** — watchlist, alertes de patrimoine, rappels d'investissement programmé (DCA), calendrier des revenus passifs (loyers, dividendes, coupons, épargne), actualités et notes.
- **Outils** — portefeuille fictif pour tester sans risque, budget personnel, projections et simulations, fiche détaillée par actif, profils d'allocation cibles.
- **Import / export & sauvegardes** — import Excel/CSV avec aperçu, export au même format, sauvegardes intégrées. Vos données restent chez vous.

## Installation (2 minutes)

1. Double-cliquez sur **Patrimoine-Setup.exe**.
2. Si Windows affiche « Windows a protégé votre ordinateur » : cliquez sur **Informations complémentaires** puis **Exécuter quand même**. (C'est normal pour un logiciel récent pas encore largement diffusé ; l'application est sans danger et ne communique aucune donnée personnelle.)
3. Choisissez l'installation **pour vous uniquement** (recommandé, sans droits administrateur) ou **pour tous les utilisateurs**, puis suivez l'assistant. Aucun autre logiciel n'est nécessaire : tout est inclus.
4. Une icône **Patrimoine** apparaît sur le Bureau et dans le menu Démarrer. Lancez-la depuis là.

## Importer votre portefeuille (Excel / CSV)

Le fichier **Exemple-import.xlsx** est un modèle prêt à remplir. Il montre comment saisir chaque type d'actif :

- Actions, ETF, ETC, Crypto
- Obligations (montant, taux, échéance)
- SCPI / rendement (montant, taux)
- Compte épargne / livret (montant, taux)
- Placement à terme (CAT, bon de caisse, bon d'État)
- Liquidités (montant)
- Loyer locatif (loyer mensuel, valeur du bien)
- Immobilier (valeur du bien)

Remplacez les lignes d'exemple par vos données, gardez les en-têtes de colonnes, puis dans l'application : onglet **Ajouter → Importer un fichier Excel/CSV**. Un aperçu vous montre le type détecté et le détail de chaque ligne avant l'import.

> Astuce : l'export Excel de l'application produit un fichier au même format ; vous pouvez le modifier puis le réimporter tel quel.

## Configuration requise

- Windows 10 ou 11 (64 bits)
- Une connexion Internet (pour récupérer les cours de bourse). L'application fonctionne aussi hors ligne avec les dernières données connues.

## Vos données

Vos données (portefeuille, sauvegardes) sont enregistrées dans votre dossier personnel :

```
%APPDATA%\Patrimoine
```

Elles restent 100 % locales et ne sont **jamais** supprimées si vous désinstallez l'application. Pensez à utiliser la fonction de sauvegarde intégrée régulièrement.

## Désinstallation

Paramètres Windows → Applications → Patrimoine → Désinstaller. (Vos données personnelles restent intactes.)
