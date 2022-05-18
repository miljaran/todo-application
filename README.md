# Todo-sovellus

## Kuvaus
Sovelluksessa käyttäjä pystyy pitämään kirjaa hänen tehtävistään. "Tehtävät"-sivulla näkyy lista tehtävistä sekä lomake uusien tehtävien lisäämistä varten. Uudelle tehtävälle pitää antaa vähintaan nimi, mutta muilla arvoilla on oletusarvot joita käytetään jos käyttäjä ei ole antanut syötettä. Samannimisiä tehtäviä ei voi luoda useita, vaan nimet ovat uniikkeja.

Käyttäjä voi valita, millä perusteella hän haluaa järjestellä tehtävälistan, esimerkiksi aakkosjärjestykseen. Jokaisesta tehtävästä näkyy listanäkymässä nimi, deadline ja tehtävän status. Klikkaamalla tehtävän nimeä pääsee tehtävän omalle sivulle, jossa näkyy myös tehtävän kuvaus ja tehtävää voi muokata tai sen voi poistaa.

Käyttäjä voi myös seurata erilaisia tilastoja tehtävistään "Tilastoja"-sivulla.

Sovelluksen tiedot eivät tallennu tällä hetkellä minnekään ja ne nollaantuvat aina kun sivua päivitetään.

## Sovelluksen ajaminen
Sovellus toimii osoitteessa [https://miljaran.github.io/todo-application/](https://miljaran.github.io/todo-application/). Omalla laitteella sovelluksen voi ajaa komentoriviltä siirymällä projektin juureen sekä ajamalla ensin komennon `npm install` ja sen jälkeen `npm start`. Tämän jälkeen sovellus toimii osoitteessa [http://localhost:3000](http://localhost:3000).