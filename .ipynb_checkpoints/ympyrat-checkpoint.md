# Ympyrä

Ympyrä kuuluu tasogeometrian perusasioihin. Tarkastellaan aluksi ympyrään liittyviä käsitteitä ja laskukaavoja. Sen jälkeen sovelletaan näitä tietoja maapallon pituus- ja leveyspiireihin liittyvissä laskuissa.

## Peruskäsitteet

Ympyrän kehä on niiden samassa tasossa olevien pisteiden joukko, joiden etäisyys määrätystä tason pisteestä (ympyrän keskipisteestä) on yhtä suuri. Ympyrä on kehän rajoittama tason osa. Keskipisteen ja kehällä olevan pisteen välinen jana on säde. Säteen pituus on kuvassa merkitty kirjaimella $r$ (radius). Kahden kehällä olevan pisteen välinen jana on jänne, ja keskipisteen kautta kulkeva jänne on halkaisija. Halkaisijaa merkitään kuvassa kirjaimella $d$ (diameter) ja sen pituus on $d=2r$. Jänne jakaa ympyrän kahteen segmenttiin.

Ympyrän kehän pituus $p$ (perimeter) on $p=2\pi r$ ja ympyrän pinta-ala on $A=\pi r^2$ tai halkaisijan avulla kirjoitettuna $A=\frac{\pi d^2}{4}$.

:::{admonition} Perustelut
:class: tip, dropdown
huh huh
:::

Kaksi sädettä jakaa ympyrän kahteen sektoriin. Säteiden väliin jää kaksi keskuskulmaa: $\alpha$ ja $360^{\circ}-\alpha$. 

Keskuskulmaa $\alpha$ vastaavan kaaren pituus $p_{\alpha}$ on keskuskulmaa vastaava osa koko ympyrän kehästä: 

$p_{\alpha}=\frac{\alpha}{360}\cdot 2\pi r$.

Vastaavasti sektorin pinta-ala $A_{\text{sek}}$ on keskuskulmaa $\alpha$ vastaava osuus koko ympyrän alasta: 
$A_{\text{sek}}=\frac{\alpha}{360}\cdot \pi r^2$.

Segmentin pinta-alaksi $A_{\text{seg}}$ saadaan keskuskulman ja jänteen rajaaman kolmion avulla: 

$A_{\text{sek}}=\frac{\alpha}{360}\cdot \pi r^2 -\frac{1}{2}r^2 \sin{\alpha}$.

:::{admonition} Segmentin pinta-alan perustelu
:class: tip, dropdown
huh huh
:::

Ympyrän kehällä olevasta pisteestä lähtevien kahden jänteen välinen kulma on nimeltään kehäkulma $\beta$ (kuvassa alla vasemmalla). Kehäkulman suuruus on puolet vastaavasta keskuskulmasta $\alpha$, siis $\beta=\frac{\alpha}{2}$.

Kun ympyrän ulkopuolelta olevasta pisteestä piirretään ympyrälle tangentit (eli ympyrää yhdessä pisteessä sivuavat suorat), tangenttien väliin jää tangenttikulma $\beta$. Tangenttikulman ja sitä vastaavan keskuskulman summa on $\alpha+\beta=180^{\circ}$.

Eräs käyttökelpainen laskusääntö ympyrälle on sekanttilause. Sen mukaan minkä tahansa (ympyrän sisä- tai ulkopuolella olevan) pisteen $P$ kautta kehän pisteiden $A$ ja $B$ sekä kehän pisteiden $C$ ja $D$ väliin piirretyille jänteille pätee $PA\cdot PB=PC\cdot PD$

:::{admonition} Sekanttilauseen perustelu
:class: tip, dropdown
huh huh
:::
 
**Esim.** Kuinka suuri on kuvan ympyrän halkaisija $CD$? Ympyrän mitoista tiedetään, että $PC=6$ ja $PA=PB=2$.

:::{admonition} Ratkaisu
:class: tip, dropdown

Sekanttilauseen perusteella $PA\cdot PB=PC\cdot PD$, josta saadaan $PD=\frac{PA\cdot PB}{PC}=\frac{2\cdot 2}{6}=\frac{4}{6}=\frac{2}{3}$. Halkaisija on siis $CD=PC+PD=6+\frac{2}{3}=\frac{18}{3}+\frac{2}{3}=\frac{20}{3}$.

