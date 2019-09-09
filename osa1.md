---
layout: page
title: osa 1
inheader: yes
permalink: /osa1/
---

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">
  <img alt="Creative Commons -lisenssi" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png"
  />
</a>

# Ohjelmistotuotanto ja sen osa-alueet

IEEE (Institute of Electrical and Electronics Engineers) yksi alamme keskeisistä vaikuttajajärjestöistä määrittelee ohjelmistotuotannon (engl. software engineering) seuraavasti:

> The application of a systematic, disciplined, quantifiable approach to the development, operation, and maintenance of software; that is, the application of engineering to software

IEEE:n mukaan ohjelmistotuotannolla tarjoitetaan systemaattista, kurinalaista, mitattavissa olevaa tapaa ohjelmistojen kehittämiseen, operointiin ja ylläpitoon. Määritelmän loppukaneetti sanoo, että kyseessä on siis "insinöörimäinen" tapa ohjelmistojen tekoon ja operointiin.

> On huomioinarvoista, että ohelmistotuotanto on englanniksi _software engineering_. Suomenkielinen vastine _ohjelmistotuotanto_ onkin terminä aika huono, jos suomenkielinen termi käännettäisiin takaisin englantiin, olisi tuloksena _software production_, eli ohjelmien valmistaminen. Termiä production käytetään yleensä suoraviivaisesta tuotteiden rakentamisesta, esim. jos tehdas valmistaa tuoleja, voidaan sanoa että sen ala on _chair production_. Ohjelmistojen tekeminen on aktiviteettina hyvin erihenkinen kuin esim. tuolin. Ohjelmistojen "rakentamisesta" käytetään englanninkielistä termiä developemt, eli voidaan sanoa että _company develops software for accounting_, joka taas suomeksi kuuluisi _yritys kehittää ohjelmistoja laskutukseen_. Kehittäminen (development) on aktiviteetti joka sisältää muutakin kuin pelkkää suoraviivaista valmistamista (production), kehittäminen sisältää mm. suunnittelun ja kysymyksenasettelun sen suhteen mitä ja miksi ylipäätään on tarve jonkinlaiselle tuotteelle. Ohjelmistotuotanto eli software engineering tarkoittaakin "insinöörimäisen" lähestymistavan soveltamista ohjelmistokehitykseen. 

Lähde määritelmälle on [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering), eli _Software Engineering Body of Knowledge_, missä IEEE on komiteavetoisesi määritellyt sillä mitä se tarkoittaa ohjelmistotuotannolla ja mitä osa-alueita se katsoo ohjelmistotuotantoon kuuluvan. SWEBOK:in uusin versio 3.0 on vuodelta 2014 eli jo jossain määrin ikääntynyt.

## Osa-alueet

SWEBOK:in mukaan ohjelmistotuotanto jakautuu seuraaviin osa-alueisiin:

- Software requirements 
- Software design 
- Software construction 
- Software testing
- Software maintenance 
- Software configuration management
- Software engineering management
- Software engineering process 
- Software engineering models and methods
- Software quality

_Software requirements_ tarkoittaa ohjelmistolle asetettuja vaatimuksia, eli sitä miten rakennettavan ohjelmiston tulisi loppukäyttäjän tai tilaajan mielestä toimia. 

_Software design_ taas tarkoitta halutun kaltaisen toiminnallisuuden omaavan ohelmiston sisäisen rakenteen ja tekniikkojen omaavan ohjelman suunnittelua. 

_Software construction_ viittaa aktiviteetteihin, jonka avulla suunniteltu ohjelmisto saadaan toiminakuntoiseksi eli käytännössä siis tarkoitetaan ohjelmointia ja debuggausta.

Kuten arvata saattaa _Software testing_ tarkoittaa niitä menetelmiä, millä varmistutaan siitä että ohjelmisto toimii kuten halutaan ja että se on riittävän bugiton käytettäväksi.

Suurin osa ohjelmisstoista ei valmistu lopullisesti koskaan, kun ohjelman ensimmäinen versio otetaan käyttöön alkaa ylläpito eli _software maintenance_ eli bugeja korjaillaan ja ohjelmaa laajennetaan uusilla toiminnoilla.

_Software configuration management_ viittaa ohjelmiston käyttöönsaattamiseen liittyviin kirjastojen, laitteistojen ja käännösprosessin konfigurointiin sekä ohjelmiston versiointiin.

