# 🔭 Browsers Secrets — Workshop DIY

> **Explorez ensemble les pages cachées de Chrome et Edge !**
> Un atelier parent-enfant à partir de 8 ans 🚀

---

## 👨‍👩‍👧 Pourquoi faire cet atelier ensemble ?

Ce n'est pas un atelier où l'enfant regarde l'adulte taper sur un clavier.
C'est l'inverse : **l'enfant explore, l'adulte découvre avec lui.**

Chrome et Edge — les navigateurs que vous utilisez tous les jours — cachent des dizaines
de pages secrètes que même la plupart des adultes ne connaissent pas.

En les explorant ensemble, vous allez naturellement parler de :
- 🌐 Comment fonctionne vraiment internet ?
- 🛡️ Comment mon ordi se protège des virus ?
- 🧠 Pourquoi le navigateur ralentit avec trop d'onglets ?
- 📡 Qui peut voir ce que je fais en ligne ?

**Pas besoin d'être informaticien. La curiosité suffit.** 😊

---

## 🤔 C'est quoi `chrome://` et `edge://` ?

Quand tu tapes `youtube.com`, tu accèdes à un site sur internet.
Mais quand tu tapes `chrome://quelquechose` ou `edge://quelquechose`,
tu accèdes à une **page interne** du navigateur lui-même —
comme ouvrir le capot d'une voiture pour voir le moteur.

Ces pages existent depuis toujours mais Google et Microsoft n'en parlent jamais.
Elles servent aux ingénieurs pour tester et déboguer les navigateurs.
Et elles sont fascinantes à explorer !

| Navigateur | Préfixe | Exemple |
|-----------|---------|---------|
| 🟢 **Google Chrome** | `chrome://` | `chrome://dino` |
| 🔵 **Microsoft Edge** | `edge://` | `edge://surf` |

---

## 🚀 Lancer l'application

### En local (sans internet)
1. Télécharge **`workshop-browsers-secrets.html`**
2. Ouvre-le dans **Google Chrome** ou **Microsoft Edge**
3. Glisse-dépose le fichier dans le navigateur
4. C'est tout — le fichier est autonome, tout est dedans ! 🎉

### En ligne
```
https://abourdim.github.io/tools/
```

> ⚠️ **Chrome uniquement pour les adresses chrome://, Edge pour edge://**
> Pas Firefox, pas Safari — ces adresses sont propres à chaque navigateur.

---

## 🟢🔵 Choisir son navigateur

En haut de l'application, deux onglets permettent de basculer :

```
┌─────────────────────────────────────────────────────┐
│   🟢 Chrome (46)        🔵 Edge (50)                │
└─────────────────────────────────────────────────────┘
```

- **🟢 Chrome** — affiche toutes les URLs `chrome://...` en vert
- **🔵 Edge** — affiche toutes les URLs `edge://...` en bleu, plus les **exclusifs Edge**
- Un clic bascule tout instantanément — même catégorie, mêmes filtres

> 💡 **La plupart des secrets sont identiques !** Chrome et Edge sont tous les deux
> basés sur Chromium. Seules les URLs changent (`chrome://` → `edge://`).
> Edge a en plus 4 exclusifs Microsoft.

---

## 📋 Comment utiliser un secret

Les adresses `chrome://` et `edge://` **ne peuvent pas** s'ouvrir automatiquement
depuis une page web — règle de sécurité de Google et Microsoft.

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  1.  Clique 📋 sur le secret de ton choix                   │
│      → l'URL est copiée dans ton presse-papier              │
│                                                             │
│  2.  Dans Chrome ou Edge, clique la barre d'adresse  Ctrl+L │
│                                                             │
│  3.  Colle l'URL                                   Ctrl+V   │
│                                                             │
│  4.  Appuie sur Entrée                             Entrée   │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🎮 Les Secrets — Liste Complète

