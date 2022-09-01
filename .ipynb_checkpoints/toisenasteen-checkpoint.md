<!-- #region -->
## Toisen asteen polynomimalli

Toisen asteen polynomimalli on muotoa $y=ax^2+bx+c$. Tällaisen mallin kuvaama asia ei kasva tai pienene tasaisesti, vaan kasvu- tai pienenemisnopeus vaihtelee. Lisäksi mallilla on jokin minimi- tai maksimikohta. Tällaiset matemaattiset mallit liittyvätkin usein tapauksiin, joissa halutaan löytää yhtälön kuvaamalle ilmiölle mahdollisimman pieni tai suuri arvo.

### Funktion muoto ja ääriarvot

Funktion kuvaaja on ylöspäin aukeava paraabeli (”kuoppa”), jos $a>0$, ja alaspäin aukeava paraabeli (”mäki”), jos $a<0$. Ylöspäin aukeavalle paraabelille voidaan löytää pienin mahdollinen arvo (”kuopan pohja”), ja alaspäin aukeavalle paraabelille voidaan löytää suurin mahdollinen arvo (”mäen huippu”).

Minimi- tai maksimikohdan x-koordinaatti voidaan laskea yhtälöstä 

$2ax+b=0$

ja vastaava minimi- tai maksimiarvo y saadaan sijoittamalla kyseinen x:n arvo polynomimallin lausekkeeseen. Kyseistä $x$:n arvoa sanotaan funktion ääriarvokohdaksi (tai minimikohdaksi tai maksimikohdaksi) ja vastaavaa polynomin arvoa funktion ääriarvoksi (tai minimiarvoksi tai maksimiarvoksi).

Ääriarvon voi laskea myös suoraan kaavalla $y=c-\frac{b^2}{4a}$.

:::{admonition} Laskukaavojen perustelu
:class: tip, dropdown

Graafisesti tai derivaatan avulla.

:::

**Esim.** Funktiolla $y=-2x^2+3x+10$ on maksimi pisteessä, jossa $2\cdot (-2)\cdot x+3=0$ eli $-4x+3=0$, josta saadaan $x=\frac{3}{4}$. Kyseisessä pisteessä funktion arvo on $y=-2\cdot(\frac{3}{4})^2+3\cdot \frac{3}{4}+10=11.125$. Sama arvo saadaan myös laskemalla $y=10-\frac{3^2}{4\cdot(-2)}=10-(-\frac{9}{8})=10+\frac{1}{8}=11.125$.

 
**Esim.** Uuden puhelinmallin hinta on $x$ €, ja valmistuskulut 50 €. Markkinatutkimuksen mukaan puhelimien myynti riippuu hinnasta lausekkeen $50 000-100x$ mukaisesti. Millä myyntihinnalla saisi maksimituoton?

Kirjoitetaan ensin yhtälö, joka kuvaa myynnistä saatavia tuloja. Myyntitulot saadaan kertomalla yhden puhelimen hinta myytyjen puhelinten lukumäärällä, siis $x(50000-100x)$. Tämä voidaan sieventää muotoon $50000x-100x^2$.

Vastaavat valmistuskulut saadaan kertomalla yhden puhelimen valmistuskulut puhelinten lukumäärällä. Kulut ovat siis $50\cdot(50000-100x)=2 500 000-5000x$.

Tuotto $y$ saadaan, kun vähennetään kulut tuloista: $y=50 000 x-100x^2-2 500 000+5000 x=-100x^2+55 000x-2 500 000$

Tämän funktion maksimikohta saadaan yhtälöstä $2ax+b=0$ eli $-2⋅100\cdotx+55 000=0$, josta ratkeaa $x=\frac{-55 000}{-200}=275$.
Hinnan pitäisi siis olla 275 €. Tällöin tuotto on $y=-100\cdot 275^2+55 000\cdot275-2 500 000=5 062 500$.



<!-- #endregion -->
