
[comment]: # (This readme file is intended for the Javascript documentation)
[comment]: # (generated by jsdoc)

_La version française est incluse ci-dessous._

**This documentation is generated automatically from comments in source files.**

# General information

While the *World editing dialog* makes it possible to create your own world,
it is limited to create worlds with pre-defined objects.  Furthermore, it
creates static worlds which are then interacted with through a user's program.
A world creator may wish to introduce additional interactivity by changing
the state of the world when a user's program has achieved a partial goal,
like reaching a pre-defined position.  The functions documented here are
intended to give world creators all the flexibility they need to create
their own worlds.

If you find that some additional capability is required, or that the information
provided here is incorrect, please do not hesitate to get in touch with me.


### About the RUR namespace

Since the goal of Reeborg's World is to allow the user (student) to
run their own programs, name clashes have to be avoided between functions
created for Reeborg's World and those created by the student.
The imperfect solution I have chosen is to try, as much as possible, to use
a single global object or namespace,
`RUR`, which can stand for **Reeborg the UsedRobot**, and is also valid
in French as _le **Robot Usagé Reeborg**_, but refers to the first time the
name **robot** was used [see wikipedia:RUR](https://en.wikipedia.org/wiki/R.U.R.).

Please note that there are many more functions belonging to the `RUR` namespace
than what is documented here.  As a rule, you should not create additional
functions belonging to this namespace.

To see the functions defined and belonging to this object, please use the
**Namespaces** selector at the top of this page.

-----

# _Information générale_

Bien que *l'éditeur de monde* vous donne la possibilité de créer vos propres
mondes, il est limité à utiliser les objets pré-définis.  De plus, les mondes
créés sont "statiques" et ne changent normalement que par le biais d'actions
encodées dans les programmes des usagers.  Il est possible que vous désiriez
créer des mondes plus interactifs et dont l'état change lorsqu'une étape
partielle dans la réalisation d'un but a été réalisée, comme, par exemple,
lorsque le robot se trouve à une certaine position. Les fonctions documentées
ici devraient vous donner toute la flexibilité requise pour créer les mondes
désirés.

Si vous croyez que d'autres fontions seraient requises, ou si vous identifiez
des erreurs dans ce document, SVP n'hésitez pas à me contacter.


### _Au sujet de l'utilisation de RUR_

_Puisque le but du Monde de Reeborg est de permettre aux apprenants de créer leur
propres fonctions, j'ai jugé qu'il était essentiel de créer un objet global
("namespace") qui contiendrait les différentes variables et
fonctions requises pour le site.
Le nom que j'ai choisi est `RUR` qu'on peut voir comme un acronyme pour
le **Robot Usagé Reeborg**, ou pour l'équivalent anglais **Reeborg the UsedRobot**
mais qui peut tout aussi bien faire référence à la toute première fois où
le nom **robot** a été utilisé [voir wikipedia:RUR](https://fr.wikipedia.org/wiki/R.U.R.)._

Veuillez noter qu'en plus des fonctions documentées ici,
il en existe plusieurs autres qui appartiennent à l'objet global `RUR`;
vous devriez vous abstenir de ne pas ajouter des fonctions à cet objet global.

Pour voir les fonctions appartenant à cet objet global, veuillez utiliser
le sélecteur **Namespaces** qui se trouve au haut de cette page.
