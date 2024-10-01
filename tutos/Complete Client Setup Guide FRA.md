# Procédure d'installation complète de Project Gorgeous (client) (Français)

> ℹ️ **Note importante d'avant propos :** Il est fortement conseillé de lire l'intégralité de ce document attentivement une première fois avant de commencer l'installation. Suivez les étapes dans l'ordre et n'en sautez pas pour éviter tout problème. Enfin, prenez bien en considération les informations "ℹ️ **Note**" et "⚠️ **ATTENTION**" tout au long du document.

## Spécifications requises pour jouer au modpack
Project Gorgeous est un très gros modpack d'environ 650 mods, et nécessite donc une configuration matérielle assez puissante pour fonctionner correctement. Voici les spécifications techniques nécessaires pour jouer à Project Gorgeous :
- CPU récent avec une fréquence de boost de 4,4 GHz ou plus
- CPU avec 6 cœurs ou plus
- CPU avec 6 threads ou plus
- 12 Go de RAM allouée à Minecraft (14 Go recommandés)
- Minimum 16 Go de RAM sur votre PC
- Un stockage SSD
- Java 8 avec la JVM OpenJ9 d'IBM installé (voir la procédure d'installation ci-dessous)

> ⚠️ **ATTENTION :** Si votre configuration matérielle ne correspond pas à ces spécifications, il est possible que le modpack ne fonctionne pas correctement ou que vous rencontriez des problèmes de performances.

> ⚠️ **ATTENTION :** Le modpack prend entre **15 et 30 minutes pour démarrer**, en fonction de la puissance de votre configuration matérielle. **Évitez toute interaction avec la fenêtre du jeu** pendant ce temps pour éviter tout problème. Si votre fenêtre est en mode "Ne répond pas", **ne touchez à rien et attendez un peu**. Cela devrait revenir à la normale peu de temps après.

> ℹ️ **Note :** Pour le moment, le modpack n'a pas été testé sur Linux et MacOS. Il est recommandé de jouer sur Windows.

> ℹ️ **Note :** Il est recommandé de lancer une première fois le modpack pour qu'il génère les fichiers nécessaires, puis de le fermer et de le relancer avant de commencer à jouer.

## Procédure d'installation et de configuration de l'environnement du modpack

### I - Installation de Java 8 OpenJ9

> ⚠️ **ATTENTION :** Il est important d'installer et d'utiliser la version OpenJ9 de Java 8 pour lancer le modpack. Cette version particulière de Java distribuée par IBM permet de réduire la consommation de RAM de Minecraft.

> ℹ️ **Note :** Cette nouvelle installation ne devrait pas interférer avec votre installation Java actuelle.

1. Rendez-vous sur le site officiel d'IBM Developer pour télécharger Java 8 OpenJ9 : https://developer.ibm.com/languages/java/semeru-runtimes/downloads/?version=8&os=Windows

2. Sélectionnez les options suivantes :
   - Version : IBM Semeru Runtime Open Edition
   - Java : Java 8 (LTS)
   - Operating System : Windows
   - Architecture : x64

3. Prenez la version étiquetée "Latest" et téléchargez le fichier `.msi` de la ligne JRE.
![Image de la page de téléchargement de Java 8 OpenJ9](images/Tuto_Install_Java_Project_Gorgeous_1.png)

4. Exécutez le fichier d'installation `.msi` téléchargé.
![Image du fichier MSI de Java 8 OpenJ9](images/Tuto_Install_Java_Project_Gorgeous_2.png)

