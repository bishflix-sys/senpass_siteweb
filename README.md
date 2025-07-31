
# 🇸🇳 Senpass – Portail d'identité numérique nationale du Sénégal

**Senpass** est une plateforme d’identité numérique souveraine développée pour permettre à chaque citoyen sénégalais d’accéder de manière sécurisée, rapide et centralisée aux services publics et privés. Le projet est basé sur une architecture moderne combinant Laravel, Blade, TypeScript, SCSS et d'autres technologies robustes.

> 🛡️ Projet porté par **Bishflix Systems** – Pour une Afrique connectée et souveraine.

---

## 📊 Technologies principales

| Technologie       | Rôle dans le projet                           |
|-------------------|-----------------------------------------------|
| **Laravel**       | Framework backend PHP (routes, APIs, logique) |
| **Blade**         | Moteur de templates Laravel                   |
| **PHP**           | Langage backend principal                     |
| **SCSS (48.7%)**  | Stylisation modulaire, responsive et maintenable |
| **TypeScript (26.2%)** | Frontend typé et structuré               |
| **JavaScript**    | Dynamique UI (complément TypeScript)          |
| **CSS**           | Fallback styles ou simples surcharges         |

---

## ✨ Fonctionnalités principales

- 🔐 Authentification forte (Mot de passe + OTP ou QR Code)
- 🆔 Gestion du **profil numérique citoyen**
- 📑 Intégration avec services administratifs : e-santé, e-foncier, e-éducation, e-finance
- 🖋️ Signature électronique conforme
- 🌍 Compatibilité régionale UEMOA (gestion multi-indicatifs)
- 📱 Interface responsive pour Web & Mobile

---

## 🗂️ Structure du projet Laravel

```plaintext
senpass_siteweb/
├── app/                 # Logique Laravel (Models, Controllers, Policies)
├── resources/
│   ├── views/           # Templates Blade
│   ├── scss/            # Styles SCSS (structurés par pages)
│   └── js/              # Scripts TypeScript / JavaScript
├── public/              # Assets publics (images, JS/CSS compilés)
├── routes/
│   ├── web.php          # Routes web
│   └── api.php          # API REST sécurisée
├── database/            # Migrations, Seeders
├── .env.example         # Configuration d’environnement
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

### 📦 Installation étape par étape

```bash
# Cloner le dépôt
git clone https://github.com/bishflix-sys/senpass_siteweb.git
cd senpass_siteweb

# Installer les dépendances PHP
composer install

# Installer les dépendances frontend
npm install && npm run dev

# Configuration de l’environnement
cp .env.example .env
php artisan key:generate

# Créer la base de données (à adapter dans .env)
php artisan migrate
```

---

## 🔐 Sécurité & conformité

* 🔒 Chiffrement des données (AES-256, RSA)
* ✅ Authentification basée sur Laravel Sanctum ou Passport
* 👥 Gestion des rôles et permissions
* 📝 Audit des accès & traçabilité
* 📜 Respect de la **loi n°2008-12** sur la protection des données (CDP Sénégal)

---

## 🌍 Extension UEMOA

Senpass est conçu pour une **interopérabilité régionale** : chaque utilisateur est associé à un identifiant unique et un indicatif téléphonique national, facilitant une gestion uniforme des identités dans les 8 pays membres de l’UEMOA.

---

## 🤝 Contribution

Vous souhaitez contribuer ? Voici comment faire :

1. Fork le dépôt
2. Créez une branche `feature/ma-fonctionnalite`
3. Commitez vos modifications
4. Pushez la branche
5. Créez une Pull Request pour revue

---

## 📄 Licence

Projet sous licence **MIT**. Voir `LICENSE` pour plus d’informations.

---

## 📬 Contact

* 🌐 Site web : [https://senpass.sn](https://senpass.sn) *(en cours)*
* 📧 Email : [contact@senpass.sn](mailto:contact@senpass.sn)
* 🏢 Organisation : Bishflix Systems, Dakar – Sénégal

---

> 🇸🇳 *"Une identité numérique fiable pour chaque citoyen. Un Sénégal plus connecté, plus souverain."*

``
