# Restore vs Reset

## git restore
- Annule les modifications d'un fichier non commité
- Ne touche PAS à l'historique
- Exemple : git restore monfichier.txt

## git reset
- Annule des commits déjà faits
- Modifie l'historique (dangereux si partagé)
- Exemple : git reset --soft HEAD~1