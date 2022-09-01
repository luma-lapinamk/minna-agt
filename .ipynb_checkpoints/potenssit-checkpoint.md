<!-- #region -->
# Potenssi- ja juurilausekkeet

Potenssi- ja juurilausekkeiden käsittely kannattaa kerrata. Taitoa tarvitaan erilaisten laskusääntöjen johtamisessa ja monimutkaisten yhtälöiden ratkaisemisessa. Monet laskinohjelmat osaavat käsitellä näitäkin lausekkeita, mutta on helpompaa pysyä mukana laajempien ongelmien ratkaisuissa, kun ymmärtää, miten lausekkeet voivat muuttua eri näköisiksi. Potenssi- ja juurilausekkeet ovat tärkeitä myös silloin, kun matemaattisia ongelmia halutaan esittää yleisissä tapauksissa, siis ilman, että jokaista lukuarvoa tarvitsee määritellä laskemista varten.

## Potenssilausekkeet

**Pohdittavaksi** Neliön sivun pituus on $3$ metriä. Kuinka moninkertaiseksi neliön pinta-ala muuttuu, jos neliön sivu kaksinkertaistuu? Ongelma on helppo, sillä neliön pinta-alan pystyy laskemaan sekä alkuperäisellä että uudella sivun pituudella. Entä, jos haluaisimmekin esittää ratkaisun yleisessä tapauksessa eli siten, että neliön sivun pituus voi olla mikä tahansa luku $x$?

:::{admonition} Ratkaisu
:class: tip, dropdown
Neliön alkuperäinen pinta-ala $A_1$ on sivun pituuden $x$ toinen potenssi, siis $A_1=x^2$. Uuden sivun pituus on $2x$. Tällöin uusi pinta-ala on $A_2=(2x)^2=4x^2 = 4 A_1$. Ala siis nelinkertaistuu.
:::

**Pohdittavaksi** Tuulivoimalan tuottama sähköteho on fysiikan lakien mukaisesti verrannollinen tuulen nopeuden kolmanteen potenssiin. Millä tavalla sähköteho muuttuu, jos tuulen nopeus pienenee 10 prosenttia? Tällaiseenkin kysymykseen voi potenssilukujen laskusääntöjen avulla vastata, vaikka alkuperäisestä sähkötehosta tai tuulen nopeudesta ei olisi mitään tietoa.

:::{admonition} Ratkaisu
:class: tip, dropdown
Merkitään alkuperäistä tehoa $P_1$ ja tuulen nopeutta $v$. Matemaattisesti "teho on verrannollinen tuulen nopeuden kolmanteen potenssiin" voidaan kirjoittaa $P_1=kv^3$, missä $k$ on verrannollisuuskerroin. Kerroin $k$ riippuu tuulivoimalan hyötysuhteesta, siivekkeen pituudesta ym. ominaisuuksista, eikä tässä tarvitse tietää sen lukuarvoa.

Uusi tuulen nopeus on 90 % alkuperäisestä eli $0.9 v$. Tällöin uudeksi tehoksi tulee $P_2=k\cdot(0.9 v)^3 = k\cdot 0.9^3 v^3 = 0.729 kv^3 = 0.729 P_1$. Teho siis pienenee noin 100 % - 73 % = 27 % riippumatta siitä, mikä alkuperäinen teho tai tuulen nopeus oli.
:::

### Määritelmä

Ilmaus ”$a$ potenssiin $n$” eli $a^n$ tarkoittaa kertolaskua $a \cdot a \cdot \ldots \cdot a$, missä tekijöitä on $n$ kappaletta. Lukua $a$ kutsutaan kantaluvuksi. Se voi olla luku, kirjain tai jokin lauseke. Luku $n$ on nimeltään eksponentti. Se on yleensä jokin kokonaisluku, mutta laskimet osaavat käsitellä myös sellaisia potenssilausekkeita, joissa eksponentti on desimaaliluku.

Esim. $5\cdot 5 \cdot 5 \cdot 5 \cdot 5 \cdot 5=5^6$

Esim. $8^3=8 \cdot 8 \cdot 8=512$

Potenssiin korotus koskee sulkujen sisällä olevaa lukua tai lauseketta kokonaisuudessaan. Jos kantaluku on negatiivinen, niin laskun lopputulos on positiivinen silloin, kun eksponentti on parillinen luku, ja negativiinen silloin, kun eksponentti on pariton luku. Jos potenssiluvun edessä kuitenkin on miinusmerkki ilman sulkuja, niin miinusmerkki ei kuulu mukaan kantalukuun, vaan se otetaan mukaan potenssilaskun lopputuloksen kertoimeksi.

Esim. $(-2)^4=(-2) \cdot (-2) \cdot (-2) \cdot (-2)=16$, mutta $-2^4=-(2\cdot 2 \cdot 2 \cdot 2) =-16$

