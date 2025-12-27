# **CHAPTER 4** Design of Rectangular Beams and One-Way Slabs

### **4.1 Load Factors**

Load factors are numbers, almost always larger than 1.0, that are used to increase the estimated loads applied to structures. They are used for loads applied to all types of members, not just beams and slabs. The loads are increased to attempt to account for the uncertainties involved in estimating their magnitudes. How close can you estimate the largest wind or seismic loads that will ever be applied to the building that you are now occupying? How much uncertainty is present in your answer?

You should note that the load factors for dead loads are much smaller than the ones used for live and environmental loads. Obviously, the reason is that we can estimate the magnitudes of dead loads much more accurately than we can the magnitudes of those other loads. In this regard, you will notice that the magnitudes of loads that remain in place for long periods of time are much less variable than are those loads applied for brief periods, such as wind and snow.

Section 9.2 of the code presents the load factors and combinations that are to be used for reinforced concrete design. The required strength, *U*, or the load-carrying ability of a particular reinforced concrete member, must at least equal the largest value obtained by substituting into ACI Equations 9-1 to 9-7. The following equations conform to the requirements of the International Building Code (IBC)<sup>1</sup> as well as to the values required by ASCE/SEI 7-10.2

| U<br>= 1.4D                                                            | (ACI Equation 9-1) |
|------------------------------------------------------------------------|--------------------|
| U<br>= 1.2D<br>+ 1.6L<br>+ 0.5(Lr<br>or<br>S<br>or<br>R)               | (ACI Equation 9-2) |
| U<br>= 1.2D<br>+ 1.6(Lr<br>or<br>S<br>or<br>R)<br>+ (L<br>or 0.5W<br>) | (ACI Equation 9-3) |
| U<br>= 1.2D<br>+ 1.0W<br>+ L<br>+ 0.5(Lr<br>or<br>S<br>or<br>R)        | (ACI Equation 9-4) |
| U<br>= 1.2D<br>+ 1.0E<br>+ L<br>+ 0.2S                                 | (ACI Equation 9-5) |
| U<br>= 0.9D<br>+ 1.0W                                                  | (ACI Equation 9-6) |
| U<br>= 0.9D<br>+ 1.0E                                                  | (ACI Equation 9-7) |
|                                                                        |                    |

In the preceding expressions, the following values are used:

*U* = the design or ultimate load the structure needs to be able to resist

*D* = dead load

*L* = live load

<sup>1</sup> International Code Council, 2012, *International Building Code*, Falls Church, Virginia 22041-3401.

<sup>2</sup> American Society of Civil Engineers, *Minimum Design Loads for Buildings and Other Structures*, ASCE 7-10 (Reston, VA: American Society of Civil Engineers), p. 7.

*Lr* = roof live load

*S* = snow load

*R* = rain load

*W* = wind load

*E* = seismic or earthquake load effects

*When impact effects need to be considered*, *they should be included with the live loads as per ACI Section 9.2.2.* Such situations occur when those loads are quickly applied, as they are for parking garages, elevators, loading docks, cranes, and others.

The load combinations presented in ACI Equations 9-6 and 9-7 contain a 0.9*D* value. This 0.9 factor accounts for cases where larger dead loads tend to reduce the effects of other loads. One obvious example of such a situation may occur in tall buildings that are subject to lateral wind and seismic forces where overturning may be a possibility. As a result, the dead loads are reduced by 10% to take into account situations where they may have been overestimated.

*The reader must realize that the sizes of the load factors do not vary in relation to the seriousness of failure. You may think that larger load factors should be used for hospitals or highrise buildings than for cattle barns, but such is not the case. The load factors were developed on the assumption that designers would consider the seriousness of possible failure in specifying the magnitude of their service loads. Furthermore, the ACI load factors are minimum values, and designers are perfectly free to use larger factors as they desire. The magnitude of wind loads and seismic loads, however, reflects the importance of the structure*. For example, in ASCE-7,3 a hospital must be designed for an earthquake load 50% larger than a comparable building with less serious consequences of failure.

For some special situations, ACI Section 9.2 permits reductions in the specified load factors. These situations are as follows:

- **(a)** In ACI Equations 9-3 to 9-5, the factor used for live loads may be reduced to 0.5 except for garages, areas used for public assembly, and all areas where the live loads exceed 100 psf.
- **(b)** If the load *W* is based on service-level wind loads, replace 1.0*W* in ACI Equations 9-4 and 9-6 with 1.6*W*. Also, replace 0.5*W* with 0.8*W* in ACI Equation 9-3.
- **(c)** Frequently, building codes and design load references convert seismic loads to strengthlevel values (i.e., in effect they have already been multiplied by a load factor). This is the situation assumed in ACI Equations 9-5 and 9-7. If, however, service-load seismic forces are specified, it will be necessary to replace 1.0*E* with 1.4*E* in these two equations.
- **(d)** Self-restraining effects, *T*, in reinforced concrete structures include the effects of temperature, creep, shrinkage, and differential settlement. In some cases, the effects can be additive. For example, creep, shrinkage, and reduction in temperature all cause a reduction of concrete volume. Often such effects can be reduced or eliminated by proper use of control joints.
- **(e)** Fluid loads, *F*, resulting from the weight and pressure of fluids shall be included with the same load factor as *D* in ACI Equations 9-5 through 9-7.

<sup>3</sup> American Society of Civil Engineers, *Minimum Design Loads for Buildings and Other Structures*. ASCE 7-10 (Reston, VA: American Society of Civil Engineers), p. 5.

- **(f)** Where soil loads, *H*, are present, they must be added to the load combinations in accordance with one of the following:
  - where *H* acts alone or adds to the effects of other loads, it shall be included with a load factor of 1.6;
  - where the effect of *H* is permanent and counteracts the effects of other loads, it shall be included with a load factor of 0.9;
  - where the effect of *H* is not permanent but, when present, counteracts the effects of other loads, *H* shall not be included.

Example 4.1 presents the calculation of factored loads for a reinforced concrete column using the ACI load combinations. The largest value obtained is referred to as the critical or governing load combination and is the value to be used in design. *Notice that the values of the wind and seismic loads can be different depending on the direction of those forces, and it may be possible for the sign of those loads to be different (i.e., compression or tension)*. This is the situation assumed to exist in the column of this example. These rather tedious calculations can be easily handled with the Excel spreadsheet entitled Load Combinations on this book's website: [www.wiley.com/college/mccormac.](http://www.wiley.com/college/mccormac)

### Example 4.1

The compression gravity axial loads for a building column have been estimated with the following results: *D* = 150 k; live load from roof, *Lr* = 60 k; and live loads from floors, *L* = 300 k. Compression wind, *W* = 112 k; tensile wind, *W* = 96 k; seismic compression load = 50 k; and tensile seismic load = 40 k. Determine the critical design load using the ACI load combinations.

#### **SOLUTION**

```
(9-1) U = 1.4D = (1.4) (150 k) = 210 k
(9-2) U = 1.2D + 1.6L + 0.5(Lr or S or R) = (1.2) (150 k) + (1.6) (300 k) + (0.5) (60 k) = 690 k
(9-3)(a) U = 1.2D + 1.6(Lr or S or R) + (L or 0.5W) = (1.2) (150 k) + (1.6) (60 k) + (300 k) = 576 k
    (b) U = 1.2D + 1.6(Lr or S or R) + (L or 0.5W) = (1.2) (150 k) + (1.6) (60 k) + (0.5) (70 k) = 311 k
    (c) U = 1.2D + 1.6(Lr or S or R) + (L or 0.5W) = (1.2) (150 k) + (1.6) (60 k) + (0.5) (−60 k) = 246 k
(9-4)(a) U = 1.2D + 1.0W + L + 0.5(Lr or S or R) = (1.2) (150 k) + (1.0) (70 k) + (300 k) + 0.5(60 k) = 580 k
    (b) U = 1.2D + 1.0W + L + 0.5(Lr or S or R) = (1.2) (150 k) + (1.0) (−60 k) + (300 k) + 0.5(60 k) = 450 k
(9-5)(a) U = 1.2D + 1.0E + L + 0.2S = (1.2) (150 k) + (1.0) (50 k) + (300 k) + (0.2) (0 k) = 530 k
    (b) U = 1.2D + 1.0E + L + 0.2S = (1.2) (150 k) + (1.0) (−40 k) + (300 k) + (0.2) (0 k) = 440 k
(9-6)(a) U = 0.9D + 1.0W = (0.9) (150 k) + (1.0) (70 k) = 205 k
    (b) U = 0.9D + 1.0W = (0.9) (150 k) + (1.0) (−60 k) = 75 k
(9-7)(a) U = 0.9D + 1.0E = (0.9) (150) + (1.0) (50 k) = 185 k
    (b) U = 0.9D + 1.0E = (0.9) (150) + (1.0) (−40 k) = 95 k
```

