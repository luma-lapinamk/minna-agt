$ \def\euro{\unicode{x20AC}} $

# Prosenttilaskentaa

Vaikka matematiikkaa ei muuten juurikaan tarvitsisi työtehtävissään tai muussa elämässä, niin prosenttilaskuille saattaa olla käyttöä. On hyvä osata laskea esimerkiksi, paljonko tuote maksaa 40 % alennuksen jälkeen, paljonko 3.5 % palkankorotus tuo rahaa pankkitilille, tai paljonko on arvonlisäverollisen tuotteen veroton hinta.

Prosentti % on lyhyt esitysmuoto murtoluvulle $\frac{1}{100}$. Tällöin $a~\%$ tarkoittaa lukua $a\cdot \frac{1}{100}$ eli $\frac{a}{100}$. 

Kahdelle luvulle $x$ ja $y$ sekä prosenttiosuudelle $a$ voidaan muodostaa yhtälö: $\frac{x}{y}=\frac{a}{100}$. Monet prosenttilaskuihin liittyvät ongelmat ratkeavat tämän yhtälön avulla.

## Peruslaskuja

:::{admonition} Kuinka monta prosenttia luku $x$ on luvusta $y$?

Ratkaisu: Yhtälöstä $\frac{x}{y}=\frac{a}{100}$ saadaan ratkaistua $a=\frac{x}{y} \cdot 100~\%$ 

Esim. Kuinka monta prosenttia luku 55 on luvusta 225?

$a=\frac{55}{225}\cdot 100~\%=24~\%$

:::

:::{admonition} Kuinka paljon tietty prosenttiosuus $a$ on luvusta $y$?

Ratkaisu: Yhtälöstä  $\frac{x}{y}=\frac{a}{100}$ saadaan ratkaistua $x=\frac{a}{100} \cdot y$ 

Huomaa, että kyseessä on ihan tavallinen kertolasku, joten sen voi esittää myös muodossa $x=\frac{y}{100} \cdot a$. 

Esim. Kuinka paljon on a) 5 prosenttia 70:stä? b) 70 prosenttia 5:stä?

a) $x=\frac{5}{100}\cdot 70=3.5$

b) $x=\frac{70}{100}\cdot 5=3.5$

:::

:::{admonition} Kuinka monta prosenttia suurempi luku $x$ on kuin luku $y$?

Ratkaisu: Nyt yhtälöön $a=\frac{x}{y} \cdot 100~\%$ laitetaan luvun $x$ paikalle erotus $x-y$. Saadan laskukaava $\frac{x-y}{y}\cdot 100~\%$.

Esim. Kuinka paljon pidempi on 195 cm pitkä henkilö kuin 180 cm pitkä henkilö?

$\frac{195-180}{180}\cdot 100~\% \approx 8.3~\%$

Huomaa: Luvun $y$ paikalle tulee se luku, johon verrataan. Voitaisiin myös kysyä, kuinka paljon lyhyempi 180 cm pitkä henkilö on kuin 195 cm pitkä henkilö. Tällöin laskuksi muodostuisi 

$\frac{195-180}{195}\cdot 100~\% \approx 7.7~\%$

ja toisaalta voitaisiin myös kysyä, kuinka monta prosenttia 180 cm pitkän henkilön pituus on 195 cm pitkän henkilön pituudesta:

$\frac{180}{195}\cdot 100~\% \approx 92.3~\%$.


:::

:::{admonition} Kuinka paljon luku kasvaa tai pienenee, kun sitä muutetaan $a$ prosenttia?

Ratkaisu: Lukuun $x$ lisätään tai luvusta $x$ vähennetään prosenttiosuutta $a$ luvusta $x$ vastaava määrä. 

Uusi luku on siis $x\pm \frac{a}{100} \cdot x$ jonka voi esittää myös muodossa $x\cdot(1\pm\frac{a}{100})$.

Esim. Palkka nousee 2.8 %. Mikä on uusi palkka, kun se alunperin oli 4352 euroa?

