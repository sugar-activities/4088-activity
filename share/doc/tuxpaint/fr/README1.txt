   Tux Paint
   Traduit septembre 2005 de
   version 0.9.14
   Un programme simple de dessin pour enfants
   Copyright 2004 par Bill Kendrick
   New Breed Software

   bill@newbreedsoftware.com
   http://www.newbreedsoftware.com/tuxpaint/
   14 juin 2002 - 24 septembre 2004
       # A propos #
   A/ Qu'est-ce que Tux Paint?
   B/ Licence.
   C/ Objectifs
       1 Facile et dr�le.
       2 Extensibilit�.
       3 Portabilit�
       4 Simplicit�.
       # Utiliser Tux Paint #
   A/ d�marrer Tux Paint.
       1 utilisateurs de Linux/Unix.
       2 Utilisateurs de Windows.
       3 Utilisateurs de Mac OS X.
   B/ Ecran de d�marrage
   C/ Ecran principal
   D/ Outils disponibles.
       1 Outils de dessin.
           1-1 Peindre (Brosses) [Paint] :
           1-2 Tampon [stamp] :
           1-3 Lignes [Lines] :
           1-4 Formes [Shapes] :
               1-4-1 Mode Normal
               1-4-2 Mode Forme Simple
           1-5 Texte [Text] :
           1-6 Magique (effets sp�ciaux) [Magic (Special Effects)] :
               1-6-1 Arc en ciel [Rainbow]
               1-6-2 Etincelles [Sparkles]
               1-6-3 Miroir [mirror]
               1-6-4 Renverser [Flip]
               1-6-5 Brouiller [Blur]
               1-6-6 Blocs [Blocks]
               1-6-7 N�gatif [Negative]
               1-6-8 Affadir [Fade]
               1-6-9 Craie [Chalk]
               1-6-10 Gouttes [Drip]
               1-6-11 Epaissir [Thick]
               1-6-12 Amincir [Thin]
               1-6-13 Remplir [Fill]
           1-7 Gomme [Eraser] :
       2 Autres outils
           2-1 D�faire [Undo] :
           2-2 Refaire [Redo] :
           2-3 Nouveau [New] :
           2-4 Ouvrir [Open] :
           2-5 Sauvegarder [Save] :
           2-6 Imprimer [Print] :
               2-6-1 D�connecter l'impression
               2-6-2 Restreindre l'impression
               2-6-3 la commande d'impression
               2-6-4 R�glage de l'imprimante
           2-7 Quitter [Quit] :

# A propos #

  A/ Qu'est-ce que Tux Paint?

   Tux Paint est un programme de dessin libre destin� aux jeunes enfants de 3
   ans et plus. Il est simple, avec une interface facile � utiliser, avec des
   effets sonores rigolos, et une mascotte motivante qui aide te guide les
   enfants lorsqu'ils utilisent le programme. Il fournit un canevas blanc et
   une vari�t�s d'outils de dessin pour aider les enfants � �tre cr�atifs.

  B/ Licence.

   Tux Paint est un projet open source, et un logiciel gratuit livr� sous la
   licence publique g�n�rale GNU (GPL). Il est gratuit, et le code source
   derri�re le programme est disponible. (Cela permet aux autres d'ajouter
   des caract�ristiques, de r�parer des bogues et d'utiliser tout ou partie
   du programme pour leur propre logiciels GPL)
   Voir COPYING.txt pour le texte complet sur la licence GPL

  C/ Objectifs

    1 Facile et dr�le.

   Tux Paint se propose d'�tre un programme simple pour les jeunes enfants.
   Il n'a pas l'ambition d'�tre un outil de dessin g�n�ral. Il est fait pour
   �tre amusant et facile � utiliser. Les effets sonores et un personnage
   "cartonnesque" aident l'utilisateur � savoir ce qui a lieu, et participent
   � l'amusement. Il y a aussi une fl�che de souris extra-large de style
   cartoon.

    2 Extensibilit�.

   Tux Paint est extensible. Des brosses et des tampons peuvent �tre ajout�s
   ou enlev�. Par exemple, un professeur peut ajouter une collection de
   formes animales et demander � ses �l�ves de dessiner un �cosyst�me. Chaque
   forme peut avoir un son propre qui est jou� et un texte qui appara�t quand
   l'enfant la s�lectionne.

    3 Portabilit�.

   Tux Paint est d�j� port� sur diverses plateformes informatiques : Windows,
   Macintosh OS X, Linux, etc... L'interface est la m�me quelque soit le
   syst�me d'exploitation. Tux Paint fonctionne parfaitement bien sur de
   vieux syst�mes (tels que les pentium 133), et peut �tre param�tr� pour
   fonctionn� mieux sous des syst�mes plus lents.

    4 Simplicit�.

   Il n'y a pas d'acc�s direct � l'arborescence du syst�me. L'image courante
   est conserv�e lorsque le programme quitte, et r�appara�t lorsqu'il
   red�marre. Sauvegarder des images ne n�cessite pas de cr�er un nom de
   fichier ou d'utiliser le clavier. Ouvrir une image se fait en la
   s�lectionnant dans une collection de vignettes. L'acc�s aux autres
   fichiers de l'ordinateur est restreint.

   haut  RetourAcceuil

