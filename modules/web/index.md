---
layout: instructions
title: Webbprogrammering
code: web
---

# Webbprogrammering med Python

Webbprogrammering är en av de mest populära tillämpningarna för Python. Det passar bra som fördjupning efter att ha gått igenom den grundläggande programmeringen i modul 1-5.

## Webbramverk

Det finns många konkurrerande ramverk och bibliotek webbprogrammering med Python. Alla delar det grundläggande målet i att förenkla vanliga uppgifter samt att ge en struktur att bygga sitt program efter.

### Rekommenderat: Bottle

[Bottle](http://bottlepy.org/) är det rekommenderade ramverket på grund av enkelheten i att installera och komma igång. Det snabbaste alternativet är att ladda hem [bottle.py](http://bottlepy.org/bottle.py) till din projektmapp. Därefter kan du använda Bottle fullt ut.

Bottle, likt de flesta andra pythonprojekt, kan även installeras globalt på systemet med hjälp av så kallade pakethanterare (`pip` eller `easy_install`).

### Andra ramverk

* [Flask](http://flask.pocoo.org) är i princip lika enkelt att använda som Bottle - båda kan kallas "mikroramverk". Flask är värt att nämna här på grund as dess popularitet, är vanligt att använda även för webbapplikationer i produktion. Flask bör installeras via `pip` eller `easy_install`.

* [Django](https://www.djangoproject.com) är kanske det mest kända webbramverket för Python, och används av några av nätets största webbplatser. Bra att känna till - och värt att titta vidare på för mer avancerade, databasdrivna webbplatser.


## Komma igång med Bottle

Istället för egenpåhittade övningar rekommenderas den [tutorial som finns på bottle.org](http://bottlepy.org/docs/dev/tutorial.html#quickstart-hello-world). Den visar viktiga koncept med korta exempel för varje. För [uppgiften](assignments/wiki.html) kommer du bara behöva vissa av delarna, men det skadar inte att titta igenom all dokumentation.

### Exempelprojekt

Viktiga delar av funktionaliteten i Bottle visas även i [detta exempelprojekt](https://github.com/fohlin/bottleexample). Du kan även [ladda hem koden som en .zip](https://github.com/fohlin/bottleexample/archive/master.zip).

## Uppgift

[Uppgift: bygg din egen wiki](assignments/wiki.html)!