Esim. $(1+3)^2=(1+3) \cdot (1+3)= 4\cdot 4=16$


Mille tahansa kantaluvulle $a$ (paitsi nolla) on määritelty sääntö: $a^0=1$. Säännön voi perustella seuraavaksi esiteltävillä potenssilukujen laskusäännöillä. Lisäksi on määritelty, että negatiivinen eksponentti muuttaa potenssiluvun käänteisluvukseen: $a^(-n)=\frac{1}{a^n}$.

Esim. $2^{-3}=\frac{1}{2^3} = \frac{1}{8}$

Esim. $(-2)^{-3}=\frac{1}{(-2)^3} = \frac{1}{(-8)}=-\frac{1}{8}$

### Laskusäännöt

Potenssilausekkeille on olemassa seuraavat laskusäännöt:

**1. Tulon potenssi on sama kuin potenssien tulo:** $(ab)^n=a^n \cdot b^n$

:::{admonition} Perustelu
:class: tip, dropdown

Kirjoitetaan tulon $ab$ potenssiinkorotus auki potenssiluvun määritelmän mukaisesti:
$(ab)^n = ab\cdot ab\cdot \ldots \cdot ab$

Kertolaskussa tulon tekijät järjestellä vapaasti. Kirjoitetaan siis kertolasku siten, että kaikki $n$ kappaletta lukua $a$ ovat laskussa ensin, ja perässä tulevat kaikki $n$ kappaletta lukua $b$.

$ab\cdot ab\cdot \dots \cdot ab= a\cdot a\cdot \ldots \cdot a \cdot b \cdot b \cdot \ldots \cdot b$

Nyt kertolaskun alussa on potenssiluvun määritelmän mukaisesti $a^n$, ja lopussa $b^n$. Lasku voidaan siis lyhyemmin kirjoittaa $a^n \cdot b^n$.

:::

Sama laskutoimitus voidaan siis laskea kahdella eri tavalla. Esimerkiksi $(4\cdot3)^2$ voidaan laskea joko laskemalla ensin tulo $4\cdot 3 = 12$ ja korottamalla se sitten potenssiin $2$, jolloin saadaan $12^2=144$, tai korottamalla erikseen luvut $4$ ja $3$ toiseen potenssiin, ja kertomalla sitten nämä luvut keskenään: $4^2\cdot 3^2=16\cdot 9=144$.

Usein tehtävien ratkaisujen välivaiheissa tarvitaan tätä sääntöä ilmaistuna vähän eri tavalla: tulon potenssiin korotuksessa kaikki tulon tekijät, eli suluissa olevat luvut tai kirjaimet, pitää korottaa eksponentin määräämään potenssiin.

Esim. $(2x)^3=2^3  \cdot x^3=8\cdot x^3$

Esim. $5(4z)^2=5 \cdot 4^2 \cdot z^2=5 \cdot 16 \cdot z^2=80z^2$

Laskusäännön avulla voidaan myös muokata lausekkeita yksinkertaisemmiksi. Jos kertolaskun tekijöinä on lukuja, joilla on keskenään sama eksponentti, niin kaikki nämä luvut voidaan yhdistää yhdeksi kertolaskuksi ja korottaa yhteisen eksponentin määräämään potenssiin.

Esim. $3^5\cdot x^2 \cdot y^5 = (3\cdot y)^5 \cdot x^2$

Esim. $x^2 y^2=(xy)^2$

**2. Osamäärän potenssi on sama kuin potenssien osamäärä:** $\left(\frac{a}{b}\right)^n=\frac{a^n}{b^n}$

Laskusääntö toimii vastaavalla tavalla kuin tulon potenssi: suluissa olevan jakolaskun voi laskea ensin ja suorittaa potenssiin korotuksen sitten, tai osamäärän luvut voi erikseen korottaa potenssiin ja laskea osamäärän lopuksi. Esimerkiksi $\left(\frac{36}{9}\right)^2$ voidaan laskea joko $4^2=16$ tai $\frac{36^2}{9^2}=\frac{1296}{81}=16$.

Kun jokin osamäärä korotetaan johonkin potenssiin, niin korotus tehdään sekä osoittajalle että nimittäjälle.

Esim. $\left(\frac{x}{2}\right)^3=\frac{x^3}{2^3} =\frac{x^3}{8}$

Laskusääntö toimii myös toisin päin: jos jakolaskussa on kaksi potenssilukua, joilla on sama eksponentti, niin jakolasku voidaan kokonaisuudessaan korottaa yhteisen eksponentin määräämään potenssiin.

Esim. $\frac{y^2}{3^2} = \left(\frac{y}{3}\right)^2$

Esim. $\frac{2x^5}{8z^5} = \frac{2}{8} \frac{x^5}{z^5} = \frac{2}{8} \left(\frac{x}{z}\right)^5 = \frac{1}{4} \left(\frac{x}{z}\right)^5$


