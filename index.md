## Welcome to Materials Dataset 

This webpage is developed based on [Jekyll](https://jekyllrb.com/), and maintain by [Dr. XIONG Jie](https://www.researchgate.net/profile/Jie-Xiong-8).

The datasets are related to metallic materials including steels, metallic glasses, and high entropy alloys



### The Steels Dataset

The original data were colleted from [NIMS database](https://mits.nims.go.jp/en/), and cleaned data are available on [steel dataset](https://github.com/George-JieXIONG/Materials-Dataset/blob/main/Chapter4/NIMS-Fatigue.csv).

This dataset contains 360 data samples comprised 16 features of three heat-treatment temperatures, nine alloying elements, one reduction ratio, three inclusions 
and four target properties of fatigue strength, tensile strength, fracture strength, and hardness.

```markdown

Features are described as following
NT (Normalizing Temperature °C) 825-900
QT (Quenching Temperature °C) 825-865
TT (Tempering Temperature °C) 550-680
C (wt% of Carbon) 0.28-0.57
Si (wt% of Silicon) 0.16-0.35
Mn (wt% of Manganese) 0.37-1.3
P (wt% of Phosphorus) 0.007-0.031
S (wt% of Sulphur) 0.003-0.03
Ni (wt% of Nickel) 0.01-2.78
Cr (wt% of Chromium) 0.01-1.12
Cu (wt% of Copper) 0.01-0.22
Mo (wt% of Molybdenum) 0-0.24
RR (Reduction ratio) 420-5530
dA (Plastic work-inclusions) 0-0.13
dB (discontinuous array-inclusions) 0-0.05
dC (isolated inclusions) 0-0.04

```
On these 16 features, machine models were built to predict the meachnical properties of steels. The developed models showed good predictive power.
![](https://github.com/George-JieXIONG/Materials-Dataset/blob/gh-pages/img/NIMS-All-Best.png)

For more detailes see the Article [Machine learning of mechanical properties of steels](https://link.springer.com/content/pdf/10.1007/s11431-020-1599-5.pdf)

### The Metallic Glasses Dataset

The original data were colleted from several related studies and the LB handbook on amorphous ternary alloys. These data covered variables such as glass forming ability (GFA), critical casting diameter(Dmax), critical transition temperatures (CTT) and elastic properties (EM), and cleaned data are available on [metallic glasses dataset](https://github.com/George-JieXIONG/Materials-Dataset/blob/main/Chapter5).

The training sets represented a wide range of elements, including metals and metalloids, with the GFA and Dmax datasets containing 54 elements, the CTT datasets containing 42 elements, and the EM datasets containing 48 elements.
```markdown

Features are described as following
NT (Normalizing Temperature °C) 825-900
QT (Quenching Temperature °C) 825-865
TT (Tempering Temperature °C) 550-680
C (wt% of Carbon) 0.28-0.57
Si (wt% of Silicon) 0.16-0.35
Mn (wt% of Manganese) 0.37-1.3
P (wt% of Phosphorus) 0.007-0.031
S (wt% of Sulphur) 0.003-0.03
Ni (wt% of Nickel) 0.01-2.78
Cr (wt% of Chromium) 0.01-1.12
Cu (wt% of Copper) 0.01-0.22
Mo (wt% of Molybdenum) 0-0.24
RR (Reduction ratio) 420-5530
dA (Plastic work-inclusions) 0-0.13
dB (discontinuous array-inclusions) 0-0.05
dC (isolated inclusions) 0-0.04

```
On these 16 features, machine models were built to predict the meachnical properties of steels. The developed models showed good predictive power.
![](https://github.com/George-JieXIONG/Materials-Dataset/blob/gh-pages/img/NIMS-All-Best.png)

For more detailes see the Article [Machine learning of mechanical properties of steels](https://link.springer.com/content/pdf/10.1007/s11431-020-1599-5.pdf)

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
