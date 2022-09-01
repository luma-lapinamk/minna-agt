<!-- #region -->
# Yleiset kolmiot

Vinokulmaisessa kolmiossa kaikki kulmat voivat olla teräviä, tai yksi kulma on tylppä ja kaksi teräviä. Kolmio pitää olettaa vinokulmaiseksi, jos ei ole erikseen kerrottu, että se on suorakulmainen. Kaikkia tässä osioissa esiteltyjä laskukaavoja voidaan käyttää myös suorakulmaisille kolmioille. Sen sijaan suorakulmaisen kolmion omia laskusääntöjä (Pythagoraan lause ja suorakulmaisen kolmion trigonometriset funktiot) voidaan käyttää vain suorakulmaisille kolmioille.
 
## Kolmioepäyhtälöt

Kolmioepäyhtälön avulla voidaan tarkistaa, onko kyseessä ylipäätään kolmio. Kolmion jokaisen sivun pitää yltää yhdistymään toisiinsa! Matematiikan merkinnöin tämä ilmaistaan siten, että jos sivujen pituudet ovat $a$, $b$ ja $c$, on seuraavien epäyhtälöiden oltava voimassa:

(1) $a+b>c$

(2) $a+c>b$

(3) $b+c>a$

**Esim.** Voivatko kolmion sivujen pituudet olla $a=20$, $b=40$ ja $c=50$? Tarkistetaan, ovatko kaikki kolme kolmioepäyhtälöä voimassa:

(1) $a+b=20+40=60,60>50$, OK

(2) $a+c=20+50=70,70>40$, OK

(3) $b+c=40+50=90,90>20$, OK

Kaikki epäyhtälöt toteutuvat, joten kolmion sivujen pituudet ovat mahdolliset.

**Esim.** Millä luvun a arvoilla janoista, joiden pituudet ovat $a$, $a+3$ ja $a+5$ voi muodostaa kolmion?

Ratkaistaan epäyhtälöt: 

(1)	$a+a+3>a+5 \leftrightarrow 2a+3>a+5 \leftrightarrow 2a-a>5-3 \leftrightarrow a>2$

(2)	$a+a+5>a+3 \leftrightarrow 2a+5>a+3 \leftrightarrow 2a-a>3-5 \leftrightarrow a>-2$

(3) $a+3+a+5>a \leftrightarrow 2a+8>a \leftrightarrow 2a-a>-8 \leftrightarrow a>-8$.

Ehdot (2) ja (3) täyttyvät kaikilla mahdollisilla sivun pituuksilla, sillä sivujen pituudet ovat varmasti positiivisia. Rajoitteeksi jää ehto (1) eli on oltava $a>2$.


## Sinilause

Käytetään seuraavissa määritelmissä alla olevan kuvan merkintöjä:

Sinilause: kulman sinin ja kulman vastaisen sivun pituuden suhde on vakio, siis 

sin⁡α/a=sin⁡β/b=sin⁡γ/c

Sinilauseen toinen esitystapa: 	a/sin⁡α =  b/sin⁡β =c/sin⁡γ 


:::{admonition} Sinilauseen perustelu
:class: tip, dropdown
Pinta-alan avulla
:::


Esim. Ratkaise sivun a  pituus, kun b=10 m,β=〖35〗^∘,α=〖52〗^∘
 
a/sin⁡α =  b/sin⁡β   ⇔┬ a=(b⋅sin⁡α)/sin⁡β  ⇔┬ a=10 m⋅sin⁡〖〖52〗^∘ 〗/sin⁡〖〖35〗^∘ 〗  ⇔┬ a=13.7 m


Esim. ratkaise kulma α, kun a=80 m,c=95 m,γ=〖45〗^∘

sin⁡α/a=sin⁡γ/c  ⇔┬  sin⁡α=a/c  sin⁡γ ⇔┬  sin⁡α=(80 m)/(95 m)⋅〖sin⁡45〗^∘ ⇔┬  sin⁡α=0.595⇔┬ α=〖36.5〗^∘

 
Esim. Ratkaise kuviosta sivun x pituus.
  
