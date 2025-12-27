# Slender Columns **CHA PTER 11**

### **11.1 Introduction**

When a column bends or deflects laterally an amount , its axial load will cause an increased column moment equal to *P*. This moment will be superimposed onto any moments already in the column. Should this *P* moment be of such magnitude as to reduce the axial load capacity of the column significantly, the column will be referred to as a *slender column*.

Section 10.10.2 of the code states that the design of a compression member should, desirably, be based on a theoretical analysis of the structure that takes into account the effects of axial loads, moments, deflections, duration of loads, varying member sizes, end conditions, and so on. If such a theoretical procedure is not used, the code (10.10.5) provides an approximate method for determining slenderness effects. This method, which is based on the factors just mentioned for an "exact" analysis, results in a moment magnifier, δ, which is to be multiplied by the larger moment at the end of the column denoted as *M*2, and that value is used in design. If bending occurs about both axes, δ is to be computed separately for each direction and the values obtained multiplied by the respective moment values.

### **11.2 Nonsway and Sway Frames**

For this discussion, it is necessary to distinguish between frames without sidesway and those with sidesway. In the ACI Code, these are referred to respectively as *nonsway frames* and *sway frames*.

For the building story in question, the columns in nonsway frames must be designed according to Section 10.10.6 of the code, while the columns of sway frames must be designed according to Section 10.10.7. As a result, it is first necessary to decide whether we have a nonsway frame or a sway frame. *You must realize that you will rarely find a frame that is completely braced against swaying or one that is completely unbraced against swaying. Therefore*, *you are going to have to decide which way to handle it.*

The question may possibly be resolved by examining the lateral stiffness of the bracing elements for the story in question. You may observe that a particular column is located in a story where there is such substantial lateral stiffness provided by bracing members, shear walls, shear trusses, and so on that any lateral deflections occurring will be too small to affect the strength of the column appreciably. You should realize that, while examining a particular structure, there may be some nonsway stories and some sway stories.

If we cannot tell by inspection whether we have a nonsway frame or a sway frame, the code provides two ways of making a decision. First, in ACI Section 10.10.5.1, a story in a frame is said to be a nonsway one if the increase in column end moments from second-order effects is 5% or less of the first-order end moments.

The second method for determining whether a particular frame is braced or unbraced is given in the code (10.10.5.2). If the value of the so-called *stability index* (which follows) is ≤ 0.05, the commentary states that the frame may be classified as a nonsway one. (Should *Vu* be equal to zero, this method will not apply.)

$$Q = \frac{\sum P_u \Delta_o}{V_u \ell_c}$$
 (ACI Equation 10-10)

where

 $\Sigma P_{\mu}$  = total factored vertical load for all of the columns on the story in question

 $\Delta_{o}$  = the elastically determined first-order lateral deflection from  $V_{u}$  at the top of the story in question with respect to the bottom of that story

 $V_{\mu}$  = the total factored horizontal shear for the story in question

 $\ell_c$  = the height of a compression member in a frame measured from center to center of the frame joints

Despite these suggestions from the ACI, the individual designer is going to have to make decisions as to what is adequate bracing and what is not, depending on the presence of structural walls and other bracing items. For the average-size reinforced concrete building, load eccentricities and slenderness values will be small, and frames will be considered to be braced. Certainly, however, it is wise in questionable cases to err on the side of the unbraced.

#### 11.3 Slenderness Effects

The slenderness of columns is based on their geometry and on their lateral bracing. As their slenderness increases, their bending stresses increase, and thus buckling may occur. Reinforced concrete columns generally have small slenderness ratios. As a result, they can usually be designed as short columns without strength reductions because of slenderness. If slenderness effects are considered small, then columns can be considered "short" and can be designed according to Chapter 10. However, if they are "slender," the moment for which the column must be designed is increased or magnified. Once the moment is magnified, the column is then designed according to Chapter 10 using the increased moment.

Several items involved in the calculation of slenderness ratios are discussed in the next several paragraphs. These include unsupported column lengths, effective length factors, radii of gyration, and the ACI Code requirements. The ACI Code (10.10.2.1) limits second-order effects to not more than 40% of first-order effects.

#### **Unsupported Lengths**

The length used for calculating the slenderness ratio of a column,  $\ell_u$ , is its unsupported length. This length is considered to be equal to the clear distance between slabs, beams, or other members that provide lateral support to the column. If haunches or capitals (see Figure 16.1 in Chapter 16) are present, the clear distance is measured from the bottoms of the capitals or haunches.

#### **Effective Length Factors**

To calculate the slenderness ratio of a particular column, it is necessary to estimate its effective length. This is the distance between points of zero moment in the column. For this initial discussion, it is assumed that no sidesway or joint translation is possible. Sidesway or joint translation means that one or both ends of a column can move laterally with respect to each other.

If there were such a thing as a perfectly pinned end column, its effective length would be its unsupported length, as shown in Figure 11.1(a). The effective length factor, k, is the number that must be multiplied by the column's unsupported length to obtain its effective length. For a perfectly pinned end column, k = 1.0.

![](_page_338_Picture_2.jpeg)

Round columns.

![](_page_338_Figure_4.jpeg)

FIGURE 11.1 Effective lengths for columns in braced frames (sidesway prevented).

Columns with different end conditions have entirely different effective lengths. For instance, if there were such a thing as a perfectly fixed end column, its points of inflection (or points of zero moment) would occur at its one-fourth points, and its effective length would be l*<sup>u</sup>* /2, as shown in Figure 11.1(b). As a result, its *k* value would equal 0.5.

Obviously, the smaller the effective length of a particular column, the smaller its danger of buckling and the greater its load-carrying capacity. Figure 11.1(c) shows a column with one end fixed and one end pinned. The *k* factor for this column is approximately 0.70.

The concept of effective lengths is simply a mathematical method of taking a column—whatever its end and bracing conditions—and replacing it with an equivalent pinned end-braced column. A complex buckling analysis could be made for a frame to determine the critical stress in a particular column. The *k* factor is determined by finding the pinned end column with an equivalent length that provides the same critical stress. The *k* factor procedure is a method of making simple solutions for complicated frame-buckling problems.

Reinforced concrete columns serve as parts of frames, and these frames are sometimes *braced* and sometimes *unbraced*. A braced frame is one for which sidesway or joint translation is prevented by means of bracing, shear walls, or lateral support from adjoining structures. An unbraced frame does not have any of these types of bracing supplied and must depend on the stiffness of its own members to prevent lateral buckling. For braced frames, *k* values can never be greater than 1.0, but for unbraced frames, the *k* values will always be greater than 1.0 because of sidesway.

An example of an unbraced column is shown in Figure 11.2(a). The base of this particular column is assumed to be fixed, whereas its upper end is assumed to be completely free to both rotate and translate. The elastic curve of such a column will take the shape of the elastic curve of a pinned-end column of twice its length. Its effective length will therefore equal 2l*<sup>u</sup>* , as shown in the figure. In Figure 11.2(b), another unbraced column case is illustrated. The bottom of this column is connected to beams that provide resistance to rotation but not enough to be considered a fixed end. In most buildings, partial rotational restraint is common, not pinned or fixed ends. Section 11.4 shows how to evaluate such partial restraint. For the case shown in Figure 11.2(b), if the beam at the bottom is flexible compared with the column, the *k* factor approaches infinity. If it is very stiff, *k* approaches 2.

The code (10.10.6.3) states that the effective length factor is to be taken as 1.0 for compression members in frames braced against sidesway unless a theoretical analysis shows

![](_page_339_Figure_8.jpeg)

**FI GU RE 11.2** Columns for unbraced frames.

that a lesser value can be used. Should the member be in a frame not braced against sidesway, the value of *k* will be larger than 1.0 and must be determined with proper consideration given to the effects of cracking and reinforcing on the column stiffness. ACI-ASCE Committee 441 suggests that it is not realistic to assume that *k* will be less than 1.2 for such columns; therefore, it seems logical to make preliminary designs with *k* equal to or larger than that value.

### **11.4 Determining** *k* **Factors with Alignment Charts**

The preliminary procedure used for estimating effective lengths involves the use of the alignment charts shown in Figure 11.3.1,2 Before computerized analysis, use of such alignment charts was the traditional method for determining effective lengths of columns. The chart of part (a) of the figure is applicable to braced frames, whereas the one of part (b) is applicable to unbraced frames.

To use the alignment charts for a particular column, ψ factors are computed at each end of the column. The ψ factor at one end of the column equals the sum of the stiffness [(*EI*/l)] of the columns meeting at that joint, including the column in question, divided by the sum of all the stiffnesses of the beams meeting at the joint. Should one end of the column be pinned, ψ is theoretically equal to ∞, and if fixed, ψ = 0. Since a perfectly fixed end is practically impossible to have, ψ is usually taken as 1.0 instead of 0 for assumed fixed ends. When column ends are supported by, but not rigidly connected to a footing, ψ is theoretically infinity but usually is taken as about 10 for practical design.

