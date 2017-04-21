   brosses, tampons...

  Comment cr�er des brosses, des tampons, des polices et des images "starter"?

   Si vous voulez ajouter ou changer des choses telles que les brosses et les
   tampons utilis�s par Tux Paint,  vous pouvez le faire simplement en
   ajoutant ou en enlevant des fichiers sur votre disque dur.

   NB : vous devrez red�marrer Tux Paint pour que les changements prennent
   effet.

    1. Les r�pertoires o� Tux Paint range les diff�rents �l�ments
    2. Comment cr�er des brosses?
    3. Comment cr�er des tampons?
    4. Comment cr�er des Images "starter"?
    5. Comment ajouter des polices?
    6. Importer des images pour les ouvrir dans Tux Paint.

1. Les r�pertoire o� Tux Paint range les diff�rents �l�ments.

  Les fichiers standards

   Tux Paint regarde dans ses r�pertoires de donn�es pour trouver ses
   fichiers de configuration.

    Linux et Unix

   O� ces r�pertoires sont install�s d�pend de la valeur d�finie pour
   "DATA_PREFIX" quand Tux Paint est construite. Pour plus de d�tail voir
   INSTALL.txt.

   Par d�faut le r�pertoire est :
    /usr/local/share/tuxpaint/

   Si vous l'avez install� � partir d'un package il est plus s�rement :
    /usr/share/tuxpaint/

    Mac OS X

   Tux Paint range ces fichiers dans le r�pertoire :
    /Users/Joe/Library/Application Support/tuxpaint/ et non pas dans
    /Users/Joe/Library/preferences/ comme indiqu� dans le texte en anglais.
   Attention aux fichiers cach�s (par exemple  /Users/Joe/Library/Application
   Support/tuxpaint/saved/.thumbnail/ )

     Windows

   Tux Paint regarde dans un r�pertoire nomm� 'data' situ� dans le m�me
   r�pertoire que le programme ex�cutable. Ces le r�pertoire qui est cr��
   lors de l'installation :
    C:\Program Files\TuxPaint\data

  Fichiers personnels

   Vous pouvez aussi cr�er des brosses, des tampons, des polices et des
   images 'starter' dans votre propre r�pertoire o� Tux Paint les trouvera.

    Linux et Unix

   Votre r�pertoire Tux Paint personnel est  "~/.tuxpaint/".

   C'est � dire que si votre r�pertoire home est "/home/karl", alors votre
   r�pertoire Tux Paint est "/home/karl/.tuxpaint/".

   Ne pas oublier le point (".") avant 'tuxpaint'!

    Mac OS X

   Dans la version anglaise rien est dit concernant Mac OS X. J'ai d'abord
   cru qu'il fallait faire comme pour linux, apr�s tout OS X est un syst�me
   UNIX; mais ce n'est pas le cas. En fait on peut cr�er les dossiers
   brushes, stamps, fonts et starters dans le dossier
    /Users/Joe/Library/Application Support/tuxpaint/ et cela fonctionne.

    Windows

   Votre r�pertoire Tux Paint personnel se nomme "userdata" et il est dans le
   m�me r�pertoire que l'ex�cutable :
    C:\Program Files\TuxPaint\userdata

       haut  RetourAcceuil