5. Suivez les instructions de l'installateur pour installer Java 8 OpenJ9. Notez le chemin d'installation par défaut.
![Image de l'installation de Java 8 OpenJ9](images/Tuto_Install_Java_Project_Gorgeous_3.png)

6. Félicitations, vous avez installé Java 8 OpenJ9. Nous pouvons maintenant passer à l'installation de CurseForge.

### II - Installation de CurseForge
1. Télécharger l'application CurseForge **Standalone** depuis le site officiel : https://www.curseforge.com/download/app
![Image de la page de téléchargement de CurseForge](images/Tuto_Install_CurseForge_Project_Gorgeous_1.png)

> ℹ️ **Note :** Téléchargez bien la version **Standalone** de CurseForge, et non la version Overwolf.

2. Exécutez le fichier d'installation `.exe` téléchargé.
![Image du fichier EXE de CurseForge](images/Tuto_Install_CurseForge_Project_Gorgeous_2.png)

3. Suivez les instructions de l'installateur pour installer CurseForge. Au moment où il faut choisir ses options de confidentialité, vous pouvez cliquer sur "Manage" et tout désactiver.
![Image de l'installation de CurseForge](images/Tuto_Install_CurseForge_Project_Gorgeous_3.png)

4. Félicitations, CurseForge est maintenant installé. Nous allons maintenant passer à la configuration de CurseForge.

### III - Configuration de CurseForge

> ⚠️ **ATTENTION :** Il est important de suivre ces étapes à la lettre pour que le modpack Project Gorgeous fonctionne correctement et de façon optimale.

1. Lancez CurseForge. Si vous n'avez pas de compte, vous pouvez très bien utiliser l'application sans vous connecter en cliquant sur "Continue as guest".
![Image du premier démarrage de l'application CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_1.png)

2. Sélectionnez le jeu Minecraft dans la liste des jeux disponibles.
![Image de la sélection du jeu Minecraft dans CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_2.png)

3. Sélectionnez l'option d'installation standard. L'installation s'effectuera dans le dossier `C:\Users\<votre nom>\CurseForge\Minecraft`.
![Image de l'installation Minecraft standard de CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_3.png)
> ℹ️ **Note :** Si vous souhaitez utiliser l'option d'installation avancée pour choisir l'emplacement du dossier d'installation de Minecraft, vous pouvez le faire. Cependant, notez qu'**il est recommandé de mettre ce dossier sur un SSD**.

4. Rendez-vous maintenant dans les paramètres de l'application CurseForge. Pour cela, cliquez sur l'icône d'engrenage en bas à gauche.
![Image de l'icône des paramètres de CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_4.png)

5. *Optionnel :* Dans l'onglet "Privacy" des paramètres, vous pouvez désactiver les options suivantes.
![Image des options de confidentialité de CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_5.png)

6. Dans l'onglet "Minecraft", dans la partie "Game Resolution", assurez-vous que la résolution du jeu est configurée à votre guise. Vous pouvez aussi utiliser la résolution de votre écran par défaut.
![Image de la configuration de la résolution de Minecraft](images/Tuto_Config_CurseForge_Project_Gorgeous_6.png)

7. Toujours dans l'onglet "Minecraft", modifiez la quantité de RAM allouée à Minecraft. Pour cela, dans la partie intitulée "Allocated Memory", déplacez le slider de RAM à la quantité que vous souhaitez allouer (1 Go = 1024 Mo).
![Image de la configuration de la RAM allouée à Minecraft](images/Tuto_Config_CurseForge_Project_Gorgeous_7.png)
> ℹ️ **Note :** Ce paramètre est global et affectera toutes vos instances Minecraft sur CurseForge.

> ⚠️ **ATTENTION :** Project Gorgeous nécessite **au minimum 12 Go** (= 12288 Mo) de RAM pour fonctionner correctement ! Il est recommandé d'allouer **14 Go** (= 14336 Mo) de RAM pour une expérience optimale.

8. Toujours dans l'onglet "Minecraft", nous allons maintenant modifier la version de Java utilisée par Minecraft. Pour cela, dans la partie intitulée "Java Versions", cliquez sur le bouton "Choose" dans la ligne "Java 8".
![Image de la configuration de Java dans CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_8.png)

9. Dans la fenêtre qui s'ouvre, naviguez jusqu'au dossier d'installation de Java 8 OpenJ9 et dans le dossier `bin`. Par défaut, le chemin d'accès est le suivant : `C:\Program Files\Semeru\jre-8.0.<numéro de version>-openj9\bin`.
![Image de la sélection de Java 8 OpenJ9 dans CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_9.png)

10. Sélectionnez le fichier `javaw.exe` et cliquez sur "Open".
> ⚠️ **ATTENTION :** Il est important de sélectionner le fichier `javaw.exe` avec un **W**, et non `java.exe`.

11. Vous devriez maintenant voir le chemin d'accès à Java 8 OpenJ9 dans la ligne "Java 8" sur CurseForge.
![Image de la configuration de Java 8 OpenJ9 dans CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_10.png)

12. Dernière étape, dans la partie intitulée "Additional Arguments", copiez le code suivant afin d'optimiser l'utilisation de la RAM.
```
-Xmx12G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
```
![Image de la configuration des arguments Java supplémentaires dans CurseForge](images/Tuto_Config_CurseForge_Project_Gorgeous_11.png)
> ⚠️ **ATTENTION :** N'oubliez pas de modifier la première partie de texte `-Xmx12G` pour correspondre à la quantité de RAM que vous avez allouée à Minecraft dans le slider précédemment. Par exemple, si vous avez alloué 14 Go de RAM, vous devrez modifier le texte en `-Xmx14G`.

13. Félicitations, vous avez configuré CurseForge pour lancer Project Gorgeous dans les meilleures conditions !

## Procédure d'installation du modpack

### I - Installation de Project Gorgeous

1. Naviguez dans l'onglet "Minecraft" de CurseForge.

2. Dans la barre de recherche "Search for Minecraft projects..." de CurseForge, recherchez "Project Gorgeous" et cliquez sur le modpack correspondant.

3. Cliquez sur le bouton "Install" pour télécharger et installer le modpack.

### II - Installation d'OptiFine

> ℹ️ **Note :** OptiFine est un mod qui permet d'optimiser les performances de Minecraft et n'est pas inclus de base avec le modpack (pour des raisons de licence). Cependant, il est très fortement recommandé de l'installer pour une meilleure expérience de jeu.

1. Rendez-vous sur le site officiel d'OptiFine : https://optifine.net/downloads

2. Cliquez sur le texte "Show all versions" pour afficher toutes les versions disponibles.

3. Défilez jusqu'à arriver à la catégorie "Minecraft 1.12.2" et cliquez sur le texte "Preview Versions".

4. Téléchargez la version `OptiFine HD U G6 pre1` en cliquant sur le texte de téléchargement (Mirror).
![Image de la page de téléchargement d'OptiFine](images/Tuto_Install_OptiFine_Project_Gorgeous_1.png)
> ℹ️ **Note :** Le modpack a été testé et approuvé uniquement sur la version `OptiFine HD U G6 pre1`.

5. Une fois le fichier `.jar` téléchargé, allez dans la liste de vos modpacks Minecraft sur CurseForge.

6. Sur le modpack Project Gorgeous, faites un clic droit sur le logo, puis cliquez sur l'option "Open Folder" pour ouvrir le dossier d'installation du modpack.
![Image de l'ouverture du dossier d'installation de Project Gorgeous](images/Tuto_Install_OptiFine_Project_Gorgeous_2.png)

7. Glissez le fichier `OptiFine_1.12.2_HD_U_G6_pre1.jar` téléchargé dans le dossier "mods" du modpack Project Gorgeous.
![Image de l'installation d'OptiFine dans Project Gorgeous](images/Tuto_Install_OptiFine_Project_Gorgeous_3.png)

8. Félicitations, vous avez installé OptiFine sur le modpack !

## Lancement de Project Gorgeous

Une fois toutes ces étapes réalisées, vous êtes fin prêt à lancer Project Gorgeous !

Pour cela, retournez dans la liste de vos modpacks Minecraft sur CurseForge, et cliquez sur le bouton "Play" du modpack Project Gorgeous.

Je n'ai plus qu'à vous souhaiter une excellente aventure sur Project Gorgeous ! Amusez-vous bien ! 🌟
