# Lieriö ja kartio

Lieriö ja kartio eivät ehkä ole arkipäiväisiä ilmaisuja, mutta muotoina ne ovat kyllä yleisiä. Esimerkiksi kahvimuki on yleensä jossain määrin lieriön, tai ehkäpä katkaistun kartion, mallinen. Näiden muotojen avulla voi mallintaa myös esimerkiksi jäävuoria, tukkipuuta tai sorakasoja.

## Lieriö

![Lieriö](lierio.png "Lieriö")

Lieriön osiin kuuluu kaksi samanlaista pohjaa, pohjia yhdistävät sivujanat, ja sivujanojen muodostama vaippa. Lieriön korkeus $h$ on pohjien kohtisuora etäisyys. Suorassa lieriössä sivujanat ovat yhtä pitkät kuin lieriön korkeus. Ympyrälieriön pohjat ovat ympyröitä. Prisma on lieriö, jonka pohja on monikulmio.

Lieriön tilavuus saadaan laskemalla pohjan alan $A$ ja korkeuden $h$ tulo, $V=Ah$. Lieriön muodosta riippuu, millä laskukaavalla pohjan ala lasketaan. 

::::{admonition} Esimerkki

Oletetaan, että Pisan kalteva torni on muodoltaan ympyrälieriö. Lieriön korkeus eli matka kohtisuoraan maasta huipulle on 55.9 metriä ja pohjan halkaisija 15.5 metriä. Laske tornin tilavuus.

:::{admonition} Ratkaisu
:class: tip, dropdown

Tornin tilavuus on $V=Ah=\pi r^2 h= \pi \cdot \left(\frac{15.5}{2}~\text{m}\right)^2\cdot 55.9~\text{m} \approx 10500~\text{m}^3$.

:::

::::

::::{admonition} Esimerkki

Tynnyrin tilavuus on 300 litraa ja pohjaympyrän säde on 40 cm. Tynnyri on suoran ympyrälieriön muotoinen. Kuinka korkea tynnyri on?

:::{admonition} Ratkaisu
:class: tip, dropdown

Tynnyrin tilavuus on $V=\pi r^2 h$, missä $r$ on säde ja $h$ on korkeus, joten korkeus on $h=\frac{V}{\pi r^2}$.

Sijoitetaan lukuarvot. Tilavuus pitää muuttaa kuutiometreiksi. Tuhat litraa vastaa yhtä kuutiometriä, joten 300 litraa on $\frac{300}{1000}~\text{m}^3=0.3~\text{m}^3$. Myös säde pitää ilmaista metreinä. Siis korkeus on

$h=\frac{0.3~\text{m}^3}{\pi\cdot (0.4~\text{m})^2} \approx 0.6~\text{m}$

:::

::::

::::{admonition} Esimerkki

Erästä taipuisaa materiaalia on suorakulmion muotoinen pala, jonka sivujen pituudet ovat 60 cm ja 100 cm. Pala kääräistään rullalle siten, että se muodostaa suoran ympyräpohjaisen lieriön seinät. Kuinka suuri on muodostuvan lieriön tilavuus?

:::{admonition} Ratkaisu
:class: tip, dropdown

Lieriö voidaan muodostaa kuvan mukaisesti kahdella tavalla:

![Kaksi lieriötä samasta suorakulmiosta](tynnyrit.png "Kaksi lieriötä samasta suorakulmiosta")

Tapauksessa A lieriön korkeus on 60 cm ja pohjaympyrän kehä 100 cm. Pohjaympyrän säde on siten $\frac{100~\text{cm}}{2\pi}$. Sijoitetaan luvut tilavuuden laskukaavaan metreinä, jolloin tilavuus saadaan kuutiometreinä:

$\pi\cdot \left(\frac{1.00~\text{m}}{2\pi}\right)^2\cdot 0.60~\text{m} \approx 0.048~\text{m}^3$ eli 48 litraa.