One of the two ψ values is called ψ*<sup>A</sup>* and the other is called ψ*<sup>B</sup>* . After these values are computed, the effective length factor, *k*, is obtained by placing a straightedge between ψ*<sup>A</sup>* and ψ*<sup>B</sup>* . The point where the straightedge crosses the middle nomograph is *k*.

It can be seen that the ψ factors used to enter the alignment charts, and thus the resulting effective length factors, are dependent on the relative stiffnesses of the compression and flexural members. If we have a very light flexible column and large stiff girders, the rotation and lateral movement of the column ends will be greatly minimized. The column ends will be close to a fixed condition, and thus the ψ values and the resulting *k* values will be small. Obviously, if the reverse happens—that is, large stiff columns framing into light flexible girders—the column ends will rotate almost freely, approaching a pinned condition. Consequently, we will have large ψ and *k* values.

To calculate the ψ values, it is necessary to use realistic moments of inertia. Usually the girders will be appreciably cracked on their tensile sides, whereas the columns will probably have only a few cracks. If the *I* values for the girders are underestimated a little, the column *k* factors will be a little large and thus on the safe side.

Several approximate rules are in use for estimating beam and column rigidities. One common practice of the past for slenderness ratios of up to about 60 or 70 was to use gross moments of inertia for the columns and 50% of the gross moments of inertia for the beams.

In ACI Section 10.10.4.1, it is stated that for determining ψ values for use in evaluating *k* factors, the rigidity of the beams may be calculated on the basis of 0.35*Ig* to account for cracking and reinforcement, while 0.70*Ig* may be used for compression members. This practice is followed for the examples in this chapter. Other values for the estimated rigidity of walls and flat plates are provided in the same section.

<sup>1</sup> Structural Stability Research Council, *Guide to Stability Design Criteria for Metal Structures*, 4th ed., T. V. Galambos, ed. (New York: John Wiley & Sons, 1988).

<sup>2</sup> Julian, O. G. and Lawrence, L. S., 1959, "Notes on J and L Nomograms for Determination of Effective Lengths," unpublished. These are also called the Jackson and Moreland Alignment Charts, after the firm with which Julian and Lawrence were associated.

![](_page_341_Figure_2.jpeg)

**FIGURE 11.3** Effective length factors.  $\psi = \text{ratio of } \Sigma(EI/\ell)$  of compression members to  $\Sigma(EI/\ell)$ of flexural members in a plane at one end of a compression member, k = effective length factor.

#### 11.5 **Determining** *k* **Factors** with **Equations**

Instead of using the alignment charts for determining k values, an alternate method involves the use of relatively simple equations. These equations, which were in the ACI 318-05 Code Commentary (R10.12.1) and taken from the British Standard Code of Practice,<sup>3</sup> are particularly useful with computer programs.

For braced compression members, an upper bound to the effective length factor may be taken as the smaller value determined from the two equations to follow in which  $\psi_A$  and  $\psi_B$  are the values just described for the alignment charts (commonly called the Jackson and Moreland alignment charts as described in footnote 2 of this chapter).  $\psi_{\min}$  is the smaller of  $\psi_A$  and  $\psi_B$ .

$$k = 0.7 + 0.05(\psi_A + \psi_B) \le 1.0$$
  
 $k = 0.85 + 0.05\psi_{\min} \le 1.0$ 

The value of k for unbraced compression members restrained at both ends may be determined from the appropriate one of the following two equations, in which  $\psi_m$  is the

<sup>&</sup>lt;sup>3</sup> British Standards Institution, 1972, Code of Practice for the Structural Use of Concrete (CP110: Part 1), London, 154 pages.

![](_page_342_Picture_2.jpeg)

Reinforced concrete columns.

average of  $\psi_A$  and  $\psi_B$ :

If 
$$\psi_m < 2$$

$$k = \frac{20 - \psi_m}{20} \sqrt{1 + \psi_m}$$
If  $\psi_m \ge 2$ 

$$k = 0.9 \sqrt{1 + \psi_m}$$

The value of the effective length factor of unbraced compression members that are hinged at one end may be determined from the following expression, in which  $\psi$  is the value at the restrained end:  $k = 2.0 + 0.3 \psi$ 

As mentioned in Section 11.3 of this chapter, the ACI Code in Section 10.10.6.3 states that *k* should be taken to be 1.0 for compression members in frames braced against sidesway unless a theoretical analysis shows that a lesser value can be used. *In the last paragraph of Section R10.10.6.3 of the commentary, use of the alignment charts or the equations just presented is said to be satisfactory for justifying <i>k values less than 1.0 for braced frames.* 

### 11.6 First-Order Analyses Using Special Member Properties

After this section, the remainder of this chapter is devoted to an approximate design procedure wherein the effect of slenderness is accounted for by computing moment magnifiers that are multiplied by the column moments. A magnifier for a particular column is a function of its factored axial load,  $P_u$ , and its critical buckling load,  $P_c$ .

Before moment magnifiers can be computed for a particular structure, it is necessary to make a first-order analysis of the structure. The member section properties used for such an analysis should take into account the influence of axial loads, the presence of cracked regions in the members, and the effect of the duration of the loads. Instead of making such an analysis, ACI Code 10.10.4.1 permits use of the following properties for the members of the structure. These properties may be used for both nonsway and sway frames.

- (a) Modulus of elasticity determined from the following expression given in Section 8.5.1 of the code:  $E_c = w_c^{1.5} 33 \sqrt{f_c'}$  for values of  $w_c$  from 90 lb/ft<sup>3</sup> to 155 lb/ft<sup>3</sup> or 57,000  $\sqrt{f_c'}$ for normal-weight concrete.
- (b) Moments of inertia where  $I_o$  = moment of inertia of gross concrete section about centroidal axis neglecting reinforcing (ACI Section 10.10.4.1):

|     | Beams                      | $0.35I_{g}$ |
|-----|----------------------------|-------------|
|     | Columns                    | $0.70I_{g}$ |
|     | Walls—Uncracked            | $0.70I_{g}$ |
|     | —Cracked                   | $0.35I_{g}$ |
|     | Flat plates and flat slabs | $0.25I_g$   |
| (c) | Area                       | $1.0A_{o}$  |

As an alternative to the above approximate equations for columns and walls, the code permits the following more complex value for moment of inertia:

$$I = \left(0.80 + 25 \frac{A_{st}}{A_g}\right) \left(1 - \frac{M_u}{P_u h} - 0.5 \frac{P_u}{P_0}\right) I_g \le 0.875 I_g$$
 (ACI Equation 10-8)

 $P_u$  and  $M_u$  are to be from the load combination under consideration, or they can conservatively be taken as the values of  $P_u$  and  $M_u$  that result in the lowest value of I. In no case is the value of I for compression members required to be taken less than  $0.35I_o$ .  $P_0$  is the theoretical concentric axial load strength (see Chapter 9 of this textbook).

For flexural members (beams and flat plates and flat slabs), the following approximate equation is permitted:

$$I = (0.10 + 25\rho) \left(1.2 - 0.2 \frac{b_w}{d}\right) I_g \le 0.5 I_g$$
 (ACI Equation 10-9)

For continuous flexural members, it is permitted to use the average value of I from the positive and negative moment sections. In no case is the value of I for flexural members required to be taken less than  $0.25I_{\odot}$ 

Often during the design process, the designer does not know the final values of member section dimensions or steel areas when making calculations such as those in ACI Equation 10-8. This leads to an iterative process where the last cycle of iteration assumes the same member properties as the final design. The code (10.10.4.1) allows these values to be only within 10% of the final values in the final iteration.

#### **Slender Columns in Nonsway and Sway Frames** 11.7

There is a major difference in the behavior of columns in nonsway or braced frames and those in sway or unbraced frames. In effect, each column in a braced frame acts by itself. In other words, its individual strength can be determined and compared to its computed factored loads and moments. In an unbraced or sway frame, a column will probably not buckle individually but will probably buckle simultaneously with all of the other columns on the same level. As a result, it is necessary in a sway frame to consider the buckling strength of all the columns on the level in question as a unit.

For a compression member in a nonsway frame, the effective slenderness ratio,  $k\ell_u/r$ , is used to determine whether the member is short or slender. For this calculation,  $\ell_u$  is the unbraced length of the member. The effective length factor, k, can be taken as 1.0 unless an analysis provides a lesser value. The radius of gyration, r, is equal to 0.25 times the diameter of a round column and 0.289 times the dimension of a rectangular column in the direction that stability is being considered. The ACI Code (10.10.1.2) permits the approximate value of 0.30 to be used in place of 0.289, and this is done herein. For other sections, the value of r will have to be computed from the properties of the gross sections.

For nonsway frames, slenderness effects may be ignored if the following expression is satisfied:

 $\frac{k\ell_u}{r} \le 34 - 12\left(\frac{M_1}{M_2}\right) \tag{ACI Equation 10-7}$ 

In this expression,  $M_1$  is the smaller factored end moment in a compression member. It has a plus sign if the member is bent in single curvature (C shaped) and a negative sign if the member is bent in double curvature (S shaped).  $M_2$  is the larger factored end moment in a compression member, and it always has a plus sign. In this equation, the term  $\left[34 - 12\left(M_1/M_2\right)\right]$  shall not be taken larger than 40, according to ACI Code 10.10.1