# Utiliser Tux Paint #

  A/ d�marrer Tux Paint.

    1 utilisateurs de Linux/Unix.

   Tux Paint doit avoir plac� une ic�ne de lancement dans votre menu KDE ou
   GNOME, dans le sous menu 'Graphique'.
   Vous pouvez aussi taper la commande shell :
   $ tuxpaint
   Si une erreur � lieu elle sera signal�e sur le terminal (stderr).

    2 Utilisateurs de Windows.

   Si vous avez install� Tux Paint sur votre ordinateur en utilisant le 'Tux
   Paint installer', il a d� vous demander si vous vouliez installer le
   raccourcis du menu d�marrage et le raccourcis du bureau. Si vous avez
   accept�, vous pouvez simplement d�marrer Tux Paint � partir de la section
   Tux Paint du menu d�marrage (i.e. sous le menu programmes sur Windows XP),
   ou en double cliquant l'ic�ne "Tux Paint" sur votre bureau.

   Si vous avez install� Tux Paint en utilisant le fichier ZIP, ou si vous
   avez refus� l'installation par l'installateur des raccourcis, vous devez
   double cliquer l'ic�ne "tuxpaint.exe" dans le r�pertoire 'Tux Paint' de
   votre ordinateur.

   Par d�faut, l'installateur 'Tux Paint' va installer le r�pertoire "Tux
   Paint" dans le r�pertoire "C:\Program Files\" � moins que vous ayez
   modifi� cela pendant l'installation.

   Si vous utilisez le fichier ZIP, le r�pertoire Tux Paint sera l� o� vous
   effectuerez la d�compression.

    3 Utilisateurs de Mac OS X.

   Double cliquez sur l'ic�ne Tux Paint apr�s avoir t�l�charg� le .dmg et
   avoir copi� le contenu dans le dossier applications.

  B/ Ecran de d�marrage

   Quand Tux Paint d�marre, un �cran titre/cr�dits appara�t.

                                �cran_demarrage
   Une fois le d�marrage termin�, appuyez sur une touche ou cliquez avec la
   souris pour continuer. (ou apr�s environ 30 seconde l'�cran de d�marrage
   dispara�t automatiquement.)

  C/ Ecran principal

   L'�cran principal est divis� selon les sections suivantes :

   - Cot� Gauche : la barre d'outils.
   La barre d'outils contient les contr�les de dessin et d'�dition.

   - Au milieu : le canevas de dessin.
   La partie la plus large de l'�cran, au centre, c'est le canevas de dessin.
   C'est L� o� on dessine.

   - Cot� droit : le s�lecteur.
   Il d�pend de l'outil s�lectionn� : le s�lecteur montre diff�rentes choses
   telles que les brosses pour dessiner lorsque l'outil dessin est
   s�lectionn�. Quand l'outil tampon est s�lectionn�, la partie droite montre
   les diff�rents tampons disponibles.

   - En bas : les couleurs.
   Une palette de couleurs disponibles se trouve en bas de la fen�tre.

   - Tout en bas : l'aire d'aide.
   Tout en bas de l'�cran, Tux, le pingouin de linux, donne des conseils et
   d'autres informations pendant que vous dessinez.

                                 ecran-travail
   haut      Retour    Accueil

  D/ Outils disponibles.

    1 Outils de dessin.

      1-1 Peindre (Brosses) [Paint] :

   Les brosses de dessin permettent de dessiner � main lev�e, en utilisant
   diff�rentes formes de brosses (choisies dans le s�lecteur) de diff�rentes
   couleurs (choisie dans la palette du bas).

                                     dessin
   Si vous appuyez sur le bouton de la souris et que vous d�placez celle-ci
   en m�me temps, vous dessinez.

   Pendant que vous dessinez, un son est jou�. Plus la brosse est grosse,
   plus le ton est bas.

      1-2 Tampon [stamp] :

   L'outil tampon est comme un tampon en caoutchouc ou alors comme des
   gommettes. Il permet de copier des images pr� dessin�es ou photographiques
   (comme des images de cheval, d'arbre, ou la lune...) dans votre dessin.

   Lorsque vous bougez la souris, une silhouette suit le pointeur, montrant
   o� le tampon va �tre appliqu�.

                                     tampon
   Diff�rents tampons peuvent avoir des effets sonores. Certains tampons
   peuvent �tre color�s ou teint�s.

   Les tampons peuvent �tre r�tr�cis et �tendus, et de nombreux tampon
   peuvent �tre bascul� verticalement et en miroir en utilisant les contr�les
   sur le bas du s�lecteur.

   (NB : Si l'option "--nostampcontrols" est utilis�e, Tux Paint ne permettra
   ni les modifications de taille, ni les basculements. Voir la documentation
   sur les options.)

      1-3 Lignes [Lines] :

   Cet outil vous permet de dessiner des lignes droites en utilisant
   diff�rentes brosses et couleurs, identiques � l'outil peindre.

                                     ligne
   Cliquez avec la souris pour d�terminer le point de d�part. En maintenant
   appuy� et en d�pla�ant la souris vous voyez une �bande �lastique� qui
   montre la ligne qui va �tre dessin�e.

   En l�chant le bouton, la ligne se forme en faisant un �boing�.

      1-4 Formes [Shapes] :

   Cet outil vous permet de dessinez de simple formes g�om�triques remplies
   ou non.

   S�lectionnez une forme dans le s�lecteur � droite (cercle, carr�,
   ovale,...etc).

                               forme choix taille
   Faites un cliqu�-gliss� avec la souris pour placer puis modifier la taille
   de la forme. Certaines formes peuvent changer de proportions (telles que
   les rectangles et les ovales) et d'autres non (telles que les carr�s et
   les cercles.).

   Rel�chez le bouton lorsque vous avez fini de choisir la taille.

        1-4-1 Mode Normal

   Maintenant vous pouvez tourner la souris autour de la forme pour la faire
   tourner.
   Cliquez sur le bouton de nouveau et la forme sera dessin�e.

   forme rotation

        1-4-2 Mode Forme Simple

   Si le mode simple forme est activ� (i.e. avec l'option "--simpleshapes"),
   la forme sera dessin�e sur le canevas d�s que le bouton sera rel�ch�,
   c'est � dire sans l'�tape de rotation.

      1-5 Texte [Text] :

   Choisir une police (� partir des lettres sur la droite) et une couleur
   (dans la palette du bas). Cliquez sur l'�cran et un curseur appara�tra.
   Tapez un texte qui appara�t alors sur l'�cran. (apparemment ne prend pas
   les lettres accentu�es du clavier Mac.)

                                     texte1
   Tapez Enter ou Return et le texte sera dessin� dans l'image et le curseur
   descendra d'une ligne.

                                     texte2
   Cliquez ailleurs dans l'�cran et la ligne courante de texte sera d�plac�e
   l�, o� vous pourrez continuer d'�diter.

      1-6 Magique (effets sp�ciaux) [Magic (Special Effects)] :

   Les outils 'magiques' sont un groupe d'outils sp�ciaux. S�lectionnez un
   des outils magiques dans le s�lecteur de droite, et ensuite appliquez
   l'effet sur l'image en cliquant et glissant la souris.

        1-6-1 Arc en ciel [Rainbow]

   Cet outil est similaire � une brosse de pinceau, mais en bougeant la
   souris, les couleurs de l'arc en ciel se succ�dent.

        1-6-2 Etincelles [Sparkles]

   Cet outil dessine des �tincelles jaunes sur l'image.

        1-6-3 Miroir [mirror]

   Lorsque cet outil est s�lectionn� et que vous cliquez sur l'image,
   celle-ci est invers�e comme dans un miroir.

        1-6-4 Renverser [Flip]

   Similaire au miroir cet outil permet d'inverser l'image par rapport � un
   miroir horizontal.

        1-6-5 Brouiller [Blur]

   Cela estompe l'image l� o� vous cliquez-glissez la souris.

        1-6-6 Blocs [Blocks]

   Cela pixellise l'image l� o� vous cliquez-glissez la souris.

        1-6-7 N�gatif [Negative]

   Cela inverse les couleurs de l'image l� o� vous cliquez-glissez la souris
   (Blanc devient noir et inversement, jaune devient bleu...etc)

        1-6-8 Affadir [Fade]

   cet outil p�lit les couleurs l� o� vous cliquez-glissez la souris.
   (Appliquer l'effet plusieurs fois au m�me endroit peut p�lir la couleur
   jusqu'au blanc.)

                                     magic1

        1-6-9 Craie [Chalk]

   Celui-ci rend des parties de l'image (o� vous bougez la souris) comme
   dessin�es � la craie.

        1-6-10 Gouttes [Drip]

   Celui-ci fait couler votre dessin l� o� vous appliquez votre souris.

        1-6-11 Epaissir [Thick]

   Cela rend les traits de couleur noire plus �pais l� o� vous passez la
   souris.

        1-6-12 Amincir [Thin]

   Similaire de Epaissir, except� que les couleurs sombres s'amincissent (et
   les couleurs claires s'�paississent.).
   Pour voir correctement l'effet de ces deux derniers outils effectuez les
   manipulations suivantes :
   - Cr�ez un trait noir et appliquez lui les deux outils
   - Cr�ez un rectangle blanc dans un surface noire et appliquez lui les deux
   outils.

        1-6-13 Remplir [Fill]

   Cet outil rempli une zone d�limit�e par un trait ferm� avec une couleur.

                                     magic2

      1-7 Gomme [Eraser] :

   Cet outil est similaire � Peindre. Partout o� vous cliquez ou
   cliquez-glissez, le dessin est effac� et devient blanc, ou de la couleur
   de l'arri�re-plan de l'image courante si vous avez choisi une image
   'starter'.

   Diff�rentes tailles de gomme sont disponibles.
   Quand vous d�placez la souris sur l'image, un cadre suit le pointeur,
   montrant quelle partie de l'image sera effac�e.
   Pendant que vous effacez, un son grin�ant de torchon sur du verre est
   �mis.
   haut  RetourAcceuil

    2 Autres outils

      2-1 D�faire [Undo] :

   Cliquer sur cet outil annule la derni�re action de dessin. Vous pouvez
   annuler plus d'une action.
   NB: Vous pouvez aussi taper ctrl-Z sur le clavier pour annuler.

      2-2 Refaire [Redo] :

   Cliquer sur cet outil restaure ce qui a �t� annul� avec le bouton Annuler.
   Tant que vous n'avez pas redessin�, vous pouvez restaurer autant d'action
   annul�es que vous voulez.
   NB: Vous pouvez aussi taper ctrl-R sur le clavier pour restaurer.

      2-3 Nouveau [New] :

   Cliquer sur le bouton Nouveau d�marre un nouveau dessin. Il vous demande
   d'abord si vous voulez vraiment en d�marrer un.
   NB: Vous pouvez aussi taper ctrl-N sur le clavier pour d�marrer un nouveau
   dessin.

      2-4 Ouvrir [Open] :

   Celui-ci vous montre la liste d'images que vous avez sauvegard�es. S'il y
   en a plus qui peuvent appara�tre sur l'�cran, utilisez les fl�ches monter
   et descendre en haut et en bas de la liste pour d�filer dans la liste
   d'images.

                                     ouvrir
   Cliquez sur le bouton vert �ouvrir� en bas � gauche pour charger l'image.
   (Vous pouvez aussi double-cliquer sur l'ic�ne d'une image pour l'ouvrir.)

   Cliquez sur le bouton rouge �Effacer� (la poubelle) en bas � droite de la
   liste pour effacer l'image s�lectionn�e. (Il vous sera demand� de
   confirmer.)

   Ou cliquez sur le bouton bleu �retour� avec une fl�che en bas � droite de
   la liste, pour annuler et retourner au dessin pr�c�dent.

         Images 'Starter'

   En plus des images que vous sauvegardez, Tux Paint fournit des images
   'Starter'. Les ouvrir revient � cr�er une nouvelle image, sauf que cette
   image n'est pas blanche, mais peut �tre comme une feuille de livre de
   coloriage (Un dessin en ligne noir et blanc, que vous pouvez colorer.) ou
   comme une photographie en trois D, o� vous pouvez dessiner des parties en
   arri�re.
   Les images 'Starter' ont un arri�re plan vert dans l'�cran d'ouverture
   (Les images normales ont un arri�re plan bleu.) Quand vous chargez un
   'starter', dessinez dessus puis le sauvegardez, cela cr�er une nouvelle
   image. (Cela n'�crase pas le starter original, ainsi vous pourrez le
   r�utiliser de nouveau plus tard.)
   Si vous choisissez d'ouvrir une image et que l'image courante n'est pas
   enregistr�e, il vous sera demand� si vous voulez la sauvegarder ou non.
   (Voir Sauvegarder ci-dessous)
   NB : Vous pouvez aussi taper [Ctrl]-[O] Sue le clavier pour obtenir le
   dialogue d'ouverture'.
   Pour plus de renseignement sur les images starter voir comment cr�er des
   brosses...

      2-5 Sauvegarder [Save] :

   Cela sauvegarde votre image courante.
   Si vous ne l'avez pas sauvegard�e avant, il va cr�er une nouvelle entr�e
   dans la liste des images sauvegard�es (i.e. Cela va cr�er un nouveau
   fichier.)
   NB : Il ne vous demande rien tel que le nom du fichier; il sauvegarde
   simplement l'image et joue un son de d�clenchement d'appareil photo.
   Si vous avez sauvegard� l'image avant, ou si c'est une image que vous
   venez juste d'ouvrir en utilisant la commande 'ouvrir', il vous sera
   d'abord demand� si vous voulez sauvegarder sur l'ancienne version ou si
   vous voulez cr�er un nouveau fichier.
   (NB: Si les options "--saveover" ou "--saveovernew" sont s�lectionn�es, il
   ne vous sera pas demand� avant de sauvegarder si vous voulez conserv�
   l'ancien fichier (Voir la documentation sur les options pour plus de
   d�tails.)
   NB: Vous pouvez aussi taper [Ctrl]-[S] sur le clavier pour sauvegarder.

      2-6 Imprimer [Print] :

   Cliquez ce bouton et votre image sera imprim�e.

        2-6-1 D�connecter l'impression

   Si l'option "--noprint" a �t� s�lectionn�e (soit avec "noprint=yes" dans
   le fichier de configuration de Tux Paint, soit en utilisant la ligne de
   commande "--noprint") le bouton imprim� est d�connect�. (Voir la
   documentation sur les options)

        2-6-2 Restreindre l'impression

   Si l'option "--printdelay" est utilis�e (soit en utilisant la commande
   "printdelay=SECONDS" dans le fichier de configuration, soit en �crivant
   dans la ligne de commande "--printdelay=SECONDS" ), vous ne pouvez
   imprimer qu'une fois toutes les SECONDS secondes.
   Par exemple, avec "printdelay=60", vous ne pouvez imprimer qu'une fois par
   minute. (Voir la documentation sur les options)

        2-6-3 la commande d'impression

   (Linux et Unix seulement)
   La commande utilis�e par d�faut est un groupe de commande qui converti un
   PNG en fichier postscript qui est envoy� � l'imprimante :
   pngtopnm | pnmtops | lpr

   Cette commande peut �tre chang�e en r�glant la valeur de "printcommand"
   dans le fichier de configuration de Tux Paint. (Voir la documentation sur
   les options )

        2-6-4 r�glage de l'imprimante

   (Windows uniquement)
   Par d�faut, Tux Paint imprime simplement sur l'imprimante par d�faut avec
   les r�glages par d�faut quand vous cliquez sur le bouton 'imprimer'.
   Toutefois si vous maintenez enfonc�e la touche [ALT] du clavier en
   cliquant sur 'imprimer', tant que vous n'�tes pas en mode plein �cran, une
   fen�tre de dialogue d'impression,dans laquelle vous pouvez changer les
   r�glages, appara�t.
   Vous pouvez changer plus d�finitivement la configuration de l'imprimante
   en utilisant l'option "printcfg", soit en utilisant "--printcfg" dans une
   ligne de commande, soit en utilisant "printcfg=yes" Dans le fichier de
   configuration de Tux Paint. ("tuxpaint.cfg").
   Si l'option "printcfg" est utilis�e, les r�glages de l'imprimante seront
   charg�s � partir du fichier "userdata/print.cfg". Tout changement sera
   sauvegard� l� de la m�me fa�on. (Voir la documentation sur les options)

      2-7 Quitter [Quit] :

   Cliquer sur le bouton 'Quitter' ferme la fen�tre Tux Paint, ainsi que
   taper sur la touche escape [esc].
   (NB : le bouton 'Quitter' peut �tre d�connect� (Par exemple avec l'option
   "--noquit" en ligne de commande) mais la touche [esc] fonctionne toujours.
   (Voir la documentation sur les options))
   Il vous sera d'abord demand� si vous voulez vraiment quitter.
   Si vous choisissez de quitter et que vous n'avez pas sauvegard� l'image
   courante, il vous est demand� si vous voulez le faire. Si ce n'est pas une
   nouvelle image, il vous est demand� si vous voulez l'enregistrer par
   dessus l'ancienne version ou si vous voulez cr�er une nouvelle entr�e.
   (Voir la fonction 'Sauvegarder' ci-dessus.)
   NB : Si l'image est sauvegard�e, elle sera recharg�e automatiquement au
   prochain d�marrage de Tux Paint.

   haut  RetourAcceuil