*Answer:* Largest value = 690 k from load case 9.2.

For most of the example problems presented in this textbook, in the interest of reducing the number of computations, only dead and live loads are specified. As a result, the only load factor combination usually applied herein is the one presented by ACI Equation 9-2. Occasionally, when the dead load is quite large compared to the live load, it is also necessary to consider Equation 9-1.

### 4.2 Design of Rectangular Beams

Before the design of an actual beam is attempted, several miscellaneous topics need to be discussed. These include the following:

- 1. Beam proportions. Unless architectural or other requirements dictate the proportions of reinforced concrete beams, the most economical beam sections are usually obtained for shorter beams (up to 20 ft or 25 ft in length), when the ratio of d to b is in the range of  $1\frac{1}{2}$  to 2. For longer spans, better economy is usually obtained if deep, narrow sections are used. The depths may be as large as three or four times the widths. However, today's reinforced concrete designer is often confronted with the need to keep members rather shallow to reduce floor heights. As a result, wider and shallower beams are used more frequently than in the past. You will notice that the overall beam dimensions are selected to whole inches. This is done for simplicity in constructing forms or for the rental of forms, which are usually available in 1-in. or 2-in. increments. Furthermore, beam widths are often selected in multiples of 2 in. or 3 in.
- 2. Deflections. Considerable space is devoted in Chapter 6 to the topic of deflections in reinforced concrete members subjected to bending. However, the ACI Code in its Table 9.5(a) provides minimum thicknesses of beams and one-way slabs for which such deflection calculations are not required. These values are shown in Table 4.1. The purpose of such limitations is to prevent deflections of such magnitudes as would interfere with the use of or cause injury to the structure. If deflections are computed for members of lesser thicknesses than those listed in the table and are found to be satisfactory, it is not necessary to abide by the thickness rules. For simply supported slabs, normal-weight concrete, and Grade 60 steel, the minimum depth given when deflections are not computed equals  $\ell/20$ , where  $\ell$  is the span length of the slab. For concrete of other weights and for steel of different yield strengths, the minimum depths required by the ACI Code are somewhat revised, as indicated in the footnotes to Table 4.1. The ACI does not specify changes in the table for concretes weighing between 120 lb/ft and 145 lb/ft because substitution into the correction expression given yields correction factors almost equal to 1.0.

The minimum thicknesses provided apply only to members that are not supporting or attached to partitions or other construction likely to be damaged by large deflections.

**3.** Estimated beam weight. The weight of the beam to be selected must be included in the calculation of the bending moment to be resisted, because the beam must support itself as well as the external loads. The weight estimates for the beams selected in this text are generally very close because the authors were able to perform a little preliminary paperwork before

**TABLE 4.1** Minimum Thickness of Nonprestressed Beams or One-Way Slabs Unless Deflections Are Computed<sup>1,2</sup>

|                               | Minimum Thickness, h |                                                                                                                  |                      |            |  |  |
|-------------------------------|----------------------|------------------------------------------------------------------------------------------------------------------|----------------------|------------|--|--|
|                               | Simply supported     | One end continuous                                                                                               | Both ends continuous | Cantilever |  |  |
| Member                        |                      | Members not supporting or attached to partitions or other construction likely to be damaged by large deflections |                      |            |  |  |
| Solid one-way slabs           | ℓ/20                 | ℓ/24                                                                                                             | ℓ/28                 | ℓ/10       |  |  |
| Beams or ribbed one-way slabs | ℓ/16                 | ℓ/18.5                                                                                                           | ℓ/21                 | ℓ/8        |  |  |

<sup>&</sup>lt;sup>1</sup>Span length,  $\ell$ , is in inches.

<sup>&</sup>lt;sup>2</sup>Values given shall be used directly for members with normal-weight concrete and Grade 60 reinforcement. For other conditions, the values shall be modified as follows:

<sup>(</sup>a) For lightweight concrete having equilibrium density in the range 90 lb/ft<sup>3</sup> to 115 lb/ft<sup>3</sup>, the values shall be multiplied by  $(1.65 - 0.005w_c)$  but not less than 1.09, where  $w_c$  is the unit weight in lb/ft<sup>3</sup>.

<sup>(</sup>b) For  $f_V$  other than 60,000 psi, the values shall be multiplied by  $(0.4 + f_V/100,000)$ .

making their estimates. You are not expected to be able to glance at a problem and give an exact estimate of the weight of the beam required. Following the same procedures as did the authors, however, you can do a little figuring on the side and make a very reasonable estimate. For instance, you could calculate the moment due to the external loads only, select a beam size, and calculate its weight. From this beam size, you should be able to make a very good estimate of the weight of the final beam section.

Another practical method for estimating beam sizes is to assume a minimum overall depth, h, equal to the minimum depth specified by Table 4.1 [ACI-318-11, Table 9.5(a)] if deflections are not to be calculated. The ACI minimum for the beam in question may be determined by referring to Table 4.1. Then the beam width can be roughly estimated equal to about one-half of the assumed value of h and the weight of this estimated beam calculated = bh/144 times the concrete weight per cubic foot. Because concrete weighs approximately 150 pcf (if the weight of steel is included), a quick-and-dirty calculation of self-weight is simply  $b \times h$  because the concrete weight approximately cancels the 144 conversion factor.

After  $M_u$  is determined for all of the loads, including the estimated beam weight, the section is selected. If the dimensions of this section are significantly different from those initially assumed, it will be necessary to recalculate the weight and  $M_{\mu}$  and repeat the beam selection. At this point you may very logically ask, "What's a significant change?" Well, you must realize that we are not interested academically in how close our estimated weight is to the final weight, but rather we are extremely interested in how close our calculated  $M_{\nu}$  is to the actual  $M_{\nu}$ . In other words, our estimated weight may be considerably in error, but if it doesn't affect  $M_{\mu}$  by more than say 1% or  $1\frac{1}{2}$ %, forget it.

In Example 4.2, beam proportions are estimated as just described, and the dimensions so selected are taken as the final ones. As a result, you can see that it is not necessary to check the beam weight and recalculate  $M_{\mu}$  and repeat the design.

In Example 4.3, a beam is designed for which the total value of  $M_u$  (including the beam weight) has been provided, as well as a suggested steel percentage.

Finally, with Example 4.4, the authors have selected a beam whose weight is unknown. Without a doubt, many students initially have a little difficulty understanding how to make reasonable member weight estimates for cases such as this one. To show how easily, quickly, and accurately this may be done for beams, this example is included.

We dreamed up a beam weight estimated out of the blue equal to 400 lb/ft. (We could just as easily and successfully have made it 10 lb/ft or 1000 lb/ft.) With this value, a beam section was selected and its weight calculated to equal 619 lb/ft. With this value, a very good weight estimate was then made. The new section obviously would be a little larger than the first one. So we estimated the weight a little above the 619 lb/ft value, recalculated the moment, selected a new section, and determined its weight. The results were very satisfactory.

- **4.** Selection of bars. After the required reinforcing area is calculated, Appendix A, Table A.4 is used to select bars that provide the necessary area. For the usual situations, bars of sizes #11 and smaller are practical. It is usually convenient to use bars of one size only in a beam, although occasionally two sizes will be used. Bars for compression steel and stirrups are usually a different size, however. Otherwise the ironworkers may become confused.
- 5. Cover. The reinforcing for concrete members must be protected from the surrounding environment; that is, fire and corrosion protection need to be provided. To do this, the reinforcing is located at certain minimum distances from the surface of the concrete so that a protective layer of concrete, called *cover*, is provided. In addition, the cover improves the bond between the concrete and the steel. In Section 7.7 of the ACI Code, specified cover is given for reinforcing bars under different conditions. Values are given for reinforced concrete beams, columns, and slabs; for cast-in-place members; for precast members; for prestressed members; for members exposed to earth and weather; for members not so exposed; and so on. The concrete for members that are to be exposed to deicing salts, brackish water, seawater, or

![](_page_106_Figure_2.jpeg)

FIGURE 4.1 Determining minimum edge distance.

