# Strength Analysis of Beams **CHAPTER 3** According to ACI Code

### **3.1 Design Methods**

From the early 1900s until the early 1960s, nearly all reinforced concrete design in the United States was performed by the working-stress design method (also called *allowable-stress design* or *straight-line design*). In this method, frequently referred to as WSD, the dead and live loads to be supported, called *working loads* or *service loads*, were first estimated. Then the members of the structure were proportioned so that stresses calculated by a transformed area did not exceed certain permissible or allowable values.

After 1963, the ultimate-strength design method rapidly gained popularity because (1) it makes use of a more rational approach than does WSD, (2) it uses a more realistic consideration of safety, and (3) it provides more economical designs. With this method (now called *strength design*), the working dead and live loads are multiplied by certain load factors (equivalent to safety factors), and the resulting values are called *factored loads*. The members are then selected so they will theoretically just fail under the factored loads.

Even though almost all of the reinforced concrete structures the reader will encounter will be designed by the strength design method, it is still useful to be familiar with WSD for several reasons:

- **1.** Some designers use WSD for proportioning fluid-containing structures (such as water tanks and various sanitary structures). When these structures are designed by WSD, stresses are kept at fairly low levels, with the result that there is appreciably less cracking and less consequent leakage. (If the designer uses strength design and makes use of proper crack control methods, as described in Chapter 6, there should be few leakage problems.)
- **2.** The ACI method for calculating the moments of inertia to be used for deflection calculations requires some knowledge of the working-stress procedure.
- **3.** The design of prestressed concrete members is based not only on the strength method but also on elastic stress calculations at service load conditions.

The reader should realize that working-stress design has several disadvantages. When using the method, the designer has little knowledge about the magnitudes of safety factors against collapse; no consideration is given to the fact that different safety factors are desirable for dead and live loads; the method does not account for variations in resistances and loads, nor does it account for the possibility that as loads are increased, some increase at different rates than others.

In 1956, the ACI Code for the first time included ultimate-strength design, as an appendix, although the concrete codes of several other countries had been based on such considerations for several decades. In 1963, the code gave ultimate-strength design equal status with working-stress design; the 1971 code made the method the predominant method and only briefly mentioned the working-stress method. From 1971 until 1999, each issue of the code permitted designers to use working-stress design and set out certain provisions for its application. *Beginning with the 2002 code, however, permission is not included for using the method.*

Today's design method was called *ultimate-strength design* for several decades, but, as mentioned, the code now uses the term strength design. The strength for a particular reinforced concrete member is a value given by the code and is not necessarily the true ultimate strength of the member. Therefore, the more general term strength design is used whether beam strength, column strength, shear strength, or others are being considered.

### Advantages of Strength Design

Among the several advantages of the strength design method as compared to the no-longerpermitted working-stress design method are the following:

- 1. The derivation of the strength design expressions takes into account the nonlinear shape of the stress-strain diagram. When the resulting equations are applied, decidedly better estimates of load-carrying ability are obtained.
- 2. With strength design, a more consistent theory is used throughout the designs of reinforced concrete structures. For instance, with working-stress design the transformed-area or straight-line method was used for beam design, and a strength design procedure was used for columns.
- 3. A more realistic factor of safety is used in strength design. The designer can certainly estimate the magnitudes of the dead loads that a structure will have to support more accurately than he or she can estimate the live and environmental loads. With workingstress design, the same safety factor was used for dead, live, and environmental loads. This is not the case for strength design. For this reason, use of different load or safety factors in strength design for the different types of loads is a definite improvement.
- 4. A structure designed by the strength method will have a more uniform safety factor against collapse throughout. The strength method takes considerable advantage of higherstrength steels, whereas working-stress design did so only partly. The result is better economy for strength design.
- 5. The strength method permits more flexible designs than did the working-stress method. For instance, the percentage of steel may be varied quite a bit. As a result, large sections may be used with small percentages of steel, or small sections may be used with large percentages of steel. Such variations were not the case in the relatively fixed workingstress method. If the same amount of steel is used in strength design for a particular beam as would have been used with WSD, a smaller section will result. If the same size section is used as required by WSD, a smaller amount of steel will be required.

#### 3.3 Structural Safety

The structural safety of a reinforced concrete structure can be calculated with two methods. The first method involves calculations of the stresses caused by the working or service loads and their comparison with certain allowable stresses. Usually the safety factor against collapse when the working-stress method was used was said to equal the smaller of  $f_c'/f_c$  or  $f_v'/f_s$ .

The second approach to structural safety is the one used in strength design in which uncertainty is considered. The working loads are multiplied by certain load factors that are larger than 1. The resulting larger or factored loads are used for designing the structure. The values of the load factors vary depending on the type and combination of the loads.

