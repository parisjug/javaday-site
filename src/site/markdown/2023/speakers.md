# Les Orateurs

<!-- MACRO{snippet|debug=false|ignoreDownloadError=false|verbatim=false|file=src/site/resources/fragments/breadcrum.snippet.html} -->

Vous pouvez retrouver la liste complète de nos speakers sur cette page. Vous pouvez [réserver vos places sur cette page](https://www.helloasso.com/associations/bjpc/evenements/paris-jug-s-java-day-2023).

Vous pouvez également vous inscrire par la formation professionnelle, grâce à [OXiane](https://oxiane-institut.com/), notre partenaire formation pour cet événement.

Les détails du parcours pédagogique se trouvent ici : <https://oxiane-institut.com/parcours-pedagogique-javaday-2023/>. Vous pouvez prendre contact avec OXiane à l'adresse suivante : [formation@oxiane.com](mailto:formation@oxiane.com).


<a id="jean-michel">&nbsp;</a>

## En route vers Java 21 par Jean-Michel Doudoux

### Résumé

En attendant la publication de Java 21, la prochaine version diffusée en septembre de cette année, et pour en donner quelques aperçus, cette présentation brosse une revue détaillée des nouveautés qui devraient être proposées dans cette future version LTS de Java, issues des projets Amber, Loom et Panama d'OpenJDK.

### Jean-Michel Doudoux

![Jean-Michel Doudoux](images/speakers/jmdoudoux.jpg)

Passionné par le développement de logiciels et par la veille technologique, je possède une longue expérience, en SSII/ESN et personnelle, dans l'écriture d'applications avec différents langages. Je suis actuellement Senior tech lead pour la société Sciam. Utilisant Java depuis sa version 1.0, j'aime partager ma passion pour cette plateforme et son écosystème notamment en me consacrant, depuis presque vingt années, à la rédaction de deux tutoriels, intitulés "Développons en Java", diffusés sous licence GNU FDL. Ce travail m'a permis d'être nommé Java Champion. Je suis également un des cofondateurs du Lorraine JUG.


<a id="antoine">&nbsp;</a>

## Les nouveautés de Jakarta EE 10 et Microprofile 6.0

### Résumé

La dernière mouture de Jakarta EE est arrivée en fin d'année dernière. Sortie enfin de la migration Java EE vers Jakarta EE, cette nouvelle édition apporte de réelles nouveautés utilisables telles quelles ou dans votre stack préférée comme MicroProfile, Quarkus ou même Spring (!).
Au même moment Microprofile 6.0 est également arrivé dans un repository près de chez vous. Cette nouvelle édition s'appuie directement sur Jakarta EE 10 pour simplifier son socle et proposer de nouvelles fonctionnalités.
Dans cette présentation nous passerons en revues les principales nouveautés de ces 2 stacks majeures. Puis non évoquerons les évolutions présentent et à venir sur les frameworks ou produits qui les implémentent.

### Antoine Sabot-Durand

![Antoine Sabot-Durant](images/speakers/Antoine-Sabot-Durant.jpg)

Antoine est un Java Champion et l'ancien spec lead de Jakarta EE CDI. Il a fait partie de l'équipe de lancement de Quarkus chez Red Hat et à travaillé sur des specs MicroProfile majeures comme Fault Tolerance ou Health Check. Aujourd'hui, Antoine est architecte et expert technique chez SCIAM. Il pilote des projets complexes en utilisant en grande partie les technologies qu'il a contribué à mette au point.


<a id="brian">&nbsp;</a>

## Spring Boot 3, GraalVM et images natives

### Résumé

Comment compiler une application Spring en code natif et profiter d'un temps de démarrage rapide et d'une consommation mémoire réduite ?
Pendant cette session, nous vous présenterons le moteur AOT qui permet aux applications Spring d'adopter la technologie GraalVM Native images.
Comment procéder, quelles sont les limitations, comment participer à la communauté GraalVM ? Nous évoquerons tous ces points en utilisant une application exemple.

### Brian Clozel

![Brian Clozel](images/speakers/Brian-Clozel.jpg)

Brian est membre de l'équipe Spring chez VMware. Il travaille sur le Spring Framework, sur Spring GraphQL et sur Spring Boot.


<a id="lilian">&nbsp;</a>

## CRaC vs GraalVM, pour un démarrage rapide

### Résumé

Dans les cas d'usages modernes (Kubernetes, Serverless), tout le monde sait que le point noir de la JVM est son démarrage.
Depuis quelques années, GraalVM s'impose comme rémède permettant ainsi un démarrage rapide via une compilation native. Cela apporte néanmoins certaines contraintes.
Une nouvelle solution apparait dans le paysage de la JVM. C'est CRaC pour Coordinated Restore at Checkpoint. Regardons ensemble comment cela fonctionne et les avantages.

### Lilian Benoit

![Lilian Benoit](images/speakers/Lilian-Benoit.png)

Lilian est Tech Leader dans une ESN Bordelaise. il est passionné par l'informatique depuis bien plus longtemps. Il aime travailler sur la plateforme Java (Java SE et Jakarta EE), d'autant plus sur sa distribution de prédilection : Debian.
Il adore apprendre et partager ses connaissances. C'est comme cela qui s'est rapproché du BordeauxJUG dont il en est JUG Leader depuis 2016. L'objectif du Bordeaux JUG est de promouvoir Java à travers des soirées/conférences mensuelles autour de la plateforme Java.


<a id="herve">&nbsp;</a>

## Software Supply Chain, SBOM et signature avec Maven

### Résumé

Ghost, Dirty cow, Log4Shell, Heart Bleed ont tous fait frémir nos managers et occupé pas mal de nos nuits d'astreinte. Cela a eu suffisamment d'importance pour que les Etats Unis imposent la livraison d'un SBOM avec nos logiciels pour renforcer la maîtrise de la "Software Supply Chain".
Et les attaques sur cette Supply Chain relancent la nécessité de la signature, qui évidemment ne peut pas se faire à l'ancienne comme au siècle dernier.
Comme souvent, il ne s'agit pas tant de technologie que d'habitude et d'hygiène que l'outillage doit faciliter.
Parcourons ensemble ces questions et comment Maven peut vous faire entrer dans le cercle vertueux.

### Hervé Boutémy

![Hervé Boutémy](images/speakers/Herve-Boutemy.png)

Hervé est Committer Maven depuis 2007, Maven PMC Chair de 2014 à 2016. Il est membre de la Fondation Apache depuis 2011, Apache Community Development, actuel VP Apache Attic.


<a id="remi">&nbsp;</a>

## La programmation concurrente structurée : un scoop sur les scopes

### Résumé

Loom en preview, c'est fini ; les threads virtuels débarquent en tant que fonctionnalité officielle de Java 21, la prochaine LTS. Les performances des API asynchrones sans utiliser de Mono, Flux et autres Multi. Comme d'habitude, dès qu'on a une grosse fonctionnalité en Java, tout le monde regarde de près le code. Là, on se rend compte qu'en fait, l'API des Executor n'est pas si bien que cela, surtout maintenant qu'on a des threads virtuels. Et si on imaginait une nouvelle API synchrone pour faire du calcul asynchrone en utilisant les principes de la programmation concurrente structurée. Dans ce talk, après une rapide explication de ce qu'est un thread virtuel, j'expliquerai quel est le principe d'une API concurrente structurée, l'API prévue en Java 21 et les améliorations prévues pour Java 22. 

### Rémi Forax

![Rémi Forax](images/speakers/Remi-Forax.jpg)

Hervé est Committer Maven depuis 2007, Maven PMC Chair de 2014 à 2016. Il est membre de la Fondation Apache depuis 2011, Apache Community Development, actuel VP Apache Attic.
