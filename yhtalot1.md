# Esimerkkejä yhtälöistä

Tässä luvussa on lisää esimerkkejä yhtälöistä, joiden ratkaisu onnistuu edellisessä luvussa mainituilla menetelmillä. Kaikki tämän luvun yhtälöt ovat pohjimmiltaan ensimmäisen asteen yhtälöitä. Toisen asteen yhtälöt sekä trigonometriset yhtälöt käsitellään muissa luvuissa.

## Ensimmäisen asteen yhtälöt

Yhtälöä, jonka voi sieventää muotoon $ax=b$, missä $a \neq 0$, sanotaan ensimmäisen asteen yhtälöksi. Tällaiset yhtälöt ratkeavat käyttämällä pelkästään lukujen lisäämistä ja vähentämistä sekä luvuilla kertomista ja jakamista. 

Jos yhtälötyypille $ax=b$ haluaa opetella ulkoa valmiin ratkaisukaavan, se on $x=\frac{b}{a}$. Usein kuitenkaan yhtälöt eivät heti alkuun ole ensimmäisen asteen yhtälön perusmuodossa. Perusmuotoon päätyy automaattisesti niillä toimenpiteillä, joilla yhtälöä muutenkin ratkaisee, eli sopivilla yhteen-, vähennys-, kerto- ja jakolaskuilla. Osassa tämän sivun esimerkkejä nämä muokkaukset on kirjattu muistiin yhtälön viereen "temppuviivoilla" eli merkinnällä ||.

::::{admonition} Esimerkki

Ratkaise yhtälö $3x-7=x+2$ välivaiheineen.

:::{admonition} Ratkaisu
:class: tip, dropdown

Yhtälö ei aluksi näytä olevan ensimmäisen asteen yhtälön perusmuotoa $ax=b$ mutta ehkä se muuttuu sellaiseksi. Aloitetaan vähentämällä yhtälön molemmilta puolilta $x$, jotta saadaan tuntematonta $x$ vain toiselle puolelle yhtälöä:

$3x-7-x=x+2-x$

Sievennetään yhtälön molemmat puolet:

$2x-7=2$

Lisätään molemmille puolille $7$:

$2x-7+7=2+7$

Sievennetään:

$2x=9$

Nyt yhtälö ratkeaakin kaavalla $x=\frac{9}{2}$ tai huomaamalla, että luku $x$ saadaan yksin yhtälön toiselle puolelle, kun jaetaan yhtälö puolittain luvulla 2.

$\frac{2x}{2}=\frac{9}{2}$

Vastauksen voi halutessaan esittää myös desimaalilukuna $x=4.5$.

:::

::::

::::{admonition} Esimerkki

Ratkaise yhtälö $5x-3-2x-3=0$ kahdella eri tavalla.

:::{admonition} Ratkaisu
:class: tip, dropdown

Eräs vaihtoehto:

$5x-3-2x-3=0$

$3x-6=0$

$3x=6~\hspace{1cm} || :3 $

$x=2$

Toinen vaihtoehto:

$5x-3-2x-3=0$

$3x-6=0~\hspace{1cm} ||:3$

$x-2=0~\hspace{1cm} ||+2$

$x=2$

:::

::::

Jos tuntemattomia on yhtälössä sulkujen sisällä, ratkaisu kannattaa aloittaa poistamalla sulut polynomin laskusääntöjen mukaisesti.

::::{admonition} Esimerkki

Ratkaise yhtälö $5x-(4-6x)=3(2x-4)+7x$.

:::{admonition} Ratkaisu
:class: tip, dropdown

$5x-(4-6x)=3(2x-4)+7x$

$5x-4+6x=6x-12+7x$

$11x-4=13x-12~\hspace{1cm} ||-13x$

$-2x-4=-12~\hspace{1cm} ||+4$

$-2x=-8~\hspace{1cm} ||:(-2)$

$x=4$

:::

::::

Tuntemattomia saattaa olla myös murtolausekkeiden nimittäjissä. Jos yhtälön kumpikin puoli koostuu vain yhdestä termistä, voi yhtälön termit "kertoa ristiin": toiselle puolelle yhtälöä tulee vasemman lausekkeen yläpuolen ja oikean puolen alapuolen tulo, ja toiselle puolelle yhtälöä tulee vasemman lausekkeen alapuolen ja oikean lausekkeen yläpuolen tulo. Ristiin kertominen on harvinainen erikoistapaus! Muulloin kerrotaan yhtälöt molemmat sillä luvulla, joka halutaan pois nimittäjästä.

::::{admonition} Esimerkki

Ratkaise yhtälö $\frac{2}{4-x}=\frac{3}{1+3x}$.

:::{admonition} Ratkaisu
:class: tip, dropdown

Kumpikin puoli koostuu vain yhdestä murtolausekkeesta, joten voidaan kertoa ristiin. Yhtälö muuttuu muotoon $2(1+3x)=3(4-x)$. Sulut poistamalla saadaan muoto $2+6x=12-3x$, joka ratkeaa esimerkiksi seuraavasti:

$2+6x=12-3x~\hspace{1cm} ||+3x$

