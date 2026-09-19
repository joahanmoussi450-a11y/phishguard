# 🛡️ PhishGuard

**PhishGuard** est un outil de sensibilisation à la cybersécurité qui détecte les signaux classiques d'une tentative de phishing (hameçonnage) dans un email ou une URL.

🔗 **Démo en ligne :** https://joahanmoussi450-a11y.github.io/phishguard/

## Fonctionnement

L'utilisateur colle le texte d'un email ou une URL suspecte dans le scanner. L'outil analyse automatiquement six familles de signaux d'alerte et affiche un score de risque sur 100, avec une explication pour chacun.

## Signaux détectés

- **Urgence artificielle** — menaces de suspension, délais courts, formulations de pression
- **Demande d'identifiants** — mots de passe, numéros de carte, codes de sécurité
- **Imitation de domaine** — un nom de domaine qui imite une marque connue sans en être le vrai
- **Liens suspects** — raccourcisseurs d'URL, adresses IP brutes, encodage punycode, tirets multiples
- **Appât au gain** — loteries, cadeaux ou remboursements inattendus
- **Salutation générique** — « Cher client » au lieu du vrai nom du destinataire, signe d'un envoi de masse

## Technique

- HTML, CSS et JavaScript purs, sans dépendance ni framework
- Analyse entièrement effectuée **côté navigateur** : aucune donnée n'est envoyée à un serveur
- Détection par expressions régulières et analyse du nom de domaine des liens

## Objectif pédagogique

Ce projet a été réalisé dans le cadre d'un devoir de cours d'intelligence artificielle, avec pour consigne de créer un site web sur un sujet de son choix en utilisant l'IA pour générer le code, jusqu'à son déploiement en ligne. Le score fourni par l'outil est indicatif : il ne remplace pas la vigilance humaine face à un message suspect. .
