# dumplings-recipe
@startuml Dumpling Preparation Process

start
partition "Prepare Dough" {
  :Mix flour and salt;
  :Add warm water gradually;
  :Knead until smooth;
  :Rest dough for 30 minutes;
}

partition "Prepare Filling" {
  :Salt cabbage and let sit;
  :Squeeze out moisture;
  :Mix all filling ingredients;
  :Refrigerate 30 minutes;
}

partition "Make Dumplings" {
  :Divide dough into portions;
  :Roll into wrappers;
  :Add filling to center;
  :Fold and seal dumplings;
}

partition "Cooking" {
  fork
    :Boiling Method;
    :Boil water;
    :Add dumplings;
    :Cook until floating plus 3-4 minutes;
  fork again
    :Pan-Frying Method;
    :Heat oil in pan;
    :Cook dumplings until bottoms are golden;
    :Add water and cover;
    :Steam until water evaporates;
    :Crisp bottoms;
  fork again
    :Steaming Method;
    :Line steamer basket;
    :Place dumplings in steamer;
    :Steam for 8-10 minutes;
  end fork
}

:Prepare dipping sauce;
:Serve dumplings with sauce;

stop
@enduml
