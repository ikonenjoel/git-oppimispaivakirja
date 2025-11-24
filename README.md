# git-oppimispaivakirja

Tämä on kurssin oppimispäiväkirja.

## Harjoitus 3

### Harjoitus 3. kohta 3
Tiedostoille ei tapahtunut mitään untracked-tilassa.

### kohta 4

Komento git log näyttää, että edellinen talletus on vielä olemassa, ja että uusimman commitin talletus on peruutettu.

## Harjoitus 4

Tallennettu muutokset master-haaraan, siitä siirtyessä tyylit haaraan saadaan taas sivun css näkyviin ja takaisin siirtyessä se katoaa, sillä tyylit.css ei ole osa master-haaraa.

Sivu ei muutu mitenkään, sillä kummatkin haarat ovat identtiset.

## Harjoitus 5

Sivulla näkyy ohjeet, siitä miten uusi repositorio luodaan, tai miten jo valmiina oleva repositorio voidaan lisätä.

Repositiorisivulla näkyy master-haara ja lokaalissa master- sekä tyylit-haara.

README.md ilmestyi lokaaliin repositorioon.

Status kertoo, että olemme yhden commitin perässä origin/masteria.

Yhdistämisen jälkeen status kertoo, että olemme ajan tasalla origin/master branchin kanssa.

## Harjoitus 6

Ohjeet löytyy exercisebot.sh:n kautta.

Nappula toimi, näytti ajan oikein sivulla. Vaihdettiin toiseen toteutukseen, jossa sivulle lisättiin animoitu kello, sekä nykyinen päivämäärä ja vuosi.

## Harjoitus 7

Luotiin uusi haara muutospyynnot, muutettiin index.html sivustoa vähän jotta saadaan tehtyä uusi commit. Vietiin se githubiin ja tehtiin yhdistämispyyntö, joka yhdistettiin master branchiin. Päivitettiin paikallinen repositorio ja poistettiin muutospyynnot-haara.

# Oppimispäiväkirja: Paikallinen git

 Osion tehtävät eivät olleet kauhean vaikeita, mutta oletan syyksi sen, että olen töiden kautta käyttänyt aikoinaan gittiä.

 | Komento | Kuvaus |
| --------| ------ |
| git add . | Lisää repositoriossa olevat tiedostot ja muutokset. |
| git commit | Lisää muutokset tietovarastoon, jotta ne voidaan myöhemmin lisätä esim. githubiin. |

# Oppimispäiväkirja: Hajautettu git

Sama kuin aikaisempi, ei mitään ihmeellisen vaikeaa. Oppimiseen auttoi hyvät ohjeet ja selitykset, sekä stack overflow. Esteet selvitin enimmäkseen stack overflown kautta ja kaverilta kysymällä.

 | Komento | Kuvaus |
| --------| ------ |
| git pull | Hakee muutokset repositioriosta jos niitä on. |
| git push | Vie muutokset repositiorioon gitissä. |

# Oppimispäiväkirja: Git projektissa

### Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?

Hyöty projektissa tulee versionhallinnasta, talletuksesta johonkin muualle varmuuskopiona ja se helpottaa uusien toiminnallisuuksien testaamista kun voit palata takaisin toimivaan versioon.

### Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?

Versionhallinta helpottaa näkemään missä kohtaa muut menee ja varmistamaan, että kaikilla on samat tiedostot ja tiedot projektista. Helpottaa myös ylläpitämistä ja eri versioiden yhdistelemistä. Takaa sen, että kaikki ovat helposti ajan tasalla uusimmasta koodista ja vähentää tarvetta kommunikoida muutoksiin liityvistä asioista.

### Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.

Origin master on vain valmiille ja toimiville ohjelmistoille. Jos lisätään uusinta funktionaalisuutta niin sille tehdään oma haara. Kommentit ovat pakollisia ja niiden kuuluisi olla selkeitä, sekä kertoa mitä muutokset sisältävät. Jokainen yhdistyspyyntö mielellään tarvitsisi kahden henkilön tarkistuksen ja hyväksynnän. Jos jotain haaraa ei enään käytetä se kuuluisi poistaa.

### Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?

Luentovideot olisivat kivoja, monet oppivat niistä paremmin kuin vain tekstistä.