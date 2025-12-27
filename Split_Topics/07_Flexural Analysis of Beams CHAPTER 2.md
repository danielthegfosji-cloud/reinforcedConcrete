# Flexural Analysis of Beams **CHAPTER 2**

### **2.1 Introduction**

In this section, it is assumed that a small transverse load is placed on a concrete beam with tensile reinforcing and that the load is gradually increased in magnitude until the beam fails. As this takes place, the beam will go through three distinct stages before collapse occurs. These are: (1) the uncracked concrete stage, (2) the concrete cracked–elastic stresses stage, and (3) the ultimate-strength stage. A relatively long beam is considered for this discussion so that shear will not have a large effect on its behavior.

### **Uncracked Concrete Stage**

At small loads when the tensile stresses are less than the *modulus of rupture* (the bending tensile stress at which the concrete begins to crack), the entire cross section of the beam resists bending, with compression on one side and tension on the other. Figure 2.1 shows the variation of stresses and strains for these small loads; a numerical example of this type is presented in Section 2.2.

### **Concrete Cracked–Elastic Stresses Stage**

As the load is increased after the modulus of rupture of the concrete is exceeded, cracks begin to develop in the bottom of the beam. The moment at which these cracks begin to form—that is, when the tensile stress in the bottom of the beam equals the modulus of rupture—is referred to as the *cracking moment*, *Mcr*. As the load is further increased, these cracks quickly spread up to the vicinity of the neutral axis, and then the neutral axis begins to move upward. The cracks occur at those places along the beam where the actual moment is greater than the cracking moment, as shown in Figure 2.2(a).

Now that the bottom has cracked, another stage is present because the concrete in the cracked zone obviously cannot resist tensile stresses—the steel must do it. This stage will

![](_page_54_Picture_9.jpeg)

**FI GU RE 2.1** Uncracked concrete stage.

![](_page_55_Picture_2.jpeg)

**FI GU RE 2.2** Concrete cracked–elastic stresses stage.

continue as long as the compression stress in the top fibers is less than about one-half of the concrete's compression strength, *f <sup>c</sup>* , and as long as the steel stress is less than its yield stress. The stresses and strains for this range are shown in Figure 2.2(b). In this stage, the compressive stresses vary linearly with the distance from the neutral axis or as a straight line.

The straight-line stress–strain variation normally occurs in reinforced concrete beams under normal service-load conditions because at those loads, the stresses are generally less than 0.50*f <sup>c</sup>* . To compute the concrete and steel stresses in this range, the transformed-area method (to be presented in Section 2.3) is used. The *service* or *working* loads are the loads that are assumed to actually occur when a structure is in use or service. Under these loads, moments develop that are considerably larger than the cracking moments. Obviously, the tensile side of the beam will be cracked. You will learn to estimate crack widths and methods of limiting their widths in Chapter 6.

#### **Beam Failure—Ultimate-Strength Stage**

As the load is increased further so that the compressive stresses are greater than 0.50*f <sup>c</sup>* , the tensile cracks move farther upward, as does the neutral axis, and the concrete compression stresses begin to change appreciably from a straight line. For this initial discussion, it is assumed that the reinforcing bars have yielded. The stress variation is much like that shown in Figure 2.3. You should relate the information shown in this figure to that given in Figure 1.1 in Chapter 1 as to the changing ratio of stress to strain at different stress levels.

To further illustrate the three stages of beam behavior that have just been described, a moment–curvature diagram is shown in Figure 2.4.1 For this diagram, θ is defined as the angle

<sup>1</sup> MacGregor, J. G., 2005, *Reinforced Concrete Mechanics and Design*, 4th ed. (Upper Saddle River, NJ: Prentice Hall), p. 109.

![](_page_56_Figure_2.jpeg)

**FI GU RE 2.3** Ultimate-strength stage.

![](_page_56_Figure_4.jpeg)

**FI GU RE 2.4** Moment–curvature diagram for reinforced concrete beam with tensile reinforcing only.

change of the beam section over a certain length and is computed by the following expression in which is the strain in a beam fiber at some distance, *y*, from the neutral axis of the beam:

$$\theta = \frac{\epsilon}{y}$$

The first stage of the diagram is for small moments less than the cracking moment, *Mcr*, where the entire beam cross section is available to resist bending. In this range, the strains are small, and the diagram is nearly vertical and very close to a straight line. When the moment is increased beyond the cracking moment, the slope of the curve will decrease a little because the

![](_page_57_Picture_2.jpeg)

Construction of Kingdome, Seattle, Washington.

beam is not quite as stiff as it was in the initial stage before the concrete cracked. The diagram will follow almost a straight line from  $M_{cr}$  to the point where the reinforcing is stressed to its yield point. Until the steel yields, a fairly large additional load is required to appreciably increase the beam's deflection.

After the steel yields, the beam has very little additional moment capacity, and only a small additional load is required to substantially increase rotations as well as deflections. The slope of the diagram is now very flat.

#### 2.2 **Cracking Moment**

The area of reinforcing as a percentage of the total cross-sectional area of a beam is quite small (usually 2% or less), and its effect on the beam properties is almost negligible as long as the beam is uncracked. Therefore, an approximate calculation of the bending stresses in such a beam can be obtained based on the gross properties of the beam's cross section. The stress in the concrete at any point a distance y from the neutral axis of the cross section can be determined from the following flexure formula in which M is the bending moment equal to or less than the cracking moment of the section and  $I_g$  is the gross moment of inertia of the cross section:

$$f = \frac{My}{I_{\varrho}}$$