Tapauksessa B lieriön korkeus on 100 cm ja pohjaympyrän kehä 60 cm, josta saadaan pohjaympyrän säteeksi $\frac{60~\text{cm}}{2\pi}$. 

Tilavuudeksi saadaan

$\pi\cdot \left(\frac{0.60~\text{m}}{2\pi}\right)^2\cdot 1.00~\text{m} \approx 0.029~\text{m}^3$ eli 29 litraa.

:::

::::



## Kartio

![Kartio](kartio.png "Kartio")

Kartion osia ovat pohja (ala $A$), huippu ja sivujanat. Sivujanat muodostavat kartion vaipan ja yhdistyvät kartion huipulla. Kartion korkeus $h$ on kohtisuora etäisyys huipulta pohjalle. Suoran kartion korkeus on sama kuin etäisyys huipulta pohjan keskipisteeseen. Ympyräkartio on kartio, jonka pohja on ympyrä. Pyramidi on kartio, jonka pohja on monikulmio. 
 
Kartion tilavuudelle voidaan johtaa laskukaava $V=\frac{1}{3} Ah$. Erityiesti ympyräpohjaiselle kartiolle pätee $V=\frac{1}{3} \pi r^2 h$.

:::{admonition} Perustelu
:class: tip, dropdown

Kartion tilavuuden kaavan voi johtaa esimerkiksi siten, että "sahataan" kartio kiekoiksi, joiden pinta-ala on sitä pienempi, mitä korkeammalla ne ovat kartiossa. Kun kiekot ovat ohuita, niiden voidaan ajatella olevan lieriömäisiä. Jokaisella kiekolla on tietty pinta-ala ja tietty paksuus, jolloin kartion tilavuuden saisi laskettua näiden kiekkojen tilavuuksien summana. Kartion sahaaminen äärettömän moneen, äärettömän ohueen, kiekkoon tapahtuu matemaattisesti integraalilaskennan avulla.

![Kartion tilavuuden perustelu](kartion_tilavuus.png "Kartion tilavuuden perustelu")

