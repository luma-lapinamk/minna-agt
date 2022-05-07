# Polynomit

## Määritelmä

Polynomi on lauseke, jossa on termejä ja termien välisiä yhteenlaskuja. Polynomin termit sisältävät numerokertoimia (kerroinosa) ja kirjaimilla merkittyjä lukuja ja niiden potensseja (kirjainosa). Kirjaimia polynomissa voi olla yhtä tai useampaa erilaista.

**Esim.** $a+2-5a^3$ on polynomi, jonka termit ovat $a$, $2$ ja $-5a^3$ (viimeisen termin kerroin on $-5$ ja kirjainosa $a^3$).

**Esim.** $3x+5y^2-2y$ on polynomi, jonka termit ovat $3x$, $5y^2$ ja $-2y$.

:::{admonition} Näkymättömät kertoimet ja kirjaimet
:class: tip, dropdown
Periaatteessa jokaisessa polynomin termissä on sekä kerroin- että kirjainosa. 

- Jos numeroa ei näy, kerroinosa on $1$. Esimerkiksi $1\cdot x$ on sama asia kuin $x$. Jos termi on $-x$, niin kerroinosa on $-1$.

- Jos kirjainta ei näy, niin kirjainosa on muotoa $x^0$. Potenssilukujen laskusääntöjen mukaanhan $a^0=1$. 

Kirjainosan eksponenttia $1$ ei yleensä merkitä näkyviin, sillä mille tahansa luvulle $a$ pätee $a^1=1$. Niinpä esimerkiksi polynomi $x+2$ voitaisiin esittää myös muodossa $1\cdot x^1+2\cdot x^0$. 

Lisäksi polynomin voi ajatella koostuvan pelkästään yhteenlaskuista. Jos polynomissa on termi, jossa on miinusmerkkinen kerroin, voidaan ajatella että yhteenlaskussa vain on mukana negatiivinen luku. Esimerkiksi $3x^2-4x$ on siis sama asia kuin $3x^2+(-4x)$.
:::

Termit ovat samanmuotoisia, jos niissä on sama kirjainosa. Niissä on oltava saman kirjain ja sama eksponentti.

**Esim.** Polynomissa $5x^3+2y+3x-y^2$ ei ole samanmuotoisia termejä.

**Esim.** Polynomissa $5x^3+2y-3x^3-y$ on samanmuotoisia termejä: $5x^3$ ja $-3x^3$ ovat keskenään samanmuotoisia, ja $2y$ ja $-y$ keskenään samanmuotoisia.

## Polynomien sieventäminen

Polynomien sieventäminen tarkoittaa polynomin esittämistä mahdollisimman yksinkertaisessa muodossa. Sieventäminen helpottaa esimerkiksi yhtälöiden käsittelyä. Sieventäminen auttaa myös silloin, kun monimutkaisia yhtälöitä annetaan tietokoneen käsiteltäväksi.

:::{admonition} Jokainen laskutoimitus vie aikaa
:class: tip, dropdown
Vaativassa numeerisessa laskennassa ja data-analytiikassa lausekkeiden esitysmuoto saattaa vaikuttaa merkittävästi aikaan, joka tietokoneelta kuluu ongelman ratkaisuun. Jokainen laskutoimitushan vie tietokoneelta tietyn ajan. Esimerkiksi laskutoimitus $2x+x$ vaatii yhden kerto- ja yhden yhteenlaskun, kun taas saman ongelman esittäminen muodossa $3x$ vie aikaa vain yhden kertolaskun verran. Kun tietokone esimerkiksi etsii usealle muuttujalle arvoja, joilla saadaan laskutoimitukselle - esimerkiksi tehtaan valmistaman uuden tuotteen tuottamalle voitolle - suurin mahdollinen tulos, laskuun voi kulua tuntikausia. Tällöin olisi hyvä, ettei tietokone turhaan laske ylimääräisiä välivaiheita huonosti sievennetyn lausekkeen takia!
:::

