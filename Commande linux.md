pwd -> permet de savoir où on est dans l’ordinateur donc il nous dit où on se retrouve dans l’arborescence de l’ordinateur.
ls -> liste de ce qu’il y a dans le home donc dans l’ordinateur
man -> voir le manuel d’une fonction (ex : man pwd)
q -> sortir du manuel ou juste sortir d’une fonction
crtl+l -> nettoyer le terminal
cd -> change directory donc pour aller où on veut (ex : cd ~/Bureau/)
cd .. -> revenir en arrière 
tree -> donne l’arborescence de l’ordinateur
[-L -> permet de faire un tri dans l’arborescence
mkdir -> permet de créer un répertoire
touch -> permet de créer un fichier (ex : touch text.txt pour créer un fichier texte)
open -> permet d’ouvrir un fichier
more -> permet d’écrire sur la ligne de commande ce qu’il y a écrit dans un fichier
ll -> équivalent à ls avec l’option liste (r = rend, w = write, e = execute
du – h -> permet de voir combien de stockage prend chaque dossier
> -> permet de rediriger un dossier 
| -> affiche les lignes de mon fichier qui contienne le signe quand il est en début de ligne ( ex : grep « ^> » seq.fasta | wc – l
^ -> cela veut dire en début de ligne donc aller chercher une valeur en début de ligne
$ -> pareil mais à la fin
grep -> permet de chercher quelque chose dans un fichier 
wc -> word count donc compte le nombre de ligne et de caractères 
cp -> permet de copier un fichier
ls -lht -> ranger les fichiers par date de création
ls-lhrt -> pareil mais à l’inverse
echo -> écrire quelque chose dans le terminal
echo $ -> montre le chemin d’accès (ex : echo $HOME pour montrer le chemin d’accès)
mv -> bouger un fichier (ex : mv temps test.txt pour mettre le fichier tesst.txt dans le répertoire temps)
mv temps/test.txt -> mettre le fichier test.txt dans le même répertoire que temps
chmod -> faire en sorte qu’un fichier soit exécutable ( ex : chmod +x pour que le fichier soit exécutable)
rmdir -> supprime définitivement un fichier 
gzip -> permet de zipper un fichier 
wget -> télécharger un fichier d’un serveur sur notre ordinateur
module avail -> affiche la liste de programme installé sur la machine
module search -> chercher le module que l’on veut
module load -> charger un module
srun –pty bash -> aller sur un nœud de login
sbash -> pour les dossier plus gros
./ -> pour utiliser un fichier BASH
Chemin d’accès absolu -> /User/epante/Desktop
Chemin d’accès relatif -> ~Desktop
