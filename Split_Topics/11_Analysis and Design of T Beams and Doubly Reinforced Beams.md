# Analysis and Design of T Beams and Doubly Reinforced Beams

#### 5.1 T Beams

Reinforced concrete floor systems normally consist of slabs and beams that are placed monolithically. As a result, the two parts act together to resist loads. In effect, the beams have extra widths at their tops, called *flanges*, and the resulting T-shaped beams are called *T beams*. The part of a T beam below the slab is referred to as the *web* or *stem*. (The beams may be L shaped if the stem is at the end of a slab.) The stirrups (described in Chapter 8) in the webs extend up into the slabs, as perhaps do bent-up bars, with the result that they further make the beams and slabs act together.

There is a problem involved in estimating how much of the slab acts as part of the beam. Should the flanges of a T beam be rather stocky and compact in cross section, bending stresses will be fairly uniformly distributed across the compression zone. If, however, the flanges are wide and thin, bending stresses will vary quite a bit across the flange due to shear deformations. The farther a particular part of the slab or flange is away from the stem, the smaller will be its bending stress.

Instead of considering a varying stress distribution across the full width of the flange, the ACI Code (8.12.2) calls for a smaller width with an assumed uniform stress distribution for design purposes. The objective is to have the same total compression force in the reduced width that actually occurs in the full width with its varying stresses.

The hatched area in Figure 5.1 shows the effective size of a T beam. For T beams with flanges on both sides of the web, the code states that the effective flange width may not exceed one-fourth of the beam span, and the overhanging width on each side may not exceed eight times the slab thickness or one-half the clear distance to the next web. An isolated T beam must have a flange thickness no less than one-half the web width, and its effective flange width may not be larger than four times the web width (ACI 8.12.4). If there is a flange on only one side of the web, the width of the overhanging flange cannot exceed one-twelfth the span,  $6h_f$ , or half the clear distance to the next web (ACI 8.12.3).

The analysis of T beams is quite similar to the analysis of rectangular beams in that the specifications relating to the strains in the reinforcing are identical. To repeat briefly, it is desirable to have  $\epsilon_t$  values  $\geq 0.005$ , and they may not be less than 0.004 unless the member is subjected to an axial load  $\geq 0.10f_c'A_g$ . You will learn that  $\epsilon_t$  values are almost always much larger than 0.005 in T beams because of their very large compression flanges. For such members, the values of c are normally very small, and calculated  $\epsilon_t$  values very large.

The neutral axis (N.A.) for T beams can fall either in the flange or in the stem, depending on the proportions of the slabs and stems. If it falls in the flange, and it almost always does for positive moments, the rectangular beam formulas apply, as can be seen in Figure 5.2(a). The concrete below the neutral axis is assumed to be cracked, and its shape has no effect on the flexure calculations (other than weight). The section above the neutral axis is rectangular. If the neutral axis is below the flange, however, as shown for the beam of Figure 5.2(b), the compression concrete above the neutral axis no longer consists of a single rectangle, and thus the normal rectangular beam expressions do not apply.

![](_page_132_Picture_1.jpeg)

FIGURE 5.1 Effective width of T beams.

![](_page_132_Picture_3.jpeg)

FIGURE 5.2 Neutral axis locations.

