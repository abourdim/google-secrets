# 🔭 Chrome Secrets — Workshop DIY

> **Explore les pages cachées de ton navigateur préféré !**
> Un atelier interactif pour les curieux de 10 ans et plus 🚀

---

## 🤔 C'est quoi Chrome Secrets ?

Tu utilises Google Chrome tous les jours pour aller sur YouTube, jouer ou faire tes recherches.
Mais savais-tu que Chrome cache des **dizaines de pages secrètes** auxquelles presque personne n'accède ?

Ces pages se trouvent à des adresses spéciales qui commencent par **`chrome://`** — et elles te montrent
les coulisses de ton navigateur : comment il dessine les images, comment il retrouve les sites web,
comment il te protège des virus, et même un jeu caché !

**Chrome Secrets** est une application web de Workshop-DIY qui te guide à travers **47 de ces pages secrètes**,
avec des explications simples, des astuces, et des anecdotes surprenantes. 🤯

---

## 🚀 Comment lancer l'application ?

### Option 1 — Fichier local (recommandé pour l'atelier)

1. Télécharge le fichier **`workshop-chrome-secrets.html`**
2. Ouvre-le dans **Google Chrome** (double-clic, ou glisse-dépose dans Chrome)
3. C'est tout ! L'application fonctionne hors connexion, aucune installation requise.

### Option 2 — En ligne

Ouvre directement l'application via le lien Workshop-DIY :
```
https://abourdim.github.io/tools/
```

---

## 📋 Comment utiliser un secret ?

Les adresses `chrome://` sont des adresses **internes** à Chrome.
Elles ne fonctionnent **pas** comme les sites web normaux — tu ne peux pas cliquer sur un lien
pour les ouvrir depuis une autre page web. Il faut les taper (ou coller) dans la barre d'adresse.

### Étapes simples :

```
┌─────────────────────────────────────────────────────────┐
│  1. Clique le bouton  📋  à côté d'un secret            │
│     → L'URL est copiée dans ton presse-papier            │
│     → Chrome essaie aussi d'ouvrir l'onglet              │
│                                                          │
│  2. Si l'onglet ne s'ouvre pas automatiquement :         │
│     → Appuie sur  Ctrl + L  (sélectionne la barre)       │
│     → Appuie sur  Ctrl + V  (colle l'URL)                │
│     → Appuie sur  Entrée                                 │
└─────────────────────────────────────────────────────────┘
```

> 💡 **Pourquoi ça ne s'ouvre pas tout seul ?**
> C'est une règle de sécurité de Google : aucun site web ne peut forcer Chrome à ouvrir
> une page `chrome://`. C'est pour te protéger !

---

## 🎮 Les 47 Secrets — Liste Complète

### 🎮 Fun & Jeux *(4 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 🦕 Jeu du Dinosaure | `chrome://dino` | ⭐ Facile |
| 🗺️ Toutes les Adresses | `chrome://chrome-urls` | ⭐ Facile |
| 🌟 Les Héros (Crédits) | `chrome://credits` | ⭐ Facile |
| 🆕 Nouveautés Chrome | `chrome://whats-new` | ⭐ Facile |

### 🌐 À Propos de Chrome *(5 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 🪪 Carte d'Identité | `chrome://version` | ⭐ Facile |
| 📋 État Local (JSON) | `chrome://local-state` | 🤩 Wow ! |
| 🧩 Composants Chrome | `chrome://components` | 🔬 Moyen |
| 📊 Informations Système | `chrome://system` | 🔬 Moyen |
| 📜 Conditions d'Utilisation | `chrome://terms` | ⭐ Facile |

### ⚗️ Laboratoire Secret *(6 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| ⚗️ Laboratoire (Flags) | `chrome://flags` | 🔬 Moyen |
| 🔍 Inspecteur DevTools | `chrome://inspect` | 🤩 Wow ! |
| 📡 Bluetooth Radar | `chrome://bluetooth-internals` | 🔬 Moyen |
| 📺 Labo Vidéo & Son | `chrome://media-internals` | 🔬 Moyen |
| 📞 WebRTC (Appels Vidéo) | `chrome://webrtc-internals` | 🤩 Wow ! |
| 🖨️ Impression | `chrome://print` | ⭐ Facile |
| 📥 Téléchargements | `chrome://download-internals` | 🔬 Moyen |

### 📡 Réseau & Internet *(6 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 🌐 Annuaire Internet (DNS) | `chrome://net-internals/#dns` | 🔬 Moyen |
| 🔌 Connexions TCP | `chrome://net-internals/#sockets` | 🤩 Wow ! |
| ⚡ HTTP/2 Sessions | `chrome://net-internals/#http2` | 🤩 Wow ! |
| 🌍 Événements Réseau | `chrome://net-internals/#events` | 🤩 Wow ! |
| 🔄 Proxy & VPN | `chrome://net-internals/#proxy` | 🔬 Moyen |
| 🛑 Pages d'Erreur | `chrome://network-errors` | ⭐ Facile |