Ohjelmistojen tekemiseen liittyy paljon suunnittelu, koordinointia, hallinnointia ja raportointia eli "managementtiä", _Software engineering management_. 

_Software engineering process_ eli ohjelmistoprosessit kuvavat tapoja tai menetelmiä miten ohelmistoa kehittävien ihmisten tulisi tulisi hoitaa ja ajoittaa erilaisia ohjelmiston tekemiseksi vaadittavia aktiviteettejä (requirements, design, construction, testing). Palaamme aiheeseen tarkemmin seuraavassa luvussa.

_Software engineering models and methods_ kuvaa yksityskohtaisempia menetelmiä, joita ohjelmistokehityksessä käytetään, kuten mallinnusta ja erilaisia suunnittelumenetelmiä. 

Ohjelmistojen laatu eli _Software quality_ on vielä testaustakin avarampi näkemys siihen onko ohjelmisto hyvä, bugittomuutta ja oikein toimivuutta keskeisempi kysymys on se, vastaako ohjelmisto ylipäätään käyttäjien tarpeeseen, onko se sopiva käyttötarkoitukseensa.

Ohjelmistotuotanto pitää siis allaan suuren määrän hyvin erilaisiakin asioita. Tällä kurssilla käydään ainakin jossain määrin läpi näitä kaikkia osa-alueita. Koska aihepiirien määrä on todella suuri ja aikaa rajallisesti, jää asioiden läpikäynti osin valitettavan pintapuoliseksi. Lähes jokaisesta aihepiiristä on kuitenkin tarjolla kursseja erityisesti maisteripuolella. 