Sinilauseen käyttämiseksi pitäisi tietää ainoan tunnetun sivun vastaisen kulman suuruus. Koska kolmion kulmien summa on aina 〖180〗^∘, niin tuntematon kulma on 
〖180〗^∘-〖47〗^∘-〖39〗^∘=〖94〗^∘. 
Nyt sinilauseen perusteella

128/sin⁡94 =x/sin⁡47 ⇔x=128⋅sin⁡47/sin⁡94 ≈94

## Kosinilause

Kosinilause: tietyn kulman kyljet, kulman vastainen sivu ja kulman kosini ovat yhteydessä toisiinsa seuraavien yhtälöiden mukaisesti:
 
c^2=a^2+b^2-2ab cos⁡γ
b^2=a^2+c^2-2ac cos⁡β
a^2=b^2+c^2-2bc cos⁡α

:::{admonition} Kosinilauseen perustelu
:class: tip, dropdown
Pythagoraan lauseen avulla
:::

Esim. Ratkaise kuvan kolmiosta sivu a, kun tiedetään, että b=389,c=372,α=〖91.9〗^∘.  
Kosinilauseen nojalla a^2=b^2+c^2-2bc cos⁡α

a^2=〖389〗^2+〖372〗^2-2⋅389⋅372⋅cos⁡91.9

a^2=299300.639

a=547
 
Esim. Kuinka suuret ovat kolmion kulmat α,β,γ, kun sivujen pituudet ovat a=10,
b=7,c=5?

a^2=b^2+c^2-2bc cos⁡α □(⇔┬ ) b^2+c^2-2bc cos⁡α=a^2 ⇔┬-2bc cos⁡α=a^2-b^2-c^2 ⇔┬
cos⁡α=(a^2-b^2-c^2)/(-2bc) ⇔┬  cos⁡α=(〖10〗^2-7^2-5^2)/(-2⋅7⋅5) ⇔┬  cos⁡〖α=〗-0.371⇔┬
α=arccos⁡〖(-0.371)〗 ⇔┬ α=〖111.8〗^∘

b^2=a^2+c^2-2ac cos⁡β ⇔┬  cos⁡β=(b^2-a^2-c^2)/(-2ac) ⇔┬  cos⁡β=(7^2-〖10〗^2-5^2)/(-2⋅10⋅5) ⇔┬
cos⁡〖β=〗 0.76⇔┬ β=arccos⁡0.76 ⇔┬ β=〖40.5〗^∘

γ=〖180〗^∘-〖111.8〗^∘-〖40.5〗^(∘ )=〖27.7〗^∘


## Yleisen kolmion pinta-ala

Kolmion pinta-alan voi laskea seuraavalla kaavalla A=1/2 ab sin⁡α
 
Perustelu: kaikille kolmioille ala on 
A=(kanta⋅korkeus)/2=ah/2

Korkeus h saadaan Pythagoran lauseen avulla (sitä käytetään nyt vain suorakulmaiseen kolmioon, joka muodostuu piirtämällä vinokulmaiseen kolmioon korkeusjana h): sin⁡α=h/b, josta h=b sin⁡α. Siis ala on A=ah/2=1/2⋅a⋅b sin⁡α

Esim. kuvan kolmion pinta-ala on A=1/2⋅150 m⋅128 m⋅sin⁡〖〖32〗^∘ 〗=5087 m^2

 

Minkä tahansa kolmion pinta-ala A voidaan laskea myös ns. Heronin kaavan avulla:

A=√(d(d-a)(d-b)(d-c) )

missä a,b,c ovat kolmion sivujen pituudet ja d=1/2(a+b+c) on kolmion piirin puolikas.

 
Esim. Kolmion sivujen pituudet ovat 2, 3 ja 4. Lasketaan pinta-ala: 

d=1/2 (2+3+4)=9/2=4.5

A=√(4.5(4.5-2)(4.5-3)(4.5-4) )
A=√(4.5⋅2.5⋅1.5⋅0.5 )
A=√8.4375
A=2.9


 


 

 






<!-- #endregion -->

```python

```