For sway frames, slenderness effects may be ignored if

$$\frac{k\ell_u}{r}$$
 < 22 (ACI Equation 10-6)

Should  $k\ell_u/r$  for a particular column be larger than the applicable ratio, we will have a slender column. For such a column, the effect of slenderness must be considered. This may be done by using approximate methods or by using a theoretical second-order analysis that takes into account the effect of deflections. Second-order effects cannot exceed 40% of first-order effects (ACI 10.10.2.1).

A second-order analysis is one that takes into account the effect of deflections and also makes use of a reduced tangent modulus. The equations necessary for designing a column in this range are extremely complicated, and, practically, it is necessary to use column design charts or computer programs.

#### **Avoiding Slender Columns**

The design of slender columns is appreciably more complicated than the design of short columns. As a result, it may be wise to give some consideration to the use of certain minimum dimensions so that none of the columns will be slender. In this way, they can be almost completely avoided in the average-size building.

If k is assumed equal to 1.0, slenderness can usually be neglected in braced frame columns, if  $\ell_u/h$  is kept to 10 or less on the first floor and 14 or less for the floors above the first one. To determine these values, it was assumed that little moment resistance was provided at the footing–column connection and the first-floor columns were assumed to be bent in single curvature. Should the footing–column connection be designed to have appreciable moment resistance, the maximum  $\ell_u/h$  value given above as 10 should be raised to about 14 or equal to the value used for the upper floors.<sup>4</sup>

Should we have an unbraced frame and assume k = 1.2, it is probably necessary to keep  $\ell_u/h$  to 6 or less. So for a 10-ft clear floor height, it is necessary to use a minimum h of about 10 ft/6 = 1.67 ft = 20 in. in the direction of bending to avoid slender columns.

<sup>&</sup>lt;sup>4</sup> Neville, G. B., ed., 1984, Simplified Design Reinforced Concrete Buildings of Moderate Size and Height (Skokie, IL: Portland Cement Association), pp. 5-10 to 5-12.

Example 11.1 illustrates the selection of the k factor and the determination of the slenderness ratio for a column in an unbraced frame. For calculating I/L values, the authors used 0.70 times the gross moments of inertia for the columns, 0.35 times the gross moments of inertia for the girders, and the full lengths of members center to center of supports.

#### Example 11.1

- (a) Using the alignment charts of Figure 11.3, calculate the effective length factor for column AB of the braced frame of Figure 11.4. Consider only bending in the plane of the frame.
- (b) Compute the slenderness ratio of column AB. Is it a short or a slender column? The maximum permissible slenderness ratio for a short unbraced column is 22, as will be described in Section 11.9 of this chapter. End moments on the column are  $M_1 = 45$  ft-k and  $M_2 = 75$  ft-k, resulting in single curvature.

#### SOLUTION

#### (a) Effective Length Factor for Column AB

Using the Reduced Moments of Inertia from 11.6(b) and applying the method described in Section 11.4

$$\psi_A = \frac{\frac{0.7 \times 8000 \text{ in.}^4}{12 \times 10 \text{ ft}}}{\left(\frac{0.35 \times 5832 \text{ in.}^4}{12 \times 20 \text{ ft}} + \frac{0.35 \times 5832 \text{ in.}^4}{12 \times 24 \text{ ft}}\right)} = 2.99$$

$$\frac{0.7 \times 8000 \text{ in.}^4}{12 \times 10 \text{ ft}} + \frac{0.7 \times 8000 \text{ in.}^4}{12 \times 12 \text{ ft}}$$

$$\psi_{B} = \frac{\frac{0.7 \times 8000 \text{ in.}^{4}}{12 \times 10 \text{ ft}} + \frac{0.7 \times 8000 \text{ in.}^{4}}{12 \times 12 \text{ ft}}}{\left(\frac{0.35 \times 13,824 \text{ in.}^{4}}{12 \times 20 \text{ ft}} + \frac{0.35 \times 13,824 \text{ in.}^{4}}{12 \times 24 \text{ ft}}\right)} = 2.31$$

![](_page_345_Figure_11.jpeg)

**FIGURE 11.4** Frame for Example 11.1.

![](_page_346_Picture_2.jpeg)

Adjustable steel column forming system.

#### From Figure 11.3(a)

![](_page_346_Figure_5.jpeg)

#### (b) Is It a Slender Column?

$$\begin{split} \ell_u &= 10 \text{ ft} - \frac{9 \text{ in.} + 12 \text{ in.}}{12 \text{ in/ft}} = 8.25 \text{ ft} \\ \frac{k\ell_u}{r} &= \frac{(0.875) \times (12 \text{ in/ft} \times 8.25 \text{ ft})}{0.3 \times 20 \text{ in.}} = 14.44 < \text{Maximum} \, \frac{k\ell_u}{r} \text{ for a short column in a braced} \\ &\text{frame by ACI Equation } 10\text{-}7 = 34 - 12 \left(\frac{+45 \text{ ft-k}}{+75 \text{ ft-k}}\right) = 26.8 \end{split}$$

... It's not a slender column

An experienced designer would first simply assume k=1 and quickly see that  $k\ell_u/r=\ell_u/r=16.5<26.5$ . There would then be no need to determine k.

If this column were in the same frame but the frame were unbraced, then k would be 1.78 and  $k\ell_u/r = 29.37 > 22$ . It would be a slender column. The only difference in determining k is the use of Figure 11.3(b) for sway columns instead of Figure 11.3(a) for nonsway columns.

### **11.8 ACI Code Treatments of Slenderness Effects**

The ACI Code permits the determination of second-order effects by one of three methods. The first is by a *nonlinear second-order analysis* (ACI 10.10.3). Such an analysis must consider nonlinearity of materials, member curvature and lateral drift, load duration, volume changes in concrete because of creep and shrinkage, and foundation or support interaction. The analysis technique should predict the ultimate loads to within 15% or test results on statically indeterminate reinforced concrete structures. This technique would require sophisticated computer software that has been demonstrated to satisfy the 15% accuracy requirement mentioned previously.

The second method is by an *elastic second-order analysis* (ACI 10.10.4). This technique is simpler than the nonlinear method because it uses member stiffnesses immediately prior to failure. Values of *Ec* and moments of inertia and cross-sectional area for columns, beams, walls, flat plates, and flat slabs that are permitted to be used in the elastic second-order analysis are listed in Section 11.6. This method would also most likely require a computer analysis.

The third method is the *moment magnifier procedure* (ACI 10.10.5). Different procedures for this method are given for sway and nonsway structures. The next two sections describe the moment magnifier method for these two cases.

### **11.9 Magnification of Column Moments in Nonsway Frames**

When a column is subjected to moment along its unbraced length, it will be displaced laterally in the plane of bending. The result will be an increased or secondary moment equal to the axial load times the lateral displacement or eccentricity. In Figure 11.5, the load *P* causes the column moment to be increased by an amount *P*. This moment will cause δ to increase a little more, with the result that the *P* moment will increase, which in turn will cause a further increase in and so on until equilibrium is reached.

We could take the column moments, compute the lateral deflection, increase the moment by *P*, recalculate the lateral deflection and the increased moment, and so on. Although about two cycles would be sufficient, this would still be a tedious and impractical procedure.

![](_page_347_Picture_9.jpeg)

**FI GU RE 11.5** Moment magnification in a nonsway column.

It can be shown<sup>5</sup> that the increased moment can be estimated very well by multiplying the primary moment by  $1/(1 - P/P_c)$ , where P is the axial load and  $P_c$  is the Euler buckling load  $\pi^2 EI/(k\ell_u)^2$ .

In Example 11.2, this expression is used to estimate the magnified moment in a laterally loaded column. It will be noted that in this problem, the primary moment of 75 ft-k is estimated to increase by 7.4 ft-k. If we computed the deflection from the lateral load, we would get 0.445 in. For this value,  $P\Delta = (150) (0.445) = 66.75$  in-k = 5.6 ft-k. This moment causes more deflection, which causes more moment, and so on.

#### Example 11.2

- (a) Compute the primary moment in the column shown in Figure 11.6 from the lateral 20-k load.
- **(b)** Determine the estimated total moment, including the secondary moment from lateral deflection, using the appropriate magnification factor just presented.  $E = 3.16 \times 10^3$  ksi. Assume k = 1.0 and  $\ell_{ij} = 15$  ft.

#### SOLUTION

(a) Primary moment resulting from lateral load:

$$M_u = \frac{(20 \text{ k})(15 \text{ ft})}{4} = \frac{75 \text{ ft-k}}{4}$$

(b) Total moment, including secondary moment:

$$P_c = \text{Euler buckling load} = \frac{\pi^2 EI}{(k\ell_u)^2}$$
 (ACI Equation 10-13)  
=  $\frac{(\pi^2) (3160 \text{ ksi}) \left(\frac{1}{12} \times 12 \text{ in.} \times 12 \text{ in.}^3\right)}{(1.0 \times 12 \text{ in/ft} \times 15 \text{ ft})^2} = 1663.4 \text{ k}$ 

