# Juhlasivu – Animoitu tervehdys

Tämä projekti on yksinkertainen HTML-sivu, joka toivottaa käyttäjälle hyvää juhlaa tai syntymäpäivää animoidulla tekstillä ja tippuvilla emojeilla.

## Ominaisuudet

* **URL-parametrit:**

  * `nimi` – vastaanottajan nimi
  * `juhla` – juhlan tyyppi (esim. syntymäpäivää, joulua)
  * `emoji` – tippuvan emojin tyyppi (esim. 🎉, 🎂)
  * `count` – tippuvien emojien määrä
  * `duration` – animaation kesto sekunneissa (esim. 3)
  * `sizeMin` – pienin emoji-koko pikseleinä (esim. 20)
  * `sizeMax` – suurin emoji-koko pikseleinä (esim. 40)
  * `bgColor1` – taustagradientin alkuväri (esim. #ff9a9e)
  * `bgColor2` – taustagradientin loppuväri (esim. #fad0c4)
  * `font` – tekstin fontti (esim. Arial, sans-serif)
  * `textColor` – tekstin väri (esim. white)
  * `shadowColor` – tekstivarjon väri (esim. rgba(0,0,0,0.3))
  * `popScale` – tekstin pop-animaation suurin skaala (esim. 1.2)

* Animoitu tekstin pop-effect

* Tippuvat emojit koko näytöllä

* Helppo käyttää ilman lisäkirjastoja

## Käyttöohjeet

1. Avaa selaimessa ja lisää URL-parametrit. Esimerkki monilla argumentoilla:

```
file:///polku/juhlasivu.html?nimi=Octocat&juhla=syntymäpäivää&emoji=🎂&count=50&duration=3&sizeMin=20&sizeMax=40&bgColor1=%23ff9a9e&bgColor2=%23fad0c4&font=Arial&textColor=white&shadowColor=rgba(0,0,0,0.3)&popScale=1.2
```

3. Sivulla näytetään viesti ja tippuvat emojit juuri määrittämilläsi asetuksilla.

## Muokkaus

* Voit muuttaa taustaväriä, fonttia, tekstin väriä, varjon väriä, pop-animaation skaalaa CSS-parametreilla.
* Muokkaa JavaScriptissä animaation kestoa, emoji-määrää, kokoja ja muita parametreja URL:in kautta.
* Kaikki parametrit voidaan asettaa suoraan URL-parametreista ilman suoraa koodin muokkausta.

## Huomioita

* URL-parametrit tulee erottaa `&`-merkillä, ei usealla `?`.
* Unicode-emojit toimivat useimmissa moderneissa selaimissa.
* Jos parametreja ei anneta, käytetään oletusarvoja.