$4352~\euro + \frac{2.8}{100} \cdot 4352~\euro \approx 4473.86~\euro$ tai $4352~\euro \cdot (1+\frac{2.8}{100}) \approx 4473.86~\euro$

Huom! Sulkulausekkeeseen kaavassa $x\cdot(1\pm\frac{a}{100})$ tulee lopputuloksena desimaalikerroin, jonka voi suoraan päätelläkin. Esimerkiksi jos arvo nousee 20 %, niin alkuperäinen luku pitää kertoa luvulla $1+\frac{20}{100}=1+0.2=1.2$. Jos taas arvo laskee 13 %, niin kertoimeksi tulee $1-0.13=9.87€.

:::

:::{admonition} Mikä on alkuperäinen luku, kun tiedetään $a$ prosenttia muuttunut luku?

Ratkaisu: Merkitään alkuperäistä lukua $x_1$ ja uutta lukua $x_2$. Edellisessä kohdassa laskettiin $x_2=x_1 (1\pm \frac{a}{100})$. Tästä saadaan ratkaistua alkuperäinen luku:

$x_1=\frac{x_2}{1\pm \frac{a}{100}}$

Esim. Tuotteen hintaa laskettiin 15 %. Hinta oli muutoksen jälkeen 77.50 €. Paljonko oli alkuperäinen hinta?

$x_1=\frac{77.50~\euro}{1-\frac{15}{100}}=91.18~\euro$ tai suoraan desimaaliluvuilla $\frac{77.50~\euro}{0.85}=91.18~\euro$

Tällaiset tehtävät kannattaa tarkistaa: Jos alkuperäistä hintaa $91.18~\euro$ pienennetään 15 %, uusi hinta todellakin on $91.18~\euro\cdot (1-0.15) = 77.50~\euro$.

:::

:::{admonition} Prosentti ja prosenttiyksikkö

Usein mediassa käsitellään prosenttiyksiköitä. Esimerkiksi jonkin puolueen kannatus voi aluksi olla 22 % ja kuukautta myöhemmin 26 %. Tällöin puolueen kannatus on noussut $26-22=4$ prosenttiyksikköä. Kannatuksen muutos prosentteina lasketaan kuitenkin toisin:

$\frac{26-22}{22}\cdot 100~\% \approx 18.2~\%$

:::

**Harjoituksia**

Seuraavat tehtävät ratkeavat edellisten mallien mukaisilla laskuilla. Mieti ennen ratkaisun katsomista, mikä kaava sopisi mihinkin ongelmaan. Tehtävät eivät välttämättä ole samassa järjestyksessä kuin laskukaavat!

::::{admonition} Esimerkki

Jalkapalloseuran joukkueet tekivät talkootyötä yhteensä 62 tuntia. Seura sai työn tilaajalta urakkapalkkana 900 €. Eräs joukkue työskenteli yhteensä 18 tuntia. Montako prosenttia palkasta kuuluu tälle joukkueelle? Kuinka monta euroa palkka on?

:::{admonition} Ratkaisu
:class: tip, dropdown

Joukkueen osuus työtunneista on $\frac{18}{62}\cdot 100~\% \approx 29~\%$ ja näin ollen palkka on $\frac{29}{100}\cdot 900~\euro = 261~\euro$.

:::

::::

::::{admonition} Esimerkki

Uuden puhelimen akun kapasiteetti on 5200 mAh ja vanhan puhelimen akun kapasiteetti oli 3800 mAh. Kuinka monta prosenttia suurempi uuden akun kapasiteetti on kuin vanhan? Jos hintakin kasvaa tässä samassa suhteessa, niin mikä olisi uusi hinta, kun vanhan mallin hinta oli 259 euroa?

:::{admonition} Ratkaisu
:class: tip, dropdown

Verrataan kapasiteettien erotusta vanhaan kapasiteettiin: $\frac{5200-3800}{3800} \cdot 100~\% \approx 36.8~\%$

