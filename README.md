# LAB10 - NavigationDrawerDemo

Application Android démontrant l'implémentation d'un **Navigation Drawer**
avec gestion dynamique de plusieurs fragments dans une seule activité.

---

## 📸 Captures d'écran

### Écran principal — Fragment 1 (Rose)
<img width="531" height="799" alt="image" src="https://github.com/user-attachments/assets/a39b2c4e-8625-4c3c-ab27-c26fff0e07ae" />

### Fragment 2 (Bleu)
<img width="554" height="810" alt="image" src="https://github.com/user-attachments/assets/1f98c17b-384a-4b02-a574-026bda765395" />

### Fragment List
<img width="552" height="789" alt="image" src="https://github.com/user-attachments/assets/f387d0f1-e29c-46de-8cae-5fd0273c58fa" />


### Navigation Drawer ouvert
<img width="521" height="794" alt="image" src="https://github.com/user-attachments/assets/0e849410-e813-4c8d-9368-9a8085e7e7f9" />

---

## 🎥 Vidéo démonstrative
https://github.com/user-attachments/assets/eb3f0bd8-33ca-4af0-8402-16832d320dbf

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

```
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
```

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
git clone https://github.com/sana-sana25/LAB10.git

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

---

## 🧩Fragments

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

**ASSEKNOUR Sana**
ENSA-Marrakech
