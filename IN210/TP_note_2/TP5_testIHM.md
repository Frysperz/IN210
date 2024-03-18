# Test Système Automatique

## Question 1 

L'intérêt du Test Setup et du Test TearDown est qu'ils permettent d'appeler un mot-clé à la création et à la destruction du test.

## Question 2 

Lorsque je positionne un Close Browser à la fin du test mais que l'une des commandes échoue, la fenêtre se ferme quand même.

## Question 3 

Nous avons choisi un locator relatif. En effet celui-ci est moins sensible que l'absolu. Il est probable que sur d'autres sets, le xpath local soit le même ou qu'il n'y ait que très peu de chose à modifer (par exemple l'id de l'attribut) alors qu'il y a de grandes chances que le chemin absolu du xpath soit radicalement différent sur une autre page web.

## Question 4 

L'intérêt des mots-clés est d'automatiser le code. En effet si l'on ne les utilise pas alors l'on va écrire plusieurs fois la même chose. Et lorsqu'on voudra réutiliser le code pour un autre exemple alors il faudra tout changer à la main. L'intérêt des mots-clés est de changer seulement une variable et/ou un argument pour changer tout le test automatiquement.

## Question 5 

On utilise une approche de test par les keywords. En effet notre code est séparé en deux parties : notre partie exécution contenant les tests et notre partie création de tests contenant les différents keywords permettant la création des différents tests.