spray from these sources must be especially proportioned to satisfy the exposure requirements of Chapter 4 of the code. These requirements pertain to air entrainment, water–cement ratios, cement types, concrete strength, and so on.

The beams designed in Examples 4.2, 4.3, and 4.4 are assumed to be located inside a building and thus protected from the weather. For this case, the code requires a minimum cover of  $1\frac{1}{2}$  in. of concrete outside of any reinforcement.

In Chapter 8, you will learn that vertical stirrups are used in most beams for shear reinforcing. A sketch of a stirrup is shown in the beam of Figure 4.1. The minimum stirrup diameter  $(d_s)$  that the code permits us to use is  $\frac{3}{8}$  in. when the longitudinal bars are #10 or smaller; for #11 and larger bars, the minimum stirrup diameter is  $\frac{1}{2}$  in. The minimum inside radius of the 90° stirrup bent around the outside longitudinal bars is two times the stirrup diameter  $(2d_s)$ . As a result, when the longitudinal bars are #14 or smaller, there will be a gap between the bars and the stirrups, as shown in the figure. This is based on the assumption that each outside longitudinal bar is centered over the horizontal point of tangency of the stirrup corner bend. For #18 bars, however, the half-bar diameter is larger than  $2d_s$  and controls.

For the beam of Figure 4.1 it is assumed that 1.50-in. clear cover, #3 stirrups, and #10 longitudinal bars are used. The minimum horizontal distance from the center of the outside longitudinal bars to the edge of the concrete can be determined as follows:

Minimum edge distance = cover + 
$$d_s$$
 +  $2d_s$  = 1.50 in. +  $\frac{3}{8}$  in. + (2)  $\left(\frac{3}{8}$  in.  $\right)$  =  $2\frac{5}{8}$  in.

The minimum cover required for concrete cast against earth, as in a footing, is 3 in., and for concrete not cast against the earth but later exposed to it, as by backfill, 2 in. Precast and prestressed concrete or other concrete cast under plant control conditions requires less cover, as described in Sections 7.7.2 and 7.7.3 of the ACI Code.

Notice the two #4 bars called *hangers* placed in the compression side of this beam. Their purpose is to provide support for the stirrups and to hold the stirrups in position.

If concrete members are exposed to very harsh surroundings, such as deicing salts, smoke, or acid vapors, the cover should be increased above these minimums.

**6.** Minimum spacing of bars. The code (7.6) states that the clear distance between parallel bars cannot be less than 1 in.<sup>[4]</sup> or less than the nominal bar diameter. If the bars are placed in more than one layer, those in the upper layers are required to be placed directly over the ones in the lower layers, and the clear distance between the layers must be not less than 1 in.

<sup>&</sup>lt;sup>4</sup> 25 mm in SI.

![](_page_107_Picture_2.jpeg)

Reinforcing bars. Note the supporting metal chairs.

A major purpose of these requirements is to enable the concrete to pass between the bars. The ACI Code further relates the spacing of the bars to the maximum aggregate sizes for the same purpose. In the code Section 3.3.2, maximum permissible aggregate sizes are limited to the smallest of (a) one-fifth of the narrowest distance between side forms, (b) one-third of slab depths, and (c) three-fourths of the minimum clear spacing between bars.

A reinforcing bar must extend an appreciable length in both directions from its point of highest stress in order to develop its stress by bonding to the concrete. The shortest length in which a bar's stress can be increased from 0 to  $f_v$  is called its development length.

If the distance from the end of a bar to a point where it theoretically has a stress equal to  $f_y$  is less than its required development length, the bar may very well pull loose from the concrete. Development lengths are discussed in detail in Chapter 7. There you will learn that required development lengths for reinforcing bars vary appreciably with their spacings and their cover. As a result, it is sometimes wise to use greater cover and larger bar spacings than the specified minimum values in order to reduce development lengths.

When selecting the actual bar spacing, the designer will comply with the preceding code requirements and, in addition, will give spacings and other dimensions in inches and fractions, not in decimals. The workers in the field are accustomed to working with fractions and would be confused by a spacing of bars such as 3 at 1.45 in. The designer should always strive for simple spacings, for such dimensions will lead to better economy.

