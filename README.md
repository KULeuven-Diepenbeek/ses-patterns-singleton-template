# SES Patterns: Singleton

Oefening voor https://brainbaking.com/teaching/ses/singleton

## Technologie

Dit is een [gradle project](https://brainbaking.com/teaching/ses/gradle).

## Opgave

1. In deze opgave is het voorbeeld uit de [labo noties](https://brainbaking.com/teaching/ses/singleton) verwerkt, maar nog zonder Singleton... Voer de unit testen uit in `src/main/test`: het resultaat zijn gefaalde testen (ROOD), omdat `DBHandle` verschillende keren wordt aangemaakt. Zorg er voor dat alle testen slagen (GROEN) door het singleton patroon te implementeren! 
2. Pas ook `ShoppingCartResource` aan naar een singleton. Is dat nodig om de database niet te overbelasten, als de andere klasse reeds een singleton is, of niet? 