### 🚀 Performance *(6 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 🎨 Carte Graphique (GPU) | `chrome://gpu` | 🔬 Moyen |
| 🧠 Mémoire RAM | `chrome://memory-internals` | 🔬 Moyen |
| 😴 Onglets Dormants | `chrome://discards` | 🔬 Moyen |
| 📈 Histogrammes Perf | `chrome://histograms` | 🤩 Wow ! |
| 🔬 Traçage Performance | `chrome://tracing` | 🤩 Wow ! |
| ⚙️ Processus Internes | `chrome://process-internals` | 🤩 Wow ! |

### 🛡️ Sécurité *(4 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 🛡️ Gardien Sécurité | `chrome://safe-browsing` | ⭐ Facile |
| 📦 Sandbox (Bac à Sable) | `chrome://sandbox` | 🔬 Moyen |
| 🔑 Mots de Passe (Logs) | `chrome://password-manager-internals` | 🔬 Moyen |
| 🏢 Politiques Entreprise | `chrome://policy` | 🔬 Moyen |

### 💾 Données & Stockage *(4 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 💿 Quotas Stockage | `chrome://quota-internals` | 🤩 Wow ! |
| 🗄️ Base de Données (IndexedDB) | `chrome://indexeddb-internals` | 🤩 Wow ! |
| ⚡ Service Workers | `chrome://serviceworker-internals` | 🤩 Wow ! |
| 📊 Engagement Sites | `chrome://site-engagement` | ⭐ Facile |

### 🔄 Synchronisation *(2 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 🔄 Synchronisation | `chrome://sync-internals` | 🔬 Moyen |
| 👤 Connexion Google | `chrome://signin-internals` | 🔬 Moyen |

### 🔧 Outils Avancés *(9 secrets)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| ♿ Accessibilité (A11Y) | `chrome://accessibility` | 🤩 Wow ! |
| 🔤 Traduction Auto | `chrome://translate-internals` | 🔬 Moyen |
| 🎯 Prédictions Omnibox | `chrome://predictors` | 🔬 Moyen |
| 💡 Suggestions Contenu | `chrome://suggestions` | ⭐ Facile |
| 🖥️ Appareils USB | `chrome://usb-internals` | 🔬 Moyen |
| 📱 Appareils Proches | `chrome://devices` | ⭐ Facile |
| 📊 Actions Utilisateur | `chrome://user-actions` | 🤩 Wow ! |
| 📲 Cast (Chromecast) | `chrome://cast` | ⭐ Facile |
| 🔔 Invalidations Sync | `chrome://invalidations` | 🤩 Wow ! |

---

## ⭐ Les niveaux expliqués

| Niveau | Signification |
|--------|---------------|
| ⭐ **Facile** | Parfait pour commencer ! Rien à configurer, juste observer. |
| 🔬 **Moyen** | Pour les curieux. Tu peux interagir, mais demande à un adulte avant de changer quoi que ce soit. |
| 🤩 **Wow !** | Des pages époustouflantes avec des données en temps réel. Impressionnant ! |

---

## 🎨 Personnalisation

### 8 Thèmes disponibles

Ouvre le panneau **⚙️ Paramètres** (bouton en haut à droite) et choisis ton thème préféré :

| Thème | Ambiance |
|-------|----------|
| 🚀 **Space Explorer** | Violet cosmique *(défaut)* |
| 🕌 **Mosque Gold** | Or et bleu nuit |
| 🔷 **Zellige Blue** | Bleu azur marocain |
| 🌿 **Andalus Green** | Vert jardin andalou |
| 🏡 **Riad** | Ivoire et terracotta *(clair)* |
| 🕌 **Medina** | Perle et jade *(clair)* |
| 🌴 **Jungle Quest** | Vert tropical |
| 🤖 **Robot Lab** | Bleu électrique |

### 3 Langues

- 🇫🇷 **Français** *(langue par défaut)*
- 🇬🇧 **English**
- 🇩🇿 **العربية** — avec mise en page droite-à-gauche automatique !

---

## 🕹️ Les Easter Eggs cachés dans l'app

L'application cache elle-même des surprises ! Essaie ces codes secrets :

| Code | Résultat |
|------|----------|
| ⬆️⬆️⬇️⬇️⬅️➡️⬅️➡️ B A | 🎮 Mode Rétro (Konami Code !) |
| Tape `matrix` au clavier | 💚 Pluie de code Matrix |
| Tape `debug` au clavier | 🔧 Panneau de débogage |
| Clique plusieurs fois sur le logo | 🐾 Animation de mascotte |
| Tape `morse` au clavier | 📡 Mode Morse |