Each time a beam is designed, it is necessary to select the spacing and arrangement of the bars. To simplify these calculations, Appendix A, Table A.5 is given. Corresponding information is provided in SI units in Appendix B, Table B.5. These tables show the minimum beam widths required for different numbers of bars. The values given are based on the assumptions that  $\frac{3}{8}$ -in. stirrups and  $1\frac{1}{2}$ -in. cover are required except for #18 bars, where the stirrup diameter is  $\frac{1}{2}$  in. If three #10 bars are required, it can be seen from the table that a minimum beam width of 10.4 in. (say 11 in.) is required.

This value can be checked as follows, noting that  $2d_s$  is the radius of bend of the bar, and the minimum clear spacing between bars in this case is  $d_b$ :

$$\begin{aligned} \text{Minimum beam width} &= \text{cover} + d_s + 2d_s + \frac{d_b}{2} + d_b + d_b + d_b + \frac{d_b}{2} + 2d_s + d_s + \text{cover} \\ &= 1.50 \text{ in.} + \frac{3}{8} \text{ in.} + (2) \left( \frac{3}{8} \text{ in.} \right) + \frac{1.27 \text{ in.}}{2} + (3) \left( 1.27 \text{ in.} \right) + \frac{1.27 \text{ in.}}{2} \\ &+ (2) \left( \frac{3}{8} \text{ in.} \right) + \frac{3}{8} \text{ in.} + 1.50 \text{ in.} \end{aligned}$$

= 10.33 in. rounded to 10.4 in.

### 4.3 Beam Design Examples

Example 4.2 illustrates the design of a simple span rectangular beam. For this introductory example, approximate dimensions are assumed for the beam cross section. The depth, h, is assumed to equal about one-tenth of the beam span, while its width, b, is assumed to equal about  $\frac{1}{2}h$ . Next the percentage of reinforcing needed is determined with the equation derived in Section 3.4, and reinforcing bars are selected to satisfy that percentage. Finally,  $\phi M_n$  is calculated for the final design.

#### Example 4.2

Design a rectangular beam for a 22-ft simple span if a dead load of 1 k/ft (not including the beam weight) and a live load of 2 k/ft are to be supported. Use  $f'_c = 4000$  psi and  $f_v = 60,000$  psi.

#### SOLUTION

#### **Estimating Beam Dimensions and Weight**

Assume 
$$h = (0.10) (22 \text{ ft}) = 2.2 \text{ ft}$$
 Say 27 in.  $(d = 24.5 \text{ in.})$ 

Assume  $b = \frac{1}{2}h = \frac{27 \text{ in.}}{2}$  Say 14 in.

Beam wt  $= \frac{(14 \text{ in.}) (27 \text{ in.})}{144 \text{ in}^2/\text{ft}^2} (150 \text{ lb/ft}^3) = 394 \text{ lb/ft} = 0.394 \text{ k/ft} (\text{klft})$ 

Computing  $w_u$  and  $M_u$ 

$$w_u = (1.2)(1 \text{ klf} + 0.394 \text{ klf}) + (1.6)(2 \text{ klf}) = 4.873 \text{ klf}$$
  
$$M_u = \frac{w_u L^2}{8} = \frac{(4.873 \text{ klf})(22 \text{ ft})^2}{8} = 294.8 \text{ ft-k}$$

Assuming  $\phi=0.90$  and computing  $\rho$  with the following expression, which was derived in Section 3.4.

$$\rho = \frac{0.85f'_c}{f_y} \left( 1 - \sqrt{1 - \frac{2R_n}{0.85f'_c}} \right)$$

$$R_n = \frac{M_u}{\phi b d^2} = \frac{(12 \text{ in/ft}) (294,800 \text{ ft-lb})}{(0.90) (14 \text{ in.}) (24.5 \text{ in.})^2} = 467.7 \text{ psi}$$

$$\rho = \frac{(0.85) (4000 \text{ psi})}{60,000 \text{ psi}} \left[ 1 - \sqrt{1 - \frac{(2) (467.7 \text{ psi})}{(0.85) (4000 \text{ psi})}} \right] = 0.00842$$

#### Selecting Reinforcing

$$A_{\rm s} = \rho bd = (0.00842)\,(14~{\rm in.})\,(24.5~{\rm in.}) = 2.89~{\rm in.}^2$$
 Use 3 #9 bars ( $A_{\rm s} = 3.00~{\rm in.}^2$ )

