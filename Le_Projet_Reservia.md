

**Le Projet RESERVIA**

**Transformez une maquette en site web**

**Scénario**

Enfin, vous avez trouvé votre premier stage en tant que développeur web chez

Reservia, une petite entreprise proposant un outil de planification de vacances.

Leur site permet aux usagers de trouver des hébergements et des activités dans la ville

de leur choix. Les hébergements peuvent également être filtrés par thématique, par

exemple leur budget ou leur ambiance.

Un nouveau design basé sur les principes du Material Design vient d’être proposé par

Loïc, designer UI.

Avant de valider définitivement ce design, l’entreprise décide de réaliser un prototype. La

première étape consiste à intégrer la maquette responsive en HTML et CSS.

Voici donc la tâche qui vous est attribuée ! Loïc vous envoie un mail pour vous en dire plus,

en mettant en copie votre manager, Sarah, qui est CTO de l’entreprise.

\---------------------------------------------------------------------------------------------------------------

*De : Loïc*

*À : Vous*

*CC : Sarah*

*Objet : Intégration maquette Reservia*

\---------------------------------------------------------------------------------------------------------------

Bonjour ! 

Je t’envoie les nouvelles [maquettes](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[ ](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[desktop](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[ ](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[et](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[ ](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[mobiles](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[ ](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[du](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[ ](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[site](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[ ](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip)[Reservia](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P2+HTML+%26+CSS/Projet+2+-+Reservia+FR.zip). Le dossier

comprend aussi les images. Voici quelques précisions qui te seront utiles pour l’intégration.

**Fonctionnalités**

• Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le champ

de recherche est donc un champ de saisie, dont le texte peut être édité par l’usager. En

revanche, à ce stade, le bouton de recherche ne sera pas fonctionnel.

• Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité. Pour

l’instant les liens seront vides.

• Les filtres ne seront pas fonctionnels pour cette version, en revanche, il faut qu’ils

changent d’apparence au survol. Je te laisse décider de l’effet le plus approprié.





• Dans le menu, les liens “Hébergements” et “Activités” sont des ancres qui doivent mener

aux sections de la page.

**Contraintes techniques**

• Je te fournis deux maquettes : l’une desktop et l’autre mobile. Le site devra également

être adapté aux tablettes. Sur ce support, tu es libre de faire les adaptations nécessaires

avec la mise en page, tant qu’aucun élément n’est coupé et que le texte a une taille

suffisante. Je te laisse choisir les breakpoints appropriés.

• Comme je ne savais pas de quels tailles et formats d’image tu avais besoin, j’ai exporté

les images en différents formats. Je te laisse choisir le format le plus adapté par rapport à

la résolution et au temps de chargement.

• Les icônes proviennent de la bibliothèque [Font](https://fontawesome.com/)[ ](https://fontawesome.com/)[Awesome](https://fontawesome.com/). Les couleurs de la charte sont

le bleu #0065FC, et sa version plus claire #DEEBFF ainsi que le gris pour le fond

#F2F2F2.

• La police du site est [Raleway](https://fonts.google.com/specimen/Raleway).

Si tu as des questions n’hésite pas à m’écrire.

*Bonne journée !*

\--------------------

Vous vous plongez dans ce projet… Et commencez à vous poser quelques questions

techniques sur l’intégration. Heureusement, votre manager rebondit sur l’échange de mails

pour vous apporter des précisions !

\---------------------------------------------------------------------------------------------------------------

D*e : Sarah*

*À : Vous*

*CC : Loïc*

*Objet : RE - Intégration maquette Reservia*

\---------------------------------------------------------------------------------------------------------------

Hello,

J’espère que les premiers éléments partagés par Loïc te semblent clairs ! Comme c’est ton

premier projet avec nous et que tu es en stage, je voulais te guider un peu plus :

• N’utilise pas de framework ou pré-compilateur CSS pour ce projet (comme SASS par

exemple) : comme tu démarres, je préfère que tu montes en compétences sur HTML et

CSS et que tu apprennes à coder from scratch. On aimerait tester tes compétences là-

dessus !

• Je te recommande d'utiliser Visual Studio Code, plusieurs plugins pourront te simplifier la

vie, par exemple Live Server ou Prettier.





• Tu peux intégrer les icônes Font Awesome en HTML ou CSS. Je te conseille fortement

d’utiliser Flexbox mais tu peux aussi utiliser CSS Grid si tu veux.

• Ton code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte

au validateur W3C HTML et CSS.

• Le site devra être compatible avec les dernières versions de Chrome et Firefox.

• Pense à séparer le HTML et le CSS et à organiser ton dossier de rendu.

• N’oublie pas de versionner ton code avec Git, et ce dès les premières lignes de code. C’est

hyper important quand on travaille en équipe. Nous on utilise GitKraken comme client

Git, c'est plus sympa qu'une console, mais tu fais comme tu veux. Ensuite il faut que tu

déploies la page sur GitHub Pages ou GitLab Pages comme tu préfères.

•

À ta disposition pour en discuter !

*Sarah*

\--------------------

**Livrables :**

• Un lien vers votre repository GitHub ou GitLab.

• Vous devez versionner votre code sur GitHub ou GitLab.

• Votre repository doit être accessible.

• Un lien vers votre page web hébergée en ligne sur GitHub Pages ou GitLab Pages,

pour

présenter votre maquette.

Pour faciliter votre passage au jury, déposez sur la plateforme, dans un dossier nommé

“P2\_nom\_prenom”, tous les livrables du projet. Chaque livrable doit être nommé avec

le numéro du projet et selon l'ordre dans lequel il apparaît, par exemple

“P2\_01\_lienGithub”, “P2\_02\_lienpageweb”, et ainsi de suite.

Le repo GitHub doit être nommé avec la convention suivante :

Nomcomplet\_#\_Datedémarrage. Le # correspond au numéro du projet sur le parcours et la

date doit être au format jjmmaaaa. Par exemple, FrancoisLenotre\_3\_05032020.

**Soutenance :**

Durant la présentation orale, votre évaluateur jouera le rôle de Sarah, votre manager :

\1. Présentation des livrables : Vous présenterez votre travail à votre évaluateur en

expliquant vos choix techniques. (10 minutes).

\2. Discussion : votre évaluateur, jouant toujours le rôle de votre manager, va vous

questionner sur la façon dont vous avez intégré les éléments ainsi que sur votre





utilisation de Git et GitHub. Comme vous venez d’arriver dans l’équipe, il est important

que vous vous familiarisiez avec les pratiques de l’équipe ! (15 minutes).

Votre évaluateur questionnera vos choix, soyez donc prêt à défendre votre travail. À la

fin de la session, votre évaluateur reprendra son rôle de mentor pour que vous puissiez

débriefer ensemble.

**Compétences évaluées**

• Utiliser un système de gestion de versions pour le suivi du projet et son

hébergement

• Mettre en place son environnement Front-End

• Intégrer du contenu conformément à une maquette

• Implémenter une interface responsive.

