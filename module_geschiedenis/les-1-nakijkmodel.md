# Les 1a nakijkmodel

## Variabelen

1\) en 2\)

Met een variabele kan je een stuk tekst makkelijk van onderwerp laten veranderen. 

Een variabele definieer je zo:
```python
dier = 'Schildpad'
```

Een variabele heeft een andere kleur dan tekst. 

Een variabele heeft geen aanhalingstekens nodig

Python gaat omhoog zoeken naar de betekenis van de variabele.

## Lijsten

1\) en 2\)

Met lijsten kan je meerdere opties voor een variabele geven.

Een lijst begint met tellen bij 0, de eerste optie is nummer 0, de tweede optie is nummer 1 etc.

Een lijst definiëer je met een = en rechte haken.

Woorden in een lijst moeten tussen aanhalingstekens.

Woorden in een lijst worden van elkaar gescheiden door een komma.

Je verwijst naar een element in de lijst door een nummer in rechte haken achter de lijstnaam te zetten.

Een lijst met een aanwijzer is zwart, net als een variabele. 

```python
dieren = ['schildpad', 'koe', 'konijn']
print('Mijn lievelingsdier is een', dieren[0])
```

## Willekeurig

1\) en 2\)

Boven aan je code zet je import random

Met de code random.shuffle(lijstnaam) geef je Python de opdracht willekeurig een element uit de lijst aan te wijzen. 

In je printopdracht zet je nog steeds een aanwijzer.

```python
import random
dieren = ['schildpad', 'koe', 'konijn']
random.shuffle(dieren)
print('Mijn lievelingsdier is een', dieren[0])
```

## If

1\) en 2\)

Met de code input() kan de lezer in het outputscherm antwoord geven op een vraag.

De input van de lezer kan worden opgeslagen in een variabele:
```python
print('Koe of paard?')
dier = input()
```

Met de if-else code kan de input van de lezer het verloop van een code beïnvloeden. Bepaalde regels kunnen worden overgeslagen en anderen juist worden uitgevoerd. 

Bij de if gebruik je ==

De regel met if sluit je af met :

De regel met else sluit je af met :

Regels onder if beginnen met twee spaties.

Regels onder else beginnen met twee spaties.

De variabele in de regel met if moet tussen aanhalingstekens. 

Python leest nog steeds naar boven wat er moet gebeuren, maar één van de twee takken wordt uitgevoerd.

Het woordt ingevuld voor if moet precies kloppen, ook wat betreft spelling en hoofdletters, anders wordt de else-tak uitgevoerd. 

```python
print('Koe of paard?')
dier = input()
if dier == 'Koe':
  print('Moehoe')
else:
  print('Hihihihi')
```

