# LAB10 - NavigationDrawerDemo

Application Android démontrant l'implémentation d'un **Navigation Drawer**
avec gestion dynamique de plusieurs fragments dans une seule activité.

---

## 📸 Captures d'écran

### Écran principal — Fragment 1 (Rose)
<!-- Ajouter capture ici -->
![Fragment 1](screenshots/fragment1.png)

### Fragment 2 (Bleu)
<!-- Ajouter capture ici -->
![Fragment 2](screenshots/fragment2.png)

### Fragment List
<!-- Ajouter capture ici -->
![Fragment List](screenshots/fragment_list.png)

### Navigation Drawer ouvert
<!-- Ajouter capture ici -->
![Navigation Drawer](screenshots/drawer_open.png)

---

## 🎥 Vidéo démonstrative
<!-- Ajouter vidéo ici -->
![Demo](screenshots/demo.gif)

> 💡 Pour créer un GIF depuis une vidéo :
> [ezgif.com](https://ezgif.com/video-to-gif)

---

## 🎯 Objectif pédagogique

Apprendre à :
- Créer un **Navigation Drawer** manuellement
- Gérer dynamiquement plusieurs **Fragments**
- Manipuler le **FragmentManager**
- Personnaliser les **icônes vectorielles**
- Appliquer un **thème Material Design**

---

## 🗂️ Architecture du projet
NavigationDrawerDemo/
│
├── app/src/main/
│   ├── java/com/example/navigationdrawerdemo/
│   │   ├── MainActivity.java
│   │   ├── BlankFragment.java
│   │   ├── BlankFragment2.java
│   │   └── FragmentList.java
│   │
│   └── res/
│       ├── drawable/
│       │   ├── ic_home.xml
│       │   ├── ic_dashboard.xml
│       │   └── ic_list.xml
│       ├── layout/
│       │   ├── activity_main.xml
│       │   ├── content_main.xml
│       │   ├── nav_header_main.xml
│       │   ├── fragment_blank.xml
│       │   └── fragment_blank2.xml
│       ├── menu/
│       │   └── activity_main_drawer.xml
│       └── values/
│           ├── colors.xml
│           ├── strings.xml
│           └── themes.xml

---

## 🛠️ Technologies utilisées

| Technologie | Version |
|---|---|
| Android Studio | Ladybug+ |
| Java | 8+ |
| Min SDK | API 24 (Android 7.0) |
| Material Components | 1.11.0 |
| AndroidX DrawerLayout | 1.2.0 |

---

## ⚙️ Installation

```bash
# Cloner le dépôt
git clone https://github.com/TON_USERNAME/NavigationDrawerDemo.git

# Ouvrir dans Android Studio
File > Open > NavigationDrawerDemo

# Synchroniser Gradle
Cliquer sur "Sync Now"

# Lancer l'application
Shift + F10
```

---

## 📱 Fonctionnalités

| Fonctionnalité | Description |
|---|---|
| 🏠 **Fragment 1** | Fond rose avec icône Home |
| 📊 **Fragment 2** | Fond bleu avec icône Dashboard |
| 📋 **Fragment List** | Liste de 10 items scrollable |
| ☰ **Navigation Drawer** | Menu latéral avec header profil |
| 🔙 **Bouton retour** | Ferme le drawer si ouvert |

---

## 🧩 Fragments

### BlankFragment (Fragment 1)
- Fond : `#F8BBD0` (Rose Pink 100)
- Icône : `ic_home`
- Chargé par défaut au lancement

### BlankFragment2 (Fragment 2)
- Fond : `#3F51B5` (Indigo 500)
- Icône : `ic_dashboard`

### FragmentList
- Liste de 10 items avec `ArrayAdapter`
- Utilise `android.R.layout.simple_list_item_1`

---

## 👨‍💻 Auteur

**Ton Nom**
- GitHub : [@TON_USERNAME](https://github.com/TON_USERNAME)
- Email : ton@email.com
