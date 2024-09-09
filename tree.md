```mermaid
graph TD;

%% Youngest generation
Simon --> Parent1
Simon --> Parent2
Elliot --> Parent1
Elliot --> Parent2

%% Parents of the youngest generation
Parent1 --> Grandparent1
Parent1 --> Grandparent2
Parent2 --> Grandparent3
Parent2 --> Grandparent4

%% Grandparents of the youngest generation
Grandparent1 --> GreatGrandparent1
Grandparent1 --> GreatGrandparent2
Grandparent2 --> GreatGrandparent3
Grandparent2 --> GreatGrandparent4

Grandparent3 --> GreatGrandparent5
Grandparent3 --> GreatGrandparent6
Grandparent4 --> GreatGrandparent7
Grandparent4 --> GreatGrandparent8

%% Great-grandparents of the youngest generation
GreatGrandparent1 --> GreatGreatGrandparent1
GreatGrandparent1 --> GreatGreatGrandparent2
GreatGrandparent2 --> GreatGreatGrandparent3
GreatGrandparent2 --> GreatGreatGrandparent4

GreatGrandparent3 --> GreatGreatGrandparent5
GreatGrandparent3 --> GreatGreatGrandparent6
GreatGrandparent4 --> GreatGreatGrandparent7
GreatGrandparent4 --> GreatGreatGrandparent8

GreatGrandparent5 --> GreatGreatGrandparent9
GreatGrandparent5 --> GreatGreatGrandparent10
GreatGrandparent6 --> GreatGreatGrandparent11
GreatGrandparent6 --> GreatGreatGrandparent12

GreatGrandparent7 --> GreatGreatGrandparent13
GreatGrandparent7 --> GreatGreatGrandparent14
GreatGrandparent8 --> GreatGreatGrandparent15
GreatGrandparent8 --> GreatGreatGrandparent16
