# OpenProject Docker

Ce dépôt permet de déployer OpenProject avec Docker Compose.

## Démarrage rapide

1. Copiez `.env.sample` en `.env` et adaptez les valeurs à votre environnement.
2. Lancez les conteneurs :
   ```bash
   docker compose up -d
   ```
3. Accédez à l’interface web sur le port configuré (ex : http://localhost:52081).

## Configuration
- Toutes les variables sensibles et personnalisables sont dans `.env`.
- Les données et secrets ne sont pas versionnés (`.gitignore`).
- SMTP est prêt pour Brevo/Sendinblue, modifiez les valeurs selon votre fournisseur.

## Sécurité
- Changez impérativement les mots de passe et la clé secrète avant mise en production.

## Ressources
- Documentation officielle : https://www.openproject.org/docs/installation-and-operations/docker/

---
Pour toute question, consultez la documentation ou ouvrez une issue.