### Samanmuotoisten termien yhdistäminen

Samanmuotoisten termien kertoimet voi laskea yhteen, jolloin lauseke sieventyy huomattavasti. Samanmuotoisia termejä yhdistetään myös silloin, kun kaksi polynomia lasketaan yhteen tai vähennetään toisistaan.

**Esim.** Yhdistä samanmuotoiset termit:

a) $2m-n+5m+4n$, b) $x^2+4x-2x^2-2x$

:::{admonition} Ratkaisu
:class: tip, dropdown

a) $2m-n+5m+4n=(2+5)m+(-1+4)n=7m+3n$

b) $x^2+4x-2x^2-2x=(1-2)x^2+(4-2)x=-x^2+2x$

:::

**Esim.** Laske polynomien summa tai erotus:

a) $(3x^2-5x+2)+(4x-1)$

b) $(2x^3+x-1)-(x^2+3x-4)$

:::{admonition} Ratkaisu
:class: tip, dropdown

a) $(3x^2-5x+2)+(4x-1) = $

$ 3x^2-5x+2+4x-1= $

$ 3x^2+(-5+4)x+(2-1) = $

$3x^2-x+1$

b) $(2x^3+x-1)-(x^2+3x-4)= $

$2x^3+x-1-x^2-3x-(-4)=$

$2x^3+x-1-x^2-3x+4=$

$2x^3-x^2+(1-3)x+(-1+4)=$

$2x^3-x^2-2x-3$

:::

### Polynomien kertolasku

Polynomien kertolaskussa polynomin jokainen termi kerrotaan luvulla (tai lausekkeella) erikseen ja tulot lasketaan yhteen.

**Esim.** $3(5x+4y-5z)=3\cdot 5x+3\cdot 4y+3\cdot (-5z)=15x+12y-15z$

**Esim.** $(a+2)(a^2+1)=a(a^2+1)+2(a^2+1)=$

$a\cdot a^2+a\cdot 1+2\cdot a^2+2\cdot 1=a^3+a+2a^2+2$

**Esim.** $(x+y)(3+z)=3x+xz+3y+yz$

**Esim.** $(x-2)(y+1)=xy+x\cdot 1-2y-2 = xy+x-2y-2$

**Binomikaavat** 

Polynomien kertolaskun erikoistapauksina saadaan kolme muistisääntöä, ns. binomikaavat:

1. Summan neliö: $(a+b)^2=a^2+2ab+b^2$

2. Erotuksen neliö: $(a-b)^2=a^2-2ab+b^2$

3. Summan ja erotuksen tulo: $(a+b)(a-b)=a^2-b^2$

Kaavoissa a ja b voivat olla lukuja, kirjaimia tai lausekkeita. 

:::{admonition} Binomikaavojen perustelu
:class: tip, dropdown
Binomikaavat voidaan perustella suoraan laskemalla.

Summan neliö: 

$(a+b)^2=(a+b)(a+b)= $

$a(a+b)+b(a+b)=a^2+ab+ba+b^2=a^2+2ab+b^2$

Erotuksen neliö: 

$(a-b)^2=(a-b)(a-b)= $

$ a(a-b)-b(a-b)=a^2-ab-ab+b^2=a^2-2ab+b^2$

Summan ja erotuksen tulo: 

$(a+b)(a-b)=a(a-b)+b(a-b)=a^2-ab+ab-b^2=a^2-b^2$
:::
 
**Esim.** Sievennä binomikaavojen avulla:

a) $(x+3)^2$

b) $(x+5)(x-5)$

c) $(3x+1)^2$

d) $(x-3)^2$

:::{admonition} Ratkaisu
:class: tip, dropdown

a) $(x+3)^2=x^2+2\cdot x \cdot 3+3^2=x^2+6x+9$

b) $(x+5)(x-5)=x^2-5^2=x^2-25$

c) $(3x+1)^2=(3x)^2+2\cdot 3x\cdot 1+1^2=9x^2+6x+1$

