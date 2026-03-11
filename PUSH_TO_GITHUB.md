# 🚀 Instructions pour Pusher sur GitHub

Votre projet est prêt ! Suivez ces étapes simples pour le publier sur GitHub.

## Étape 1 : Créer un repository sur GitHub

1. Allez sur **https://github.com/new**
2. Remplissez les informations :
   - **Repository name** : `Projet-01` (ou le nom que vous préférez)
   - **Description** : `OpenVAS : Guide Complet de A à Z - Tutoriel de cybersécurité`
   - **Visibility** : Public (pour votre portfolio)
   - **Ne cochez PAS** "Initialize this repository with a README"
3. Cliquez sur **"Create repository"**

## Étape 2 : Copier l'URL de votre repository

Une fois créé, GitHub vous affichera l'URL. Elle ressemblera à :
```
https://github.com/VOTRE_USERNAME/Projet-01.git
```

## Étape 3 : Exécuter les commandes pour pousher

Ouvrez PowerShell ou Bash et exécutez ces commandes (remplacez par votre vraie URL) :

```bash
cd "C:\Users\Rhemael\OneDrive\Documents\WeCode\Mini-Projet\Projet-01\Github"

# Configurer le repository distant
git remote add origin https://github.com/VOTRE_USERNAME/Projet-01.git

# Renommer la branche en 'main'
git branch -M main

# Pousser le code sur GitHub
git push -u origin main
```

## Étape 4 : Vérifier que c'est bon

- Allez sur votre repository GitHub
- Vous devriez voir :
  - ✅ Le README.md bien formaté
  - ✅ Le fichier LICENSE
  - ✅ Le fichier .gitignore
  - ✅ Le PDF de votre rapport
  - ✅ Le badge "Status: Complete"

## ✨ Résumé - Fichiers dans votre repository

```
Projet-01/
├── README.md                                  (Professionnel et complet)
├── SN-FC-004_Brou-Yao-Jean-Yves.pdf         (Votre rapport détaillé)
├── LICENSE                                    (MIT)
└── .gitignore                                (Configuré)
```

## 🎯 Une fois sur GitHub

Pour ajouter ce projet à votre portfolio :
1. Ajoutez le lien dans votre portfolio Web/CV
2. Rendez le repository "Featured" (optionnel)
3. Invitez des recruteurs à consulter votre travail !

---

**Note** : Git est déjà initialisé et tous les commits sont créés. Vous n'avez que les 3 commandes ci-dessus à exécuter ! 🎉
