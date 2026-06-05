# Premier Lien 🐝

Le site web officiel de l'association **Premier Lien**, créée par de jeunes étudiantes passionnées par la santé, la parentalité et la petite enfance.

Ce site vise à promouvoir une information fiable, accessible et bienveillante autour de la santé de la femme, de la parentalité, de la petite enfance et du lien parent-enfant.

---

## 🚀 Fonctionnalités du Site

- **Accueil & Présentation :** Section Hero, Histoire & Équipe (Clara & Josiane), Missions & Valeurs, et Domaines d'Actions.
- **Ressources Fiables :** Compilation de liens d'orientation vers des sources de santé validées scientifiquement (Ameli, Haute Autorité de Santé, 1000 Premiers Jours, etc.).
- **FAQ :** Réponses interactives aux questions fréquentes des parents et futurs parents.
- **Formulaire de Contact AJAX :** Formulaire de contact fonctionnel avec FormSubmit.co acheminant les messages d'intérêt (bénévoles, partenaires, professionnels) directement vers `premier.lien.asso@gmail.com` avec un template d'e-mail propre et un e-mail de confirmation visiteur.
- **Bannière de Consentement des Cookies :** Gestion locale du consentement aux cookies de session.
- **Réseaux Sociaux :** Liens intégrés vers les comptes officiels Instagram et TikTok de l'association.

---

## 🛠️ Stack Technique

- **Structure :** HTML5 Sémantique
- **Style :** CSS3 via Tailwind CSS CDN (avec configuration sur-mesure de couleurs et typographies Outfit & Plus Jakarta Sans)
- **Logique :** JavaScript Vanilla (transitions, menu mobile, formulaires)
- **Hébergement :** Vercel
- **Formulaire :** FormSubmit.co (AJAX Fetch)

---

## 📁 Architecture du Projet

```text
├── index.html                  # Page d'accueil principale et formulaire de contact
├── ressources.html             # Page listant les ressources scientifiques d'orientation
├── faq.html                    # Page de Foire Aux Questions
├── mentions-legales.html       # Mentions Légales (avec infos d'hébergement Vercel)
├── politique-confidentialite.html # Politique de Confidentialité des données (RGPD)
├── vercel.json                 # Configuration Vercel (URLs propres)
├── images/                     # Contient les images d'illustration et le logo
│   ├── logo.jpg
│   ├── Clara.jpg
│   └── ...
└── .github/
    └── workflows/
        └── pipeline.yml        # Pipeline CI/CD sécurisée
```

---

## 💻 Développement Local

Pour exécuter le site en local sur votre machine :

1. Ouvrez le projet dans votre éditeur (VS Code, etc.).
2. Utilisez une extension de serveur local (comme **Live Server**) ou exécutez la commande suivante dans votre terminal si vous avez Python installé :
   ```bash
   python3 -m http.server 8080
   ```
3. Accédez à l'adresse [http://localhost:8080](http://localhost:8080) dans votre navigateur.

---

## 🌐 Déploiement sur Vercel

Le site est configuré pour être hébergé sur Vercel avec des liens propres (sans l'extension `.html` visible dans l'URL).

### Déployer via GitHub (Recommandé) :
1. Créez un compte ou connectez-vous sur [Vercel](https://vercel.com).
2. Cliquez sur **Add New...** > **Project**.
3. Importez ce dépôt GitHub (`premier-lien`).
4. Dans les paramètres de build (Build and Development Settings), laissez les valeurs par défaut (Vercel détectera qu'il s'agit d'un projet HTML statique).
5. Cliquez sur **Deploy**. Chaque push sur la branche `main` déclenchera automatiquement un nouveau déploiement.

---

## 📄 Licence & Droits

Tous droits réservés © 2026 Premier Lien.
Pour toute question, veuillez consulter nos [Mentions Légales](mentions-legales.html).
