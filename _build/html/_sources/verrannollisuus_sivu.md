<!-- #region -->
# Suoraan ja kääntäen verrannollisuus

Verrannollisuus on käsite, jonka avulla voidaan vastata esimerkiksi seuraavanlaisiin kysymyksiin:

a) Kolme kiloa mangoja maksaa 6.90 €. Paljonko maksaa viisi kiloa samoja mangoja?

b) Säiliön tyhjentäminen kestää 4 h ja 30 min, kun tyhjennyspumpun teho on 200 l/min. Kauanko tyhjentäminen kestää pumpulla, jonka teho on 120 l/min?

Lisäksi verrannollisuutta tarvitaan mittakaavoissa (kartat, pienoismallit). 

Verrannossa on kaksi toisistaan riippuvaa asiaa. Niitä merkitään usein kirjaimilla $x$ ja $y$. Muuttujat $x$ ja $y$ voivat riippua toisistaan kahdella eri tavalla: 

- Kun $x$ kasvaa, niin myös $y$ kasvaa. Tällöin kyseessä on suoraan verrannollisuus. Esimerkiksi kilohinnalla ostettujen hedelmien kokonaishinta $y$ varmasti kasvaa, jos ostettujen hedelmien määrä $x$ kasvaa.

- Kun $x$ kasvaa, niin $y$ pienenee. Tällöin kyseessä on kääntäen verrannollisuus. Esimerkiksi jos säiliötä tyhjentävän pumpun teho $x$ kasvaa, niin säiliön tyhjentämiseen kuluva aika $y$ pienenee.

 
## Suoraan verrannollisuus

Suoraan verrannollisten muuttujien $x$ ja $y$ välinen riippuvuus on muotoa $y=kx^n$, missä luku $k$ on nimeltään verrannollisuuskerroin ja $n$ on jokin positiivinen kokonaisluku. Kun $x$ kasvaa, myös $y$ kasvaa. Esimerkiksi jos riippuvuus on muotoa $y=3x$, niin verrannollisuuskerroin on $3$, ja arvot riippuvat toisistaan seuraavasti: $x=1 \rightarrow y=3, x=2 \rightarrow y=6, x=3 \rightarrow y=9, \ldots$.

### Riippuvuus muotoa $y=kx$

Yksinkertaisimmassa tapauksessa muuttujen $x$ eksponentti on 1. Tällöin yhtälö on muotoa $y=kx$. 

Verrannollisuuskerrointa $k$ ei välttämättä suoraan tiedetä. Se voidaan kuitenkin ratkaista yhtälöstä $y=kx$, siis $k=\frac{y}{x}$. 

Ongelmien ratkaisussa hyödynnetään tietoa, että $k$ on sama kaikille lukupareille $(x,y)$. Niinpä jos tiedetään yksi lukupari $(x_1,y_1)$, voidaan sen avulla selvittää ensin verrannollisuuskerroin $k$ yhtälöstä $y_1=k x_1$. Sen jälkeen voidaan toisesta lukuparista ratkaista $(x_2,y_2)$ jompikumpi muuttujista $x_2$ tai $y_2$ hyödyntämällä yhtälöä $y_2=k x_2$.

Samantyyppinen ongelma voidaan ratkaista myös yhtälönä. Merkitään jälleen kahteen eri tilanteeseen liittyviä suureita $x$ ja $y$ alaindekseillä $(x_1,y_1)$ ja $(x_2,y_2)$. Koska verrannollisuuskerroin on $k=\frac{y}{x}$ riippumatta $x$:n ja $y$:n arvoista, voidaan kirjoittaa $k=\frac{y_1}{x_1}$ ja $k=\frac{y_2}{x_2}$ ja edelleen $\frac{y_1}{x_1} = \frac{y_2}{x_2}$. Tähän yhtälöön voidaan sijoittaa tunnetut suureiden arvot ja ratkaista tuntematon. 

**Esim.** Eräässä kerrostalossa 80 neliömetrin kokoinen asunto maksaa 160 000 €. Oletetaan, että asunnon hinta $y$ on suoraan verrannollinen asunnon kokoon $x$. Kuinka paljon maksaisi 120 neliömetrin kokoinen asunto?