:::

## Pituus- ja leveyspiirit

Maapallon pituuspiirit (longitude) tai pituusasteet määritellään kulmina $\lambda$ sovitun ns. nollameridiaanin suhteen. Nollameridiaanin sijainniksi on vuonna 1884 valittu Greenwichin kuninkaallisen tähtitornin kautta kulkeva pituuspiiri. Pituuspiirit ovat napojen kautta kulkevia isoympyröitä, eli pisimpiä mahdollisia pallon pinnalla kulkevia ratoja.

Leveyspiirit (latitude) tai leveysasteet määritellään kulmina $\phi$ päiväntasaajalta pohjoiseen tai etelään. Leveyspiirit ovat päiväntasaajan suuntaisia pikkuympyröitä. Päiväntasaajaa lukuunottamatta ne ovat siis lyhyempiä kuin pituuspiirit. 

Seuraavat laskuesimerkit pätevät sillä oletuksella, että maapallo olisi todella pallon muotoinen. Oikeasti näin ei ole. Maapallon pyöriminen akselinsa ympäri muokkaa hieman maapallon muotoa siten, että maapallo on aavistuksen litistynyt. Leveyspiireihin liittyy myös ajallista vaihtelua. Pohjoisen napapiirin leveysasteet ovat tällä hetkellä noin $66^{\circ}~33'~39''$. Napapiiri määräytyy maapallon pyörimisakselin kaltevuuden perusteella, ja se puolestaan vaihtelee säännöllisin väliajoin maan, auringon ja kuun välisten vuorovaikutusten mukaan.

Lyhin reitti maapallolla pisteestä toiseen on kahden pisteen välistä isoympyrää pitkin. Laskuihin sopiva likiarvo isoympyrän pituudelle, eli maapallon ympärysmitalle, on 40 000 km. Maapallon säteelle käytetään yleensä arvoa 6370-6380 km. Laskemalla säteen avulla ympärysmitta kaavalla $p=2 \pi r$ saataisiin hieman eri arvo. 

**Esim.** Helsinki ja Ateena sijaitsevat likimain samalla pituuspiirillä. Helsingin leveyspiiri on 60° pohjoista leveyttä ja Ateenan 38° pohjoista leveyttä. Mikä on kaupunkien etäisyys?

:::{admonition} Ratkaisu
:class: tip, dropdown

Kaupunkien leveyspiirien välinen kulma on $\alpha=60^{\circ}-38^{\circ}=22^{\circ}$. Kaupunkien välinen etäisyys on kulmaa vastaava osuus isoympyrän kehän pituudesta $p$:

$\frac{22^{\circ}}{360^{\circ}}\cdot 40000~\text{km} = 2440~\text{km}$.

:::

Leveyspiiriä pitkin kuljettaessa matkan pituus riippuu sekä pisteiden pituuspiirien välisestä kulmasta että leveyspiirin sijainnista. Eri leveyspiirithän ovat eri mittaisia. On siis ensin laskettava maapallon ympärysmitta annetun leveyspiirin kohdalla.

**Esim.** Helsinki ja Oslo sijaitsevat likimain leveyspiirillä 60°. Oslo sijaitsee pituuspiirillä 10.4° ja Helsinki pituuspiirillä 25.0°. Mikä on kaupunkien etäisyys?

:::{admonition} Ratkaisu
:class: tip, dropdown

Lasketaan ensin 60° leveyspiiriä vastaavan pikkuympyrän säde $r$. Vasempaan kuvaan täydennetylle suorakulmaiselle kolmiolle pätee $\sin{30^{\circ}}=\frac{r}{R}$, missä $R=6370~\text{km}$ on maapallon säde. Yhtälöstä saadaan 

$r=R \sin{30^{\circ}}= 6370~\text{km} \cdot \sin{30^{\circ}}=3185~\text{km}$.

Kaupunkien välinen etäisyys $s$ on nyt pituuspiirien välistä kulmaa $\alpha$ vastaava osuus pikkuympyrän kehän pituudesta:

$\alpha=25.0^{\circ}-10.4^{\circ}=14.6^{\circ}$,

$s=\frac{\alpha}{360^{\circ}}\cdot 2\pi r=\frac{14.6^{\circ}}{360^{\circ}}\cdot 2\pi \cdot 3185~\text{km}=812~\text{km}$.

:::
