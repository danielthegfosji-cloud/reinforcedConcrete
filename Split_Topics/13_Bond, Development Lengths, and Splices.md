# Bond, Development Lengths, and Splices

### 7.1 Cutting Off or Bending Bars

The beams designed up to this point have been selected on the basis of maximum moments. These moments have occurred at or near span centerlines for positive moments and at the faces of supports for negative moments. At other points in the beams, the moments were less. Although it is possible to vary beam depths in some proportion to the bending moments, it is normally more economical to use prismatic sections and reduce or cut off some reinforcing when the bending moments are sufficiently small. Reinforcing steel is quite expensive, and cutting it off where possible may appreciably reduce costs.

Should the bending moment fall off 50% from its maximum, approximately 50% of the bars can be cut off or perhaps bent up or down to the other face of the beam and made continuous with the reinforcing in the other face. For this discussion, the uniformly loaded simple beam of Figure 7.1 is considered. This beam has six bars, and it is desired to cut off two bars when the moment falls off a third and two more bars when it falls off another third. For the purpose of this discussion, the maximum moment is divided into three equal parts by the horizontal lines shown. If the moment diagram is drawn to scale, a graphical method is satisfactory for finding the theoretical cutoff points.

For the parabolic moment diagram of Figure 7.1, the following expressions can be written and solved for the bar lengths  $x_1$  and  $x_2$  shown in the figure:

$$\frac{x_1^2}{(\ell/2)^2} = \frac{2}{6}$$

$$\frac{x_2^2}{(\ell/2)^2} = \frac{4}{6}$$

For different-shaped moment diagrams, other mathematical expressions would have to be written, or a graphical method used.

Actually, the design ultimate moment capacity

$$\phi M_n = \phi A_s f_y \left( d - \frac{a}{2} \right)$$

does not vary exactly in proportion to the area of the reinforcing bars, as is illustrated in Example 7.1, because of variations in the depth of the compression block as the steel area is changed. The change is so slight, however, that for all practical purposes, the moment capacity of a beam can be assumed to be directly proportional to the steel area.

It will be shown in this chapter that the moment capacities calculated as illustrated in this example problem will have to be reduced if sufficient lengths are not provided beyond the theoretical cutoff points for the bars to develop their full stresses.

![](_page_204_Figure_2.jpeg)

FIGURE 7.1 Theoretical cutoff locations for a simple span beam.

### Example 7.1

For the uniformly loaded simple beam of Figure 7.2, determine the theoretical points on each end of the beam where two bars can be cut off, and then determine the points where two more bars can be cut off.  $f_c' = 3000 \text{ psi}$ ,  $f_y = 60,000 \text{ psi}$ .

#### SOLUTION

When the beam has only four bars,

