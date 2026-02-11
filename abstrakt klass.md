En abstrakt klass är en mekanism för att implementera partiell abstraktion. Till skillnad från ett interface, som definierar ett kontrakt,  definerar en abstrakt klass en grundläggande identitet och tillstånd. 
En abstrakt klass kan inte instanseras men man kan skapa konstruktorer med dem.
Om underklassen inte implementerar _alla_ abstrakta metoder, måste även underklassen deklareras som `abstract`.
Abstrakta klasser kan ha instansvariabler till skillnad från interface som endast kan ha konstanten (public  static final)