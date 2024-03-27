# 1.) Lancez TightVNC en tant que "System Service"
Si vous avez bien suivi le INSTALL.md, votre serveur sera en "System Service" par défaut, cela signifie qu'il sera possible de vous connecter au serveur, à partir du moment ou celui-ci est allumé. Sinon veuillez suivre les étapes si dessous : 

Ouvrez le menu "Démarrer"

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide1.png?raw=true)

Dans le dossier "TightVNC" cliquez sur "Register TightVNC Service"



Une fois cela fait, au même endroit cliquez sur "Start TightVNC Service"

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide1.png?raw=true)

Celui-ci apparaitra en bas a droite de votre écran comme ci dessous. (En survolant avec votre souris vous constaterez qu'il est spécifié **TightVNC Service -** suivi de l'IP de votre serveur)

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide2.png?raw=true)
# 2.) Configuration du serveur

Faites un clic droit sur l'icône TightVNC et cliquez sur "**Configuration**"

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide6.png?raw=true)

Commençons par repérer les éléments importants que l'on voit sur ce premier onglet :

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide3.png?raw=true)

* La première information importante que l'on peut constater est **Incoming Viewer Connection**, Celle ci contient une option : **"Accept incoming connection"**, c'est cette option qui fera en sorte que votre Serveur TightVNC sera en attente d'une requête sur le port en écoute. On peut modifier à volonté le port d'écoute du serveur via l'option **"Main server port"**. 

* En activant l'option **"Require VNC Authentication"**, vous pouvez attribuer un mot de passe que votre "**TightVNC client**" devra renseigner afin de pouvoir vous connecter au "**Serveur TightVNC**", Pour configurer ce mot de passe il vous suffit de cliquez sur les boutons "**Set**". Il correspond au premier encart dans l'attribution des mots de passe de l'installation

* On retrouve ensuite la Partie "**Miscellaneous**" celle ci regroupe des option diverse :

	* "**Enable file transfert**" qui permet d'activer l'option de transfert de fichier
	* "**Hide Destkop Wallpaper**" qui permet de cacher le fond d'écran de la machine pendant la prise de controle
	* "**Show icon in the notification area**" Permet d'afficher le "**TightVNC SERVICE**"
	* "**Connect to RDP session**" Permet la connection via RemoteDesktop (VNC intégré a Windows)

Sur l'onglet "**Administration**"

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide4.png?raw=true)

* Le "**Control Interface**" permet de configurer le mot de passe qui vous sera demandé a chaque modification que vous appliquerez sur la configuration de votre serveur. Il correspond au deuxième encart dans l'attribution des mots de passe de l'installation. Ce qui ressemble a ceci une fois fait

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide5.png?raw=true)

* Le "Logging" permet de configurer l'emplacement du fichier .log stockant toutes les actions qui ont été effectuées lors de la prise de contrôle
# 3) Le Client TightVNC

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/Userguide7.png?raw=true)

L'utilisation du client est relativement simple, pour vous connecter à votre serveur, il suffit de renseigner dans le "**Remote host:**" l'IP ou le nom de domaine du serveur ainsi que le port (optionnel). Si vous ne renseignez pas le port, par défaut le client envoie la requête sur le port 5900. Si vous souhaitez le renseignez, utilisez le format suivant : ```
```
"Domaine-name::port" or "IPv4::port"
```
Pour que la connection réussisse il faut utiliser le port que vous avez configuré sur le TightVNC Server.

