# SES Patterns: Singleton

Oefening voor https://kuleuven-diepenbeek.github.io/ses-course/patterns/singleton

## Technologie

Dit is een [gradle project](https://kuleuven-diepenbeek.github.io/ses-course/dependency-management/).

## Opgave

1. In deze opgave is het voorbeeld uit de [labo noties](https://kuleuven-diepenbeek.github.io/ses-course/patterns/singleton) verwerkt, maar nog zonder Singleton... Voer de unit testen uit in `src/main/test`: het resultaat zijn gefaalde testen (ROOD), omdat `DBHandle` verschillende keren wordt aangemaakt. Zorg er voor dat alle testen slagen (GROEN) door het singleton patroon te implementeren! 
2. Pas ook `ShoppingCartResource` aan naar een singleton. Is dat nodig om de database niet te overbelasten, als de andere klasse reeds een singleton is, of niet? 