d) $(x-3)^2=x^2-2\cdot x \cdot 3+3^2=x^2-6x+9$

:::

:::{admonition} Binomikaavojen käyttö takaperin
:class: tip, dropdown
Binomikaavoja voi käyttää myös toiseen suuntaan, eli muuttamaan polynomin joko summan tai erotuksen neliöksi, tai summan ja erotuksen tuloksi. Tätä tarvitaan esimerkiksi silloin, kun johdetaan ratkaisukaava toisen asteen yhtälölle.

Geometriassa taas on joskus tarvetta esittää muotoja yhtälöinä. Esimerkiksi ympyrä, jonka keskipiste on $xy$-koordinaatiston piste $(x_0,y_0)$ ja säde $r$, voidaan esittää muodossa $(x-x_0)^2+(y-y_0)^2=r^2$. Binomikaavoja takaperin hyödyntämällä voidaan esimerkiksi huomata, että yhtälö $x^2 - 6 x + y^2 - 8 y = 0$ esittää ympyrää, jonka keskipiste on (3,4) ja säde 5.
:::

### Yhteisen tekijän erottaminen

Usein on hyödyllistä muuttaa polynomi kertolaskuksi. Tätä varten polynomille pitää etsiä yhteinen tekijä eli kerroin, joka koskee kaikkia polynomin termejä. Yhteinen tekijä voi olla luku, kirjain tai monimutkaisempi lauseke. Yhteinen tekijä voi olla jokin seuraavista:
- lukua 1 suurempi kerroin, jolla polynomin jokainen termi on jaollinen
- kirjain, joka esiintyy jokaisessa polynomin termissä, korotettuna pienintä polynomissa esiintyvää eksponenttia vastaavaan potenssiin
- edellisten yhdistelmä.

Joskus polynomissa ei ole sellaista lukua, joka täyttäisi minkään edellisistä ehdoista. Kun yhteinen tekijä on tunnistettu, se erotetaan kertoimeksi koko polynomin eteen, ja polynomi kirjoitetaan perään suluissa ilman yhteistä tekijää. Suluissa olevan osan saa muodostettua jakamalla polynomin jokaisen termin yhteisellä tekijällä. 

**Esim.** Erota yhteinen tekijä.

a) $2x^3+4x^2-2x+8$ 

b) $3x^4+x^2+2x$

c) $-6x^3+12x^2-3x$

d) $2x^2+5x-3$

:::{admonition} Ratkaisu
:class: tip, dropdown

a) Jokaisen termin kerroin on jaollinen luvulla 2. Tällöin kertolaskuna kirjoitettu polynomi on

$2(\frac{2x^3}{2}+\frac{4x^2}{2}-\frac{2x}{2}+\frac{8}{2})$, 
joka sievenee muotoon $2(2x^3+2x^2-x+4)$.

b) Jokaisessa termissä on kirjain $x$. Yhteiseksi tekijäksi valitaan kirjainosista $x^4$, $x^2$ ja $x$ se, jossa on pienin eksponentti, siis tässä tapauksessa $x$. Kertolaskuna polynomi on siis

$x(\frac{3x^4}{x}+\frac{x^2}{x}+\frac{2x}{x})$ 
eli $x(3x^3+x+2)$.

c) Polynomin kaikki kertoimet ovat jaollisia luvulla 3. Lisäksi jokaisessa termissä esiintyy kirjain $x$ siten, että termi, jonka eksponentti on pienin, on $x$. Valitaan yhteiseksi tekijäksi tulo $3x$. Tällöin polynomi on kertolaskuna

$3x(-\frac{6x^3}{3x}+\frac{12x^2}{3x}-\frac{3x}{3x})=3x(2x^2+4x-1)$.

d) Ei ole lukua, jolla kaikki polynomin kertoimet voitaisiin jakaa. Kirjainta $x$ ei esiinny kaikissa polynomin termeissä. Tätä polynomia ei voi muuttaa kertolaskumuotoon.

:::
