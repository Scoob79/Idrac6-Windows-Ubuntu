# Idrac6-Windows-Ubuntu
Console virtuel sur Windows 7 et Ubuntu

Bonjour,

Après plusieurs jours à chercher, je peux vous donner deux solutions pour Win 7 et Linux (Ubuntu) :

**Windows 7 :**

rien de plus simple il suffit de passer l'idrac en mode Natif dans les paramétrages et d'installer Java 1.6.0_43 voir 45 puis de lancer 
la console.

**Ubuntu :**

Un peu plus compliqué, il faut installer wine puis firefox sur wine (Attention pas les dernière version tablez plus sur une version 20.0) et pour finir JRE 1.6.0_45. Vous lancez firefox depuis Wine puis vous allez sur l'IDRAC et pour finir vous lancé la console.

`sudo apt install wine32 # installation de wine à ce jour`

**Petit plus :**

Vous ne pouvez pas normalement conserver le fichier viewer.jnpl il faut le re-télécharger à bout d'un certain temps (mesure de sécurité),
mais en le modifiant et en remplacent les balises "user=xxxxx" et "passwd=xxxxx" part par exemple "user=root" et "passwd=calvin", 
vous pouvez conserver le fichier viewer.jnpl autant de temps que vous voulez.

**A savoir : **

Les tests ont été effectués sur un Dell R710 avec une iDrac 6 à jours au 21/01/2019 soit la version 2.90.

Traduction en Anglais Google Translate : 

Hello,

After several days searching, I can give you two solutions for Win 7 and Linux (Ubuntu):

**Windows 7 :**

nothing more simple simply pass the idrac in native mode in the settings and install Java 1.6.0_43 see 45 and then launch the console.

**Ubuntu :**

A little more complicated, it is necessary to install wine then firefox on wine (Attention not the last version table more on a version 
20.0) and to finish JRE 1.6.0_45. You launch firefox from Wine then you go on the IDRAC and finally you launched the console.

`sudo apt install wine32 # wine installation to date`

**Little more :**

You can not normally keep the file viewer.jnpl you have to re-download it after a certain time (security measure), but by modifying it 
and replacing the tags "user = xxxxx" and "passwd = xxxxx" for example, "user = root" and "passwd = calvin", you can keep the viewer.jnpl file as long as you want.

**To know :**

The tests were carried out on a Dell R710 with an iDrac 6 on the 21/01/2019 or version 2.90.
