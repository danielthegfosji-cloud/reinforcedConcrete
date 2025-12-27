# Design of Short Columns Subject **CHA PTER 10** to Axial Load and Bending

### **10.1 Axial Load and Bending**

All columns are subjected to some bending as well as axial forces, and they need to be proportioned to resist both. The so-called axial load formulas presented in Chapter 9 do take into account some moments, because they include the effect of small eccentricities with the 0.80 and 0.85 factors. These values are approximately equivalent to the assumption of actual eccentricities of 0.10*h* for tied columns and 0.05*h* for spiral columns.

Columns will bend under the action of moments, and those moments will tend to produce compression on one side of the columns and tension on the other. Depending on the relative magnitudes of the moments and axial loads, there are several ways in which the sections might fail. Figure 10.1 shows a column supporting a load, *Pn*. In the various parts of the figure, the load is placed at greater and greater eccentricities (thus producing larger and larger moments) until finally in part (f) the column is subject to such a large bending moment that the effect of the axial load is negligible. Each of the six cases shown is briefly discussed in the paragraphs to follow, where the letters (a) through (f) correspond to those same letters in the figure. The column is assumed to reach its ultimate capacity when the compressive concrete strain reaches 0.003.

- **(a)** *Large axial load with negligible moment*—For this situation, failure will occur by the crushing of the concrete, with all reinforcing bars in the column having reached their yield stress in compression.
- **(b)** *Large axial load and small moment such that the entire cross section is in compression*—When a column is subject to a small bending moment (i.e., when the eccentricity is small), the entire column will be in compression, but the compression will be higher on one side than on the other. The maximum compressive stress in the column will be 0.85*f <sup>c</sup>* , and failure will occur by the crushing of the concrete with all the bars in compression.
- **(c)** *Eccentricity larger than in case (b) such that tension begins to develop on one side of the column*—If the eccentricity is increased somewhat from the preceding case, tension will begin to develop on one side of the column, and the steel on that side will be in tension but less than the yield stress. On the other side, the steel will be in compression. Failure will occur as a result of the crushing of the concrete on the compression side.
- **(d)** *A balanced loading condition*—As we continue to increase the eccentricity, a condition will be reached in which the reinforcing bars on the tension side will reach their yield stress at the same time that the concrete on the opposite side reaches its maximum compression, 0.85*f <sup>c</sup>* . This situation is called the *balanced loading condition*.
- **(e)** *Large moment with small axial load*—If the eccentricity is further increased, failure will be initiated by the yielding of the bars on the tensile side of the column prior to concrete crushing.
- **(f)** *Large moment with no appreciable axial load*—For this condition, failure will occur as it does in a beam.

![](_page_301_Figure_2.jpeg)

**FI GU RE 10.1** Column subject to load with larger and larger eccentricities.

### **10.2 The Plastic Centroid**

The eccentricity of a column load is the distance from the load to the *plastic centroid* of the column. The plastic centroid represents the location of the resultant force produced by the steel and the concrete. It is the point in the column cross section through which the resultant column load must pass to produce uniform strain at failure. For locating the plastic centroid, all concrete is assumed to be stressed in compression to 0.85*f <sup>c</sup>* and all steel to *fy* in compression. For symmetrical sections, the plastic centroid coincides with the centroid of the column cross section, while for nonsymmetrical sections, it can be located by taking moments.

Example 10.1 illustrates the calculations involved in locating the plastic centroid for a nonsymmetrical cross section. The ultimate load, *Pn*, is determined by computing the total

![](_page_302_Picture_2.jpeg)

Pennsylvania Southern Expressway, Philadelphia, Pennsylvania.

compressive forces in the concrete and the steel and adding them together. *Pn* is then assumed to act downward at the plastic centroid, at a distance *x* from one side of the column, and moments are taken on that side of the column of the upward compression forces acting at their centroids and the downward *Pn*.

#### Example 10.1

Determine the plastic centroid of the T-shaped column shown in Figure 10.2 if *f <sup>c</sup>* = 4000 psi and *fy* = 60,000 psi.

#### **SOLUTION**

The plastic centroid falls on the *x*-axis, as shown in Figure 10.2, because of symmetry. The column is divided into two rectangles, the left one being 16 in. × 6 in. and the right one 8 in. × 8 in. *C*<sup>1</sup> is assumed to be the total compression in the left concrete rectangle, *C*<sup>2</sup> the total compression in the right rectangle, and *C <sup>s</sup>* the total compression in the reinforcing bars.

$$C_1 = (16 \text{ in.}) (6 \text{ in.}) (0.85) (4 \text{ ksi}) = 326.4 \text{ k}$$
  
 $C_2 = (8 \text{ in.}) (8 \text{ in.}) (0.85) (4 \text{ ksi}) = 217.6 \text{ k}$ 

![](_page_303_Figure_2.jpeg)

**FI GU RE 10.2** Column cross section for Example 10.1.

In computing *C <sup>s</sup>*, the concrete where the bars are located is subtracted; that is,

$$C_s' = (4.00 \text{ in.}^2) \, (60 \text{ ksi} - 0.85 \times 4 \text{ ksi}) = 226.4 \text{ k}$$
   
 Total compression =  $P_n = 326.4 \text{ k} + 217.6 \text{ k} + 226.4 \text{ k} = 770.4 \text{ k}$ 

#### **Taking Moments about Left Edge of Column**

$$-(326.4 \text{ k}) (3 \text{ in.}) - (217.6 \text{ k}) (10 \text{ in.}) - (226.4 \text{ k}) (7 \text{ in.}) + (770.4 \text{ k}) ( $\overline{x}$ ) = 0  $\overline{x}$  = 6.15 in.$$

### **10.3 Development of Interaction Diagrams**

Should an axial compressive load be applied to a short concrete member, it will be subjected to a uniform strain or shortening, as is shown in Figure 10.3(a). If a moment with zero axial load is applied to the same member, the result will be bending about the member's neutral axis such that strain is proportional to the distance from the neutral axis. This linear strain variation is shown in Figure 10.3(b). Should axial load and moment be applied at the same time, the resulting strain diagram will be a combination of two linear diagrams and will itself be linear, as illustrated in Figure 10.3(c). As a result of this linearity, we can assume certain numerical values of strain in one part of a column and determine strains at other locations by straight-line interpolation.

As the axial load applied to a column is changed, the moment that the column can resist will change. This section shows how an interaction curve of nominal axial load and moment values can be developed for a particular column.

Assuming that the concrete on the compression edge of the column will fail at a strain of 0.003, a strain can be assumed on the far edge of the column, and the values of *Pn* and *Mn* can be computed by statics. Holding the compression strain at 0.003 on the far edge, we can then assume a series of different strains on the other edge and calculate *Pn* and *Mn* for each.1 Eventually a sufficient number of values will be obtained to plot an interaction curve

<sup>1</sup> Leet, K., 1991, *Reinforced Concrete Design*, 2nd ed. (New York: McGraw-Hill), pp. 316–317.

such as the one shown in Figure 10.8. Example 10.2 illustrates the calculation of *Pn* and *Mn* for a column for one set of assumed strains.

![](_page_304_Figure_3.jpeg)

**FI GU RE 10.3** Column strains.

#### Example 10.2

It is assumed that the tied column of Figure 10.4 has a strain on its compression edge equal to −0.003 and has a tensile strain of +0.002 on its other edge. Determine the values of *Pn* and *Mn* that cause this strain distribution if *fy* = 60 ksi and *f <sup>c</sup>* = 4 ksi.

#### **SOLUTION**

Determine the values of *c* and of the steel strains *<sup>s</sup>* and *<sup>s</sup>* by proportions with reference to the strain diagram shown in Figure 10.5.

$$c = \left(\frac{0.003}{0.003 + 0.002}\right) (24 \text{ in.}) = 14.40 \text{ in.}$$

$$\epsilon'_s = \left(\frac{11.90 \text{ in.}}{14.40 \text{ in.}}\right) (0.003) = 0.00248 > 0.00207 \quad \underline{\because \text{ yields}}$$

$$\epsilon_s = \left(\frac{7.10 \text{ in.}}{9.60 \text{ in.}}\right) (0.002) = 0.00148 \quad \underline{\text{does not yield}} \qquad \therefore \phi = 0.65 \text{ (Section 3.7)}$$