[Matematiikkalehti Solmussa](https://matematiikkalehtisolmu.fi/2012/3/induktio_ympyra_kartio_pallo.pdf) on esitetty samantapainen perustelu kartion tilavuuden kaavalle. Jokaisen kiekon ala on verrannollinen kartion leveyden toiseen potenssiin kyseisen kiekon kohdalla. Koska kartio levenee kärjestä pohjaa kohti tasaisesti, niin $k$:nnen kiekon halkaisija on verrannollinen sen sijaintiin $n$:n kiekon pinossa. Tietystä kohtaa "sahatun" kiekon alan $A_k$ suhde kartion pohjan alaan $A$ on siis verrannollinen kiekon sijainnin toiseen potenssiin: 

$\frac{A_k}{A}=\left(\frac{k}{n}\right)^2$

Tästä saadaan ratkaistua $A_k=A \left(\frac{k}{n}\right)^2 $

Jos kartion korkeus on $h$ ja se on jaettu $n$ kiekkoon, niin jokaisen kiekon paksuus on $\frac{h}{n}$. Kohdassa $k$ olevan kiekon tilavuus on kyseisen kiekon ala kerrottuna kiekon paksuudella $\frac{h}{n}$, siis

$V_k=A_k \frac{h}{n}= A \left(\frac{k}{n}\right)^2 \frac{h}{n} = A \frac{k^2 h}{n^3}, k=1,2, \ldots n$.

Näitä kiekkoja on yhteensä $n$ kappaletta. Koko kartion tilavuus kuvan mukaisesti on pienempi kuin kartioiden kattava ala, joten $V < A \frac{1^2 h}{n^3} + A \frac{2^2 h}{n^3} + \ldots A \frac{n^2 h}{n^3}$

Oikea puoli voidaan sieventää yhteisen tekijän avulla, joten

$V < A \frac{h}{n^3} (1^2 + 2^2 + \ldots n^2)$

Suluissa oleva summa voidaan (parin lukiotasoisen oppitunnin jälkeen) esittää muodossa $\frac{1}{6}\cdot 2(n+1)(2n+1)$, jolloin tilavuuden ylärajaksi tulee

$V < A \frac{h}{n^3} \cdot \frac{1}{6}\cdot 2(n+1)(2n+1)$

joka edelleen voidaan muokata muotoon

$V < \frac{Ah}{6} \cdot(2+\frac{1}{n^2}+\frac{3}{n})$.

Kartion tilavuuden yläraja saadaan asettamalla kiekkojen määrä äärettömäksi. Kiekkojen määrä ei oikeastaan voi *olla* ääretön, mutta se voi kyllä *lähestyä* ääretöntä. Kun $n$ lähestyy ääretöntä, niin termit $\frac{1}{n^2}$ ja $\frac{3}{n}$ lähestyvät nollaa. Tällöin tilavuuden yläraja lähestyy lukua 

$V < \frac{Ah}{6}\cdot 2 = \frac{1}{3}Ah$.

Vastaavanlaisella päättelyllä, mutta määrittämällä kiekot kartion "sisäpuolelle", saataisiin kartion tilavuudelle määritettyä yhtä suuri alaraja. Tällöin siis kartion pitää olla tasan yhtä suuri kuin $\frac{1}{3}Ah$.

:::

::::{admonition} Esimerkki

Popcornia pakataan suoran ympyräkartion muotoiseen pahviastiaan, jonka korkeus on 20 cm ja pohjaympyrän halkaisija 14 cm. Jos sama määrä popcornia pakattaisiin yhtä korkeaan neliöpohjaisen pyramidin muotoiseen astiaan, niin kuinka pitkä olisi pyramidin pohjana olevan neliön sivu $x$?

:::{admonition} Ratkaisu
:class: tip, dropdown

Kirjoitetaan yhtälö, jossa toisella puolella on pyramidin tilavuus ja toisella puolella ympyräkartion tilavuus:

$\frac{1}{3} x^2 \cdot 20~\text{cm}=\frac{1}{3} \pi \cdot \left(\frac{14}{2}~\text{cm}\right)^2\cdot 20~\text{cm}$

Kertoimet $\frac{1}{3}$ saadaan pois kertomalla yhtälön molemmat puolet luvulla 3. Vastaavasti kertoimet 20 saadaan pois jakamalla molemmat puolet luvulla 20. Tämän jälkeen voidaan helposti ratkaista

$x=\sqrt{\pi \cdot 7^2~\text{cm}^2} \leftrightarrow x=12.4~\text{cm}$

:::

::::

::::{admonition} Esimerkki

Hiekkaa kipataan maahan 3 kuutiometriä. Hiekka asettuu suoran ympyräpohjaisen kartion muotoiseksi kasaksi, jonka korkeus on 2 metriä. Mikä on kasan ympärysmitta?

Selvitä lisäksi kasan kaltevuuskulma eli sivujanan ja pohjaympyrän säteen välinen kulma. Eri aineet asettuvat luonnostaan erilaisiksi kasoiksi. Voit vertailla vaikka uimarannalla märän ja kuivan hiekan kasautumista. Kaltevuuskulma on eksakti tapa kuvailla kasan muotoa. 

:::{admonition} Ratkaisu
:class: tip, dropdown

Selvitään ensin kasan säde yhtälöstä $V= \pi r^2 h$, siis $r=\sqrt{\frac{V}{\pi h}}$. 

Sijoitetaan lukuarvot: $r=\sqrt{\frac{3~\text{m}^3}{\pi \cdot 2~\text{m}}}\approx 1.2~\text{m}$

Ympärysmitta on $2 \pi r=2\pi \cdot 1.2~\text{m}=7.5~\text{m}$

Kaltevuuskulma on kuvan mukaisesti $\alpha=\arctan{\frac{h}{r}}=\arctan{\frac{2}{1.2}}\approx 59^{\circ}$.

![Kartion sivujanan kaltevuus](hiekkakasa.png "Kartion sivujanan kaltevuus")

:::

::::

## Katkaistu kartio

Katkaistu kartio on nimensä mukaisesti kartio, josta on katkaistu kärki pois. Tällaisella kartiossa on kaksi pohjaa, joiden alat ovat $A_1$ ja $A_2$. Katkaistua kartiota voidaan käyttää mallina esim. puutukin tilavuuden laskemiseen. Puuthan ovat yleensä tyvestä paksumpia kuin latvasta.

Katkaistun kartion tilavuus on $V=\frac{1}{3}h (A_1+ \sqrt{A_1 A_2} +A_2 )$

:::{admonition} Perustelu
:class: tip, dropdown

Katkaistun kartion tilavuuden kaava on käsitteellisesti helppo, mutta algebrallisesti hieman työläs johtaa. Olkoon kokonaisen kartion korkeus $H$, jäljelle jääneen alaosan korkeus $h$ ja katkaistun osan pituus $H-h$. Merkitään kartion suurempaa pohjaa $A_1$ ja pienempää pohjaa, eli pois katkaistun kartion pohjaa, $A_2$. Katkaistun kartion tilavuus saadaan, kun kokonaisen kartion tilavuudesta vähennetään yläosa:

$V=\frac{1}{3}A_1 H - \frac{1}{3}A_2 (H-h)$

$V=\frac{1}{3}A_1 H - \frac{1}{3}A_2 H +\frac{1}{3}A_2 h$

Muokataan yhtälö vielä muotoon $V=\frac{1}{3} \left((A_1-A_2)H + A_2 h\right)$.

Koska kokonainen ja pois katkaistu kartio ovat yhdenmuotoisia, niiden pohjien aloille pätee $\frac{A_2}{A_1}=\frac{(H-h)^2}{h^2}$. Yhtälön oikea puoli on korotettu potenssiin 2, koska pohjien mitat (esim. ympyränmuotoisen pohjan säteet) ovat verrannollisia kartioiden korkeukseen, mutta pinta-alat ovat verrannollisia näiden mittojen toiseen potenssiin.

Edellisestä yhtälöstä saadaan muutaman [välivaiheen](https://mathalino.com/reviewer/derivation-of-formulas/derivation-of-formula-for-volume-of-a-frustum) kautta ratkaistua $H=h\left(\frac{A_1+\sqrt{A_1 A_2}}{A_1-A_2}\right)$. Sijoitetaan tämä tilavuuden yhtälöön ja sievennetään:

$V=\frac{1}{3} \left((A_1-A_2) \cdot h \cdot \frac{A_1+\sqrt{A_1 A_2}}{A_1-A_2} + A_2 h\right)$

$V=\frac{1}{3} \left(h(A_1+\sqrt{A_1 A_2}) + A_2 h\right)$

$V=\frac{1}{3} h (A_1+\sqrt{A_1 A_2} + A_2)$

:::

::::{admonition} Esimerkki

Puutukin pituus on 6 metriä. Tyvipään halkaisija on 40 cm ja latvapään halkaisija 20 cm. Laske tukin tilavuus kuutiometreinä.

:::{admonition} Ratkaisu
:class: tip, dropdown

Pohjien säteet ovat puolet halkaisijoista, siis metreinä ilmaistuna 0.2 m ja 0.1 m. Tukin tilavuus on 

$V=\frac{1}{3} \cdot 6~\text{m}\cdot \dots $

$ \dots \left(\pi\cdot (0.2~\text{m})^2+\sqrt {(\pi \cdot (0.2 ~\text{m})^2 \cdot \pi \cdot (0.1~\text{m})^2}+ \pi\cdot (0.1~\text{m})^2\right)$

$V=0.44~\text{m}^3$.

:::

::::