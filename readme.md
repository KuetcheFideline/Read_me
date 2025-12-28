

# Installation de Miniconda sur Ubuntu 22.04

## 1. Télécharger Miniconda
Téléchargez la dernière version de Miniconda pour Linux 64-bit :  
```bash
  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
``` 
## 2. lancer l'instalation de mini Conda 

```bash 
bash ~/Miniconda3-latest-Linux-x86_64.sh
```
## 3. refresh le terminal au lieu de le fermer
```bash 
   source ~/.bashrc
```

## 4. retirer le .env a chaque lancement 
```bash 
  conda config --set auto_activate_base false   
```
## 5.creation d'un environement virtuel avec une version specifiques de python 
```bash 
conda create -n envCookie python=3.8
```
