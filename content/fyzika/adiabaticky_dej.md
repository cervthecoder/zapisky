+++

title="Adiabatický děj"

date=2021-04-16

+++

- označuje se jako **Poissonův zákon** $\to pV^{\kappa}=konst.$
- kde $\kappa=\frac{c_p}{c_V}$ $\to$ *Possionova konstanta*

### Základní axiomatika adiabatického dějě

- Při adiabatickém ději nedochází k výměně tepla s okolím $\to$ $\Delta Q=0$
- z 1. termodynamického zákona poté výjde $\to$ $\Delta U=W$
- při adiabatickém stlačování, $\Delta V<0$, je práce konána na plynu. Vnitřní energie plynu se zvyšuje $\Delta U>0$. (plyn se ohřívá)
- Při rozpínání, $\Delta V>0$, plyn práci koná. Vnitřní energie se snižuje $\Delta U<0$. (plyn se ochlazuje)

### Poissonova konstanta

- tvrzení $\to$ $\kappa>1$

- Entalpii soustavy ideálního plynu lze vyjádřit jako $H=U + pV$

- pro izobarický proces lze zaměnit entalpii za teplo ($Q=H$)

  $\to$ $H=mc_p\Delta T$

- pro izochorický proces lze zaměnit vnitřní energii za teplo ($Q=U$)

  $\to U=mc_v\Delta T$

  1. $c_p=\frac{H}{m\Delta T}$
  2. $c_v=\frac{U}{m\Delta T}$

  $$
  \begin{align*}
  \kappa &=\frac{c_p}{c_v}\\
  \kappa& =\frac{\frac{H}{m\Delta T}}{\frac{U}{m\Delta T}}\\
  \kappa &= \frac{H}{U}
  \end{align*}
  $$

- z definice entalpie bude vždy platit $H>U$

- tedy, že $\kappa>1$

- tvrzení lze dokázat i přes vratný děj ideálního plynu

  ![](https://github.com/cervthecoder/github_images/blob/master/Mayer.png?raw=true)

- na diagramu vidíte 2 rozdílné izotermy
- proces $AB$ je izochorický $V=$ konst.
- proces $AC$ je izobarický
- Ve stavech $B$ a $C$  má plyn stejnou teplotu (leží na stejné isotermě)
- protože platí, že $T_1<T_2$, tak určitá část tepla bude absorbována plynem

- Pro proces $AB$ platí $\to$ $Q_{AB}=nC_V\Delta T$  ($C_V$: molární izochorická měrná tepelná kapacita )
- Pro proces $AC$ platí $\to$ $Q_{AC}=nC_p\Delta T$ ($C_P$: molární izobarická měrná tepelná kapacita)
- Pro jednotlivé procesy zapíšem 1. termodynamický princip
  1. $\Delta U_{AB}=Q_{AB} - W_{AB}$ ($W_{AB}=0 \to$ Není zde změna v objemu)
  2. $\Delta U_{AC}=Q_{AC}-W_{AC}$
- Bude tedy platit $Q_{AB}=Q_{AC}-W_{AC}$ $\to$ $nC_V\Delta T=nC_p\Delta T - p\Delta V$
- ze stavové rovnice objem lze vyjádřit jako $V=\frac{nRT}{p}$
- po dosazení do naší rovnice $\to$ $C_p-C_V=R$
- Z čehož vyplývá $C_p>C_V$
- Tomuto vztahu se říká **Mayerova relace**