---

## 🛠️ Fichiers du projet

```
workshop-chrome-secrets/
│
├── 📄 workshop-chrome-secrets.html   ← L'application complète (standalone)
│                                       Tout est intégré : CSS + JS + contenu
│
└── 📖 README.md                       ← Ce fichier !
```

> **Note :** Le fichier HTML est **autonome** (standalone). Il contient tout :
> le style, le code JavaScript, les 47 secrets, les 8 thèmes.
> Un seul fichier à partager, aucune dépendance !

---

## 🔧 Basé sur le template Workshop-DIY v1.2

Cette application est construite sur le **template officiel Workshop-DIY** qui inclut :

- 🎨 **8 thèmes** via `[data-theme]` sur `<html>`
- 🌐 **i18n trilingue** (FR / EN / AR) avec RTL automatique
- 📜 **Journal d'activité** avec filtres et export
- ⚙️ **Panneau Paramètres** coulissant
- ❓ **Panneau Aide** avec FAQ / Comment faire / Wiki
- 🐾 **Mascotte animée** Workshop-DIY
- 🎵 **Effets sonores** optionnels
- 🌙 **Splash screen** au démarrage
- 🕌 **Bismillah** animé dans le header
- 📅 **Date hijri** dans le footer
- 🎮 Easter eggs : Konami, Matrix rain, debug, mascotte

---

## 🏫 Pour les animateurs — Guide de l'atelier

### Déroulement suggéré (1h30)

| Durée | Activité |
|-------|----------|
| **10 min** | Introduction : "Qu'est-ce que Chrome fait vraiment ?" |
| **5 min** | Démonstration : ouvrir `chrome://dino` ensemble |
| **30 min** | Exploration libre par catégorie (⭐ Facile d'abord) |
| **20 min** | Défi en groupe : qui trouve le plus impressionnant ? |
| **15 min** | Discussion : "Comment fonctionne internet ?" |
| **10 min** | Questions et partage de découvertes |

### Conseils pédagogiques

- 🦕 **Commencer par `chrome://dino`** — tout le monde connaît le dinosaure, ça brise la glace
- 📊 **`chrome://site-engagement`** est très fun : les élèves voient leurs propres habitudes de navigation !
- 🧠 **`chrome://memory-internals`** ouvre un débat sur "pourquoi Chrome ralentit quand on a trop d'onglets"
- ⚗️ **`chrome://flags`** fascine les élèves mais attention : leur rappeler de ne rien changer sans un adulte
- 🌐 **`chrome://net-internals/#dns`** est parfait pour expliquer comment fonctionne internet

### Questions pour lancer la discussion

- *"Qu'est-ce qui se passe quand tu tapes youtube.com ?"* → DNS
- *"Pourquoi ton ordi est lent quand tu as 30 onglets ?"* → RAM/Discards
- *"Comment Chrome sait si un site est dangereux ?"* → Safe Browsing
- *"Est-ce que ton navigateur te 'regarde' ?"* → User Actions, Site Engagement

---

## ⚠️ Avertissements importants

> 🔴 **`chrome://flags`** — Ne change aucun flag sans comprendre ce que ça fait.
> Certains peuvent rendre Chrome instable. Utilise "Reset all" si quelque chose se passe mal.

> 🟡 **`chrome://local-state`** et **`chrome://system`** — Ces pages affichent des informations
> sur ton ordinateur. Ne partage pas de screenshots en public.

> 🟢 **Regarder** ces pages ne cause aucun dommage. La curiosité est toujours la bienvenue ! 😊

---

## 🌍 À propos de Workshop-DIY

**Workshop-DIY** propose des ateliers d'initiation à l'informatique, à l'IA, à la robotique
et au code pour les enfants et les familles.

- 🌐 Site web : [workshop-diy.org](https://workshop-diy.org)
- ✉️ Contact : contact@workshop-diy.org
- 📞 Téléphone : 06 19 51 51 73
- 📍 Lieu : Salle du Parc du Souvenir, Stade Pierre Duport — Chelles

### Rejoindre Workshop-DIY

| Statut | Tarif atelier |
|--------|---------------|
| 👤 Non-adhérent | 7 € / personne |
| ✅ Adhérent | Gratuit |

---

## 📝 Licence

Ce projet est développé par Workshop-DIY pour un usage éducatif.
Libre d'utilisation dans un cadre pédagogique non-commercial.

---

*بِسْمِ ٱللَّٰهِ ٱلرَّحْمَـٰنِ ٱلرَّحِيمِ*

*✨ Curiosité et sourire bienvenus !*
