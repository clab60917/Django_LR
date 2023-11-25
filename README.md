# Django_LR
# Django Backend pour Application Android

![Badge Langage](https://img.shields.io/badge/language-Python-blue.svg)
![Badge Framework](https://img.shields.io/badge/framework-Django-green.svg)
![Badge Platform](https://img.shields.io/badge/platform-Android-brightgreen.svg)

## Description

Ce projet est un backend Django conçu pour fournir des services d'authentification et de gestion des utilisateurs pour une application Android en Kotlin. Il gère les fonctionnalités de connexion, d'inscription, d'envoi de mails de confirmation et de réinitialisation de mot de passe.

## Fonctionnalités

- **Authentification et Inscription** : Permet aux utilisateurs de créer un compte et de se connecter.
- **Confirmation par Email** : Envoie des emails de confirmation lors de l'inscription.
- **Réinitialisation du Mot de Passe** : Permet aux utilisateurs de réinitialiser leur mot de passe en cas d'oubli.
- **API RESTful** : Fournit une interface API claire pour l'interaction avec l'application Android.

## Technologies Utilisées

- **Backend** : Django, Python
- **Base de Données** : SQLite
- **Envoi d'Emails** : SMTP

## Installation et Configuration

Pour mettre en place le projet, suivez ces étapes :

```bash
git clone https://github.com/clab60917/Django_LR.git
cd Django_LR
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
## Utilisation
Après avoir démarré le serveur, l'API est prête à être utilisée par l'application Android pour les opérations d'authentification et de gestion des utilisateurs.

## Contribution

Si vous souhaitez contribuer à ce projet, vos contributions sont les bienvenues. Veuillez suivre les étapes suivantes :

1. Forkez le projet.
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`).
4. Push vers la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](https://github.com/clab60917/Django_LR/blob/main/LICENSE) pour plus de détails.

---


