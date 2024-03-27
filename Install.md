# 1. Pré-requis

Il faut : 

* La source logicielle
Téléchargement :
Rendez-vous sur ce lien : https://www.tightvnc.com/download.php et cliquez sur **"Installer for Windows (64-bit)"**
![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install1.png?raw=true)

* Une machine de type **serveur** (physique ou virtuelle) :
	* OS : `Windows Serveur 2022`
	* RAM : `8 GB`
	* CPU : `2` 
	* Espace disque libre : `30GB d'espace de stockage`
	* Les pare-feu doivent être désactivés (ou configurés pour les ports concernés)

> Si la machine est une VM, sa carte réseau doit être réglée sur **"Internal Network"**.
 ![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/ConfigVM.png?raw=true)

* Une machine de type **cliente** (physique ou virtuelle) :
	* OS : `Windows 10`
	* RAM : `4 GB`
	* CPU : `2` 
	* Espace disque libre : `30GB d'espace de stockage`
	* Les pare-feu doivent être désactivés (ou configurés pour les ports concernés)

Si la machine est une VM, sa carte réseau doit être réglée sur **"Internal Network"**.

# 2. Installation du serveur TightVNC sur votre machine Serveur

Une fois le téléchargement terminé : lancez l'installateur. 

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install2.png?raw=true)


Cliquez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install3.png?raw=true)

Acceptez les termes de la License (après l'avoir lu) et cliquez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install4.png?raw=true)

Sélectionnez l'option **"Custom"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install5serve.png?raw=true)

Dans un premier temps effectuez un **clic GAUCHE** sur l'**ICONE** de **"TightVNC Viewer"**  
Ensuite selectionnez l'option **"Entire feature will be unavailable"**  
Grâce à cela, nous évitons d'installer le **"Client"** de TighVNC qui nous est inutile sur la machine **Server** pour le projet.

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install6serve.png?raw=true)

Laissez les paramètres par défaut et appuyez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install7serve.png?raw=true)

Cliquez sur le bouton **"Installer"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install8serve.png?raw=true)

* Cette étape est optionnelle mais il est fortement recommandé de saisir des mots de passe pour protéger le serveur **TightVNC**.
Cela empêchera tout client d'essayer de prendre le contrôle du serveur sans en avoir le mot de passe !

* Si vous ratez cette étape, pas de panique vous pourrez les configurer plus tard

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install9serve.png?raw=true)

Félicitations, vous avez terminé l'installation de votre Serveur VNC sur votre Serveur Windows 2022 !

# 3. Installation du client TightVNC sur votre Machine Client

Une fois le téléchargement terminé : lancez l'installeur 

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install2.png?raw=true)

Cliquez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install3.png?raw=true)

Acceptez les termes de la license (après l'avoir lu) et cliquez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install4.png?raw=true)

Sélectionnez l'option **"Custom"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install5client.png?raw=true)

Dans un premier temps effectuez un **clic GAUCHE** sur l'**ICONE** de **"TightVNC Server"**   

Ensuite selectionnez l'option **"Entire feature will be unavailable"**  

Grâce à cela, nous évitons d'installer le "server" de TighVNC qui nous est inutile sur la machine **Client** pour le projet.  

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install6client.png?raw=true)

Laissez les paramètres par défaut et appuie sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install7client.png?raw=true)

Cliquez sur le bouton **"Installer"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install8client.png?raw=true)

Félicitations, vous avez terminé l'installation de votre Client VNC sur votre Windows 10 !

Je vous laisse donc vous rendre dans la partie USER_GUIDE.md pour effectuer les configurations d'usages et lancer votre première prise de contrôle.
