# LeonidBoost
🚀 Boost instantané pour Windows : nettoyage, optimisation réseau, plan d'alim ultra perf et lancement automatisé de Sophia Script – développé par Norealis.

# ⚡ LeonidBoost – par Norealis

**LeonidBoost** est un script PowerShell transformé en exécutable, conçu par **Norealis** pour améliorer instantanément les performances de Windows. Léger, autonome, et sans dépendance externe, il s’exécute en quelques secondes et laisse toujours l’utilisateur aux commandes.

---

## 🔧 Fonctions incluses

- Création d’un **point de restauration**
- **Nettoyage** des fichiers temporaires système
- Activation du plan d’alimentation **"Ultra Performance"**
- Optimisation du **réseau TCP**
- Ouverture automatique :
  - de **Snappy Driver Installer** pour mettre à jour les pilotes
  - de **WinToys** via le Microsoft Store
- Téléchargement et exécution de **Sophia Script** dans une fenêtre PowerShell dédiée

---

## 🧩 Prérequis

- Windows 10 ou 11
- Droits administrateur (demandés automatiquement)
- Connexion Internet active

---

## ▶️ Utilisation

1. Double-clique sur `LeonidBoost.exe`
2. Accepte la demande d’élévation
3. Laisse le script s’exécuter
4. Consulte les logs à l’écran avant de fermer

---

## 🛠 Développement

Développé en PowerShell par **Norealis**. Compilation via [`ps2exe`](https://github.com/MScholtes/TechNet-Gallery/tree/master/ps2exe):
```powershell
ps2exe.ps1 -inputFile Optimisation.ps1 -outputFile LeonidBoost.exe -iconFile icon.ico
