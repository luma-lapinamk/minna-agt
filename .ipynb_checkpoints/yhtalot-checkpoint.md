# Yhtälöiden ratkaisu

Yhtälössä on yhtäsuuruusmerkin eri puolilla kaksi lauseketta, joiden arvo on koko ajan yhtä suuri. Yhtälöitä ovat esimerkiksi $5x+7=4$ ja $V=π r^2 h$.  

Yhtälöissä on usein yksi kirjain, jota ei tunneta, esimerkiksi $x$. Mahdollisia muita kirjaimia pidetään tunnettuina, vaikkei niille olisi kerrottu mitään lukuarvoa.

Yhtälön ratkaisu perustuu siihen, että tuntematon kirjain pyritään saamaan sopivilla toimenpiteillä yksin jommallekummalle puolelle yhtäsuuruusmerkkiä. Nämä toimenpiteet pitää aina tehdä yhtä aikaa yhtälön kummallekin puolille. Esimerkkejä näistä toimenpiteistä ovat

- luvun lisääminen 
- luvun vähentäminen
- luvulla kertominen
- luvulla jakaminen.

Monimutkaisemmille yhtälöille voidaan tarvita näiden lisäksi myös potenssiinkorotusta tai juuren ottamista, logaritmia, trigonometrisia funktioita tai niiden käänteisfunktiota jne.

Jos siis yhtälön toisen lausekkeen arvoa muutetaan jollakin yllämainituista toimenpiteistä, on myös toisen lausekkeen arvoa samalla muutettava samalla tavalla. 

Yhtälön lausekkeita saa kuitenkin sieventää tai olla sieventämättä erikseen. Yhtälön vasemman ja oikean puolen saa aina vaihtaa keskenään.

Yhtälön ratkaisu kirjoitetaan siten, että yhtälö säilyy koko ajan muodossa ”vasen puoli = oikea puoli”. Jokaisen välivaiheen jälkeen tulee rivinvaihto tai ns. ekvivalenssinuoli ”⇔”. Laskutoimitukset voidaan merkitä “temppuviivojen” || viereen. Lopulta yhtälö muuttuu muotoon ”x=ratkaisu”. Yhtälön ratkaisua ei kannata aloittaa kirjoittamalla heti ensimmäisen rivin alkuun "x= ... ", sillä silloinhan ei vielä tiedä, mitä toiselle puolelle tulee!

Yhtälön ratkaisun voi tarkistaa sijoittamalla saamansa ratkaisun alkuperäiseen yhtälöön. Tällöin vasemman ja oikean puolen pitäisi olla samat.

## Ensimmäisen asteen yhtälöt

Yhtälöä, jonka voi sieventää muotoon $ax=b$, missä $a \neq 0$, sanotaan ensimmäisen asteen yhtälöksi. Tällaiset yhtälöt ratkeavat käyttämällä pelkästään lukujen lisäämistä ja vähentämistä sekä luvuilla kertomista ja jakamista.

**Esim.** Ratkaise yhtälö $3x-7=x+2$ välivaiheineen.

:::{admonition} Ratkaisu
:class: tip, dropdown

$3x-7=x+2~\hspace{3cm} ||~-x$

$3x-7-x=x+2-x$\hspace{3cm} ||~ \text{sievennetään}$

$2x-7=2\hspace{3cm} ||~+7$

$2x-7+7=2+7\hspace{3cm} ||~\text{sievennetään}$
	
$2x=9$\hspace{3cm} ||~:2$

$\frac{2x}{2}=\frac{9}{2}\hspace{3cm} ||~\text{sievennetään}$

$x=4.5$

:::

Toimenpiteiden järjestyksellä ei ole väliä. Joskus se tosin vaikuttaa ratkaisun pituuteen.

Esim. Ratkaise yhtälön $5x-3-2x-3=0$ kahdella eri tavalla.

:::{admonition} Ratkaisu
:class: tip, dropdown

Eräs vaihtoehto:

$5x-3-2x-3=0\hspace{3cm} ||\text{sievennetään}$

$3x-6=0 \hspace{3cm} ||~+6$

