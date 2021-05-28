# AlbanPoulet_2_05022021

Brief en résumé : 
Prototype pour l'intégration d'un nouveau design web pour le site d'une entreprise nommée Reservia qui propose un outil de planification de vacances.

Notes :

- Version Mobile : actuellement la version mobile a été construite pour s'afficher au mieux sur les smartphone/iphone avec une width de 375px

- Version Tablette : actuellement la version tablette a été construite pour s'afficher au mieux à partir d'une width de 859px. 

- Version Desktop : cette version s'enclenche à partir d'une résolution d'écran de 1025px de large.

- Version définitive : la version définitive gérera les transitions entre ces différents affichages pour s'adapter à toutes les largeurs d'écran/résolutions et sera réglée pour faire appel aux images dans les bonnes proportions pour chaque type d'écran et d'affichage (ex : orientation de l'écran pour les appareils concernés tels que les mobiles ou les tablettes).

- Eléments laissés à interprétation : / les filtres, la couleur a été choisie parmis la charte pour qu'elle soit visible au premier regard et que l'utilisateur final ait un repère visuel marquant qui lui permet de constater quels filtres sont activés pour sa recherche. 

/ le design tablette est une première proposition qui vise à mettre en avant la section "Les Plus Populaires" avec des cartes de dimensions plus importantes que celles des autres sections et avec des visuels plus généreux en proportion afin d'orienter l'utilisateur et de tenter de capter son attention immédiatetement (l'enjeu majeur dans notre contexte "économie de l'attention"), dès le chargement de la page, vers les hébergements les plus consultés par rapport à son profil. 

En effet, cette section communiquera avec notre base de données RGPD friendly afin d'adapter les informations en fonction du profil et selon différents critères "Datas" habituellement utilisés par le marketing afin d'orienter au mieux l'utilisateur pour optimiser les chances de transformation dans un esprit respectant les "best practices" tels qu'identifiées par les tendances des nombreuses études sur le comportement d'achat des utilisateurs. 

- Notes finales : 
/ Cette codebase étant assez basique, elle nécessitera une refactorisation afin de cadrer avec les pratiques permettant de la rendre plus facilement maintenable et modifiable en respectant une norme de "naming" plus pertinente dans la logique BEM ainsi qu'avec le préprocesseur Sass et ses fonctions avancées afin de répartir le code d'une façon plus pertinente, et notamment de disposer de blocs "basiques" plus faciles à adapter selon les futures tendances en terme d'expérience utilisateur, d'érgonomie ou de design. 

/ Référencement : comme ce n'était pas le cadre du prototype, les balises ne sont pas encore optimisées selon règles du référencement tout comme les photos qui nécessiteront quelques tests afin de trouver le bon équilibre entre qualité et vitesse d'affichage, autre enjeu majeur pour éviter les taux de rebond en cas de pages qui seraient trop lentes à charger. La codebase refactorisé permettra aussi d'optimiser le référencement sur des critères techniques et de vitesse, notamment en éliminant du code "en surplus".


Merci pour votre attention, je reste disponible pour toute suggestion ou amélioration pour la version définitive et vous remercie chaleureusement de m'avoir confié ce projet très enrichissant!