### 🎮 Fun & Jeux *(4 secrets — commencez par ici !)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| 🦕 Jeu caché | `chrome://dino` | `edge://surf` 🏄 | ⭐ Facile |
| 🗺️ Toutes les adresses | `chrome://chrome-urls` | `edge://edge-urls` | ⭐ Facile |
| 🌟 Les héros (crédits) | `chrome://credits` | `edge://credits` | ⭐ Facile |
| 🆕 Nouveautés | `chrome://whats-new` | `edge://whats-new` | ⭐ Facile |

> 🦕 Le dino Chrome s'appelle **"Project Bolan"** en interne.
> Le surf Edge est bien plus élaboré — modes, costumes, boss ! 🏄

---

### 🌐 À Propos du Navigateur *(5 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| 🪪 Carte d'identité | `chrome://version` | `edge://version` | ⭐ Facile |
| 📋 Fichier de config | `chrome://local-state` | `edge://local-state` | 🤩 Wow ! |
| 🧩 Composants internes | `chrome://components` | `edge://components` | 🔬 Moyen |
| 📊 Informations système | `chrome://system` | `edge://system` | 🔬 Moyen |
| 📜 Conditions d'utilisation | `chrome://terms` | `edge://terms` | ⭐ Facile |

---

### 🔵 Exclusifs Edge *(4 secrets — uniquement dans Edge !)*

| Secret | Adresse | Niveau |
|--------|---------|--------|
| 💰 Microsoft Rewards | `edge://rewards` | ⭐ Facile |
| 🛍️ Assistant Shopping | `edge://shopping` | ⭐ Facile |
| 📋 Collections | `edge://collections` | ⭐ Facile |
| ⚡ Mode Performance | `edge://performance` | 🔬 Moyen |

> 💰 Edge **paie littéralement** les gens pour naviguer !
> Les Rewards s'échangent contre des cartes cadeaux Xbox, Amazon et plus.

---

### ⚗️ Laboratoire Secret *(7 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| ⚗️ Fonctions cachées (Flags) | `chrome://flags` | `edge://flags` | 🔬 Moyen |
| 🔍 Inspecteur DevTools | `chrome://inspect` | `edge://inspect` | 🤩 Wow ! |
| 📡 Radar Bluetooth | `chrome://bluetooth-internals` | `edge://bluetooth-internals` | 🔬 Moyen |
| 📺 Labo vidéo & son | `chrome://media-internals` | `edge://media-internals` | 🔬 Moyen |
| 📞 Appels vidéo (WebRTC) | `chrome://webrtc-internals` | `edge://webrtc-internals` | 🤩 Wow ! |
| 🖨️ Impression | `chrome://print` | `edge://print` | ⭐ Facile |
| 📥 Téléchargements | `chrome://download-internals` | `edge://download-internals` | 🔬 Moyen |

---

### 📡 Réseau & Internet *(6 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| 🌐 Annuaire Internet (DNS) | `chrome://net-internals/#dns` | `edge://net-internals/#dns` | 🔬 Moyen |
| 🔌 Connexions TCP | `chrome://net-internals/#sockets` | `edge://net-internals/#sockets` | 🤩 Wow ! |
| ⚡ HTTP/2 Sessions | `chrome://net-internals/#http2` | `edge://net-internals/#http2` | 🤩 Wow ! |
| 🌍 Événements réseau | `chrome://net-internals/#events` | `edge://net-internals/#events` | 🤩 Wow ! |
| 🔄 Proxy & VPN | `chrome://net-internals/#proxy` | `edge://net-internals/#proxy` | 🔬 Moyen |
| 🛑 Pages d'erreur | `chrome://network-errors` | `edge://network-errors` | ⭐ Facile |

---

### 🚀 Performance *(6 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| 🎨 Carte graphique (GPU) | `chrome://gpu` | `edge://gpu` | 🔬 Moyen |
| 🧠 Mémoire RAM | `chrome://memory-internals` | `edge://memory-internals` | 🔬 Moyen |
| 😴 Onglets dormants | `chrome://discards` | `edge://discards` | 🔬 Moyen |
| 📈 Histogrammes perf | `chrome://histograms` | `edge://histograms` | 🤩 Wow ! |
| 🔬 Traçage performance | `chrome://tracing` | `edge://tracing` | 🤩 Wow ! |
| ⚙️ Processus internes | `chrome://process-internals` | `edge://process-internals` | 🤩 Wow ! |