$3x=6\hspace{3cm} ||~:3$

$x=2$

Toinen vaihtoehto:	

$5x-3-2x-3=0\hspace{3cm} ||\text{sievennetään}$

$3x-6=0 \hspace{3cm} ||~:3$

$x-2=0 \hspace{3cm} ||~+2$

$x=2$
:::

Jos tuntemattomia on yhtälössä sulkujen sisällä, ratkaisu kannattaa aloittaa poistamalla sulut polynomin laskusääntöjen mukaisesti.

Esim. Ratkaise yhtälö $5x-(4-6x)=3(2x-4)+7x$.

:::{admonition} Ratkaisu
:class: tip, dropdown

$5x-(4-6x)=3(2x-4)+7x$

$5x-4+6x=6x-12+7x$

$11x-4=13x-12 \hspace{3cm} ||~-13x$

$-2x-4=-12\hspace{3cm} ||~+4$

$-2x=-8\hspace{3cm} ||~:(-2)$

$x=4$

:::

Tuntemattomia saattaa olla myös murtolausekkeiden nimittäjissä. Jos yhtälön kumpikin puoli koostuu vain yhdestä termistä, voi yhtälön termit ”kertoa ristiin”: toiselle puolelle yhtälöä tulee vasemman lausekkeen yläpuolen ja oikean puolen alapuolen tulo, ja toiselle puolelle yhtälöä tulee vasemman lausekkeen alapuolen ja oikean lausekkeen yläpuolen tulo.

Esim. Ratkaise yhtälö $\frac{2}{4-x}=\frac{3}{1+3x}$.

:::{admonition} Ratkaisu
:class: tip, dropdown

Kumpikin puoli koostuu vain yhdestä murtolausekkeesta, joten voidaan kertoa ristiin. Yhtälö muuttuu muotoon $2(1+3x)=3(4-x)$. Sulut poistamalla saadaan muoto $2+6x=12-3x$, joka ratkeaa esimerkiksi seuraavasti:

$2+6x=12-3x\hspace{3cm} ||~+3x$

$2+9x=12\hspace{3cm} || -2$

$9x=10\hspace{3cm} || :9$

$x=\frac{9}{10}$

:::

Esim. Ratkaise yhtälö $\frac{2}{x+1}+7=3$.

:::{admonition} Ratkaisu
:class: tip, dropdown

Aloitetaan kertomalla yhtälön molemmat puolet lausekkeelle $x+1$.

$\frac{2}{x+1}+7=3\hspace{3cm} ||~\cdot(x+1)$

$2+7(x+1)=3(x+1)$

$2+7x+7=3x+3$

$9+7x=3x+3\hspace{3cm} ||~-3x$

$9+4x=3\hspace{3cm} ||~-9$

$4x=-6\hspace{3cm}||~:4$

$x=-\frac{6}{4}$

$x=-\frac{3}{2}$

:::

Ensimmäisen asteen yhtälössä voi olla myös kirjaimia, jotka on korotettu toiseen tai korkeampaan potenssiin. Yhtälö on silti ensimmäisen asteen yhtälö, jos ratkaistava muuttuja esiintyy ainoastaan potenssiin 1 korotettuna.

**Esim.** Ratkaise $h$ yhtälöstä $gh=\frac{1}{2}v^2$. 

:::{admonition} Ratkaisu
:class: tip, dropdown

Yhtälö on muuttujan $h$ suhteen ensimmäisen asteen yhtälö. Yhtälö ratkeaa jakamalla molemmat puolet kirjaimella $g$:

$gh=\frac{1}{2} v^2 $

$h=\frac{1}{2}\frac{v^2}{g}$
:::

**Esim.** Ratkaise $b$ yhtälöstä $c=\frac{\pi r^2}{2a+b}$.

:::{admonition} Ratkaisu
:class: tip, dropdown

$c=\frac{\pi r^2}{2a+b}$

$c(2a+b)=\pi r^2$

$2ac+bc=\pi r^2$

$bc=\pi r^2-2ac$

$b=\frac{\pi r^2-2ac}{c}$

$b=\frac{\pi r^2}{c}-2a$

:::