:::{admonition} Ratkaisu
:class: tip, dropdown

Koska asunnon hinta oletettavasti on sitä suurempi, mitä suurempi on asunnon koko, niin kyseessä ovat suoraan verrannolliset suureet. Tällöin asunnon hinta riippuu asunnon koosta yhtälön $y=kx$ mukaisesti.

Ongelma voidaan ratkaista kahdella tavalla:

(1) Selvitetään verrannollisuuskerroin $k$ tiedossa olevien suureiden avulla: $k=\frac{y}{x}=\frac{160000~€}{80~\text{m}^2}=2000~\text{€/m}^2$.

Nyt voidaan laskea toisen asunnon hinta sijoittamalla asunnon pinta-ala yhtälöön $y=2000~\text{€/m}^2\cdot x$, siis
$y=2000~\text{€/m}^2\cdot 120~\text{m}^2=240000~€$.

(2) Merkitään tunnetun asunnon kokoa $x_1=80~\text{m}^2$ ja hintaa $y_1=160000~€$. Toisen asunnon koko on $x_2=120~\text{m}^2$ ja hinta tuntematon $y_2$. Ratkaistaan $y_2$ yhtälöstä $\frac{y_1}{x_1} = \frac{y_2}{x_2}$:

$\frac{y_1}{x_1} = \frac{y_2}{x_2}$

$y_2=\frac{x_2}{x_1} y_1$

$y_2=\frac{120~\text{m}^2}{80~\text{m}^2}\cdot 160000~€$

$y_2 = 240000~€$.
:::

### Riippuvuus muotoa $y=kx^n, n > 1$

Vaikka muuttujan $x$ eksponentti $n$ olisi jokin lukua 1 suurempi luku, edelleen verrannollisuuskerroin $k$ pysyy samana, ja ongelmien ratkaisu tapahtuu samalla periaatteella kuin edellä. Verrannollisuuskerroin voidaan laskea $k=\frac{y}{x^n}$. Vastaavasti voidaan ratkaista tuntematon muuttuja yhtälöstä $\frac{y_1}{x_1^n}=\frac{y_2}{x_2^n}$.

**Esim.** Auton jarrutusmatka pysähdykseen saakka riippuu olosuhteista, mutta on suoraan verrannollinen nopeuden toiseen potenssiin. Eräällä tiellä jarrutusmatkaksi nopeudesta 40 km/h todettiin 16 m. Kuinka pitkä on jarrutusmatka samalla tiellä, jos alkunopeus onkin 70 km/h?

:::{admonition} Ratkaisu
:class: tip, dropdown

Nopeus tunnetussa tilanteessa on $x_1=40$ km/h ja jarrutusmatka $y_1=16$ metriä. Toisessa tilanteessa nopeus on $x_2=70$ km/h ja jarrutusmatka tuntematon $y_2$. Ratkaistaan $y_2$ yhtälöstä $\frac{y_1}{x_1^2}=\frac{y_2}{x_2^2}$:

$y_2=y_1 \frac{x_2^2}{x_1}^2= 16~\text{m}\cdot\frac{70^2}{40^2} = 49~\text{m}$.

Huomaa, että nopeuden yksikkö km/h on jätetty pois, sillä se supistuu pois, kunhan vain kumpikin nopeus on ilmoitettu samassa yksikössä. Fysiikan tehtävissä nopeudet yleensä muutetaan muotoon m/s, jolloin voidaan käyttää monia muitakin laskukaavoja. Tässä tapauksessa kuitenkin riittää tarkastella nopeuksien suhdetta, ja se on sama riippumatta siitä, missä yksikössä nopeudet on ilmaistu.

:::

**Esim.** Auton jarrutusjäljet olivat 32 metriä pitkät. Samoissa olosuhteissa todettiin, että jarrutusmatka nopeudesta 60 km/h on 22 metriä. Mikä oli jarrutusjäljet jättäneen auton nopeus ennen jarrutusta?