If the neutral axis is assumed to fall within the flange, the value of a can be computed as it was for rectangular beams:

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{\rho f_y d}{0.85 f_c'}$$

The distance to the neutral axis, c, equals  $a/\beta_1$ . If the computed value of a is equal to or less than the flange thickness, the section for all practical purposes can be assumed to be rectangular, even though the computed value of c is actually greater than the flange thickness.

A beam does not really have to look like a T beam to be one. This fact is shown by the beam cross sections shown in Figure 5.3. For these cases the compression concrete is T shaped, and the shape or size of the concrete on the tension side, which is assumed to be cracked, has no effect on the theoretical resisting moments. It is true, however, that the shapes, sizes, and weights of the tensile concrete do affect the deflections that occur (as is described in Chapter 6), and their dead weights affect the magnitudes of the moments to be resisted.

![](_page_133_Figure_2.jpeg)

**FIGURE 5.3** Various cross sections of T beams.

![](_page_133_Picture_4.jpeg)

Natural History Museum, Kensington, London, England.

#### **Analysis of T Beams** 5.2

The calculation of the design strengths of T beams is illustrated in Examples 5.1 and 5.2. In the first of these problems, the neutral axis falls in the flange, while for the second, it is in the web. The procedure used for both examples involves the following steps:

- 1. Check  $A_{s \text{ min}}$  as per ACI Section 10.5.1 using  $b_w$  as the web width.
- **2.** Compute  $T = A_s f_y$ .
- **3.** Determine the area of the concrete in compression  $(A_c)$  stressed to  $0.85f_c'$ .

$$C = T = 0.85 f_c' A_c$$

$$A_c = \frac{T}{0.85 f_c'}$$

- **4.** Calculate a, c, and  $\epsilon_r$ .
- **5.** Calculate  $\phi M_n$ .

For Example 5.1, where the neutral axis falls in the flange, it would be logical to apply the normal rectangular equations of Section 3.4 of this book, but the authors have used the couple method as a background for the solution of Example 5.2, where the neutral axis falls in the web. This same procedure can be used for determining the design strengths of tensilely reinforced concrete beams of any shape  $(\top, \Gamma, \Gamma)$  triangular, circular, etc.).

#### Example 5.1

Determine the design strength of the T beam shown in Figure 5.4, with  $f'_c = 4000$  psi and  $f_y = 60,000$  psi. The beam has a 30-ft span and is cast integrally with a floor slab that is 4 in. thick. The clear distance between webs is 50 in.

#### SOLUTION

#### **Check Effective Flange Width**

$$b \le 16h_f + b_w = 16(4 \text{ in.}) + 10 \text{ in.} = 74 \text{ in.}$$
  
 $b \le \text{ average clear distance to adjacent webs } + b_w = 50 \text{ in. } + 10 \text{ in.} = 60 \text{ in.} \leftarrow b \le \frac{\text{span}}{4} = \frac{30 \text{ ft}}{4} = 7.5 \text{ ft} = 90 \text{ in.}$ 

#### Checking A<sub>s min</sub>

$$A_{s \text{ min}} = \frac{3\sqrt{f_c}}{f_y} b_w d = \frac{(3\sqrt{4000} \text{ psi})}{60,000 \text{ psi}} (10 \text{ in.}) (24 \text{ in.}) = 0.76 \text{ in.}^2$$

$$\text{nor less than } \frac{200b_w d}{f_y} = \frac{(200) (10 \text{ in.}) (24 \text{ in.})}{60,000 \text{ psi}} = 0.80 \text{ in.}^2 \leftarrow$$

$$< A_s = 6.00 \text{ in.}^2 \quad \underline{OK}$$

#### Computing T

$$T = A_{\rm s} f_y = (6.00 \ {\rm in.^2}) (60 \ {\rm ksi}) = 360 \ {\rm k}$$

![](_page_134_Figure_12.jpeg)

**FIGURE 5.4** Beam cross section for Example 5.1.

#### Determining A.

$$A_c = \frac{T}{0.85f_c'} = \frac{360 \text{ k}}{(0.85)(4 \text{ ksi})} = 105.88 \text{ in.}^2$$

< flange area = (60 in.) (4 in.) = 240 in.<sup>2</sup> ... Compression stress block, a, is in flange

#### Calculating a, c, and $\epsilon_{\star}$

$$a = \frac{105.88 \text{ in.}^2}{60 \text{ in.}} = 1.76 \text{ in.}$$

$$c = \frac{a}{\beta_1} = \frac{1.76 \text{ in.}}{0.85} = 2.07 \text{ in.}$$

$$\epsilon_t = \left(\frac{d-c}{c}\right) (0.003) = \left(\frac{24 \text{ in.} - 2.07 \text{ in.}}{2.07 \text{ in.}}\right) (0.003)$$

$$= 0.0318 > 0.005 \qquad \qquad \therefore \text{ Section is ductile and } \phi = 0.90$$

#### Calculating $\phi M_n$

Obviously, the stress block is entirely within the flange, and the rectangular formulas apply. However, using the couple method as follows:

Lever arm = 
$$z = d - \frac{a}{2} = 24$$
 in.  $-\frac{1.76 \text{ in.}}{2} = 23.12$  in. 
$$\phi M_n = \phi Tz = (0.90) (360 \text{ k}) (23.12 \text{ in.})$$
$$= 7490.9 \text{ in-k} = \underline{624.2 \text{ ft-k}}$$

#### Example 5.2

Compute the design strength for the T beam shown in Figure 5.5, in which  $f_c' = 4000$  psi and  $f_{v} = 60,000 \text{ psi.}$ 

#### SOLUTION

#### Checking A<sub>s min</sub>

$$A_{\text{s min}} = \frac{3\sqrt{4000 \text{ psi}}}{60,000 \text{ psi}} (14 \text{ in.}) (30 \text{ in.}) = 1.33 \text{ in.}^2$$

nor less than  $\frac{(200) (14 \text{ in.}) (30 \text{ in.})}{60,000 \text{ psi}} = 1.40 \text{ in.}^2 \leftarrow$ 
 $< A_{\text{s}} = 10.12 \text{ in.}^2 \quad \underline{OK}$ 

#### Computing T

$$T = A_s f_v = (10.12 \text{ in.}^2) (60 \text{ ksi}) = 607.2 \text{ k}$$

#### Determining A<sub>c</sub> and Its Center of Gravity

$$A_c = \frac{T}{0.85f'_c} = \frac{607.2 \text{ k}}{(0.85)(4 \text{ ksi})} = 178.59 \text{ in.}^2$$
  
> flange area = (30 in.) (4 in.) = 120 in.<sup>2</sup>

Obviously, the stress block must extend below the flange to provide the necessary compression area,  $178.6 \text{ in.}^2 - 120 \text{ in.}^2 = 58.6 \text{ in.}^2$ , as shown in Figure 5.6.

![](_page_136_Figure_2.jpeg)

**FIGURE 5.5** Beam cross section for Example 5.2.

Computing the Distance  $\overline{y}$  from the Top of the Flange to the Center of Gravity of  $A_c$ 

$$\overline{y} = \frac{(120 \text{ in.}^2)(2 \text{ in.}) + (58.6 \text{ in.}^2)\left(4 \text{ in.} + \frac{4.19 \text{ in.}}{2}\right)}{178.6 \text{ in.}^2} = 3.34 \text{ in.}$$

The Lever Arm Distance from T to C = 30.00 in. -3.34 in. = 26.66 in. = z

Calculating a, c, and  $\epsilon_t$ 

$$a = 4 \text{ in.} + 4.19 \text{ in.} = 8.19 \text{ in.}$$

$$c = \frac{a}{\beta_1} = \frac{8.19 \text{ in.}}{0.85} = 9.64 \text{ in.}$$

$$\epsilon_t = \frac{d-c}{c}(0.003) = \left(\frac{30 \text{ in.} - 9.64 \text{ in.}}{9.64 \text{ in.}}\right)(0.003) = 0.00634$$

$$> 0.005 \qquad \qquad \therefore \text{ Section is ductile and } \phi = 0.90$$

#### Calculating $\phi M_n$

$$\phi M_n = \phi Tz =$$
 (0.90) (607.2 k) (26.66 in.) = 14,569 in-k  
= 1214 ft-k

![](_page_136_Figure_11.jpeg)

FIGURE 5.6 Area of concrete in compression.

### **5.3 Another Method for Analyzing T Beams**

The preceding section presented a very important method of analyzing reinforced concrete beams. It is a general method that is applicable to tensilely reinforced beams of any cross section, including T beams. T beams are so very common, however, that many designers prefer another method that is specifically designed for T beams.

First, the value of *a* is determined as previously described in this chapter. Should it be less than the flange thickness, *hf* , we will have a rectangular beam and the rectangular beam formulas will apply. Should it be greater than the flange thickness, *hf* (as was the case for Example 5.2), the special method to be described here will be very useful.

The beam is divided into a set of rectangular parts consisting of the overhanging parts of the flange and the compression part of the web (see Figure 5.7).

The total compression, *Cw*, in the web rectangle, and the total compression in the overhanging flange, *Cf* , are computed:

$$C_w = 0.85 f'_c a b_w$$
  
$$C_f = 0.85 f'_c (b - b_w) (h_f)$$

Then the nominal moment, *Mn* , is determined by multiplying *Cw* and *Cf* by their respective lever arms from their centroids to the centroid of the steel:

$$M_n = C_w \left( d - \frac{a}{2} \right) + C_f \left( d - \frac{h_f}{2} \right)$$

This procedure is illustrated in Example 5.3. Although it seems to offer little advantage in computing *Mn* , we will learn that it does simplify the design of T beams when *a* > *hf* because it permits a direct solution of an otherwise trial-and-error problem.

![](_page_137_Figure_11.jpeg)

**FI GU RE 5.7** Separation of T beam into rectangular parts.

#### Example 5.3

Repeat Example 5.2 using the value of *a* (8.19 in.) previously obtained and the alternate formulas just developed. Reference is made to Figure 5.8, the dimensions of which were taken from Figure 5.5.

#### SOLUTION

(Noting that  $a > h_f$ )

Computing  $C_w$  and  $C_f$ 

$$C_w = (0.85) (4 \text{ ksi}) (8.19 \text{ in.}) (14 \text{ in.}) = 389.8 \text{ k}$$
  
 $C_f = (0.85) (4 \text{ ksi}) (30 \text{ in.} - 14 \text{ in.}) (4 \text{ in.}) = 217.6 \text{ k}$ 

Computing c and  $\epsilon_{+}$ 

$$c = \frac{a}{\beta_1} = \frac{8.19 \text{ in.}}{0.85} = 9.64 \text{ in.}$$

$$\epsilon_t = \left(\frac{d-c}{c}\right) (0.003) = \left(\frac{30 \text{ in.} - 9.64 \text{ in.}}{9.64 \text{ in.}}\right) (0.003) = 0.00634$$

$$> 0.005 \qquad \qquad \therefore \text{ Section is ductile and } \phi = 0.90$$

Calculating  $M_n$  and  $\phi M_n$ 

$$\begin{split} M_n &= C_w \left( d - \frac{a}{2} \right) + C_f \left( d - \frac{h_f}{2} \right) \\ &= (389.8 \text{ k}) \left( 30 \text{ in.} - \frac{8.19 \text{ in.}}{2} \right) + (217.6 \text{ k}) \left( 30 \text{ in.} - \frac{4 \text{ in.}}{2} \right) \\ &= 16,190 \text{ in-k} = 1349 \text{ ft-k} \\ \phi M_n &= (0.90) \left( 1349 \text{ ft-k} \right) = \underline{1214 \text{ ft-k}} \end{split}$$

![](_page_138_Figure_12.jpeg)

**FIGURE 5.8** Concrete compression areas for Example 5.3.

#### **Design of T Beams** 5.4

For the design of T beams, the flange has normally already been selected in the slab design, as it is for the slab. The size of the web is normally not selected on the basis of moment requirements but probably is given an area based on shear requirements; that is, a sufficient area is used so as to provide a certain minimum shear capacity, as will be described in Chapter 8. It is also possible that the width of the web may be selected on the basis of the width estimated to be needed to put in the reinforcing bars. Sizes may also have been preselected, as previously described in Section 4.5, to simplify formwork for architectural requirements or for deflection reasons. For the examples that follow (5.4 and 5.5), the values of  $h_f$ , d, and  $b_w$  are given.

The flanges of most T beams are usually so large that the neutral axis probably falls within the flange, and thus the rectangular beam formulas apply. Should the neutral axis fall within the web, a trial-and-error process is often used for the design. In this process, a lever arm from the center of gravity of the compression block to the center of gravity of the steel is estimated to equal the larger of 0.9d or  $d - (h_f/2)$ , and from this value, called z, a trial steel area is calculated  $(A_s = M_n/f_v z)$ . Then by the process used in Example 5.2, the value of the estimated lever arm is checked. If there is much difference, the estimated value of z is revised and a new  $A_c$  determined. This process is continued until the change in  $A_c$  is quite small. T beams are designed in Examples 5.4 and 5.5 by this process.

Often a T beam is part of a continuous beam that spans over interior supports, such as columns. The bending moment over the support is negative, so the flange is in tension. Also, the magnitude of the negative moment is usually larger than that of the positive moment near midspan. This situation will control the design of the T beam because the depth and web width will be determined for this case. Then, when the beam is designed for positive moment at midspan, the width and depth are already known. See Section 5.5 for other details on T beams with negative moments.

Example 5.6 presents a more direct approach for the case where  $a > h_f$ . This is the case where the beam is assumed to be divided into its rectangular parts.

#### Example 5.4

Design a T beam for the floor system shown in Figure 5.9, for which  $b_w$  and d are given.  $M_D = 80 \text{ ft-k}, M_L = 100 \text{ ft-k}, f_C' = 4000 \text{ psi}, f_V = 60,000 \text{ psi}, \text{ and simple span} = 20 \text{ ft.}$ 

#### SOLUTION

#### **Effective Flange Width**

- (a)  $\frac{1}{4}$  ft × 20 ft = 5 ft = 60 in.
- **(b)** 12 in. + (2) (8) (4 in.) = 76 in.
- (c) 10 ft = 120 in.

![](_page_139_Figure_14.jpeg)

FIGURE 5.9 Cross section of T-beam floor system for Example 5.4.

#### Computing Moments Assuming $\phi = 0.90$

$$M_u = (1.2) (80 \text{ ft-k}) + (1.6) (100 \text{ ft-k}) = 256 \text{ ft-k}$$
  
 $M_n = \frac{M_u}{\phi} = \frac{256 \text{ ft-k}}{0.90} = 284.4 \text{ ft-k}$ 

Assuming a Lever Arm z Equal to the Larger of 0.9d or  $d - (h_f/2)$ 

$$z = (0.9) (18 \text{ in.}) = \underline{16.20 \text{ in.}}$$
  
 $z = 18 \text{ in.} - \frac{4 \text{ in.}}{2} = 16.00 \text{ in.}$ 

**Trial Steel Area** 

$$A_s f_y z = M_n$$
  
 $A_s = \frac{(12 \text{ in/ft}) (284.4 \text{ ft-k})}{(60 \text{ ksi}) (16.20 \text{ in.})} = 3.51 \text{ in.}^2$ 

Computing Values of a and z

$$0.85f_c'A_c = A_s f_y$$

$$(0.85) (4 \text{ ksi}) (A_c \text{ in.}^2) = (3.51 \text{ in.}^2) (60 \text{ ksi})$$

$$A_c = 61.9 \text{ in.}^2 < (4 \text{ in.}) (60 \text{ in.}) = 240 \text{ in.}^2$$

$$a = \frac{61.9 \text{ in.}^2}{60 \text{ in.}} = 1.03 \text{ in.}$$

$$z = d - \frac{a}{2} = 18 \text{ in.} - \frac{1.03 \text{ in.}}{2} = 17.48 \text{ in.}$$

Calculating A<sub>s</sub> with This Revised z

$$A_s = \frac{\text{(12 in/ft) (284.4 ft-k)}}{\text{(60 ksi) (17.48 in.)}} = 3.25 \text{ in.}^2$$

Computing Values of a and z

$$A_c = \frac{(3.25 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (4 \text{ ksi})} = 57.4 \text{ in.}^2$$

$$a = \frac{57.4 \text{ in.}^2}{60 \text{ in.}} = 0.96 \text{ in.}$$

$$z = 18 \text{ in.} - \frac{0.96 \text{ in.}}{2} = 17.52 \text{ in.}$$

Calculating  $A_s$  with This Revised z

$$A_{\rm s} = \frac{(12 \text{ in/ft}) (284.4 \text{ ft-k})}{(60 \text{ ksi}) (17.52 \text{ in.})} = 3.25 \text{ in.}^2$$
 OK, close enough to previous value

**Checking Minimum Reinforcing** 

$$A_{\text{s min}} = \frac{3\sqrt{f_c'}}{f_v} b_w d = \frac{3\sqrt{4000 \text{ psi}}}{60,000 \text{ psi}} (12 \text{ in.}) (18 \text{ in.}) = 0.68 \text{ in.}^2$$

but not less than

$$A_{\text{s min}} = \frac{200b_w d}{f_y} = \frac{(200)(12 \text{ in.})(18 \text{ in.})}{60,000 \text{ psi}} = 0.72 \text{ in.}^2 < 3.25 \text{ in.}^2$$

or  $\rho_{\min}$  (from Appendix A, Table A.7) = 0.0033

$$A_{\text{s min}} = (0.0033) (12 \text{ in.}) (18 \text{ in.}) = 0.71 \text{ in.}^2 < 3.25 \text{ in.}^2$$
 OK

Computing c,  $\epsilon_t$ , and  $\phi$ 

$$c = \frac{a}{\beta_1} = \frac{0.96 \text{ in.}}{0.85} = 1.13 \text{ in.}$$

$$\epsilon_t = \left(\frac{d-c}{c}\right) (0.003) = \left(\frac{18 \text{ in.} - 1.13 \text{ in.}}{1.13 \text{ in.}}\right) (0.003)$$

$$= 0.045 > 0.005$$

$$\therefore \phi = 0.90 \text{ as assumed}$$

$$A_{\rm s \ reqd} = 3.25 \ {\rm in.}^2$$

#### Example 5.5

Design a T beam for the floor system shown in Figure 5.10, for which  $b_{\rm w}$  and d are given.  $M_D=$  200 ft-k,  $M_L=$  425 ft-k,  $f_c^\prime=$  3000 psi,  $f_\gamma=$  60,000 psi, and simple span = 18 ft.

#### SOLUTION

#### **Effective Flange Width**

- (a)  $\frac{1}{4}$  ft × 18 ft = 4 ft 6 in. =  $\underline{54}$  in. (b) 15 in. + (2) (8) (3 in.) = 63 in.
- (c) 6 ft = 72 in.

#### Moments Assuming $\phi = 0.90$

$$M_u = (1.2)(200 \text{ ft-k}) + (1.6)(425 \text{ ft-k}) = 920 \text{ ft-k}$$
  
 $M_n = \frac{M_u}{0.90} = \frac{920 \text{ ft-k}}{0.90} = 1022 \text{ ft-k}$ 

#### Assuming a Lever Arm z

(Note that the compression area in the slab is very wide, and thus its required depth is very small.)

$$z = (0.90) (24 \text{ in.}) = 21.6 \text{ in.}$$
  
 $z = 24 \text{ in.} - \frac{3 \text{ in.}}{2} = \underline{22.5 \text{ in.}}$ 

![](_page_141_Figure_19.jpeg)

FIGURE 5.10 Cross section for T-beam floor system of Example 5.5.

**Trial Steel Area** 

$$A_s = \frac{(12 \text{ in/ft})(1022 \text{ ft-k})}{(60 \text{ ksi})(22.5 \text{ in.})} = 9.08 \text{ in.}^2$$

Checking Values of a and z

$$A_c = \frac{(60 \text{ ksi}) (9.08 \text{ in.}^2)}{(0.85) (3 \text{ ksi})} = 213.6 \text{ in.}^2$$

The stress block extends down into the web, as shown in Figure 5.11.

Computing the Distance  $\overline{y}$  from the Top of the Flange to the Center of Gravity of  $A_c$ 

$$\overline{y} = \frac{(162 \text{ in.}^2)(1.5 \text{ in.}) + (51.6 \text{ in.}^2)\left(3 \text{ in.} + \frac{3.44 \text{ in.}}{2}\right)}{213.6 \text{ in.}^2} = 2.28 \text{ in.}$$

$$z = 24 \text{ in.} - 2.28 \text{ in.} = 21.72 \text{ in.}$$

$$A_s = \frac{(12 \text{ in/ft})(1022 \text{ ft-k})}{(60 \text{ ksi})(21.72 \text{ in.})} = 9.41 \text{ in.}^2$$

The steel area required (9.41 in.<sup>2</sup>) could be refined a little by repeating the design, but space is not used to do this. (If this is done,  $A_s = 9.51$  in.<sup>2</sup>.)

#### **Checking Minimum Reinforcing**

 $\rho_{\min}$  (from Appendix A, Table A.7) = 0.00333

or

$$A_{s \text{ min}} = (0.00333) (15 \text{ in.}) (24 \text{ in.}) = 1.20 \text{ in.}^2 < 9.51 \text{ in.}^2$$

#### Checking Values of $\epsilon_t$ and $\phi$

$$a=3 \text{ in.} + 3.44 \text{ in.} = 6.44 \text{ in.}$$

$$c=\frac{a}{\beta_1}=\frac{6.44 \text{ in.}}{0.85}=7.58 \text{ in.}$$

$$\epsilon_t=\left(\frac{d-c}{c}\right)(0.003)=\left(\frac{24 \text{ in.} -7.58 \text{ in.}}{7.58 \text{ in.}}\right)(0.003)$$

$$=0.00650>0.005$$

$$\therefore \phi=0.90 \text{ as assumed}$$

If the calculations for  $\epsilon_t$  and  $\phi$  are repeated using the more refined values of  $A_s=9.51$  in.<sup>2</sup>, then a=7.12 in.,  $\epsilon_t=0.0056$ , and  $\phi=0.90$ .

![](_page_142_Figure_17.jpeg)

**FIGURE 5.11** Concrete compression area for Example 5.5.

Our procedure for designing T beams has been to assume a value of z, compute a trial steel area of  $A_s$ , determine a for that steel area assuming a rectangular section, and so on. Should  $a > h_f$ , we will have a real T beam. A trial-and-error process was used for such a beam in Example 5.5. It is easily possible, however, to determine A<sub>s</sub> directly using the method of Section 5.3, where the member was broken down into its rectangular components. For this discussion, reference is made to Figure 5.7.

The compression force provided by the overhanging flange rectangles must be balanced by the tensile force in part of the tensile steel,  $A_{sf}$ , while the compression force in the web is balanced by the tensile force in the remaining tensile steel,  $A_{sw}$ .

For the overhanging flange, we have

$$0.85f_c'(b - b_w)(h_f) = A_{sf}f_v$$

from which the required area of steel,  $A_{sf}$ , equals

$$A_{sf} = \frac{0.85f_c'(b - b_w)h_f}{f_v}$$

The design strength of these overhanging flanges is

$$M_{uf} = \phi A_{sf} f_y \left( d - \frac{h_f}{2} \right)$$

The remaining moment to be resisted by the web of the T beam and the steel required to balance that value are determined next.

$$M_{uw} = M_u - M_{uf}$$

The steel required to balance the moment in the rectangular web is obtained by the usual rectangular beam expression. The value  $M_{\mu\nu}/\phi b_w d^2$  is computed, and  $\rho_w$  is determined from the appropriate Appendix table or the expression for  $\rho_w$  previously given in Section 3.4 of this book. Think of  $\rho_w$  as the reinforcement ratio for the beam shown in Figure 5.7(b). Then

$$A_{sw} = \rho_w b_w d$$
$$A_s = A_{sf} + A_{sw}$$

#### Example 5.6

Rework Example 5.5 using the rectangular component method just described.

#### SOLUTION

First assume  $a \le h_f$  (which is very often the case). Then the design would proceed like that of a rectangular beam with a width equal to the effective width of the T-beam flange.

$$\frac{M_u}{\phi b d^2} = \frac{920 \text{ ft-k } (12,000 \text{ in-lb/ft-k})}{(0.9) (54 \text{ in.}) (24 \text{ in.})^2} = 394.4 \text{ psi}$$

 $\rho = 0.0072$  (from Appendix A, Table A.12)

$$a = \frac{\rho f_y d}{0.85 f_c'} = \frac{0.0072(60 \text{ ksi})(24 \text{ in.})}{(0.85)(3 \text{ ksi})} = 4.06 \text{ in.} > h_f = 3 \text{ in.}$$

The beam acts like a T beam, not a rectangular beam, and the values for  $\rho$  and a above are not correct. If the value of a had been  $\leq h_f$ , the value of  $A_s$  would have been simply  $\rho bd = 0.0072(54 \text{ in.}) (24 \text{ in.}) = 9.33 \text{ in.}^2$ . Now break the beam up into two parts (Figure 5.7) and design it as a T beam.

Assuming  $\phi = 0.90$ 

$$A_{sf} = \frac{(0.85) (3 \text{ ksi}) (54 \text{ in.} - 15 \text{ in.}) (3 \text{ in.})}{60 \text{ ksi}} = 4.97 \text{ in.}^2$$

$$M_{uf} = (0.9) (4.97 \text{ in.}^2) (60 \text{ ksi}) \left(24 \text{ in.} - \frac{3}{2} \text{ in.}\right) = 6039 \text{ in-k} = 503 \text{ ft-k}$$

$$M_{uw} = 920 \text{ ft-k} - 503 \text{ ft-k} = 417 \text{ ft-k}$$

Designing a Rectangular Beam with  $b_w = 15$  in. and d = 24 in. to Resist 417 ft-k

$$\frac{M_{uw}}{\phi b_w d^2} = \frac{(12 \text{ in/ft}) (417 \text{ ft-k}) (1000 \text{ lb/k})}{(0.9) (15 \text{ in.}) (24 \text{ in.})^2} = 643.5 \text{ psi}$$

$$\rho_w = 0.0126 \text{ (from Appendix A, Table A.12)}$$

$$A_{sw} = (0.0126) (15 \text{ in.}) (24 \text{ in.}) = 4.54 \text{ in.}^2$$

$$A_s = 4.97 \text{ in.}^2 + 4.54 \text{ in.}^2 = \underline{9.51 \text{ in.}^2}$$

### 5.5 Design of T Beams for Negative Moments

When T beams are resisting negative moments, their flanges will be in tension and the bottom of their stems will be in compression, as shown in Figure 5.12. Obviously, for such situations, the rectangular beam design formulas will be used. Section 10.6.6 of the ACI Code requires that part of the flexural steel in the top of the beam in the negative-moment region be distributed over the effective width of the flange or over a width equal to one-tenth of the beam span, whichever is smaller. Should the effective width be greater than one-tenth of the span length, the code requires that some additional longitudinal steel be placed in the outer portions of the flange. The intention of this part of the code is to minimize the sizes of the flexural cracks that will occur in the top surface of the flange perpendicular to the stem of a T beam subject to negative moments.

In Section 3.8, it was stated that if a rectangular section had a very small amount of tensile reinforcing, its design-resisting moment,  $\phi M_n$ , might very well be less than its cracking moment. If this were the case, the beam might fail without warning when the first crack occurred. The same situation applies to T beams with a very small amount of tensile reinforcing.

When the flange of a T beam is in tension, the amount of tensile reinforcing needed to make its ultimate resisting moment equal to its cracking moment is about twice that of a rectangular section or that of a T section with its flange in compression. As a result, ACI

![](_page_144_Picture_11.jpeg)

**FIGURE 5.12** T beam with flange in tension and bottom (hatched) in compression (a rectangular beam).

![](_page_145_Picture_2.jpeg)

Reinforced concrete building in Calgary, Canada.

![](_page_145_Picture_4.jpeg)

New Comiskey Park, Chicago, Illinois.

Courtesy of EFCO Corp.

Section 10.5.1 states that the minimum amount of reinforcing required equals the larger of the two values that follow:

$$A_{s \text{ min}} = \frac{3\sqrt{f_c}}{f_y} b_w d$$
 (ACI Equation 10-3)

or

$$A_{s \min} = \frac{200b_w d}{f_y}$$

For statically determinate members with their flanges in tension,  $b_w$  in the above expression is to be replaced with either  $2b_w$  or the width of the flange, whichever is smaller.

### 5.6 L-Shaped Beams

The author assumes for this discussion that L beams (i.e., edge T beams with a flange on one side only) are not free to bend laterally. Thus they will bend about their horizontal axes and will be handled as symmetrical sections, exactly as with T beams.

For L beams, the effective width of the overhanging flange may not be larger than one-twelfth the span length of the beam, six times the slab thickness, or one-half the clear distance to the next web (ACI 8.12.3).

If an L beam is assumed to be free to deflect both vertically and horizontally, it will be necessary to analyze it as an unsymmetrical section with bending about both the horizontal and vertical axes. An excellent reference on this topic is given in a book by MacGregor.<sup>1</sup>

### 5.7 Compression Steel

The steel that is occasionally used on the compression sides of beams is called *compression steel*, and beams with both tensile and compressive steel are referred to as *doubly reinforced beams*. Compression steel is not normally required in sections designed by the strength method because use of the full compressive strength of the concrete decidedly decreases the need for such reinforcement, as compared to designs made with the working-stress design method.

Occasionally, however, space or aesthetic requirements limit beams to such small sizes that compression steel is needed in addition to tensile steel. To increase the moment capacity of a beam beyond that of a tensilely reinforced beam with the maximum percentage of steel [when  $(\epsilon_t = 0.005)$ ], it is necessary to introduce another resisting couple in the beam. This is done by adding steel in both the compression and tensile sides of the beam. Compressive steel increases not only the resisting moments of concrete sections but also the amount of curvature that a member can take before flexural failure. This means that the ductility of such sections will be appreciably increased. Though expensive, compression steel makes beams tough and ductile, enabling them to withstand large moments, deformations, and stress reversals such as might occur during earthquakes. As a result, many building codes for earthquake zones require that certain minimum amounts of compression steel be included in flexural members.

Compression steel is very effective in reducing long-term deflections due to shrinkage and plastic flow. In this regard you should note the effect of compression steel on the long-term deflection expression in Section 9.5.2.5 of the code (to be discussed in Chapter 6 of this text). Continuous compression bars are also helpful for positioning stirrups (by tying them to the compression bars) and keeping them in place during concrete placement and vibration.

<sup>&</sup>lt;sup>1</sup> Wight, J. K. and MacGregor, J. G., 2011, *Reinforced Concrete Mechanics and Design*, 6th ed. (Upper Saddle River, NJ: Pearson Prentice Hall), pp. 165–168.

Tests of doubly reinforced concrete beams have shown that even if the compression concrete crushes, the beam may very well not collapse if the compression steel is enclosed by stirrups. Once the compression concrete reaches its crushing strain, the concrete cover spalls or splits off the bars, much as in columns (see Chapter 9). If the compression bars are confined by closely spaced stirrups, the bars will not buckle until additional moment is applied. This additional moment cannot be considered in practice because beams are not practically useful after part of their concrete breaks off. (Would you like to use a building after some parts of the concrete beams have fallen on the floor?)

Section 7.11.1 of the ACI Code states that compression steel in beams must be enclosed by ties or stirrups or by welded wire fabric of equivalent area. In Section 7.10.5.1, the code states that the ties must be at least #3 in size for longitudinal bars #10 and smaller and at least #4 for larger longitudinal bars and bundled longitudinal bars. The ties may not be spaced farther apart than 16 bar diameters, 48 tie diameters, or the least dimension of the beam cross section (code 7.10.5.2).

For doubly reinforced beams, an initial assumption is made that the compression steel yields as well as the tensile steel. (The tensile steel is always assumed to yield because of the ductile requirements of the ACI Code.) If the strain at the extreme fiber of the compression concrete is assumed to equal 0.00300 and the compression steel,  $A_s$ , is located two-thirds of the distance from the neutral axis to the extreme concrete fiber, then the strain in the compression steel equals  $\frac{2}{3} \times 0.003 = 0.002$ . If this is greater than the strain in the steel at yield, as say  $50,000/(29 \times 10^6) = 0.00172$  for 50,000-psi steel, the steel has yielded. It should be noted that actually the creep and shrinkage occurring in the compression concrete help the compression steel to yield.

Sometimes the neutral axis is quite close to the compression steel. As a matter of fact, in some beams with low steel percentages, the neutral axis may be right at the compression steel. For such cases, the addition of compression steel adds little, if any, moment capacity to the beam. It can, however, make the beam more ductile.

When compression steel is used, the nominal resisting moment of the beam is assumed to consist of two parts: the part due to the resistance of the compression concrete and the balancing tensile reinforcing, and the part due to the nominal moment capacity of the compression steel and the balancing amount of the additional tensile steel. This situation is illustrated in Figure 5.13. In the expressions developed here, the effect of the concrete in compression, which is replaced by the compressive steel,  $A'_s$ , is neglected. This omission will cause us to overestimate  $M_n$  by a very small and negligible amount (less than 1%). The first of the two resisting moments is illustrated in Figure 5.13(b).

$$M_{n1} = A_{s1} f_y \left( d - \frac{a}{2} \right)$$

![](_page_147_Figure_8.jpeg)

FIGURE 5.13 Doubly reinforced beam broken into parts.

The second resisting moment is that produced by the additional tensile and compressive steel  $(A_{s2} \text{ and } A'_s)$ , which is presented in Figure 5.13(c).

$$M_{n2} = A_s' f_v(d - d')$$

Up to this point it has been assumed that the compression steel has reached its yield stress. If such is the case, the values of  $A_{s2}$  and  $A_s'$  will be equal because the addition to T of  $A_{s2}f_y$  must be equal to the addition to C of  $A_s'f_y$  for equilibrium. If the compression steel has not yielded,  $A_s'$  must be larger than  $A_{s2}$ , as will be described later in this section.

Combining the two values, we obtain

$$M_{n} = A_{s1}f_{y}\left(d - \frac{a}{2}\right) + A_{s2}f_{y}(d - d')$$

$$\phi M_{n} = \phi \left[A_{s1}f_{y}\left(d - \frac{a}{2}\right) + A_{s2}f_{y}(d - d')\right]$$

The addition of compression steel only on the compression side of a beam will have little effect on the nominal resisting moment of the section. The lever arm, z, of the internal couple is not affected very much by the presence of the compression steel, and the value of T will remain the same. Thus, the value  $M_n = Tz$  will change very little. To increase the nominal resisting moment of a section, it is necessary to add reinforcing on both the tension and the compression sides of the beam, thus providing another resisting moment couple.

Examples 5.7 and 5.8 illustrate the calculations involved in determining the design strengths of doubly reinforced sections. In each of these problems, the strain,  $f_s'$ , in the compression steel is checked to determine whether or not it has yielded. With the strain obtained, the compression steel stress,  $f_s'$ , is determined, and the value of  $A_{s2}$  is computed with the following expression:

$$A_{s2}f_{v} = A'_{s}f'_{s}$$

In addition, it is necessary to compute the strain in the tensile steel,  $\epsilon_t$ , because if it is less than 0.005, the value of the bending,  $\phi$ , will have to be computed, inasmuch as it will be less than its usual 0.90 value. The beam may not be used in the unlikely event that  $\epsilon_t$  is less than 0.004.

To determine the value of these strains, an equilibrium equation is written, which upon solution will yield the value of c and thus the location of the neutral axis. To write this equation, the nominal tensile strength of the beam is equated to its nominal compressive strength. Only one unknown appears in the equation, and that is c.

Initially the stress in the compression steel is assumed to be at yield  $(f'_s = f_y)$ . From Figure 5.14, summing forces horizontally in the force diagram and substituting  $\beta_1 c$  for a leads to

$$A_{s}f_{y} = 0.85f'_{c}\beta_{1}cb + A'_{s}f_{y}$$

$$c = \frac{(A_{s} - A'_{s})f_{y}}{0.85f'_{c}\beta_{1}b}$$

Referring to the strain diagram of Figure 5.14, from similar triangles

$$\epsilon_s' = \frac{c - d'}{c} (0.003)$$

If the strain in the compression steel  $\epsilon_s' > \epsilon_y = f_y/E_s$ , the assumption is valid and  $f_s'$  is at yield,  $f_y$ . If  $\epsilon_s' < \epsilon_y$ , the compression steel is not yielding, and the value of c calculated above is not correct. A new equilibrium equation must be written that assumes  $f_s' < f_y$ .

$$A_s f_y = 0.85 f_c' \beta_1 cb + A_s' \left(\frac{c - d'}{c}\right) (0.003) E_s$$

where  $E_s = 29,000,000 \text{ psi} = 29,000 \text{ ksi}.$ 

![](_page_149_Figure_2.jpeg)

FIGURE 5.14 Internal strains and forces for doubly reinforced rectangular beam.

The value of c determined enables us to compute the strains in both the compression and tensile steels and thus their stresses. Even though the writing and solving of this equation are not too tedious, use of the Excel spreadsheet for beams with compression steel makes short work of the whole business.

Examples 5.7 and 5.8 illustrate the computation of the design moment strength of doubly reinforced beams. In the first of these examples, the compression steel yields, while in the second, it does not.

#### Example 5.7

Determine the design moment capacity of the beam shown in Figure 5.15 for which  $f_v =$ 60,000 psi and  $f'_c = 3000$  psi.

#### SOLUTION

Writing the Equilibrium Equation Assuming  $f'_s = f_v$ 

$$A_{\rm s}f_y=0.85f_c'b\beta_1c+A_{\rm s}'f_y$$
 (6.25 in.²) (60 ksi) = (0.85) (3 ksi) (14 in.) (0.85c) + (2.00 in.²) (60 ksi)

![](_page_149_Figure_11.jpeg)

**FIGURE 5.15** Beam cross section for Example 5.7.

$$c = \frac{(6.25 \text{ in.}^2 - 2.00 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (3 \text{ ksi}) (0.85) (14 \text{ in.})} = 8.40 \text{ in.}$$
$$a = \beta_1 c = (0.85) (8.40 \text{ in.}) = 7.14 \text{ in.}$$

#### Computing Strains in Compression Steel to Verify Assumption that It Is Yielding

$$\begin{split} \epsilon_s' &= \frac{c - d'}{c} (0.003) = \frac{8.40 \text{ in.} - 2.5 \text{ in.}}{8.40 \text{ in.}} (0.003) = 0.00211 \\ \epsilon_y &= \frac{f_y}{E_s} = \frac{60,000 \text{ psi}}{29,000,000 \text{ psi}} = 0.00207 < \epsilon_s' \\ & \therefore f_s' = f_y \text{ as assumed.} \end{split}$$

Note: Example 5.8 shows what to do if this assumption is not correct.

$$A_{s2} = \frac{A_s' f_s'}{f_y} = \frac{(2.00 \text{ in.}^2) (60,000 \text{ psi})}{60,000 \text{ psi}} = 2.00 \text{ in.}^2$$

$$A_{s1} = A_s - A_{s2} = 6.25 \text{ in.}^2 - 2.00 \text{ in.}^2 = 4.25 \text{ in.}^2$$

$$\epsilon_t = \frac{d - c}{c} 0.003 = \frac{24 \text{ in.} - 8.40 \text{ in.}}{8.40 \text{ in.}} (0.003) = 0.00557 > 0.005$$

$$\therefore \phi = 0.9$$

Then the design moment strength is

$$\phi M_n = \phi \left[ A_{s1} f_y \left( d - \frac{a}{2} \right) + A_s' f_s' (d - d') \right]$$

$$= 0.9 \left[ (4.25 \text{ in.}^2) (60 \text{ ksi}) \left( 24 \text{ in.} - \frac{7.14 \text{ in.}}{2} \right) + (2.00 \text{ in.}^2) (60 \text{ ksi}) (24 \text{ in.} - 2.5 \text{ in.}) \right]$$

$$= 7010 \text{ in-k} = 584.2 \text{ ft-k}$$

#### Example 5.8

Compute the design moment strength of the section shown in Figure 5.16 if  $f_y = 60,000$  psi and  $f_c' = 4000$  psi.

![](_page_150_Figure_11.jpeg)

**FIGURE 5.16** Beam cross section for Example 5.8.

#### SOLUTION

Writing the Equilibrium Equation Assuming  $f'_s = f_v$ 

$$A_s f_y = 0.85 f_c' b \beta_1 c + A_s' f_y$$

$$(5.06 in.^2) (60 ksi) = (0.85) (4 ksi) (14 in.) (0.85c) + (1.20 in.^2) (60 ksi)$$

$$c = \frac{(5.06 in.^2 - 1.20 in.^2) (60 ksi)}{(0.85) (4 ksi) (0.85)} = 5.72 in.$$

$$a = \beta_1 c = (0.85) (5.72 in.) = 4.86 in.$$

Computing Strains in Compression Steel to Verify Assumption that It Is Yielding

$$\begin{split} \epsilon_s' &= \frac{c - d'}{c} (0.003) = \frac{5.72 \text{ in.} - 2.5 \text{ in.}}{5.72 \text{ in.}} (0.003) = 0.00169 \\ \epsilon_y &= \frac{f_y}{E_s} = \frac{60,000 \text{ psi}}{29,000,000 \text{ psi}} = 0.00207 > \epsilon_s' \\ & \therefore f_s' \neq f_y \text{ as assumed} \end{split}$$

Since the assumption is not valid, we have to use the equilibrium equation that is based on  $f'_s$ not yielding.

$$A_s f_y = 0.85 f_c' \beta_1 cb + A_s' \left(\frac{c - d'}{c}\right) (0.003) E_s$$

$$(5.06 in.^2) (60 ksi) = (0.85) (4 ksi) (0.85c) (14 in.) + (1.20 in.^2) \left(\frac{c - 2.5 in.}{c}\right) (0.003) (29,000 ksi)$$

Solving the Quadratic Equation for c = 6.00 in. and  $a = \beta_1 c = 5.10$  in.

Compute strains, stresses, and steel areas

$$\epsilon_s' = \left(\frac{c - d'}{c}\right) (0.003) = \frac{6.00 \text{ in.} - 2.5 \text{ in.}}{6.00 \text{ in.}} (0.003) = 0.00175 < \epsilon_y$$

$$f_s' = \epsilon_s' E_s = (0.00175) (29,000 \text{ ksi}) = 50.75 \text{ ksi}$$

$$A_{s2} = \frac{A_s' f_s'}{f_y} = \frac{(1.20 \text{ in.}^2) (50,750 \text{ psi})}{60,000 \text{ psi}} = 1.015 \text{ in.}^2$$

$$A_{s1} = A_s - A_{s2} = 5.06 \text{ in.}^2 - 1.015 \text{ in.}^2 = 4.045 \text{ in.}^2$$

$$\epsilon_t = \left(\frac{d - c}{c}\right) (0.003) = \frac{24 \text{ in.} - 6.00 \text{ in.}}{6.00 \text{ in.}} (0.003) = 0.0090 > 0.005 \qquad \therefore \phi = 0.9$$

Then the design moment strength is

$$\phi M_n = \phi \left[ A_{s1} f_y \left( d - \frac{a}{2} \right) + A_s' f_s' (d - d') \right]$$

$$= 0.9 \left[ (4.045 \text{ in.}^2) (60 \text{ ksi}) \left( 24 \text{ in.} - \frac{5.10 \text{ in.}}{2} \right) + (1.20 \text{ in.}^2) (50.75 \text{ ksi}) (24 \text{ in.} - 2.5 \text{ in.}) \right]$$

$$= 5863 \text{ in-k} = 488.6 \text{ ft-k}$$

#### 5.8 **Design of Doubly Reinforced Beams**

Sufficient tensile steel can be placed in most beams so that compression steel is not needed. But if it is needed, the design is usually quite straightforward. Examples 5.9 and 5.10 illustrate the design of doubly reinforced beams. The solutions follow the theory used for analyzing doubly reinforced sections.

Design a rectangular beam for  $M_D = 325$  ft-k and  $M_L = 400$  ft-k if  $f'_c = 4000$  psi and  $f_y = 60,000$  psi. The maximum permissible beam dimensions are shown in Figure 5.17.

$$M_{II} = (1.2)(325 \text{ ft-k}) + (1.6)(400 \text{ ft-k}) = 1030 \text{ ft-k}$$

#### SOLUTION

#### Assuming $\phi = 0.90$

$$M_n = \frac{M_u}{\phi} = \frac{1030 \text{ ft-k}}{0.90} = 1144.4 \text{ ft-k}$$

Assuming maximum possible tensile steel with no compression steel and computing beam's nominal moment strength

$$\rho_{\rm max} \ ({\rm from \ Appendix \ A, \ Table \ A.7}) = 0.0181$$
 
$$A_{\rm s1} = (0.0181) (15 \ {\rm in.}) (28 \ {\rm in.}) = 7.60 \ {\rm in.}^2$$
 
$${\rm For \ } \rho = 0.0181 \frac{M_u}{\phi b d^2} \ ({\rm from \ Table \ A.13}) = 912.0 \ {\rm psi}$$
 
$$M_{u1} = (912.0 \ {\rm psi}) (0.9) (15 \ {\rm in.}) (28 \ {\rm in.})^2 = 9,652,608 \ {\rm in-lb}$$
 
$$= 804.4 \ {\rm ft-k}$$
 
$$M_{n1} = \frac{804.4}{0.90} = 893.8 \ {\rm ft-k}$$
 
$$M_{n2} = M_n - M_{n1} = 1144.4 \ {\rm ft-k} - 893.8 \ {\rm ft-k} = 250.6 \ {\rm ft-k}$$

#### Checking to See Whether Compression Steel Has Yielded

$$a = \frac{(7.60 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (4 \text{ ksi}) (15 \text{ in.})} = 8.94 \text{ in.}$$

$$c = \frac{8.94 \text{ in.}}{0.85} = 10.52 \text{ in.}$$

$$\epsilon_s' = \left(\frac{10.52 \text{ in.} - 3 \text{ in.}}{10.52 \text{ in.}}\right) (0.00300) = 0.00214 > 0.00207$$

Therefore, compression steel has yielded.

![](_page_152_Figure_13.jpeg)

**FIGURE 5.17** Beam cross section for Example 5.9.

Theoretical 
$$A_s'$$
 required  $=\frac{M_{n2}}{(f_y)(d-d')}=\frac{(12 \text{ in/ft}) (250.6 \text{ ft-k})}{(60 \text{ ksi}) (28 \text{ in.} - 3 \text{ in.})}=2.00 \text{ in.}^2$  
$$A_s'f_s' = A_{s2}f_y$$
 
$$A_{s2} = \frac{A_s'f_s'}{f_y} = \frac{(2.00 \text{ in.}^2) (60 \text{ ksi})}{60 \text{ ksi}} = 2.00 \text{ in.}^2$$
 
$$\underline{\text{Try 2 #9 (2.00 in.}^2)}$$
 
$$A_s = A_{s1} + A_{s2}$$
 
$$A_s = 7.60 \text{ in.}^2 + 2.00 \text{ in.}^2 = \underline{9.60 \text{ in.}^2}$$
 
$$\text{Try 8 #10 (10.12 in.}^2)$$

If we had been able to select bars with exactly the same areas as calculated here,  $\epsilon_t$  would have remained = 0.005 as originally assumed and  $\phi = 0.90$ , but such was not the case.

From the equation for c in Section 5.7, c is found to equal 11.24 in. and  $a = \beta_1 c = 9.55$  in. using actual, not theoretical, bar areas for  $A_s$  and  $A'_s$ .

$$\begin{split} \epsilon_{\rm s}' &= \left(\frac{11.24~{\rm in.} - 3~{\rm in.}}{11.24~{\rm in.}}\right) (0.003) = 0.00220 > 0.00207~{\rm compression~steel~yields} \\ \epsilon_t &= \left(\frac{28~{\rm in.} - 11.24~{\rm in.}}{11.24~{\rm in.}}\right) (0.003) = 0.00447 < 0.005 \\ \phi &= 0.65 + (0.00447 - 0.002) \left(\frac{250}{3}\right) = 0.855 \\ \phi M_n &= 0.855 \left[ (10.12~{\rm in.}^2 - 2.00~{\rm in.}^2) (60~{\rm ksi}) \left(28~{\rm in.} - \frac{9.55~{\rm in.}}{2}\right) \right. \\ &\quad \left. + (2.00~{\rm in.}^2) (60~{\rm ksi}) (25~{\rm in.}) \right] \\ &= 12,241~{\rm in-lb} = 1020~{\rm ft-k} < 1030~{\rm ft-k} \qquad {\rm No~good} \end{split}$$

The beam does not have sufficient capacity because of the variable  $\phi$  factor. This can be avoided if you are careful in picking bars. Note that the actual value of  $A_s'$  is exactly the same as the theoretical value. The actual value of  $A_s$ , however, is higher than the theoretical value by 10.12 - 9.6 = 0.52 in.<sup>2</sup>. If a new bar selection for  $A_s$  is made whereby the actual value of  $A_s'$  exceeds the theoretical value by about this much (0.52 in.<sup>2</sup>), the design will be adequate. Select three #8 bars  $(A'_s = 2.36 \text{ in.}^2)$  and repeat the previous steps. Note that the actual steel areas are used below, not the theoretical ones. As a result, the values of  $c, a, \epsilon'_s$ , and  $f'_s$  must be recalculated.

#### Assuming $f_s' = f_v$

$$c = \frac{(A_s - A_s')f_y}{0.85f_c'b\beta_1} = \frac{(10.12 \text{ in.}^2 - 2.36 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (4 \text{ ksi}) (15 \text{ in.}) (0.85)} = 10.74 \text{ in.}$$

$$\epsilon_s' = \left(\frac{c - d'}{c}\right) (0.003) = \frac{10.74 \text{ in.} - 3 \text{ in.}}{10.74 \text{ in.}} (0.003) = 0.00216 > \epsilon_y \qquad \therefore \text{ Assumption is valid}$$

$$\epsilon_t = \left(\frac{d - c}{c}\right) (0.003) = \frac{28 \text{ in.} - 10.74 \text{ in.}}{10.74 \text{ in.}} (0.003) = 0.00482 < 0.005 \qquad \therefore \phi \neq 0.9$$

$$\phi = 0.65 + (\epsilon_t - 0.002) \left(\frac{250}{3}\right) = 0.88$$

$$A_{s2} = \frac{A_s' f_s'}{f_y} = \frac{(2.36 \text{ in.}^2) (60 \text{ ksi})}{60 \text{ ksi}} = 2.36 \text{ in.}^2$$

$$A_{s1} = A_s - A_{s2} = 10.12 \text{ in.}^2 - 2.36 \text{ in.}^2 = 7.76 \text{ in.}^2$$

$$M_{n1} = A_{s1} f_y \left( d - \frac{a}{2} \right) = (7.76 \text{ in.}^2) (60 \text{ ksi}) \left[ 28 \text{ in.} - \frac{(0.85) (10.74 \text{ in.})}{2} \right] = 10,912 \text{ in-k} = 909.3 \text{ ft-k}$$

$$M_{n2} = A_{s2} f_y (d - d') = (2.36 \text{ in.}^2) (60 \text{ ksi}) (28 \text{ in.} - 3 \text{ in.}) = 3540 \text{ in-k} = 295 \text{ ft-k}$$

$$M_n = M_{n1} + M_{n2} = 909.3 \text{ ft-k} + 295 \text{ ft-k} = 1204.3 \text{ ft-k}$$

$$\phi M_n = (0.88) (1204.3 \text{ ft-k}) = 1059.9 \text{ ft-k} > M_u \qquad \underline{OK}$$

Note that eight #10 bars will not fit in a single layer in this beam. If they were placed in two layers, the centroid would have to be more than 3 in. from the bottom of the section. It would be necessary to increase the beam depth, h, in order to provide for two layers or to use bundled bars (Section 7.4).

#### Example 5.10

A beam is limited to the dimensions b=15 in., d=20 in., and d'=4 in. If  $M_D=170$  ft-k,  $M_L=225$  ft-k,  $f_c'=4000$  psi, and  $f_v=60,000$  psi, select the reinforcing required.

#### SOLUTION

$$M_{ij} = (1.2)(170 \text{ ft-k}) + (1.6)(225 \text{ ft-k}) = 564 \text{ ft-k}$$

#### Assuming $\phi = 0.90$

$$\begin{split} M_n &= \frac{564 \text{ ft-k}}{0.90} = 626.7 \text{ ft-k} \\ \text{Max } A_{s1} &= (0.0181) \, (15 \text{ in.}) \, (20 \text{ in.}) = 5.43 \text{ in.}^2 \\ \text{For } \rho &= 0.0181 \frac{M_u}{\phi \, b d^2} = 912.0 \text{ psi (from Appendix A, Table A.13)} \\ M_{u1} &= (912 \text{ psi)} \, (0.90) \, (15 \text{ in.}) \, (20 \text{ in.})^2 = 4,924,800 \text{ in-lb} = 410.4 \text{ ft-k} \\ M_{n1} &= \frac{410.4 \text{ ft-k}}{0.90} = 456.0 \text{ ft-k} \\ M_{n2} &= 626.7 \text{ ft-k} - 456.0 \text{ ft-k} = 170.7 \text{ ft-k} \end{split}$$

#### Checking to See If Compression Steel Has Yielded

$$a = \frac{A_{s1}f_y}{0.85f_c'b} = \frac{(5.43 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (4 \text{ ksi}) (15 \text{ in.})} = 6.39 \text{ in.}$$

$$c = \frac{6.39 \text{ in.}}{0.85} = 7.52 \text{ in.}$$

$$\epsilon_s' = \left(\frac{7.52 \text{ in.} - 4.00 \text{ in.}}{7.52 \text{ in.}}\right) (0.003) = 0.00140 < \frac{60 \text{ ksi}}{29,000 \text{ ksi}} = 0.00207$$

$$\therefore f_s' = (0.00140) (29,000 \text{ ksi}) = 40.6 \text{ ksi}$$

Theoretical 
$$A'_{s \text{ reqd}} = \frac{M_{n2}}{f'_{s}(d-d')}$$

$$= \frac{(12 \text{ in/ft}) (170.7 \text{ ft-k})}{(40.6 \text{ ksi}) (20 \text{ in.} - 4 \text{ in.})} = \underline{3.15 \text{ in.}^{2}}$$

$$A'_{s}f'_{s} = A_{s2}f_{y}$$

$$A_{s2} = \frac{(3.14 \text{ in.}^{2}) (40.6 \text{ ksi})}{60 \text{ ksi}} = 2.12 \text{ in.}^{2}$$

$$A_{s} = A_{s1} + A_{s2} = 5.43 \text{ in.}^{2} + 2.12 \text{ in.}^{2} = \underline{7.55 \text{ in.}^{2}}$$
Try 6 #10 (7.59 in.<sup>2</sup>)

Subsequent checks using actual steel areas reveal  $\epsilon_t=0.00495, \phi=0.896,$  and  $\phi M_n=459.4$ ft-k, which is less than  $M_{ij}$  by about 0.1%.

#### SI Examples 5.9

Examples 5.11 and 5.12 illustrate the analysis of a T beam and the design of a doubly reinforced beam using SI units.

#### Example 5.11

Determine the design strength of the T beam shown in Figure 5.18 if  $f_{\rm y}=420\,{\rm MPa},$  $f_c' = 35$  MPa, and  $E_s = 200,000$  MPa.

#### SOLUTION

Computing T and  $A_c$ 

$$T = (3060 \text{ mm}^2)(420 \text{ MPa}) = 1 285 200 \text{ N}$$

$$A_c = \frac{T}{0.85f'_c} = \frac{1 \text{ 285 200 N}}{(0.85)(35 \text{ MPa})} = 43 \text{ 200 mm}^2$$

![](_page_155_Figure_12.jpeg)

**FIGURE 5.18** Beam cross section for Example 5.11.

$$\rho = \frac{A_{\rm s}}{b_{\rm w}d} = \frac{3060~{\rm mm}^2}{(300~{\rm mm})(550~{\rm mm})} = 0.0185 < \rho_{\rm max}$$

= 0.0216 (from Appendix B, Table B.7) OK

$$\rho_{\min} = \frac{\sqrt{f_{\rm c}'}}{4f_{\rm v}} = \frac{\sqrt{35} \text{ MPa}}{(4) (420 \text{ MPa})} = 0.003 \text{ } 52 < 0.0185 \quad \underline{\underline{\rm OK}}$$

or

$$\frac{1.4}{f_v} = \frac{1.4}{420 \text{ MPa}} = 0.003 \text{ } 33 < 0.0185 \quad \underline{\underline{OK}}$$

#### **Calculating Design Strength**

$$a = \frac{43,200 \text{ mm}^2}{1200 \text{ mm}} = 36 \text{ mm} < h_f = 100 \text{ mm}$$

: stress block is entirely within flange

$$z = d - \frac{a}{2} = 550 \text{ mm} - \frac{36 \text{ mm}}{2} = 532 \text{ mm}$$

$$\phi M_n = \phi Tz$$

$$= 6.153 \times 10^8 \text{ N} \cdot \text{mm} = \underline{615.3 \text{ kN} \cdot \text{m}}$$

#### Example 5.12

If  $M_u=1225~{\rm kN\cdot m}$ , determine the steel area required for the section shown in Figure 5.19. Should compression steel be required, assume that it will be placed 70 mm from the compression face.  $f_C'=21~{\rm MPa}$ ,  $f_V=420~{\rm MPa}$ , and  $E_S=200,000~{\rm MPa}$ .

#### SOLUTION

$$M_n = \frac{1225 \text{ kN} \cdot \text{m}}{0.9} = 1361 \text{ kN} \cdot \text{m}$$

![](_page_156_Figure_18.jpeg)

**FIGURE 5.19** Beam cross section for Example 5.12.

$$ho_{
m max}$$
 if singly reinforced = 0.0135 (from Appendix B, Table B.7) 
$$A_{\rm s1} = (0.0135)\,(350~{\rm mm})\,(700~{\rm mm}) = 3307~{\rm mm}^2 \\ \frac{M_{u1}}{\phi\,bd^2} = 4.769~{\rm MPa}\,({\rm from~Table~B.8}) \\ M_{u1} = (\phi\,bd^2)\,(4.769~{\rm MPa}) = \frac{(4.769~{\rm MPa})\,(0.9)\,(350~{\rm mm})\,(700~{\rm mm})^2}{10^6} = 736.1~{\rm kN\cdot m} \\ M_{n1} = \frac{736.1~{\rm kN\cdot m}}{0.9} = 818~{\rm kN\cdot m} \\ < M_n~{\rm of~1361~kN\cdot m} \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad$$

#### **Checking to See If Compression Steel Yields**

$$a = \frac{(3307 \text{ mm}^2) (420 \text{ MPa})}{(0.85) (21 \text{ MPa}) (350 \text{ mm})} = 222.32 \text{ mm}$$

$$c = \frac{222.32 \text{ mm}}{0.85} = 261.55 \text{ mm}$$

$$\epsilon'_s = \left(\frac{261.55 \text{ mm} - 70 \text{ mm}}{261.55 \text{ mm}}\right) (0.003) = 0.00220$$

$$> \frac{420 \text{ MPa}}{200 \text{ 000 MPa}} = 0.002 \text{ 10} \qquad \qquad \text{:: Compression steel yields}$$

$$A'_{s \text{ reqd}} = \frac{M_{n2}}{f_y(d - d')} = \frac{543 \text{ kN} \cdot \text{m} \times 10^6}{(700 \text{ mm} - 70 \text{ mm}) (420 \text{ MPa})} = \frac{2052 \text{ mm}^2}{\text{Use } 3 \text{ #32 bars } (2457 \text{ mm}^2)}$$

$$\frac{\text{Use } 3 \text{ #32 bars } (2457 \text{ mm}^2)}{(2457 \text{ mm}^2)}$$

Use 6 #36 bars ( $A_s = 6036 \text{ mm}^2$ )

#### 5.10 **Computer Examples**

#### Example 5.13

Repeat Example 5.3 using the Excel spreadsheet.

#### SOLUTION

Open the Excel spreadsheet for T beams and select the Analysis worksheet tab at the bottom. Input only cells C3 through C9 highlighted in yellow (only in the Excel spreadsheets, not the printed example).

#### **T-Beam Analysis**

$$f'_{c} = egin{array}{c} 4{,}000 & \mathrm{psi} \\ f_{y} = 60{,}000 & \mathrm{psi} \\ b_{\mathrm{eff}} = 30 & \mathrm{in.} \\ b_{w} = 14 & \mathrm{in.} \\ d = 30 & \mathrm{in.} \\ h_{f} = 4 & \mathrm{in.} \\ A_{s} = 10.12 & \mathrm{in.}^{2} \\ \beta_{1} = 0.85 \\ A_{s \, \mathrm{min}} = \frac{3\sqrt{f'_{c}}}{f_{y}} b_{w} d = 1.33 \, \mathrm{in.}^{2} \\ A_{s \, \mathrm{min}} = \frac{200}{f_{v}} b_{w} d = 1.40 \, \mathrm{in.}^{2} \quad \mathrm{minimum \, steel \, is} \, \underline{\mathrm{OK}} \\ \end{array}$$

If 
$$\mathbf{a} \leq \mathbf{h_f}$$
:  $a > h_f$ , so this analysis is not valid.

$$a=\frac{A_s f_y}{0.85 f_c' b}=5.95 \text{ in.}$$
 
$$M_n=A_s f_y(d-a/2)= \qquad \qquad -\text{ in-lb} \qquad =\text{ See solution below} \qquad \text{ft-k}$$
 
$$c=a/\beta_1=7.00346$$
 
$$\epsilon_t=\frac{d-c}{c}(0.003)=0.009851 \qquad -$$
 
$$\phi=0.9$$
 
$$\phi M_n= \qquad \qquad -\text{ in-lb} \qquad =\text{ See solution below} \qquad \text{ft-k}$$

If 
$$a > h_f$$
:  $a > h_f$ , so this analysis is valid—acts like a T beam.

$$A_{sf} = \frac{0.85f_c'(b-b_w)h_f}{f_y} = 3.627 \text{ in.}^2$$

$$A_{sw} = A_s - A_{sf} = 6.493 \text{ in.}^2$$

$$a = \frac{A_{sw}f_y}{0.85f_c'b} = 8.185 \text{ in.}$$

$$M_n = A_{sf}f_y\left(d - \frac{h_f}{2}\right) + A_{sw}f_y\left(d - \frac{a}{2}\right) = 16,186,387 \text{ in-lb} = 1348.9 \text{ ft-k}$$

$$c = a/\beta_1 = 9.629263 \text{ in.}$$

$$\epsilon_t = \frac{d-c}{c}(0.003) = 0.006347 - \frac{d}{c} = 0.9$$

$$\phi M_n = 14,567,748 \text{ in-lb} = 1214.0 \text{ ft-k}$$

#### Example 5.14

Repeat Example 5.6 using the Excel spreadsheet.

#### SOLUTION

Open the Excel spreadsheet for T beams and select the T-Beam Design worksheet tab at the bottom. Input only cells C3 through C9 highlighted in yellow.

#### T-Beam Design

![](_page_159_Figure_7.jpeg)

If 
$$a \le h_f$$
:  $a > h_f$ , so this analysis is not valid. 
$$R_n = \frac{M_u}{\phi b d^2} = 394.38 \text{ in.}$$

$$\rho = \frac{0.85 f_c'}{f_y} \left( 1 - \sqrt{1 - \frac{2R_n}{0.85 f_c'}} \right) = 0.007179$$

$$a = \frac{\rho f_y d}{0.85 f_c'} = 4.054201 \text{ in.}$$

$$c = a/\beta_1 = 4.769648$$

$$\epsilon_t = \frac{d-c}{c}(0.003) = 0.012095 \qquad A_{s \min} = \frac{3\sqrt{f_c'}}{f_y} b_w d = 0.985901 \text{ in.}^2$$

$$\phi = 0.9 \qquad - \qquad -$$

$$A_s = \rho b d = 9.304391 \text{ in.}^2 \qquad A_{s \min} = \frac{200}{f_y} b_w d = 1.2 \text{ in.}^2$$

If  $a > h_f$ :  $a > h_f$ , so this analysis is valid—acts like a T beam.

$$A_{sf} = \frac{0.85f_c'(b - b_w)h_f}{f_y} = 4.97 \text{ in.}^2$$

$$M_{uf} = A_{sf}f_y\left(d - \frac{h_f}{2}\right) = 503.5 \text{ ft-k}$$

$$\begin{split} M_{uw} &= M_{uf} - M_u = 416.5 \\ R_{nw} &= \frac{M_{uw}}{\phi b d^2} = 642.8 \\ \rho_w &= \frac{0.85 f_c'}{f_y} \left( 1 - \sqrt{1 - \frac{2R_{nw}}{0.85 f_c'}} \right) = 0.012573 \\ a &= \frac{\rho_w f_y d}{0.85 f_c'} = 7.100128 \text{ in.} \\ c &= a/\beta_1 = 8.353092 \text{ in.} \\ \epsilon_t &= \frac{d-c}{c} (0.003) = 0.00562 \\ \phi &= 0.9 \\ A_{sw} &= \rho_w b_w d = 4.53 \text{ in.}^2 \\ A_{s \min} &= \frac{3\sqrt{f_c'}}{f_y} b_w d = 0.985901 \text{ in.}^2 \\ A_{s \min} &= \frac{200}{f_y} b_w d = 1.2 \text{ in.}^2 \\ Note: \text{ Solution is based on } \phi &= 0.9. \end{split}$$

#### Example 5.15

Repeat Example 5.7 using the Excel spreadsheet.

#### SOLUTION

Open the Excel spreadsheet for Beams with Compression Steel and select the Analysis worksheet tab at the bottom. Input only cells C3 through C9 highlighted in yellow. Other values are calculated from those input values. See comment on cell E22 for Goal Seek instructions.

#### Analysis of Doubly Reinforced Beams by ACI 318-11

 $A_s$ ,  $A'_s$ , b, d,  $M_u$ ,  $f'_c$ ,  $f_v$  known or specified

$$\begin{array}{llllllllllllllllllllllllllllllllllll$$

Determine the location of the neutral axis, c.

$$c = 8.40 \text{ in.}$$

$$e'_s = 0.00211$$

$$a = 7.14 \text{ in.}$$

$$f'_s = 60.00 \text{ psi} \quad \text{Compression steel is at yield}$$

$$0.85 f'_c \beta_1 cb + A'_s f'_s = A_s f_y$$

$$0.85 f'_c \beta_1 cb + A'_s f'_s = 120 \text{ kips}$$

$$A_s f_y = 375 \text{ kips}$$

$$0.85 f'_c \beta_1 cb + A'_s f' - A_s f_y = 0 \text{ OK}$$

$$A_{s2} = A'_s f'_s / f_y = 2.000 \text{ in.}^2$$

$$A_{s1} = A_s - A_{s2} = 4.250 \text{ in.}^2$$

$$f_s = \frac{d - c}{c} (0.003) = 0.005568 \text{ OK} \text{ tensile strain exceeds } 0.004$$

$$\phi = 0.900 - 0.00568 \text{ on.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.} \text{ in.$$

#### Example 5.16

Repeat Example 5.9 using the Excel spreadsheet.

#### SOLUTION

Open the Excel spreadsheet for Beams with Compression Steel and select the ACI 318-11 Case I worksheet tab at the bottom. Input only cells C3 through C9 highlighted in yellow. Other values are calculated from those input values.

### Design of Doubly Reinforced Beams by ACI 318-11 when both $A_{\rm s}$ and $A_{\rm s}'$ are unknown

 $A_s$  and  $A'_s$  are unknown; b, d,  $M_u$ ,  $f'_u$ ,  $f_v$  known or specified.

$$M_u = 1,030.00$$
 ft-k  
 $b = 15$  in.  
 $d = 28$  in.  
 $d' = 3$  in.  
 $f'_c = 4,000$  psi  
 $f_y = 60,000$  psi  
 $\beta_1 = 0.85$ 

1. Determine the maximum ultimate moment permitted by the code for the beam if it were singly reinforced (using the maximum value of  $\rho$  associated with  $\phi = 0.9$ ).

$$\rho = 0.375(0.85\beta_1 f_C'/f_V) = 0.018063$$

$$M_{\text{max}} = \phi \rho b d^2 f_y \left( 1 - \frac{\rho f_y}{1.7 f_m'} \right) = \begin{cases} 9,642,313.4 & \text{in-lb} \\ 803.53 & \text{ft-k} \end{cases}$$

- **2.** If  $M_{\text{max}} \ge M_u$ , compression steel is not needed. Design as singly reinforced beam. If  $M_{\text{max}} < M_u$ , continue to step 3.
- **3.** The most economical design uses  $M_{u1} = M_{\text{max}}$ , which corresponds to  $\rho_1$  = the maximum value of  $\rho$  associated with  $\phi = 0.9$ .

$$\begin{array}{cccccccccccccccccccccccccccccccccccc$$

**4.** 
$$M_{u2} = M_u - M_{u1} = 226.47$$
 ft-k

**5.** 
$$A_{s2} = \frac{M_{u2}}{\phi \cdot f_v(d - d')} = 2.013 \text{ in.}^2$$

**6.** 
$$c = a/\beta_1$$
 = 10.500 in.

7. 
$$f'_s = \frac{c - d'}{c}$$
 (87,000) = 62,143 psi if  $f'_s > f_y$ , use  $f_s = f_y$   $f'_s = 60,000$  psi

**8.** 
$$A_s = \frac{A_{s2}f_y}{f_s'}$$
 = 2.01 in.<sup>2</sup> Select bars No. of bars #8  $A_s' = 2.36$  in.<sup>2</sup>

**9.** 
$$A'_s = A_{s1} + A_{s2}$$
 = 9.60 in.<sup>2</sup> Select bars 8 #10  $A_s = 10.13$  in.<sup>2</sup>

#### **PROBLEMS**

**Problem 5.1** What is the effective width of a T beam? What does it represent?

**Problem 5.2** What factors affect the selection of the dimensions of T-beam stems?

**Problem 5.3** If additional reinforcing bars are placed only in the compression side of a reinforced concrete beam, will they add significantly to the beam's flexural strength? Explain your answer.

**Problem 5.4** Why is compression reinforcing particularly important in reinforced concrete flexural members located in earthquake-prone areas?

#### **Analysis of T Beams**

For Problems 5.5 to 5.15, determine the design moment strengths **Problem 5.11** (Ans. 297.4 ft-k)  $\phi M_n$  of the sections shown. Use  $f_v = 60,000$  psi and  $f_c' =$ 4000 psi, except for Problem 5.9, where  $f_c' = 5000$  psi. Check each section to see if it is ductile.

**Problem 5.5** (*Ans.* 369.1 ft-k)

![](_page_163_Figure_4.jpeg)

**Problem 5.6** Repeat Problem 5.5 if four #10 bars are used.

**Problem 5.7** Repeat Problem 5.5 if 10 #7 bars are used. (Ans. 721.4 ft-k)

#### Problem 5.8

![](_page_163_Figure_8.jpeg)

**Problem 5.9** Repeat Problem 5.8 if  $f'_c = 5000$  psi. (Ans. 1042 ft-k)

Problem 5.10 Repeat Problem 5.8 if eight #9 bars are used and  $f_c' = 4000$  psi.

![](_page_163_Figure_12.jpeg)

Problem 5.12

![](_page_163_Figure_14.jpeg)

**Problem 5.13** (*Ans*. 419.7 ft-k)

![](_page_164_Picture_2.jpeg)

**Problem 5.15** (*Ans*. 1075.2 ft-k)

![](_page_164_Figure_4.jpeg)

**Problem 5.14**

![](_page_164_Figure_6.jpeg)

**Problem 5.16** Calculate the design strength  $\phi M_n$  for one of the T beams if  $f_c' = 5000$  psi,  $f_v = 60,000$  psi, and the section has a 24-ft simple span. Is  $\epsilon_t \geq 0.005$ ?

![](_page_165_Figure_3.jpeg)

**Problem 5.17** Repeat Problem 5.16 if  $f'_c = 3000$  psi and three #11 bars are used in each web. (Ans. 486.1 ft-k)

#### **Design of T Beams**

**Problem 5.18** Determine the theoretical area of reinforcing steel required for the T beam shown if  $f_c' = 3000$  psi,  $f_y = 60,000 \text{ psi}$ ,  $M_u = 400 \text{ ft-k}$ , and L = 28 ft. Clear distance between flanges = 3 ft.

![](_page_165_Picture_7.jpeg)

**Problem 5.19** Repeat Problem 5.18 if  $M_u = 500$  ft-k. (Ans.  $4.12 \text{ in.}^2$ 

**Problem 5.20** Repeat Problem 5.18 if  $f_v = 50,000$  psi and  $f_c' = 5000 \text{ psi.}$ 

Problem 5.21 Determine the amount of reinforcing steel required for each T beam in the accompanying illustration if  $f_y = 60,000$  psi,  $f_c' = 4000$  psi, simple span = 24 ft, clear distance between stems = 3 ft,  $M_D = 200$  ft-k (includes effect of concrete weight), and  $M_L = 400$  ft-k. (Ans. 6.80 in.<sup>2</sup>)

![](_page_165_Figure_11.jpeg)

Problem 5.22 Select the tensile reinforcing needed for the T beams if the reinforced concrete is assumed to weigh 150 lb/ft<sup>3</sup> and a live floor load of 140 lb/ft<sup>2</sup> is to be supported. Assume 40-ft simple spans,  $f_v = 60,000$  psi, and  $f_c' = 3000$  psi.

![](_page_166_Figure_3.jpeg)

**Problem 5.23** With  $f_v = 60,000$  psi and  $f_c' = 4000$  psi, select the reinforcing for T beam AB for the floor system shown. Assume simple supports at A and B. The live load is to be 80 psf, while the dead load in addition to the concrete's weight is to be 100 psf. Concrete is assumed to weigh 150 lb/ft<sup>3</sup>. The slab is 4 in. thick, while d is 24 in. and  $b_w$  is 15 in. (Ans. 5.01 in.<sup>2</sup>, use 4 #10 bars)

![](_page_166_Figure_5.jpeg)

**Problem 5.24** Repeat Problem 5.23 if the span is 36 ft and the **Problem 5.26** live load is 120 psf.

**Problem 5.25** Prepare a flowchart for the design of tensilely reinforced T beams with  $\phi = 0.9$ .

#### **Analysis of Doubly Reinforced Beams**

For Problems 5.26 to 5.32, compute the design moment strengths  $\phi M_n$  of the beams shown if  $f_v = 60,000 \text{ psi}$  and  $f_c' = 4000$  psi. Check the maximum permissible  $A_s$  in each case to ensure ductile behavior.

![](_page_166_Figure_10.jpeg)

**Problem 5.27** (*Ans*. 679.1 ft-k)

![](_page_167_Figure_3.jpeg)

**Problem 5.28**

![](_page_167_Figure_5.jpeg)

**Problem 5.29** (*Ans*. 613.0 ft-k)

![](_page_167_Figure_7.jpeg)

**Problem 5.30**

![](_page_167_Figure_9.jpeg)

**Problem 5.31** (*Ans*. 737.1 ft-k)

![](_page_167_Figure_11.jpeg)

#### Problem 5.32

![](_page_168_Picture_3.jpeg)

**Problem 5.33** Compute the design moment strength,  $\phi M_n$ , of the beam shown. How much can this permissible moment be increased if four #9 bars are added to the top  $2\frac{1}{2}$  in. from the compression face,  $f'_c = 4000$  psi, and  $f_v = 60,000$  psi? (Ans. 690.2 ft-k, 35.5 ft-k)

![](_page_168_Picture_5.jpeg)

Problem 5.34 Repeat Problem 5.30 if three #10 bars are used in the top.

#### **Design of Doubly Reinforced Beams**

For Problems 5.35 to 5.38, determine the theoretical steel areas required for the sections shown. In each case, the dimensions are limited to the values shown. If compression steel is required, assume it will be placed 3 in. from the compression face,  $f_c' =$ 4000 psi, and  $f_v = 60,000$  psi.

**Problem 5.35** (Ans.  $A_s = 8.87 \text{ in.}^2$ ,  $A'_s = 1.77 \text{ in.}^2$ )

![](_page_168_Picture_10.jpeg)

Problem 5.36

![](_page_168_Picture_12.jpeg)

**Problem 5.37** (Ans.  $A_s = 8.02 \text{ in.}^2$ ,  $A'_s = 2.37 \text{ in.}^2$ )

![](_page_168_Picture_14.jpeg)

#### Problem 5.38

![](_page_169_Figure_3.jpeg)

**Problem 5.39** Prepare a flowchart for the design of doubly reinforced rectangular beams.

#### **Computer Problems**

Solve Problems 5.40 to 5.45 using the Chapter 5 spreadsheet.

**Problem 5.40** Problem 5.5

**Problem 5.41** Problem 5.7 (*Ans.* 721.4 ft-k)

**Problem 5.42** Problem 5.14

**Problem 5.43** Problem 5.21 (*Ans.*  $A_s = 6.80 \text{ in.}^2$ )

**Problem 5.44** Problem 5.27

**Problem 5.45** Problem 5.35 (*Ans.*  $A_s = 8.86 \text{ in.}^2$ ,  $A_s' = 1.78 \text{ in.}^2$ 

#### **Problems in SI Units**

For Problems 5.46 and 5.47, determine the design moment strengths of the beams shown in the accompanying illustrations if  $f_c'=28$  MPa and  $f_v=420$  MPa. Are the steel percentages in each case sufficient to ensure tensile behavior; that is,  $\epsilon_t \geq 0.005$ ?

#### Problem 5.46

![](_page_169_Figure_16.jpeg)

#### **Problem 5.47** (Ans. 1785 kN·m)

![](_page_169_Figure_18.jpeg)

For Problems 5.48 and 5.49, determine the area of reinforcing steel required for the T beams shown if *f <sup>c</sup>* = 28 MPa and *fy* = 420 MPa. Check *<sup>t</sup>* to see that it is ≥ 0.005.

#### **Problem 5.48**

![](_page_170_Figure_4.jpeg)

### **Problem 5.49** (*Ans*. 3750 mm2)

![](_page_170_Figure_6.jpeg)

For Problems 5.50 to 5.52, compute the design moment strengths of the beams shown if  $f_v = 420 \text{ MPa}$  and  $f_c' =$ 21 MPa. Check the maximum permissible  $A_s$  in each case to ensure ductile failure.  $E_s = 200\,000\,\mathrm{MPa}$ .

#### Problem 5.50

![](_page_171_Figure_4.jpeg)

**Problem 5.51** (*Ans.* 926.9 kN·m)

![](_page_171_Figure_6.jpeg)

Problem 5.52

![](_page_171_Figure_8.jpeg)

For Problems 5.53 and 5.54, determine the theoretical steel areas required for the sections shown. In each case, the dimensions are limited to the values shown. If compression steel is required, assume it will be placed 70 mm from the compression face.  $f_c'=28$  MPa,  $f_v=420$  MPa, and  $E_s=200\,$  000 MPa.

**Problem 5.53** (Ans.  $A_s = 6592 \text{ mm}^2$ ,  $A'_s = 2158 \text{ mm}^2$ )

![](_page_171_Figure_11.jpeg)

 $M_{u} = 1500 \text{ kN} \cdot \text{m}$ 

#### Problem 5.54

![](_page_171_Figure_14.jpeg)

$$M_u = 750 \text{ kN} \cdot \text{m}$$

#### More Detailed Problems

**Problem 5.55** Two-foot-wide, 4-in.-deep precast reinforced concrete slabs are to be used for a flat roof deck. The slabs are to be supported at their ends by precast rectangular beams spanning the 30 ft width of the roof (measured c. to c. of the supporting masonry walls). Select  $f_y$  and  $f_c'$ , design the slabs including their length, and design one of the supporting interior beams. Assume 30-psf roof live load and 6-psf built-up roof. (*One ans.* Use 12-in.  $\times$  24-in. beams with 3 #9 bars.)

**Problem 5.56** Repeat Problem 5.55 if the beams span is 40 ft and roof live load is 40 psf.

**Problem 5.57** For the same building considered in Problem 5.55, a 6-in.-deep cast-in-place concrete slab has been designed. It is to be supported by T beams cast integrally with the slabs. The architect says that the 30-ft-long T beams are to be supported by columns that are to be spaced 18 ft o.c. The building is to be used for light manufacturing (see Table 1.3 in Chapter 1 for live loads). Select  $f_y$  and  $f_c'$ , and design one of the interior T beams. (*One ans.* Use T beam web 12 in. wide, h = 32 in.,  $f_c' = 4$  ksi,  $f_y = 60$  ksi, and 4 #10 bars.)

**Problem 5.58** Repeat Problem 5.57 if the building is to be used for offices. The beam spans are to be 36 ft and the columns are to be placed 20 ft. o.c.

**Problem 5.59** Determine the lowest cost design for a tensilely reinforced concrete beam for the conditions that follow:  $f_y = 60 \text{ ksi}$ ,  $f_c' = 4 \text{ ksi}$ ,  $M_u = 400 \text{ ft-k}$ ,  $\ell = 24 \text{ ft}$ , h = d + 2.5 in.; concrete costs \$120 per yard and weighs 150 lb/ft<sup>3</sup>; and reinforcing bars cost \$0.95/lb and weigh 490 lb/ft<sup>3</sup>. Design the beam for the moment given with d = 1.5b, and calculate its cost per linear foot. Plot the cost per linear foot of beam (y-axis) versus steel percentage (x-axis). Then change the beam size and recalculate  $\rho$  and the new cost. Limit beam sizes to increments of 1 in. for b. Find the lowest-cost design and the corresponding value of  $\rho$ . (Ans. Approx.  $\rho = 0.0139$  and cost = \$26.03/ft.)

![](_page_172_Figure_8.jpeg)

**Problem 5.60** Repeat Problem 5.59 if d = 2b.

