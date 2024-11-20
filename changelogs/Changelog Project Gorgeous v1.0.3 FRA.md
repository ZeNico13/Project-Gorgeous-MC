### Project Gorgeous v1.0.3 Changelog (648 mods)

🟩 **Ajouts**
+ Extended Bone Meal
+ Nothirium
+ RenderLib

⬆️ **Mises à jour**
+ MixinBooter (*9.4* => **10.2**)
+ FermiumASM (*5.23* => **5.24**)
+ Forestry (*5.8.2.422* => **5.8.2.424**)
+ Had Enough Items (*4.26.0* => **4.26.2**)
+ JAOPCA (*2.3.11.27* => **2.3.12.29**)
+ Corail Tombstone (*4.7.0* => **4.7.3**)
+ Simple Voice Chat (*2.5.24* => **2.5.26**)

🟥 **Suppressions**
- Caliper
- JEI Hider
- Nether Portal Spread

⚙ **Configs**
+ Aqua Acrobatics : Désactivation du Crawling car la gestion des hitbox est bugée
+ Aqua Acrobatics : La barre d'air se remplit désormais lentement au lieu d'instantanément (même comportement que la 1.13+)
+ Cavern : Diminution du multiplicateur de spawn de mobs pour toutes les cavernes (à 50)
+ Creeper Confetti : Augmentation de la chance d'obtenir un Creeper Confetti (de 20% à 25%)
+ Custom Main Menu : Ajout d'un lien vers le GitHub du modpack lors d'un clic sur le numéro de version en haut à droite pour pouvoir voir les Changelogs
+ DimensionalDoors : Diminution de la taille maximale que peuvent avoir les Rifts (de 3 blocs à 2 blocs de rayon)
+ InGame Info XML : Suppression du mot "time" dans l'affichage de l'heure pour gagner un peu de place
+ Living Enchantment : Activation de l'affichage des dialogues pour les objets ayant l'enchantement "Living" (cooldown minimum de 25 secondes entre 2 messages)
+ FermiumASM : Désactivation de la nouvelle fonctionnalité Object2ObjectOpenHashMap qui amène une sur-utilisation de RAM
+ Matter Overdrive : Augmentation de l'apparition des anomalies gravitationnelles (de 0,005 à 0,006 par chunk)
+ Nyx : Augmentation de la probabilité d'avoir une lune de sang (de 15% à 20% de chance lors d'une pleine lune)
+ Nyx : Augmentation du multiplicateur de spawn de mobs lors d'une lune de sang (de 2 à 20)
+ Nyx : Diminution de la probabilité d'apparition des étoiles filantes (de 1% à 0,5% par joueur par seconde)
+ Nyx : Augmentation de la probabilité d'avoir une lune des récoltes (de 5% à 15% de chance lors d'une pleine lune)
+ Nyx : Désactivation complète des météores
+ Railcraft : Activation des recettes "Vanilla" pour les rails
+ Simple Voice Chat : Modification du port par défaut pour le serveur vocal. Le port utilisé est désormais le même que celui du serveur Minecraft.
+ JourneyMap : Diminution de la taille de la mini-carte (de 30% à 28%)
+ Trinkets and Baubles : Ajustement de l'emplacement de la barre de mana pour correspondre à la diminution de taille de la mini-carte de JourneyMap

ℹ️ **Infos**
- Cette mise à jour se concentre sur des améliorations QoL, de l'optimisation et des ajustements du modpack.
- Le temps de chargement du modpack a été considérablement réduit suite à la suppression de JEI Hider ! Vous verrez une **réduction d'environ 45% du temps de lancement**.
- La quantité de RAM utilisée par le modpack a été réduit, notamment suite à la suppression du mod de debug Caliper ! Vous verrez une **réduction d'environ 1,2 Go de RAM utilisée**.
- Suite à des tests, Nothirium a été ajouté au modpack pour remplacer OptiFine **si vous jouez sur Linux**. Si vous jouez sur Windows, cet ajout n'a pas d'impact et il est toujours fortement recommandé d'installer OptiFine !
- Nether Portal Spread a été supprimé en raison de son impact négatif sur les performances serveur.
- Les météores de Nyx ont été désactivés car difficiles à contrôler en jeu, destructeurs, et beaucoup trop fréquents. De plus, les météores s'accumulaient massivement dans les chunks non chargés, provoquant une pluie incessante de météores lorsque les joueurs se rendaient dans ces chunks.
- Pour Simple Voice Chat, le port par défaut a été modifié afin de faciliter l'installation et la configuration du serveur du modpack. Néanmoins, si vous le pouvez, il est recommandé de modifier le port qu'utilise Simple Voice Chat (dans le fichier `voicechat-server.properties` du dossier `config/voicechat`) pour un autre que celui utilisé pour le serveur Minecraft.
- La prochaine mise à jour majeure du modpack se concentrera sur l'ajout des quêtes au modpack.