:::{admonition} Ratkaisu
:class: tip, dropdown

Nyt nopeus tunnetussa tilanteessa on $x_1=60$ km/h ja jarrutusmatka $y_1=22$ metriä. Toisessa tilanteessa nopeus on $x_2$ on tuntematon ja jarrutusmatka on $y_2=32$ metriä. Ratkaistaan $x_2$ yhtälöstä $\frac{y_1}{x_1^2}=\frac{y_2}{x_2^2}$:

$x_2^2=x_1^2\frac{y_2}{y_1}$

$x_2=\sqrt{x_1^2\frac{y_2}{y_1}}$

$x_2=\sqrt{(60~\text{km/h})^2 \cdot \frac{32~\text{m}}{22~\text{m}}}$ 

$x_2 \approx 72~\text{km/h}$.

:::

 
## Kääntäen verrannollisuus

Kääntäen verrannollisten muuttujien suhdetta kuvaava yhtälö on $y=\frac{k}{x^n}$. Kun $x$ kasvaa, niin $y$ pienenee. Esimerkiksi jos riippuvuus on muotoa $y=\frac{120}{x}$, niin arvot riippuvat toisistaan seuraavasti: $x=1 \rightarrow y=120, x=2 \rightarrow y=60, x=3 \rightarrow y=40, \ldots$. Ongelmat ratkeavat samaan tapaan kuin suoraan verrannollisuudessa, eli kirjoittamalla yhtälö, joka yhdistää lukuparit $(x_1,y_1)$ ja $(x_2,y_2)$ verrannollisuuskertoimen $k$ avulla.


### Riippuvuus muotoa $y=\frac{k}{x}$

Yksinkertaisimmassa tapauksessa kääntäen verrannollisia suureita yhdistää yhtälö $y=\frac{k}{x}$. Tällöin verrannollisuuskertoimeksi saadaan $k=yx$. Lukupareille $(x_1,y_1)$ ja $(x_2,y_2)$ pätee siis yhtälö $x_1 y_1 = x_2 y_2$.

**Esim.** Neljä henkilöä tekee työn 6 tunnissa. Paljonko aikaa kuluu kolmelta henkilöltä saman työn tekemiseen? 

:::{admonition} Ratkaisu
:class: tip, dropdown

Merkitään työntekijöiden määrää $x$ ja työhön kuluvaa aikaa $y$. Kun työntekijöiden määrä kasvaa, niin työhön kuluva aika pienenee. Aika riippuu siis henkilömäärästä yhtälön $y=\frac{k}{x}$ mukaisesti.

Verrannollisuuskerroin on tässä tapauksessa $k=xy=4~\text{hlö}\cdot 6~\text{h}=24~\text{hlö}\cdot\text{h}$. Nyt voidaan sijoittaa verrannollisuuskertoimen arvo ja uusi henkilömäärä 3 yhtälöön $y=\frac{k}{x}$: 

$y=\frac{24 \text{hlö}\cdot\text{h}}{3~\text{hlö}}=8~\text{h}$.

Toinen vaihtoehto on ratkaista yhtälö $x_1 y_1 = x_2 y_2$, missä tunnetut lukuarvot ovat $x_1=4$, $y_1=6$ ja $x_2=3$. Tuntematon aika $y_2$ on 

$y_2=y_1\frac{x_1}{x_2}=6~\text{h}\frac{4~\text{hlö}}{3\text{hlö}}=8~\text{h}$.

:::

**Esim.** Uima-altaan täyttö pumppausnopeudella $x_1=120$ l/min kestää $y_1=4$ h. Kuinka kauan täyttäminen kestää pumpulla, jonka nopeus on $x_2=210$ l/min?

:::{admonition} Ratkaisu
:class: tip, dropdown

Ratkaistaan tuntematon täyttöaika $y_2$ yhtälöstä $y_1 x_1=y_2 x_2$:

$y_2 x_2=y_1 x_1 \leftrightarrow  y_2= y_1 \frac{x_1}{x_2}$

