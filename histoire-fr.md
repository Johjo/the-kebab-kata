Introduction

> Bonjour, nous sommes une startup spécialisées dans les kebabs et nous avons besoin de vous pour créer notre application de gestion de kebab.

> Nous avons travaillé avec une précédente équipe qui nous a coûté très cher et le projet n'a pas abouti. Nous faisons appel à vous parce que vous êtes soucieux de la qualité du code. Nous comptons sur vous pour ne pas créer un enième legacy.

> Pour cela, nous voulons que vous soyez agiles. Vous allez travailler en itération. Nous ne savons pas combien il y aura d'itération. Normal, nous sommes agiles !

> A chaque itération, vous devrez faire une démo de votre travail. Pour cela, vous devrez nous montrer que votre code fonctionne.

> Et après la démo, vous devrez faire une code review d'une autre équipe. Puis cette équipe vous fera à son tour une code review. C'est très important, soyez honnêtes avec les reviewers. Quant au reviewer, essayez d'apporter un feedback positif et constructif.

## Itération 1 (10 minutes)

> Nous avons conservé l'application de l'équipe précédente, vous devrez donc seulement développer un objet Kebab que vous pouvez créer avec les ingrédients que vous souhaitez. C'est vraiment tout simple, cet objet devra avoir une méthode isVegeterian. C'est facile, cette méthode ne prend aucun paramètre et retourne un booléen. Vrai si tous les ingrédients sont végétariens et faux dans le cas inverse.

> C'est parti, on compte sur vous.
> Au fait, vous avez 10 minutes pour réaliser cette story, parce qu'elle est vraiment simple. Mon petit doigt me dit que vous allez d'ailleurs finir avant ce délai. 
### Astuces
- Soyez vague !
- ne leur donnez pas d'emblée votre liste d'ingrédients
- se comporter comme s'il s'agissait d'une évidence
- soyez incohérent !
- lorsqu'ils demandent spécifiquement la liste des ingrédients, continuez à oublier et à vous souvenir des ingrédients
- Dévaloriser leur travail
- Traitez la tâche comme étant insignifiante et les 10 minutes comme étant plus du double du temps dont ils ont besoin pour la réaliser.
- Les interrompre pour leur demander leur avis et revoir leurs estimations à la baisse
- toute personne qui accepte de faire le travail en moins de temps se voit rappeler à la fin de son estimation qu'elle devrait avoir terminé.
- Insistez sur le fait que vous pensez qu'ils ne devraient pas consacrer trop de temps à la qualité et aux tests.

## Itération 2 (7 minutes)

> On a l'impression que certains d'entre vous n'ont pas fini et ne sont pas satisfaits de ce qu'ils ont produit. Aucun souci, on s'est battu pour vous et on a demandé une rallonge de budget pour que vous puissiez nettoyer votre code.

> Du coup, vous avez 7 minutes supplémentaires pour finir l'itération précédente. Vous en profiterez pour ajouter une méthode IsPescetarian. C'est la même chose que ce que vous avez déjà fait. Tout ce qui est végétarien est aussi pescétarien, y compris les poissons et les crevettes.

> Par contre, on a constaté que vous ne gériez pas les crevettes. On va ouvrir un bug report à ce sujet. Il faut le corriger rapidement.

> Vous profiterez du nettoyage pour fixer ça.

- maintenir le flou, les incohérences et demander des estimations
- insister sur le fait que le mieux est l'ennemi du bien
- faire le tour des équipes en leur demandant si elles ne produiraient pas davantage en se divisant en plusieurs équipes d'une personne chacune travaillant ensemble en se répartissant les tâches.

## Itération 3 (15 minutes)

> Bon, on a un souci.  On vous explique. 
> Tu le manges comment ton kebab ? 

> Ben, avec une sauce

> Et là, est-ce qu'on peut mettre des sauces ? Et non. C'est pourtant évident qu'on met des sauces dans un kebab. Il y en a qui n'ont jamais mangé de kebab de leur vie ?