![](_page_304_Figure_10.jpeg)

**FI GU RE 10.4** Column cross section for Example 10.2.

![](_page_305_Figure_2.jpeg)

**FIGURE 10.5** Strain diagram for Example 10.2.

In the following calculations,  $C_c$  is the total compression in the concrete,  $C_s'$  is the total compression in the compression steel, and  $T_{\rm s}$  is the total tension in the tensile steel. Each of these values is computed below.

The reader should note that  $C_s'$  is reduced by  $0.85f_c'A_s'$  to account for concrete displaced by the steel in compression.

$$a = (0.85) (14.40 \text{ in.}) = 12.24 \text{ in.}$$
  
 $C_c = (0.85) (12.24 \text{ in.}) (14 \text{ in.}) (4.0 \text{ ksi}) = -582.62 \text{ k}$   
 $C_s' = (60 \text{ ksi}) (3.0 \text{ in.}^2) - (0.85) (3.0 \text{ in.}^2) (4.0 \text{ ksi}) = -169.8 \text{ k}$   
 $T_s = (0.00148) (29,000 \text{ ksi}) (3.0 \text{ in.}^2) = +128.76 \text{ k}$ 

By statics,  $P_n$  and  $M_n$  are determined with reference to Figure 10.6, where the values of  $C_c$ ,  $C'_s$ , and  $T_s$  are shown.

$$\Sigma V = 0$$
 
$$-P_n + 169.8 \text{ k} + 582.62 \text{ k} - 128.76 \text{ k} = 0$$
 
$$P_n = 623.7 \text{ k}$$
 
$$\phi P_n = (0.65)(623.7 \text{ k}) = 405.4 \text{ k}$$

![](_page_305_Figure_9.jpeg)

FIGURE 10.6 Internal column forces for Example 10.2.

### *M* **= 0 about Tensile Steel**

(623.7 k) (9.50 in.) + 
$$M_n$$
 - (582.62 k) (15.38 in.) - (169.8 k) (19.00 in.) = 0 
$$M_n = 6261.3 \text{ in-k} = 521.8 \text{ ft-k}$$
 
$$\phi M_n = (0.65) (6261.3 \text{ in-k}) = 4069.8 \text{ in-k} = 339.2 \text{ ft-k}$$

In this manner, a series of *Pn* and *Mn* values is determined to correspond with a strain of −0.003 on the compression edge and varying strains on the far column edge. The resulting values are plotted on a curve, as shown in Figure 10.8.

A few remarks are made here concerning the extreme points on this curve. One end of the curve will correspond to the case where *Pn* is at its maximum value and *Mn* is zero. For this case, *Pn* is determined as in Chapter 9 for the axially loaded column of Example 10.2.

$$P_n = 0.85f'_c(A_g - A_s) + A_s f_y$$
  
= (0.85) (4.0 ksi) (14 in. × 24 in. – 6.00 in.²) + (6.00 in.²) (60 ksi)  
= 1482 k

On the other end of the curve, *Mn* is determined for the case where *Pn* is zero. This is the procedure used for a doubly reinforced member as previously described in Chapter 5. For the column of Example 10.2, *Mn* is equal to 297 ft-k.

A column reaches its ultimate capacity when the concrete reaches a compressive strain of 0.003. If the steel closest to the extreme tension side of the column reaches yield strain, or even more when the concrete reaches a strain of 0.003, the column is said to be tension controlled; otherwise, it is compression controlled. The transition point between these regions

![](_page_306_Picture_9.jpeg)

Washington Redskins Stadium.

![](_page_307_Figure_2.jpeg)

FIGURE 10.7 Strain diagram for balanced conditions.

is the balance point. In Chapter 3, the term balanced section was used in referring to a section whose compression concrete strain reached 0.003 at the same time as the tensile steel reached its yield strain at  $f_v/E_s$ . In a beam, this situation theoretically occurred when the steel percentage equaled  $\rho_h$ . A column can undergo a balanced failure no matter how much steel it has if it has the right combination of moment and axial load.

For columns, the definition of balanced loading is the same as it was for beams—that is, a column that has a strain of 0.003 on its compression side at the same time that its tensile steel on the other side has a strain of  $f_{\nu}/E_{\varsigma}$ . Although it is easily possible to prevent a balanced condition in beams by requiring that tensile steel strains be kept well above  $f_v/E_s$ , such is not the case for columns. Thus, for columns, it is not possible to prevent sudden compression failures or balanced failures. For every column, there is a balanced loading situation where an ultimate load,  $P_{bn}$ , placed at an eccentricity,  $e_b$ , will produce a moment,  $M_{bn}$ , at which time the balanced strains will be reached simulataneously.

At the balanced condition, we have a strain of -0.003 on the compression edge of the column and a strain of  $f_{\nu}/29 \times 10^3$  ksi =  $60 \text{ ksi}/29 \times 10^3$  ksi = 0.00207 in the tensile steel. This information is shown in Figure 10.7. The same procedure used in Example 10.2 is used to find  $P_n = 504.4 \text{ k}$  and  $M_n = 559.7 \text{ ft-k}$ .

The curve for  $P_n$  and  $M_n$  for a particular column may be extended into the range where  $P_n$  becomes a tensile load. We can proceed in exactly the same fashion as we did when  $P_n$  was compressive. A set of strains can be assumed, and the usual statics equations can be written and solved for  $P_n$  and  $M_n$ . Several different sets of strains were assumed for the column of Figure 10.4, and then the values of  $P_n$  and  $M_n$  were determined. The results were plotted at the bottom of Figure 10.8 and were connected with the dashed line labeled "tensile loads."

![](_page_307_Figure_8.jpeg)

**FIGURE 10.8** Interaction curve for the column of Figure 10.4. Notice these are nominal values.

![](_page_308_Picture_2.jpeg)

Round columns.

Because axial tension and bending are not very common for reinforced concrete columns, the tensile load part of the curves is not shown in subsequent figures in this chapter. You will note that the largest tensile value of *Pn* will occur when the moment is zero. For that situation, all of the column steel has yielded, and all of the concrete has cracked. Thus, *Pn* will equal the total steel area, *As*, times the yield stress. For the column of Figure 10.4

$$P_n = A_s f_y = (6.0 \text{ in.}^2)(60 \text{ ksi}) = 360 \text{ k}$$

On some occasions, members subject to axial load and bending have unsymmetrical arrangements of reinforcing. Should this be the case, you must remember that eccentricity is correctly measured from the plastic centroid of the section.

In this chapter, *Pn* values were obtained only for rectangular tied columns. The same theory could be used for round columns, but the mathematics would be somewhat complicated because of the circular layout of the bars, and the calculations of distances would be rather tedious. Several approximate methods have been developed that greatly simplify the mathematics. Perhaps the best known of these is the one proposed by Charles Whitney, in which equivalent rectangular columns are used to replace the circular ones.2 This method gives results that correspond quite closely with test results.

In Whitney's method, the area of the equivalent column is made equal to the area of the actual circular column, and its depth in the direction of bending is 0.80 times the outside diameter of the real column. One-half the steel is assumed to be placed on one side of the equivalent column and one-half on the other. The distance between these two areas of steel is assumed to equal two-thirds of the diameter (*Ds*) of a circle passing through the center of the bars in the real column. These values are illustrated in Figure 10.9. Once the equivalent column is established, the calculations for *Pn* and *Mn* are made as for rectangular columns.

<sup>2</sup> Whitney, Charles S., 1942, "Plastic Theory of Reinforced Concrete Design," *Transactions ASCE*, 107, pp. 251–326.

![](_page_309_Picture_2.jpeg)

**FI GU RE 10.9** Replacing a circular column with an equivalent rectangular one.

### **10.4 Use of Interaction Diagrams**

We have seen that by statics, the values of *Pn* and *Mn* for a given column with a certain set of strains can easily be determined. Preparing an interaction curve with a hand calculator for just one column, however, is quite tedious. Imagine the work involved in a design situation where various sizes, concrete strengths, and steel percentages need to be considered. Consequently, designers resort almost completely to computer programs, computer-generated interaction diagrams, or tables for their column calculations. The remainder of this chapter is concerned primarily with computer-generated interaction diagrams such as the one in Figure 10.10. As we have seen, such a diagram is drawn for a column as the load changes from one of a pure axial nature through varying combinations of axial loads and moments and on to a pure bending situation.