$$a = \frac{A_{\rm S}f_y}{0.85f_c'b} = \frac{(4.00~{\rm in.}^2)\,(60~{\rm ksi})}{(0.85)\,(3~{\rm ksi})\,(18~{\rm in.})} = 5.23~{\rm in.}$$
 
$$\phi M_n = \phi A_{\rm S}f_y\left(d-\frac{a}{2}\right) = (0.9)\,(4.00~{\rm in.}^2)\,(60~{\rm ksi})\left(27~{\rm in.}-\frac{5.23~{\rm in.}}{2}\right) = 5267~{\rm in-k} = 439~{\rm ft-k}$$

When the moment falls off to 439 ft-k, two of the six bars can theoretically be cut off.

![](_page_204_Figure_10.jpeg)

![](_page_204_Figure_11.jpeg)

**FIGURE 7.2** Given information for Example 7.1.

![](_page_205_Figure_2.jpeg)

**FI GU RE 7.3** Beam reactions.

When the beam has only two bars,

$$a = \frac{(2.00 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (3 \text{ ksi}) (18 \text{ in.})} = 2.61 \text{ in.}$$

$$\phi M_n = (0.9) (2.00 \text{ in.}^2) (60 \text{ ksi}) \left(27 \text{ in.} - \frac{2.61 \text{ in.}}{2}\right) = 2775 \text{ in-k} = 231 \text{ ft-k}$$

When the moment falls off to 231 ft-k, two more bars can theoretically be cut off, leaving two bars in the beam.

(Notice that <sup>ρ</sup> with 6 bars <sup>=</sup> 6.00 in.2/(18 in.) (27 in.) <sup>=</sup> 0.0123, which is less than <sup>ρ</sup>max <sup>=</sup> 0.0136 from Appendix A, Table A.7, so the beam is ductile and φ = 0.9. Also, this ρ is > ρmin of 200/60,000 psi = 0.00333.)

The moment at any section in the beam at a distance *x* from the left support is as follows, with reference being made to Figure 7.3:

$$M = 82.5x - (5.5x)\left(\frac{x}{2}\right)$$

From this expression, the location of the points in the beam where the moment is 439 ft-k and 231 ft-k can be determined. The results are shown in Figure 7.4.

**Discussion:** If the approximate procedure had been followed (where bars are cut off purely on the basis of the ratio of the number of bars to the maximum moment, as was illustrated with the equations on the previous page), the first two bars would have had lengths equal to 17.2 ft (as compared to the theoretically correct value of 16.16 ft), and the second two bar lengths would be equal to 24.45 ft (as compared to the theoretically correct value of 23.75 ft). It can then be seen that the approximate procedure yields fairly reasonable results.

![](_page_205_Figure_12.jpeg)

**FI GU RE 7.4** φ*Mn* diagram for beam in Example 7.1.

![](_page_206_Picture_2.jpeg)

Lab Building, Portland Cement Association, Skokie, Illinois.

In this section, the theoretical points of cutoff have been discussed. As will be seen in subsequent sections of this chapter, the bars will have to be run additional distances because of variations of moment diagrams, anchorage requirements of the bars, and so on.

### **7.2 Bond Stresses**

A basic assumption made for reinforced concrete design is that there must be absolutely no slippage of the bars in relation to the surrounding concrete. In other words, the steel and the concrete should stick together, or *bond*, so that they will act as a unit. If there is no bonding between the two materials and if the bars are not anchored at their ends, they will pull loose from the concrete. As a result, the concrete beam will act as an unreinforced member and will be subject to sudden collapse as soon as the concrete cracks.

It is obvious that the magnitude of bond stresses will change in a reinforced concrete beam as the bending moments in the beam change. The greater the rate of bending moment change (occurring at locations of high shear), the greater will be the rate of change of bar tensions and, thus, bond stresses.

What may not be so obvious is the fact that bond stresses are also drastically affected by the development of tension cracks in the concrete. At a point where a crack occurs, all of the longitudinal tension will be resisted by the reinforcing bar. At a small distance along the bar at a point away from the crack, the longitudinal tension will be resisted by both the bar and the uncracked concrete. In this small distance, there can be a large change in bar tension due to the fact that the uncracked concrete is now resisting tension. Thus the bond stress in the surrounding concrete, which was zero at the crack, will drastically change within this small distance as the tension in the bar changes.

In the past, it was common to compute the maximum theoretical bond stresses at points in the members and to compare them with certain allowable values obtained by tests. It is

![](_page_207_Picture_2.jpeg)

**FI GU RE 7.5** Bearing forces on bar and bearing of bar ribs on concrete.

the practice today, however, to look at the problem from an ultimate standpoint, where the situation is a little different. Even if the bars are completely separated from the concrete over considerable parts of their length, the ultimate strength of the beam will not be affected if the bars are so anchored at their ends that they cannot pull loose.

The bonding of the reinforcing bars to the concrete is due to several factors, including the chemical adhesion between the two materials, the friction due to the natural roughness of the bars, and the bearing of the closely spaced rib-shaped deformations on the bar surfaces against the concrete. The application of the force *P* to the bar shown in Figure 7.5 is considered in the discussion that follows.

When the force is first applied to the bar, the resistance to slipping is provided by the adhesion between the bar and the concrete. If plain bars were used, it would not take much tension in the bars to break this adhesion, particularly adjacent to a crack in the concrete. If this were to happen for a smooth surface bar, only friction would remain to keep the bar from slipping. There is also some Poisson's effect due to the tension in the bars. As they are tensioned, they become a little smaller, enabling them to slip more easily. If we were to use straight, plain, or smooth reinforcing bars in beams, there would be very little bond strength, and the beams would be only a little stronger than if there were no bars. Deformed bars were introduced so that in addition to the adhesion and friction, there would also be a resistance due to the bearing of the concrete on the lugs or ribs (or deformations) of the bars as well as the so-called shear-friction strength of the concrete between the lugs.

Deformed bars are used in almost all work. However, plain bars or plain wire fabrics are sometimes used for transverse reinforcement in compression members (as ties or spirals, as described in Chapter 9), for members subject to torsion, and for confining reinforcing in splices (ACI R3.5.4).

As a result of these facts, reinforcing bars are made with rib-type deformations. The chemical adhesion and friction between the ribs are negligible, and thus bond is primarily supplied by bearing on the ribs. Based on testing, the crack patterns in the concrete show that the bearing stresses are inclined to the axis of the bars from about 45◦ to 80◦ (the angle being appreciably affected by the shape of the ribs).1

![](_page_207_Picture_9.jpeg)

Courtesy of Clemson University Communications Center.

Twisted square bar, formerly used to increase bond between concrete and steel.

<sup>1</sup> Goto, Y., 1971, "Cracks Formed on Concrete Around Deformed Tensioned Bar," *ACI Journal*, *Proceedings 68*, p. 244.

![](_page_208_Picture_2.jpeg)

![](_page_208_Picture_4.jpeg)

![](_page_208_Picture_6.jpeg)

**FI GU RE 7.6** Types of bond failures.

Equal and opposite forces develop between the reinforcing bars and the concrete, as shown in Figure 7.5. These internal forces are caused by the wedging action of the ribs bearing against the concrete. They will cause tensile stresses in a cylindrical piece of concrete around each bar. It's rather like a concrete pipe filled with water that is pressing out against the pipe wall, causing it to be placed in tension. If the tension becomes too high, the pipe will split.

In a similar manner, if the bond stresses in a beam become too high, the concrete will split around the bars, and eventually the splits will extend to the side and/or bottom of the beam. If either of these types of splits runs all the way to the end of the bar, the bar will slip and the beam will fail. The closer the bars are spaced together and the smaller the cover, the thinner will be the concrete cylinder around each bar and the more likely that a bond-splitting failure will occur.

Figure 7.6 shows examples of bond failures that may occur for different values of concrete cover and bar spacing. These are as shown by MacGregor.2

Splitting resistance along bars depends on quite a few factors, such as the thickness of the concrete cover, the spacing of the bars, the presence of coatings on the bars, the types of aggregates used, the transverse confining effect of stirrups, and so on. Because there are so many variables, it is impossible to make comprehensive bond tests that are good for a wide range of structures. Nevertheless, the ACI has attempted to do just this with its equations, as will be described in the sections to follow.

### **7.3 Development Lengths for Tension Reinforcing**

For this discussion, reference is made to the cantilever beam of Figure 7.7. It can be seen that both the maximum moment in the beam and the maximum stresses in the tensile bars occur at the face of the support. Theoretically, a small distance back into the support the moment is zero, and thus it would seem that reinforcing bars would no longer be required. This is the situation pictured in Figure 7.7(a). Obviously, if the bars were stopped at the face of the support, the beam would fail.

The bar stresses must be transferred to the concrete by bond between the steel and the concrete before the bars can be cut off. In this case the bars must be extended some distance back into the support and out into the beam to anchor them or develop their strength. This distance, called the *development length* (l*<sup>d</sup>* ), is shown in Figure 7.7(b). It can be defined as

<sup>2</sup> MacGregor, J. G., 2005, *Reinforced Concrete Mechanics and Design*, 4th ed. (Upper Saddle River, NJ: Prentice-Hall), p. 334.

![](_page_209_Figure_2.jpeg)

**FIGURE 7.7** Development length in a cantilever support.

the minimum length of embedment of bars that is necessary to permit them to be stressed to their yield point plus some extra distance to ensure member toughness. A similar case can be made for bars in other situations and in other types of beams.

As previously mentioned, the ACI for many years required designers to calculate bond stresses with a formula that was based on the change of moment in a beam. Then the computed values were compared to allowable bond stresses in the code. Originally, bond strength was measured by means of pullout tests. A bar would be cast in a concrete cylinder and a jack would be used to see how much force was required to pull it out. The problem with such a test is that the concrete is placed in compression, preventing the occurrence of cracks. In a flexural member, however, we have an entirely different situation due to the off-again/on-again nature of the bond stresses caused by the tension cracks in the concrete. In recent years, more realistic tests have been made with beams; the ACI Code development length expressions to be presented in this chapter are based primarily on such tests at the National Institute of Standards and Technology and the University of Texas.

The development lengths used for deformed bars or wires in tension may not be less than the values computed with ACI Equation 12-1 or 12 in. If the equation is written as  $(\ell_d/d_b)$ , the results obtained will be in terms of bar diameters. This form of answer is very convenient to use as, say, 30 bar diameters, 40 bar diameters, and so on.

$$\ell_d = \frac{3}{40} \frac{f_y}{\lambda \sqrt{f_c'}} \frac{\psi_t \psi_e \psi_s}{\left(\frac{c_b + K_{tr}}{d_b}\right)} d_b$$
(ACI Equation 12-1)
$$\frac{\ell_d}{d_b} = \frac{3}{40} \frac{f_y}{\lambda \sqrt{f_c'}} \frac{\psi_t \psi_e \psi_s}{\left(\frac{c_b + K_{tr}}{d_t}\right)}$$

or

$$\ell_d = \frac{9}{10} \frac{f_y}{\lambda \sqrt{f_c'}} \frac{\psi_t \psi_e \psi_s}{\left(\frac{c_b + K_{tr}}{d_b}\right)} d_b$$

This expression, which seems to include so many terms, is much easier to use than it might at first appear because several of the terms are usually equal to 1.0. Even if not equal to 1.0, the factors can be quickly obtained.

**TABLE 7.1** Factors for Use in the Expressions for Determining Required Development Lengths for Deformed Bars and Deformed Wires in Tension (ACI 12.2.4)

| (1) | $\begin{array}{l} \psi_t = \textit{reinforcement location factor} \\ Horizontal reinforcement so placed that more than 12 in. of fresh concrete is cast in the member below the development length or splice $                                                                                                                                                                                |
|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| (2) | $\begin{array}{ll} \psi_{\rm e} = {\it coating factor} \\ {\it Epoxy-coated bars or wires with cover less than } 3d_b, {\it or clear spacing less than } 6d_b & 1.5 \\ {\it All other epoxy-coated bars or wires} & 1.2 \\ {\it Uncoated and zinc-coated reinforcement} & 1.0 \\ {\it However, the product of } \psi_t \psi_{\rm e} {\it need not be taken as greater than 1.7.} \end{array}$ |
| (3) | $\begin{array}{ll} \psi_{\scriptscriptstyle S} = \textit{reinforcement size factor} \\ \text{No. 6 and smaller bars and deformed wires} & 0.8 \\ \text{No. 7 and larger bars} & 1.0 \\ \end{array}$                                                                                                                                                                                           |
|     | In SI units  No. 19 and smaller bars and deformed wires                                                                                                                                                                                                                                                                                                                                       |
| (4) | $\lambda$ (lambda) = lightweight aggregate concrete factor When lightweight aggregate concrete is used, $\lambda$ shall not exceed                                                                                                                                                                                                                                                            |
|     | It's $\sqrt{f_c'}/1.8f_{ct}$ in SI.                                                                                                                                                                                                                                                                                                                                                           |
|     | but not greater than                                                                                                                                                                                                                                                                                                                                                                          |
| (5) | $c_b = spacing \ or \ cover \ dimension, \ in.$ Use the smaller of either the distance from the center of the bar or wire to the nearest concrete surface, or one-half the center-to-center spacing of the bars or wires being developed.                                                                                                                                                     |

In the following paragraphs, all of the terms in ACI Equation 12-1 that have not previously been introduced are described. Then their values for different situations are given in Table 7.1.

- 1. Location of reinforcement—Horizontal bars that have a least 12 in. [3] of fresh concrete placed beneath them do not bond as well to concrete as do bars placed nearer the bottom of the concrete. These bars are referred to as top bars. During the placing and vibration of the concrete, some air and excess water tend to rise toward the top of the concrete, and some portion may be caught under the higher bars. In addition, there may be some settlement of the concrete below. As a result, the reinforcement does not bond as well to the concrete underneath, and increased development lengths will be needed. To account for this effect, the reinforcement location factor,  $\psi_t$ , is used.
- 2. Coating of bars—Epoxy-coated reinforcing bars are frequently used today to protect the steel from severe corrosive situations, such as where deicing chemicals are used. Bridge decks and parking garage slabs in the colder states fit into this class. When bar coatings are used, bonding is reduced and development lengths must be increased. To account for this fact, the term  $\psi_e$ —the coating factor—is used in the equation.
- **3.** Sizes of reinforcing—If small bars are used in a member to obtain a certain total cross-sectional area, the total surface area of the bars will be appreciably larger than if fewer but larger bars are used to obtain the same total bar area. As a result, the required

<sup>&</sup>lt;sup>3</sup> 300 mm in SL

development lengths for smaller bars with their larger surface bonding areas (in proportion to their cross-sectional areas) are less than those required for larger-diameter bars. This factor is accounted for with the reinforcement size factor,  $\psi_s$ .

- **4.** Lightweight aggregates—The dead weight of concrete can be substantially reduced by substituting lightweight aggregate for the regular stone aggregate. The use of such aggregates (expanded clay or shale, slag, etc.) generally results in lower-strength concretes. Such concretes have lower splitting strengths, and so development lengths will have to be larger. In the equation,  $\lambda$  is the *lightweight concrete modification factor* discussed in Section 1.12.
- 5. Spacing of bars or cover dimensions—Should the concrete cover or the clear spacing between the bars be too small, the concrete may very well split, as was previously shown in Figure 7.6. This situation is accounted for with the  $(c_b + K_{tr})/d_b$  term in the development length expression. It is called the *confinement term*. In the equation,  $c_h$ represents the smaller of the distance from the center of the tension bar or wire to the nearest concrete surface, or one-half the center-to-center spacing of the reinforcement.

In this expression,  $K_{tr}$  is a factor called the transverse reinforcement index. It is used to account for the contribution of confining reinforcing (stirrups or ties) across possible splitting planes.

$$K_{tr} = \frac{40A_{tr}}{sn}$$

where

 $A_{tr}$  = the total cross-sectional area of all transverse reinforcement having the center-to-center spacing s and a yield strength  $f_{vt}$ 

n = the number of bars or wires being developed along the plane of splitting. If steel is in two layers, n is the largest number of bars in a single layer.

s = center-to-center spacing of transverse reinforcing

The code in Section 12.2.3 conservatively permits the use of  $K_{tr} = 0$  to simplify the calculations, even if transverse reinforcing is present. ACI 12.2.3 limits the value of  $(c_h + K_{rr})/d_h$ used in the equation to a maximum value of 2.5. (It has been found that if values larger than 2.5 are used, the shorter development lengths resulting will increase the danger of pullout-type failures.)

The calculations involved in applying ACI Equation 12-1 are quite simple, as is illustrated in Example 7.2.

In SI units, 
$$K_{tr} = \frac{A_{tr}f_{yt}}{10sn}$$

#### Example 7.2

Determine the development length required for the #8 uncoated bottom bars shown in Figure 7.8,

- (a) assume  $K_{tr} = 0$  and
- **(b)** use the computed value of  $K_{tr}$ .

#### SOLUTION

From Table 7.1

 $\psi_t = 1.0$  for bottom bars

 $\psi_{\rm e}\,=\,1.0$  for uncoated bars

![](_page_212_Figure_2.jpeg)

**FIGURE 7.8** Beam cross section for Example 7.2.

 $\psi_s = 1.0$  for #8 bars

 $\lambda = 1.0$  for normal-weight concrete

 $c_b = \text{side cover of bars measured from center of bars} = 2\frac{1}{2} \text{ in.}$ 

or

 $c_b$  = one-half of c. to c. spacing of bars =  $1\frac{1}{2}$  in.  $\leftarrow$ 

(a) Using ACI Equation 12-1 with  $K_{tr} = 0$ 

$$\begin{split} \frac{c_b + K_{tr}}{d_b} &= \frac{1.50 \text{ in.} + 0 \text{ in.}}{1.00 \text{ in.}} = 1.50 < 2.50 \quad \underline{OK} \\ \frac{\ell_d}{d_b} &= \frac{3}{40} \frac{f_y}{\lambda \sqrt{f_c'}} \frac{\psi_t \psi_e \psi_s}{\left(\frac{c_b + K_{tr}}{d_b}\right)} \\ &= \left(\frac{3}{40}\right) \left[\frac{60,000 \text{ psi}}{(1.0)\sqrt{3000} \text{ psi}}\right] \frac{(1.0)(1.0)(1.0)}{1.50} = \underline{55 \text{ diameters}} \end{split}$$

(b) Using Computed Value of  $K_{tr}$  and ACI Equation 12-1

$$K_{tr} = \frac{40A_{tr}}{sn} = \frac{(40)(2)(0.11 \text{ in.}^2)}{(8 \text{ in.})(3)} = 0.367 \text{ in.}$$

$$\frac{c_b + K_{tr}}{d_b} = \frac{1.50 \text{ in.} + 0.367 \text{ in.}}{1.0 \text{ in.}} = 1.867 < 2.5 \quad \underline{OK}$$

$$\frac{\ell_d}{d_b} = \left(\frac{3}{40}\right) \left(\frac{60,000 \text{ psi}}{\sqrt{3000} \text{ psi}}\right) \frac{(1.0)(1.0)(1.0)(1.0)}{1.867} = \underline{44 \text{ diameters}}$$

In determining required development lengths, there are two more ACI specifications to keep in mind:

- 1. Section 12.1.2 states that values of  $\sqrt{f_c'}$  used in the equations cannot be greater than 100 psi or  $\frac{25}{3}$  MPa in SI. (This limit is imposed because there has not been a sufficient amount of research on the development of bars in higher-strength concretes to justify higher  $\sqrt{f_c'}$  values, which would result in smaller  $\ell_d/d_b$  values.)
- **2.** When the amount of flexural reinforcing provided exceeds the theoretical amount required, and where the specifications being used do not specifically require that the development lengths be based on  $f_v$ , the value of  $\ell_d/d_b$  may be multiplied by

 $(A_{s \text{ required}}/A_{s \text{ provided}})$ , according to ACI 12.2.5. This reduction factor may not be used for the development of reinforcement at supports for positive reinforcement, for the development of shrinkage and temperature reinforcement, or for a few other situations referenced in R12.2.5. This reduction also is not permitted in regions of high seismic risk, as described in ACI 318-11, Chapter 21.

Instead of using ACI Equation 12-1 for computing development lengths, the ACI in its Section 12.2 permits the use of a somewhat simpler and more conservative approach (as shown in Table 7.2 herein) for certain conditions. With this approach, the ACI recognizes that in a very large percentage of cases, designers use spacing and cover values and confining reinforcing that result in a value of  $(c_b + K_{tr})/d_b$  equal to at least 1.5. Based on this value and the appropriate values of  $\psi_s$ , the expressions in Table 7.2 were determined.

For SI values, see Section 12.2.2 of the 318M-11 Code.

If a minimum cover equal to  $d_b$  and a minimum clear spacing between bars of  $2d_b$  (or a minimum clear spacing of bars equal to  $d_b$ , along with a minimum of ties or stirrups) are used, the expressions in Table 7.2 can be used. Otherwise, it is necessary to use the more rigorous ACI Equation 12-1.

The authors feel that the application of the so-called simplified equations requires almost as much effort as is needed to use the longer equation. Furthermore, the development lengths computed with the "simpler" equations are often so much larger than the ones determined with the regular equation as to be uneconomical.

For these reasons the authors recommend the use of Equation 12-1 for computing development lengths. In using this long-form equation, however, you may very well like to assume that  $K_{tr} = 0$ , as the results obtained usually are only slightly more conservative than those obtained with the full equation. The authors use Equation 12-1 with  $K_{tr} = 0$  for all applications after this chapter.

Examples 7.3 and 7.4, which follow, present the determination of development lengths using each of the methods that have been described in this section.

|                                                                                                                                                                                  | #6 and Smaller Bars and<br>Deformed Wires                               | #7 and Larger Bars                                                      |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|
| Clear spacing of bars being developed or spliced not less than $d_b$ , clear cover not less than $d_b$ , and stirrups or ties throughout $\ell_d$ not less than the code minimum | $\frac{\ell_d}{d_b} = \frac{f_y \psi_t \psi_e}{25\lambda \sqrt{f_C'}}$  | $\frac{\ell_d}{d_b} = \frac{f_y \psi_t \psi_e}{20 \lambda \sqrt{f_C'}}$ |
| or                                                                                                                                                                               |                                                                         |                                                                         |
| Clear spacing of bars being developed or spliced not less than $2d_b$ and clear cover not less than $d_b$                                                                        |                                                                         |                                                                         |
| Other cases                                                                                                                                                                      | $\frac{\ell_d}{d_b} = \frac{3f_y \psi_t \psi_e}{50\lambda \sqrt{f_c'}}$ | $\frac{\ell_d}{d_b} = \frac{3f_y \psi_t \psi_e}{40\lambda \sqrt{f_c'}}$ |

**TABLE 7.2** Simplified Development Length Equations

#### Example 7.3

The #7 bottom bars shown in Figure 7.9 are epoxy coated. Assuming normal-weight concrete,  $f_v = 60,000$  psi, and  $f_c' = 3500$  psi, determine required development lengths

- (a) Using the simplified equations of Table 7.2.
- **(b)** Using the full ACI Equation 12-1 with the calculated value of  $K_{tr}$ .
- (c) Using ACI Equation 12-1 with  $K_{tr} = 0$ .

#### SOLUTION

With reference to Table 7.1

 $\psi_t = 1.0$  for bottom bars

 $\psi_{\rm e} = 1.5$  for epoxy-coated bars with clear spacing  $< 6d_b$ 

$$\psi_t \psi_e = (1.0)(1.5) = 1.5 < 1.7$$
 OK

 $\psi_s = 1.0$  for #7 and larger bars

 $\lambda = 1.0$  for normal-weight concrete

 $c_b = \text{cover} = 3 \text{ in.}$ 

or

 $c_b$  = one-half of c. to c. spacing of bars =  $1\frac{1}{2}$  in.  $\leftarrow$  controls

(a) Using Simplified Equation

$$\frac{\ell_d}{d_b} = \frac{f_y \psi_t \psi_e}{20 \lambda_v f_c'} = \frac{(60,000 \text{ psi}) (1.0) (1.5)}{20 (1.0) \sqrt{3500} \text{ psi}} = 76 \text{ diameters}$$

(b) Using ACI Equation 12-1 with Computed Value of  $K_{tr}$ 

$$\begin{split} K_{tr} &= \frac{40A_{tr}}{sn} = \frac{(40)(2)(0.11 \text{ in.}^2)}{(6 \text{ in.})(4)} = 0.367 \text{ in.} \\ \frac{c_b + K_{tr}}{d_b} &= \frac{1.5 \text{ in.} + 0.367 \text{ in.}}{0.875 \text{ in.}} = 2.13 < 2.50 \quad \underline{OK} \\ \frac{\ell_d}{d_b} &= \frac{3}{40} \frac{f_y}{\lambda \sqrt{f_c'}} \frac{\psi_t \psi_e \psi_s}{c_b + K_{tr}} \\ &= \left(\frac{3}{40}\right) \left(\frac{60,000 \text{ psi}}{(1.0)\sqrt{3500} \text{ psi}}\right) \frac{(1.0)(1.5)(1.0)}{2.13} \\ &= \underline{54 \text{ diameters}} \end{split}$$

(c) Using ACI Equation 12-1 with  $K_{tr} = 0$ 

$$\begin{split} \frac{c_b + K_{tr}}{d_b} &= \frac{1.5 \text{ in.} + 0 \text{ in.}}{0.875 \text{ in.}} = 1.71 < 2.50 \quad \underline{OK} \\ \frac{\ell_d}{d_b} &= \left(\frac{3}{40}\right) \left(\frac{60,000 \text{ psi}}{(1.0)\sqrt{3500} \text{ psi}}\right) \frac{(1.0)(1.5)(1.0)}{1.71} \\ &= \underline{67 \text{ diameters}} \end{split}$$

![](_page_215_Figure_2.jpeg)

**FIGURE 7.9** Beam cross section for Example 7.3.

### Example 7.4

The required reinforcing steel area for the lightweight concrete beam of Figure 7.10 is 2.88 in.<sup>2</sup> The #8 top bars shown are uncoated. Compute development lengths if  $f_v = 60,000$  psi and  $f_{\rm c}' = 3500 \, {\rm psi}.$ 

- (a) Using simplified equations.
- (b) Using the full ACI Equation 12-1.
- (c) Using Equation 12-1 with  $K_{tr} = 0$ .

#### SOLUTION

With reference to Table 7.1

 $\psi_t = 1.3$  for top bars

 $\psi_e = 1.0$  for uncoated bars

 $\psi_t \psi_e = (1.3)(1.0) < 1.7$  <u>OK</u>

 $\psi_{s} = 1.0$  for #7 and larger bars

 $\lambda = 0.75$  for lightweight concrete

 $c_b = \text{cover} = 3 \text{ in.}$ 

or

 $c_b$  = one-half of c. to c. spacing of bars = 2 in.  $\leftarrow$  controls

![](_page_215_Figure_19.jpeg)

FIGURE 7.10 Cross section of cantilever beam for Example 7.4.

#### (a) Using Simplified Equations

$$\frac{\ell_d}{d_b} = \frac{f_y \psi_t \psi_e}{20\lambda \sqrt{f_c'}} = \frac{(60,000 \text{ psi})(1.3)(1.0)}{20(0.75)\sqrt{3500} \text{ psi}} = 88 \text{ diameters}$$

$$\frac{\ell_d}{d_b}$$
 reduced for excess reinforcement to  $\left(\frac{2.88 \text{ in.}^2}{3.14 \text{ in.}^2}\right)$  (88) =  $\frac{81 \text{ diameters}}{12.14 \text{ in.}^2}$ 

(b) Using ACI Equation 12-1 with Computed Value of  $K_{t}$ ,

$$K_{tr} = \frac{40A_{tr}}{sn} = \frac{(40)(2)(0.11 \text{ in.}^2)}{(8 \text{ in.})(4)} = 0.275$$

$$\frac{c_b + K_{tr}}{d_b} = \frac{2.0 \text{ in.} + 0.275 \text{ in.}}{1.0 \text{ in.}} = 2.275 < 2.5 \quad \underline{OK}$$

$$\frac{\ell_d}{d_b} = \frac{3}{40} \frac{f_y}{\lambda \sqrt{f_c'}} \frac{\psi_t \psi_e \psi_s}{c_b + K_{tr}}$$

$$= \left(\frac{3}{40}\right) \left[\frac{60,000 \text{ psi}}{(0.75)\sqrt{3500} \text{ psi}}\right] \frac{(1.3)(1.0)(1.0)}{2.275}$$

$$= 58 \text{ diameters}$$

$$\frac{\ell_d}{d_b}$$
 reduced for excess reinforcement to  $\left(\frac{2.88 \text{ in.}^2}{3.14 \text{ in.}^2}\right)$  (58) =  $\frac{53 \text{ diameters}}{12.14 \text{ in.}^2}$ 

(c) Using ACI Equation 12-1 with  $K_{tr} = 0$ 

$$\frac{c_b + K_{tr}}{d_b} = \frac{2.0 \text{ in.} + 0 \text{ in.}}{1.0 \text{ in.}} = 2.0 < 2.5$$

$$\frac{\ell_d}{d_b} = \left(\frac{3}{40}\right) \left[\frac{60,000 \text{ psi}}{(0.75)\sqrt{3500} \text{ psi}}\right] \frac{(1.3)(1.0)(1.0)}{2.0}$$
= 66 diameters

$$\frac{\ell_d}{d_b}$$
 reduced for excess reinforcement to  $\left(\frac{2.88 \text{ in.}^2}{3.14 \text{ in.}^2}\right)$  (66) =  $\frac{61 \text{ diameters}}{12.14 \text{ in.}^2}$ 

### 7.4 Development Lengths for Bundled Bars

When bundled bars are used, greater development lengths are needed because there is not a "core" of concrete between the bars to provide resistance to slipping. The code, Section 12.4.1, states that splice and development lengths for bundled bars are to be determined by first computing the lengths needed for the individual bars and then by increasing those values by 20% for three-bar bundles and 33% for four-bar bundles.

When the factors relating to cover and clear spacing are being computed for a particular bundle, the bars are treated as though their area were furnished by a single bar. In other words, it is necessary to replace the bundle of bars with a fictitious single bar with a diameter such that its cross-sectional area equals that of the bundle of bars. This is conservative because the bond properties of the bundled bars are actually better than for the fictitious single bar. When determining  $c_b$ , the confinement term, and the  $\psi_e$  factor, the bundle is considered to have a centroid coinciding with that of the bar bundle. Example 7.5 presents the calculation of the development length needed for a three-bar bundle of #8 bars.

#### Example 7.5

Compute the development length required for the uncoated bundled bars shown in Figure 7.11, if  $f_{\rm y}=60{,}000$  psi and  $f_{\rm c}'=4000$  psi with normal-weight concrete. Use ACI Equation 12-1 and assume  $K_{tr} = 0$ .

#### SOLUTION

With reference to Table 7.1

$$\psi_t = \psi_e = \psi_s = \lambda = 1.0$$

 $\psi_t = \psi_{\rm e} = \psi_{\rm s} = \lambda = 1.0$  Area of 3 #8 bars = 2.35 in.<sup>2</sup>

Diameter  $d_{bf}$  of a single bar of area 2.35 in.<sup>2</sup>

$$\frac{\pi d_{bf}^2}{4} = 2.35$$

$$d_{hf} = 1.73 \text{ in.}$$

Find the lowest value for  $c_b$  [Figure 7.11(b)].

$$c_{b1} = \text{side cover of bars} = 2 \text{ in.} + \frac{3}{8} \text{ in.} + 1.00 \text{ in.} = 3.38 \text{ in.}$$

$$c_{b2} = {
m bottom\ cover\ of\ bars} = 2\ {
m in.} + {3\over 8}\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + {3\over 8}\ {
m in.} + 0.79 (1.00\ {
m in.}) = 3.16\ {
m in.} \leftarrow 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + {3\over 8}\ {
m in.} + 0.79 (1.00\ {
m in.}) = 3.16\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + {3\over 8}\ {
m in.} + 0.79 (1.00\ {
m in.}) = 3.16\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + {3\over 8}\ {
m in.} + 0.79 (1.00\ {
m in.}) = 3.16\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.} + 0.79 d_b^{\text{[4]}} = 2\ {
m in.}$$

where  $d_h$  is the actual (not the fictitious) bar diameter.

$$c_{b3} = \frac{1}{2}$$
 c. to c. spacing of bars  $= \frac{10 \text{ in.} - (2) \left(\frac{3}{8} \text{ in.}\right) - (2) (1.00 \text{ in.})}{2} = 3.62 \text{ in.}$ 

![](_page_217_Figure_16.jpeg)

**FIGURE 7.11** Beam cross section for Example 7.5.

<sup>&</sup>lt;sup>4</sup> See Figure 7.11(b) for this dimension.

Using ACI Equation 12-1 with  $K_{tr} = 0$ 

$$\begin{split} \frac{c_b + K_{tr}}{d_{bf}} &= \frac{3.16 \text{ in.} + 0 \text{ in.}}{1.73 \text{ in.}} = 1.83 < 2.5 \\ \frac{\ell_d}{d_b} &= \left(\frac{3}{40}\right) \left(\frac{60,000 \text{ psi}}{(1.0)\sqrt{4000} \text{ psi}}\right) \frac{(1.0)(1.0)(1.0)}{1.83} \\ &= 39 \text{ diameters} \end{split}$$

But should be increased 20% for a three-bar bundle according to ACI Section 12.4.1.

$$\frac{\ell_d}{d_b} = (1.20)(39) = 47 \text{ diameters}$$
 $\ell_d = (47)(1.0 \text{ in.}) = 47 \text{ in.}$ 

Note that the actual bar diameter is used in the last equation, not the fictitious bar.

#### 7.5 **Hooks**

When sufficient space is not available to anchor tension bars by running them straight for their required development lengths, as described in Section 7.3, hooks may be used. (Hooks are considered ineffective for compression bars for development length purposes.)

Figure 7.12 shows details of the standard 90° and 180° hooks specified in Sections 7.1 and 7.2 of the ACI Code. Either the  $90^{\circ}$  hook with an extension of 12 bar diameters  $(12d_b)$ at the free end or the  $180^{\circ}$  hook with an extension of 4 bar diameters  $(4d_h)$  but not less than  $2\frac{1}{2}$  in. may be used at the free end. The radii and diameters shown are measured on the inside of the bends.

![](_page_218_Figure_10.jpeg)

![](_page_218_Figure_11.jpeg)

FIGURE 7.12 Hook configurations.

The dimensions given for hooks were developed to protect members against splitting of the concrete or bar breakage, no matter what concrete strengths, bar sizes, or bar stresses are used. Actually, hooks do not provide an appreciable increase in anchorage strength because the concrete in the plane of the hook is somewhat vulnerable to splitting. This means that adding more length (i.e., more than the specified  $12d_b$  or  $4d_b$  values) onto bars beyond the hooks doesn't really increase their anchorage strengths.

The development length needed for a hook is directly proportional to the bar diameter. This is because the magnitude of compressive stresses in the concrete on the inside of the hook is governed by  $d_h$ . To determine the development lengths needed for standard hooks, the ACI (12.5.2) requires the calculation of

$$\ell_{dh} = \frac{0.02\psi_e f_y d_b}{\lambda \sqrt{f_c'}}$$

The value of  $\ell_{dh}$ , according to ACI Section 12.5.1, may not be less than 6 in. or  $8d_b$ . For deformed bars, the ACI, Section 12.5.2, states that  $\psi_e$  in this expression can be taken as equal to 1.2 for epoxy-coated reinforcing and the  $\lambda$  used as equal to 0.75 for lightweight aggregate concrete. For all other cases,  $\psi_e$  and  $\lambda$  are to be set equal to 1.0.

In SI units, 
$$\ell_{dh} = \frac{0.24 \psi_e f_y}{\lambda \sqrt{f_c'}} d_b$$

The development length,  $\ell_{dh}$ , is measured from the critical section of the bar to the outside end or edge of the hooks, as shown in Figure 7.13.

The modification factors that may have to be successively multiplied by  $\ell_{dh}$  are listed in Section 12.5.3 of the code and are summarized in subparagraphs (a) to (d). These values apply only for cases where standard hooks are used. The effect of hooks with larger radii is

![](_page_219_Figure_9.jpeg)

FIGURE 7.13 Hooked-bar details for development of standard hooks.

not covered by the code. For the design of hooks, no distinction is made between top bars and other bars. (It is difficult to distinguish top from bottom anyway when hooks are involved.)

- (a) Cover—When hooks are made with #11 or smaller bars and have side cover values normal to the plane of the hooks no less than  $2\frac{1}{2}$  in. and where the cover on the bar extensions beyond 90° hooks is not less than 2 in., multiply by 0.7.
- (b) Ties or stirrups—When hooks made of #11 or smaller bars are enclosed either vertically or horizontally within ties or stirrup ties along their full development length  $\ell_{dh}$ , and the stirrups or ties are spaced no farther apart than  $3d_b$  (where  $d_b$  is the diameter of the hooked bar), multiply by 0.8. This situation is shown in Figure 7.14. (Detailed dimensions are given for stirrup and tie hooks in Section 7.1.3 of the ACI Code.)
- (c) When 180° hooks consisting of #11 or smaller bars are used and are enclosed within ties or stirrups placed perpendicular to the bars being developed, and spaced no further than 3d apart along the development length  $\ell_{dh}$  of the hook, multiply by 0.8. If the 90° hook shown in Figure 7.14 is replaced with a 180° hook and ties or stirrups are perpendicular (not parallel) to the longitudinal bar being developed, Figure 7.14 applies to this case as well.
- (d) Should anchorage or development length not be specially required for  $f_{\nu}$  of the bars, it is permissible to multiply  $\ell_{dh}$  by  $A_{s \text{ required}}/A_{s \text{ provided}}$ .

The danger of a concrete splitting failure is quite high if both the side cover (perpendicular to the hook) and the top and bottom cover (in the plane of the hook) are small. The code (12.5.4), therefore, states that when standard hooks with less than  $2\frac{1}{2}$  in. side and top or bottom cover are used at discontinuous ends of members, the hooks shall be enclosed within ties or stirrups spaced no farther than  $3d_b$  for the full development length,  $\ell_{dh}$ . The first tie or stirrup must enclose the bent part of the hook within a distance of  $2d_{bh}$  of the outside of the bend. Furthermore, the modification factor of 0.8 of items (b) and (c) herein shall not be

![](_page_220_Figure_8.jpeg)

**FIGURE 7.14** Stirrup or tie detail for 90° hooks complying with the 0.8 multiplier. The stirrups or ties shown can be either vertical (as illustrated) or horizontal.

applicable. If the longitudinal bar being developed with the hook shown in Figure 7.14 were at a discontinuous end of a member, such as the free end of a cantilever beam, the ties or stirrups shown in that figure would be *required*, unless side and top cover both were at least  $2\frac{1}{2}$  in.

Example 7.6, which follows, illustrates the calculations necessary to determine the development lengths required at the support for the tensile bars of a cantilever beam. The lengths for straight or hooked bars are determined.

#### Example 7.6

Determine the development or embedment length required for the epoxy-coated bars of the beam shown in Figure 7.15

- (a) If the bars are straight, assuming  $K_{tr} = 0$ .
- (b) If a 180° hook is used.
- (c) If a  $90^{\circ}$  hook is used.

The six #9 bars shown are considered to be top bars.  $f'_c = 4000$  psi and  $f_v = 60,000$  psi.

#### SOLUTION

(a) Straight Bars

 $\psi_t = 1.3$  for top bars  $\psi_{\rm e} = 1.5$  for coated bars with cover  $< 3d_{\rm b}$  or clear spacing  $< 6d_{\rm b}$  $\psi_t \psi_e = (1.3)(1.5) = 1.95 > 1.7$  : Use 1.7  $\psi_s = 1.0$  for 9 bars  $\lambda = 1.0$  for normal-weight concrete

 $c_b = \text{side cover} = \text{top cover} = 2.5 \text{ in.}$  $c_b = \text{one-half of c. to c. spacing of bars} = 2.25 \text{ in.} \leftarrow \text{controls}$ 

$$\begin{split} \frac{c_b + K_{tr}}{d_b} &= \frac{2.25 \text{ in.} + 0 \text{ in.}}{1.128 \text{ in.}} = 1.99 < 2.5 \quad \underline{OK} \\ \frac{\ell_d}{d_b} &= \left(\frac{3}{40}\right) \left(\frac{60,000 \text{ psi}}{(1.0) \sqrt{4000} \text{ psi}}\right) \frac{(1.7)(1.0)}{1.99} = 61 \text{ diameters} \\ \ell_d &= (61)(1.128 \text{ in.}) = \underline{69 \text{ in.}} \end{split}$$

![](_page_221_Figure_15.jpeg)

**FIGURE 7.15** Given information for Example 7.6.

(b) Using 180° hooks (see Figure 7.16) note that  $\psi_e = 1.2$  as required in ACI Section 12.5.2 for epoxy-coated hooks

$$\begin{split} \ell_{dh} &= \frac{0.02 \psi_{\rm e} f_y d_b}{\lambda \sqrt{f_c'}} = \frac{(0.02)\,(1.2)\,(60,\!000~{\rm psi})\,(1.128~{\rm in.})}{(1.0)\sqrt{4000}~{\rm psi}} \\ &= 25.68~{\rm in.} \quad \underline{\rm Say~26~in.} \end{split}$$

Note: The dimensions shown in the beam cross section (Figure 7.15) indicate  $2\frac{1}{2}$  in. from the bar center to the top and side of the beam. The cover is 2.5 in.  $-d_b/2=1.936$  in. <2.5 in. If this hook were in the free end of a cantilever beam, ties or stirrups would be required, and the 0.8 reduction factor would not be applicable. In this example, the hook is in a column, so special ties are not required. If they were provided, a reduction of 0.8 would apply. In this example, they are not provided.

![](_page_222_Figure_5.jpeg)

**FIGURE 7.16** Details for 180° hook.

(c) Using 90° hooks (see Figure 7.17)

$$\ell_{dh} = 26 \text{ in.}$$

as the 0.8 reduction factor does not apply because ties or stirrups are not provided.

![](_page_222_Figure_10.jpeg)

**FIGURE 7.17** Details for  $90^{\circ}$  hook

### 7.6 Development Lengths for Welded Wire Fabric in Tension

Section 12.7 of the ACI Code provides minimum required development lengths for deformed welded wire fabric, whereas Section 12.8 provides minimum values for plain welded wire fabric.

The minimum required development length for deformed welded wire fabric in tension measured from the critical section equals the value determined for  $\ell_d$ , as per ACI Section 12.2.2 or 12.2.3, multiplied by a wire fabric factor,  $\psi_w$ , from ACI Section 12.7.2 or 12.7.3.

This factor, which follows, contains the term s, which is the spacing of the wire to be developed. The resulting development length may not be less than 8 in. except in the

computation of lap splices. You might note that epoxy coatings seem to have little effect on the lengths needed for welded wire fabric, and it is thus permissible to use  $\psi_e = 1.0$ .

The wire fabric factor,  $\psi_w$ , for welded wire fabric with at least one crosswire within the development length not less than 2 in. from the critical section is

$$\psi_w = \frac{f_y - 35,000}{f_y} \text{ not less than } \frac{5d_b}{s}$$

but need not be taken > 1.0.

In SI units for welded wire fabric with at least one crosswire within the development length and not less than 50 mm from the point of the critical section, the wire fabric factor,  $\psi_w$ is  $(f_v - 240)/f_v$ , not less than  $5d_b/s$  but need not be taken > 1.0.

The yield strength of welded plain wire fabric is considered to be adequately developed by two crosswires if the closer one is not less than 2 in. from the critical section. The code (Section 12.8), however, says that the development length,  $\ell_d$ , measured from the critical section to the outermost crosswire may not be less than the value computed from the following equation, in which  $A_w$  is the area of the individual wire to be developed.

$$\ell_d = 0.27 \frac{A_w}{s} \left( \frac{f_y}{\lambda \sqrt{f_c'}} \right)$$
 but not < 6 in.

Or in SI units

$$\ell_d = 3.3 \frac{A_w}{s} \left( \frac{f_y}{\lambda \sqrt{f_c'}} \right)$$
 but not < 150 mm

The development lengths obtained for either plain or deformed wire may be reduced, as were earlier development lengths, by multiplying them by  $(A_{s \text{ required}}/A_{s \text{ furnished}})$  (ACI 12.2.5), but the modified results may not be less than the minimum values given in this section.

### **Development Lengths for Compression Bars**

There is not a great deal of experimental information available about bond stresses and needed embedment lengths for compression steel. It is obvious, however, that embedment lengths will be smaller than those required for tension bars. For one reason, there are no tensile cracks present to encourage slipping. For another, there is some bearing of the ends of the bars on concrete, which also helps develop the load.

The code (12.3.2) states that the minimum basic development length provided for compression bars  $(\ell_{dc})$  may not be less than the value computed from the following expression.

$$\ell_{dc} = \frac{0.02 f_y d_b}{\lambda \sqrt{f_c'}} \ge 0.0003 \ f_y d_b$$
 but not less than 8 in.

Or in SI units

$$\ell_{dc} = \frac{0.02 f_y d_b}{\lambda \sqrt{f_c'}} \ge 0.0003 \ f_y d_b$$
 but not less than 200 mm

If more compression steel is used than is required by analysis,  $\ell_{dc}$  may be multiplied by  $(A_{s \text{ required}}/A_{s \text{ provided}})$  as per ACI Section 12.3.3. When bars are enclosed in spirals for any kind of concrete members, the members become decidedly stronger due to the confinement or lateral restraint of the concrete. The normal use of spirals is in spiral columns, which are discussed in Chapter 9. Should compression bars be enclosed by spirals of not less than  $\frac{1}{4}$  in. diameter and with a pitch not greater than 4 in., or within #4 ties spaced at not more than 4 in. on center, the value of  $\ell_{dc}$  may be multiplied by 0.75 (ACI 12.3.3). In no case can the development length be less than 8 in. Thus

$$\ell_d = \ell_{dc} \times \text{applicable modification factors} \geq 8.0 \text{ in.}$$

An introductory development length problem for compression bars is presented in Example 7.7. The forces in the bars at the bottom of the column of Figure 7.18 are to be transferred down into a reinforced concrete footing by means of dowels. Dowels such as these are usually bent at their bottoms (as shown in the figure) and set on the main footing reinforcing where they can be tied securely in place. The bent or hooked parts of the dowels, however, do not count as part of the required development lengths for compression bars (ACI 12.5.5), as they are ineffective.

In a similar fashion, the dowel forces must be developed up into the column. In Example 7.7, the required development lengths up into the column and down into the footing are different because the  $f_c'$  values for the footing and the column are different in this case. The topic of dowels and force transfer from walls and columns to footings is discussed in some detail in Chapter 12. (The development lengths determined in this example are for compression bars, as would normally be the case at the base of columns. If uplift is possible, however, it will be necessary to consider tension development lengths, which could very well control.)

#### Example 7.7

The forces in the column bars of Figure 7.18 are to be transferred into the footing with #9 dowels. Determine the development lengths needed for the dowels (a) down into the footing and (b) up into the column if  $f_y = 60,000$  psi. The concrete in both the column and the footing is normal weight.

![](_page_224_Figure_8.jpeg)

**FIGURE 7.18** Information for Example 7.7.

#### SOLUTION

(a) Down into the footing,

$$\ell_{dc} = \frac{0.02 d_b f_y}{\lambda \sqrt{f_c'}} = \frac{(0.02) (1.128 \text{ in.}) (60,000 \text{ psi})}{(1.0) \sqrt{3000} \text{ psi}} = 24.71 \text{ in.} \leftarrow$$

$$\ell_{dc} = (0.0003) (1.128 \text{ in.}) (60,000 \text{ psi}) = 20.30 \text{ in.}$$

Hence  $\ell_d = 24.71$  in., say 25 in., as there are no applicable modification factors. Under no circumstances may  $\ell_d$  be less than 8 in.

(b) Up into column,

$$\ell_{dc} = \frac{(0.02) (1.128 \text{ in.}) (60,000 \text{ psi})}{(1.0) \sqrt{5000} \text{ psi}} = 19.14 \text{ in.}$$

$$\ell_{dc} = (0.0003) (1.128 \text{ in.}) (60,000 \text{ psi}) = 20.30 \text{ in.} \leftarrow$$

Hence  $\ell_d=$  20.30 in., say 21 in. (can't be < 8 in.), as there are no applicable modification factors. (Answer: Extend the dowels 25 in. down into the footing and 21 in. up into the column.)

Note: The bar details shown in Figure 7.18 are unsatisfactory for seismic areas, as the bars should be bent inward and not outward. The reason for this requirement is that the code, Chapter 21, on seismic design, stipulates that hooks must be embedded in confined concrete.

### **Critical Sections for Development Length**

Before the development length expressions can be applied in detail, it is necessary to understand clearly the critical points for tensile and compressive stresses in the bars along the beam.

First, it is obvious that the bars will be stressed to their maximum values at those points where maximum moments occur. Thus, those points must be no closer in either direction to the bar ends than the  $\ell_d$  values computed.

There are, however, other critical points for development lengths. As an illustration, a critical situation occurs whenever there is a tension bar whose neighboring bars have just been cut off or bent over to the other face of the beam. Theoretically, if the moment is reduced by a third, one-third of the bars are cut off or bent, and the remaining bars would be stressed to their yield points. The full development lengths would be required for those bars.

This could bring up another matter in deciding the development length required for the remaining bars. The code (12.10.3) requires that bars that are cut off or bent be extended a distance beyond their theoretical flexure cutoff points by d or 12 bar diameters, whichever is greater. In addition, the point where the other bars are bent or cut off must also be at least a distance  $\ell_d$  from their points of maximum stress (ACI 12.10.4). Thus, these two items might very well cause the remaining bars to have a stress less than  $f_v$ , thus permitting their development lengths to be reduced somewhat. A conservative approach is normally used, however, in which the remaining bars are assumed to be stressed to  $f_v$ .

#### **Effect of Combined Shear and Moment** 7.9 on Development Lengths

The ACI Code does not specifically consider the fact that shear affects the flexural tensile stress in the reinforcing. The code (12.10.3) does require bars to be extended a distance beyond their theoretical cutoff points by a distance no less than the effective depth of the member d or 12 bar diameters, whichever is larger. The commentary (R12.10.3) states that this extension is required to account for the fact that the locations of maximum moments may shift due to changes in loading, support settlement, and other factors. It can be shown that a diagonal tension crack in a beam without stirrups can shift the location of the computed tensile stress a distance approximately equal to *d* toward the point of zero moment. When stirrups are present, the effect is still there but is somewhat less severe.

The combined effect of shear and bending acting simultaneously on a beam may produce premature failure due to overstress in the flexural reinforcing. Professor Charles Erdei5,6,7 has done a great deal of work on this topic. His work demonstrates that web reinforcing participates in resisting bending moment. He shows that the presence of inclined cracks increases the force in the tensile reinforcing at all points in the shear span except in the region of maximum moment. The result is just as though we have a shifted moment diagram, which leads us to the thought that we should be measuring l*<sup>d</sup>* from the shifted moment diagram rather than from the basic one. He clearly explains the moment shift and the relationship between development length and the shift in the moment diagram.

The late Professor P. M. Ferguson<sup>8</sup> stated that whether or not we decide to use the shifted moment concept, it is nevertheless desirable to stagger the cutoff points of bars (and it is better to bend them than to cut them).

### **7.10 Effect of Shape of Moment Diagram on Development Lengths**

A further consideration of development lengths will show the necessity of considering the shape of the moment diagram. To illustrate this point, the uniformly loaded beam of Figure 7.19 with its parabolic moment diagram is considered. *It is further assumed that the length of the*

![](_page_226_Figure_7.jpeg)

**FI GU RE 7.19** Effects of shape of moment diagram.

<sup>5</sup> Erdei, C. K., 1961, "Shearing Resistance of Beams by the Load-Factor Method," *Concrete and Constructional Engineering*, 56(9), pp. 318–319.

<sup>6</sup> Erdei, C. K., 1962, "Design of Reinforced Concrete for Combined Bending and Shear by Ultimate Lead Theory," *Journal of the Reinforced Concrete Association*, 1(1).

<sup>7</sup> Erdei, C. K., 1963, "Ultimate Resistance of Reinforced Concrete Beams Subjected to Shear and Bending," *European Concrete Committees Symposium on Shear*, Wiesbaden, West Germany, pp. 102–114.

<sup>8</sup> Ferguson, P. M., 1979, *Reinforced Concrete Fundamentals*, 4th ed. (New York: John Wiley & Sons), p. 187.

reinforcing bars on each side of the beam centerline equals the computed development length  $\ell_d$ . The discussion to follow will prove that this distance is not sufficient to properly develop the bars for this moment diagram.

At the centerline of the beam of Figure 7.19, the moment is assumed to equal  $M_{\nu}$ , and the bars are assumed to be stressed to  $f_v$ . Thus the development length of the bars on either side of the beam centerline must be no less than  $\ell_d$ . If one then moves along this parabolic moment diagram on either side to a point where the moment has fallen off to a value of  $M_u/2$ , it is correct to assume a required development length from this point equal to  $\ell_d/2$ .

The preceding discussion clearly shows that the bars will have to be extended farther out from the centerline than  $\ell_d$ . For the moment to fall off 50%, one must move more than halfway toward the end of the beam.

#### 7.11 **Cutting Off or Bending Bars (Continued)**

This section presents a few concluding remarks concerning the cutting off of bars, a topic that was introduced in Section 7.1. The last several sections have offered considerable information that affects the points where bars may be cut off. Here we give a summary of the previously mentioned requirements, together with some additional information. First, a few comments concerning shear are in order.

When some of the tensile bars are cut off at a point in a beam, a sudden increase in the tensile stress will occur in the remaining bars. For this increase to occur, there must be a rather large increase in strain in the beam. Such a strain increase quite possibly may cause large tensile cracks to develop in the concrete. If large cracks occur, there will be a reduced beam cross section left to provide shear resistance—and thus a greater possibility of shear failure.

To minimize the possibility of a shear failure, Section 12.10.5 of the ACI Code states that at least one of the following conditions must be met if bars are cut off in a tension zone:

- 1. The shear at the cutoff point must not exceed two-thirds of the design shear strength,  $\phi V_n$ , in the beam, including the strength of any shear reinforcing provided (ACI 12.10.5.1).
- 2. An area of shear reinforcing in excess of that required for shear and torsion must be provided for a distance equal to  $\frac{3}{4}d$  from the cutoff point. The minimum area of this reinforcing and its maximum spacing are provided in Section 12.10.5.2 of the code.
- 3. When #11 or smaller bars are used, the continuing bars should provide twice the area of steel required for flexure at the cutoff point, and the shear should not exceed three-fourths of the permissible shear (ACI 12.10.5.3).

The moment diagrams used in design are only approximate. Variations in loading, settlement of supports, the application of lateral loads, and other factors may cause changes in those diagrams. In Section 7.9 of this chapter, we saw that shear forces could appreciably offset the tensile stresses in the reinforcing bars, thus in effect changing the moment diagrams. As a result of these factors, the code (12.10.3) says that reinforcing bars should be continued for a distance of 12 bar diameters or the effective depth d of the member, whichever is greater (except at the supports of simple spans and the free ends of cantilevers), beyond their theoretical cutoff

Various other rules for development lengths apply specifically to positive-moment reinforcement, negative-moment reinforcement, and continuous beams. These are addressed in

<sup>&</sup>lt;sup>9</sup> Ibid., pp. 191-193.

![](_page_228_Picture_2.jpeg)

Los Angeles County water project.

Chapter 14 of this text. Another item presented in that chapter, which is usually of considerable interest to students, are the rules of thumb that are frequently used in practice to establish cutoff and bend points.

Another rather brief development length example is presented in Example 7.8. A rectangular section and satisfactory reinforcing have been selected for the given span and loading condition. It is desired to determine where two of the four bars may be cut off, considering both moment and development length.

#### Example 7.8

The rectangular beam with four #8 bars shown in Figure 7.20(b) has been selected for the span and loading shown in part (a) of the figure. Determine the cutoff point for two of the bars, considering both the actual moment diagram and the required development length.

![](_page_229_Figure_2.jpeg)

**FI GU RE 7.20** Given information for Example 7.8.

The design moment capacity (φ*Mn*) of this beam has been computed to equal 359.7 ft-k when it has four bars and 185.3 ft-k when it has two bars. (Notice that ρ with two bars = 1.57 in.2/(18 in.) (27 in.) <sup>=</sup> 0.00323 < ρmin <sup>=</sup> <sup>200</sup>/60,000 psi <sup>=</sup> 0.00333, but is considered to be close enough.) In addition, l*<sup>d</sup>* for the bars has been determined to equal 41 in., using ACI Equation 12-1 with λ = 0.75 and *Ktr* = 0.275 in. based on #3 stirrups at *s* = 8 in. (similar to Example 7.4).

#### **SOLUTION**

The solution for this problem is shown in Figure 7.21. There are two bars beginning at the left end of the beam. As no development length is available, the design moment capacity of the member is zero. If we move a distance l*<sup>d</sup>* from point A at the left end of the beam to point B, the design moment capacity will increase in a straight line from 0 to 185.3 ft-k. From point B to point C, it will remain equal to 185.3 ft-k.

At point C, we reach the cutoff point of the bars, and from C to D (a distance equal to l*d*), the design moment capacity will increase from 185.3 ft-k to 359.7 ft-k. (In Figure 7.21(a) the bars seem to be shown in two layers. They are actually on one level, but the authors have shown them this way so that the reader can get a better picture of how many bars there are at any point along the beam.)

At no point along the span may the design strength of the beam be less than the actual bending moment caused by the loads. We can then see that point C is located where the actual bending moment equals 185.3 ft-k. The left reaction for this beam is 44.8 k, as shown in Figure 7.20(a). Using this value, an expression is written for the moment at point C (185.3 ft-k) at a distance *x* from the left support. The resulting expression can be solved for *x*.

$$44.8x - (2.8x)(\frac{x}{2}) = 185.3 \text{ ft-k}$$
  
 $x = 4.88 \text{ ft}$  Say, 4 ft 10 in.

By the time we reach point D (3 ft 5 in. to the right of C and 8 ft 3 in. from the left support), the required moment capacity is

$$M_u = (44.8 \text{ k}) (8.25 \text{ ft}) - (2.8 \text{ klf}) (8.25 \text{ ft}) \left(\frac{8.25 \text{ ft}}{2}\right) = 274.3 \text{ ft-k}$$

![](_page_230_Figure_2.jpeg)

FIGURE 7.21 Comparison of moment diagram to moment capacities.

Earlier in this section, reference was made to ACI Section 12.10.5, where shear at bar cutoff points was considered. It is assumed that this beam will be properly designed for shear as described in the next chapter and will meet the ACI shear requirements.

### 7.12 Bar Splices in Flexural Members

Field splices of reinforcing bars are often necessary because of the limited bar lengths available, requirements at construction joints, and changes from larger bars to smaller bars. Although steel fabricators normally stock reinforcing bars in 60-ft lengths, it is often convenient to work in the field with bars of shorter lengths, thus necessitating the use of rather frequent splices.

The reader should carefully note that the ACI Code, Sections 1.2.1(h) and 12.14.1, clearly state that the designer is responsible for specifying the types and locations for splices for reinforcement.

The most common method of splicing #11 or smaller bars is simply to lap the bars one over the other. Lapped bars may be either separated from each other or placed in contact, with the contact splices being much preferred since the bars can be wired together. Such bars also hold their positions better during the placing of the concrete. Although lapped splices are easy to make, the complicated nature of the resulting stress transfer and the local cracks that frequently occur in the vicinity of the bar ends are disadvantageous. Obviously, bond stresses play an important part in transferring the forces from one bar to another. Thus the required splice lengths are closely related to development lengths. It is necessary to understand that the minimum specified clear distances between bars also apply to the distances between contact lap splices and adjacent splices or bars (ACI Section 7.6.4).

Lap splices are not very satisfactory for several situations. They include: (1) where they would cause congestion; (2) where the laps would be very long, as they are for #9 to #11

Grade 60 bars; (3) where #14 or #18 bars are used because the code (12.14.2) does not permit them to be lap spliced except in a few special situations; and (4) where very long bar lengths would be left protruding from existing concrete structures for purposes of future expansion. For such situations, other types of splices, such as those made by welding or by mechanical devices, may be used. Welded splices, from the view of stress transfer, are the best splices, but they may be expensive and may cause metallurgical problems. The result may be particularly disastrous in high seismic zones. The ACI Code (12.14.3.4) states that welded splices must be accomplished by welding the bars together so that the connection will be able to develop at least 125% of the specified yield strength of the bars. It is considered desirable to butt the bars against each other, particularly for #7 and larger bars. Splices not meeting this strength requirement can be used at points where the bars are not stressed to their maximum tensile stresses. It should be realized that welded splices are usually the most expensive because of the high labor costs and the costs of proper inspection.

Mechanical connectors usually consist of some type of sleeve splice, which fits over the ends of the bars to be joined and into which a metallic grout filler is placed to interlock the grooves inside the sleeve with the bar deformations. From the standpoint of stress transfer, good mechanical connectors are next best to welded splices. They do have the disadvantage that some slippage may occur in the connections; as a result, there may be some concrete cracks in the area of the splices.

Before the specific provisions of the ACI Code are introduced, the background for these provisions should be explained briefly. The following remarks are taken from a paper by George F. Leyh of the CRSI.10

- **1.** Splicing of reinforcement can never reproduce exactly the same effect as continuous reinforcing.
- **2.** The goal of the splice provisions is to require a ductile situation where the reinforcing will yield before the splices fail. Splice failures occur suddenly without warning and with dangerous results.
- **3.** Lap splices fail by splitting of the concrete along the bars. If some type of closed reinforcing is wrapped around the main reinforcing (such as ties and spirals, described for columns in Chapter 9), the chances of splitting are reduced and smaller splice lengths are needed.
- **4.** When stresses in reinforcement are reduced at splice locations, the chances of splice failure are correspondingly reduced. For this reason, the code requirements are less restrictive where stresses are low.

Splices should be located away from points of maximum tensile stress. Furthermore, not all of the bars should be spliced at the same locations—that is, the splices should be staggered. Should two bars of different diameters be lap spliced, the lap length used shall be the splice length required for the smaller bar or the development length required for the larger bar, whichever is greater (ACI Code 12.15.3).

The length of lap splices for bundled bars must be equal to the required lap lengths for individual bars of the same size, but increased by 20% for three-bar bundles and 33% for four-bar bundles (ACI Code 12.4) because there is a smaller area of contact between the bars and the concrete, and thus less bond. Furthermore, individual splices within the bundles are not permitted to overlap each other.

<sup>10</sup> Portland Cement Association, 1972, *Proceedingsof the PCA-ACI Teleconference on ACI 318-71 Building Code Requirements* (Skokie, IL: Portland Cement Association), p. 14–1.

 $\frac{A_{s \text{ provided}}}{A_{s \text{ required}}} \qquad \qquad 50 \qquad \qquad 100$  Equal to or greater than 2

**TABLE 7.3** Tension Lap Splices

### 7.13 Tension Splices

The code (12.15) divides tension lap splices into two classes, A and B. The class of splice used is dependent on the level of stress in the reinforcing and on the percentage of steel that is spliced at a particular location.

Class A splices are those where the reinforcing is lapped for a minimum distance of  $1.0\ell_d$  (but not less than 12 in.) and where one-half or less of the reinforcing is spliced at any one location.

Class B splices are those where the reinforcing is lapped for a minimum distance of 1.3  $\ell_d$  (but not less than 12 in.) and where all the reinforcing is spliced at the same location.

The code (12.15.2) states that lap splices for deformed bars and deformed wire in tension must be Class B unless (1) the area of reinforcing provided is equal to two or more times the area required by analysis over the entire length of the splice and (2) one-half or less of the reinforcing is spliced within the required lap length. A summary of this information is given in Table 7.3, which is Table R12.15.2 in the ACI Commentary.

In calculating the value of  $\ell_d$  to be multiplied by 1.0 or 1.3, the reduction for excess reinforcing furnished,  $A_{s \text{ provided}}/A_{s \text{ required}}$ , should not be used because the class of splice (A or B) already reflects any excess reinforcing at the splice location (see ACI Commentary R12.15.1).

### 7.14 Compression Splices

Compression bars may be spliced by lapping, by end bearing, and by welding or mechanical devices. (Mechanical devices consist of bars or plates or other pieces welded or otherwise attached transversely to the flexural bars in locations where sufficient anchorage is not available.) The code (12.16.1) says that the minimum splice length of such bars should equal  $0.0005f_yd_b$  for bars with  $f_y$  of 60,000 psi or less,  $(0.0009f_y - 24)d_b$  for bars with higher  $f_y$  values, but not less than 12 in. Should the concrete strengths be less than 3000 psi, it is necessary to increase the computed laps by one-third. Reduced values are given in the code for cases where the bars are enclosed by ties or spirals (12.17.2.4 and 12.17.2.5).

The required length of lap splices for compression bars of different sizes is the larger of the computed compression lap splice length of the smaller bars or the compression development length,  $\ell_{dc}$  of the larger bars. It is permissible to lap splice #14 and #18 compression bars to #11 and smaller bars (12.16.2).

The transfer of forces between bars that are always in compression can be accomplished by end bearing, according to Section 12.16.4 of the code. For such transfer to be permitted, the bars must have their ends square cut (within  $1\frac{1}{2}^{\circ}$  of a right angle), must be fitted within 3° of full bearing after assembly, and must be suitably confined (by closed ties, closed stirrups, or spirals). Section 12.17.4 further states that when end-bearing splices are used in columns, in each face of the column more reinforcement has to be added that is capable of providing

![](_page_233_Picture_2.jpeg)

Picture of #7 GR75 Dywidag THREADBAR (R) reinforcing bar including a couple for transferring tension loads.

a tensile strength at least equal to 25% of the yield strength of the vertical reinforcement provided in that face.

The code (12.14.2.1), with one exception, prohibits the use of lap splices for #14 or #18 bars. When column bars of those sizes are in compression, it is permissible to connect them to footings by means of dowels of smaller sizes with lap splices, as described in Section 15.8.2.3 of the code.

### **7.15 Headed and Mechanically Anchored Bars**

Headed deformed bars (Figure 1.3 in Chapter 1) were added to the code in the 2008 edition. Such devices transfer force from the bar to the concrete through a combination of bearing force at the head and bond forces along the bar. There are several limitations to the use of headed bars, as follows:

- **(a)** bar *fy* shall not exceed 60,000 psi
- **(b)** bar size shall not exceed No. 11
- **(c)** concrete shall be normal weight
- **(d)** net bearing area of head *Abrg* shall not be less than four times the area of the bar *Ab*
- **(e)** clear cover for bar shall not be less than 2*db*
- **(f)** clear spacing between bars shall not be less than 4*db*

Clear cover and clear spacing requirements in (e) and (f) are measured to the bar, not to the head.

Headed bars are limited to those types that meet the requirements of HA heads in ASTM A970 because a number of methods are used to attach heads to bars, some involving significant obstructions or interruptions of the bar deformations. Headed bars with significant obstructions or interruptions of the bar deformations were not evaluated in the tests used to formulate the provisions in ACI Section 12.6.2.

The development length in tension for headed deformed bars that comply with the ASTM A970 and other special requirements pertaining to obstructions (ACI Section 3.5.9) is given by

$$\ell_{dt} = \frac{0.016\psi_e f_y}{\sqrt{f_c'}} d_b$$

In applying this equation,  $f_c'$  cannot be taken as greater than 6000 psi, and  $\psi_e$  is 1.2 for epoxy-coated bars and 1.0 otherwise. The calculated value of  $\ell_{dt}$  cannot be less than  $8d_b$  or 6 in., whichever is larger. The multiplier used earlier for deformed bars without heads,  $A_s$  required  $A_s$  provided, is not permitted. There are no  $\lambda$ ,  $\psi_t$  or  $\psi_s$  terms in this expression.

In SI units, 
$$\ell_{dt} = \frac{0.192 \psi_e f_y}{\sqrt{f_c'}} d_b$$

The code (ACI 12.6.4) also permits other mechanical devices shown by tests to be effective and approved by the building official.

#### Example 7.9

Repeat Example 7.6 using a headed bar, and compare with the results of Example 7.6.

$$\ell_{dt} = \frac{0.016 \psi_e f_y}{\sqrt{f_C'}} d_b = \frac{(0.016) (1.2) (60,000 \text{ psi})}{\sqrt{4000} \text{ psi}} (1.128 \text{ in.}) = 20.54 \text{ in.}$$
 Say 21 in.

This value compares with 69 in. for a straight bar and 26 in. for a 90° or 180° hooked bar.

### 7.16 SI Example

#### Example 7.10

Determine the development length required for the epoxy-coated bottom bars shown in Figure 7.22.

- (a) assuming  $K_{tr} = 0$  and
- **(b)** computing  $K_{tr}$  with the appropriate equation,  $f_v = 420$  MPa and  $f_c' = 21$  MPa.

#### SOLUTION

From Table 6.1 in Chapter 6

 $\psi_t = 1.0$  for bottom bars

 $\psi_e = 1.5$  for epoxy-coated bars with clear spacing  $< 6d_b$ 

$$\psi_t \psi_e = (1.0)(1.5) = 1.5 < 1.7$$
 Ok

$$\psi_{\rm s} = \lambda = 1.0$$

 $c_b = \text{side cover of bars} = 80 \text{ mm}$ 

 $c_b = \frac{1}{2}$  of c. to c. spacing of bars = 40 mm  $\leftarrow$  controls

![](_page_235_Figure_2.jpeg)

FIGURE 7.22 Beam cross section for Example 7.10.

(a) Using SI Equation 12-1 with  $K_{tr} = 0$ 

$$\begin{split} \frac{c_b + K_{tr}}{d_b} &= \frac{40 \text{ mm} + 0 \text{ mm}}{25.4 \text{ mm}} = 1.575 < 2.5 \quad \underline{OK} \\ \frac{\ell_d}{d_b} &= \frac{9}{10} \frac{f_y}{\lambda \sqrt{f_c'}} = \frac{\psi_t \psi_e \psi_s}{c_b + K_{tr}} \\ &= \left(\frac{9}{10}\right) \left(\frac{420 \text{ MPa}}{(1.0) \sqrt{21} \text{ MPa}}\right) \frac{(1.0)(1.5)(1.0)}{1.575} = \underline{78.6 \text{ diameters}} \end{split}$$

(b) Using Computed Value of  $K_{tr}$  and SI Equation 12-1

$$\begin{split} K_{tr} &= \frac{42A_{tr}}{sn} = \frac{(42)\,(2)\,(71~\text{mm}^2)}{(200~\text{mm})\,(4)} = 7.45~\text{mm} \\ \frac{c_b + K_{tr}}{d_b} &= \frac{40~\text{mm} + 7.45~\text{mm}}{25.4~\text{mm}} = 1.87 < 2.5 \qquad \underline{OK} \\ \frac{\ell_d}{d_b} &= \left(\frac{9}{10}\right) \left(\frac{420}{(1.0)\,\sqrt{21}}\right) \frac{(1.0)\,(1.5)\,(1.0)}{1.87} = \underline{66.2~\text{diameters}} \end{split}$$

#### **Computer Example** 7.17

#### Example 7.11

Using the worksheet entitled "devel length tens - calc As" in the spreadsheet for Chapter 7, determine the required tension development length  $\ell_d$  of the beam shown in Figure 7.20 if lightweight aggregate concrete and #3 stirrups at 8 in. centers are used.

Printout of Example 7.11 results.

#### SOLUTION

Input the values of the cells highlighted in yellow (only in the Excel spreadsheets, not the printed example). Some cells are optional (see note marked with \* in the printout for Example 7.11 shown above). Pass the cursor over cells for comments explaining what is to be input. Note that two answers are given, one with the  $A_{\rm s\ required}/A_{\rm s\ provided}$  reduction and one without. In this example, there is little difference because this ratio is nearly 1.0.

#### **PROBLEMS**

**Problem 7.1** Why is it difficult to calculate actual bond stresses?

**Problem 7.2** What are top bars? Why are the required development lengths greater than they would be if they were not top bars?

**Problem 7.3** Why do the cover of bars and the spacing of those bars affect required development lengths?

**Problem 7.4** Why isn't the anchorage capacity of a standard hook increased by extending the bar well beyond the end of the hook?

![](_page_237_Figure_2.jpeg)

For Problems 7.6 to 7.9, determine the development lengths required for the tension bar situations described using ACI Equation 12-1 and: (a) assuming  $K_{tr} = 0$ , and (b) the calculated value of  $K_{tr}$ .

**Problem 7.6** Uncoated bars in normal-weight concrete.  $A_{s \text{ required}} = 3.44 \text{ in.}^2$ .

![](_page_237_Figure_5.jpeg)

**Problem 7.7** Uncoated bars in normal-weight concrete.  $A_{s \text{ required}} = 4.25 \text{ in.}^2$ . (*Ans.* 43 in., 27 in.)

![](_page_237_Figure_7.jpeg)

**Problem 7.8** Epoxy-coated bars in lightweight concrete,  $A_{s \text{ required}} = 2.76 \text{ in.}^2$ .

![](_page_237_Figure_9.jpeg)

**Problem 7.9** Uncoated top bars in normal-weight concrete.  $A_{s \text{ required}} = 3.68 \text{ in.}^2$ . (*Ans.* 59 in., 50 in.)

![](_page_237_Figure_11.jpeg)

**Problem 7.10** Repeat Problem 7.6 if the bars are epoxy coated.

**Problem 7.11** Repeat Problem 7.7 if all-lightweight concrete with  $f'_c = 3000$  psi and epoxy-coated bars are used. (*Ans.* 98.8 in., 62.1 in.)

**Problem 7.12** Repeat Problem 7.8 if three uncoated #6 bars are used and  $A_{s \text{ required}} = 1.20 \text{ in.}^2$ .

**Problem 7.13** Repeat Problem 7.9 if the bars are four #8 and epoxy coated and all-lightweight concrete is used. (*Ans.* 81.6 in., 69.0 in.)

**Problem 7.14** The bundled #10 bars shown are uncoated and used in normal-weight concrete.  $A_{s \text{ required}} = 4.44 \text{ in.}^2$ .

![](_page_238_Figure_4.jpeg)

**Problem 7.15** Repeat Problem 7.14 if the bars are epoxy coated and used in sand-lightweight concrete with  $f'_c = 4000$  psi. (*Ans.* 78.3 in., 63.4 in., etc.)

**Problem 7.16** Set up a table for required development lengths for the beam shown, using  $f_y = 60,000$  psi and  $f_c'$  values of 3000 psi, 3500 psi, 4000 psi, 4500 psi, 5000 psi, 5500 psi, and 6000 psi. Assume the bars are uncoated and normal-weight concrete is used. Use ACI Equation 12-1 and assume  $K_{tr} = 0$ .

![](_page_238_Picture_7.jpeg)

**Problem 7.17** Repeat Problem 7.16 if #8 bars are used. (*Ans.* 41.1 in., 38.0 in., 35.6 in., 33.5 in., 31.8 in., etc.)

**Problem 7.18** Repeat Problem 7.16 if #7 bars are used.

**Problem 7.19** Repeat Problem 7.16 if #6 epoxy-coated bars are used in lightweight concrete. (*Ans.* 39.4 in., 36.5 in., 34.2 in., 32.2 in., 30.6 in., etc.)

#### Problem 7.20

- (a) Determine the tensile development length required for the uncoated #8 bars shown if normal-weight concrete is used and the bars are straight. Use ACI Equation 12-1 and compute the value of  $K_{tr}$ :  $f_c' = 4000$  psi and  $f_v = 60,000$  psi.
- **(b)** Repeat part (a) if 180° hooks are used.

Assume side, top, and bottom cover in all cases to be at least  $2\frac{1}{2}$  in.

![](_page_238_Picture_15.jpeg)

Problem 7.21 Are the uncoated #8 bars shown anchored sufficiently with their  $90^{\circ}$  hooks?  $f'_c = 3000$  psi and  $f_y = 60$  ksi. Side and top cover is  $2\frac{1}{2}$  in. on bar extensions. Normal-weight concrete is used.  $A_{s \text{ required}} = 2.20 \text{ in.}^2$ . (Ans.  $\ell_{dh} = 14.3$  in., sufficient)

![](_page_239_Picture_3.jpeg)

**Problem 7.22** Repeat Problem 7.21 if headed bars are used instead of 90° hooks and  $f_c' = 5000$  psi.

**Problem 7.23** Repeat Problem 7.7 if the bars are in compression. (Ans. 17.9 in.)

For Problems 7.24 to 7.29, use ACI Equation 12-1 and assume  $K_{tr} = 0$ .

Problem 7.24 The required bar area for the wall footing shown is 0.65 in.<sup>2</sup> per foot of width and #8 epoxy-coated bars 12 in. on center are used. Maximum moment is assumed to occur at the face of the wall. If  $f_v = 60,000$  psi and  $f_c' = 4000$  psi, do the bars have sufficient development lengths? Assume  $c_b = 3$  in.

![](_page_239_Figure_8.jpeg)

Problem 7.25 Repeat Problem 7.24 using #7 @ 9 in. and without epoxy coating. (Ans.  $\ell_d = 20.2$  in. < 27 in.  $\underline{OK}$ )

Problem 7.26 Problem 7.24 has insufficient embedment length. List four design modifications that would reduce the required development length.

**Problem 7.27** The beam shown is subjected to an  $M_u$  of 250 ft-k at the support. If  $c_b = 1.5$ ,  $K_{tr} = 0$ , the concrete is lightweight,  $f_v = 60,000$  psi, and  $f'_c = 4000$  psi, do the following: (a) select #9 bars to be placed in one row, (b) determine the development lengths required if straight bars are used in the beam, and (c) determine the development lengths needed if 180° hooks are used in the support. (Ans. 3 #9, 95.2 in., 26.0 in.)

![](_page_239_Picture_12.jpeg)

**Problem 7.28** In the column shown, the lower column bars are #8 and the upper ones are #7. The bars are enclosed by ties spaced 12 in. on center. If  $f_y = 60,000$  psi and  $f_c' = 4000$  psi, what is the minimum lap splice length needed? Normal-weight concrete is to be used for the 12-in.  $\times$  12-in. column.

![](_page_240_Picture_3.jpeg)

**Problem 7.29** Calculations show that 2.64 in.<sup>2</sup> of top or negative moment steel is required for the beam shown. Three #9 bars have been selected. Are the 4 ft. 6 in. embedment lengths shown satisfactory if  $f_c' = 4000$  psi and  $f_y = 60,000$  psi? Bars are spaced 3 in. o.c. with 3-in. side and top cover measured from c.g. of bars. Use  $K_{tr} = 0$ . (Ans. No;  $\ell_d = 69$  in. > 4 ft 6 in., not adequate)

![](_page_240_Picture_5.jpeg)

**Problem 7.31** If  $f_y = 75,000$  psi,  $f_c' = 4000$  psi,  $w_D = 1.5$  k/ft, and  $w_L = 5$  k/ft, are the development lengths of the straight bars satisfactory? Assume that the bars extend 6 in. beyond the centerline of the reactions and that  $K_{tr} = 0$ .  $A_{s \text{ required}} = 3.05$  in.<sup>2</sup>. The bars are uncoated and the concrete is normal weight. (Ans.  $\ell_d = 57.6$  in., embedment length is adequate)

![](_page_240_Figure_7.jpeg)

**Problem 7.30** Calculations show that 4.90 in.<sup>2</sup> of top or negative steel is required for the beam shown. If four uncoated #10 bars have been selected,  $f_c' = 4000$  psi, and  $f_y = 60,000$  psi, determine the minimum development length needed for the standard 90° hooks shown. Assume bars have 3-in. side and top cover measured from c.g. of bars and are used in normal-weight concrete. The bars are not enclosed by ties or stirrups spaced at  $3d_b$  or less.

![](_page_240_Picture_9.jpeg)

#### **Compression Splices**

**Problem 7.32** Determine the compression lap splices needed for a 14-in.  $\times$  14-in. reinforced concrete column with ties (whose effective area exceeds 0.0015 hs, as described in Section 12.17.2.4 of the code) for the cases to follow. There are eight #8 longitudinal bars equally spaced around the column.

- (a)  $f'_c = 4000 \text{ psi and } f_v = 60,000 \text{ psi}$
- **(b)**  $f'_c = 2000 \text{ psi and } f_v = 50,000 \text{ psi}$

#### **Problems in SI Units**

For Problems 7.33 to 7.36, determine the tensile development lengths required using: (a) ACI Metric Equation 12-1, assuming  $K_{tr} = 0$ , and (b) ACI Metric Equation 12-1 and the computed value of  $K_{tr}$ . Use  $f_v = 420$  MPa and  $f_c' = 28$  MPa.

**Problem 7.33** (*Ans.* 922 mm, 769 mm)

![](_page_241_Figure_8.jpeg)

#### Problem 7.34

![](_page_241_Figure_10.jpeg)

**Problem 7.35** Repeat Problem 7.33 if the longitudinal bars are #19. (*Ans.* 437 mm, 437 mm)

**Problem 7.36** Repeat Problem 7.34 if the bars are epoxy coated.

#### **Computer Problems**

For Problems 7.37 and 7.38, use the Chapter 7 spreadsheet.

**Problem 7.37** Repeat Problem 7.6. (Ans. 52.1 in., 44.0 in.)

**Problem 7.38** Repeat Problem 7.9.

**Problem 7.39** Repeat Problem 7.22. (*Ans.*  $\ell_{dt} = 13.6$  in. > 13 in. available  $\therefore$  no good)