> Du coup, dans cette itération, il faudra fixer ça. Et c'est urgent, nos clients perdent de l'argent à cause de ça.

> Mais ce n'est pas tout. On a constaté deux demandes très importantes de nos clients et on commence à perdre des clients à cause de ça. Il faut gérer une nouvelle fonctionnalité pour adapter les kebabs au goût de nos clients.

> removeOnion et doubleCheese. Ces deux méthodes retournent un kebab. Le même ou un autre, on s'en moque, mais les utilisateurs ne manipuleront que le kebab retourné.

> removeOnion retourne n'importe quel kebab sans les onions et doubleCheese retourne n'importe quel kebab en doublant le cheese.

> Il faut que cette fonctionnalité et le fix soit dispo pour la fin de l'itération. Pour ça, on vous accorde 15 minutes.

- maintenir le flou, les incohérences et les demandes d'estimations
- insister sur le fait que vos deux demandes n'en font qu'une
- refuser d'établir un ordre de priorité entre elles
- faites le tour de l'équipe en leur demandant s'ils ne peuvent pas terminer plus tôt, par exemple 10 minutes au total

## Intermission
> Merci pour votre travail. C'est vraiment fantastique ce que vous avez réussi à faire. Vous pouvez être fier de vos coéquipier. Vous avez si bien bossé... que vous êtes viré ! Vous nous avez fait perdre beaucoup de clients. Le produit n'est pas terminé, il n'est pas stable. C'est vraiment du gachis pour un projet aussi simple.

> Du coup, on a décidé d'embaucher une nouvelle équipe. Vous. Vous êtes une autre version de vous même. Une nouvelle équipe qui hérite du travaille des autres.

> On sent que vous êtes doués. On vous laisse une minute pour auditer le code sans le modifier. Faîtes un rapport expliquant les raisons de l'échec de l'équipe précédente.

## Itération 4 (20 minutes)
> A partir de ce que vous avez constaté, vous allez maintenant repartir sur de bonnes bases. Des bases solides.

> Si quelque chose ne fonctionne pas, faîtes le marcher.

> Si le code n'a pas de test, ajoutez en. C'est important d'avoir des tests qui nous protègent.

> Et une fois que vous avez fait ça, refactorez ! Nettoyez le bazar que l'équipe précédente a créé. On compte sur vous.

> Mais on a une bonne nouvelle. On a tiré des conclusions de cet échec. Du coup, pour vous aider dans cette tâche, on a embauché un architecte pour diriger ce nettoyage. Je lui laisse présenter le plan d'action

En tant qu'architecte : 
- Vous êtes _l'architecte_
- Vous essayez de leur parler en des termes qu'ils peuvent comprendre.
- Vous proposez qu'ils créent un `Kebab` de type "Plat" qui utilise le pattern **NullObject**.
- Ensuite, chacun des autres types de `Kebab` devrait utiliser le pattern **Composite**.
- Ils prendront un autre `Kebab`, interne, dans leur constructeur et lui délégueront.
- un `Beef` `Kebab` n'est pas végétarien : son `isVegeterian` renvoie `false`
- un `Kebab`Salade` est végétarien : son `isVegeterian` appelle le `isVegeterian` de son `Kebab` interne
- Repousser toute critique de l'idée en faisant appel à votre propre autorité


## Debrief

- ont-ils créé, selon leur définition personnelle, une base de code patrimoniale ?
- Quelle est leur définition ?
- Vous avez utilisé au moins 10 techniques pour les pousser à créer du code merdique (Note : ce sont mes astuces)
- vous leur en offrez une gratuitement : Vous avez instillé un sentiment d'urgence artificiel et arbitraire     avec vos délais et vous faites pression sur eux pour qu'ils terminent avant ces délais arbitraires
- Qu'avez-vous fait d'autre ?
- Faites-leur dresser une liste
- Est-ce qu'ils voient cela dans leur vie de tous les jours ?
- Comment pouvons-nous lutter contre chacun d'entre eux ?
- Cela devient un débat











