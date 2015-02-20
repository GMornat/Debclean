# UbuntuCleaner
Un petit programme simple pour nettoyer et mettre à jour les paquets et le système

### Comment ça marche ?
C'est tout simplement un petit script batch, qui rend les commandes automatiques.

### Qui peut exécuter ce logiciel ?
Techniquement, tout système Debian, seule la distribution Ubuntu est supportée, ainsi que toutes ses dérives xfce, gnome, KDE, et autres. Il vous faut aussi quelques bases avec le terminal, mais franchement ce n'est pas très compliqué...

### Installation
* Il vous suffit d'aller dans Releases, télécharger le code source, et d'extraire les fichiers. Vous pouvez aussi utiliser git clone. A vous de voir. 
* Il faut rendre le fichier exécutable, pour cela, entrez la commande

```sh
chmod a+x ubuntucleaner
```

* Ensuite, pour exécuter le fichier

```sh
./ubuntucleaner
```

### Qu'est ce que ça fait concrétement ?
* Dans un premier temps, on vous demande votre mot de passe
* Le script met à jour la base de données de paquets
* Puis supprime le cache et les paquets inutiles
* Met à jour les paquets et le système

### A venir
* Version anglophone
* Meilleure présentation
* Votre aide aimable ?