Hinnaksi saadaan $259~\euro\cdot(1+\frac{36.8}{100}) \approx 354 ~\euro$.

:::

::::

::::{admonition} Esimerkki

Suomenhevonen jaksaa vetää reessä noin 110 % omasta massastaan. Hevosen massa on 530 kg. Paljonko voi olla tukkikuorman massa? Suositeltu ratsastajan enimmäismassa sen sijaan on vain noin 18 % hevosen massasta. Kuinka monta prosenttia enemmän hevonen vetää perässään kuin kantaa selässään?

:::{admonition} Ratkaisu
:class: tip, dropdown

Merkitään kuormaa luvulla $x$, jolloin on ratkaistava yhtälö $\frac{x}{530~\text{kg}}=\frac{110}{100}$. Tästä ratkeaa $x=\frac{110}{100}\cdot 530~\text{kg}$ eli 583 kg.

Ratsastajan massa voi olla $\frac{18}{100}\cdot 530~\text{kg}$ eli 95.4 kg.

Tukkikuorman massa on $\frac{583-95.4}{95.4}\cdot 100~\% \approx 511 ~\%$ suurempi kuin ratsastajan. Tämän voi laskea myös ilman tietoa varsinaisista kilomääristä: $\frac{110-18}{18}\cdot 100~\% \approx 511 ~\%$$.

:::

::::


::::{admonition} Esimerkki 

Kahvikupillinen maksaa 2.30 € ja teemukillinen 2.10 €. Kummankin hintaa nostetaan 20 %. Kuinka monta prosenttia kalliimpi kahvi on kuin tee ennen korotusta? Entä korotuksen jälkeen?

:::{admonition} Ratkaisu
:class: tip, dropdown

Ennen korotusta: $\frac{2.30~\euro-2.10~\euro}{2.10~\euro} \cdot 100~\% \approx 9.5~\%$

Uudet hinnat ovat $2.30~\euro\cdot(1+0.2)=2.76~\euro$ ja $2.30~\euro\cdot(1+0.2)=2.52~\euro$.

Hintaero on edelleen $\frac{2.76~\euro-2.52~\euro}{2.52~\euro} \cdot 100~\% \approx 9.5~\%$

Yleisesti kun luvut $x$ ja $y$ muuttuvat saman prosenttiosuuden $a$, niin laskun $\frac{x\cdot(1 \pm \frac{a}{100})-y\cdot (1 \pm \frac{a}{100})}{y\cdot(1 \pm \frac{a}{100})}$ tulos on sama kuin laskun $\frac{x-y}{y}$.

:::

::::


## Sovelluksia

Käytännönläheisen prosenttilaskuihin liittyvät ongelmat vaativat edellisten laskukaavojen soveltamista. Tehtävistä selviää, kun muistaa, että alennukset ja korotukset ovat käytännössä desimaaliluvulla kertomista.

::::{admonition} Esimerkki

Nappulakenkien hinta urheiluliikkeen hyllyssä oli 90 euroa. Paketissa oli alennustarra -30 %. Urheiluseuran jäsenet saavat loppusummasta 10 % alennuksen. Paljonko kengille jäi hintaa?

:::{admonition} Ratkaisu
:class: tip, dropdown

Äkkiseltään voisi kuvitella, että alennusta saisi yhteensä 40 %, jolloin hinnaksi jäisi $90~\euro \cdot(1-0.40) = 54~\euro$. Näin ei kuitenkaan ole. Kahdesta erillisestä prosenttiosuudesta tulee kertolasku, ei yhteenlasku.

Tässä tapauksessa alennettu hinta on $90~\euro \cdot(1-0.3) = 0.7\cdot 90~\euro = 63~\euro$ ja sen jälkeen lasketaan jäsenalennus tästä hinnasta kertolaskulla: $63~\euro \cdot (1-0.1) = 0.9~\cdot 63~\euro = 56.70~\euro$.

Kertolaskut voi toki laskea kerrallakin: $0.7~\cdot 0.9 \cdot 90~\euro = 56.70~\euro$.

:::

::::