To accurately estimate the ultimate strength of a structure, it is necessary to take into account the uncertainties in material strengths, dimensions, and workmanship. This is done by multiplying the theoretical ultimate strength (called the nominal strength herein) of each

![](_page_86_Picture_2.jpeg)

Water Tower Place, Chicago, Illinois, tallest reinforced concrete building in the United States (74 stories, 859 ft).

member by the *strength reduction factor*, φ, which is less than 1. These values generally vary from 0.90 for bending down to 0.65 for some columns.

In summary, the strength design approach to safety is to select a member whose computed ultimate load capacity multiplied by its strength reduction factor will at least equal the sum of the service loads multiplied by their respective load factors.

Member capacities obtained with the strength method are appreciably more accurate than member capacities predicted with the working-stress method.

### **3.4 Derivation of Beam Expressions**

Tests of reinforced concrete beams confirm that strains vary in proportion to distances from the neutral axis even on the tension sides and even near ultimate loads. Compression stresses vary approximately in a straight line until the maximum stress equals about 0.50*f <sup>c</sup>* . This is not the case, however, after stresses go higher. When the ultimate load is reached, the strain and stress variations are approximately as shown in Figure 3.1.

The compressive stresses vary from zero at the neutral axis to a maximum value at or near the extreme fiber. The actual stress variation and the actual location of the neutral axis vary somewhat from beam to beam, depending on such variables as the magnitude and history of past loadings, shrinkage and creep of the concrete, size and spacing of tension cracks, speed of loading, and so on.

If the shape of the stress diagram were the same for every beam, it would be possible to derive a single rational set of expressions for flexural behavior. Because of these stress variations, however, it is necessary to base the strength design on a combination of theory and test results.

Although the actual stress distribution given in Figure 3.2(b) may seem to be important, in practice any assumed shape (rectangular, parabolic, trapezoidal, etc.) can be used if the

![](_page_87_Figure_2.jpeg)

**FIGURE 3.1** Nonlinear stress distribution at ultimate conditions.

resulting equations compare favorably with test results. The most common shapes proposed are the rectangle, parabola, and trapezoid, with the rectangular shape used in this text as shown in Figure 3.2(c) being the most common one.

If the concrete is assumed to crush at a strain of about 0.003 (which is a little conservative for most concretes) and the steel to yield at  $f_{v}$ , it is possible to make a reasonable derivation of beam formulas without knowing the exact stress distribution. However, it is necessary to know the value of the total compression force and its centroid.

Whitney<sup>1</sup> replaced the curved stress block [Figure 3.2(b)] with an equivalent rectangular block of intensity  $0.85f'_c$  and depth  $\alpha = \beta_1 c$ , as shown in Figure 3.2(c). The area of this rectangular block should equal that of the curved stress block, and the centroids of the two blocks should coincide. Sufficient test results are available for concrete beams to provide the depths of the equivalent rectangular stress blocks. The values of  $\beta_1$  given by the code (10.2.7.3) are intended to give this result. For  $f_c'$  values of 4000 psi or less,  $\beta_1 = 0.85$ , and it is to be reduced continuously at a rate of 0.05 for each 1000-psi increase in  $f'_c$  above 4000 psi. Their value may not be less than 0.65. The values of  $\beta_1$  are reduced for high-strength concretes primarily because of the shapes of their stress-strain curves (see Figure 1.1 in Chapter 1).

For concretes with  $f_c' > 4000$  psi,  $\beta_1$  can be determined with the following formula:

$$\beta_1 = 0.85 - \left(\frac{f_c' - 4000 \text{ psi}}{1000}\right)(0.05) \ge 0.65$$

![](_page_87_Picture_9.jpeg)

**FIGURE 3.2** Some possible stress distribution shapes.

<sup>&</sup>lt;sup>1</sup> Whitney, C. S., 1942, "Plastic Theory of Reinforced Concrete Design," *Transactions ASCE*, 107, pp. 251–326.

In SI units,  $\beta_1$  is to be taken equal to 0.85 for concrete strengths up to and including 30 MPa. For strengths above 30 MPa,  $\beta_1$  is to be reduced continuously at a rate of 0.05 for each 7 MPa of strength in excess of 30 MPa but shall not be taken less than 0.65.

For concretes with  $f_c' > 30$  MPa,  $\beta_1$  can be determined with the following expression:

$$\beta_1 = 0.85 - 0.008 (f_c' - 30 \text{ MPa}) \ge 0.65$$

Based on these assumptions regarding the stress block, statics equations can easily be written for the sum of the horizontal forces and for the resisting moment produced by the internal couple. These expressions can then be solved separately for a and for the moment,  $M_n$ .

A very clear statement should be made here regarding the term  $M_n$  because it otherwise can be confusing to the reader.  $M_n$  is defined as the theoretical or nominal resisting moment of a section. In Section 3.3, it was stated that the usable strength of a member equals its theoretical strength times the strength reduction factor, or, in this case,  $\phi M_n$ . The usable flexural strength of a member,  $\phi M_n$ , must at least be equal to the calculated factored moment,  $M_u$ , caused by the factored loads

$$\phi M_n \geq M_u$$

For writing the beam expressions, reference is made to Figure 3.3. Equating the horizontal forces C and T and solving for a, we obtain

$$0.85f'_c ab = A_s f_y$$

$$a = \frac{A_s f_y}{0.85f'_c b} = \frac{\rho f_y d}{0.85f'_c}, \text{ where } \rho = \frac{A_s}{bd} = \text{ percentage of tensile steel}$$

Because the reinforcing steel is limited to an amount such that it will yield well before the concrete reaches its ultimate strength, the value of the nominal moment,  $M_n$ , can be written as

$$M_n = T\left(d - \frac{a}{2}\right) = A_s f_y\left(d - \frac{a}{2}\right)$$

and the usable flexural strength is

$$\phi M_n = \phi A_s f_y \left( d - \frac{a}{2} \right) \tag{Eq. 3-1}$$

If we substitute into this expression the value previously obtained for a (it was  $\rho f_y d/0.85 f_c'$ ), replace  $A_s$  with  $\rho b d_s$ , and equate  $\phi M_n$  to  $M_u$ , we obtain the following expression:

$$\phi M_n = M_u = \phi b d^2 f_y \rho \left( 1 - \frac{\rho f_y}{1.7 f_c'} \right)$$
 (Eq. 3-2)

![](_page_88_Figure_16.jpeg)

FIGURE 3.3 Beam internal forces at ultimate conditions.

Replacing  $A_s$  with  $\rho bd$  and letting  $R_n = M_n/\phi bd^2$ , we can solve this expression for  $\rho$  (the percentage of steel required for a particular beam) with the following results:

$$\rho = \frac{0.85f_c'}{f_v} \left( 1 - \sqrt{1 - \frac{2R_n}{0.85f_c'}} \right)$$
 (Eq. 3-3)

Instead of substituting into this equation for  $\rho$  when rectangular sections are involved, the reader will find Tables A.8 to A.13 in Appendix A of this text to be quite convenient. (For SI units, refer to Tables B.8 and B.9 in Appendix B.) Another way to obtain the same information is to refer to Graph 1 in Appendix A. The user, however, will have some difficulty in reading this small-scale graph accurately. This expression for  $\rho$  is also very useful for tensilely reinforced rectangular sections that do not fall into the tables. An iterative technique for determination of reinforcing steel area is also presented later in this chapter.

#### **Strains in Flexural Members**

As previously mentioned, Section 10.2.2 of the code states that the strains in concrete members and their reinforcement are to be assumed to vary directly with distances from their neutral axes. (This assumption is not applicable to deep flexural members whose depths over their clear spans are greater than 0.25.) Furthermore, in Section 10.2.3 the code states that the maximum usable strain in the extreme compression fibers of a flexural member is to be 0.003. Finally, Section 10.3.3 states that for Grade 60 reinforcement and for all prestressed reinforcement we may set the strain in the steel equal to 0.002 at the balanced condition. (Theoretically, for 60,000-psi steel, it equals  $f_v/E_s = 60,000 \text{ psi}/29 \times 10^6 \text{ psi} = 0.00207.$ 

In Section 3.4, a value was derived for a, the depth of the equivalent stress block of a beam. It can be related to c with the factor  $\beta_1$  also given in that section:

$$a = \frac{A_s f_y}{0.85 f_c' b} = \beta_1 c$$

Then the distance c from the extreme concrete compression fibers to the neutral axis is

$$c = \frac{a}{\beta_1}$$

In Example 3.1, the values of a and c are determined for the beam previously considered in Example 2.8, and by straight-line proportions the strain in the reinforcing  $\epsilon_i$  is computed.

#### Example 3.1

Determine the values of a, c, and  $\epsilon_t$  for the beam shown in Figure 3.4.  $f_v = 60,000$  psi and  $f_{\rm c}' = 3000 \, {\rm psi}.$ 

#### SOLUTION

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{(3.00 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (3 \text{ ksi}) (14 \text{ in.})} = \frac{5.04 \text{ in.}}{0.85 f_c' b}$$

 $\beta_1 = 0.85$  for 3000-psi concrete

![](_page_90_Figure_2.jpeg)

**FI GU RE 3.4** Beam cross section for Example 3.1.

$$c = \frac{a}{\beta_1} = \frac{5.04 \text{ in.}}{0.85} = \underline{\frac{5.93 \text{ in.}}{60.003}}$$

$$\epsilon_t = \frac{d - c}{c}(0.003) = \left(\frac{21 \text{ in.} - 5.93 \text{ in.}}{5.93 \text{ in.}}\right)(0.003) = \underline{0.00762}$$

This value of strain is much greater than the yield strain of 0.002. This is an indication of ductile behavior of the beam, because the steel is well into its yield plateau before concrete crushes.

### **3.6 Balanced Sections, Tension-Controlled Sections, and Compression-Controlled or Brittle Sections**

A beam that has a *balanced steel ratio* is one for which the tensile steel will theoretically just reach its yield point at the same time the extreme compression concrete fibers attain a strain equal to 0.003. Should a flexural member be so designed that it has a balanced steel ratio or be a member whose compression side controls (i.e., if its compression strain reaches 0.003 before the steel yields), the member can suddenly fail without warning. As the load on such a member is increased, its deflections will usually not be particularly noticeable, even though the concrete is highly stressed in compression and failure will probably occur without warning to users of the structure. These members are *compression controlled* and are referred to as *brittle members*. Obviously, such members must be avoided.

The code, in Section 10.3.4, states that members whose computed tensile strains are equal to or greater than 0.0050 at the same time the concrete strain is 0.003 are to be referred to as *tension-controlled sections*. For such members, the steel will yield before the compression side crushes and deflections will be large, giving users warning of impending failure. Furthermore, members with *<sup>t</sup>* ≥ 0.005 are considered to be fully ductile. The ACI chose the 0.005 value for *<sup>t</sup>* to apply to all types of steel permitted by the code, whether regular or prestressed. The code further states that members that have net steel strains or *<sup>t</sup>* values between *<sup>y</sup>* and 0.005 are in a transition region between compression-controlled and tension-controlled sections. For Grade 60 reinforcing steel, which is quite common, *<sup>y</sup>* is approximated by 0.002.

### **3.7 Strength Reduction or** *φ* **Factors**

Strength reduction factors are used to take into account the uncertainties of material strengths, inaccuracies in the design equations, approximations in analysis, possible variations in dimensions of the concrete sections and placement of reinforcement, the importance of members in

the structures of which they are part, and so on. The code (9.3) prescribes  $\phi$  values or strength reduction factors for most situations. Among these values are the following:

0.90 for tension-controlled beams and slabs

0.75 for shear and torsion in beams

0.65 or 0.75 for columns

0.65 or 0.75 to 0.9 for columns supporting very small axial loads

0.65 for bearing on concrete

The sizes of these factors are rather good indications of our knowledge of the subject in question. For instance, calculated nominal moment capacities in reinforced concrete members seem to be quite accurate, whereas computed bearing capacities are more questionable.

For ductile or tension-controlled beams and slabs where  $\epsilon_t \geq 0.005$ , the value of  $\phi$  for bending is 0.90. Should  $\epsilon_i$  be less than 0.005, it is still possible to use the sections if  $\epsilon_i$  is not less than certain values. This situation is shown in Figure 3.5, which is similar to Figure R.9.3.2 in the ACI Commentary to the 2011 code.

Members subject to axial loads equal to or less than  $0.10f'_cA_{\varrho}$  may be used only when  $\epsilon_i$  is no lower than 0.004 (ACI Section 10.3.5). An important implication of this limit is that reinforced concrete beams must have a tension strain of at least 0.004. Should the members be subject to axial loads  $\geq 0.10 f'_i A_o$ , then  $\epsilon_i$  is not limited. When  $\epsilon_i$  values fall between 0.002 and 0.005, they are said to be in the transition range between tension-controlled and compressioncontrolled sections. In this range,  $\phi$  values will fall between 0.65 or 0.70 and 0.90, as shown in Figure 3.5. When  $\epsilon_t \leq 0.002$ , the member is compression controlled, and the column  $\phi$ factors apply.

The procedure for determining  $\phi$  values in the transition range is described later in this section. You must clearly understand that the use of flexural members in this range is usually uneconomical, and it is probably better, if the situation permits, to increase member depths and/or decrease steel percentages until  $\epsilon_t$  is equal to or larger than 0.005. If this is done, not only will  $\phi$  values equal 0.9 but also steel percentages will not be so large as to cause crowding of reinforcing bars. The net result will be slightly larger concrete sections, with consequent smaller deflections. Furthermore, as you will learn in subsequent chapters, the bond of the reinforcing to the concrete will be increased as compared to cases where higher percentages of steel are used.

![](_page_91_Figure_12.jpeg)

**FIGURE 3.5** Variation of  $\phi$  with net tensile strain  $\epsilon$ , and c/d, for Grade 60 reinforcement and for prestressing steel.

We have computed values of steel percentages for different grades of concrete and steel for which  $\epsilon_t$  will exactly equal 0.005 and present them in Appendix Tables A.7 and B.7 of this textbook. It is desirable, under ordinary conditions, to design beams with steel percentages that are no larger than these values, and we have shown them as suggested maximum percentages to be used.

The horizontal axis of Figure 3.5 gives values also for  $c/d_t$  ratios. If  $c/d_t$  for a particular flexural member is  $\leq 0.375$ , the beam will be ductile, and if it is > 0.600, it will be brittle. In between is the transition range. You may prefer to compute  $c/d_t$  for a particular beam to check its ductility rather than computing  $\rho$  or  $\epsilon_t$ . In the transition region, interpolation to determine  $\phi$  using  $c/d_t$  instead of  $\epsilon_t$ , when  $0.375 < c/d_t < 0.600$ , can be performed using the equations

$$\phi = 0.75 + 0.15 \left( \frac{1}{c/d_t} - \frac{5}{3} \right) \qquad \textit{for spiral members}$$
 
$$\phi = 0.65 + 0.25 \left( \frac{1}{c/d_t} - \frac{5}{3} \right) \qquad \textit{for other members}$$

The equations for  $\phi$  here and in Figure 3.5 are for the special case where  $f_y = 60$  ksi and for prestressed concrete. For other cases, replace 0.002 with  $\epsilon_y = f_y/E_s$ . Figure 10.25 in Chapter 10 shows Figure 3.5 for the general case, where  $\epsilon_y$  is not assumed to be 0.002.

The resulting general equations in the range  $\epsilon_v < \epsilon_t < 0.005$  are

$$\phi = 0.75 + (\epsilon_t - \epsilon_y) \frac{0.15}{(0.005 - \epsilon_y)}$$
 for spiral members

and

$$\phi = 0.65 + (\epsilon_t - \epsilon_y) \frac{0.25}{(0.005 - \epsilon_y)}$$
 for other members

The impact of the variable  $\phi$  factor on moment capacity is shown in Figure 3.6. The two curves show the moment capacity with and without the application of the  $\phi$  factor. Point A corresponds to a tensile strain,  $\epsilon_t$ , of 0.005 and  $\rho=0.0181$  (Appendix A, Table A.7). This is the largest value of  $\rho$  for  $\phi=0.9$ . Above this value of  $\rho$ ,  $\phi$  decreases to as low as 0.65 as shown by point B, which corresponds to  $\epsilon_t$  of  $\epsilon_y$ . ACI 10.3.5 requires  $\epsilon_t$  not be less than 0.004 for flexural members with compressive axial loads less than 0.10  $f_m'A_g$ . This situation corresponds to point C in Figure 3.6. The only allowable range for  $\rho$  is below point C. From the figure, it is clear that little moment capacity is gained in adding steel area above point A. The variable  $\phi$  factor provisions essentially permit a constant value of  $\phi M_n$  when  $\epsilon_t$  is less

![](_page_92_Figure_11.jpeg)

**FIGURE 3.6** Moment capacity versus  $\rho$ .

than 0.005. It is important for the designer to know this because often actual bar selections result in more steel area than theoretically required. If the slope between points A and C were negative, the designer could not use a larger area. Knowing the slope is slightly positive, the designer can use the larger bar area with confidence that the design capacity is not reduced.

For values of  $f_v$  of 75 ksi and higher, the slope between point A and B in Figure 3.6 is actually negative. It is therefore especially important, when using high-strength reinforcing steel, to verify your final design to be sure the bars you have selected do not result in a moment capacity less than the design value.

Continuing our consideration of Figure 3.5, you can see that when  $\epsilon$ , is less than 0.005, the values of  $\phi$  will vary along a straight line from their 0.90 value for ductile sections to 0.65 at balanced conditions where  $\epsilon_i$  is 0.002. Later you will learn that  $\phi$  can equal 0.75 rather than 0.65 at this latter strain situation if spirally reinforced sections are being considered.

#### 3.8 Minimum Percentage of Steel

A brief discussion of the modes of failure that occur for various reinforced beams was presented in Section 3.6. Sometimes, because of architectural or functional requirements, beam dimensions are selected that are much larger than are required for bending alone. Such members theoretically require very small amounts of reinforcing.

Actually, another mode of failure can occur in very lightly reinforced beams. If the ultimate resisting moment of the section is less than its cracking moment, the section will fail immediately when a crack occurs. This type of failure may occur without warning. To prevent such a possibility, the ACI (10.5.1) specifies a certain minimum amount of reinforcing that must be used at every section of flexural members where tensile reinforcing is required by analysis, whether for positive or negative moments. In the following equations,  $b_w$  represents the web width of beams.

$$A_{s \min} = \frac{3\sqrt{f_c'}}{f_y} b_w d$$
 nor less than  $\frac{200b_w d}{f_y}$  (ACI Equation 10-3)

In SI units, these expressions are 
$$\left(\frac{\sqrt{f_c'}}{4f_y}\right)b_wd$$
 and  $\left(\frac{1.4b_wd}{f_y}\right)$ , respectively.

The  $(200b_w d)/f_v$  value was obtained by calculating the cracking moment of a plain concrete section and equating it to the strength of a reinforced concrete section of the same size, applying a safety factor of 2.5 and solving for the steel required. It has been found, however, that when  $f_c'$  is higher than about 5000 psi, this value may not be sufficient. Thus, the  $(3\sqrt{f_c'/f_v})b_w d$  value is also required to be met, and it will actually control when  $f_c'$  is greater than 4440 psi.

This ACI equation (10-3) for the minimum amount of flexural reinforcing can be written as a percentage, as follows:

$$\rho_{\min} \text{ for flexure} = \frac{3\sqrt{f_c'}}{f_y} \ge \frac{200}{f_y}$$

Values of  $\rho_{\min}$  for flexure have been calculated by the authors and are shown for several grades of concrete and steel in Appendix A, Table A.7 of this text. They are also included in Tables A.8 to A.13. (For SI units, the appropriate tables are in Appendix B, Tables B.7 to B.9.)

![](_page_94_Picture_2.jpeg)

Wastewater treatment plant, Fountain Hills, Arizona.

Section 10.5.3 of the code states that the preceding minimums do not have to be met if the area of the tensile reinforcing furnished at every section is at least one-third greater than the area required by moment. Furthermore, ACI Section 10.5.4 states that for slabs and footings of uniform thickness, the minimum area of tensile reinforcing in the direction of the span is that specified in ACI Section 7.12 for shrinkage and temperature steel which is much lower. When slabs are overloaded in certain areas, there is a tendency for those loads to be distributed laterally to other parts of the slab, thus substantially reducing the chances of sudden failure. This explains why a reduction of the minimum reinforcing percentage is permitted in slabs of uniform thickness. Supported slabs, such as slabs on grade, are not considered to be structural slabs in this section unless they transmit vertical loads from other parts of the structure to the underlying soil.

### 3.9 Balanced Steel Percentage

In this section, an expression is derived for  $\rho_b$ , the percentage of steel required for a balanced design. At ultimate load for such a beam, the concrete will theoretically fail (at a strain of 0.00300), and the steel will simultaneously yield (see Figure 3.7).

The neutral axis is located by the triangular strain relationships that follow, noting that  $E_s = 29 \times 10^6$  psi for the reinforcing bars:

$$\frac{c}{d} = \frac{0.00300}{0.00300 + (f_y/E_s)} = \frac{0.00300}{0.003 + (f_y/29 \times 10^6 \text{ psi})}$$

This expression is rearranged and simplified, giving

$$c = \frac{87,000}{87,000 + f_y} d$$

![](_page_95_Picture_2.jpeg)

![](_page_95_Picture_3.jpeg)

FIGURE 3.7 Balanced conditions.

In Section 3.4 of this chapter, an expression was derived for depth of the compression stress block, a, by equating the values of C and T. This value can be converted to the neutral axis depth, c, by dividing it by  $\beta_1$ :

$$a = \frac{\rho f_y d}{0.85 f_c'}$$

$$c = \frac{a}{\beta_1} = \frac{\rho f_y d}{0.85 \beta_1 f_c'}$$

Two expressions are now available for c, and they are equated to each other and solved for the percentage of steel. This is the balanced percentage,  $\rho_h$ :

$$\frac{\rho f_y d}{0.85 \beta_1 f_c'} = \frac{87,000}{87,000 + f_y} d$$

$$\rho_b = \left(\frac{0.85 \beta_1 f_c'}{f_y}\right) \left(\frac{87,000}{87,000 + f_y}\right)$$

or in SI units 
$$\left(\frac{0.85\beta_1 f_c'}{f_y}\right) \left(\frac{600}{600 + f_y}\right)$$

Values of  $\rho_b$  can easily be calculated for different values of  $f_c'$  and  $f_v$  and tabulated for U.S. customary units as shown in Appendix A, Table A.7. For SI units, it's Appendix B, Table B.7.

Previous codes (1963-1999) limited flexural members to 75% of the balanced steel ratio,  $\rho_b$ . However, this approach was changed in the 2002 code to the new philosophy explained in Section 3.7, whereby the member capacity is penalized by reducing the  $\phi$  factor when the strain in the reinforcing steel at ultimate is less than 0.005.

#### 3.10 **Example Problems**

Examples 3.2 to 3.4 present the computation of the design moment capacities of three beams using the ACI Code limitations. Remember that, according to the code (10.3.5), beams whose axial load is less than  $0.10f_c/A_v$  may not, when loaded to their nominal strengths, have net tensile calculated strains less than 0.004.

### Example 3.2

Determine the ACI design moment capacity,  $\phi M_n$ , of the beam shown in Figure 3.8 if  $f_c'=4000$  psi and  $f_y=60{,}000$  psi.

#### SOLUTION

#### **Checking Steel Percentage**

$$\rho = \frac{A_{\rm s}}{bd} = \frac{4.00~{\rm in.}^2}{(15~{\rm in.})\,(24~{\rm in.})} = 0.0111$$
 
$$> \rho_{\rm min} = 0.0033 \} \qquad \text{both from}$$
 
$$< \rho_{\rm max} = 0.0181 \} \qquad \text{Appendix A, Table A.7}$$
 
$$a = \frac{A_{\rm s}f_y}{0.85f_c'b} = \frac{(4.00~{\rm in.}^2)\,(60,000~{\rm psi})}{(0.85)(4000~{\rm psi})\,(15~{\rm in.})} = 4.71~{\rm in.}$$
 
$$\beta_1 = 0.85~{\rm for}~4000~{\rm psi}~{\rm concrete}$$
 
$$c = \frac{a}{\beta_1} = \frac{4.71~{\rm in.}}{0.85} = 5.54~{\rm in.}$$

#### **Drawing Strain Diagram (Figure 3.9)**

$$\epsilon_t = \frac{d-c}{c}(0.003) = \frac{18.46 \text{ in.}}{5.54 \text{ in.}}(0.003) = 0.0100$$

$$> 0.005 \qquad \therefore \text{ tension controlled}$$

$$M_n = A_s f_y \left( d - \frac{a}{2} \right) = (4.00 \text{ in.}^2) (60 \text{ ksi}) \left( 24 \text{ in.} - \frac{4.71 \text{ in.}}{2} \right)$$

$$= 5194.8 \text{ in-k} = 432.9 \text{ ft-k}$$

$$\phi M_n = (0.9) (432.9 \text{ ft-k}) = \underline{389.6 \text{ ft-k}}$$

![](_page_96_Figure_9.jpeg)

![](_page_96_Figure_10.jpeg)

![](_page_96_Figure_11.jpeg)

**FIGURE 3.9** Neutral axis location for Example 3.2.

#### Example 3.3

Determine the ACI design moment capacity,  $\phi M_n$ , of the beam shown in Figure 3.10 if  $f_c' = 4000 \text{ psi and } f_y = 60,000 \text{ psi.}$ 

#### SOLUTION

#### **Checking Steel Percentage**

$$\rho = \frac{A_s}{bd} = \frac{4.68 \text{ in.}^2}{(12 \text{ in.})(15 \text{ in.})} = 0.026 > \rho_{\text{min}} = 0.0033$$

 $> \rho_{\text{max}} = 0.0181$  (from Appendix A, Table A.7). As a result, we know that  $\epsilon_t$  will be < 0.005.

#### Computing Value of $\epsilon_t$

$$a = \frac{A_{s}f_{y}}{0.85f_{c}'b} = \frac{(4.68 \text{ in.}^{2}) (60,000 \text{ psi})}{(0.85) (4000 \text{ psi}) (12 \text{ in.})} = 6.88 \text{ in.}$$

$$\beta_{1} = 0.85 \text{ for } 4000 \text{ psi concrete}$$

$$c = \frac{a}{\beta_{1}} = \frac{6.88 \text{ in.}}{0.85} = 8.09 \text{ in.}$$

$$\epsilon_{t} = \frac{d-c}{c} (0.003) = \frac{15 \text{ in.} - 8.09 \text{ in.}}{8.09 \text{ in.}} (0.003)$$

$$= 0.00256 < 0.004$$

:. Section is not ductile and may not be used as per ACI Section 10.3.5.

![](_page_97_Figure_11.jpeg)

**FIGURE 3.10** Beam cross section for Example 3.3.

#### Example 3.4

Determine the ACI design moment capacity,  $\phi M_n$ , for the beam of Figure 3.11 if  $f_c'=4000~\mathrm{psi}$ and  $f_v = 60,000 \text{ psi.}$ 

#### SOLUTION

#### **Checking Steel Percentage**

$$\rho = \frac{A_{\rm s}}{bd} = \frac{3.00~{\rm in.}^2}{(10~{\rm in.})(15~{\rm in.})} = 0.020 > \rho_{\rm min} = 0.0033$$
 but also  $<\rho_{\rm max} = 0.0181~{\rm (for}~\epsilon_t = 0.005)$ 

#### Computing Value of $\epsilon_t$

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{(3.00 \text{ in.}^2) (60,000 \text{ psi})}{(0.85) (4000 \text{ psi}) (10 \text{ in.})} = 5.29 \text{ in.}$$

 $\beta_1 = 0.85$  for 4000 psi concrete

$$c = \frac{a}{\beta_1} = \frac{5.29 \text{ in.}}{0.85} = 6.22 \text{ in.}$$

$$\epsilon_t = \frac{d-c}{c}(0.003) = \left(\frac{15 \text{ in.} - 6.22 \text{ in.}}{6.22 \text{ in.}}\right)(0.003) = 0.00423 > 0.004 \text{ and } < 0.005$$

.. Beam is in transition zone and

$$\phi$$
 (from Figure 3.5) = 0.65 + (0.00423 - 0.002)  $\left(\frac{250}{3}\right)$  = 0.836

$$M_n = A_s f_y \left( d - \frac{a}{2} \right) = (3.00 \text{ in.}^2) (60 \text{ ksi}) \left( 15 \text{ in.} - \frac{5.29 \text{ in.}}{2} \right) = 2223.9 \text{ in-k} = 185.3 \text{ ft-k}$$

$$\phi M_n = (0.836) (185.3 \text{ ft-k}) = \underline{154.9 \text{ ft-k}}$$

![](_page_98_Figure_10.jpeg)

FIGURE 3.11 Beam cross section for Example 3.4.

### 3.11 Computer Examples

#### Example 3.5

Repeat Example 3.2 using the Excel spreadsheet provided for Chapter 3.

#### **SOLUTION**

Open the Chapter 3 spreadsheet, and open the Rectangular Beam worksheet. Enter values only in the cells highlighted yellow (only in the Excel spreadsheet, not the printed example). The final result is  $\phi M_n = 389.6$  ft-k (same answer as Example 3.2).

#### Example 3.6

Repeat Example 3.3 using the Excel spreadsheet provided for Chapter 3.

#### **SOLUTION**

Open the Chapter 3 spreadsheet and the Rectangular Beam worksheet. Enter values only in the cells highlighted yellow. The spreadsheet displays a message, ''code violation ...too much steel.'' This is an indication that the beam violates ACI Section 10.3.5 and is not ductile. This beam is not allowed by the ACI Code.

#### Example 3.7

Repeat Example 3.4 using the Excel spreadsheet provided for Chapter 3.

#### **SOLUTION**

Open the Chapter 3 spreadsheet and the Rectangular Beam worksheet. Enter values only in the cells highlighted yellow. The final result is φ*Mn* = 154.5 ft-k (nearly the same answer as Example 3.4). The φ factor is also nearly the same as Example 3.4 (0.0834 compared with 0.0836). The difference is the result of the spreadsheet using the more general value for *<sup>y</sup>* of *fy*/*Es* = 0.00207 instead of the approximate value of 0.002 permitted by the code for Grade 60 reinforcing steel. A difference of this magnitude is not important, as discussed in Section 1.25, ''Calculation Accuracy.''

### **PROBLEMS**

**Problem 3.1** What are the advantages of the strength design method as compared to the allowable stress or alternate design method?

**Problem 3.2** What is the purpose of strength reduction factors? Why are they smaller for columns than for beams?

**Problem 3.3** What are the basic assumptions of the strength design theory?

**Problem 3.4** Why does the ACI Code specify that a certain minimum percentage of reinforcing be used in beams?

**Problem 3.5** Distinguish between tension-controlled and compression-controlled beams.

**Problem 3.6** Explain the purpose of the minimum cover requirements for reinforcing specified by the ACI Code.

For Problems 3.7 to 3.9, determine the values of *<sup>t</sup>* , φ, and φ*Mn* for the sections shown.

**Problem 3.7** (*Ans.* φ*Mn* = 379.1 ft-k)

![](_page_99_Figure_19.jpeg)

#### **Problem 3.8**

![](_page_100_Figure_3.jpeg)

**Problem 3.9** (*Ans. <sup>t</sup>* = 0.00408, φ = 0.797, φ*Mn* = 1320.7 ft-k)

![](_page_100_Figure_5.jpeg)

#### **Problem 3.10**

![](_page_100_Figure_7.jpeg)