$2+9x=12~\hspace{1cm} ||-2$

$9x=10~\hspace{1cm} ||:9$

$x=\frac{9}{10}$

:::

::::

::::{admonition} Esimerkki

Ratkaise yhtälö $\frac{2}{x+1}+7=3$.

:::{admonition} Ratkaisu
:class: tip, dropdown

Tapa 1:

Aloitetaan kertomalla yhtälön molemmat puolet lausekkeella $x+1$ ja sievennetään.

$\frac{2}{x+1}+7=3$

$2+7(x+1)=3(x+1)$

$2+7x+7=3x+3$

$9+7x=3x+3$

Vähennetään molemmilta puolilta $3x$ ja sievennetään:

$9+4x=3$

$4x=-6$

Jaetaan molemmat puolet luvulla 4:

$x=-\frac{6}{4}$

$x=-\frac{3}{2}$

Tapa 2:

Aloitetaan vähentämällä molemmilta puolelta $7$ ja sievennetään:

$\frac{2}{x+1}+7-7=3-7$

$\frac{2}{x+1}=-4$

Kerrotaan molemmat puolet lausekkeella $x+1$ ja sievennetään:

$2=-4(x+1)$

$2=-4x-4$

Lisätään molemmille puolille $4$ ja sievennetään:

$6=-4x$

Jaetaan luvulla $-4$:

$\frac{6}{-4} = x$

Vaihdetaan yhtälön puolet ja sievennetään:

$x=-\frac{3}{2}$

:::

::::

::::{admonition} Esimerkki

Ratkaise yhtälöt a) $\frac{3}{x}=4$, b) $\frac{3}{x}-1=4-\frac{2}{x}$.

:::{admonition} Ratkaisu
:class: tip, dropdown

a) Nimittäjässä olevan muuttujan $x$ saa pois nimittäjästä kertomalla yhtälön molemmat puolet luvulla $x$:

$x\cdot \frac{3}{x}=4\cdot x$

Sievennetään molemmat puolet:

$3=4x$

Vaihdetaan yhtälön puolet toisin päin:

$4x=3$

Jaetaan molemmat puolet luvulla $4$:

$x = \frac{3}{4}$

b) Aloitetaan jälleen kertomalla yhtälön molemmat puolet luvulla $x$. Tällöin kummankin lausekkeen kaikki termit pitää kertoa kyseisellä luvulla!

$x\cdot(\frac{3}{x}-1)=x\cdot(4-\frac{2}{x})$

Poistetaan sulut eli sievennetään lausekkeet laskemalla kertolaskut:

$\frac{3x}{x}-x=4x-\frac{2x}{x}$

$3-x=4x-2$

Poistetaan vasemmalta puolelta luku $3$ vähennyslaskulla ja samalla vähennetään se myös oikealta:

$3-x-3=4x-2-3$

$-x=4x-5$

Poistetaan oikealta puolelta termi $4x$ vähennyslaskulla ja vähennetään se samalla myös vasemmalta:

$-x-4x=4x-5-4x$

$-5x=-5$

Lopuksi jaetaan molemmat puolet luvulla $-5$:

$x=1$

:::

::::

Ensimmäisen asteen yhtälössä voi olla myös kirjaimia, jotka on korotettu toiseen tai korkeampaan potenssiin. Yhtälö on silti ensimmäisen asteen yhtälö, jos ratkaistava muuttuja esiintyy ainoastaan potenssiin 1 korotettuna. Muita kirjaimia käsitellään samalla tavalla kuin lukuja, eli niitä voi lisätä ja vähentää, ja niillä voi kertoa ja jakaa yhtälön molempia puolia.

::::{admonition} Esimerkki

Ratkaise yhtälö $ax+8b=cx-d$.

:::{admonition} Ratkaisu
:class: tip, dropdown

$ax+8b=cx-d~\hspace{1cm} || -cx$

$ax+8b-cx=-d~\hspace{1cm} || -8b$

$ax-cx=-d-8b$

$x(a-c)=-d-8b~\hspace{1cm} || :(a-c)$

$x=\frac{-d-8b}{a-c}$

:::

::::

::::{admonition} Esimerkki

Ratkaise $h$ yhtälöstä $gh=\frac{1}{2}v^2$. 

:::{admonition} Ratkaisu
:class: tip, dropdown

Yhtälö on muuttujan $h$ suhteen ensimmäisen asteen yhtälö. Yhtälö ratkeaa jakamalla molemmat puolet kirjaimella $g$:

$gh=\frac{1}{2} v^2 $

$h=\frac{1}{2}\frac{v^2}{g}$

:::

::::

::::{admonition} Esimerkki

Ratkaise $b$ yhtälöstä $c=\frac{\pi r^2}{2a+b}$.

:::{admonition} Ratkaisu
:class: tip, dropdown

$c=\frac{\pi r^2}{2a+b}$

$c(2a+b)=\pi r^2$

$2ac+bc=\pi r^2$

$bc=\pi r^2-2ac$

$b=\frac{\pi r^2-2ac}{c}$

$b=\frac{\pi r^2}{c}-2a$

:::

::::