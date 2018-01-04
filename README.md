# cljs-kurssi

Tulevan sisäisen ClojureScript kurssin template sovellus.

# Ohjeet

* Forkkaa tämä repo
* Käynnistä repl: lein run
* Käynnistä figwheel: rlwrap lein figwheel
* Avaa http://localhost:3000/index.html
* Testit ajoon: lein doo phantom test
* Koodaa menemään!

# Frontin kehitys

Kun figwheel on käynnissä frontend buildi päivittyy automaattisesti ja kytkeytynyt selain saa uudet
koodimuutokset. Joissain tapauksissa täytyy selain uudelleenladata, jos React jää virheelliseen
tilaan, mutta useimmat muutokset toimivat livenä.

# Backend kehitys

Kun kehität backendiä, aja `lein run` komennon sijasta `lein repl` ja kytkeydy siihen lempieditorillasi.
REPListä palvelimen saa käyntiin `(-main)` funktiota kutsumalla `widgetshop.main` nimiavaruudessa.