Interaction diagrams are useful for studying the strengths of columns with varying proportions of loads and moments. Any combination of loading that falls inside the curve is satisfactory, whereas any combination falling outside the curve represents failure.

If a column is loaded to failure with an axial load only, the failure will occur at point *A* on the diagram (Figure 10.10). Moving out from point *A* on the curve, the axial load capacity decreases as the proportion of bending moment increases. At the very bottom of the curve, point *C* represents the bending strength of the member if it is subjected to moment only with no axial load present. In between the extreme points *A* and *C*, the column fails because of a combination of axial load and bending. Point *B* is called the *balanced point* and represents the balanced loading case, where theoretically a compression failure and tensile yielding occur simultaneously.

Refer to point *D* on the curve. The horizontal and vertical dashed lines to this point indicate a particular combination of axial load and moment at which the column will fail. Should a radial line be drawn from point 0 to the interaction curve at any point (as to *D* in this case), it will represent a constant eccentricity of load, that is, a constant ratio of moment to axial load.

You may be somewhat puzzled by the shape of the lower part of the curve from *B* to *C*, where bending predominates. From *A* to *B* on the curve, the moment capacity of a section increases as the axial load decreases, but just the opposite occurs from *B* to *C*. A little thought on this point, however, shows that the result is quite logical after all. The part of the curve from *B* to *C* represents the range of tensile failures. Any axial compressive load in that range tends to reduce the stresses in the tensile bars, with the result that a larger moment can be resisted.

![](_page_310_Figure_2.jpeg)

**FI GU RE 10.10** Column interaction diagram.

![](_page_310_Picture_4.jpeg)

Reinforced concrete columns.

![](_page_311_Figure_2.jpeg)

**FI GU RE 10.11** Interaction curves for a rectangular column with different sets of reinforcing bars.

In Figure 10.11, an interaction curve is drawn for the 14-in. × 24-in. column with six #9 bars considered in Section 10.3. If eight #9 bars had been used in the same dimension column, another curve could be generated as shown in the figure; if ten #9 bars were used, still another curve would result. The shape of the new diagrams would be the same as for the six #9 curve, but the values of *Pn* and *Mn* would be larger.

### **10.5 Code Modifications of Column Interaction Diagrams**

If interaction curves for *Pn* and *Mn* values were prepared, they would be of the types shown in Figures 10.10 and 10.11. To use such curves to obtain design values, they would have to have three modifications made to them as specified in the code. These modifications are as follows:

- **(a)** ACI Code 9.3.2 specifies strength reduction or φ factors (0.65 for tied columns and 0.75 for spiral columns) that must be multiplied by *Pn* values. If a *Pn* curve for a particular column were multiplied by φ, the result would be a curve something like the ones shown in Figure 10.12.
- **(b)** The second modification also refers to φ factors. The code specifies values of 0.65 and 0.75 for tied and spiral columns, respectively. Should a column have quite a large

![](_page_311_Figure_9.jpeg)

**FI GU RE 10.12** Curves for *Pn* and φ*Pn* for a single column.

moment and a very small axial load so that it falls on the lower part of the curve between points *B* and *C* (see Figure 10.10), the use of these small φ values may be a little unreasonable. For instance, for a member in pure bending (point *C* on the same curve), the specified φ is 0.90, but if the same member has a very small axial load added, φ would immediately fall to 0.65 or 0.75. Therefore, the code (9.3.2.2) states that when members subject to axial load and bending have net tensile strains (*<sup>t</sup>* ) between the limits for compression-controlled and tensile-controlled sections, they fall in the transition zone for φ. In this zone, it is permissible to increase φ linearly from 0.65 or 0.75 to 0.90 as *<sup>t</sup>* increases from the compression-controlled limit to 0.005. In this regard, the reader is again referred to Figure 3.5 in Chapter 3 where the transition zone and the variation of φ values are clearly shown. This topic is continued in Section 10.10.

**(c)** As described in Chapter 9, maximum permissible column loads were specified for columns no matter how small their *e* values. As a result, the upper part of each design interaction curve is shown as a horizontal line representing the appropriate value of

