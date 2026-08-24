# Patrimoine

Application de bureau (Windows) pour suivre et analyser votre patrimoine : actions, ETF, ETC, crypto, obligations, SCPI, épargne, liquidités, immobilier et loyers locatifs.

## Téléchargement

| Fichier | Description |
|---|---|
| **[⬇️ Patrimoine-Setup.exe](../../raw/main/Patrimoine-Setup.exe)** | Installateur de l'application (Windows 64 bits) |
| [⬇️ Patrimoine-v1.0.zip](../../raw/main/Patrimoine-v1.0.zip) | Archive complète : installateur + README + modèle d'import |
| [⬇️ Exemple-import.xlsx](../../raw/main/Exemple-import.xlsx) | Modèle Excel prêt à remplir pour importer votre portefeuille |

## Installation (2 minutes)

1. Double-cliquez sur **Patrimoine-Setup.exe**.
2. Si Windows affiche « Windows a protégé votre ordinateur » : cliquez sur **Informations complémentaires** puis **Exécuter quand même**. (C'est normal pour un logiciel récent non signé ; l'application est sans danger.)
3. Suivez l'assistant. Aucun autre logiciel n'est nécessaire : tout est inclus.
4. Une icône **Patrimoine** apparaît sur le Bureau et dans le menu Démarrer. Lancez-la depuis là.

## Importer votre portefeuille (Excel / CSV)

Le fichier **Exemple-import.xlsx** est un modèle prêt à remplir. Il montre comment saisir chaque type d'actif :

- Actions, ETF, ETC, Crypto
- Obligations (montant, taux, échéance)
- SCPI / rendement (montant, taux)
- Compte épargne / livret (montant, taux)
- Liquidités (montant)
- Loyer locatif (loyer mensuel, valeur du bien)
- Immobilier (valeur du bien)

Remplacez les lignes d'exemple par vos données, gardez les en-têtes de colonnes, puis dans l'application : onglet **Investissements → Importer un fichier Excel/CSV**. Un aperçu vous montre le type détecté et le détail de chaque ligne avant l'import.

> Astuce : l'export Excel de l'application (menu Outils) produit un fichier au même format ; vous pouvez le modifier puis le réimporter tel quel.

## Configuration requise

- Windows 10 ou 11 (64 bits)
- Une connexion Internet (pour récupérer les cours de bourse). L'application fonctionne aussi hors ligne avec les dernières données connues.

## Vos données

Vos données (portefeuille, sauvegardes) sont enregistrées dans votre dossier personnel :

```
%APPDATA%\Patrimoine
```

Elles ne sont **jamais** supprimées si vous désinstallez l'application. Pensez à utiliser la fonction de sauvegarde intégrée régulièrement.

## Désinstallation

Paramètres Windows → Applications → Patrimoine → Désinstaller. (Vos données personnelles restent intactes.)
