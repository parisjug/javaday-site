# Les Orateurs

[L'accueil](index.html) | [Le programme](schedule.html) | **Les orateurs** | [S'enregistrer](register.html) | [L'équipe](the-team.html) | [Le lieu](lieu.md)

Nous sommes en train d'annoncer les speakers présents, un tous les deux jours. L'agenda complet sera publié le 9 Mai prochain. En attendant vous pouvez déjà [réserver vos places à tarif réduit blind bird](https://www.helloasso.com/associations/bjpc/evenements/paris-jug-s-java-day). Ce tarif réduit prendra fin lorsque notre agenda complet sera publié.

Vous pouvez également vous inscrire par la formation professionnelle, grâce à [OXiane](https://www.oxiane.com/), notre partenaire formation pour cet événement.

Les détails du parcours pédagogique se trouvent ici : https://www.oxiane.com/parcours-pedagogique-javaday-2022/. Vous pouvez prendre contact avec OXiane à l'adresse suivante : [formation@oxiane.com](mailto:formation@oxiane.com).


## Java en 2022 : profiter de Java 17 par Jean-Michel Doudoux

### Résumé

Beaucoup d'applications utilisent encore Java 8 mais Java a beaucoup évolué depuis notamment avec la diffusion de deux versions LTS.

L'objectif de cette présentation est de revenir sur certaines de ces nombreuses évolutions de Java, notamment récentes afin d'en profiter dans nos applications. Au-delà des évolutions syntaxiques et dans les API, ce sera aussi l'occasion de justifier la migration vers des versions plus récentes de Java.

### Jean-Michel Doudoux

![Jean-Michel Doudoux](images/speakers/jmdoudoux.jpg)

Passionné par le développement de logiciels et par la veille technologique, je possède une longue expérience, en SSII/ESN et personnelle, dans l'écriture d'applications avec différents langages. Je suis actuellement le CTO d'Oxiane Luxembourg et du groupe Oxiane. Utilisant Java depuis sa version 1.0, j'aime partager ma passion pour cette plateforme et son écosystème notamment en me consacrant, depuis une vingtaine d'années, à la rédaction de deux tutoriels, intitulés "Développons en Java", diffusés sous licence GNU FDL. Ce travail m'a permis d'être nommé Java Champion. Je suis également un des cofondateurs du Lorraine JUG.


## Micronaut AOT pour optimiser vos applications pour le JIT et GraalVM par Cédric Champeau

### Résumé

Micronaut est un framework Java moderne, multi-facettes, permettant de développer aussi bien des applications Java en ligne de commande que des microservices.
Il est conçu pour maximiser la productivité du développeur, sans compromettre les performances.
Dans ce contexte, Micronaut propose depuis le premier jour des optimisations faites à _build time_ plutôt qu'au _run time_.
En particulier, Micronaut n'utilise pas de _reflection_: ceci le rend particulièrement adapté à son utilisation avec GraalVM pour la compilation d'images natives.

### Cédric Champeau

![Cédric Champeau](images/speakers/cedric-champeau_red.jpg)

Cédric Champeau est développeur Java chez Oracle Labs, dans l'équipe Micronaut et GraalVM. Il travaille notamment sur les problématiques d'optimisation de la productivité développeur (aussi bien interne que pour les utilisateurs de Micronaut) et maintient notamment les plugins Gradle et Maven de Micronaut et de GraalVM native-image. Avant celà, Cédric a passé plusieurs années à travailler chez Gradle Inc sur l'outil de build open source Gradle, où il a notamment contribué à de nombreuses améliorations en termes de performance, gestion des dépendances et sécurité. Enfin, Cédric a longtemps été un des contributeurs principaux du langage Groovy, pour lequel il a notamment développé le compilateur statique et des outils d'optimisations à compile time (AST transformations).


## Sécurité en Java 17 : les nouveautés passées et à venir

En plus de plusieurs nouveautés syntaxiques très intéressantes, Java 17 apporte quelques évolutions dans le domaine de la sécurité, que l'on se propose de couvrir dans cette présentation. Notre bon vieux `SecurityManager` est déprécié, et va être retiré. Quelques éléments sont ajoutés en cryptographie. La déserialization voit sa sécurité améliorée avec les `Record` et les filtres de déserialization. Les types scellés sont introduits, qui permettent de contrôler la façon dont on peut étendre une hiérarchie d'interfaces et de classes.

### Charles Sabourdin

![Charles Sabourdin](images/speakers/charles-sabourdin.jpg)

Investi depuis longtemps dans l'informatique, Linuxiens, Javaiste et viscéralement DevOps-ien, Charles Sabourdin est architecte indépendant, Jug Leader du ParisJUG de 2013 à 2020. Il reprend du service en 2022, pour continuer à partager avec la communauté.

Il est régulièrement chargé de problématiques d'architecture, de sécurité et de production. Il travaille sur de nombreux sujets tous ayant un but commun: l'amélioration du processus de delivery et l'expérience utilisateur.

En 2021, il co-ecrit un livre ur la haute-disponibilité (Kubernetes) et se focalise sur les operators kubernetes.



## Remèdes aux oomkill, warm-ups, et lenteurs pour des conteneurs JVM

Mes conteneurs JVM sont en prod, oups ils se font oomkill, oups le démarrage traîne en longueur, oups ils sont lent en permanence. Nous avons vécu ces situations.
Ces problèmes émergent parce qu'un conteneur est par nature un milieu restreint. Sa configuration a un impact sur le process Java cependant ce process a lui aussi des besoins pour fonctionner.
Il y a un espace entre la heap Java et le RSS : c'est la mémoire off-heap et elle se décompose en plusieurs zones. À quoi servent-elles ? Comment les prendre en compte ? La configuration du CPU impacte la JVM sur divers aspects : Quelles sont les influences entre le GC et le CPU ? Que choisir entre la rapidité ou la consommation CPU au démarrage ?
Au cours de cette session nous verrons comment diagnostiquer, comprendre et remédier à ces problèmes.

### Brice Dutheil

![Brice Dutheil](images/speakers/Brice_Dutheil_red.jpg)

Ingénieur logiciel senior Java chez Datadog, Depuis 15 ans j'exploite la JVM en tant que développeur de libraries (notamment en ayant été le 2ème contributeur principal de Mockito), en tant que consommateur de libraries en tant qu'ops (configuration et tuning de JVM sur du Docker, k8s, helm, cpu quota, oomkill, GCs, JFR, async-profiler, pmap). Ayant survécu à l'immobilisme de JEE, je surveille et promeut avec engouement le travail des ingénieurs du JDK (ZGC, Shenendoah, Loom, Panama, Valhalla, CRaC, Leyden...) ainsi que les avancés de l'écosystème Java (GraalVM, etc).

### Jean-Philippe Bempel

![Jean-Philippe Bempel](images/speakers/jean-philippe-bempel.jpg)

Développeur passionné par les performances, les runtimes (JVM, CLR) et adepte de Mechanical Sympathy, Jean-Philippe Bempel a plus de 8 ans d'expérience dans les systèmes de trading low latency. Après avoir optimisé les resources de larges clusters (2000+ noeuds) chez Criteo, Il a intégré l'équipe Profiling de Datadog et contribue à Java Mission Control.




## Valhalla: Vers de nouveaux generics universels et specialisables

Dans le cadre du projet de l'OpenJDK Valhalla, nous allons introduire une nouvelle sorte de classe à Java (nommée "value class") qui permet de manipuler des objets directement sans pointeur.

Ce nouveau type d'objet pose un léger problème technique: ils ne marche pas avec les types paramétrés de Java, les fameux generics, tout comme les types primitifs d'ailleurs, qui sont eux aussi manipulés sans pointeur.

Dans cette présentation, je vous propose de regarder de plus près quels cela pose exactement et comment nous nous proposons de les résoudre dans la machine virtuelle Java.

La cerise sur le gâteau est que si on se débrouille bien, la VM devrait aussi pouvoir supporter les `ArrayList<int>`.

### Rémi Forax

![Rémi Forax](images/speakers/Remi-Forax.jpg)

Java Plombier, Maître de Conférence, Virtual Machine Whisperer, martyrise ses pauvres étudiants, complexifie Java en étant expert pour les JSR 292, 335 et 376, développe des librariries et langage dynamiques open source utilisés ou pas.