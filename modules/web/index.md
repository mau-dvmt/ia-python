---
layout: instructions
title: Webbprogrammering
code: web
---

# Webbprogrammering med Python

Webbprogrammering är en av de mest populära tillämpningarna för Python. Det passar bra som fördjupning efter att ha gått igenom den grundläggande programmeringen i modul 1-5.

<!--

## ScalableLearning - Videos om webbapplikationer

Till denna modul finns det videoinspelningar som jag gjort. De är kompletterande till föreläsningarna som vi haft i denna modul, och går igenom alla koncept grundligt. All kod som skrivs i videoinspelningarna finns även tillgänglig. För att få tillgång till dessa videos, och möjlighet att ställa frågor till videoinspelningarna så följ dessa instuktioner:

1. Surfa till [https://www.scalable-learning.com/#/](https://www.scalable-learning.com/#/) och skapa ett konto med valfri epostadress.
2. Lägg till denna kursen genom att välja  “Join Course” från menyn “Courses” och ange följande nyckel för kusen: DA354A : YELAT-29268

-->

## Webbramverk

Det finns många konkurrerande ramverk och bibliotek webbprogrammering med Python. Alla delar det grundläggande målet i att förenkla vanliga uppgifter samt att ge en struktur att bygga sitt program efter.

### Rekommenderat: Bottle

[Bottle](http://bottlepy.org/) är det rekommenderade ramverket på grund av enkelheten i att installera och komma igång. Det snabbaste alternativet är att ladda hem bottle genom deras [webbplats](http://bottlepy.org/docs/stable/) till din projektmapp. Därefter kan du använda Bottle fullt ut.

Bottle, likt de flesta andra pythonprojekt, kan även installeras globalt på systemet med hjälp av så kallade pakethanterare (`pip` eller `easy_install`).

### Andra ramverk

* [Flask](http://flask.pocoo.org) är i princip lika enkelt att använda som Bottle - båda kan kallas "mikroramverk". Flask är värt att nämna här på grund as dess popularitet, är vanligt att använda även för webbapplikationer i produktion. Flask bör installeras via `pip` eller `easy_install`.

* [Django](https://www.djangoproject.com) är kanske det mest kända webbramverket för Python, och används av några av nätets största webbplatser. Bra att känna till - och värt att titta vidare på för mer avancerade, databasdrivna webbplatser.


## Komma igång med Bottle

Istället för egenpåhittade övningar rekommenderas den [tutorial som finns på bottle.org](http://bottlepy.org/docs/dev/tutorial.html#quickstart-hello-world). Den visar viktiga koncept med korta exempel för varje. För [uppgiften](assignments/wiki.html) kommer du bara behöva vissa av delarna, men det skadar inte att titta igenom all dokumentation.

### Exempelprojekt

Viktiga delar av funktionaliteten i Bottle visas även i [detta exempelprojekt](https://github.com/Tibbelit/Example-bottle-app) (Obs, använder ej JSON - men det är valfritt att göra det, eller inte). Du kan även ladda hem koden via den länken (som t.ex. en ZIP-fil).

<!--
[Så här ser det ut när man kör projektet](http://tibbelit2.pythonanywhere.com/). (Publicerat gratis via [PythonAnywhere](https://www.pythonanywhere.com).)
-->

## Uppgift

[Uppgift: bygg din egen wiki](assignments/wiki.html)!
