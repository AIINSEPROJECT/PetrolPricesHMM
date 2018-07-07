# PetrolPricesHMM
PROJECT BSSE 3RD YEAR SECTION B

COURSE: AI IN SOFTWARE ENGINEERING 

HIDDEN MARKOV MODEL 

The Hidden Markov Model is a finite set of states, each of which is associated with a (generally multidimensional) probability distribution []. Transitions among the states are governed by a set of probabilities called transition probabilities. In a particular state an outcome or observation can be generated, according to the associated probability distribution. It is only the outcome, not the state visible to an external observer and therefore states are ``hidden'' to the outside; hence the name Hidden Markov Model.


PETROL PRICE HMM INCLUDES 2 STATES:

1)INFLATION

2)DEFLATION


THIS HMM INCLUDES START AND END STATE ALSO.


THE OBSERVATION SEQUENCE IS :

90.24,90.24,59.35,59.35,76.98,90.24,90.24,59.35,76.98


Initial transition probabilities pi are :

1)0.7

2)0.3

emission and transitional probabilty are defined in STEProbab.txt as:

Transition probablities:

  START INFLATION DEFLATION END       
  
S 0.0, 0.7, 0.3,0.0

I 0.0, 0.6, 0.3,0.1

D 0.0, 0.4, 0.5,0.1

E 0.0, 0.0, 0.0,0.0

EMISSION PROBAB:

0.0, 0.0, 0.0

0.1, 0.4, 0.5

0.6, 0.3, 0.1

0.0, 0.0, 0.0
