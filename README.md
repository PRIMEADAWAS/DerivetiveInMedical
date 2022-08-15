<!-- # Derivetive In Medicine

For assignment application of derivative in medicine -->

# Axon conduction velocity and structure by Rushton Differential Equation

##Introduction

> It was reasonable for people to think that why they need to learn mathematic in university because they think it will not use in the future, just do for an examination. However, Mathemetic have been using in every part of life but they do not notice about that due to knowledge was changed and adapted to easier to use and understand. This Document will use calculus to explain regarding medical knowledge in axon conduction velocity field.

##Basic knowledge about Axon

####Axon structure and action potential

> Neuron system separates by location in 2 areas central nervous system(CNS) and peripheral nervous system(PNS).The CNS is in brain and spinal cord. Also, PNS has long distant nerve transmit signal from extremity and organ to CNS.

<p align=center><img width=300 src='./images/cns.jpg'></p>

> Each neuron cell contains three major part such as dendrite, soma, and axon which some have myeline sheath. Normally, It has cell membrane which is phospholipid bilayers and seperates Na ion more in the outer cell and K ion more in the inner cell. In addition, axon membrane have Na and K channel which can control voltage in cell.

<!-- In additionally, they have three main type of channels. Firstly, Unconjugated or leakage channel which contains Na and K channel allow both K with Na pass through cell membrane by electric flow. Secondly, conjugated channel such as ligated, mechanic, and electric that have Na and K channel too. -->

<p align=center><img src='./images/neuronstructure.png'>
</p>

> When the stimuli come Na channel will open, Na pass through cell membrane make ion become more positive, then activate other Na channel to open, become threshold and lead to action potential induce other area to active state and reach to the target. If their have myeline sheath this process become faster due to saltatory conduction which mean they can jump pass myelinated areas that make conduction faster 10 time.

<p align=center>
<img width=400 src='./images/channel.jpg'>
      
<img width=400 src='./images/conduct.jpg'>
</p>

####Axon conduction velocity in CNS and PNS

> G-ratio is an important value in axon they can determine function and structural myelinated optimization which g value is the ratio of inner and total outer diameter of axon include myelin sheath thickness.

> In fact, Axon in PNS and CNS have optimized in difference g-ratio due to their own function. Almost PNS trend to adapt for rapid transmit sensory from organ to CNS as well as bring command from brain to control extremities such as grasp object, walk, and postural behavior.This PNS has average g-ratio about 0.6 which optimized for maximizing axon conduction velocity due to long distance transportation.

> However, In CNS optimal g-ratio was approximately 0.77 since the conduction velocity maximization is not the main criteria for structure optimize due to short distance and volume constriction. Also, they need an suitable adaptation for other function such as minimizing conduction delays, resist high pressure overload from skull and spine, and saving consumption energy.

<p align=center><img  width=300 src='./images/cnspns.png'></p>

> This two graphs illustrate the relationship between myelin sheath thickness and efficacy index(A), inner and outer diameter of axon(B) in both CNS and PNS.

<!--
<p align=center><img src='./images/VelocityRelation.png'></p> -->

<!-- $e^{i\pi} + 1 = A$

$\sum_(i=1)^n i^3=((n(n+1))/2)^2$

$\sum_{n=1}^{10} n^2$

$\frac{dx}{dt}$

$\log{_a}{n}$ -->

###Rushton formula

> From rushton experiment they get parameter that predict axon conduction velocity by structural diameter. In addition, they get optimal g-ratio 0.6 for the best conduction velocity

$$Conduction \space Velocity \space\space \alpha \space\space \frac{d}{D}\sqrt{\log{_e}\frac{D}{d}}$$

$d\space\space\space\space=$ Inner axon diameter
$D\space\space\space=$ Total outer axon diameter (inner diameter combine with myelin sheath thickness)

The definition of g-ratio ; $g=\frac{d}{D}$

$$CV \space\space \alpha \space\space g\sqrt{(-\ln{g})}$$
Formular:
$$CV = kg\sqrt{(-\ln{g})}$$

$CV\space=$ Conduction velocity of axon
$k\space\space\space\space=$ Conduct constant
$g\space\space\space\space=\displaystyle\frac{d}{D}$ ; The ratio between inner and outer axon diameter
$d\space\space\space\space=$ Inner axon diameter
$D\space\space\space=$ Total outer axon diameter (inner diameter combine with myelin sheath thickness)

> To get maximum velocity we differentiation this equation to get crecent point where slope was zero

$$k\frac{\partial }{\partial g} (g\sqrt{(-\ln{g})}) = 0$$

$$g( \frac{\partial \sqrt{(-\ln{g})}}{\partial g}) + \frac{\partial g}{\partial g} (\sqrt{(-\ln{g})})= 0$$

$$g[ \frac{1}{2\sqrt{(-\ln{g})}}\frac{\partial {(-\ln{g})}}{\partial g}] +  \sqrt{(-\ln{g})}= 0$$

$$g[ \frac{1}{2\sqrt{(-\ln{g})}}(-\frac{1}{g})] +  (\sqrt{(-\ln{g})})= 0$$

<!-- $$\sqrt{(-\ln{g})} [1+\frac{1}{2\ln{g}}]=0$$ -->

<!-- $$\sqrt{(-\ln{g})}=0$$
$$\ln{g}=0$$
$$g=e^0=1$$

g cannot become 1 because this is myelinated axon -->

<!-- $$ 1+\frac{1}{2\ln{g}}=0$$ -->

$$ \sqrt{(-\ln{g})}= \frac{1}{2\sqrt{(-\ln{g})}} $$

$$ (\sqrt{(-\ln{g})})^2= \frac{1}{2} $$

$$-\ln{g}=\frac{1}{2}$$

$$\log{_e}{g}=-\frac{1}{2}$$

$$g=e^{-1/2}=\frac{1}{\sqrt{e}}=\frac{1}{2.71828...}$$

$$g=0.60653...$$

> G value 0.6 can create highest value for this function

<p align=center><img  width=300 src='./images/graph.png'></p>

> Example graph demonstate if K=1

####Conclusion

> Taking everything into consideration, the g ratio

<!-- - <img src="https://latex.codecogs.com/gif.latex?O_t=\text { Onset event at time bin } t " />
- <img src="https://latex.codecogs.com/gif.latex?s=\text { sensor reading }  " />
- <img src="https://latex.codecogs.com/gif.latex?P(s | O_t )=\text { Probability of a sensor reading value when sleep onset is observed at a time bin } t " /> -->

####Referrence

> Ref:Rushton W.A.H. A theory of the effects of fibre size in medullated nerve. J. Physiol. 1951;115:101–122.

> image ref:
> https://cdn1.byjus.com/wp-content/uploads/2020/02/STRUCTURE-OF-NEURON.png
> https://www.getbodysmart.com/wp-content/uploads/2017/09/Proteins-Axon-Structure-and-Functions-Labeled-770x500.png
> https://biology12plo.weebly.com/peripheral-nervous-system-pns.html