**3. Samankantaisten potenssien kertolaskussa eksponentit lasketaan yhteen:** $a^m\cdot a^n=a^{m+n}$

Esim. $3^2 \cdot 3^3 $ voi laskea joko $3^{2+3} = 3^5=243$ tai $3^2 \cdot 3^3 = 9\cdot27=243$.

Esim. $x^5 \cdot x^3=x^{3+5}=x^8$

Esim. $(a+b)^{-2}\cdot (a+b)^2=(a+b)^{-2+2}=(a+b)^0=1$

**4. Samankantaisten potenssien jakolaskussa nimittäjän eksponentti vähennetään osoittajan eksponentista:** $\frac {a^m}{a^n}=a^{m-n}$

Esim. $\frac{4^3}{4^2}$ voidaan laskea joko $\frac{64}{16}=4$ tai $4^{3-2}=4^1=4$.

Esim. $\frac{y^5}{y^7} = y^{5-7}=y^{-2}= \frac{1}{y^2}$

**5. Potenssiluvun potenssiinkorotuksessa eksponentit kerrotaan keskenään:**  $(a^m )^n=a^{mn}$


Esim. $(x^3)^{-2}=x^{3\cdot(-2}=x^{-6}=\frac{1}{x^6}$

Tämä laskusääntö voi auttaa hyvin suurten ja hyvin pienten lukujen käsittelyssä. Sellaisia tulee eteen esimerkiksi fysiikan ongelmissa ja pinta-alojen tai tilavuuksien muunnoksissa.

:::{admonition} Kymmenpotenssilukujen lyhenteet
:class: tip, dropdown

tähän: nano, mikro, ...

Esimerkkinä pinta-alojen ja tilavuuksien muunnokset

:::

Esim. $(10^3)^2=10^{3\cdot 2}=10^6$

Esim. $(10^{-3})^{-4}=10^{-3\cdot(-4)}=10^{12}$


**Esimerkkejä laskusääntöjen yhdistelystä:**

1. $\left(\frac{6x}{3y}\right)^2=\frac{(6x)^2}{(3y)}^2 =\frac{6^2 x^2}{(3^2 y^2)}=\frac{36x^2}{9y^2} =4 \frac{x^2}{y^2}$

2. $\left(\frac{6x}{3y}\right)^2=\left(\frac{6}{3} \frac{x}{y}\right)^2=\left(2 \frac{x}{y}\right)^2= 2^2 \left(\frac{x}{y}\right)^2= 4 \frac{x^2}{y^2\$ 

3. $\frac{x^5 z}{z^6 x^3} = \frac{x^5}{x^3} \frac{z}{z^6} = x^{5-3} z^{1-6} =x^2 z^{-5} = \frac{x^2}{z^5}$


## Juurilausekkeet

**Pohdittavaksi** Neliöstä lohkaistaan pienempi neliö, jonka pinta-ala on $\frac{1}{8}$ alkuperäisestä pinta-alasta. Kuinka suuri on pienemmän neliön sivun pituus verrattuna alkuperäiseen?

:::{admonition} Ratkaisu
:class: tip, dropdown
Merkitään neliön alkuperäistä pinta-alaa $A$. Tällöin alkuperäinen sivun pituus on $x=\sqrt{A}$. Uusi pinta-ala on $\frac{A}{8}$. Uuden sivun pituus on $\sqrt{\frac{A}{8}}=\frac{\sqrt{A}}{\sqrt{8}}=\frac{\sqrt{A}}{2.83}=\frac{1}{2.83} x$. Sivu on siis noin $\frac{1}{2.83} x = 0.35 x$.
:::

**Pohdittavaksi** Tuulivoimalan tuottama sähköteho on fysiikan lakien mukaisesti verrannollinen tuulen nopeuden kolmanteen potenssiin. Kuinka paljon tuulen nopeuden pitäisi kasvaa, jotta tuulivoimalan teho kaksinkertaistuisi?

:::{admonition} Ratkaisu
:class: tip, dropdown

Merkitään alkuperäistä tehoa $P=kv_1^3$, missä $k$ on verrannollisuuskerroin ja $v_1$ alkuperäinen tuulen nopeus. Uusi teho on $2P=kv_2^2$, missä $v_2$ on tämän tehon saavuttamiseksi tarvittava tuulen nopeus. Näistä saadaan yhtälö $2 kv_1^3=kv_2^3$, josta ratkeaa $v_2=\sqrt[3]{2v_1^3}=\sqrt[3]{2}v_1 = 1.26 v_1$. Tuulen nopeuden pitäisi kasvaa vain 26 % alkuperäisestä.
:::


### Määritelmä



### Laskusäännöt

### Murtopotenssit


<!-- #endregion -->