---

### 🛡️ Sécurité *(4 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| 🛡️ Gardien sécurité | `chrome://safe-browsing` | `edge://safe-browsing` | ⭐ Facile |
| 📦 Sandbox (bac à sable) | `chrome://sandbox` | `edge://sandbox` | 🔬 Moyen |
| 🔑 Mots de passe (logs) | `chrome://password-manager-internals` | `edge://password-manager-internals` | 🔬 Moyen |
| 🏢 Politiques admin | `chrome://policy` | `edge://policy` | 🔬 Moyen |

---

### 💾 Données & Stockage *(4 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| 💿 Quotas stockage | `chrome://quota-internals` | `edge://quota-internals` | 🤩 Wow ! |
| 🗄️ Base de données (IndexedDB) | `chrome://indexeddb-internals` | `edge://indexeddb-internals` | 🤩 Wow ! |
| ⚡ Service Workers | `chrome://serviceworker-internals` | `edge://serviceworker-internals` | 🤩 Wow ! |
| 📊 Engagement sites | `chrome://site-engagement` | `edge://site-engagement` | ⭐ Facile |

---

### 🔄 Synchronisation *(2 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| 🔄 Synchronisation | `chrome://sync-internals` | `edge://sync-internals` | 🔬 Moyen |
| 👤 Connexion compte | `chrome://signin-internals` | `edge://signin-internals` | 🔬 Moyen |

---

### 🔧 Outils Avancés *(8 secrets)*

| Secret | 🟢 Chrome | 🔵 Edge | Niveau |
|--------|-----------|---------|--------|
| ♿ Accessibilité (A11Y) | `chrome://accessibility` | `edge://accessibility` | 🤩 Wow ! |
| 🔤 Traduction auto | `chrome://translate-internals` | `edge://translate-internals` | 🔬 Moyen |
| 🎯 Prédictions omnibox | `chrome://predictors` | `edge://predictors` | 🔬 Moyen |
| 💡 Suggestions contenu | `chrome://suggestions` | `edge://suggestions` | ⭐ Facile |
| 🖥️ Appareils USB | `chrome://usb-internals` | `edge://usb-internals` | 🔬 Moyen |
| 📱 Appareils proches | `chrome://devices` | `edge://devices` | ⭐ Facile |
| 📊 Actions utilisateur | `chrome://user-actions` | `edge://user-actions` | 🤩 Wow ! |
| 📲 Cast (TV) | `chrome://cast` | `edge://cast` | ⭐ Facile |

---

## ⭐ Les niveaux de difficulté

| Niveau | Pour qui | Exemple |
|--------|----------|---------|
| ⭐ **Facile** | Tout le monde dès 8 ans | `chrome://dino` — appuie sur Espace et joue ! |
| 🔬 **Moyen** | Les curieux, 10 ans+ | `chrome://gpu` — regarde ta carte graphique |
| 🤩 **Wow !** | Les explorateurs | `chrome://user-actions` — vois chaque clic en direct ! |

> ⚠️ Pour les pages **Moyen** et **Wow**, **demande à un adulte** avant de changer quoi que ce soit.
> Regarder ne cause jamais de problème — c'est modifier qui peut être risqué.

---

## 🕹️ Les Easter Eggs de l'Application

L'application elle-même cache des surprises ! 🤫

| Action | Surprise |
|--------|----------|
| ⬆️⬆️⬇️⬇️⬅️➡️⬅️➡️ **B A** au clavier | 🎮 Mode Rétro vert (Konami Code !) |
| Tape `matrix` au clavier | 💚 Pluie de code Matrix |
| Tape `debug` au clavier | 🔧 Panneau de débogage secret |
| Clique plusieurs fois sur le logo | 🐾 La mascotte s'anime ! |

---

## 🎨 Personnalisation

### 8 Thèmes (bouton ⚙️ en haut à droite)