2. Comment cr�er des brosses?

   Pour cr�er des brosses : il faut d'abord cr�er un dossier brushes, s'il
   n'existe pas, dans votre r�pertoire personnel de Tux Paint.
   Les brosses utilis�es pour l'outil dessin et l'outil ligne dans Tux Paint
   sont de simple images PNG en niveau de gris.
   La couche alpha (transparence) de l'image PNG est utilis�e pour d�terminer
   la forme de la brosse, ce qui signifie que la forme peut-�tre anti-alias�e
   et m�me partiellement transparente. (L'anti-aliasing est une technique qui
   rend les bord d'une figure l�g�rement floue pour qu'on ait pas
   l'impression de voir une forme pixellis�e).
   Les images de brosses ne doivent pas �tre plus grande que 40 pixel par 40.

   Une fois l'image PNG de la brosse cr�e il n'y a plus qu'� la sauvegarder
   dans le dossier brushes.

   NB : Si votre nouvelle brosse appara�t comme un rectangle (ou un carr�)
   plein, c'est parce que vous avez oubli� d'utiliser la transparence! Voir
   la documentation Qu'est qu'un PNG? Et comment en cr�er un? pour plus
   d'informations et de conseils.


       haut  RetourAcceuil

3. Comment cr�er des tampons?

   Ils se rangent dans le r�pertoire stamps, s'il n'existe pas, dans votre
   r�pertoire personnel de Tux Paint.
   On peut cr�er des sous-dossiers dans son dossier stamps (par exemple
   /stamps/vacances/ et /stamps/animaux/ - ceux qui utilisent l'OS du cot�
   obscur remplacent les / par des \.-).

   Un tampon, c'est une image au format PNG qui doit consid�rer les pixels
   blancs comme transparents (en fait c'est l'alpha qui d�termine la
   transparence, c'est � dire que chaque pixel de l'image est plus ou moins
   transparent en fonction de la valeur alpha qui lui est allou�e. Chaque
   point est plus ou moins transparent et laisse donc plus ou moins voir
   l'arri�re plan.)

                                   tete_chien
   Pour des raisons d�monstratives, le blanc appara�t en jaune dans le dessin
                                   ci-dessus.
   exemple 1 : seuls les contours de la t�te sont marqu� dans le dessin et on
                         peut colorier autour et dedans
       exemple 2 : toute la t�te est marqu�e, mais le tour du chien c'est
                                  transparent.
   exemple 3 : la transparence du dessin n'a pas �t� conserv�e le tampon est
                rectangulaire avec une t�te de chien au milieu.
   Comment fait-on une image au format PNG? Personnellement j'utilise un
   logiciel open source de dessin qui s'appelle le GIMP (voir Qu'est qu'un
   PNG? Et comment en cr�er un?) ou photoshop element. D'autres logiciels
   sont capables de cr�er des images png. Le format se choisit au moment de
   l'enregistrement.
   La taille de l'image ne doit pas d�passer 100 pixels sur 100 (d�j� une
   grosse image pour Tux Paint : mais attention �� veut dire que les d�tails
   du dessin peuvent ne pas passer donc prendre un dessin de base assez
   simple)
   Attention de bien enregistrer l'alpha en transparent. et attention dans le
   choix du nom : pas de caract�res sp�ciaux ni accentu�s (Ils sont souvent
   responsables de probl�mes.)

   Consid�rons maintenant que l'image tetechien.png. a �t� cr��e et qu'elle a
   �t� plac�e dans /stamps/animaux/
   On peut faire un texte d'explication qui appara�tra dans le bas de la
   fen�tre de Tux Paint :
   ouvrir un �diteur de texte (par ex Text Edit sur Mac OS X, Kedit sur
   Linux, word pad sur Windows)
   premi�re ligne description en anglais :"en .utf8= head of dog"
   deuxi�me ligne description en fran�ais "fr .utf8= t�te de chien"
   (Si on veut mettre une description en espagnol 3� ligne :" es .utf8=
   cabeza de perro")
   On sauvegarde au format UTF8 (Param�trez Text Edit pour qu'il cr�er de
   nouveaux documents au format simple text et choisir l'encodage UTF8 lors
   de l'enregistrement, sous Windows choisissez Plain text (ou simple texte))
   avec l'extension .txt (tetechien.txt) dans le dossier /stamps/animaux/

   On peut peux aussi associer un son � son image.
   On cr�er un son au format .WAV (AIFF sur Mac OS X dont on modifie
   l'extension .aif ou .aiff en .wav) nomm� tetechien.wav dans le dossier
   /stamps/animaux/. Si ce son est un mot, on peut cr�er toute une suite de
   traduction :
   par exemple

     * dog.wav, "son=dog";
     * dog_fr.wav, "son=chien";
     * dog_es.wav, "son=perro".

   On peut donner des instructions au logiciel pour qu'il g�re d'une certaine
   mani�re le tampon. Pour cela il faut ouvrir un �diteur de texte et taper
   les instructions suivantes :
   colorable = si on �crit cette instruction le logiciel permettra �
   l'utilisateur de choisir la couleur au moment de l'utilisation (comme pour
   les pinceaux)
   tintable = si on �crit cette instruction l'image d'origine sera teint�e
   par la couleur choisie par l'utilisateur; Seules les zones � plus de 25 %
   de saturations seront teint�es.
   On peut si on veut rendre les gris non "teintables" en tapant notintgray.
   noflip = emp�che la possibilit� de retourner le tampon.
   nomirror = emp�che la possibilit� de mettre l'image du tampon en miroir.
   On sauvegardes en UTF8 mais avec l'extension .dat (tetechien.dat) dans le
   dossier /stamps/animaux/
   Un exemple de texte de param�trage pour ma t�te de chien :
       colorable
       noflip

   Enfin on peut cr�er une image miroir pr�-enregistr�e : par exemple si on a
   un camion de pompiers avec �crit service incendie, si on le laisse se
   mettre en miroir dans le logiciel normalement, on va avoir les mots �crit
   en miroir; on peut alors cr�er l'image miroir avec les mots bien �crits
   que tu nomme image_mirror.png dans le m�me dossier que image.png.

       haut  RetourAcceuil

4. Comment cr�er des images "starter".

   Il faut cr�er un r�pertoire /starters/, s'il n'existe pas, dans votre
   r�pertoire personnel de Tux Paint.
   Les images de d�part ('starter') apparaissent dans le dialogue d'ouverture
   de document, � cot� des images que vous avez cr��s. Elles ont des boutons
   verts au lieu de bleu derri�re.

   Contrairement � vos images sauvegard�es, quand vous s�lectionner et ouvrez
   un 'starter', en r�alit� vous cr�ez une nouvelle image. Au lieu d'�tre
   blanche, cependant, la nouvelle image contient le contenu du 'starter'. De
   plus quand vous �ditez votre nouvelle image, le contenu du 'starter'
   original l'affecte.

  Style livre de coloriage

   Le mode de 'starter' le plus basique ressemble � une image d'un livre �
   colorier. C'est une forme d�limit�e par des lignes � laquelle on peut
   ajouter des d�tails et des couleurs. Dans Tux Paint, quand vous dessinez,
   tapez du texte, utilisez les tampons, les lignes du dessins restent
   au-dessus de ce que vous dessinez. Vous pouvez effacer ce que vous
   rajoutez mais pas les lignes du 'starter'.

   Pour cr�er une telle image, dessinez simplement une forme en ligne dans un
   programme de dessin, rendez le reste transparent (ce qui deviendra blanc
   dans Tux Paint), et sauvegardez au format PNG dans le dossier /starters/.

  Style sc�ne

   A cot� du style livre de coloriage, vous pouvez aussi procurer comme
   'starter', un avant plan et un arri�re plan s�par� de l'image. Le principe
   est le m�me : on ne peut pas l'effacer, lui appliquer les effet magiques.
   On ne peut pas dessiner sur l'avant plan.

   Quand la gomme est appliqu�e � ce type d'image, au lieu de r�v�ler du
   blanc elle r�v�le l'image d'arri�re plan.

   En cr�ant � la fois un avant plan et un arri�re plan, on peut cr�er un
   'starter' simulant un effet de perspective. Imaginez un arri�re plan
   repr�sentant l'oc�an et un avant plan qui repr�sente un r�cif. On peut
   ensuite dessiner ou tamponner des poissons dans l'image : ils appara�tront
   dans l'oc�an mais jamais en avant du r�cif.

   Pour cr�er ce genre de starter, il faut cr�er un avant plan (avec
   transparence alpha) comme d�crit pr�c�demment, et le sauvegarder au format
   PNG dans le dossier /starters/. Ensuite cr�ez une autre image sans
   transparence et la sauvegarder avec le m�me nom mais avec le suffixe
   "-back" ( Par exemple le r�cif du premier plan s'appelle reef.png et
   l'oc�an de l'arri�re plan reef-back.png.)

   Le 'starter' doit avoir la m�me taille de canevas que Tux Paint. Par
   d�faut c'est le mode 640x480, c'est � dire 448x376 pixels. (Si vous
   utilisez le mode 800x600, cela doit �tre 608x496 pixels.)

   Les 'starter' apparaissent avec un  bouton vert au d�but de la liste dans
   le dialogue d'ouverture.

   NB : Les 'starter' ne peuvent pas �tre sauv�s comme tels � partir de Tux
   Paint car charger un starter, c'est vraiment comme cr�er une nouvelle
   image. (Au lieu d'�tre blanche, elle a quelque chose � l'int�rieur. La
   commande 'sauvegarde' ne fait que cr�er une nouvelle image, tout comme si
   la commande 'nouvelle' avait �t� utilis�e.)

   NB : Les 'starter' sont "attach�s" aux images sauvegard�es, via un petit
   fichier texte qui a le m�me nom que le dessin sauvegard�, mais au format
   .dat. Cela permet au premier plan et � l'arri�re plan, s'ils existent, de
   continuer d'affecter le dessin apr�s que Tux Paint ait �t� quitt�, ou
   qu'une autre image ait �t� charg�e ou d�marr�e. (En d'autres mots, si vous
   construisez un dessin � partir d'un 'starter', il sera toujours affect�
   par celui-ci.)

        haut  RetourAcceuil

5. Comment ajouter des polices?

   Il faut l� encore cr�er un dossier fonts, s'il n'existe pas, dans votre
   r�pertoire personnel de Tux Paint.
   Mettre dans ce dossier des polices de format TrueType. (Voir avec un
   gestionnaire de polices pour voir quel type de police on utilise). La
   police sera alors prise en charge dans Tux Paint,  avec 4 tailles
   diff�rente propos�es.

       haut  RetourAcceuil

6. Importer des images pour les ouvrir dans Tux Paint.

   Comme le dialogue d'ouverture de Tux Paint ne nous montre que les dessins
   cr��s par lui-m�me, comment faire si vous voulez charger une autre image
   ou photographie dans Tux Paint pour l'�diter?

   Pour faire cela, vous devez convertir l'image en PNG ( voir Qu'est qu'un
   PNG? Et comment en cr�er un? ), et la placer dans le r�pertoire saved de
   Tux Paint (~/.tuxpaint/saved/ sous linux et UNIX, userdata\saved\ sous
   windows ~/Library/Application Support/tuxpaint/saved/ sous Mac OS X -et
   pas dans preferences comme indiqu� dans la version anglaise-) Il faut
   aussi pr�voir une ic�ne pour appara�tre dans le menu ouverture qui sera
   dans le r�pertoire  ~/.tuxpaint/saved/.thumb sous linux et
   UNIX, ~/Library/Application Support/tuxpaint/saved/.thumb sous Mac OS X,
   et je ne sais pas pour windows peut-�tre userdata\saved\thumb tout
   simplement.

  Utiliser 'tuxpaint-import'

   Les utilisateurs de Linux et d'UNIX peuvent utiliser le 'tuxpaint-import',
   un script shell qui s'installe quand vous installez Tux Paint. Il utilise
   quelques outils NetPBM pour convertir l'image  ("anytopnm"),  pour la
   retailler afin qu'elle entre dans le canevas de Tux Paint  ("pnmscale"),
   et la convertie en PNG  ("pnmtopng"). Il cr�e en m�me temps une ic�ne pour
   afficher dans le menu ouverture.

   Il utilise aussi la commande date pour renommer l'image avec les
   conventions de Tux Paint qui nomme ses fichiers images sauvegard�s en
   fonction de la date, de l'heure... (Souvenez-vous que vous ne demandez
   jamais un nom de fichier pour ouvrir ou sauvegarder une image!)

   Pour utiliser 'tuxpaint-import', lancez la commande � partir d'un shell et
   donnez lui le nom du fichier que vous voulez convertir.

   Il sera alors convertit et plac� dans votre r�pertoire saved. (NB : Si
   vous fa�tes cela pour un utilisateur diff�rent - par exemple votre enfant,
   il faut ex�cuter la commande dans sa session.)

   Exemple:
    $ tuxpaint-import grandma.jpg
    grandma.jpg -> /home/username/.tuxpaint/saved/20020921123456.png
    jpegtopnm: WRITING A PPM FILE

   La premi�re ligne ("tuxpaint-import grandma.jpg") est la commande �
   lancer. Les deux lignes suivantes sont les sorties ('output') pendant que
   le script s'ex�cute.

   Apr�s le red�marrage de Tux Paint, l'image est alors disponible dans le
   dialogue d'ouverture. Il ne reste plus qu'� cliquer dessus l'ic�ne.

   Pour les utilisateurs de Mac OS X contrairement � ce qui est dit dans la
   version anglaise, on peut aussi utiliser un script shell. Peut-�tre le
   script Tuxpaint-import est adaptable � Mac OS X, mais personnellement j'en
   ai r�cris un autre.
   Pr� requis : il faut installer les outils NetPBM (� l'aide de fink et
   finkcommander par exemple) et il faut cr�er un r�pertoire ~/.tmp

   Voici donc le script que j'ai �crit

   #!/bin/bash

   # creation d'une variable date
     DATE=`date '+%Y%m%d%H%M%S'`

   # creation d'une variable de travail
     FICHIER_IMAGE=$1

   #creation et d�placement dans un fichier de travail
     cp $FICHIER_IMAGE $HOME/.tmp/

   #creation d'une image pour Thumbnail
     cp $HOME/.tmp/$FICHIER_IMAGE $HOME/.tmp/$FICHIER_IMAGE-t

   #creation de l'image au format png qui sera chargeable dans tux paint
     anytopnm $HOME/.tmp/$FICHIER_IMAGE | pnmscale --xysize 448 376 |
   pnmtopng  > $HOME/.tmp/$FICHIER_IMAGE.png

   # renommer en utilisant la variable date l'image png car le fichier doit
   # avoir le format suivant yyyymmddhhmmss.png
     mv $HOME/.tmp/$FICHIER_IMAGE.png $HOME/.tmp/$DATE.png

   #creation de l'image du dialogue d'ouverture
     anytopnm $HOME/.tmp/$FICHIER_IMAGE-t | pnmscale --xysize 92 56 |
   pnmtopng > $HOME/.tmp/$FICHIER_IMAGE-t.png

   # renommer en utilisant la variable date l'image png car le fichier doit
   # avoir le format suivant yyyymmddhhmmss-t.png
     mv $HOME/.tmp/$FICHIER_IMAGE-t.png $HOME/.tmp/$DATE-t.png

   # faire le menage
     rm $HOME/.tmp/$FICHIER_IMAGE


     rm $HOME/.tmp/$FICHIER_IMAGE-t

     mv $HOME/.tmp/$DATE.png $HOME/Library/Application\
   support/TuxPaint/saved/
     mv $HOME/.tmp/$DATE-t.png $HOME/Library/Application\
   support/TuxPaint/saved/.thumb

   exit 0
   Ce script s'utilise comme 'tuxpaint -import'

  Le faire Manuellement

   Les utilisateurs de Windows et de BeOS doivent actuellement faire la
   conversion manuellement.

   Lancez un programme qui est capable d'ouvrir votre image et de la
   convertir au format PNG. (Voir Qu'est qu'un PNG? Et comment en cr�er un?
   Pour avoir quelques suggestions concernant les programmes capables de
   faire cela.)

   Ouvrez l'image et r�duisez sa taille � une taille inf�rieure ou �gale �
   448X376 pixels.

   Sauvegardez l'image au format PNG. Il est fortement recommand� de nommer
   le fichier en utilisant la date et l'heure courante, puisque par
   convention Tux Paint utilise :
   AAAAMMJJhhmmss.png
        o     AAAA = Ann�e
        o      MM = Mois (01-12)
        o      JJ = Jour (01-31)
        o      HH = Heure, au format 24h (00-23)
        o      mm = Minute (00-59)
        o      ss = Second (00-59)

    i.e. :
   20020921130500 - pour le 21 Septembre 2002 13h05m00

   Sauvegardez le PNG dans le dossier 'saved' de Tux Paint. (Voir plus haut)

       haut  RetourAcceuil
