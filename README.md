Merci pour les précisions sur la stack du site web **Senpass**. Voici une version optimisée du `README.md`, reflétant exactement les technologies utilisées :

---

````markdown
# 🇸🇳 Senpass – Portail d'identité numérique nationale du Sénégal

**Senpass** est une plateforme numérique souveraine qui permet à chaque citoyen sénégalais d’accéder de manière simple, rapide et sécurisée à une multitude de services administratifs et privés à travers une seule identité numérique.

> 🛡️ Développé par **Bishflix Systems** – Pour une Afrique connectée et souveraine.

---

## 📊 Stack technologique principale

| Langage / Tech | Usage |
|----------------|-------|
| **SCSS (48.7%)**     | Stylisation avancée et responsive |
| **TypeScript (26.2%)** | Typage strict et développement frontend |
| **Blade (10.0%)**     | Moteur de templates Laravel |
| **PHP (7.8%)**        | Backend – APIs et logique métier |
| **JavaScript (6.7%)** | Interactivité côté client |
| **CSS (0.6%)**        | Feuilles de style de base / fallback |

---

## ✨ Fonctionnalités clés

- 🔐 Authentification multi-facteur (Mot de passe + OTP ou QR)
- 🆔 Création et gestion du **profil numérique unique**
- 🖋️ Signature électronique officielle
- 📑 Accès aux services : état civil, santé, foncier, éducation, banque...
- 📱 Expérience utilisateur responsive (mobile & desktop)
- 🌍 Support multilingue & régional (UEMOA-ready)

---

## 🗂️ Arborescence simplifiée

```plaintext
senpass_siteweb/
├── resources/
│   ├── views/         # Fichiers Blade (templates)
│   ├── scss/          # Feuilles de style SCSS
│   └── js/            # Scripts TypeScript et JavaScript
├── public/            # Fichiers accessibles au public (assets, images)
├── routes/            # Routes Laravel (web.php, api.php)
├── app/               # Logique backend PHP (contrôleurs, modèles)
├── .env               # Variables d’environnement
└── README.md
````

---

## 🚀 Lancer le projet localement

### ⚙️ Prérequis

* PHP ≥ 8.1
* Composer
* Node.js ≥ 18
* Laravel ≥ 10.x
* PostgreSQL ou MySQL
* Git

### 📦 Installation

```bash
# Cloner le dépôt
git clone https://github.com/bishflix-sys/senpass_siteweb.git
cd senpass_siteweb

# Installer les dépendances backend
composer install

# Installer les dépendances frontend
npm install && npm run dev

# Configurer .env
cp .env.example .env
php artisan key:generate

# Migrer la base de données
php artisan migrate
```

---

## 🔒 Sécurité & confidentialité

* Chiffrement des données sensibles (AES-256 / RSA)
* Authentification via token sécurisé (JWT / Laravel Sanctum)
* Système de rôles & permissions
* Conformité à la Loi n° 2008-12 du Sénégal (Protection des données)
* Audit & traçabilité intégrés

---

## 🌍 Vision UEMOA

Senpass est conçu comme un **modèle interopérable** et extensible pour les 8 pays de l’UEMOA, avec un système modulaire qui gère les identifiants nationaux, les indicatifs régionaux et les services personnalisés.

---

## 🧑‍💻 Contribuer

Envie d’aider ? Voici comment démarrer :

1. **Fork** le dépôt
2. Créez une branche : `git checkout -b feature/ma-fonctionnalite`
3. **Codez** votre fonctionnalité
4. Commitez : `git commit -m "Ajout fonctionnalité"`
5. Pushez : `git push origin feature/ma-fonctionnalite`
6. Ouvrez une **Pull Request**

---

## 📄 Licence

Distribué sous la licence **MIT**. Voir `LICENSE` pour plus d’informations.

---

## 📬 Contact & Informations

* 🌐 Site officiel : [https://senpass.sn](https://senpass.sn) *(en construction)*
* 🏢 Développé par : [Bishflix Systems](https://bishflix.com)
* ✉️ Email : [contact@senpass.sn](mailto:contact@senpass.sn)
* 📍 Dakar, Sénégal

---

> 🇸🇳 *"Une identité numérique pour tous. Un accès sécurisé. Un Sénégal plus connecté."*

```

```