Sijoitetaan luvut: $y_2 = 4~\text{h}\cdot \frac{120~\text{l/min}}{210~\text{l/min}}\approx 2.3~\text{h}=2~\text{h} ~18~\text{min}$.

Lopuksi voidaan laskea verrannollisuuskerroin, joka kuvaa uima-altaassa olevaa vesimäärää:

$k=120~\text{l/min} \cdot 4~\text{h}=120 \text{l/min} \cdot 4\cdot 60~\text{min} \approx 29 000~\text{l}$

tai

$k=210~\text{l/min}\cdot 2~\text{h}~18~\text{min}=210~\text{l/min}\cdot 138~\text{min}\approx 29 000~\text{l}$.

:::

### Riippuvuus muotoa $y=\frac{k}{x^n}, n > 1$

Jos kääntäen verrannollisia suureita yhdistää yhtälö $y=\frac{k}{x^n}, n> 1$, niin verrannollisuuskertoimeksi saadaan $k=yx^n$. Lukupareille $(x_1,y_1)$ ja $(x_2,y_2)$ pätee siis yhtälö $x_1^n y_1 = x_2^n y_2$.

**Esim.** Lampun valaistusvoimakkuus, jota mitataan lukseina (lux), on kääntäen verrannollinen etäisyyden toiseen potenssiin. Jos valaistusvoimakkuus kahden metrin päässä lampusta on 90 lux, paljonko se on viiden metrin päässä lampusta?

:::{admonition} Ratkaisu
:class: tip, dropdown

Merkitään tunnettua valaistusvoimakkuutta $y_1=90~\text{lx}$, tunnettua etäisyyttä $x_2=2~\text{m}$ ja toista etäisyyttä $x_2=5~\text{m}$. Ratkaistaan tuntematon valaistusvoimakkuus $y_2$ yhtälöstä $x_1^2 y_1 = x_2^2 y_2$:

$x_1^2 y_1 = x_2^2 y_2 \leftrightarrow y_2 = y_2 \frac{x_1^2}{x_2}^2 = 90~\text{lux}\cdot \frac{\left(2~\text{m}\right)^2}{\left(5~\text{m}\right)^2} = 14.4~\text{lx}$.

:::

**Esim.** Auringon säteilyn intensiteetti jollakin planeetilla on kääntäen verrannollinen planeetan etäisyyden toiseen potenssiin. Maan etäisyys auringosta on 1 AU (astronomical unit). Intensiteetti maapallolla on noin $1400~\text{W/m}^2$. Millä etäisyydellä intensiteetti olisi kaksinkertainen maapallolle kohdistuvaan intensiteettiin verrattuna?

:::{admonition} Ratkaisu
:class: tip, dropdown

Merkitään maapallon etäisyyttä auringosta $x_1=1~\text{AU}$ ja intensiteettiä $y_1=1400~\text{W/m}^2$. Tehtävässä annettu intensiteetti on $y_2=2\cdot 1400~\text{W/m}^2$. Ratkaistaan tuntematon etäisyys $x_2$ yhtälöstä $x_1^2 y_1 = x_2^2 y_2$:

$x_1^2 y_1 = x_2^2 y_2$

$x_2^2 = x_1^2 \cdot \frac{y_1}{y_2}$

$x_2 = \sqrt{x_1^2\cdot \frac{y_1}{y_2}}$

$x_2 = \sqrt{(1~\text{AU})^2\cdot \frac{1400~\text{W/m}^2}{2\cdot 1400~\text{W/m}^2}}$

Huomaa, että intensiteetin arvo yksiköineen supistuu pois yhtälöstä! Tehtävässä voitaisiin siis pelkästään kysyä, millä etäisyydellä intensiteetti kaksinkertaistuu, ilman tietoa siitä paljonko se maapallolla on. Vastaukseksi saadaan

$x_2 = \sqrt{(1~\text{AU})^2\cdot \frac{1}{2}} \approx 0.71~\text{AU}$. 

Etäisyys vastaa suunnilleen Venuksen sijaintia.

:::

<!-- #endregion -->
