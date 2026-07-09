# 🐧 Mise à jour d'une machine virtuelle Ubuntu

## 🎯 Contexte

Cette machine virtuelle Ubuntu a été téléchargée depuis une ressource en ligne. Avant de l'utiliser pour mes futurs laboratoires, j'ai souhaité vérifier son état et effectuer les mises à jour nécessaires.

---

## 🎯 Objectif

Préparer une machine virtuelle propre, à jour et prête à être utilisée pour les prochains travaux pratiques Linux.

---

## 🛠️ Étapes réalisées

### 1. Démarrage de la machine virtuelle

J'ai lancé la machine virtuelle Ubuntu et ouvert une session utilisateur.

![Ubuntu Login](https://github.com/MelTechJourney/linux-lab/blob/main/screenshots/01-vm-login-screen.png)

![Ubuntu Desktop](https://github.com/MelTechJourney/linux-lab/blob/main/screenshots/02-ubuntu-desktop.png)

---

### 2. Mise à jour de la liste des paquets

Commande utilisée :

```bash
sudo apt update
```

Cette commande permet de récupérer la liste des dernières versions disponibles des paquets présents dans les dépôts configurés.

![APT Update](https://github.com/MelTechJourney/linux-lab/blob/main/screenshots/03-apt-update.png)

---

### 3. Mise à jour des paquets installés

Commande utilisée :

```bash
sudo apt upgrade
```

Cette étape installe les mises à jour disponibles pour les logiciels déjà présents sur le système.

![APT Upgrade](https://github.com/MelTechJourney/linux-lab/blob/main/screenshots/04-apt-upgrade.png)

---

### 4. Suppression des dépendances inutiles

Commande utilisée :

```bash
sudo apt autoremove
```

Cette commande supprime les paquets devenus inutiles après les mises à jour.

![APT Autoremove](https://github.com/MelTechJourney/linux-lab/blob/main/screenshots/05-apt-autoremove.png)

---

### 5. Vérification et configuration de la langue

J'ai vérifié la langue actuellement utilisée par le système et commencé la configuration de l'environnement en français.

![Language Configuration](https://github.com/MelTechJourney/linux-lab/blob/main/screenshots/06-language-configuration.png)

---

### 6. Vérification des informations système

Commande utilisée :

```bash
neofetch
```

Cette commande affiche un résumé des principales informations concernant le système (version d'Ubuntu, noyau Linux, processeur, mémoire, environnement graphique, etc.).

![Neofetch](https://github.com/MelTechJourney/linux-lab/blob/main/screenshots/07-neofetch-system-information.png)

---

## 💡 Ce que j'ai appris

Cette première manipulation m'a permis de comprendre la différence entre :

- `apt update` : met à jour la liste des paquets disponibles.
- `apt upgrade` : installe les mises à jour des paquets déjà installés.
- `apt autoremove` : supprime les dépendances devenues inutiles.

J'ai également retenu qu'avant d'utiliser un système, il est important de vérifier son état et de le maintenir à jour afin de bénéficier des dernières corrections de sécurité et d'améliorations.

---

## 🚀 Prochaine étape

Poursuivre ma découverte de Linux avant de commencer la mise en place de mon laboratoire Active Directory sous Windows Server.