::::{admonition} Esimerkki

Laimennuslaskuja tarvitaan esimerkiksi hoitoalalla. Kuinka paljon vettä pitää lisätä 250 grammaan 4-prosenttista suolaliuosta, jotta liuos laimenee 3-prosenttiseksi?

:::{admonition} Ratkaisu
:class: tip, dropdown

Lasketaan ensin suolan määrä grammoina alkuperäisessä liuoksessa:

$\frac{4}{100}\cdot 250~\text{g} = 10 ~\text{g}$

Lopullisessa liuoksessa suolaa on yhä tämä 10 grammaa, ja sen pitäisi olla 3 % koko liuoksesta. Siis koko liuoksen massa $m$ saadaan yhtälöstä

$\frac{3}{100} \cdot m =10~\text{g}$, josta $m=10~\text{g}\cdot \frac{100}{3}\approx 333.33~\text{g}$.

Lisäystä alkuperäiseen on siis $333.33~\text{g}-250\text{g}\approx 83~\text{g}$. Vettä on lisättävä tämän verran.

:::

::::

::::{admonition} Esimerkki

Tuotteen hinta 240 € sisältää 24 % arvonlisäveroa. Paljonko on tuotteen veroton hinta? Mikä on tuotteen uusi hinta, jos verokanta muuttuu siten että uusi vero on 14 % verottomasta hinnasta?

:::{admonition} Ratkaisu
:class: tip, dropdown

Arvonlisävero 24 % lisätään tuotteen verottomaan hintaan. Veroton hinta saadaan samalla tavalla kuin alkuperäinen arvo ennen muutosta:

$\frac{240~\euro}{1+0.24}\approx 193.55~\euro$

Uusi hinta pienemmällä verolla on $193.55~\euro \cdot(1+0.14) \approx 220.65~\euro$

:::

::::

::::{admonition} Esimerkki

Verkkokaupassa tuotteen hinta nousi ensin 20 % ja laski sitten 15 %. Kuinka monta prosenttia hinta muuttui kokonaisuudessaan?

:::{admonition} Ratkaisu
:class: tip, dropdown

Korotusta vastaa luvulla $1+\frac{20}{100}=1.2$ kertominen ja alennusta luvulla $1-\frac{15}{100}=0.85$ kertominen. Hinnaksi jää siis $1.2\cdot 0.85 = 1.02$ kertaa alkuperäinen hinta. Hinta siis nousi 2 %. Laskun tulos ei riipu alkuperäisestä hinnasta.

:::

::::

::::{admonition} Esimerkki

Bensiinin litrahinta nousee 12 %. Kuinka monta prosenttia bensiinin kulutusta pitäisi vähentää, jotta polttoainekulut pysyisivät ennallaan?

:::{admonition} Ratkaisu
:class: tip, dropdown

Alkuun pääsee merkitsemällä polttoaineen hintaa, polttoaineen kulutusta ja ajamisen kustannuksia joillakin kirjaimilla. Olkoon bensiinin hinta ennen korotusta $x$ euroa/litra ja alkuperäinen kulutettu määrä $y$ litraa jossakin tietyssä ajassa. Tällöin kyseisenä ajanjaksona polttoainekustannuksiksi tulee hinnan ja kulutuksen tulo $xy$ euroa.

Hinnankorotuksen jälkeen bensiinin hinta on $1.12x$ euroa/litra. Kerrotaan kulutus jollain toistaiseksi tuntemattomalla kertoimella $a$, eli uusi kulutus on $ay$. Tällöin kustannuksiksi tulee $1.12xay$. Ratkaistaan $a$ yhtälöstä $1.12xay=xy$. Alkuperäinen hinta ja kulutus supistuvat pois, jolloin yhtälöksi jää $1.12a=1$ ja tästä ratkeaa $a=\frac{1}{1.12}$ eli $a\approx 0.893$. Kulutuksen pitäisi siis laskea $100~\%-89.3~\% = 10.7~\%$ tai noin 11 %.

:::

::::