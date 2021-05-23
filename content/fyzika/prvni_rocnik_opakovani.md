+++

title="Opakování fyziky 1. ročník"

date=2021-05-21

+++

## 1. Pohyb po kružnici

- nejjednodušší příklad křivočarého pohybu
- poloha tělesa (hmotného bodu) na kružnici je určena **průvodičem** $\to$ je to v podstatě poloměr kružnice
- Pokud přejde těleso z bodu $A$ do $B$ po kružnici, tak průvodič opíše úhel $\phi$ a urazí dráhu $s$

<img src="https://github.com/cervthecoder/github_images/blob/master/Screenshot%202021-05-22%20at%2020.25.08.png?raw=true" style="zoom: 50%;" />

- úhel se udáva v jednotkách **radiány** [$rad$], lze použít i stupně [$^\circ$]

  $360^\circ=2\pi$ $rad$

- **radián je úhel, který by průvodič opsal, pokud by po kružnici ušel vzdálenost jednoho poloměru**

- Obvod kružnice $\to o=2\pi r$ $\to$ **Dvakrát obtáhneme poloměr po obvodu kružnice**

### Úhlová rychlost [$rad/s$]

- úhel $\phi$, který průvodič opíše za čas $t$ $\to \omega$ 

  $\omega = \frac{\phi}{t}$

- Pokud známe čas za, který těleso opíše kružnici celou, tak ho značíme $T$

  výpočet úhlové rychlosti $\omega = \frac{2\pi}{T}$ ($2\pi$ je $360^\circ$)

- **Frekvence** $\to$ počet kmitů za sekundu $f=\frac{1}{T}$ $\to \omega=2\pi f$

### Obvodová rychlost [$m/s$]

- dráha, kterou těleso doopravdy urazí (průvodič opíše po kružnici)

  (úhel x poloměr)/ čas $\to$ $v = \frac{\phi r}{t} = \omega r$

- Pokud známe čas oběhu kolem celé kružnice $\to v=\frac{2\pi r}{T}$ ($2\pi r \to$ obvod kružnice)

### Do/Odstředivé zrychlení

$a_d = \frac{v^2}{r}$

- těleso zrychluje neustále ke středu kružnice jinak by odletělo tečnou po kružnici

- z Newtonova 1. pohybového zákona $F=m\cdot a$

  $\to$ Od/Dostředivá síla $F=m\frac{v^2}{r}$

## 2. Gravitační pole

### Newtonův grav. zákon

$F=G\frac{Mm}{r^2}$

- gravitační silové působení mezi tělesy je vždy vzájemné

- Velikost gravitační síly, kterou působí jedno těleso na druhé je stejná jako velikost gravitační síly kterou působí druhé těleso na první

- gravitační konstanta $\to$ $G=6.67 \cdot 10^{-11}N/kg^2\cdot m^2$ - někdy označovaná jako $\kappa$

- gravitační zrychlení z newtonova G. zákona při povrchu země

  $m \cdot g = G\frac{Mm}{r^2}/:m$

  $g=G\frac{M}{r^2}$

  $g\approx10\frac{m}{s^2}$

## 3. Tíha a tíhová síla

### Tíhová síla [$N$]

- vzniká působením gravitačního (tíhového) podle země na těleso
- značí se - $F_g$
- $F_g=m\cdot g$

### Tíha

- působení tělesa v gravitačním poli země na jiná tělesa
- značí se $G$
- $G=m\cdot g$

## 4. Pohyby těles v homogenním poli Země (vrhy)

- homogenní tíhové pole - zanedbáváme změnu tíhového zrychlení

### Svislý vrh

- těleso vrženo počáteční rychlostí $v_0$ přímo proti působení tíhového zrychlení
- velikost rychlosti se zpomaluje, jak těleso cestuje vzhůru, až je v jednom bodě nulová $v_0=0 m/s$
- Poté letí zase dolů
- Výška, které těleso dosáhne za čas $t$ $\to$ $y = v_0t-1/2gt^2$
- Njevětší výška, které těleso $\to$ $h=v^2/2g$
- Doba pohybu tělesa $\to$ $t=2\sqrt{2h/g}=2v_0/g$

<img src="https://www.dopocitej.cz/files/vrh_svisly_vzhuru.jpg" style="zoom:150%;" />

### Vodorovný vrh

<img src="https://lh3.googleusercontent.com/proxy/VIVmSxNbchUgOHw2uByNNXjhn_ri4ofNpxwdBgZNhbzQeNIkTueFxv7-uHWIc4jLizXt0Pm0qVmzREQYd4sBykN1OXf0Mu6H4qg4vUk-jMX5UE5ZqM15U16vpCylejc7kCBiqp24z3N9xh6wPTBc-xr23BU" style="zoom:150%;" />

