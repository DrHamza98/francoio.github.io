---
title: "Formulaire de réponse pour le test 1"
output: html_document
---

** **

##### Prénom Nom Groupe
Hamza DRIDI G6


##### Question 1

* Déterminer l'espérance du nombre de candidats réussissant l'examen.

###### Réponse : 

** ** E = 0.98 * 240 = 235.2

##### Question 2

* Calculer les probabilités P($N = i$), pour tout $i$ de 1 à 4.  

###### Réponse : 

** ** i = 1 P(N=1) = 1/16
      i = 2 P(N=2) = 1/8
      i = 3 P(N=3) = 3/16
      i = 4 P(N=4) = 1/4

##### Question 3

* Calculer la probabilité de l'événement $G$ sachant que le candidat change de porte. Calculer la probabilité de l'événement $G$ sachant que le candidat conserve son choix initial.

###### Réponse : 

** ** A = "le candidat conserve son choix "
      B = "le candidat change son choix "
      P(G|A) = 1/2
      P(G|B) = 1/2

##### Question 4

* Le candidat opte a priori pour une stratégie aléatoire. Il change de porte avec la probabilité $p = 1/3$. Puis il joue et gagne le jeu. Quelle est la probabilité que le candidat ait changé de porte ?   

###### Réponse : 

** ** P(B|G) = 1/3

##### Question 5

* Calculer la valeur médiane de la variable $X$.  

###### Réponse : 

** ** m = 9/13


##### Question 6

* Calculer la probabilité de l'événement $(Z_N > 1)$  

###### Réponse : 

** ** P(Z>1) = exp(-1) * (exp(exp(-μ)) -1)


##### Question 7

* Déterminer la loi de la variable $Z$. Donner son espérance.


###### Réponse : 

** ** Z suit la loi binomial de parametre 2n = 40 et de probabilité p(1-p) = 1/3
      E(Z) = 2n * p(1-p) = 40/3


##### Question 8

* Déterminer la loi de la variable $Y$. Donner son espérance.

###### Réponse : 

** ** Y = Z - X
      E(Y) = E(Z) - E(X) = 40/3 - 40/3 = 0


##### Question 9

* Donner une relation simple liant ${\rm E}[XY]$ à l'espérance d'une fonction simple de $X$ et la valeur de cette espérance (une ligne). 

###### Réponse : 

** **

##### Question 10

* Calculer la variance de la variable aléatoire $Z$. En déduire la covariance du couple $(X,Y)$ et retrouver le résultat précédent (une ligne). 
   
###### Réponse : 


** **  V(Z) = 2n * p(1-p) * (1- p(1-p)) = 40/3 * 2/3 = 80/9