Aloittelevalle ohjelmistoalan opiskelijalle onkin tässä vaiheessa oleellisempaa saada kokonaiskuva ohjlemistotuotannon kentästä ja sen jälkeen soveltaa ja reflektoida oppimaansa käytännön ohjelmistotyössä, esim. Tietojenkäsittelytieteen osaston opintojaksolla [ohjelmistotuotantoprojekti](https://github.com/HY-TKTL/TKT20007-Ohjelmistotuotantoprojekti) tai oikeassa työelämässä. Aihepiiriä syventävät kurssit ovat todennäköisesti huomattavasti mielekkäämpää suorittaa siinä vaiheessa kun opiskelija omaa jo jonkinlaisen määrän alan käytännön kokemusta.

# Ohjelmiston elinkaari

Edellisessä luvussa mainituttujen ohjelmistotuotannon osa-alueeiden

- Software requirements, vaatimusten määrittely
- Software design, suunnittelu
- Software construction, ohjelmiston toteutus
- Software testing, testaus
- Software maintenance, ylläpito 

voidaan ajatella muodostavan _vaiheet_, joiden kautta ohjelmisto kehityksensä aikana etenee. Joskus näistä vaiheista käytetään nimitystä ohjelmiston _elinkaari_ (software lifecycle). Aikojen saatossa on ollut erilaisia tapoja jäsentää ohjelmistojen kehittäminen elinkaaren suhteen, eli se miten ja kenen toimesta vaiheet on suoritettu, on vaihdellut.

## Code'n'fix

Tietokoneiden historian alkuaikoina laitteet maksoivat paljon, ohjelmistot olivat laitteistoihin nähden "triviaaleja". Ohjelmointi tapahtui alussa kaapeleita yhdistelemällä ja hieman myöhemmin konekielellä. Sovellusten käyttäjät, kuten aseteollisuudessa olleet fyysikot jotka laskivat ammusten lentoratoja, yleensä ohjelmoivat itse tarvitsemansa sovellukset. 

Sovelluskehitys tapahtui pitkälti _code and fix_ -mentaliteetilla, eli koodattiin ja katsottiin toimiko softa. Ohjelmistojen yksinkertaisuuden ja suhteellisne halpuuden takia se ei muodostanut minkäänlaista pullonkaulaa.

Vähitellen ohjelmistot alkavat kasvaa. Kehitettiin korkeamman tason ohjelmointikieliä kuten Fortran, Cobol, Algol ja ohjelmistojen käyttöalue alkoi laajeta koskemaan muitakin elämänalueita kuin sotateollisuutta. Ohjelmistoja alettiin tekemään loppukäyttäjille, jotka eivät enää olleet ohjelmistoalan ammattilaisia, eli kuilu ohjelmiston tekijöiden ja loppukäyttäjien välillä alkoi kasvaa.

Ohjelmistoala alkoi joutua ongelmiin, [wikipedia](https://en.wikipedia.org/wiki/Software_crisis) mukaan ongelmia olivat

- budjetit ylittyivät ja projektit myöhästyivät aikatauluista
- ohjelmistot olivat tehottomia, niiden laatu oli huono ja ne eivät toimineet käyttäjien tarpeiden mukaan
- koodin ylläpito ja laajentaminen oli vaikeaa
- ja jopa usein kävi niin, että ohjelmistoja ei hyvistä aikista huolimatta saatu ollenkaan toimitettua

## Ohjelmistokriisi

Kesällä 1968 NATO:n järjestämässä konferenssissa julkistettiinkin että maailmassa on _software crisis_, eli ohjelmistokriisi.

Termillä viittaa siihen miten vaikeaa on toteuttaa käyttökelpoisia, oikein toimivia, tehokkaita ja laajennettavissa olevia ohjelmistoja käytössä olevien resurssien puitteissa.

Eräs tietojenkäsittelyn pioneereista, Turing-palkittu Edsger Dijkstra ilmaisi asian seuraavasti vuonna 1972 pitämässään [esitelmäsä](https://www.cs.utexas.edu/~EWD/transcriptions/EWD03xx/EWD340.html) 

> The major cause of the software crisis is that the machines have become several orders of magnitude more powerful! To put it quite bluntly: as long as there were no machines, programming was no problem at all; when we had a few weak computers, programming became a mild problem, and now we have gigantic computers, programming has become an equally gigantic problem.

Eli kun tietokoneita ei ollut, ohjelmointi ei muodotanut ongelmaa. Ensimmäistet tietokoneet olivat laskentateholtaan pieniä, ja ne aiheuttivat ainoastaan pieniä ongelmia ohjelmointiin. Massiivisen tehokkaiden tietokoneiden myötä myös ohjelmoinnista on tullut massiivinen ongelma...

## Ohjelmistokehitys insinööritieteenä: software engineerin

Termi _software engineering_ eli ohjelmistotuotanto määritellään ensimmäistä kertaa 1968:

> The establishment and use of sound engineering principles in order to obtain economically software that is reliable and works efficiently on real machines
     
Syntyy idea siitä, että _code'n'fix_ -mentaliteetin sijaan ohjelmistojen kehittämisen tulisi olla kuin mikä tahansa muu insinöörityö, eli kuten esim. siltojen rakentamisessa, tulee ensin rakennettava artefakti määritellä (requirements) tarkasti ja suunnitella (design) aukottomasti ja tämän jälkeen rakentaminen (construction) on melko suoraviivainen vaihe.

## Vesiputous- eli lineaarinen malli

Winston Roycen vuonna 1970 julkaisema artikkeli [Management of the development of Large Software](http://www-scf.usc.edu/~csci201/lectures/Lecture11/royce1970.pdf) pohdiskelee isojen ohjelmistojen kehittämiseen liittyvää problematiikkaa. Artikkelin sivulla 2 Royce esittelee yksinkertaisen prosessimallin (eli ohjeiston työvaiheiden jaksottamiseen), jossa ohjelmiston elinkaaren vaiheet suoritetaan lineaarisesti peräkkäin:

![](https://raw.githubusercontent.com/mluukkai/ohjelmistotekniikka-kevat2019/master/web/images/l-1.png)

Roycen versio kuvasta näyttää seuraavalta:

![](https://raw.githubusercontent.com/mluukkai/ohjelmistotuotanto2019/master/images/1-1.png?token=AAD7XYZV2IWJZ3IYM3C6AQC5PYLP2)

Suoraviivainen lineaarinen malli, jota ruvettiin kutsumaan vesiputousmalliksi, saavutti nopeasti suosiota. Malli on monella tapaan järkeenkäypä, ensi kannattaa selvittää mitä ollaan tekemässä ja suunnittelu hoitaa vasta tämän jälkeen. Kun suunnitelma on valmis, voidaan tuote valmistaa ja sen jälkeen testata että se toimii kuiten haluttiin, näinhän toimitaan monella muullakin tuotannon alalla.

Vesiputousmallin suosion taustalla oli osittain se, että Yhdysvaltain puolustusministerö (Department of Defence, DoD) joka oli tuohon aikaan eräs maailman suurimmista ohjelmistojen tilaajista, rupesi vaatimaan kaikilta alihankkijoiltaan prosessin noudattamista (Standardi DoD STD 2167). Muutkin ohjelmistoja tuottaneet tahot ajattelivat, että koska DoD vaatii vesiputousmallia, on se hyvä asia ja tapa kannattaa omaksua itselleen

Vesiputousmalli perustuu vahvasti siihen, että eri vaiheet ovat erillisten tuotantotiimien tekemiä, joukko analyytikkoja miettii asiakkaan kanssa sovellukselle asetetut vaatimuksen, ohjelmistoarkkitehdit saavat vaatimusmääritelmän tuloksen ja suunnittelevat ohjelman sen perusteella. Ohjelmoijat toteuttavat sovelluksen arkkitehtien suunnitelman mukaan ja antavat sen testaajille laadunhallintaa varten. Tämä tuntuu luonnolliselta työnjaolta, kutakin erilaista vaihetta tekee kyseessäolevaan vaiheen työskentelymenetelmiin erikoistunut ihmisjoukko. 

Jotta tieto ohjelmiston eri vaiheiden välillä, tulee kunkin vaiheen tulokset dokumentoida huolellisesti, erityisesti asiakkaan kanssa tehtävän vaatimusmäärittelyn on oltava huolellisesti tehty ja hyvin dokumentoitu, sillä kaikki myöhemmät vaiheet olettavat että vaatimukset on kattavasti ja virheettömästi kirjattu.

Vesiputousmallin mukaisesta toiminnasta käytetään joskus luonnehdintaa _Big Design Up Front_ lyhenteenä BDUF, kuvaamaan sitä faktaa, että koko ohjelmisto määritellään ja suunnitellaan tyhjentävästi ennen ohjelmointivaiheen aloittamista. Termiä BDUF käytetään yleensä negatiivisessa merkityksessä kuvaamaan vesiputousmallin raskautta.

Vesiputousmallin mukainen ohjelmistoprosessi on yleensä tarkkaan etukäteen suunniteltu, resursoitu ja aikataulutettu,
tästä johtuu joskus siitä käytetty nimike _plan based process_, eli suunnitelmavetoinen prosessi.

### Vesiputousmallin ongelmat

Vesiputousmallin mukainen ohjelmistotuotanto siis ei ole osoittautunut erityisen onnistuneeksi. 

Vesiputosusmalli siis olettaa että ohjelmistotuotannon vaiheet tapahtuvat peräkkäin ja jokainen vaihe ainakin isoissa projekteissa eri ihmisten toimesta. Tästä koituu useita ongelmia.

Ongelmista keskeisin on se, että tehtiin vaatimusmäärittely miten huolellisesti tahansa, tulevat vaatimukset kuitenkin melkein varmasti muuttumaan matkan varrella. On osoittautunut, että asiakkaat eivät ohjelmistoja tilatessaan tiedä tai osaa sanoa mitä haluavat tai tarvitsevat. Asiakkaan tarpeet nimittäin saattavat muuttua projektin kuluessa. Kilpailutilanne saattaa vaihtua, tulee uusia lainsäädäntöjä, firmat fuusioituvat, mailman taloussuhtanteet vaihtuvat. Mitä pidempi ohjelmiston kehitysprosessi on, sitä varmampaa on, että vaatimukset elävät. 

On myös kerta toisensa jälkeen nähty se, että asiakas alkaa haluta muutoksia heti kun näkee valmiin lopputuloksen. Koska ohjelmistot ovat abstrakteja tuotteita, on asiakkaiden hyvin vaikea pystyä etukäteen miettimään kaikkea toiminnallisuutta etukäteen sillä tasolla, että se voitaisiin lyödä täysin lukkoon kuten vesiputousmalli olettaa.

Oma riskinsä on myös se, että suunnittelijat tai ohjelmoijat tulkitsevat dokumentoituja asiakkaan vaatimuksia väärällä tavalla, tai asiakas ei ole tullut ymmärretyksi täysin vaatimusten kirjaushetkellä, eli dokumentoidut vaatimukset ovat jo lähtökohtaisesti väärät. 

Vesiputousmallin mukainen vaatimusmäärittelyn, suunnittelun ja toteutuksen erottaminen on käytännössä järjetöntä tai jopa mahdotonta. Valittu ohjelmiston arkkitehtuuri ja käytössä olevat toteutusteknologiat vaikuttavat suuresti määriteltyjen ominaisuuksien hintaan, määritellessä kannattaa siis miettiä myös suunnittelua ja toteutusta, missä muodossa asiakkaan vaatimukset on ylipäätään mahdollista toteuttaa järjevin resurssein. 

Suunnittelun ja toteutuksen eriyttäminenkään ei ole osoittautunut toimivaksi ideaksi. Ohjelmistoja on mahdotonta suunnitella siten, että toteutus on suoraviivainen mekaaninen toimenpide, osa suunnittelusta tapahtuu pakosti vasta ohjelmointivaiheessa.

Vesiputousmalliin perustuvan ohjelmistotuotannon takana on siis pitkälti analogia muihin insinööritieteisiin:
rakennettava artefakti tulee ensin määritellä ja suunnitella (design) aukottomasti, tämän jälkeen rakentaminen (construction) on triviaali vaihe.

> Perinteisesti ohjelmointi on rinnastettu triviaalina pidettyyn "rakentamisvaiheeseen" ja kaiken haasteen on ajateltu olevan määrittelyssä ja suunnittelussa. Tätä rinnastusta on kuitenkin ruvettu kritisoimaan, sillä ohjelmistojen suunnittelu sillä tarkkuudella, että suunnitelma voidaan muuttaa suoraviivaisesti koodiksi on osoittautunut mahdottomaksi.
> 
> Onkin [esitetty](http://www.bleading-edge.com/Publications/C++Journal/Cpjour2.htm) että perinteisen insinööritiedeanalogian triviaali rakennusvaihe ei ohjelmistoprosessissa olekaan ohjelmointi, vaan ohjelmakoodin kääntäminen eli että ohjelmakoodi on itseasiassa ohjelmiston lopullinen suunnitelma siinä mielessä kuin insinööritieteet käsittävät suunnittelun (design).

Vesiputousmallin mukaisessa ohjelmistokehityksessä testaus suoritetaan kun ohjelmisto on valmiina. Vasta lopussa tapahtuva laadunhallinta paljastaa ongelmat kuitenkin aivan liian myöhään. Vikojen korjaaminen saattaa tulla hyvinkin kalliiksi, sillä testaus voi paljastaa ongelmia jotka pakottavat muuttamaan radikaalilla tavalla ohjelmiston rakennetta tai jopa sen vaatimuksia.

Martin Fowlerin artikkeli [The New Methodology]( http://martinfowler.com/articles/newMethodology.html) käsittelee laajalti lineaarisen mallin ongelmia.

### Royce ja vesiputousmalli

Paradoksaalista kyllä vesiputousmallin isänä pidetty Royce ei suosittele artikkelissaan suoraviivaisen lineaarisen mallin käyttöä. Royce kyllä esittelee lineaarisen vesiputousmallin artikkelin sivulla 2, mutta toteaa että se _ei sovellu_ monimutkaisten ohjelmistoprojektien tekotavaksi.

Roycen mukaan sovelluksesta tulee ensin tehdä prototyyppi ja vasta siitä saatujen kokemusten valossa kannattaa suunnitella ja toteuttaa lopullinen ohjelmisto. Royce esitteleekin artikkelin loppupuolella mallin, missä ohjelmisto tehdään kahdessa iteraatiossa, kuva Roycen artikkelista

![](https://raw.githubusercontent.com/mluukkai/ohjelmistotuotanto2019/master/images/1-3.png?token=AAD7XYZASQIRBBG4DNPKH6C5PZOXI)

Vesiputousmalli tai ainakin Roycen nimeäminen vesiputousmallin isäksi on siis iso väärinymmärrys, onneksi Roycen artikkeli on nykyään helposti saatavilla internetissä.

## Iteratiivinen ja inkrementaalinen ohjelmistokehitys

Lineaarisen mallin ongelmiin reagoinut _iteratiivinen_ tapa tehdä ohjelmistoja alkoi yleistyä 90-luvulla (mm. spiraalimalli, prototyyppimalli, Rational Unified process.

Iteratiivisessa mallissa ohjelmistotuotanto jaetaan pienempiin aikaväleihin, eli iteraatioihin. Toisin kuin vesiputousmallin mukaisessa ohjelmistotuotannossa, iteratiivisesti edetessä ei pyritä tekemään heti alussa kattavaa määrittelyä ja suunnittelua.

Jokaisen iteraation aikana määritellään, suunnitellaan toteutetaan ja testataan ohjelmistoa, eli ohjelmisto kehittyy vähitellen. Ohjelma valmistuu siis pala palalta, tämän takia iteratiivisten menetelmien sanotaan olevan myös _inkrementaalisia_.

Asiakasta tavataan jokaisen iteraation välissä, asiakas näkee sen hetkisen version ohjelmasta ja pystyy vaikuttamaan seuraavien iteraatioiden kulkuun. Ohjelmiston iinkrementaalisen kasvamisen takia sen perusversio on mahdollista saada loppukäyttäjien käyttöönkin vielä kehitystyön kuluessa.

![](https://raw.githubusercontent.com/mluukkai/ohjelmistotuotanto2019/master/images/1-4.png?token=AAD7XY7336DQD2D7CFRM3SC5PZP52)

Vesiputousmallin "isä" Royce suositteli siis jo vuonna juurikin iteratiivista (kahden iteraation versiota) tapaa monimutkaisten ohjelmistojen kehitysmalliksi. Roycen ehdottama menetelmä ei oikeastaan ollut inkrementaalinen, sillä ensimmäisen iteraation aikana rakennettiin ainoastaan prototyyppi, jonka pohjalta varsinainen sovellus määriteltiin, suunniteltiin ja toteutetiin.

Yhdysvaltojen puolustusministeriön vuonna 2000 julkaisema standardi (MIL-STD-498) alkoi suosittelemaan iteratiivista ohjelmistoprosessia:

> There are two approaches, evolutionary (iterative) and single step (waterfall), to full capability. An evolutionary approach is preferred. ... In this approach, the ultimate capability delivered to the user is divided into two or more blocks, with increasing increments of capability...software development shall follow an iterative spiral development process in which continually expanding software versions are based on learning from earlier development. It can also be done in phases

Itseasiassa iteratiivinen ohjelmistokehitys on paljon vanhempi idea kun lineaarinen malli. Esimerkiksi NASA:n ensimmäisen Amerikkalaisen avaruuteen vieneen Project Mercuryn ohjelmisto kehitettiin 50-luvun lopussa iteratiivisesti. Avaruussukkuloiden ohjelmisto tehtiin vesiputousmallin valtakaudella 70-luvun lopussa, mutta sekin kehitetiin lopulta iteratiivista prosessia käyttäen 8 viikon iteraatioissa, 31 kuukauden aikana. Lisää aiheesta Larmanin ja Basilin erinomaisessa artikkelissa [incremental and iterative development, a brief history](http://www.craiglarman.com/wiki/downloads/misc/history-of-iterative-larman-and-basili-ieee-computer.pdf)

## Ketterä ohjelmistokehitys

1980- ja 1990-luvun prosessimalleissa korostettiin huolellista projektisuunnittelua, formaalia laadunvalvontaa, yksityiskohtaisia analyysi- ja suunnittelumenetelmiä ja täsmällistä, tarkasti ohjattua ohjelmistoprosessia. Prosessimallit tukivat erityisesti laajojen, pitkäikäisten ohjelmistojen kehitystyötä, mutta pienten ja keskisuurten ohjelmistojen tekoon ne osoittautuivat usein turhan jäykiksi.

Perinteisissä prosessimalleissa (myös iteratiivisissa) on pyritty työtä tekevän yksilön merkityksen minimoimiseen. Ajatuksena on ollut että yksilö on "tehdastyöläinen", joka voidaan helposti korvata toisella ja tällä ei ole ohjelmistoprosessin etenemiselle mitään vaikutusta.

Ristiriidan seurauksena syntyi joukko ketteriä menetelmiä (agile methods), jotka korostivat itse ohjelmistoa sekä ohjelmiston asiakkaan ja toteuttajien merkitystä yksityiskohtaisen suunnittelun ja dokumentaation sijaan.

### Ketterä manifesto

17 ketterien menetelmien pioneeria kerääntyi helmikuussa 2001 kokoukseen, jonka tuloksena oli [Agile manifesto](http://agilemanifesto.org/), eli näkemys siitä mitä ketterällä ohjelmistokehityksellä tarkoitetaan.

Manifesto on käänneetty monelle kielelle, myös [suomeksi](https://agilemanifesto.org/iso/fi/manifesto.html), mutta tarkastellaan sen englanninkielistä versiota:

We are uncovering better ways of developing software by doing it and helping others do it. Through this work we have come to value:

- _Individuals and interactions_ over processes and tools 
- _Working software_ over comprehensive documentation 
- _Customer collaboration_ over contract negotiation 
- _Responding to change_ over following a plan

That is, while there is value in the items on the right, we value the items on the left more.

Manifesti siis koostuu neljstä vastakkainasettelun sisältäväst kohdasta, jotka ilmaisevat mikä on ketterien menetelmien näkemyksen mukaan oleellisinta ohjelmistokehityksessä. Ensimmäinen kohta sanoo, että erilaiset työkalut ja prosessit voivat olla tärkeää, mutta _vielä tärkeämpää_ ovat ohjelmiston kehittäjät, käyttäjät, tilaajat ja heidän välinen interaktio. Toinen kohta taas ei kiellä dokumentaation tärkeyttä, mutta sanoo että lopulta tärkeintä on toimiva ohjelmisto. Ketterä manifesti ei siis kiellä tai pidä arvottomana "vanhan maailman" tärkeänä pitämiä asioita kuten _suunnitelman noudattamista_, mutta osoittaa, että niitäkin oleellisimpia seikkoja on, kuten _muutokseen reagoiminen_.

Manifestin [laatijoiden joukko](https://agilemanifesto.org/authors.html) koostuu monesta tutusta ja vaikutusvaltaisesta nimestä, kuten Kent Beck, Robert Martin, Ken Schwaber, Martin Fowler ja Alistair Coburn, jotka ovat vaikuttaneet merkittävästi nykyiseen vallitsevaan ohjelmistokehityksen tapaan.

### Ketterät periaatteet

Manifesti sisältää yllä olevan lisäksi 12 ketterää periaatetta. Käydään periaatteet nyt läpi ja pohdiskellaan hieman niiden taustalla olevia ajatuksia.

Aloitetan kolmesta 

_Our highest priority is to satisfy the customer through early and continuous delivery of valuable software._

_Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale._

_Working software is the primary measure of progress._

Oleellisinta kaikesta ja mittarina projektin edistymiselle on toimintakelpoisen, arvoa tuottavan ohjelmiston toimittaminen asiakkaalle. Toisin kuin vesiputousmallissa, aloitetaan valmiiden ohjelmistofeatureiden toimittaminen jo aikaisessa vaiheessa ja sitä tehdään toistuvasti tiheähkösti iteroiden. Manifesti puhuu _from couple of weeks to couple of months_, nykyään ideaali on vieläkin tiheämpi toimitusväli, jopa useiden sovelluksen versioiden julkaisu päivässä. 

_Business people and developers must work together daily throughout the project._

_The most efficient and effective method of conveying information to and within a development team is face-to-face conversation._

_Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage._

Vesiputousmallissa fundamentaalina periaattena oli se, että ohjelmiston valmistaminen alkaa kattavalla vaatimusmäärittelyllä, jonka aikana asiakkaan vaatimukset selvitetään, dokumentoidan huolellisesti ja "jäädytetään", eli vaatimuksiin ei sen koommin edes sallita muutoksia. Asiakas on seuraavan kerran mukana kehitystyössä ehkä vasta lopussa tekemässä hyväksymistestausta.

Ketterän manifestin periaatteet ovat täysin päinvastaiset. Asiakkaiden ja sovelluskehittäjien oletetaan toimivan koko ohejlmiston kehityskaaren tiiviissä, jopa päivittäisessä yhteistyössä. Kommunikointi pyritään hoitamaan raskaan dokumentaation sijaan jopa keskustellen. Myös suhtautuminen vaatimusmäärittelyyn on mennyt päälaelleen. Asiakas saa vaihtaa vaatimuksiaan kesken ohjelmistokehityksen, ja siihen jopa rohkaistaan, jos muuttuneen vaatimusmäärittelyn avulla asiakas pystyy saamaan itselleen etua aikaan. 

> Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.

> The best architectures, requirements, and designs emerge from self-organizing teams.

Ketterät periaatteet luottavat siihen, että kun ohjelmistokehittäjille annetaan sopiva työskentely-ympäristö, he tekevät parhaansa toimittaakseen asiakkaalle arvokkaan sovelluksen ilman tarvetta ulkoiselle kontrolloinnille. Ei ole tarvetta myöskään erillisille vaatimuksia keräävän analyytikon tai suunnittelusta huolehtivan ohjelmistoarkkitehdin rooleille, softatiimit osaavat toimia parhaiten itseorganisoitumalla, eli päättämällä itse toimintamenetelmistään.

> At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

Aiemmin mainittu periaate _Welcome changing requirements..._ siis kuvailee, että ketterä mahdollistaa ja suorastaan kannustaa tuotteen kehityssuunnan muuttamisen uusien tarpeiden ilmetessä. Vastaavasti kehitystiimin odotetaan tarkastelevan omaa toimintaansa ja muokkaamaan sitä jatkuvasti parempaan suuntaan.

> Simplicity – the art of maximizing the amount of work not done – is essential.

Vesiputousmalli ja muut vanhemmat kehitysmenetelmät antoivat suuren painoarvon dokumentaatiolle ja erilaisille "prosessin määräämille" raporteille, joihin käytettiin paljon aikaa ja vaivaa, ilman että ne olisivat kuitenkaan kovin paljoa edistäneet itse tuotteen valmistumista. Ketteräissä menetelmissä ideana on eliminoida mahdollisimman pitkälle kaikki mikä ei ole primääristen tavoitteiden kannalta oleellista (_Working software is the primary measure of progress_). Myös ohjelmistokehittäjllä on pyrkimys rakentaa ohjelmistoon tulevaisuuden varalta kaikenlaista ekstraa, myös tälläiseen tulisi ketterässä hengessä suhtautua kriittisesti. 

Viimeiset kaksi periaatetta ovat ne, jotka tahtovat useimmiten unohtua:

> Continuous attention to technical excellence and good design enhances agility.

> Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.

Ketteryys edellyttää että tiimi pystyy muuttamaan tarvittaessa sovelluskehityksen suuntaa uusien tarpeiden noustessa esiin. Tämä taas edellyttää, että tiimin on ylläpidettävä ohjelmiston laatua riittävällä tasolla, jos nimittäin sovellus on sisäiseltä rakenteeltaan huono purkkaviritys, on siitä koko ajan vaikeampi laajentaa uusilla toiminnallisuuksilla, erityisesti sellaisilla, joiden tarvetta ei aiemmin ehkä osattu ennakoida. Eli jos laatuun ei kiinnitetä riittävää huomiota, ketteryys menetetään, ja sovelluksen kehitys muuttuu erittäin hitaaksi.

## Ketterät menetelmät ja Lean

Ketterät menetelmät on sateenvarjotermi useille ketterille menetelmille. 2000 luvun alkupuolella [Extreme programming](http://www.extremeprogramming.org/) eli XP oli ketteristä menetelmistä suosituin. Nykyään harva enää soveltaa "oppikirjamaista" XP:tä, mutta runsaasti sen käytänteistä on jäänyt elämään ja omaksuttu monien softatiimien työkalupakkiin. Tutustumme moniin XP:n käytänteisiin kurssin aikana.

XP:ltä valta-aseman otti pikkuhijaa [Scrum](https://www.scrum.org/), joka lienee tällä hetkellä maailman eniten käytetty ohjelmistokehitysmenetelmä. Tutustumme Scrumiin tarakemmin seuraavassa luvussa.

Ketterä ohjelmistotuotanto on ottanut runsaasti vaikutteita [Toyota production systemin](https://global.toyota/en/company/vision-and-philosophy/production-system/) taustalla olevasta _lean_-ajattelusta. Viime vuosina termi lean on alkanut näkyä yhä tiiviimmin termin agile rinnalla tai sijasta ohjelmistokehityksestä puhuttaessa. Leanista peräisin olevaa [kanbania](https://fi.wikipedia.org/wiki/Kanban) on ruvettu soveltamaan runsaasti ohjelmistokehitykseen, usein se täydentää jotain ketterää menetelmää kuten Scrumia. Kanbanin ja Scrumin yhdistelmä kulkeekin nimellä [Scrumban](https://www.amazon.com/exec/obidos/ASIN/0321150783/poppendieckco-20). Palaamme Leaniin tarkemin kurssin osassa 8.

Ketterät menetelmät on alun perin suunniteltu yksittäisen, pienehköjen ohjelmistotiimien hallintaan. Viime aikoina ketterille menetelmille on hahmoteltu useitakin laajennuksia mm. [SaFe](https://www.scaledagileframework.com/) ja [Less](https://less.works/), joiden avulla on mahdollista hallinnoida useista ohjelmistotiimeistä koostuvia kokonaisuuksia. Ketterien periaatteiden lisäksi nämä laajemman skaalan kehitysmenetelmän nojaavat voimakkaasti leanin tarjoamiin periaatteisiin. Palaamme asiaan kurssin yhdekäsnnessä osassa.