| Thème | Ambiance |
|-------|----------|
| 🚀 **Space Explorer** | Violet cosmique *(défaut)* |
| 🕌 **Mosque Gold** | Or et bleu nuit |
| 🔷 **Zellige Blue** | Bleu azur marocain |
| 🌿 **Andalus Green** | Vert jardin andalou |
| 🏡 **Riad** | Ivoire et terracotta *(clair)* |
| 🕌 **Medina** | Blanc perle et jade *(clair)* |
| 🌴 **Jungle Quest** | Vert tropical |
| 🤖 **Robot Lab** | Bleu électrique |

### 3 Langues

- 🇫🇷 Français *(défaut)*
- 🇬🇧 English
- 🇩🇿 العربية — mise en page droite-à-gauche automatique !

---

## 🏫 Guide Animateur

### Déroulement suggéré (1h30)

| Durée | Activité |
|-------|----------|
| **10 min** | Introduction : "Connaissez-vous le dinosaure Chrome ?" → montrer `chrome://dino` et `edge://surf` |
| **5 min** | Expliquer comment copier-coller une URL secrète |
| **10 min** | Choisir son navigateur et explorer les **⭐ Faciles** ensemble |
| **30 min** | Exploration libre par catégorie — chaque enfant choisit |
| **15 min** | Chacun présente le secret le plus surprenant qu'il a trouvé |
| **10 min** | Discussion : "Chrome vs Edge — lequel préfères-tu et pourquoi ?" |
| **10 min** | Questions |

### Les 5 secrets à montrer en premier

1. **`chrome://dino`** / **`edge://surf`** — Le jeu caché ! Tout le monde connaît le dino 🦕
2. **`chrome://site-engagement`** — Ils voient leurs propres sites préférés avec des scores !
3. **`chrome://memory-internals`** — "Voilà pourquoi l'ordi rame avec 30 onglets !"
4. **`chrome://bluetooth-internals`** — Radar qui voit tous les appareils Bluetooth autour d'eux 📡
5. **`edge://rewards`** — "Edge te donne des points pour naviguer !" 💰

### Questions pour faire réfléchir

- *"Pourquoi Chrome et Edge ont des adresses différentes ?"* → Chromium vs personnalisation
- *"Qu'est-ce qui se passe quand tu tapes youtube.com ?"* → DNS
- *"Comment le navigateur sait si un site est dangereux ?"* → Safe Browsing
- *"Pourquoi Edge te donne des points ?"* → Concurrence entre navigateurs

---

## ⚠️ Règles importantes

```
✅ Tu PEUX toujours :        ⚠️ Sans adulte, ne change PAS :
──────────────────────       ──────────────────────────────
Regarder toutes              Les flags sur
les pages                    chrome:// ou edge://flags

Copier et coller             Les fichiers sur
les adresses                 chrome://local-state

Jouer au dino 🦕             Les politiques sur
ou au surf 🏄                chrome://policy
```

---

## 🗂️ Fichiers du projet

```
browsers-secrets/
├── 📄 workshop-browsers-secrets.html   ← L'application complète
│                                        Chrome 🟢 + Edge 🔵 + 8 thèmes
│                                        Tout intégré, 0 dépendance
│
└── 📖 README.md                        ← Ce fichier
```

---

## 🌍 Workshop-DIY

Des ateliers d'initiation à l'informatique, l'IA, la robotique et le code
pour les enfants et les familles !

| | |
|-|-|
| 🌐 Site | [workshop-diy.org](https://workshop-diy.org) |
| ✉️ Email | contact@workshop-diy.org |
| 📞 Téléphone | 06 19 51 51 73 |
| 📍 Lieu | Salle du Parc du Souvenir, Stade Pierre Duport — Chelles |
| 🎟️ Non-adhérent | 7 € / atelier |
| ✅ Adhérent | Gratuit |

---

*بِسْمِ ٱللَّٰهِ ٱلرَّحْمَـٰنِ ٱلرَّحِيمِ*

*✨ Curiosité et sourire bienvenus !*
