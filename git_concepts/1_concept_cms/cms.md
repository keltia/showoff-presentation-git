!SLIDE

# Concept 1
## Git est un gestionnaire de contenu 

!SLIDE

# Influence fortement la philosophie générale 

!SLIDE

# Une définition possible :
## "Systême de fichier orienté contenu"

!SLIDE

# Snapshot vs Delta

!SLIDE center

![snapshot](git-53.png)

!SLIDE center

![snapshot](git-54.png)

!SLIDE center

![snapshot](git-55.png)

!SLIDE center

![snapshot](git-56.png)

!SLIDE center

![snapshot](git-57.png)

!SLIDE center

![snapshot](git-58.png)

!SLIDE center

![snapshot](git-59.png)

!SLIDE center

![snapshot](git-60.png)

!SLIDE center

![snapshot](git-61.png)

!SLIDE center

![snapshot](git-62.png)

!SLIDE center

![snapshot](git-63.png)

!SLIDE center

![snapshot](git-64.png)

!SLIDE center

![snapshot](git-65.png)

!SLIDE center

![snapshot](git-66.png)

!SLIDE center

![snapshot](git-67.png)

!SLIDE center

![storey](storey.099.jpg)

!SLIDE center

![storey](storey.100.jpg)

!SLIDE center

![storey](storey.101.jpg)

!SLIDE center

![storey](storey.102.jpg)

!SLIDE center

![storey](storey.104.jpg)

!SLIDE center

![storey](storey.105.jpg)

!SLIDE center

![storey](storey.106.jpg)

!SLIDE center

![storey](storey.107.jpg)

!SLIDE center

![storey](storey.109.jpg)

!SLIDE center

![storey](storey.110.jpg)

!SLIDE center

![storey](storey.112.jpg)

!SLIDE center

![storey](storey.113.jpg)

!SLIDE center

![storey](storey.114.jpg)

!SLIDE center

![storey](storey.115.jpg)

!SLIDE center

![storey](storey.118.jpg)

!SLIDE center

# dans une base clé / valeur ##

!SLIDE

![get_put](get_put.jpg)

!SLIDE center

![key_value](key_value.019.jpg)

!SLIDE center

![key_value](key_value.020.jpg)

!SLIDE center

![key_value](key_value.021.jpg)

!SLIDE center

![key_value](key_value.022.jpg)

!SLIDE center

![key_value](key_value.023.jpg)

!SLIDE center

![key_value](key_value.024.jpg)

!SLIDE center

![key_value](key_value.025.jpg)

!SLIDE center

![key_value](key_value.026.jpg)

!SLIDE center

![key_value](key_value.027.jpg)

!SLIDE center

![key_value](key_value.028.jpg)

!SLIDE center

![key_value](key_value.029.jpg)

!SLIDE center

![key_value](key_value.030.jpg)

!SLIDE

# Identification par clé SHA1
## concept simple et efficace

!SLIDE

## La clé est générée par une fonction de «hashage cryptographique» (SHA1) 
### SHA1(contenu) => signature sur 160 bits


!SLIDE bullets incremental

# Avantages :
* Intégrité
* Unicité (2^160 ou 10^48 possibilités)
* Facilite la comparaison

!SLIDE

# Ce concept est massivement utilisé :
## Tout est identifié par une clé SHA1

!SLIDE center

![object](object1.jpg)

!SLIDE center

![object](object2.jpg)

!SLIDE code

# Rappel du 1er commit de Git

	$ ls
	cache.h  cat-file.c  commit-tree.c
	init-db.c  Makefile read-cache.c 
	README  read-tree.c  show-diff.c 
	update-cache.c  write-tree.c

!SLIDE bullets

# Résumé du concept 1:

* Base de données clé / valeur
* 3 types (commit, tree, blob)
* La clé est une signature SHA1
* Orienté contenu (et non fichier)