### Šikmý vrh

<img src="https://lh3.googleusercontent.com/proxy/crJKY3M0pcwO_2rNcSB0tLErq1mGzfLsIdBYFXC-vmNC6dQE5s7swrZHvBcyCFjoe-f7zI7IruHmaP6yWbBVbpuEpfFWINyFdYoGmBJdhyWPyQCpSVd3PJ1y3ZX_9t-GH3Srf0ga4XBWUp5HEggbwdCPh50" style="zoom: 150%;" />

## 5. Pohyby v centrálním poli země

### 1. Kosmická rychlost

- Pohyb kolem země po kružnici $\to$ **1. Kosmická rychlost**

- Dostředivá síla = gravitační síle
  $$
  \begin{align*}
  	F_g &=F_d\\
  	G\frac{Mm}{r^2} &= \frac{mv^2}{r}\\
  	G\frac{M}{r} &= v^2\\
  	v=\sqrt{G\frac{M}{r}}
  \end{align*}
  $$

- říká se jí také kruhová síla $v_k$

### 2. Kosmická rychlost

- hranice, při které se stává trajektorie tělesa parabolická a opouští zemi

- Někdy se také nazývá parabolická rychlost, nebo úniková rychlost

  $v_p=\sqrt{2}v_k$

### 3. Kosmická rychlost

- těleso se při této rychlosti vymaní z gravitačního pole slunce
- opouští sluneční soustavu
- Někdy se také nazývá hyperbolická rychlost (hyperbolická dráha)

<img src="http://www.fyzika007.cz/_/rsrc/1472857156843/gravitacni-pole/pohyby-teles-v-centralnim-gravitacnim-poli-zeme---druzice-a-sondy/kosmickerychlosti.jpg" style="zoom:150%;" />

## 6. Moment síly [$N\cdot m$]

- vyjadřuje otáčivý účinek síly působící na těleso, které se otačí kolem nehybné osy

  $M=F\cdot d=F\cdot r \cdot sin(\alpha)$

<img src="http://fyzika.jreichl.com/data/M_tuheteleso_soubory/image008.png" style="zoom: 150%;" />

## 7. Skládání sil

- vektorové sčítání
- Určujeme graficky, či pomocí analytické geometrii

- síly, které působí z jednoho počátečního bodu naskládáme za sebe a následně z počátečního bodu vedeme úsečku do koncového bodu z posledního vektoru
- pokud skládáme 2 různoběžné síly, tak hledáme úhlopříčku kosodelníku, kterou by tyto dvě "strany" vytvořily

<img src="https://fyzika-marsovska.webnode.cz/_files/200000024-3a2e83b28e/sily3.JPG" style="zoom:67%;" />

## 8. Rozkládání sil

- Udává se **výslednice** $F$ sil a jedna složka $F_n$ $\to$ předpokládáme, že výslednice vytvoří úhlopříčku daného kosodelníku
- Grafické řešení









## 9. Moment dvojice sil

- **dvojice sil** - síly, které jsou rovnoběžné, stejně velké, ale opačně orientované a nemají společný počáteční bod $\to$ způsobují **otačívý pohyb**

  platí tedy, že $F_1=F_2=F_d$

- výpočet momentu $\to$ $D=Fd$, kde $d$ je vzdálenost počátečních bodů těchto sil

<img src="http://fyzika.jreichl.com/data/M_tuheteleso_soubory/image036.png" style="zoom:200%;" />

## 10. těžiště, rovnovážné polohy tělesa

### Těžiště tuhého tělesa

- tuhé těleso je složené z mnoha hmotných bodů (bezrozměrný fyzikální model, který má hmotnost)

- Na jednotlivé hmotné body působí síly (tíhové) $\to F_1, F_2, F_3....F_n$

- výslednice těchto sil $F_g$ má počáteční bod v těžišti $T$

  <img src="https://github.com/cervthecoder/github_images/blob/master/IMG_6437.jpg?raw=true" style="zoom: 25%;" /> 

- Poloha těžiště v tělese je stálá a závisí na rozložení látky v tělese

### Rovnovážné polohy tělesa

- zavěšené, či podepřené těleso je v rovnováze, pokud $F_g$ směřující z těžiště prochází bodem závěsu a těleso je v klidu
- **Rozeznáváme 2 druhy rovnováhy**
  1. **Statická rovnováha** $\to$ výsledná síla působící na těleso je nulová, těleso však může rotovat kolem své osy
  2. **Dynamická rovnováha** $\to$ výsledná síla působící na tělso je nulová, ale těleso nesmí rotovat

<img src="http://fyzika.jreichl.com/data/M_tuheteleso_soubory/image094.png" style="zoom:150%;" />



