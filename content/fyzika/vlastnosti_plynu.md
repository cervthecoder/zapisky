+++

title="Vlastnosti plynů"

date=2021-02-08

+++

### Ideální plyn

- model, který se snadno popisuje

1. Rozměry molekul ideálního plynu jsou ve srovnání se střední velikosti vzdálenosti molekul od sebe zanedbatelně malé $\to$ **Je dokonale stlačitelný**
2. Molekuly ideálního plynu mimo vzájemné srážky na sebe vzájemně nepůsobí
3. Vzájemné srážky molekul ideálního plynu a srážky srážky těchto molekul se stěnou nádoby jsou dokonale pružné

### Ekvipartiční theorém

- Střední kinetická energie jednoatomové molekuly ideálního plynu

  $\to$ $E_k=\frac{3}{2}kT$

- jednoatomová molekula má $3$ stupně volnosti $\to$ vykonává pohy, který se dá popsat 3 souřadnicemi

- jeden stupeň volnosti $\to$ $\frac{kT}{2}$

- Pro plyn složení z dvouatomových molekul je jiný vztah

- Má 3 stupně volnosti pro translační pohyb $x, y, z$

- A poté má 3 stupeň volnosti pro rotační pohyb, z toho jeden se "spotřebuje na vazebnou podmínku"

- $\to$ 5 stupňů volnosti $\to$ $E_k=\frac{5}{2}kT$ (pokud nevykonává vibrační pohyb)

- celkový počet stupňů volnosti pro molekulu $\to$ $f$

- $E_k=\frac{f}{2}kT$

  ![](https://github.com/cervthecoder/github_images/blob/master/Screenshot%202021-03-08%20at%2014.01.13.png?raw=true)

**Střední kvadratická rychlost0**

$v_k=\sqrt{\frac{3kT}{m_0}}$

kde *k* $\to$ Boltzmanova konstanta; *T* $\to$ Termodynamická teplota; $m_0$ $\to$ hmotnost molekuly ideálního plynu

Vychází ze vztahů pro střední kinetickou energii molekuly ideální plynu

 $\to$ $E_0=\frac{1}{2}m_0v_k^2=\frac{3}{2}kT$



### Stavová rovnice pro ideální plyny (Clapeyronova rovnice)

- Spojuje stavové veličiny do jednoho vztahu pro popis ideálního plynu
- střední hodnota tlaku plynu $\to$ $p=\frac{1}{3}\frac{N}{V}m_0v_k^2$ ($v_k=\sqrt{\frac{3kT}{m_0}}$)
  - tlak $\to$ **Objemová hustota energie**
- $pV=NkT$ $\to$ $N=nN_a$
- $pV=nN_akT$ $\to$ $N_ak=R$ (Rienmanova konstanta)
- <u>$pV=nRT$</u>
- *Wander wallsova rovnice pro reálné plyny*

### Stavové změny

**Izotermický**

- změna stavu při konstantní teplotě

- *Boyleův-Mariottův zákon*

- předpokládáme, že se látkové množství nemění

- $pV=nRT$ $\to$ $pV=konst.$

- Tlak je energie na objem $\to$ vychází to v Joulech

  <img src="https://upload.wikimedia.org/wikipedia/commons/1/15/Izoterma.jpg" style="zoom:150%;" />

- $p=1/V$ - nepřímá úměrnost

**Izobarický**

- změna stavu při konstantním tlaku

- *Gay-Lussacův zákon*
  $$
  \begin{align*}
  pV&=nRT\\
  \frac{V}{T}&=\frac{nR}{p}\\
  \frac{V}{T}&= konst.
  \end{align*}
  $$
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/37/Izobara.jpg" style="zoom:150%;" />

  

**Izochorický**

- změna stavu konstantním objemu

- *Charlesův zákon*
  $$
  \begin{align*}
  pV&=nRT\\
  \frac{p}{T}&=\frac{nR}{V}\\
  \frac{p}{T}&=konst.
  \end{align*}
  $$
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Izochora.jpg" style="zoom:150%;" />

  **Adiabatický děj**

- při tomto ději neprobíhá tepelná výměna mezi plynem a okolím

- *Posionův zákon*

- $pV^k=konst.$

- *k* = poisonova konstanta = c/c = měrná tepelná kapicata plynu - 1. konstantní tlak 2. konstatní objem >1

  ![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/Adiabatic.svg/1024px-Adiabatic.svg.png)

> úkol - zakreslit grafy pro děje
>
> diagram V a T
>
> a diagramu P a T



### Práce plynů

- první termodynamický princip $\to \Delta U=Q+W$
- plyn koná práci, když zvětšuje objem
- $J/m^3 = Pa$
- práce, kterou vykoná plyn při izotermickém/izobarickém ději $\to \Delta W'=\Delta p\Delta V$

### Kruhový děj

- děj při, kterém se mění stav plynu tak, že se následně vrátí do svého původního stavu

![](https://github.com/cervthecoder/github_images/blob/master/Screenshot%202021-03-29%20at%2014.36.22.png?raw=true)

- práce z 1) do 2) je kladná
- práce z 2) do 1) je záporná
- kruhový děj lze charakterizovat pomocí přírustku vnitřní energie $\to \Delta U=0J$ (je nulový)

ohřívač - plyn od něj teplo přebírá ($Q_1$ - teplo dodané)

chladič - přebírá teplo od plynu ($Q_2$ - teplo odevzdané)

$W=Q_1-Q_2$



$Q=\Delta U + W'$

$Q=W'$



**účinnost**

$\theta=1-\frac{Q_2}{Q_1}=\frac{W'}{Q_1}$ 

- kdybychom byli schopni, aby teplo přijmuté bylo stejné jako to odevzdané, tak by byla účinnost 100%
- Druhý termodynamický princip nám toto však nedovoluje $\to$ nešlo by sestrojit perpetum mobile
- **nelze sestrojit tepelný periodicky pracující stroj, který by přijímal teplo od ohřívače a vykonával stejně velkou práci**

### Příklad 1.

Spočtěte teoretickou účinost, který by využíval rozdílu teplot ve vodě.

$\theta=1-\frac{T_1}{T_2}$

