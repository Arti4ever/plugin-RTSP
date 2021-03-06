# Configuration

### Configuration du plugin

Après téléchargement du plugin, il vous faudra simplement activer le plugin :

image::../images/RTSP_Plugin_Installation.png[]

### Configuration des équipements

La configuration des équipements RTSP est accessible à partir du menu plugin :

image::../images/RTSP_Menu.png[]

Voilà à quoi ressemble la page du plugin RTSP (ici avec déjà 1 équipements) :

image::../images/RTSP_MesFlux.png[]

Comme à beaucoup d'endroits sur Jeedom, placer la souris tout à gauche permet de faire apparaître un menu d'accès rapide (vous pouvez, à partir de votre profil, le laisser toujours visible).

Une fois que vous cliquez sur l'un d'eux, vous obtenez :

image::../images/RTSP_Configuration_Equipement.png[]

Vous retrouvez ici toute la configuration de votre équipement :

* *Nom de l'équipement RTSP* : nom de votre flux RTSP,
* *Objet parent* : indique l'objet parent auquel appartient l'équipement,
* *Catégorie* : les catégories de l'équipement (il peut appartenir à plusieurs catégories),
* *Activer* : permet de rendre votre équipement actif

Vous retrouvez ici le paramètrage du flux RTSP de votre caméra :

* *Adresse IP* : ip de votre flux RTSP
* *Port* : port de votre flux RTSP, par exemple : 554
* *Nom de la caméra* :  nom du service associé à la capture de votre flux RTSP
* *Résolution* : résolution de votre flux RTSP, par exemple : 1280x720
* *Complément url (/chemin)* : url du flux, par exemple : /ch1_0.h264

Vous retrouvez ici les paramètres optionnels du flux RTSP de votre caméra :

* *Délai* : délai entre 2 captures de votre flux RTSP
* *Emplacement des captures* : répertoire de sauvegarde de vos captures /tmp par défaut, il est conseillé de ne pas modifier cette option, sauf si /tmp n'est pas en ram (Voir la section dédiée plus bas)
* *Nom d'utilisateur* : utilisateur pour vous connecter à votre caméra (peut être vide)
* *Mot de passe* : mot de passe pour vous connecter à votre caméra (peut être vide)

Vous retrouvez ici le résultat du fichier à ajouter à votre équipement dans le plugin Camera :

* *URL de capture (pour le plugin camera)* : URL (en lecture seule) à fournir au plugin Camera, par exemple : snapshot_xiaoyi1.jpg :

image::../images/RTSP_Camera.png[]


Vous retrouvez ici la capture réalisée au moment où vous cliquez afin de tester votre configuration :

* *Aperçu de la capture* : Aperçu de la capture réalisée sur ce flux RTSP
* *Rafraîchir* : Action de rafraichissement de la capture de ce flux RTSP
* *Status* : Retour d'état du service RTSP pour ce flux

### Caméras compatibles

Vous avez maintenant une documentation d'assistance sur l'équipement, cette documentation ouverte vous permettra de trouver l'url, le port ainsi que le protocole utilisé par votre caméra :

image::../images/RTSP_Assistant_Camera.png[]

### [NOTE]
Pour le moment Il n'y a aucune commande
