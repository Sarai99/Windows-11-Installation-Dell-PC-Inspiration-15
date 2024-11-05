# Windows-11-Installation-Dell-PC-Inspiration-15
Comment installer Windows 11 sur un Dell Inspiron 15 à partir d’une clé USB :
1- Télécharger l'image ISO de Windows 11 :
-  Rendez-vous sur le site officiel de Microsoft pour télécharger l'ISO de Windows 11.
2- Créer un support d'installation bootable avec Rufus :
Insérez votre clé USB dans l'ordinateur.
-  Ouvrez Rufus (disponible gratuitement sur le site de Rufus) et sélectionnez l'ISO téléchargé.
-  Dans Périphérique, choisissez votre clé USB.
-  Configurez le Schéma de partition en GPT si votre système est en mode UEFI ou en MBR si en mode Legacy BIOS.
-  Cliquez sur Démarrer pour rendre la clé USB bootable.
3- Entrer dans le BIOS de l'ordinateur :
-  Redémarrez l'ordinateur et appuyez plusieurs fois sur la touche F2 au démarrage pour accéder au BIOS.
- Configurer le mode de stockage :
    - Dans le BIOS, allez dans le menu Storage ou Configuration SATA.
    - Changez le mode en AHCI ou en RAID selon les besoins de votre système, puis enregistrez les modifications (généralement en appuyant sur F10).
    - Modifier l'ordre de démarrage (Boot) :
    - Dans le BIOS, accédez à la section Boot.
    - Assurez-vous que la clé USB est en première position dans l'ordre de démarrage (Boot Order) pour que l'ordinateur démarre à partir de la clé USB.
    - Enregistrez les modifications et quittez le BIOS.
4- Démarrer l’installation de Windows 11 :
- L’ordinateur redémarre et démarre depuis la clé USB. Suivez les instructions à l’écran pour commencer l’installation de Windows 11.
- Sélectionnez les paramètres de langue, de clavier et de région, puis cliquez sur Installer maintenant.
- Entrez la clé de produit (ou choisissez de l’ajouter plus tard) et suivez les étapes pour choisir la partition sur laquelle installer Windows.
- Terminer l'installation de Windows :
    Une fois l’installation terminée, Windows 11 va redémarrer plusieurs fois pour finaliser la configuration.
    Configurez les paramètres de base de Windows, connectez-vous à votre compte Microsoft (facultatif), et finalisez l'installation.

**How to Install Windows 11 on a Dell Inspiron 15 from a USB Flash Drive:**

1- Download the Windows 11 ISO image:
- Go to the official Microsoft website to download the Windows 11 ISO.
- Create a bootable installation media with Rufus:

2- Insert your USB flash drive into the computer.
- Open Rufus (available for free on the Rufus website) and select the downloaded ISO file.
- In the Device section, choose your USB drive.
- Set the Partition scheme to GPT if your system is in UEFI mode, or MBR if in Legacy BIOS mode.
- Click Start to make the USB drive bootable.
  
3- Enter the computer’s BIOS:
- Restart the computer and press F2 several times during startup to enter the BIOS.
- Configure the storage mode:
    - In the BIOS, go to the Storage or SATA Configuration menu.
    - Change the mode to AHCI or RAID depending on your system's requirements, then save the changes (usually by pressing F10).
- Change the boot order:
    - In the BIOS, go to the Boot section.
    - Make sure the USB drive is set as the first boot device (Boot Order) so that the computer boots from the USB drive.
    - Save the changes and exit the BIOS.
4- Start the Windows 11 installation:
- The computer will restart and boot from the USB drive. Follow the on-screen instructions to begin the Windows 11 installation.
- Select your language, keyboard, and region settings, then click Install Now.
- Enter the product key (or choose to enter it later) and follow the steps to select the partition where you want to install Windows.
-Complete the Windows installation:
    Once the installation is complete, Windows 11 will restart several times to finalize the setup.
    Configure the basic settings of Windows, sign in to your Microsoft account (optional), and complete the installation

 