$$P_u = \phi P_{n \text{ max}} \text{ for tied columns} = 0.80 \phi [0.85 f_c' (A_g - A_{st}) + f_y A_{st}]$$
 (ACI Equation 10-2)

$$P_u = \phi P_{n \text{ max}} \text{ for spiral columns} = 0.85 \phi [0.85 f_c'(A_g - A_{st}) + f_y A_{st}]$$
 (ACI Equation 10-1)

These formulas were developed to be approximately equivalent to loads applied with eccentricities of 0.10*h* for tied columns and 0.05*h* for spiral columns.

Each of the three modifications described here is indicated on the design curve of Figure 10.13. In Figure 10.13, the solid curved line represents *Pu* and *Mu*, whereas the dashed curved line is *Pn* and *Mn*. The difference between the two curves is the φ factor. The two curves would have the same shape if the φ factor did not vary. Above the radial line labeled

![](_page_312_Figure_8.jpeg)

**FI GU RE 10.13** A column interaction curve adjusted for the three modifications described in this section (10.5).

"balanced case,"  $\phi = 0.65$  (0.75 for spirals). Below the other radial line, labeled "strain of 0.005,"  $\phi = 0.9$ . It varies between the two values in between, and the  $P_n$  versus  $M_n$  curve assumes a different shape.

### **Design and Analysis of Eccentrically Loaded Columns Using Interaction Diagrams**

If individual column interaction diagrams were prepared as described in the preceding sections, it would be necessary to have a diagram for each different column cross section, for each different set of concrete and steel grades, and for each different bar arrangement. The result would be an astronomical number of diagrams. The number can be tremendously reduced, however, if the diagrams are plotted with ordinates of  $K_n = P_n/f_c'A_g$  (instead of  $P_n$ ) and with abscissas of  $R_n = P_n e/f_c' A_g h$  (instead of  $M_n$ ). The resulting normalized interaction diagrams can be used for cross sections with widely varying dimensions. The ACI has prepared normalized interaction curves in this manner for the different cross section and bar arrangement situations shown in Figure 10.14 and for different grades of steel and concrete.<sup>3</sup>

Two of the ACI diagrams are given in Figures 10.15 and 10.16, while Appendix A (Graphs 2 to 13) presents several other ones for the situations given in parts (a), (b), and (d) of Figure 10.14. Notice that these ACI diagrams do not include the three modifications described in the last section.

The ACI column interaction diagrams are used in Examples 10.3 to 10.7 to design or analyze columns for different situations. In order to correctly use these diagrams, it is necessary to compute the value of  $\gamma$  (gamma), which is equal to the distance from the center of the bars on one side of the column to the center of the bars on the other side of the column divided by h,

![](_page_313_Figure_7.jpeg)

FIGURE 10.14 Column cross sections for normalized interaction curves in Appendix A, Graphs 2-13.

<sup>&</sup>lt;sup>3</sup> American Concrete Institute, 1997, Design Handbook (Farmington Hills, MI: ACI). Publication SP-17 (97).

![](_page_314_Figure_2.jpeg)

**FIGURE 10.15** ACI rectangular column interaction diagrams when bars are placed on two faces only. (Permission of American Concrete Institute.)

the depth of the column (both values being taken in the direction of bending). Usually the value of  $\gamma$  obtained falls in between a pair of curves, and interpolation of the curve readings will have to be made.

#### Caution

Be sure that the column picture at the upper right of the interaction curve being used agrees with the column being considered. In other words, are there bars on two faces of the column or on all four faces? If the wrong curves are selected, the answers may be quite incorrect.

Although several methods are available for selecting column sizes, a trial-and-error method is about as good as any. With this procedure, the designer estimates what he or she thinks is a reasonable column size and then determines the steel percentage required for that column size from the interaction diagram. If it is felt that the  $\rho_g$  determined is unreasonably large or small, another column size can be selected and the new required  $\rho_g$  selected from the diagrams, and so on. In this regard, the selection of columns for which  $\rho_g$  is greater than 4% or 5% results in congestion of the steel, particularly at splices, and consequent difficulties in getting the concrete down into the forms.

![](_page_315_Figure_2.jpeg)

ACI rectangular column interaction diagram when bars are placed along all four faces. (Permission of American Concrete Institute.)

A slightly different approach is used in Example 10.4, where the average compression stress at ultimate load across the column cross section is assumed to equal some value—say,  $0.5f_c'$  to  $0.6f_c'$ . This value is divided into  $P_n$  to determine the column area required. Crosssectional dimensions are then selected, and the value of  $\rho_{\rho}$  is determined from the interaction curves. Again, if the percentage obtained seems unreasonable, the column size can be revised and a new steel percentage obtained.

In Examples 10.3 to 10.5, reinforcing bars are selected for three columns. The values of  $K_n = P_n/f_c/A_g$  and  $R_n = P_n e/f_c/A_g h$  are computed. The position of those values is located on the appropriate graph, and  $\rho_g$  is determined and multiplied by the gross area of the column in question to determine the reinforcing area needed.

#### Example 10.3

The short 14-in.  $\times$  20-in. tied column of Figure 10.17 is to be used to support the following loads and moments:  $P_D=125~{\rm k},\,P_L=140~{\rm k},\,M_D=75~{\rm ft}$ -k, and  $M_L=90~{\rm ft}$ -k. If  $f_c'=4000~{\rm psi}$  and  $f_{\nu}=60,000$  psi, select reinforcing bars to be placed in its end faces only using appropriate ACI column interaction diagrams.

![](_page_316_Figure_2.jpeg)

**FIGURE 10.17** Column cross section for Example 10.3.

#### SOLUTION

$$\begin{split} P_u &= (1.2) (125 \text{ k}) + (1.6) (140 \text{ k}) = 374 \text{ k} \\ P_n &= \frac{374 \text{ k}}{0.65} = 575.4 \text{ k} \\ M_u &= (1.2) (75 \text{ ft-k}) + (1.6) (90 \text{ ft-k}) = 234 \text{ ft-k} \\ M_n &= \frac{234 \text{ ft-k}}{0.65} = 360 \text{ ft-k} \\ e &= \frac{(12 \text{ in/ft}) (360 \text{ ft-k})}{575.4 \text{ k}} = 7.51 \text{ in.} \\ \gamma &= \frac{15 \text{ in.}}{20 \text{ in.}} = 0.75 \end{split}$$

Compute values of  $K_n$  and  $R_n$ 

$$K_n = \frac{P_n}{f'_c A_g} = \frac{575.4 \text{ k}}{(4 \text{ ksi}) (14 \text{ in.} \times 20 \text{ in.})} = 0.513$$

$$R_n = \frac{P_n e}{f'_c A_c h} = \frac{(575.4 \text{ k}) (7.51 \text{ in.})}{(4 \text{ ksi}) (14 \text{ in.} \times 20 \text{ in.}) (20 \text{ in.})} = 0.193$$

The value of  $\gamma$  falls between  $\gamma$  values for Graphs 3 and 4 of Appendix A. Therefore, interpolating between the two as follows:

| γ          | 0.70   | 0.75   | 0.80   |
|------------|--------|--------|--------|
| $\rho_{g}$ | 0.0220 | 0.0202 | 0.0185 |

$$A_s = \rho_a bh = (0.0202) (14 \text{ in.}) (20 \text{ in.}) = 5.66 \text{ in.}^2$$

 $\underline{\text{Use 6 #9 bars} = 6.00 in.}^2$ 

#### **Notes**

- (a) Note that  $\phi=0.65$  as initially assumed since the graphs used show  $f_{\rm s}/f_{\rm y}$  is < 1.0 and, thus,  $\epsilon_t<0.002$ .
- (b) Code requirements must be checked as in Example 9.1. (See Figure 10.25 to visualize this.)

#### Example 10.4

Design a short square column for the following conditions:  $P_u=600$  k,  $M_u=80$  ft-k,  $f_c'=4000$  psi, and  $f_y=60,000$  psi. Place the bars uniformly around all four faces of the column.

#### SOLUTION

Assume the column will have an average compression stress = about  $0.6f'_c = 2400 \text{ psi} = 2.4 \text{ ksi.}$ 

$$A_{g \text{ required}} = \frac{600 \text{ k}}{2.4 \text{ ksi}} = 250 \text{ in.}^2$$

Try a 16-in.  $\times$  16-in. column ( $A_q=256$  in.<sup>2</sup>) with the bar arrangement shown in Figure 10.18.

$$e = \frac{M_u}{P_u} = \frac{(12 \text{ in/ft}) (80 \text{ ft-k})}{600 \text{ k}} = 1.60 \text{ in.}$$

$$P_n = \frac{P_u}{\phi} = \frac{600 \text{ k}}{0.65} = 923.1 \text{ k}$$

$$K_n = \frac{P_n}{f_c'A_g} = \frac{923.1 \text{ k}}{(4 \text{ ksi}) (16 \text{ in.} \times 16 \text{ in.})} = 0.901$$

$$R_n = \frac{P_n e}{f_c'A_g h} = \frac{(923.1 \text{ k}) (1.6 \text{ in.})}{(4 \text{ ksi}) (16 \text{ in.} \times 16 \text{ in.}) (16 \text{ in.})} = 0.0901$$

$$\gamma = \frac{11 \text{ in.}}{16 \text{ in}} = 0.6875$$

Interpolating between values given in Graphs 6 and 7 of Appendix A.

| γ          | 0.600 | 0.6875 | 0.700 |
|------------|-------|--------|-------|
| $\rho_{g}$ | 0.025 | 0.023  | 0.022 |

$$A_s = (0.023)(16 \text{ in.})(16 \text{ in.}) = 5.89 \text{ in.}^2$$

Use 8 #8 bars =  $6.28 \text{ in.}^2$ 

![](_page_317_Figure_13.jpeg)

**FIGURE 10.18** Column cross section for Example 10.4.

#### Notes

- (a) Note that  $\phi=0.65$  as initially assumed since the graphs used show  $f_{\rm S}/f_{\rm y}<1.0$  and, thus,  $\epsilon_{\rm t}<0.002$ .
- (b) Code requirements must be checked as in Example 9.1. (See Figure 10.25.)

#### Example 10.5

Using the ACI column interaction graphs, select reinforcing for the short round spiral column shown in Figure 10.19 if  $f'_c = 4000$  psi,  $f_v = 60,000$  psi,  $P_u = 500$  k, and  $M_u = 225$  ft-k.

#### SOLUTION

$$e = \frac{(12 \text{ in/ft}) (225 \text{ ft-k})}{500 \text{ k}} = 5.40 \text{ in.}$$

$$P_n = \frac{P_u}{\phi} = \frac{500 \text{ k}}{0.75} = 666.7 \text{ k}$$

$$K_n = \frac{P_n}{f_c' A_g} = \frac{666.7 \text{ k}}{(4 \text{ ksi}) (314 \text{ in.}^2)} = 0.531$$

$$R_n = \frac{P_n e}{f_c' A_g h} = \frac{(666.7 \text{ k}) (5.40 \text{ in.})}{(4 \text{ ksi}) (314 \text{ in.}^2) (20 \text{ in.})} = 0.143$$

$$\gamma = \frac{15 \text{ in.}}{20 \text{ in.}} = 0.75$$

By interpolation between Graphs 11 and 12 of Appendix A,  $\rho_g$  is found to equal 0.0235 and  $f_{\rm S}/f_{\rm V}<$  1.0.

$$\rho A_q = (0.0235)(314 \text{ in.}^2) = 7.38 \text{ in.}^2$$

Use 8 #9 bars =  $8.00 \text{ in.}^2$ 

The same notes apply here as for Examples 10.3 and 10.4.

![](_page_318_Picture_13.jpeg)

FIGURE 10.19 Column cross section for Example 10.5.

In Example 10.6, it is desired to select a 14-in. wide column with approximately 2% steel. This is done by trying different column depths and then determining the steel percentage required in each case.

#### Example 10.6

Design a 14-in.-wide rectangular short tied column with bars only in the two end faces for  $P_u = 500$  k,  $M_u = 250$  ft-k,  $f_c' = 4000$  psi, and  $f_v = 60,000$  psi. Select a column with approximately 2% steel.

#### SOLUTION

$$e = \frac{M_u}{P_u} = \frac{(12 \text{ in/ft}) (250 \text{ ft-k})}{500 \text{ k}} = 6.00 \text{ in.}$$

$$P_n = \frac{P_u}{\phi} = \frac{500 \text{ k}}{0.65} = 769.2 \text{ k}$$

Trying several column sizes and determining reinforcing.

| Trial sizes (in.)                      | 14 × 20 | 14 × 22 | 14 × 24 |
|----------------------------------------|---------|---------|---------|
| $K_n = \frac{P_n}{f_c' A_g}$           | 0.687   | 0.624   | 0.572   |
| $R_n = \frac{P_n e}{f_c' A_g h}$       | 0.206   | 0.170   | 0.143   |
| $\gamma = \frac{h - 2 \times 2.50}{h}$ | 0.750   | 0.773   | 0.792   |
| $ ho_g$ by interpolation               | 0.0315  | 0.020   | 0.011   |

Use 14-in. × 22-in. column

$$A_a = (0.020) (14 \text{ in.} \times 22 \text{ in.}) = 6.16 \text{ in.}^2$$

Use 8 #8 bars =  $6.28 \text{ in.}^2$ 

Same notes as for Examples 10.3 and 10.4.

One more illustration of the use of the ACI interaction is presented with Example 10.7. In this example, the nominal column load  $P_n$  at a given eccentricity that a column can support is determined.

With reference to the ACI interaction curves, the reader should carefully note that the value of  $R_n$  (which is  $P_n e/f_c A_g h$ ) for a particular column equals e/h times the value of  $K_n$   $(P_n/f_c/A_a)$  for that column. This fact needs to be understood when the user desires to determine the nominal load that a column can support at a given eccentricity.

In Example 10.7, the nominal load that the short column of Figure 10.20 can support at an eccentricity of 10 in. with respect to the x-axis is determined. If we plot on the interaction diagram the intersection point of  $K_n$  and  $R_n$  for a particular column and draw a straight line from that point to the lower-left corner or origin of the figure, we will have a line with a constant e/h. For the column of Example 10.6, e/h = 10 in./20 in. = 0.5. Therefore, a line is plotted from the origin through a set of assumed values for  $K_n$  and  $R_n$  in the proportion of 10/20 to each other. In this case,  $K_n$  was set equal to 0.8 and  $R_n = 0.5 \times 0.8 = 0.4$ . Next, a line was drawn from that intersection point to the origin of the diagram, as shown in Figure 10.16. Finally, the intersection of this line with  $\rho_g$  (0.0316 in this example) was determined, and the value of  $K_n$  or  $R_n$  was read. This latter value enables us to compute  $P_n$ .

![](_page_320_Figure_2.jpeg)

**FIGURE 10.20** Column cross section for Example 10.6.

#### Example 10.7

Using the appropriate interaction curves, determine the value of  $P_n$  for the short tied column shown in Figure 10.20 if  $e_x = 10$  in. Assume  $f_c' = 4000$  psi and  $f_y = 60,000$  psi.

#### SOLUTION

$$\frac{e}{h} = \frac{10 \text{ in.}}{20 \text{ in.}} = 0.500$$

$$\rho_g = \frac{(2) (3.79 \text{ in.}^2)}{(12 \text{ in.}) (20 \text{ in.})} = 0.0316$$

$$\gamma = \frac{14 \text{ in.}}{20 \text{ in.}} = 0.700$$

Plotting a straight line through the origin and the intersection of assumed values of  $K_n$  and  $R_n$  (say, 0.8 and 0.4, respectively).

For  $\rho_q$  of 0.0316, we read the value of  $R_n = 0.24$ :

$$R_n = \frac{P_n e}{f'_c A_g h} = 0.24$$

$$P_n = \frac{(0.24) (4 \text{ ksi}) (12 \text{ in.} \times 20 \text{ in.}) (20 \text{ in.})}{10 \text{ in.}} = 460.8 \text{ k}$$

When the usual column is subjected to axial load and moment, it seems reasonable to assume initially that  $\phi = 0.65$  for tied columns and 0.75 for spiral columns. It is to be remembered, however, that under certain conditions, these  $\phi$  values may be increased, as discussed in detail in Section 10.10.

#### 10.7 Shear in Columns

The shearing forces in interior columns in braced structures are usually quite small and normally do not control the design. However, the shearing forces in exterior columns can be large, even in a braced structure, particularly in columns bent in double curvature. Section 11.2.1.2 of the ACI Code provides the following equations for determining the shearing force that can

be carried by the concrete for a member subjected simultaneously to axial compression and shearing forces.

$$V_c = 2\left(1 + \frac{N_u}{2000A_g}\right)\lambda\sqrt{f_c'}b_w d$$
 (ACI Equation 11-4)

In SI units this equation is:

$$V_c = \left(1 + \frac{N_u}{14A_g}\right) \left(\frac{\lambda\sqrt{f_c'}}{6}\right) b_w d$$

In these equations,  $N_n$  is the factored axial force acting simultaneously with the factored shearing force,  $V_u$ , that is applied to the member. The value of  $N_u/A_g$  is the average factored axial stress in the column and is expressed in units of psi. Should  $V_{\mu}$  be greater than  $\phi V_{c}/2$ , it will be necessary to calculate required tie spacing using the stirrup spacing procedures described in Chapter 8. The results will be closer tie spacing than required by the usual column rules discussed earlier in Section 9.5.

Sections 11.2.3 and 11.4.7.3 of the ACI Code specify the method for calculating the contribution of the concrete to the total shear strength of circular columns and for calculating the contribution of shear reinforcement for cases where circular hoops, ties, or spirals are present. According to the commentary of the code in Section 11.2.3, the entire cross section in circular columns is effective in resisting shearing forces. The shear area,  $b_w d$ , in ACI Equation 11-4 then would be equal to the gross area of the column. However, to provide for compatibility with other calculations requiring an effective depth, the ACI requires that, when applied to circular columns, the shear area in ACI Equation 11-4 be computed as an equivalent rectangular area in which

$$b_w = D$$
$$d = 0.8D$$

In these equations, D is the gross diameter of the column. If the constant modifying D in the effective depth equation were equal to  $\pi/4$ , which is equal to 0.7854, the effective rectangular area would be equal to the gross area of the circular column. Thus, the area of the column is overestimated by a little less than 2% when using the equivalent area prescribed by the ACI.

#### 10.8 **Biaxial Bending**

Many columns are subjected to biaxial bending, that is, bending about both axes. Corner columns in buildings where beams and girders frame into the columns from both directions are the most common cases, but there are others, such as where columns are cast monolithically as part of frames in both directions or where columns are supporting heavy spandrel beams. Bridge piers are almost always subject to biaxial bending.

Circular columns have polar symmetry and, thus, the same ultimate capacity in all directions. The design process is the same, therefore, regardless of the directions of the moments. If there is bending about both the x- and y-axes, the biaxial moment can be computed by combining the two moments or their eccentricities as follows:

$$M_u = \sqrt{(M_{ux})^2 + (M_{uy})^2}$$

$$e = \sqrt{(e_x)^2 + (e_y)^2}$$

For shapes other than circular ones, it is necessary to consider the three-dimensional interaction effects. Whenever possible, it is desirable to make columns subject to biaxial bending circular in shape. Should it be necessary to use square or rectangular columns for such cases, the reinforcing should be placed uniformly around the perimeters.

You might quite logically think that you could determine  $P_n$  for a biaxially loaded column by using static equations, as was done in Example 10.2. Such a procedure will lead to the correct answer, but the mathematics involved is so complicated because of the shape of the compression side of the column that the method is not a practical one. Nevertheless, a few comments are made about this type of solution, and reference is made to Figure 10.21.

An assumed location is selected for the neutral axis, and the appropriate strain triangles are drawn, as shown in Figure 10.21. The usual equations are written with  $C_c = 0.85 f_c'$  times the shaded area  $A_c$  and with each bar having a force equal to its cross-sectional area times its stress. The solution of the equation yields the load that would establish that neutral axis—but the designer usually starts with certain loads and eccentricities and does not know the neutral axis location. Furthermore, the neutral axis is probably not even perpendicular to the resultant  $e = \sqrt{(e_x)^2 + (e_y)^2}$ .

For column shapes other than circular ones, it is desirable to consider three-dimensional interaction curves such as the one shown in Figure 10.22. In this figure, the curve labeled  $M_{nxo}$  represents the interaction curve if bending occurs about the x-axis only, while the one labeled  $M_{nyo}$  is the one if bending occurs about the y-axis only.

In this figure, for a constant  $P_n$ , the hatched plane shown represents the contour of  $M_n$  for bending about any axis.

Today, the analysis of columns subject to biaxial bending is primarily done with computers. One of the approximate methods that is useful in analysis and that can be handled

![](_page_322_Picture_10.jpeg)

FIGURE 10.21 Column cross section with skewed neutral axis from biaxial bending.

![](_page_323_Figure_2.jpeg)

FIGURE 10.22 Interaction surface for biaxially loaded column.

with pocket calculators includes the use of the so-called reciprocal interaction equation, which was developed by Professor Boris Bresler of the University of California at Berkeley.<sup>4</sup> This equation, which is shown in Section R10.3.6 of the ACI Commentary, follows:

$$\frac{1}{P_{ni}} = \frac{1}{P_{nx}} + \frac{1}{P_{ny}} - \frac{1}{P_{o}}$$

where

 $P_{ni}$  = the nominal axial load capacity of the section when the load is placed at a given eccentricity along both axes.

 $P_{nx}$  = the nominal axial load capacity of the section when the load is placed at an eccentricity  $e_r$ .

 $P_{ny}$  = the nominal axial load capacity of the section when the load is placed at an eccentricity  $e_{v}$ .

 $P_{o}$  = the nominal axial load capacity of the section when the load is placed with a zero eccentricity. It is usually taken as  $0.85f_c'A_g + f_yA_s$ .

<sup>&</sup>lt;sup>4</sup> Bresler, B., 1960, "Design Criteria for Reinforced Concrete Columns under Axial Load and Biaxial Bending," *Journal ACI*, 57, p. 481.

The Bresler equation works rather well as long as  $P_{ni}$  is at least as large as  $0.10P_o$ . Should  $P_{ni}$  be less than  $0.10P_o$ , it is satisfactory to neglect the axial force completely and design the section as a member subject to biaxial bending only. This procedure is a little on the conservative side. For this lower part of the interaction curve, it will be remembered that a little axial load increases the moment capacity of the section. The Bresler equation does not apply to axial tension loads. Professor Bresler found that the ultimate loads predicted by his equation for the conditions described do not vary from test results by more than 10%.

Example 10.8 illustrates the use of the reciprocal theorem for the analysis of a column subjected to biaxial bending. The procedure for calculating  $P_{nx}$  and  $P_{ny}$  is the same as the one used for the prior examples of this chapter.

#### Example 10.8

Determine the design capacity,  $P_{ni}$ , of the short tied column shown in Figure 10.23, which is subjected to biaxial bending.  $f'_c = 4000$  psi,  $f_v = 60,000$  psi,  $e_x = 16$  in., and  $e_v = 8$  in.

#### SOLUTION

#### For Bending about x-Axis

$$\gamma = \frac{20 \text{ in.}}{25 \text{ in.}} = 0.80$$

$$\rho_g = \frac{8.00 \text{ in.}^2}{(15 \text{ in.})(25 \text{ in.})} = 0.0213$$

$$\frac{e}{h} = \frac{16 \text{ in.}}{25 \text{ in.}} = 0.64$$

Drawing Line of Constant e/h=0.64 in Graph 8 of Appendix A and Estimating  $R_n$  Corresponding to  $\rho_q=0.0213$ , Read  $R_n\cong0.185$ 

$$R_n = \frac{P_{nx}e}{f'_c A_g h} = 0.185$$

$$P_{nx} = \frac{(4 \text{ ksi}) (15 \text{ in.} \times 25 \text{ in.}) (25 \text{ in.}) (0.185)}{16 \text{ in}} = 434 \text{ k}$$

![](_page_324_Figure_11.jpeg)

**FIGURE 10.23** Column cross section for Example 10.8.

For Bending about v-Axis

$$\gamma = \frac{10 \text{ in.}}{15 \text{ in.}} = 0.667$$

$$\rho_g = \frac{8.00 \text{ in.}^2}{(15 \text{ in.})(25 \text{ in.})} = 0.0213$$

$$\frac{e}{h} = \frac{8 \text{ in.}}{15 \text{ in}} = 0.533$$

Drawing Radial Lines of Constant e/h (0.533) in Graphs 6 and 7 of Appendix A and Interpolating between Them for  $\gamma = 0.667$ 

$$R_n = \frac{P_{ny}e}{f'_c A_g h} = 0.163$$
  
 $P_{ny} = \frac{(4 \text{ ksi})(15 \text{ in.} \times 25 \text{ in.})(15 \text{ in.})(0.163)}{8 \text{ in.}} = 458 \text{ k}$ 

**Determining Axial Load Capacity of Section** 

$$P_0 = (0.85)(4.0 \text{ ksi})(15 \text{ in.} \times 25 \text{ in.}) + (8.00 \text{ in.}^2)(60 \text{ ksi}) = 1755 \text{ k}$$

Using the Bresler Expression to Determine  $P_{ni}$ 

$$\frac{1}{P_{ni}} = \frac{1}{P_{nx}} + \frac{1}{P_{ny}} - \frac{1}{P_{o}}$$
$$\frac{1}{P_{ni}} = \frac{1}{434 \text{ k}} + \frac{1}{458 \text{ k}} - \frac{1}{1755 \text{ k}}$$

Multiplying through by 1755 k

$$\frac{1755 \text{ k}}{P_{ni}} = 4.044 + 3.832 - 1$$
$$P_{ni} = 255.3 \text{ k}$$

If the moments in the weak direction (y-axis here) are rather small compared to bending in the strong direction (x-axis), it is common to neglect the smaller moment. This practice is probably reasonable as long as  $e_y$  is less than about 20% of  $e_x$ , since the Bresler expression will show little reduction for  $P_{ni}$ . For the example just solved, an  $e_v$  equal to 50% of  $e_x$  caused the axial load capacity to be reduced by approximately 40%.

Example 10.9 illustrates the design of a column subject to biaxial bending. The Bresler expression, which is of little use in the proportioning of such members, is used to check the capacities of the sections selected by some other procedure. Exact theoretical designs of columns subject to biaxial bending are very complicated and, as a result, are seldom handled with pocket calculators. They are proportioned either by approximate methods or with computer programs.

### **Design of Biaxially Loaded Columns**

During the past few decades, several approximate methods have been introduced for the design of columns with biaxial moments. For instance, quite a few design charts are available with which satisfactory designs may be made. The problems are reduced to very simple calculations

![](_page_326_Picture_2.jpeg)

Richmond Convention Center, Richmond, Virginia. Notice column size changes.

in which coefficients are taken from the charts and used to magnify the moments about a single axis. Designs are then made with the regular uniaxial design charts.<sup>5,6,7</sup>

Another approximate procedure that works fairly well for design office calculations is used for Example 10.9. If this simple method is applied to square columns, the values of both  $M_{nx}$  and  $M_{ny}$  are assumed to act about both the x-axis and the y-axis (i.e.,  $M_x = M_y = M_{nx} + M_{ny}$ ). The steel is selected about one of the axes and is spread around the column, and the Bresler expression is used to check the ultimate load capacity of the eccentrically loaded column.

Should a rectangular section be used where the y-axis is the weaker direction, it would seem logical to calculate  $M_y = M_{nx} + M_{ny}$  and to use that moment to select the steel required about the y-axis and spread the computed steel area over the whole column cross section. Although such a procedure will produce safe designs, the resulting columns may be rather uneconomical, because they will often be much too strong about the strong axis. A fairly

<sup>&</sup>lt;sup>5</sup> Parme, A. L., Nieves, J. M., and Gouwens, A., 1966, "Capacity of Reinforced Rectangular Columns Subject to Biaxial Bending," *Journal ACI*, 63 (11), pp. 911–923.

<sup>&</sup>lt;sup>6</sup> Weber, D. C., 1966, "Ultimate Strength Design Charts for Columns with Biaxial Bending," *Journal ACI*, 63 (11), pp. 1205–1230.

<sup>&</sup>lt;sup>7</sup> Row, D. G., and Paulay, T., 1973, "Biaxial Flexure and Axial Load Interaction in Short Reinforced Concrete Columns," *Bulletin of New Zealand Society for Earthquake Engineering*, 6 (2), pp. 110–121.

satisfactory approximation is to calculate *My* = *Mnx* + *Mny* and multiply it by *b*/*h*, and with that moment design the column about the weaker axis.8

Example 10.9 illustrates the design of a short square column subject to biaxial bending. The approximate method described in the last two paragraphs is used, and the Bresler expression is used for checking the results. If this had been a long column, it would have been necessary to magnify the design moments for slenderness effects, regardless of the design method used.

#### Example 10.9

Select the reinforcing needed for the short square tied column shown in Figure 10.24 for the following: *PD* = 100 k, *PL* = 200 k, *MDX* = 50 ft-k, *MLX* = 110 ft-k, *MDY* = 40 ft-k, *MLY* = 90 ft-k, *f <sup>c</sup>* = 4000 psi, and *fy* = 60,000 psi.

#### **SOLUTION**

#### **Computing Design Values**

$$P_u = (1.2) (100 \text{ k}) + (1.6) (200 \text{ k}) = 440 \text{ k}$$
  
 $\frac{P_u}{f'_c A_g} = \frac{440 \text{ k}}{(4 \text{ ksi}) (484 \text{ in.}^2)} = 0.227$ 

Assume φ = 0.65

$$P_n = \frac{440 \text{ k}}{0.65} = 677 \text{ k}$$

$$M_{ux} = (1.2) (50 \text{ ft-k}) + (1.6) (110 \text{ ft-k}) = 236 \text{ ft-k}$$

$$M_{nx} = \frac{236 \text{ ft-k}}{0.65} = 363 \text{ ft-k}$$

$$M_{uy} = (1.2) (40 \text{ ft-k}) + (1.6) (90 \text{ ft-k}) = 192 \text{ ft-k}$$

$$M_{ny} = \frac{192 \text{ ft-k}}{0.65} = 295 \text{ ft-k}$$

As a result of biaxial bending, the design moment about the *x*- or *y*-axis is assumed to equal *Mnx* + *Mny* = 363 ft-k + 295 ft-k = 658 ft-k.

![](_page_327_Figure_12.jpeg)

**FI GU RE 10.24** Column cross section for Example 10.9.

<sup>8</sup> Fintel, M., ed., 1985, *Handbook of Concrete Engineering*, 2nd ed. (New York: Van Nostrand), pp. 37–39.

#### **Determining Steel Required**

$$e_x = e_y = \frac{(12 \text{ in/ft}) (658 \text{ ft-k})}{677 \text{ k}} = 11.66 \text{ in.}$$

$$\gamma = \frac{16 \text{ in.}}{22 \text{ in.}} = 0.727$$

By interpolation from interaction diagrams with bars on all four faces,

$$ho_g = 0.0235$$
 $A_s = (0.0235) (22 \text{ in.}) (22 \text{ in.}) = 11.37 \text{ in.}^2$ 

Use 8 #11 <sup>=</sup> 12.50 in.2

A review of the column with the Bresler expression gives a *Pni* = 804 k > 677 k, which is satisfactory. Should the reader go through the Bresler equation here, he or she must remember to calculate the correct *ex* and *ey* values for use with the interaction diagrams. For instance,

$$e_x = \frac{\text{(12 in/ft) (363 ft-k)}}{\text{677 k}} = 6.43 \text{ in.}$$

When a beam is subjected to biaxial bending, the following approximate interaction equation may be used for design purposes:

$$\frac{M_x}{M_{ux}} + \frac{M_y}{M_{uy}} \le 1.0$$

In this expression, *Mx* and *My* are the design moments, *Mux* is the design moment capacity of the section if bending occurs about the *x*-axis only, and *Muy* is the design moment capacity if bending occurs about the *y*-axis only. This same expression may be satisfactorily used for axially loaded members if the design axial load is about 15% or less of the axial load capacity of the section. For a detailed discussion of this subject, the reader is referred to the *Handbook of Concrete Engineering*. 9

Numerous other methods are available for the design of biaxially loaded columns. One method that is particularly useful to the design profession is the PCA Load Contour Method, which is recommended in the ACI *Design Handbook*. 10

### **10.10 Continued Discussion of Capacity Reduction Factors,** *φ*

As previously described, the value of φ can be larger than 0.65 for tied columns, or 0.75 for spiral columns, if *<sup>t</sup>* is larger than *fy*/*Es*. The lower φ values are applicable to compressioncontrolled sections because of their smaller ductilities. Such sections are more sensitive to varying concrete strengths than are tensilely controlled sections. The code (9.3.2.2) states that φ for a particular column may be increased linearly from 0.65 or 0.75 to 0.90 as the net tensile strain, *t*, increases from the compression-controlled strain, *fy*/*Es*, to the tensilely controlled one of 0.005.

For this discussion, Figure 3.5 from Chapter 3 is repeated with slight modification as Figure 10.25. From this figure, you can see the range of *<sup>t</sup>* values for which φ may be increased.

<sup>9</sup> Fintel, M., *Handbook of Concrete Engineering*, p. 38.

<sup>10</sup> American Concrete Institute, 2007, *Design Handbook in Accordance with the Strength Design Method*, Vol. 2, *Columns*, (Farmington Hills, MI: ACI), Publication SP-17 (07).

![](_page_329_Figure_2.jpeg)

**FIGURE 10.25** Variation of  $\phi$  with net tensile  $\epsilon_t$  and  $c/d_t$ .

The hand calculation of  $\epsilon_t$  for a particular column is a long and tedious trial-and-error problem, and space is not taken here to present a numerical example. However, a description of the procedure is presented in the next few paragraphs. The average designer will not want to spend the time necessary to make these calculations and will either just use the smaller  $\phi$ values or make use of a computer program, such as the Excel spreadsheet provided for this chapter. This program uses a routine for computing  $\epsilon_t$  and  $\phi$  for columns.

The procedure described here can be used to make a long-hand determination of  $\epsilon_t$ . As a beginning, we assume  $c/d_t=0.60$  where  $\epsilon_t=0.002$  (assumed yield strain for Grade 60 reinforcement), as shown in Figure 10.25. With this value, we can calculate c, a,  $\epsilon_c$ ,  $\epsilon_t$ ,  $f_s$ , and  $f'_c$  for our column. Then, with reference to Figure 10.26, moments can be taken about the centerline of the column and the result solved for  $M_n$  and e determined.

$$M_n = T_s \left( \frac{d_t - d'}{2} \right) + C_s \left( \frac{d_t - d'}{2} \right) + C_c \left( \frac{h}{2} - \frac{a}{2} \right)$$

As the next step,  $c/d_t$  can be assumed equal to 0.375 (where  $\epsilon_t = 0.005$  as shown in Figure 10.25) and another value of  $\epsilon_t$  determined. If the  $\epsilon_t$  of our column falls between the two  $\epsilon$ , values we have just calculated, the column falls in the transition zone for  $\phi$ . To determine its value, we can try different  $c/d_t$  values between 0.600 and 0.375 until the calculated  $\epsilon_t$  equals the actual  $\epsilon_t$  of the column.

If you go through this process one time, you will probably have seen all you want to see of it and will no doubt welcome the fact that the Excel spreadsheet provided for this textbook can be used to determine the value of  $\phi$  for a particular column.

When using the interaction diagrams in Appendix A, it is easy to see the region where the variable  $\phi$  factor applies. In Figure 10.15, note that there are lines labeled  $f_s/f_v$ . If the coordinates of  $K_n$  and  $R_n$  are greater than the value of  $f_s/f_v=1$ , the  $\phi$  factor is 0.65 (0.75 for spiral columns). If the coordinates are below the line labeled  $\epsilon_r = 0.005$ , the  $\phi$  factor is 0.90. Between these lines, the  $\phi$  factor is variable, and you would have to resort to approximate methods or to the spreadsheet provided.

![](_page_330_Picture_2.jpeg)

**FI GU RE 10.26** Notation used for column cross section.

### **10.11 Computer Example**

**Circular Column Capacity**

*Es =* **29,000 ksi** *c***bal** *=* **10.36 in.** *c***0.005** *=* **6.5625 in.**

#### Example 10.10

Using the Excel spreadsheet provided, plot the interaction diagram for the column obtained in Example 10.5.

#### **SOLUTION**

Open the Excel spreadsheet called Chapter 9 and Chapter 10. Open the worksheet entitled Circular Column. In the cells highlighted in yellow (only in the Excel spreadsheet, not in the printed example), enter the values required. You do not have to input values for *Pu* and *Mu*, but it is helpful to see how the applied loads compare with the interaction diagram. Next, open the worksheet called Interaction Diagram—Circular. The diagram shows that the applied load (single dot) is within the *Pu* versus *Mu* diagram (smaller curved line), hence the column cross section is sufficient if it is a short column.

#### *Pu =* **500 k** *Mu =* **200 ft-k = 2400 in-k** *h =* **20 in. 0.75** *f'c =* **4,000 psi** *fy =* **60,000 psi** *Ast =* **6.28 in.2** *Ag =* **314.2 in.2** *ρt =* **0.0200** *γ =* **0.85** ²*y =* **0.00207** *β***1** *= h d*5 *d*4 *d*3 *d*2 *d*1 *γ h*

![](_page_331_Figure_2.jpeg)

#### **PROBLEMS**

#### **Location of Plastic Centroids**

For Problems 10.1 and 10.2, locate the plastic centroids if  $f_c' =$  $4000 \text{ psi and } f_{y} = 60,000 \text{ psi.}$ 

**Problem 10.1** (Ans. 12.40 in. from left edge)

![](_page_331_Picture_7.jpeg)

#### Problem 10.2

![](_page_331_Picture_9.jpeg)

#### **Analysis of Column Subjected to Axial Load and Moment**

**Problem 10.3** Using statics equations, determine the values of  $P_n$  and  $M_n$  for the column shown, assuming it is strained to -0.003 on its right-hand edge and to +0.002 on its left-hand edge.  $f'_c = 4000$  psi and  $f_v = 60,000$  psi. (Ans.  $P_n = 608.9$  k,  $M_n = 399.1 \text{ ft-k}$ 

![](_page_331_Picture_12.jpeg)

**Problem 10.4** Repeat Problem 10.3 if the strain on the left edge is +0.001.

**Problem 10.5** Repeat Problem 10.3 if the strain on the left edge is 0.000. (Ans.  $P_n = 1077 \text{ k}$ ,  $M_n = 199.5 \text{ ft-k}$ )

**Problem 10.6** Repeat Problem 10.3 if the strain on the left edge is -0.001.

**Problem 10.7** Repeat Problem 10.3 if the steel on the left side has a strain in tension of  $\epsilon_v = f_v/E_s$  and the right edge is at 0.003. (Ans.  $P_n = 498 \text{ k}$ ,  $M_n = 418.8 \text{ ft-k}$ )

#### **Design of Columns for Axial Load and Moment**

For Problems 10.8 to 10.10, use the interaction curves in Appendix A to select reinforcing for the short columns shown.  $f_c' = 4000$  psi and  $f_v = 60,000$  psi.

#### Problem 10.8

![](_page_332_Figure_4.jpeg)

**Problem 10.9** (*One ans.* 6 #9 bars)

![](_page_332_Figure_6.jpeg)

#### Problem 10.10

![](_page_332_Picture_8.jpeg)

For Problems 10.11 to 10.16, use the interaction diagrams in Appendix A to determine  $P_n$  values for the short columns shown, which have bending about one axis.  $f_y = 60,000$  psi and  $f'_c = 4000$  psi.

**Problem 10.11** (Ans. 559 k)

![](_page_332_Figure_11.jpeg)

**Problem 10.12** Repeat Problem 10.11 if  $e_x = 9$  in.

#### **Problem 10.13** (Ans. 697 k)

![](_page_332_Figure_14.jpeg)

Problem 10.14

![](_page_332_Figure_16.jpeg)

#### **Problem 10.15** (*Ans.* 607 k)

![](_page_333_Figure_2.jpeg)

#### Problem 10.16

![](_page_333_Picture_4.jpeg)

For Problems 10.17 to 10.21, determine  $P_n$  values for the short columns shown if  $f_y=60{,}000$  psi and  $f_c'=4000$  psi.

**Problem 10.17** (Ans. 303 k)

![](_page_333_Figure_7.jpeg)

#### Problem 10.18

![](_page_333_Figure_9.jpeg)

**Problem 10.19** (Ans. 306 k)

![](_page_333_Picture_11.jpeg)

#### Problem 10.20

![](_page_333_Figure_13.jpeg)

**Problem 10.21** Repeat Problem 10.20 if  $e_x = 12$  in. and  $e_y = 6$  in. (Ans. 377 k)

For Problems 10.22 and 10.23, select reinforcing for the short columns shown if  $f_y = 60,000$  psi and  $f_c' = 4000$  psi. Check results with the Bresler equation.

#### Problem 10.22

![](_page_334_Figure_3.jpeg)

**Problem 10.23** (*One ans.* 8 #9 bars,  $P_n = 432 \text{ k}$ )

![](_page_334_Figure_5.jpeg)

For Problems 10.24 to 10.27, use the Chapters 9 and 10 Excel spreadsheet.

**Problem 10.24** If the column of Problem 10.8 is supporting a load  $P_u = 250$  k and  $e_x = 0$ , how large can  $M_{ux}$  be if six #9 bars (three in each face) are used?

**Problem 10.25** If the column of Problem 10.13 is supporting a load  $P_u = 400$  k and  $e_x = 0$ , how large can  $M_{uy}$  be if six #9 bars are used? (Ans. 264 ft-k)

**Problem 10.26** If the column of Problem 10.15 is to support an axial load  $P_u = 400$  k and  $e_x = 0$ , how many #10 bars must be used to resist a design moment  $M_{ux} = 300$  ft-k?

**Problem 10.27** If the column in Problem 10.11 has a moment  $M_{ux} = 375$  ft-k, what are the limits on  $P_u$ ? (Ans. 325 k  $\geq P_u \geq 30$  k)

**Problem 10.28** Prepare a flowchart for the preparation of an interaction curve for axial compression loads and bending for a short rectangular tied column.

#### **Problems with SI Units**

Column interaction curves are not provided in this text for the usual SI concrete strengths (21 MPa, 24 MPa, 28 MPa, etc.) or for the usual steel yield strength (420 MPa). Therefore, the problems that follow are to be solved using the column curves for  $f_c' = 4000$  psi and  $f_y = 60,000$  psi. These diagrams may be applied for the corresponding SI units (27.6 MPa and 413.7 MPa), just as they are for U.S. customary units, but it is necessary to convert the results to SI values.

For Problems 10.29 to 10.31, use the column interaction diagrams in Appendix A to determine  $P_n$  values for the short columns shown if  $f'_c = 28$  MPa and  $f_v = 420$  MPa.

**Problem 10.29** (Ans. 1855 kN)

![](_page_334_Figure_16.jpeg)

#### Problem 10.30

![](_page_335_Figure_3.jpeg)

**Problem 10.31** (*Ans.*  $P_u = 1528 \text{ kN}$ )

![](_page_335_Figure_5.jpeg)

For Problems 10.32 to 10.34, select reinforcing for the short columns shown if  $f'_c = 27.6 \text{ MPa}$  and  $f_v = 413.7 \text{ MPa}$ . Remember to apply the conversion factor provided before Problem 10.28 when using the interaction curves.

#### Problem 10.32

![](_page_335_Figure_8.jpeg)

#### **Problem 10.33** (One ans. 6 #36)

![](_page_335_Figure_10.jpeg)

#### Problem 10.34

![](_page_335_Figure_12.jpeg)