![](_page_348_Figure_12.jpeg)

**FIGURE 11.6** Column for Example 11.2.

<sup>&</sup>lt;sup>5</sup> Timoshenko, S. P., and Gere, J. M., 1961, *Theory of Elastic Stability*, 2nd ed. (New York: McGraw-Hill), pp. 319–356.

Magnified moment = 
$$\frac{1}{1 - \frac{P}{P_c}} M_2$$
  
=  $\frac{1}{1 - \frac{150 \text{ k}}{1663.4 \text{ k}}} 75 \text{ ft-k} = \underline{82.4 \text{ ft-k}}$ 

As you have seen, it is possible to calculate approximately the increased moment resulting from lateral deflection by using the  $(1 - P/P_c)$  expression. In ACI Code 10.10.16, the factored design moment for slender columns with no sway is increased by using the following expression, in which  $M_c$  is the magnified or increased moment and  $M_2$  is the larger factored end moment on a compression member:

$$M_c = \delta M_2$$
 (ACI Equation 10-11)

Should our calculations provide very small moments at both column ends, the code provides an absolutely minimum value of  $M_2$  to be used in design. In effect, it requires the computation of a moment based on a minimum eccentricity of 0.6 + 0.03h, where h is the overall thickness of the member perpendicular to the axis of bending.

$$M_{2 \min} = P_{\mu}(0.6 + 0.03h)$$
 (ACI Equation 10-17)

Or in SI units

$$M_{2 \text{ min}} = P_u (15 + 0.03h)$$
, where h is in mm, as is the number 15

A moment magnifier,  $\delta$ , is used to estimate the effect of member curvature between the ends of compression members. It involves a term  $C_m$ , which is defined later in this section.

$$\delta = \frac{C_m}{1 - \frac{P_u}{0.75P_c}} \ge 1.0 \tag{ACI Equation 10-12}$$

The determination of the moment magnifier,  $\delta_{ns}$ , involves the following calculations:

- 1.  $E_c = 57,000\sqrt{f_c'}$  for normal-weight concrete (see Section 1.11 for other densities).
- 2.  $I_{\varphi}$  = gross inertia of the column cross section about the centroidal axis being considered.
- 3.  $E_s = 29 \times 10^6$  psi.
- **4.**  $I_{se}$  = moment of inertia of the reinforcing about the centroidal axis of the section. (This value equals the sum of each bar area times the square of its distance from the centroidal axis of the compression member.)
- 5. The term  $\beta_{dns}$  accounts for the reduction in stiffness caused by sustained axial loads and applies only to nonsway frames. It is defined as the ratio of the maximum factored sustained axial load divided by the total factored axial load associated with the same load combination. It is always assumed to have a plus sign and is never permitted to exceed 1.0.

**6.** Next, it is necessary to compute *EI.* The two expressions given for *EI* in the code were developed so as to account for creep, cracks, and so on. If the column and bar sizes have already been selected or estimated, *EI* can be computed with the following expression, which is particularly satisfactory for columns with high steel percentages.

$$EI = \frac{(0.2E_cI_g + E_sI_{se})}{1 + \beta_{dns}}$$
 (ACI Equation 10-14)

The alternate expression for *EI* that follows is probably the better expression to use when steel percentages are low. Notice also that this expression will be the one used if the reinforcing has not been previously selected.

$$EI = \frac{0.4E_c I_g}{1 + \beta_{dns}}$$
 (ACI Equation 10-15)

**7.** The Euler buckling load is computed:

$$P_c = \frac{\pi^2 EI}{(k \ell_u)^2}$$
 (ACI Equation 10-13)

**8.** For some moment situations in columns, the amplification or moment magnifier expression provides moments that are too large. One such situation occurs when the moment at one end of the member is zero. For this situation, the lateral deflection is actually about half of the deflection in effect provided by the amplification factor. Should we have approximately equal end moments that are causing reverse curvature bending, the deflection at middepth and the moment there are close to zero. As a result of these and other situations, the code provides a modification factor (*Cm*) to be used in the moment expression that will result in more realistic moment magnification.

For braced frames without transverse loads between supports, *Cm* can vary from 0.4 to 1.0 and is determined with the expression at the end of this paragraph. For all other cases, it is to be taken as 1.0. (Remember the sign convention: *M*<sup>1</sup> is positive for single curvature and is negative for reverse curvature, and *M*<sup>2</sup> is always positive.)

$$C_m = 0.6 + 0.4 \frac{M_1}{M_2}$$
 (ACI Equation 10-16)

Should *M*2 min as computed with ACI Equation 10-17 be larger than *M*2, the value of *Cm* in this equation shall either be taken as equal to 1.0 or be based on the ratio of the computed end moments *M*1/*M*<sup>2</sup> (ACI Section 10.10.6.4).

Example 11.3 illustrates the design of a column in a nonsway frame.

#### Example 11.3

The tied column of Figure 11.7 has been approximately sized to the dimensions 12 in. × 15 in. It is to be used in a frame braced against sidesway. The column is bent in single curvature about its *y*-axis and has an l*<sup>u</sup>* of 16 ft. If *k* = 0.83, *fy* = 60,000 psi, and *f <sup>c</sup>* = 4000 psi, determine the reinforcing required. Consider only bending in the plane of the frame. Note also that the unfactored dead axial load *PD* is 30 k, and concrete is normal weight.

![](_page_351_Figure_2.jpeg)

FIGURE 11.7 Column profile and cross section for Example 11.3.

#### SOLUTION

1. Is it a slender column?

$$\begin{split} \text{Max } \frac{k\ell_u}{r} \text{ for short columns} &= 34 - 12 \frac{M_1}{M_2} = 34 - 12 \left( \frac{+82 \text{ ft-k}}{+86 \text{ ft-k}} \right) \\ &= 22.56 \\ \text{Actual } \frac{k\ell_u}{r} &= \frac{(0.83) \, (12 \text{ in/ft} \times 16 \text{ ft})}{0.3 \times 15 \text{ in.}} = 35.41 > 22.56 \end{split}$$

: It's a slender column

**2.** 
$$E_c = 57,000\sqrt{f_c'} = 57,000\sqrt{4000} \text{ psi} = 3,605,000 \text{ psi} = 3.605 \times 10^3 \text{ ksi}$$

**3.** 
$$I_g = \left(\frac{1}{12}\right) (12 \text{ in.}) (15 \text{ in.})^3 = 3375 \text{ in.}^4$$

**4.** 
$$\beta_d = \frac{\text{factored axial dead load}}{\text{factored axial total load}} = \frac{(1.2)(30 \text{ k})}{110 \text{ k}} = 0.327$$

5. Because reinforcing has not been selected, we must use ACI Equation 10-15 for El.

$$EI = \frac{0.4E_c I_g}{1 + \beta_d} = \frac{(0.4) (3605 \text{ ksi}) (3375 \text{ in.}^4)}{1 + 0.327} = 3.67 \times 10^6 \text{ k-in.}^2$$
 (ACI Equation 10-15)

**6.** 
$$P_c = \frac{\pi^2 EI}{(k\ell_v)^2} = \frac{(\pi^2)(3.67 \times 10^6 \text{ k} \cdot \text{in.}^2)}{(0.83 \times 12 \text{ in/ft} \times 16 \text{ ft})^2} = 1426 \text{ k}$$
 (ACI Equation 10-13)

7. 
$$C_m = 0.6 + 0.4 \frac{M_1}{M_2} = 0.6 + 0.4 \left(\frac{+82 \text{ ft-k}}{+86 \text{ ft-k}}\right) = 0.981$$
 (ACI Equation 10-16)

8. 
$$\delta = \frac{C_m}{1 - \frac{P_u}{0.75P_c}} = \frac{0.981}{1 - \frac{110 \text{ k}}{(0.75)(1426 \text{ k})}} = 1.09$$
 (ACI Equation 10-12)

9. 
$$M_{2 \, \text{min}} = P_u(0.6 + 0.03h) = 110 \, \text{k} (0.6 + 0.03 \times 15 \, \text{in.})$$
  
= 115.5 in-k = 9.6 ft-k (ACI Equation 10-17)

**10.** 
$$M_c = \delta M_2 = (1.09) (86 \text{ ft-k}) = 93.7 \text{ ft-k}$$
 (ACI Equation 10-11)

**11.** Magnified 
$$e = \delta e = \frac{(12)(93.7 \text{ ft-k})}{110 \text{ k}} = 10.22 \text{ in.}$$

**12.** v = 10 in./15 in. = 0.667

 $\therefore \rho_g$  is determined by interpolation between values presented in Appendix A, Graphs 2 and 3.

$$P_n = \frac{P_u}{\phi} = \frac{110 \text{ k}}{0.65} = 169.23 \text{ k}$$

$$K_n = \frac{P_n}{f_c' A_g} = \frac{169.23 \text{ k}}{(4 \text{ ksi}) (12 \text{ in.} \times 15 \text{ in.})} = 0.235$$

$$R_n = \frac{P_n}{f_c' A_g} \frac{\delta e}{h} = (0.235) \left(\frac{10.22 \text{ in.}}{15 \text{ in.}}\right) = 0.160$$

$$\rho_g = 0.0160$$

$$A_g = (0.0160) (12 \text{ in.}) (15 \text{ in.}) = 2.88 \text{ in.}^2$$

Use 4 #8 bars (3.14 in.2)

Since  $K_n$  and  $R_n$  are between the radial lines labeled  $f_s/f_y = 1.0$  and  $\epsilon_t = 0.005$  on the interaction diagrams, the  $\phi$  factor is permitted to be increased from the 0.65 value used. If the spreadsheet for rectangular columns given in Chapters 9 and 10 is used, an area of reinforcing of only 1.80 in.<sup>2</sup> is found to be sufficient. This significant reduction occurs because of the increased  $\phi$  factor in this region.

Most columns are designed for multiple load combinations, and the designer must be certain that the column is able to resist all of them. Often there are some columns with high axial load and low moment, such as 1.2D + 1.6L, and others with low axial load and high moment, such as 0.9D + 1.6E. The first of these is likely to have a  $\phi$  factor of 0.65. The second, however, is more likely to be eligible for the increase in the  $\phi$  factor.

In this example, the authors assumed that the frame was braced, and yet we have said that frames are often in that gray area between being fully braced and fully unbraced. Assuming a frame is fully braced clearly may be quite unconservative.

### 11.10 Magnification of Column Moments in Sway Frames

Tests have shown that even though the lateral deflections in unbraced frames are rather small, their buckling loads are far less than they would be if the frames had been braced. As a result, the buckling strengths of the columns of an unbraced frame can be decidedly increased (perhaps by as much as two or three times) by providing bracing.

If a frame is unbraced against sidesway, it is first necessary to compute its slenderness ratio. If  $k\ell_u/r$  is less than 22, slenderness may be neglected (ACI 10.10.1). For this discussion, it is assumed that values greater than 22 are obtained.

When sway frames are involved, it is necessary to decide for each load combination which of the loads cause appreciable sidesway (probably the lateral loads) and which do not. The factored end moments that cause sidesway are referred to as  $M_{1s}$  and  $M_{2s}$ , and they must

be magnified because of the  $P\Delta$  effect. The other end moments, resulting from loads that do not cause appreciable sidesway, are  $M_{1ns}$  and  $M_{2ns}$ . They are determined by first-order analysis and will not have to be magnified.

The code (10.10.7) states that the moment magnifier,  $\delta_s$ , can be determined by one of the following two methods.

1. The moment magnifier may be calculated with the equation given at the end of this paragraph in which Q is the stability index previously presented in Section 11.2 of this chapter. Should the computed value of  $\delta_s$  be greater than 1.5, it will be necessary to compute  $\delta_s$  by ACI Section 10.10.7.4 or by a second-order analysis.

$$\delta_s = \frac{1}{1 - Q} \ge 1 \tag{ACI Equation 10-20}$$

2. With the second method and the one used in this chapter, the magnified sway moments may be computed with the following expression:

$$\delta_s = \frac{1}{1 - \frac{\Sigma P_u}{0.75 \Sigma P_c}} \ge 1$$
 (ACI Equation 10-21)

In this last equation,  $\Sigma P_u$  is the summation of all the vertical loads in the story in question, and  $\Sigma P_c$  is the sum of all the Euler buckling loads,  $P_c = \pi^2 E I/(k \ell_u)^2$ , for all of the sway-resisting columns in the story with k values determined as described in ACI Section 10.10.7.2. This formula reflects the fact that the lateral deflections of all the columns in a particular story are equal, and thus the columns are interactive.

Whichever of the preceding methods is used to determine the  $\delta_s$  values, the design moments to be used must be calculated with the expressions that follow.

$$M_1 = M_{1ns} + \delta_s M_{1s} \qquad (ACI Equation 10-18)$$

$$M_2 = M_{2ns} + \delta_s M_{2s} \qquad (ACI Equation 10-19)$$

![](_page_353_Picture_12.jpeg)

Reinforced concrete columns and shearwalls supporting structural steel roof.

Sometimes the point of maximum moment in a slender column will fall between its ends. The ACI Commentary (R10.10.2.2) says the moment magnification for this case may be evaluated using the procedure described for nonsway frames (ACI Section 10.10.6).

Example 11.4 illustrates the design of a slender column subject to sway.

#### Example 11.4

Select reinforcing bars using the moment magnification method for the 18 in.  $\times$  18 in. unbraced column shown in Figure 11.8 if  $\ell_u=17.5$  ft, k=1.3,  $f_y=60$  ksi, and  $f_c'=4$  ksi. A first-order analysis has resulted in the following axial loads and moments:

$$P_D = 300 \text{ k}$$
  $M_D = 48 \text{ ft-k}$   
 $P_L = 150 \text{ k}$   $M_L = 25 \text{ ft-k}$   
 $P_W = 272 \text{ k}$   $M_W = 32 \text{ ft-k}$ 

The loading combination assumed to control for the case with no sidesway is ACI Equation 9.2 (Section 4.1 of this text).

$$P_U = 1.2P_D + 1.6P_L = 1.2(300 \text{ k}) + 1.6(150 \text{ k}) = 600 \text{ k}$$
  
 $M_U = 1.2M_D + 1.6M_U = 1.2(48 \text{ ft-k}) + 1.6(25 \text{ ft-k}) = 97.6 \text{ ft-k} = M_{208}$ 

The loading combination assumed to control with sidesway is ACI Equation 9.6.

$$P_U = 0.9P_D + 1.0P_W = 0.9(300 \text{ k}) + 1.0(272 \text{ k}) = 542 \text{ k}$$
  
 $M_U = 0.9M_D + 1.0M_W = 0.9(48 \text{ ft-k}) + 1.0(32 \text{ ft-k}) = 75.2 \text{ ft-k}$   
 $M_{2s} = 1.0M_W = (1.0)(32 \text{ ft-k}) = 32 \text{ ft-k}$ 

Note that ACI Equation 9.3 or 9.4 may also control for sidesway, but in this case it is unlikely.

$$\Sigma P_u = 12,000$$
 for all columns on floor  $\Sigma P_c = 60,000$  for all columns on floor

#### SOLUTION

Is it a slender column? (ACI Section 10.13.2)

$$\frac{k\ell_u}{r} = \frac{\text{(1.3) (12 in/ft) (17.5 ft)}}{\text{(0.3) (18 in.)}} = 50.55 > 22$$
 Yes

![](_page_354_Figure_16.jpeg)

**FIGURE 11.8** Column cross section for Example 11.4.

#### Calculating the Magnified Moment $\delta_a$

$$\delta_s = \frac{1}{1 - \frac{\Sigma P_u}{0.75 \Sigma P_c}}$$

$$= \frac{1}{1 - \frac{12,000 \text{ k}}{(0.75)(60,000 \text{ k})}} = 1.364$$
(ACI Equation 10-18)

#### Computing Magnified Moment Ma

$$M_2 = M_{2ns} + \delta_{\rm s} M_{2s}$$
 (ACI Equation 10-19)  
= 97.6 ft-k + (1.364) (32 ft-k) = 141.2 ft-k

Is  $M_{2ns} \ge minimum \ value \ permitted \ in ACI \ Section 10.10.6.5?$ 

$$M_{2\,\mathrm{min}} = P_u (0.6 + 0.03h)$$
 (ACI Equation 10-17) 
$$= (542\,\mathrm{k})\,(0.6 + 0.03 \times 18\,\mathrm{in.}) = 617.9\,\mathrm{in-k}$$
 
$$= 51.5\,\mathrm{ft-k} < 97.6\,\mathrm{ft-k} \qquad \underline{\mathrm{Yes}}$$

#### **Selecting Reinforcing**

$$\gamma = \frac{13 \text{ in.}}{18 \text{ in.}} = 0.722 \text{ with reference to Figure 11.8}$$

$$P_n = \frac{P_u}{\phi} = \frac{542 \text{ k}}{0.65} = 833.8 \text{ k}$$

$$e = \frac{(12 \text{ in/ft}) (141.2 \text{ ft-k})}{542 \text{ k}} = 3.13 \text{ in.}$$

$$K_n = \frac{P_n}{f_c' A_g} = \frac{833.8 \text{ k}}{(4 \text{ ksi}) (18 \text{ in.} \times 18 \text{ in.})} = 0.643$$

$$R_n = \frac{P_n}{f_c' A_g} \frac{e}{h} = (0.643) \left(\frac{3.13 \text{ in.}}{18 \text{ in.}}\right) = 0.112$$

By interpolation between Appendix A, Graphs 3 and 4, we find  $\rho_7$  is less than 0.01, so use 0.01.

$$A_{\rm s} = \rho_z A_q = (0.01) \, (18 \, \text{in.} \times 18 \, \text{in.}) = 3.24 \, \text{in.}^2$$

### Analysis of Sway Frames

The frame of Figure 11.9 is assumed to be unbraced in the plane of the frame. It supports a uniform gravity load,  $w_u$ , and a short-term concentrated lateral load,  $P_w$ . As a result, it is necessary to consider both the moments resulting from the loads that do not cause appreciable sidesway and the loads that do. It will, therefore, be necessary to compute both  $\delta$  and  $\delta_s$  values, if the column proves to be slender.

The  $M_s$  values are obviously caused by the lateral load in this case. The reader should realize, however, that if the gravity loads and/or the frame are unsymmetrical, additional M<sub>s</sub> or sidesway moments will occur.

If we have an unbraced frame subjected to short-term lateral wind or earthquake loads, the columns will not have appreciable creep (which would increase lateral deflections and,

![](_page_356_Figure_2.jpeg)

**FI GU RE 11.9** Sway frame for Example 11.5.

thus, the *P* moments). The effect of creep is accounted for in design by reducing the stiffness *EI* used to calculate *Pc* and thus δ*<sup>s</sup>* by dividing *EI* by 1 + β*dns*, as specified in ACI Section 10.10.6.1. Both the concrete and steel terms in ACI Equation 10-14 are divided by this value. In the case of sustained lateral load, such as soil backfill or water pressure, ACI Section 10.10.4.2 requires that the moments of inertia for compression members in Section 11.6 be divided by (1 + β*ds*). The term β*ds* is the ratio of the maximum factored sustained shear within a story to the maximum factored shear in that story for the same load combination.

To illustrate the computation of the magnified moments needed for the design of a slender column in a sway frame, the authors have chosen the simple frame of Figure 11.9. We hope thereby that the student will not become lost in a forest of numbers, as he or she might if a large frame were considered.

The beam and columns of the frame have been tentatively sized, as shown in the figure. In Example 11.5, the frame is analyzed for each of the conditions specified in ACI Section 9.2 using 1.0*W.*

In the example, the magnification factors δ and δ*<sup>s</sup>* are computed for each of the loading conditions and used to compute the magnified moments. Notice in the solution that different *k* values are used for determining δ and δ*s*. The *k* for the δ calculation is determined from the alignment chart of Figure 11.3(a) for braced frames, whereas the *k* for the δ*<sup>s</sup>* calculation is determined from the alignment chart of Figure 11.3(b) for unbraced frames.

#### Example 11.5

Determine the moments and axial forces that must be used for the design of column CD of the unbraced frame of Figure 11.9. Consider only bending in the plane of the frame. The assumed member sizes shown in the figure are used for the analyses given in the problem. *fy* = 60,000 psi and *f <sup>c</sup>* = 4000 psi. For this example, the authors considered the load factor cases of ACI Equations 9-2, 9-4, and 9-6. For other situations, other appropriate ACI load factor equations will have to be considered.

#### **SOLUTION**

**1.** *Determine the effective length factor for the sway case using 0.35Ig for the girder and 0.70Ig for the columns*.

$$I_{\text{column}} = (0.70) \left(\frac{1}{12}\right) (12 \text{ in.}) (12 \text{ in.})^3 = 1210 \text{ in.}^4$$

Note that if the lateral load were sustained,  $I_{\rm column}$  would be divided by  $(1 + \beta_{\rm ds})$ .

$$I_{\text{girder}} = (0.35) \left(\frac{1}{12}\right) (12 \text{ in.}) (18 \text{ in.})^3 = 2041 \text{ in.}^4$$

$$\psi_B = \frac{\frac{1210 \text{ in.}^4}{12 \text{ ft}}}{\frac{2041 \text{ in.}^4}{30 \text{ ft}}} = 1.48$$

 $\psi_{A}=\infty$  for pinned ends

(For practical purposes, use 10.)

k = 1.95 from Figure 11.3(b)

2. Is it a slender column?

$$\ell_u = 12 \text{ ft} - \frac{9 \text{ in.}}{12 \text{ in/ft}} = 11.25 \text{ ft}$$

 $\operatorname{Max} \frac{k\ell_u}{r} \text{ to be a short column} = 22 \text{ for sway frames}$ 

$$\frac{k\ell_u}{r} = \frac{(1.95)(12 \text{ in/ft} \times 11.25 \text{ ft})}{0.3 \times 12 \text{ in.}} = 73.12 > 22$$

: It is a slender column

- **3.** Consider the loading case U = 1.2D + 1.6L (see Figure 11.10).
  - (a) Are column moments ≥ ACI minimum?

$$e_{min} = 0.6 + 0.03 \times 12 \text{ in.} = 0.96 \text{ in.}$$

$$M_{2 \text{ min}} = (66 \text{ k}) (0.96 \text{ in.}) = 63.36 \text{ in-k} = 5.28 \text{ ft-k} < 173.5 \text{ ft-k} \text{ (see Figure 11.10)}$$

![](_page_357_Figure_16.jpeg)

**FIGURE 11.10** Loading 1.2D + 1.6L.

**(b)** Compute the magnification factor  $\delta$ :

$$E_c = 57,000\sqrt{4000} \text{ psi} = 3,605,000 \text{ psi} = 3605 \text{ ksi}$$

$$\beta_d = \frac{(1.2) (1 \text{ klf})}{(1.2) (1 \text{ klf}) + (1.6) (2 \text{ klf})} = 0.273$$

$$EI = \frac{(0.4) (3605 \text{ ksi}) (1728 \text{ in.}^4)}{1 + 0.273} = 1.96 \times 10^6 \text{ k-in.}^2$$

Assuming conservatively that k = 1.0 for computing  $P_c$ 

$$P_c = \frac{(\pi^2) (1.96 \times 10^6 \text{ k-in.}^2)}{(1.0 \times 12 \text{ in/ft} \times 11.25 \text{ ft})^2} = 1061 \text{ k}$$

$$C_m = 0.6 + (0.4) \left(\frac{-0 \text{ ft-k}}{+173.5 \text{ ft-k}}\right) = 0.6$$

$$\delta_{ns} = \frac{0.6}{1 - \frac{66 \text{ k}}{(0.75) (1061 \text{ k})}} = 0.65 < 1.0$$
Use 1.0

(c) Compute the magnification factor  $\delta_s$ : Using k = 1.95 as given for determining  $P_c$ 

$$P_c = \frac{(\pi^2)(1.96 \times 10^6 \text{ k-in.}^2)}{(1.95 \times 12 \text{ in/ft} \times 11.25 \text{ ft})^2} = 279.1 \text{ k}$$

$$\delta_s = \frac{1}{1 - \frac{\Sigma P_u}{0.75 \Sigma P}} = \frac{1}{1 - \frac{(2)(66 \text{ k})}{(0.75)(2 \times 279 \text{ l/k})}} = 1.46$$

(d) Compute the magnified moment:

$$M_c = (1.0)(173.5 \text{ ft-k}) + (1.47)(0 \text{ ft-k}) = 173.9 \text{ ft-k}$$

- **4.** Consider the loading case U = (1.2D + 1.0L + 1.0W) as specified in ACI Code Section 9.2.1(b). Analysis results are shown in Figure 11.11.
  - (a) Are column moments > ACI minimum?

$$e_{min} = 0.6 \text{ in.} + 0.03 \times 12 \text{ in.} = 0.96 \text{ in.}$$
  
 $M_{2 \text{ min}} = (48 \text{ k}) (0.96 \text{ in.}) = 46.08 \text{ in-k} = 3.84 \text{ ft-k} < 126.2 \text{ ft-k}$  OK

**(b)** Computing  $\delta$ :  $\beta_{ns}$ , EI, and  $P_c$  are the same as before

$$C_m = 0.6 + 0.4 \left(\frac{-0 \text{ ft-k}}{126.2 \text{ ft-k}}\right) = 0.6$$

$$\delta = \frac{0.6}{1 - \frac{48 \text{ k} + 5.12 \text{ k}}{0.75 \times 1061 \text{ k}}} = 0.64$$
Use 1.0

![](_page_359_Figure_2.jpeg)

**FIGURE 11.11** Nonsway and sway load cases for U = 1.2D + 1.0L + 1.0W.

(c) Computing 
$$\delta_s$$
: 
$$\beta_{dns} = \frac{1.2D}{1.2D + 1.0L + 1.0W} = \frac{18 \text{ k}}{18 \text{ k} + 30 \text{ k} + 5.12 \text{ k}} = 0.339$$

$$EI = \frac{(0.4) (3605 \text{ ksi}) (1728 \text{ in}.^4)}{1 + 0.339} = 1.86 \times 10^6 \text{ k-in}.^2$$

$$P_c = \frac{(\pi^2) (1.86 \times 10^6 \text{ k-in}.^2)}{(1.95 \times 12 \text{ in/ft} \times 11.25 \text{ ft})^2} = 264.9 \text{ k}$$

$$\delta_s = \frac{1}{1 + \frac{\Sigma P_u}{0.75 \Sigma P_c}} = \frac{1}{1 - \frac{(2) (48 \text{ k}) + 5.12 \text{ k} - 5.12 \text{ k}}{0.75 \times 2 \times 264.9 \text{ k}}} = 1.32$$

(d) Compute the magnified moment:

$$M_c = (1.0) (126.2 \text{ ft-k}) + (1.32) (76.8 \text{ ft-k}) = 227.6 \text{ ft-k}$$

- **5.** Consider the loading case 0.9D + 1.0W. Analysis results are shown in Figure 11.12.
  - (a) Are column moments > ACI minimum?

$$e_{min} = 0.6 \text{ in.} + 0.03 \times 12 \text{ in.} = 0.96 \text{ in.}$$
  
 $M_{2 \text{ min}} = (13.5 \text{ k})(0.96 \text{ in.}) = 12.96 \text{ in-k} = 1.08 \text{ ft-k} < 35.5 \text{ ft-k}$  OK

**(b)** Computing  $\delta$ :

$$\beta_{dns} = \frac{0.9D}{0.9D + 1.0W} = \frac{13.5 \text{ k}}{13.5 \text{ k} + 5.12 \text{ k}} = 0.725$$

$$EI = \frac{(0.4)(3605 \text{ ksi})(1728 \text{ in.}^4)}{1 + 0.725} = 1.44 \times 10^6 \text{ k-in.}^2$$

$$P_c = \frac{(\pi^2)(1.44 \times 10^6 \text{ k-in.}^2)}{(1.00 \times 12 \text{ in/ft} \times 11.25 \text{ ft})^2} = 780 \text{ k}$$

![](_page_360_Figure_2.jpeg)

**FIGURE 11.12** Nonsway and sway load cases for U = 0.9D + 1.0W.

$$C_m = 0.6 + 0.4 \left(\frac{-0 \text{ ft-k}}{35.5 \text{ ft-k}}\right) = 0.6$$

$$\delta = \frac{0.6}{1 - \frac{13.5 \text{ k} + 13.5 \text{ k}}{0.75 \times 2 \times 780 \text{ k}}} = 0.61 < 1.0$$
Use 1.0

(c) Computing  $\delta_s$ :

$$EI = 1.44 \times 10^{6} \text{ k-in.}^{2}$$

$$P_{c} = \frac{780 \text{ k}}{1.95^{2}} = 205 \text{ k}$$

$$\delta_{s} = \frac{1}{1 - \frac{(2)(13.5 \text{ k}) + 5.12 \text{ k} - 5.12 \text{ k}}{1.096}} = 1.096$$

 $\beta_d = 0.725$  (from previous step)

(d) Calculate moment:

$$M_c = (1.0)(35.5 \text{ ft-k}) + (1.096)(76.8 \text{ ft-k}) = 119.7 \text{ ft-k}$$

6. Summary of axial loads and moments to be used in design:

Loading II: 
$$P_u=66~{\rm k},~~M_c=173.5~{\rm ft-k}$$
  
Loading II:  $P_u=48~{\rm k}+5.12~{\rm k}=53.12~{\rm k},~~M_c=227.6~{\rm ft-k}$   
Loading III:  $P_u=13.5~{\rm k}+5.12~{\rm k}=18.62~{\rm k},~~M_c=119.7~{\rm ft-k}$ 

*Note*: Should the reader now wish to determine the reinforcing needed for the above loads and moments, he or she will find that the steel percentage is much too high. As a result, a larger column will have to be used.

#### 11.12 **Computer Examples**

The Excel spreadsheet provided for Chapter 11 computes the effective length factor, k, for both braced and unbraced frames. It uses the same method as Example 11.1, with the exception that it uses the equations from Section 11.5 instead of the Jackson-Moreland Alignment Chart to determine k.

#### Example 11.6

Repeat Example 11.1, using the Excel spreadsheet for Chapter 11.

#### SOLUTION

Open the Chapter 11 spreadsheet and select the k factor tab. Enter the values of the cells highlighted in yellow (only in the Excel spreadsheets, not in the printed example). Note that a value of b = 0 is entered for member AB, since it does not exist. The software determines a value of  $\Psi_{A}=2.99$  and  $\Psi_{B}=2.31.$  These values are the same as those calculated by hand in Example 11.1. The value of k from the spreadsheet is 1.72 if the frame is unbraced compared with 1.74 from the Jackson-Moreland Alignment Chart. If the frame were braced, the software would give a value of k = 0.96. The Jackson-Moreland Alignment Chart gives a value of 0.87. The equations in Section 11.5 do not agree well with the chart in the case of braced frames.

This spreadsheet calculates the *k* factor for column BC.

 $\Psi_{\rm m}$ 

Enter the values of cells in yellow highlight.

If you do not have all the members shown, enter b = 0 for the missing member.

|        | Column      | s    |                  |         | Girder      | s    |                  |
|--------|-------------|------|------------------|---------|-------------|------|------------------|
|        | $f_c'=$     | 4000 | psi              |         | $f_c'=$     | 4000 |                  |
| Col AB | b           | 0    | in.              | Beam EB | b           | 12   | in.              |
|        | h           | 12   | in.              |         | h           | 18   | in.              |
|        | col ht.     | 15   |                  |         | span        | 20   |                  |
|        | $0.70I_{g}$ | 0    | in. <sup>4</sup> |         | $0.35I_{g}$ | 2041 | in. <sup>4</sup> |
| Col BC | b           | 12   | in. <sup>2</sup> | Beam BF | b           | 12   |                  |
|        | h           | 20   |                  |         | h           | 18   |                  |
|        | col ht.     | 10   | ft               |         | span        |      | in.              |
|        | $0.70I_{g}$ | 5600 |                  |         | $0.35I_{g}$ | 2041 | in. <sup>4</sup> |
| Col CD | b           |      | in.              | Beam CG | b           | 12   | in.              |
|        | h           | 20   | in.4             |         | h           | 24   |                  |
|        | col ht.     | 12   | ft               |         | span        | 20   | ft               |
|        | $0.70I_{g}$ | 5600 |                  |         | $0.35I_{g}$ | 4838 | in. <sup>4</sup> |
|        |             |      |                  | Beam CH | b           | 12   | k                |
|        |             |      |                  |         | h           | 24   | k                |
|        |             |      |                  |         | span        | 24   |                  |
|        |             |      |                  |         | $0.35I_{g}$ | 4838 | in.4             |

![](_page_361_Picture_12.jpeg)

$$\Psi_{\rm B} = \begin{array}{c} \frac{E_c \times 0.70 I_g/l_{\rm AB} + E_c \times 0.70 I_g/l_{\rm BC}}{E_c \times 0.35 I_g/l_{\rm BE} + E_c \times 0.35 I_g/l_{\rm BF}} & 2.993 & \textbf{Braced} \\ \Psi_{\rm C} = \frac{E_c \times 0.70 I_g/l_{\rm BC} + E_c \times 0.70 I_g/l_{\rm CD}}{E_c \times 0.35 I_g/l_{\rm CG} + E_c \times 0.35 I_g/l_{\rm CH}} & 2.315 & \textbf{Unbraced} \\ \Psi_{\rm min} & = & 2.315 & \textbf{Unbraced} \end{array}$$

2.654

### Example 11.7

Repeat Example 11.3, using the Excel spreadsheet for Chapter 11.

#### **SOLUTION**

Open the Chapter 11 spreadsheet and select the ''slender column braced rect.'' tab. Enter the values in the cells highlighted in yellow. The value of *As* entered is zero since the column is not yet designed. The software automatically uses ACI Equation 10-15 in this case. If a value for *As* is entered, the software compares the value of *EI* from ACI Equations 10-15 and 10-16 and uses the larger. The final value of δ is 1.093, which is in agreement with the solution obtained in Example 11.3. The final magnified moment, δ*M*2, equals 93.97 ft-k. To complete the design, the Column Design spreadsheets for Chapters 9 and 10 can be used.

|           |                       | Slender Column Braced - Rectangular |                      |  |  |
|-----------|-----------------------|-------------------------------------|----------------------|--|--|
|           | f '<br>c              | 4000                                | psi                  |  |  |
|           | γ                     | 145                                 | pcf                  |  |  |
| Column    | b                     | 12                                  | in.                  |  |  |
|           | h                     | 15 in.                              |                      |  |  |
|           | u                     | 16 ft.                              |                      |  |  |
|           | Ast                   |                                     | 0 in.2               |  |  |
|           | ρg                    | 0                                   |                      |  |  |
| Col loads | PD                    | 30 k                                |                      |  |  |
|           | PL                    | 46.25 k                             |                      |  |  |
|           | M2D                   |                                     | 10 ft-k              |  |  |
|           | M2L                   | 46.25 ft-k                          |                      |  |  |
|           | PU                    | 110 k                               |                      |  |  |
|           | M2                    |                                     | 86 ft-k              |  |  |
|           | M1D                   |                                     | 10 ft-k              |  |  |
|           | M1L                   | 43.75 ft-k                          |                      |  |  |
|           | M1                    |                                     | 82 ft-k              |  |  |
|           | Cm                    | 0.9814                              |                      |  |  |
|           | k                     | 0.83                                |                      |  |  |
|           | k`u⎢r                 | 35.41                               |                      |  |  |
|           | 34-12M1⎢M2            | 22.56                               |                      |  |  |
|           | Is k`u⎢r < 34-12M1⎢M2 |                                     | consider slenderness |  |  |
|           | Ec                    | 3644 psi                            |                      |  |  |
|           | n                     | 7.96                                |                      |  |  |
|           | Ig                    | 3375 in.4                           |                      |  |  |
|           | γ                     | 0.67                                |                      |  |  |
|           | βdns                  | 0.327                               |                      |  |  |
|           | n                     | 0.500                               |                      |  |  |
|           | 0.4EcIgn              |                                     | 4920 k-in.2          |  |  |
|           | EI = 0.4EIn⎢1 + βd    |                                     | 3707 k-in.2          |  |  |
|           | Pc                    | 1440 k                              |                      |  |  |
|           | M2 min                | 9.625 ft-k                          |                      |  |  |
|           |                       | —                                   |                      |  |  |
|           | δ                     | 1.093                               |                      |  |  |
|           | δM2                   | 93.97 ft-k                          |                      |  |  |

Use the Chapter 10 spreadsheet to design this column for

| PU  | 110 k      |  |
|-----|------------|--|
| δM2 | 93.97 ft-k |  |

#### **PROBLEMS**

**Problem 11.1** Using the alignment charts of Figure 11.3, determine the effective length factors for columns CD and DE for the braced frame shown. Assume that the beams are 12 in.  $\times$  20 in. and the columns are 12 in.  $\times$  16 in. Use 0.70 gross moments of inertia of columns and 0.35 gross moments of inertia of beams. Assume  $\psi_A$  and  $\psi_C = 10$ . (Ans. 0.93, 0.88)

![](_page_363_Picture_4.jpeg)

**Problem 11.2** Repeat Problem 11.1 if the column bases are fixed.

Problem 11.3 Using the alignment charts of Figure 11.3, determine the effective length factors for columns AB and BC of the braced frame shown. Assume that all beams are 12 in. × 20 in. and all columns are 12 in. × 16 in. Use 0.70 gross moments of inertia of columns and 0.35 gross moments of inertia of beams. Assume far ends of beams are pinned, and use  $\psi_A = 10$ . (Ans. 0.93, 0.88)

![](_page_363_Picture_7.jpeg)

**Problem 11.4** Repeat Problem 11.3 if the frame is unbraced.

**Problem 11.5** The tied column shown is to be used in a braced frame. It is bent about its *y*-axis with the factored moments shown and  $\ell_u$  is 16 ft. If  $k=1.0, f_y=60,000$  psi, and  $f_c'=4000$  psi, select the reinforcing required. Assume  $P_D=50$  k. (One ans.  $\delta=1.18, 6$  #7)

![](_page_364_Picture_3.jpeg)

**Problem 11.7** Repeat Problem 11.5 if the column is bent in reverse curvature, and its length is 20 ft. Use ACI Equation 10-15 for *El.* (*One ans.*  $\delta = 1.0$ , 6 #6)

![](_page_364_Picture_5.jpeg)

For Problems 11.8 to 11.12 and the braced tied columns given, select reinforcing bars (placed in two faces) if the distance from the column edge to the c.g. of the bars is 2.5 in.,  $f_y = 60$  ksi, and  $f'_c = 4$  ksi. Rectangular columns are bent about their strong axis. Use ACI Equation 10-15 for *EI*.

|             | Column size        |                       |      |           | Not<br>factored | Factored        | Factored        |           |                                            |
|-------------|--------------------|-----------------------|------|-----------|-----------------|-----------------|-----------------|-----------|--------------------------------------------|
| Problem No. | $b \times h$ (in.) | $\ell_u(\mathrm{ft})$ | k    | $P_u$ (k) | $P_D$ (k)       | $M_{1b}$ (ft-k) | $M_{2b}$ (ft-k) | Curvature |                                            |
| 11.8        | 14 × 14            | 12                    | 1.0  | 400       | 100             | 75              | 85              | Single    |                                            |
| 11.9        | 16 × 16            | 16                    | 1.0  | 500       | 120             | 100             | 120             | Double    | ( <i>One ans.</i> $\delta = 1.0, 6 \# 9$ ) |
| 11.10       | 16 × 18            | 15                    | 0.85 | 250       | 40              | 100             | 120             | Single    |                                            |
| 11.11       | 12 × 20            | 16                    | 0.80 | 500       | 120             | 80              | 100             | Single    | (One ans. $\delta = 1.12, 4 \# 9$ )        |
| 11.12       | 14 × 18            | 18                    | 0.90 | 600       | 150             | 100             | 130             | Double    |                                            |

**Problem 11.13** Repeat Problem 11.9 using single curvature and ACI Equation 10-14 for *EI*. Assume six #9 bars to calculate *EI*. (*One ans.*  $\delta = 1.44$ , 8 #10)

For Problems 11.14 to 11.17 and the unbraced tied columns given, select reinforcing bars (placed in two faces) if the distance from the column edge to the c.g. of the bars is 2.5 in.,  $f_y = 60$  ksi, and  $f'_c = 4$  ksi. Rectangular columns are bent about their strong axis. None of the wind load is considered sustained. Use ACI Equation 10-15 for *EI*.

|             |                    |               |      |                 |           |           |           | $M_u$  | $\sum P_u$ (k) | $\sum P_c$ (k) |                   |
|-------------|--------------------|---------------|------|-----------------|-----------|-----------|-----------|--------|----------------|----------------|-------------------|
|             |                    |               |      | $P_u$ (k) for   | $P_u$ (k) |           |           | (ft-k) | for all        | for all        |                   |
|             | Column size        |               |      | loads not       | due to    | $M_{1ns}$ | $M_{2ns}$ | due to | columns        | columns        |                   |
| Problem No. | $b \times h$ (in.) | $\ell_u$ (ft) | k    | considered sway | wind      | (ft-k)    | (ft-k)    | wind   | on floor       | on floor       |                   |
| 11.14       | 16 × 20            | 15            | 1.3  | 500             | 110       | 80        | 90        | 100    | 12,000         | 34,000         |                   |
| 11.15       | 14 × 18            | 12            | 1.4  | 300             | 80        | 70        | 75        | 80     | 10,000         | 30,000         | (One ans. 6 #11)  |
| 11.16       | 16 × 20            | 16            | 1.65 | 500             | 140       | 110       | 140       | 120    | 16,500         | 80,000         |                   |
| 11.17       | 15 × 20            | 12            | 1.5  | 480             | 140       | 90        | 120       | 110    | 14,000         | 36,200         | (One ans. 10 #11) |

#### SI Problems

For Problems 11.18 to 11.20 and the braced tied columns given, select reinforcing bars (placed in two faces) if the distances from column edges to c.g. of bars are 75 mm each. To be able to use Appendix A graphs, use  $f_v = 413.7$  MPa and  $f'_c = 27.6$  MPa. Also remember to apply the conversion factor. Use ACI Equation 10-15 for EI.

| Problem No. | Column size $b \times d$ (mm) | $\ell_u$ (m) | k    | $P_u$ (kN) | P <sub>D</sub> not factored (kN) | M <sub>1b</sub> factored (kN⋅m) | M <sub>2b</sub><br>factored<br>(kN•m) | Curvature |                  |
|-------------|-------------------------------|--------------|------|------------|----------------------------------|---------------------------------|---------------------------------------|-----------|------------------|
| 11.18       | 450 × 450                     | 4            | 1.0  | 1800       | 400                              | 80                              | 100                                   | Single    |                  |
| 11.19       | 300 × 400                     | 5            | 0.92 | 2200       | 500                              | 110                             | 125                                   | Double    | (One ans. 6 #32) |
| 11.20       | 300 × 500                     | 6            | 0.88 | 2400       | 550                              | 120                             | 140                                   | Single    |                  |

For Problems 11.21 to 11.23 and the unbraced tied columns given, select reinforcing bars (placed on two faces) if the distance from the column edge to the c.g. of the bars is 75 mm.  $f_v = 420$  MPa and  $f_c' = 28$  MPa. Remember to apply the conversion factor. Use ACI Equation 10-15 for EI.

|             |                                |                      |      | P <sub>u</sub> (kN) | P <sub>u</sub> (kN) |                  |                  | $M_u$ (kN·m) | $\frac{\sum P_u \text{ (kN)}}{\text{for all}}$ | $ \sum_{\text{for all}} P_c \text{ (kN)} $ |                  |
|-------------|--------------------------------|----------------------|------|---------------------|---------------------|------------------|------------------|--------------|------------------------------------------------|--------------------------------------------|------------------|
| Problem No. | Column size $b \times d$ (in.) | $\ell_u(\mathbf{m})$ | k    | considered<br>sway  | u · ·               | $M_{1ns}$ (kN•m) | $M_{2ns}$ (kN•m) | due to wind  | columns<br>on floor                            | columns<br>on floor                        |                  |
| 11.21       | 300 × 400                      | 5                    | 1.2  | 400                 | 1200                | 40               | 50               | 60           | 40 000                                         | 110 000                                    | (One ans. 6 #32) |
| 11.22       | 300 × 500                      | 4                    | 1.3  | 500                 | 1800                | 50               | 60               | 70           | 44 000                                         | 125 000                                    |                  |
| 11.23       | 350 × 600                      | 6                    | 1.35 | 600                 | 2500                | 65               | 90               | 110          | 50 000                                         | 156 000                                    | (One ans. 6 #32) |