Section 9.5.2.3 of the ACI Code states that the cracking moment of a section may be determined with ACI Equation 9-9, in which  $f_r$  is the modulus of rupture of the concrete and y, is the distance from the centroidal axis of the section to its extreme fiber in tension. In this section, with its equation 9-10, the code states that  $f_r$  may be taken equal to  $7.5\lambda\sqrt{f_c'}$  with  $f_c'$ in psi.

The "lambda" term is 1.0 for normal-weight concrete and is less than 1.0 for lightweight concrete, as described in Section 1.12. The cracking moment is as follows:

$$M_{cr} = \frac{f_r I_g}{y_t}$$
 (ACI Equation 9-9)

Example 2.1 presents calculations for a reinforced concrete beam where tensile stresses are less than its modulus of rupture. As a result, no tensile cracks are assumed to be present, and the stresses are similar to those occurring in a beam constructed with a homogeneous material.

#### Example 2.1

- (a) Assuming the concrete is uncracked, compute the bending stresses in the extreme fibers of the beam of Figure 2.5 for a bending moment of 25 ft-k. The normal-weight concrete has an  $f_c$  of 4000 psi and a modulus of rupture  $f_c = 7.5(1.0)\sqrt{4000}$  psi = 474 psi.
- **(b)** Determine the cracking moment of the section.

#### SOLUTION

(a) Bending stresses:

$$I_g = \frac{1}{12}bh^3$$
 with  $b = 12$  in. and  $h = 18$  in.   
 $I_g = \left(\frac{1}{12}\right)(12 \text{ in.})(18 \text{ in.})^3 = 5832 \text{ in.}^4$    
 $f = \frac{My}{I_g}$  with  $M = 25 \text{ ft-k} = 25,000 \text{ ft-lb}$ 

Next, multiply the 25,000 ft-lb by 12 in/ft to obtain in-lb as shown here:

$$f = \frac{\text{(12 in/ft} \times 25,000 ft-lb) (9.00 in.)}{5832 in.^4} = 463 \text{ psi}$$

Since this stress is less than the tensile strength or modulus of rupture of the concrete of 474 psi, the section is assumed not to have cracked.

(b) Cracking moment:

$$M_{cr} = \frac{f_r I_g}{y_t} = \frac{(474 \text{ psi}) (5832 \text{ in.}^4)}{9.00 \text{ in.}} = 307,152 \text{ in-lb} = \underline{25.6 \text{ ft-k}}$$

![](_page_58_Figure_16.jpeg)

**FIGURE 2.5** Beam cross section for Example 2.1.

#### Example 2.2

- (a) If the T-beam shown is uncracked, calculate the stress in the concrete at the top and bottom extreme fibers under a positive bending moment of 80 ft-k.
- (b) If  $f_c' = 3000$  psi and normal-weight concrete is used, what is the maximum uniformly distributed load the beam can carry if it is used as a simple beam with 24-ft span without exceeding the modulus of rupture of the concrete?
- (c) Repeat part (b) if the beam is inverted.

![](_page_59_Picture_6.jpeg)

#### SOLUTION

(a) Locate the neutral axis with respect to the top of the section:

$$\overline{y} = \frac{b_f h_f \left(\frac{h_f}{2}\right) + (b_f) (h - h_f) \left(h_f - \frac{h - h_f}{2}\right)}{b_f h_f + (b_f) (h - h_f)}$$

$$= \frac{(60 \text{ in.}) (5 \text{ in.}) (2.5 \text{ in.}) + (12 \text{ in.}) (27 \text{ in.}) \left(5 \text{ in.} + \frac{27 \text{ in.}}{2}\right)}{(60 \text{ in.}) (5 \text{ in.}) + (12 \text{ in.}) (27 \text{ in.})} = 10.81 \text{ in.}$$

The moment of inertia is:

$$I_{g} = \frac{b_{f}h_{f}^{3}}{12} + b_{f}h_{f} \left[ \left( \overline{y} - \frac{h_{f}}{2} \right)^{2} + \frac{b_{w}(h - h_{f})^{3}}{12} + b_{w}(h - h_{f}) \right] \left[ \overline{y} - h_{f} - \frac{(h - h_{f})}{2} \right]^{2}$$

$$= \frac{(60 \text{ in.}) (5 \text{ in.})^{3}}{12} + (60 \text{ in.}) (5 \text{ in.}) \left( 10.81 \text{ in.} - \frac{5 \text{ in.}}{2} \right)^{2} + \frac{(12 \text{ in.}) (32 \text{ in.} - 5 \text{ in.})^{3}}{12}$$

$$+ (12 \text{ in.}) (32 \text{ in.} - 5 \text{ in.}) \left( 10.81 \text{ in.} - 5 \text{ in.} - \frac{27 \text{ in.}}{2} \right)^{2}$$

$$= 60.185 \text{ in.}^{4}$$

The stress in the bottom fiber under the given moment of 80 ft-k is:

$$f_{\text{top}} = \frac{Mc}{I} = \frac{\text{(80 ft-k) (12 in/ft) (32 in.} - 10.81 in.)}{60,185 in.^4} = 0.338 \text{ k/in.}^2 = 338 \text{ lb/in.}^2$$

The stress in the top fiber is:

$$f_{\text{top}} = \frac{Mc}{I} = \frac{\text{(80 ft-k) (12 in/ft) (10.81 in.)}}{60.185 \text{ in.}^4} = 0.172 \text{ k/in.}^2 = 172 \text{ lb/in.}^2$$

**(b)** The modulus of rupture,  $f_r$ , of normal-weight concrete with  $f_c' = 3000$  psi is:

$$f_r = 7.5\lambda \sqrt{f_c'} = 7.5(1.0)\sqrt{3000} = 411 \text{ lb/in.}^2$$

The moment that causes a stress equal to the modulus of rupture is:

$$M_{cr} = \frac{f_r I_g}{c} = \frac{(411 \text{ lb/in.}^2) (60,185 \text{ in.}^4)}{(32 \text{ in.} - 10.81 \text{ in.})} = 1167.344 \text{ in-lb} = 97.28 \text{ ft-k}$$

The uniformly distributed load on a simple span that causes this much moment is:

$$w = \frac{8M}{l^2} = \frac{8(97.28 \text{ ft-k})}{(24 \text{ ft})^2} = 1.351 \text{ k/ft} = 1351 \text{ lb/ft}$$

(c) If the beam is inverted, then the c term used to calculate M<sub>cr</sub> is 10.81 in. instead of 21.19 in., hence:

$$M_{cr} = \frac{f_r I_g}{c} = \frac{(411 \text{ lb/in.}^2)(60,185 \text{ in.}^4)}{(10.81 \text{ in.})} = 2,288,255 \text{ in-lb} = 190.69 \text{ ft-k}$$

The uniformly distributed load on a simple span that causes this much moment is:

$$w = \frac{8M}{l^2} = \frac{8(190.69 \text{ ft-k})}{(24 \text{ ft})^2} = 2.648 \text{ k/ft} = 2648 \text{ lb/ft}$$

This is almost double the load that the beam can carry if oriented the opposite way. Don't get the impression that this is the best orientation for a T beam, however. In the next section, when we examine reinforced sections, the opposite will be true.

### 2.3 Elastic Stresses - Concrete Cracked

When the bending moment is sufficiently large to cause the tensile stress in the extreme fibers to be greater than the modulus of rupture, it is assumed that all of the concrete on the tensile side of the beam is cracked and must be neglected in the flexure calculations.

The cracking moment of a beam is normally quite small compared to the service load moment. Thus, when the service loads are applied, the bottom of the beam cracks. The cracking of the beam does not necessarily mean that the beam is going to fail. The reinforcing bars on the tensile side begin to pick up the tension caused by the applied moment.

On the tensile side of the beam, an assumption of perfect bond is made between the reinforcing bars and the concrete. Thus, the strain in the concrete and in the steel will be equal at equal distances from the neutral axis. If the strains in the two materials at a particular point are the same, however, their stresses cannot be the same since they have different moduli of elasticity. Thus, their stresses are in proportion to the ratio of their moduli of elasticity. The ratio of the steel modulus to the concrete modulus is called the *modular ratio*, n:

$$n = \frac{E_s}{E_c}$$

If the modular ratio for a particular beam is 10, the stress in the steel will be 10 times the stress in the concrete at the same distance from the neutral axis. Another way of saying this is that when n = 10, 1 in.<sup>2</sup> of steel will carry the same total force as 10 in.<sup>2</sup> of concrete.

For the beam of Figure 2.6, the steel bars are replaced with an equivalent area of fictitious concrete  $(nA_s)$ , which supposedly can resist tension. This area is referred to as the *transformed area*. The resulting revised cross section or transformed section is handled by the usual methods for elastic homogeneous beams. Also shown in the figure is a diagram showing the stress variation in the beam. On the tensile side, a dashed line is shown because the diagram is

![](_page_61_Picture_2.jpeg)

**FI GU RE 2.6** Cracked, transformed section.

discontinuous. There, the concrete is assumed to be cracked and unable to resist tension. The value shown opposite the steel is the fictitious stress in the concrete if it could carry tension. This value is shown as *fs*/*n* because it must be multiplied by *n* to give the steel stress *fs*.

Examples 2.3, 2.4, and 2.5 are transformed-area problems that illustrate the calculations necessary for determining the stresses and resisting moments for reinforced concrete beams. The first step to be taken in each of these problems is to locate the neutral axis, which is assumed to be located a distance *x* from the compression surface of the beam. The first moment of the compression area of the beam cross section about the neutral axis must equal the first moment of the tensile area about the neutral axis. The resulting quadratic equation can be solved by completing the squares or by using the quadratic formula.

![](_page_61_Picture_6.jpeg)

Bridge construction on an expressway interchange.

After the neutral axis is located, the moment of inertia of the transformed section is calculated, and the stresses in the concrete and the steel are computed with the flexure formula.

#### Example 2.3

Calculate the bending stresses in the beam shown in Figure 2.7 by using the transformed area method,  $f'_c = 3000$  psi, n = 9, and M = 70 ft-k.

#### SOLUTION

Taking Moments about Neutral Axis (Referring to Figure 2.8)

(12 in.) (x) 
$$\left(\frac{x}{2}\right)$$
 = (9) (3.00 in.) (17 in. - x)  

$$6x^2 = 459 - 27.00x$$

Solving by Completing the Square

$$6x^{2} + 27.00x = 459$$

$$x^{2} + 4.50x = 76.5$$

$$(x + 2.25)(x + 2.25) = 76.5 + (2.25)^{2}$$

$$x = 2.25 + \sqrt{76.5 + (2.25)^{2}}$$

$$x = 6.780 \text{ in.}$$

Moment of Inertia

$$I = \left(\frac{1}{3}\right) (12 \text{ in.}) (6.78 \text{ in.})^3 + (9) (3.00 \text{ in.}^2) (10.22 \text{ in.})^2 = 4067 \text{ in.}^4$$

**Bending Stresses** 

$$f_c = \frac{My}{I} = \frac{(12) (70,000 \text{ ft-lb}) (6.78 \text{ in.})}{4067 \text{ in.}^4} = \underline{\frac{1400 \text{ psi}}{1}}$$

$$f_s = n \frac{My}{I} = (9) \frac{(12) (70,000 \text{ ft-lb}) (10.22 \text{ in.})}{4067 \text{ in.}^4} = \underline{\frac{18,998 \text{ psi}}{1}}$$

![](_page_62_Figure_14.jpeg)

FIGURE 2.7 Beam cross section for Example 2.3.

![](_page_62_Figure_16.jpeg)

FIGURE 2.8 Cracked, transformed section for Example 2.3.

#### Example 2.4

Determine the allowable resisting moment of the beam of Example 2.3, if the allowable stresses are  $f_c = 1350$  psi and  $f_s = 20,000$  psi.

#### SOLUTION

$$M_c = \frac{f_c I}{y} = \frac{(1350 \text{ psi}) (4067 \text{ in.}^4)}{6.78 \text{ in.}} = 809,800 \text{ in-lb} = \underline{67.5 \text{ ft-k}} \leftarrow M_s = \frac{f_s I}{ny} = \frac{(20,000 \text{ psi}) (4067 \text{ in.}^4)}{(9) (10.22 \text{ in.})} = 884,323 \text{ in-lb} = 73.7 \text{ ft-k}$$

#### **Discussion**

For a given beam, the concrete and steel will not usually reach their maximum allowable stresses at exactly the same bending moments. Such is the case for this example beam, where the concrete reaches its maximum permissible stress at 67.5 ft-k, while the steel does not reach its maximum value until 73.7 ft-k is applied. The resisting moment of the section is 67.5 ft-k because if that value is exceeded, the concrete becomes overstressed even though the steel stress is less than its allowable stress.

#### Example 2.5

Compute the bending stresses in the beam shown in Figure 2.9 by using the transformed-area method; n = 8 and M = 110 ft-k.

#### SOLUTION

#### Locating Neutral Axis (Assuming Neutral Axis below Hole)

$$(18 \text{ in.}) (x) \left(\frac{x}{2}\right) - (6 \text{ in.}) (6 \text{ in.}) (x - 3 \text{ in.}) = (8) (5.06 \text{ in.}^2) (23 \text{ in.} - x)$$

$$9x^2 - 36x + 108 = 931 - 40.48x$$

$$9x^2 + 4.48x = 823$$

$$x^2 + 0.50x = 91.44$$

$$(x + 0.25) (x + 0.25) = 91.44 + (0.25)^2 = 91.50$$

$$x + 0.25 = \sqrt{91.50} = 9.57$$

$$x = 9.32 \text{ in.} > 6 \text{ in.}$$

$$\therefore \text{ N.A. below hole as assumed}$$

#### Moment of Inertia

$$I = \left(\frac{1}{3}\right) (6 \text{ in.}) (9.32 \text{ in.})^3 (2) + \left(\frac{1}{3}\right) (6 \text{ in.}) (3.32 \text{ in.})^3 + (8) (5.06 \text{ in.}^2) (13.68 \text{ in.})^2 = 10,887 \text{ in.}^4$$

#### **Computing Stresses**

$$f_c = \frac{(12)(110,000 \text{ ft-lb})(9.32 \text{ in.})}{10,887 \text{ in.}^4} = \underline{\frac{1130 \text{ psi}}{10,887 \text{ in.}^4}}$$

$$f_s = (8)\frac{(12)(110,000 \text{ ft-lb})(13.68 \text{ in.})}{10,887 \text{ in.}^4} = \underline{\frac{13,269 \text{ psi}}{10,887 \text{ in.}^4}}$$

![](_page_64_Figure_2.jpeg)

**FIGURE 2.9** Beam cross section for Example 2.5.

#### Example 2.6

Calculate the bending stresses in the concrete and the reinforcing steel, using the transformed area method:  $f'_c = 3000$  psi, normal-weight concrete, n = 9, M = 250 ft-k.

![](_page_64_Figure_6.jpeg)

#### SOLUTION

Assume the neutral axis is in the web, and take moments about the neutral axis of the transformed section for this example:

$$(b_f - b_w)h_f\left(x - \frac{h_f}{2}\right) + \frac{b_w x^2}{2} = nA_s(d - x)$$

$$(60 \text{ in.} - 12 \text{ in.})(5 \text{ in.})\left(x - \frac{5 \text{ in.}}{2}\right) + \frac{(12 \text{ in.})(x)^2}{2} = (9)(4.71 \text{ in.}^2)(28 \text{ in.} - x)$$

Using a calculator with a solver for quadratic equations results in x=5.65 in. Since this value of x exceeds  $h_f$  of 5 in., the assumption that the neutral axis is in the web is valid. If x had been smaller than 5 in., then the value we obtained would not have been valid, and the preceding equations would have to be rewritten and solved assuming  $x < h_f$ .

$$I_{cr} = \frac{(b_f - b_w)h_f^3}{12} + (b_f - b_w)h_f \left(x - \frac{h_f}{2}\right)^2 + \frac{b_w x^3}{12} + b_w x \left(\frac{x}{2}\right) + nA_s (d - x)^2$$

$$= \frac{(60 \text{ in.} - 12 \text{ in.}) (5 \text{ in.})^3}{12} + (60 \text{ in.} - 12 \text{ in.}) (5 \text{ in.}) \left(5.65 \text{ in.} - \frac{5 \text{ in.}}{2}\right)^2$$

$$+ \frac{(12 \text{ in.}) (5.65 \text{ in.})^3}{3} + (9) (4.71 \text{ in.}^2) (28 \text{ in.} - 5.65 \text{ in.})$$

$$= 24,778 \text{ in.}^4$$

The T-shaped part of the transformed section could be divided into rectangles in other ways besides the one shown. The resulting answer would still be the same.

The stress in the concrete can now be calculated:

$$f_c = \frac{Mx}{I_{cr}} = \frac{(250 \text{ ft-k}) (5.65 \text{ in.}) (12 \text{ in/ft})}{24,778 \text{ in.}^4} = 0.684 \text{ k/in.}^2 = 684 \text{ lb/in.}^2$$

This concrete stress is well below the allowable values that were once in the ACI Code. They used to be  $0.45f'_{c} = (0.45)(3000 \text{ lb/in.}^2) = 1350 \text{ lb/in.}^2$ .

The stress in the reinforcing steel can now be calculated:

$$f_{\rm S} = \frac{nM(d-x)}{I_{\rm Cr}} = \frac{(9)\,(250\,\,{\rm ft-k})\,(28\,\,{\rm in.}\,-5.65\,\,{\rm in.})\,(12\,\,{\rm in/ft})}{24,778\,\,{\rm in.}^4} = 24.354\,\,{\rm k/in.}^2 = 24,354\,\,{\rm lb/in.}^2$$

This reinforcing steel stress is slightly greater than the allowable values that were once in the ACI Code. They used to be 24,000 lb/in.2 for Grade 60 reinforcing steel. This is about a 1.5% overstress in the steel, and many engineers would accept this much overstress as being within the accuracy of their other assumptions. This beam would be called "tension controlled" because the moment capacity is controlled by the steel, not the concrete. This same beam could be compression controlled if a lot more steel were used. Tension-controlled beams are preferable to compression-controlled ones, as will be discussed later in this text.

Example 2.7 illustrates the analysis of a doubly reinforced concrete beam—that is, one that has compression steel as well as tensile steel. Compression steel is generally thought to be uneconomical, but occasionally its use is quite advantageous.

Compression steel will permit the use of appreciably smaller beams than those that make use of tensile steel only. Reduced sizes can be very important where space or architectural requirements limit the sizes of beams. Compression steel is quite helpful in reducing long-term deflections, and such steel is useful for positioning stirrups or shear reinforcing, a subject to be discussed in Chapter 8. A detailed discussion of doubly reinforced beams is presented in Chapter 5.

The creep or plastic flow of concrete was described in Section 1.11. Should the compression side of a beam be reinforced, the long-term stresses in that reinforcing will be greatly affected by the creep in the concrete. As time goes by, the compression concrete will compact more tightly, leaving the reinforcing bars (which themselves have negligible creep) to carry more and more of the load.

As a consequence of this creep in the concrete, the stresses in the compression bars computed by the transformed-area method are assumed to double as time goes by. In Example 2.7, the transformed area of the compression bars is assumed to equal 2n times their area,  $A'_{\rm s}$ .

On the subject of "hairsplitting," it will be noted in the example that the compression steel area is really multiplied by 2n-1. The transformed area of the compression side equals the gross compression area of the concrete plus  $2nA'_s$  minus the area of the holes in the concrete  $(1A'_s)$ , which theoretically should not have been included in the concrete part. This equals the compression concrete area plus  $(2n-1)A_s'$ . Similarly, 2n-1 is used in the moment of inertia calculations. The stresses in the compression bars are determined by multiplying 2n times the stresses in the concrete located at the same distance from the neutral axis.

#### Example 2.7

Compute the bending stresses in the beam shown in Figure 2.10; n = 10 and M = 118 ft-k.

#### **SOLUTION**

#### **Locating Neutral Axis**

$$(14 in.)(x) \left(\frac{x}{2}\right) + (20 - 1)(2.00 in.^2)(x - 2.5 in.) = (10)(4.00 in.^2)(17.5 in. - x)$$

$$7x^2 + 38x - 95 = 700 - 40x$$

$$7x^2 + 78x = 795$$

$$x^2 + 11.14x = 113.57$$

$$x + 5.57 = \sqrt{113.57 + (5.57)^2} = 12.02$$

$$x = 6.45 in.$$

#### Moment of Inertia

$$I = \left(\frac{1}{3}\right) (14 \text{ in.}) (6.45 \text{ in.})^3 + (20 - 1) (2.00 \text{ in.}^2) (3.95 \text{ in.})^2 + (10) (4.00 \text{ in.}^2) (11.05 \text{ in.})^2$$

$$= 6729 \text{ in.}^4$$

#### **Bending Stresses**

$$f_c = \frac{(12) (118,000 \text{ ft-lb}) (6.45 \text{ in.})}{6729 \text{ in.}^4} = \underline{\frac{1357 \text{ psi}}{1}}$$

$$f_s' = 2n \frac{My}{I} = (2) (10) \frac{(12) (118,000 \text{ ft-lb}) (3.95 \text{ in.})}{6729 \text{ in.}^4} = \underline{\frac{16,624 \text{ psi}}{1}}$$

$$f_s = (10) \frac{(12) (118,000 \text{ ft-lb}) (11.05 \text{ in.})}{6729 \text{ in.}^4} = \underline{\frac{23,253 \text{ psi}}{1}}$$

![](_page_66_Figure_11.jpeg)

**FIGURE 2.10** Beam cross section for Example 2.7.

#### **Ultimate or Nominal Flexural Moments** 2.4

In this section, a very brief introduction to the calculation of the ultimate or nominal flexural strength of beams is presented. This topic is continued at considerable length in the next chapter, where formulas, limitations, designs, and other matters are presented. For this discussion, it is assumed that the tensile reinforcing bars are stressed to their yield point before the concrete on the compressive side of the beam is crushed. You will learn in Chapter 3 that the ACI Code requires all beam designs to fall into this category.

After the concrete compression stresses exceed about  $0.50f_c$ , they no longer vary directly as the distance from the neutral axis or as a straight line. Rather, they vary much as shown in Figure 2.11(b). It is assumed for the purpose of this discussion that the curved compression diagram is replaced with a rectangular one with a constant stress of  $0.85f_c$ , as shown in part (c) of the figure. The rectangular diagram of depth a is assumed to have the same c.g. (center of gravity) and total magnitude as the curved diagram. (In Section 3.4 of Chapter 3 of this text, you will learn that this distance a is set equal to  $\beta_1 c$ , where  $\beta_1$  is a value determined by testing and specified by the code.) These assumptions will enable us to easily calculate the theoretical or nominal flexural strength of reinforced concrete beams. Experimental tests show that with the assumptions used here, accurate flexural strengths are determined.

To obtain the nominal or theoretical moment strength of a beam, the simple steps to follow are illustrated in Figure 2.11 and Example 2.8.

- **1.** Compute total tensile force  $T = A_s f_v$ .
- **2.** Equate total compression force  $C = 0.85 f_c' ab$  to  $A_s f_v$  and solve for a. In this expression, ab is the assumed area stressed in compression at  $0.85f_c$ . The compression force C and the tensile force T must be equal to maintain equilibrium at the section.
- 3. Calculate the distance between the centers of gravity of T and C (For a rectangular beam cross section, it equals d - a/2.)
- **4.** Determine  $M_n$ , which equals T or C times the distance between their centers of gravity.

![](_page_67_Figure_10.jpeg)

FIGURE 2.11 Compression and tension couple at nominal moment.

#### Example 2.8

Determine  $M_n$ , the nominal or theoretical ultimate moment strength of the beam section shown in Figure 2.12, if  $f_v = 60,000$  psi and  $f_c' = 3000$  psi.

#### SOLUTION

#### Computing Tensile and Compressive Forces T and C

$$T = A_s f_y = (3.00 \text{ in.}^2) (60 \text{ k/in.}^2) = 180 \text{ k}$$
  
 $C = 0.85 f_c' ab = (0.85) (3 \text{ k/in.}^2) (a) (14 \text{ in.}) = 35.7a$ 

#### Equating T and C and Solving for a

$$T = C$$
 for equilibrium  
180 k = 35.7a  
 $a = 5.04$  in.

#### **Computing the Internal Moment Arm and Nominal Moment Capacity**

$$d - \frac{a}{2} = 21 \text{ in.} - \frac{5.04 \text{ in.}}{2} = 18.48 \text{ in.}$$
  
 $M_n = (180 \text{ k}) (18.48 \text{ in.}) = 3326.4 \text{ in-k} = 277.2 \text{ ft-k}$ 

![](_page_68_Figure_11.jpeg)

FIGURE 2.12 Beam cross section for Example 2.8.

In Example 2.9, the nominal moment capacity of another beam is determined much as it was in Example 2.8. The only difference is that the cross section of the compression area  $(A_c)$  stressed at  $0.85f_c'$  is not rectangular. As a result, once this area is determined, we need to locate its center of gravity. The c.g. for the beam of Figure 2.13 is shown as being a distance  $\overline{y}$  from the top of the beam in Figure 2.14. The lever arm from C to T is equal to  $d - \overline{y}$  (which corresponds to d - a/2 in Example 2.8) and  $M_n$  equals  $A_s f_y (d - \overline{y})$ .

With this very simple procedure, values of  $M_n$  can be computed for tensilely reinforced beams of any cross section.

![](_page_69_Figure_2.jpeg)

FIGURE 2.13 Beam cross section for Example 2.9.

![](_page_69_Figure_4.jpeg)

FIGURE 2.14 Area under compression stress block for Example 2.9.

### Example 2.9

Calculate the nominal or theoretical ultimate moment strength of the beam section shown in Figure 2.13, if  $f_{\rm V}=60{,}000$  psi and  $f_{\rm C}'=3000$  psi. The 6-in.-wide ledges on top are needed for the support of precast concrete slabs.

#### SOLUTION

$$T = A_s f_y = (4.00 \text{ in.}^2) (60 \text{ k/in.}^2) = 240 \text{ k}$$
  
 $C = (0.85 f_c') \text{ (area of concrete } A_c \text{ stressed to } 0.85 f_c')$   
 $= 0.85 f_c' A_c$ 

![](_page_69_Picture_10.jpeg)

Finger piers for U.S. Coast Guard base, Boston, Massachusetts.

#### Equating T and C and Solving for $A_c$

$$A_c = \frac{T}{0.85f_c'} = \frac{240 \text{ k}}{(0.85)(3 \text{ k/in.}^2)} = 94.12 \text{ in.}^2$$

The top  $94.12 \text{ in.}^2$  of the beam in Figure 2.14 is stressed in compression to  $0.85f_c'$ . This area can be shown to extend 9.23 in. down from the top of the beam. Its c.g. is located by taking moments at the top of the beam as follows:

$$\overline{y} = \frac{(36 \text{ in.}^2)(3 \text{ in.}) + (58.12 \text{ in.}^2)\left(6 \text{ in.} + \frac{3.23 \text{ in.}}{2}\right)}{94.12} = 5.85 \text{ in.}$$

$$d - \overline{y} = 21 \text{ in.} - 5.85 \text{ in.} = 15.15 \text{ in.}$$

$$M_n = (240 \text{ k})(15.15 \text{ in.}) = 3636 \text{ in-k} = \underline{303 \text{ ft-k}}$$

### 2.5 SI Example

In Example 2.10, the nominal moment strength of a beam is computed using SI units. Appendix B, Tables B.1 to B.9 provide information concerning various concrete and steel grades, as well as bar diameters, areas, and so on, all given in SI units.

#### Example 2.10

Determine the nominal moment strength of the beam shown in Figure 2.15 if  $f_c'=28\,\mathrm{MPa}$  and  $f_v=420\,\mathrm{MPa}$ .

#### SOLUTION

$$T = C$$

$$A_s f_y = 0.85 f_c' ab$$

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{(1530 \text{ mm}^2) (420 \text{ MPa})}{(0.85) (28 \text{ MPa}) (300 \text{ mm})} = 90 \text{ mm}$$

$$M_n = T \left( d - \frac{a}{2} \right) = C \left( d - \frac{a}{2} \right) = A_s f_y \left( d - \frac{a}{2} \right)$$

$$= (1530 \text{ mm}^2) (420 \text{ MPa}) \left( 430 \text{ mm} - \frac{90 \text{ mm}}{2} \right)$$

$$= 2.474 \times 10^8 \text{ N·mm} = \underline{247.4 \text{ kN·m}}$$

![](_page_70_Figure_12.jpeg)

 $(A_s = 1530 \text{ mm}^2 \text{ from Appendix B, Table B.4})$ 

**FIGURE 2.15** Beam cross section for Example 2.10.

#### 2.6 **Computer Examples**

On the John Wiley website for this textbook, several spreadsheets have been provided for the student to use in assisting in the solution of problems. They are categorized by chapter. Note that most of the spreadsheets have multiple worksheets indicated by tabs at the bottom. The three worksheets available for Chapter 2 include (1) calculation of cracking moment, (2) stresses in singly reinforced rectangular beams, and (3) nominal strength of singly reinforced rectangular beams.

#### Example 2.11

Repeat Example 2.1 using the spreadsheet provided for Chapter 2.

#### SOLUTION

Open the Chapter 2 spreadsheet and select the worksheet called Cracking Moment. Input only the cells highlighted in yellow (only in the Excel spreadsheets, not in the printed example), the first six values below.

| $f_{c}^{\prime}$ | =                           | 4000    | psi              |
|------------------|-----------------------------|---------|------------------|
| Μ                | =                           | 25      | ft-k             |
| b                | =                           | 12      | in.              |
| h                | =                           | 18      | in.              |
| $\gamma_c$       | =                           | 145     | pcf              |
| λ                | =                           | 1.00    |                  |
| $I_g$            | $= bh^3/12 =$               | 5832    | in. <sup>4</sup> |
| $f_r$            | $= 7.5\lambda SQRT(f_c') =$ | 474     | psi              |
| f                | =                           | 463     | psi              |
| $M_{cr}$         | =                           | 307,373 | in-lb            |
| $M_{cr}$         | =                           | 25.6    | ft-k             |
|                  |                             |         |                  |

The last five values are the same as calculated in Example 2.1.

#### Example 2.12

Repeat Example 2.3 using the spreadsheet provided for Chapter 2.

#### SOLUTION

Open the Chapter 2 spreadsheet and select the worksheet called Elastic Stresses. Input only the cells highlighted in yellow, the first seven values below.

| b               | = | 12 | in.              |
|-----------------|---|----|------------------|
| d               | = | 17 | in.              |
| n               | = | 9  |                  |
| $A_{\varsigma}$ | = | 3  | in. <sup>2</sup> |

| M =                 | 70        | ft-k             |
|---------------------|-----------|------------------|
| $f_{\text{C}}' =$   | 3000      | psi              |
| $\gamma_c =$        | 145       | pcf              |
| $E_c =$             | 3,155,924 | psi              |
| n =                 | 9.19      |                  |
| $n\rho =$           | 0.132     |                  |
| X =                 | 6.78      | in.              |
| $I_{cr} =$          | 4067      | in. <sup>4</sup> |
| $f_c = Mx/I =$      | 1401      | psi              |
| $f_s = nM(d-x)/I =$ | 18,996    | psi              |
|                     |           |                  |

The last four values are the same (within a small roundoff) as calculated in Example 2.2.

#### Example 2.13

Repeat Example 2.8 using the spreadsheet provided for Chapter 2.

#### SOLUTION

Open the Chapter 2 spreadsheet, and select the worksheet called Nominal Moment Strength. Input only the cells highlighted in yellow, the first five values below.

| $f_{\mathcal{C}}'$ | = | 3000   | psi              |
|--------------------|---|--------|------------------|
| b                  | = | 14     | in.              |
| d                  | = | 21     | in.              |
| $A_{s}$            | = | 3      | in. <sup>2</sup> |
| $f_y$              | = | 60     | ksi              |
| а                  | = | 5.04   |                  |
| $M_n$              | = | 3326.2 | in-k             |
|                    | = | 277.2  | ft-k             |
|                    |   |        |                  |

The third worksheet, called Nominal Moment Strength, can be used to easily work Example 2.8. In this case, enter the first five values, and the results are the same as in the example. The process can be reversed if "goal seek" is used. Suppose that you would like to know how much reinforcing steel,  $A_{\rm s}$ , is needed to resist a moment,  $M_{\rm n}$ , of 320 ft-k

for the beam shown in Example 2.8. Highlight the cell where  $M_n$  is calculated in ft-k (cell C11), then go to "Data" at the top of the Excel window and select "What-If Analysis" and "Goal seek ..." The Goal Seek window shown will open. In "Set cell," C11 appears because it was highlighted when you selected "Goal seek ...". In "To value," type 320 because that is the moment you are seeking. Finally, for "By changing cell," insert C7 because the area of reinforcing steel is what you want to

![](_page_72_Figure_11.jpeg)

vary to produce a moment of 320 ft-k. Click OK, and the value of  $A_{\rm s}$  will change to 3.55. This means that a steel area of 3.55 in.<sup>2</sup> is required to produce a moment capacity  $M_n$  of 320 ft-k. The Goal Seek feature can be used in a similar manner for most of the spreadsheets provided in this text.

#### **PROBLEMS**

#### **Cracking Moments**

For Problems 2.1 to 2.5, determine the cracking moments for the sections shown if  $f'_c = 4000$  psi and  $f_r = 7.5\sqrt{f'_c}$ 

**Problem 2.1** (*Ans.* 34.8 ft-k)

![](_page_73_Picture_6.jpeg)

Problem 2.2

![](_page_73_Figure_8.jpeg)

**Problem 2.3** (*Ans.* 31.6 ft-k)

![](_page_73_Figure_10.jpeg)

![](_page_73_Figure_11.jpeg)

**Problem 2.5** (Ans. 85.3 ft-k)

![](_page_73_Figure_13.jpeg)

For Problems 2.6 and 2.7, calculate the uniform load (in addition to the beam weight) that will cause the sections to begin to crack if they are used for 28-ft simple spans.  $f_c'=4000$  psi,  $f_r=7.5\sqrt{f_c'}$ , and reinforced concrete weight = 150 lb/ft<sup>3</sup>.

Problem 2.6

![](_page_74_Picture_4.jpeg)

**Problem 2.7** (Ans. 0.343 k/ft)

![](_page_74_Picture_6.jpeg)

#### **Transformed-Area Method**

For Problems 2.8 to 2.14, assume the sections have cracked and use the transformed-area method to compute their flexural stresses for the loads or moments given.

Problem 2.8

![](_page_74_Figure_10.jpeg)

**Problem 2.9** Repeat Problem 2.8 if four #6 bars are used. (Ans.  $f_c = 1356$  psi,  $f_s = 26,494$  psi)

Problem 2.10

![](_page_74_Picture_13.jpeg)

**Problem 2.11** (Ans.  $f_c = 1258$  psi,  $f_s = 14,037$  psi in bottom layer,  $f_s = 12,889$  psi at steel centroid)

![](_page_74_Figure_15.jpeg)

#### Problem 2.12

![](_page_75_Figure_2.jpeg)

**Problem 2.13** (Ans.  $f_c = 2369$  psi,  $f_s = 32,574$  psi at the steel centroid, 36,255 psi in the bottom layer)

![](_page_75_Figure_4.jpeg)

#### Problem 2.14

![](_page_75_Figure_6.jpeg)

**Problem 2.15** Using the transformed-area method, compute the resisting moment of the beam of Problem 2.10 if  $f_s = 24,000$  psi and  $f_c = 1800$  psi. (*Ans.* 258.8 ft-k)

**Problem 2.16** Compute the resisting moment of the beam of Problem 2.13 if eight #10 bars are used and n=10,  $f_s=20{,}000$  psi, and  $f_c=1125$  psi. Use the transformedarea method.

**Problem 2.17** Using transformed area, what allowable uniform load can this beam support in addition to its own weight for a 28-ft simple span? Concrete weight = 150 lb/ft<sup>3</sup>,  $f_s = 24,000$  psi, and  $f_c = 1800$  psi. (*Ans.* 2.757 k/ft)

![](_page_75_Figure_10.jpeg)

For Problems 2.18 to 2.21, determine the flexural stresses in these members using the transformed-area method.

#### Problem 2.18

![](_page_76_Figure_3.jpeg)

**Problem 2.19** (Ans.  $f_c = 1374 \text{ psi}, f_s = 32,611 \text{ psi}$  at the steel centroid)

![](_page_76_Figure_5.jpeg)

Problem 2.20

![](_page_76_Figure_7.jpeg)

**Problem 2.21** (Ans.  $f_c = 1406 \text{ psi}, f_s' = 16,886 \text{ psi}, f_s = 36,217 \text{ psi})$ 

![](_page_76_Figure_9.jpeg)

**Problem 2.22** Compute the allowable resisting moment of the section shown using transformed area if allowable stresses are *fc* = 1800 psi, *fs* = *f <sup>s</sup>* = 24,000 psi, and *n* = 8.

![](_page_77_Figure_3.jpeg)

For Problems 2.23 to 2.25, using the transformed-area method, determine the allowable resisting moments of the sections shown.

#### **Problem 2.23** (*Ans*. 140.18 ft-k)

![](_page_77_Figure_6.jpeg)

#### Problem 2.24

![](_page_78_Figure_2.jpeg)

#### **Problem 2.25** (Ans. 124.4 ft-k)

![](_page_78_Figure_4.jpeg)

#### **Nominal Strength Analysis**

For Problems 2.26 to 2.29, determine the nominal or theoretical moment capacity  $M_n$  of each beam if  $f_y = 60,000$  psi and  $f'_c = 4000$  psi.

Problem 2.26

![](_page_78_Figure_8.jpeg)

**Problem 2.27** (Ans. 688.2 ft-k)

![](_page_78_Figure_10.jpeg)

**Problem 2.28**

![](_page_79_Figure_2.jpeg)

**Problem 2.29** (*Ans*. 845.5 ft-k)

![](_page_79_Picture_4.jpeg)

For Problems 2.30 to 2.34, determine the nominal moment capacity *Mn* for each of the rectangular beams.

| Problem<br>No. | b (in.) | d (in.) | Bars  | f<br>c (ksi) | fy<br>(ksi) | Ans.       |
|----------------|---------|---------|-------|--------------|-------------|------------|
| 2.30           | 14      | 21      | 3 #9  | 4.0          | 60          | —          |
| 2.31           | 16      | 27      | 8 #9  | 4.0          | 60          | 903.6 ft-k |
| 2.32           | 14      | 20.5    | 4 #10 | 5.0          | 60          | —          |
| 2.33           | 21      | 28      | 4 #10 | 5.0          | 75          | 818.3 ft-k |
| 2.34           | 22      | 36      | 6 #11 | 3.0          | 60          | —          |

For Problems 2.35 to 2.39, determine *Mn* if *fy* = 60,000 psi and *f <sup>c</sup>* = 4000 psi.

**Problem 2.35** (*Ans*. 704 ft-k)

![](_page_79_Picture_9.jpeg)

**Problem 2.36**

![](_page_79_Figure_11.jpeg)

**Problem 2.37** Repeat Problem 2.35 if four #11 bars are used. (*Ans*. 865 ft-k)

**Problem 2.38** Compute *Mn* for the beam of Problem 2.36 if six #8 bars are used.

#### **Problem 2.39** (Ans. 763.3 ft-k)

![](_page_80_Figure_3.jpeg)

**Problem 2.40** Determine the nominal uniform load  $w_n$  (including beam weight) that will cause a bending moment equal to  $M_n$ .  $f_y = 60,000$  psi and  $f_c' = 4000$  psi.

![](_page_80_Figure_5.jpeg)

**Problem 2.41** Determine the nominal uniform load  $w_n$  (including beam weight) that will cause a bending moment equal to  $M_n$ .  $f_c^\prime = 3000 \text{ psi and } f_y = 60,000 \text{ psi. } (Ans. 6.77 \text{ k/ft})$ 

![](_page_80_Figure_7.jpeg)

#### **Problems in SI Units**

For Problems 2.42 to 2.44, determine the cracking moments for the sections shown if  $f_c'=28$  MPa and the modulus of rupture is  $f_r=0.7\sqrt{f_c'}$  with  $f_c'$  in MPa.

#### Problem 2.42

![](_page_81_Figure_5.jpeg)

**Problem 2.43** (*Ans.* 46.30 kN-m)

![](_page_81_Figure_7.jpeg)

#### Problem 2.44

![](_page_81_Figure_9.jpeg)

For Problems 2.45 to 2.47, compute the flexural stresses in the concrete and steel for the beams shown using the transformed-area method.

**Problem 2.45** (Ans.  $f'_c = 7.785$  MPa,  $f_s = 109.31$  MPa)

![](_page_81_Figure_12.jpeg)

#### Problem 2.46

![](_page_81_Figure_14.jpeg)

![](_page_81_Figure_15.jpeg)

**Problem 2.47** (Ans.  $f_c = 10.20 \text{ MPa}, f_s' = 103.10 \text{ MPa}, f_s = 188.56 \text{ MPa})$ 

![](_page_82_Figure_3.jpeg)

For Problems 2.48 to 2.55, compute  $M_n$  values.

| Problem<br>No. | b (mm) | d (mm) | Bars  | $f_c'$ (MPa) | f <sub>y</sub> (MPa) | Ans.       |
|----------------|--------|--------|-------|--------------|----------------------|------------|
| 2.48           | 300    | 600    | 3 #36 | 35           | 350                  | _          |
| 2.49           | 320    | 600    | 3 #36 | 28           | 350                  | 560.5 kN-m |
| 2.50           | 350    | 530    | 3 #25 | 24           | 420                  | _          |
| 2.51           | 370    | 530    | 3 #25 | 24           | 420                  | 313 kN-m   |

#### Problem 2.52

![](_page_82_Figure_7.jpeg)

**Problem 2.53** Repeat Problem 2.48 if four #36 bars are used. (Ans. 734 kN·m)

![](_page_83_Figure_2.jpeg)

**Problem 2.56** Repeat Problem 2.27 using Chapter 2 spreadsheets.

**Problem 2.57** Repeat Problem 2.28 using Chapter 2 spreadsheets. (*Ans*. 561.9 ft-k)

**Problem 2.58** Prepare a flowchart for the determination of *Mn* for a rectangular tensilely reinforced concrete beam.

