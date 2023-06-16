# Thunderbird+ #

* Tekijät: Pierre-Louis Renaud (Thunderbirdin versiot 78-102), Daniel
  Poiraud (TB:n versiot 68-91), Abdelkrim Bensaïd osasta TB:n versiota 78,
  Yannick (TB:n versiot 38-60)
* URL:
  [Käyttöopas](https://www.rptools.org/Outils-DV/NVDA-ThunderbirdPlus-en.html)
  , [Ota yhteyttä ranskaksi tai
  englanniksi](https://www.rptools.org/Outils-DV/contact.html)
* Lataa [vakaa versio][1]
* Lataa [viimeisin versio RPTools.orgista][2]
* Yhteensopivuus: NVDA 2019.3 ja uudemmat
* Yhteensopivat Thunderbirdin versiot: 102.x
* [Lähdekoodi GitHubissa][3]

Huom: Tämä lisäosa ei ole yhteensopiva Mozilla-sovellusten laajennukset
-lisäosan kanssa. Mikäli se on asennettuna, poista se käytöstä tai poista
sen asennus ennen tämän lisäosan käyttöä.

Tämä lisäosa parantaa huomattavasti Mozilla Thunderbird -sähköpostiohjelman
käytön saavutettavuutta, tehokkuutta ja mukavuutta NVDA:lla.

## Kuulomukavuus

* "Sen ja sen pyydetty kuittaus" -ilmoitukset voidaan poistaa käytöstä
  asetuksista.
* "Tämä on luonnos"- ja "Thunderbirdin mielestä tämä viesti on petollinen"
  -ilmoitukset jätetään huomiotta.
* Asetukset mahdollistavat postituslistojen nimien ilmoittamisen käytöstä
  poistamisen, "RE"-etuliitteiden poistamisen tai ryhmittelyn sekä
  keskustelukumppanien nimien puhdistamisen poistamalla niistä numerot ja
  muut hankalat erikoismerkit.

## Paranneltu navigointi

* Seuraavaan paneeliin siirrytään Sarkain-näppäimellä ja Esc-näppäimellä
  palataan edelliseen. Tämä on mukavampaa kuin F6 ja Vaihto+F6.
* Kaksi valintaikkunaa tileille ja liittyvät kansiot mahdollistavat niiden
  suodattamisen avainsanalla tai näyttämällä vain kansiot, joissa on
  lukemattomia viestejä.
* Kansiopuussa Alt+Nuoli alas/ylös mahdollistavatlukemattomia viestejä
  sisältävien kansioiden välillä liikkumisen.
* Kansiopuussa kirjaimen tai numeron painaminen valitsee seuraavan kansion,
  jonka nimi alkaa kyseisellä merkillä. Vaihto-näppäimen kanssa painettaessa
  siirtyminen tapahtuu alhaalta ylös. Lisäksi ilmoitetaan sen tilin nimi,
  johon kansio kuuluu.
* Väli-näppäimen painaminen lukemattomia viestejä sisältävän kansion
  kohdalla valitsee luettelossa ensimmäisenä olevan lukemattoman viestin.

## Viestiluettelossa

* Sarakkeiden valitseminen ja niiden järjestäminen viestiluettelossa on
  mahdollista yksinkertaisen valintaikkunan avulla.
* Viestiluettelon sarakkeiden puhuminen: Mahdollistaa lähettäjän nimen,
  viestin aiheen tai päivämäärän puhuttamisen, tavaamisen tai leikepöydälle
  kopioimisen painamalla numeroa aakkosnumeeriselta
  näppäimistöltä. Esimerkiksi 1 tai & ilmoittaa lähettäjän, kaksi
  painallusta tavaa sen ja kolme painallusta kopioi leikepöydälle.
* F8:lla näytettävän esikatseluruudun otsakkeiden puhuminen: Alt+numeron
  yksi painallus puhuu lähettäjän tai vastaanottajien osoitteet sisältävän
  otsakkeen, kaksi painallusta avaa valintaikkunan, jossa ne voidaan
  kopioida leikepöydälle, kolme painallusta avaa natiivin
  Thunderbird-pikavalikon otsakkeelle.
* Viestin tekstin puhdas pikaesikatselu välilyönnillä, Alt+Nuoli alas
  -näppäimillä tai F4:llä: Viestilainausten suuret lohko-otsakkeet korvataan
  "Lähettäjän nimi kirjoitti" -virkkeellä. NVDA sanoo lisäksi "napsautettava
  linkki" pitkän linkin osoitteen sijaan.
* Lainausten pikakatselu kronologisessa järjestyksessä alhaalta ylös
  Vaihto+Väli-näppäimellä, Alt+Nuoli ylös -näppäimillä tai Vaihto+F4:llä.
* Helppo pääsy liitteisiin pikanäppäimellä Alt+Page down tai
  aakkosnumeerisen näppäimistön numero 1:llä.
* Pikasuodatuspalkki tehty saavutettavaksi ja tärkeystunnuksien hallintaa
  yksinkertaistettu:

	* Suodatinvaihtoehtojen välillä on mahdollista liikkua pystysuuntaisilla
	  nuolinäppäimillä. Vaihtoehto valitaan tai sen valinta poistetaan
	  Enter-näppäimellä.
	* Tärkeystunnuksia lisätään tai poistetaan painamalla Vaihto+numeroa
	  aakkosnumeeriselta näppäimistöltä. Esimerkiksi numero 4:n painaminen
	  lisää viestiin "Tehtävä"-tunnuksen. Tämän jälkeen viestiluetteloa voidaan
	  suodattaa tunnuksien perusteella pikasuodatuspalkista, joka on nyt
	  saavutettava.
	
	## Viestinkirjoitusikkuna

* Alt+1 puhuu lähettäjän, Alt+2 vastaanottajan, Alt+3 liitteet jne. Kaksi
  painallusta siirtää kohdistuksen kyseiseen kenttään.
* Oikeinkirjoituksen tarkistuksen valintaikkunassa:

	* Väärin kirjoitettu sana puhutaan ennen ehdotettua sanaa. NVDA+Sarkain-
	  tai Alt+Nuoli ylös -pikanäppäimet puhuvat väärin kirjoitetun ja korvaavan
	  sanan: Yhdellä painalluksella sanat tavataan normaalinopeudella, kahdella
	  painalluksella ne tavataan nopeasti, kolmella painalluksella väärin
	  kirjoitettu sana kopioidaan leikepöydälle.
	* Lisätty tämän valintaikkunan käyttömukavuutta lisäämällä Enter-näppäimen
	  eri yhdistelmiä Korvaa-, Korvaa kaikki-, Ohita-, Ohita kaikki- tai Lisää
	  sanastoon -painikkeiden painamiseen.

* Automaattinen lisäosan päivitys
* Sekä monia muita ominaisuuksia, jotka löytyvät [käyttöoppaasta][4].

[[!tag dev stable]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=thunderbirdPlus

[2]: https://www.rptools.org/?p=8610

[3]: https://github.com/RPTools-org/ThunderbirdPlus/

[4]: https://www.rptools.org/Outils-DV/NVDA-ThunderbirdPlus-en.html
