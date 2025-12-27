# Two-Way Slabs, Equivalent Frame Method

### 17.1 Moment Distribution for Nonprismatic Members

Most of the moment distribution problems the student has previously faced have dealt with prismatic members for which carryover factors of  $\frac{1}{2}$ , fixed-end moments for uniform loads of  $w_u \ell^2/8$ , stiffness factors of  $I/\ell$ , and so on were used. Should nonprismatic members be encountered, such as the continuous beam of Figure 17.1, none of the preceding values applies.

Carryover factors, fixed-end moments, and so forth can be laboriously obtained by various methods, such as the moment-area and column-analogy methods. There are various tables available, however, from which many of these values can be obtained. The tables numbered A.16 through A.20 of Appendix A cover most situations encountered with the equivalent frame method.

Before the equivalent frame method is discussed, an assumed set of fixed-end moments is balanced in Example 17.1 for the nonprismatic beam of Figure 17.1. The authors' purpose in presenting this example is to show the reader how moment distribution can be applied to the analysis of structures consisting of nonprismatic members.

#### Example 17.1

The carryover factors (C.O.), stiffness factors (*K*), and fixed-end moments (FEM) shown in Figure 17.2 have been assumed for the continuous nonprismatic member of Figure 17.1. Balance these moments by moment distribution. It will be shown later, in Example 17.2, how to determine these factors for two-way slab systems. The purpose of this example is to demonstrate the moment distribution method when nonprismatic members are involved.

![](_page_551_Picture_8.jpeg)

FIGURE 17.1 Nonprismatic beam.

<sup>&</sup>lt;sup>1</sup> McCormac, J. C., 1984, Structural Analysis, 4th ed. (New York: Harper & Row), pp. 333–334, 567–582.

![](_page_552_Figure_2.jpeg)

**FI GU RE 17.2** Moment distribution.

#### **SOLUTION**

![](_page_552_Figure_5.jpeg)

FEM (ft-k) 
$$\begin{array}{ccccccccccccccccccccccccccccccccccc$$

### **17.2 Introduction to the Equivalent Frame Method**

With the preceding example, the authors hoped to provide the reader with a general idea of the kinds of calculations he or she will face with the equivalent frame method. A part of a two-way slab building will be taken out by itself and analyzed by moment distribution. The slab-beam members of this part of the structure will be nonprismatic because of the columns, beams, drop panels, and so on of which they consist. As a result, it will be quite similar to the beam of Figure 17.1, and we will analyze it in the same manner.

The only difference between the direct design method and the equivalent frame method is in the determination of the longitudinal moments in the spans of the equivalent rigid frame. Whereas the direct design method involves a one-cycle moment distribution, the equivalent frame method involves a normal moment distribution of several cycles. The design moments obtained by either method are distributed to the column and middle strips in the same fashion.

It will be remembered that the range in which the direct design method can be applied is limited by a maximum 2-to-1 ratio of live-to-dead load and a maximum ratio of the longitudinal span length to the transverse span length of 2 to 1. In addition, the columns may not be

![](_page_553_Picture_2.jpeg)

**FI GU RE 17.3** Slab beam.

offset by more than 10% of the span length in the direction of the offset from either axis between centerlines of successive columns. There are no such limitations on the equivalent frame method. This is a very important matter because so many floor systems do not meet the limitations specified for the direct design method.

Analysis by either method will yield almost the same moments for those slabs that meet the limitations required for application of the direct design method. For such cases, it is simpler to use the direct design method.

The equivalent frame method involves the elastic analysis of a structural frame consisting of a row of equivalent columns and horizontal slab members that are each one panel long and have a transverse width equal to the distance between centerlines of the panels on each side of the columns in question. For instance, the hatched strip of the floor system in Figure 17.3 can be extracted and the combined slab and beam analyzed to act as a beam element as part of a structural frame (see also Figure 17.4). This assumption approximately models the actual behavior of the structure. It is a reasonably accurate way of calculating moments in the overall structural frame, which then may be distributed to the slab and beams. This process is carried out in both directions. That is, it is done to the hatched strip in Figure 17.3 and all other strips parallel to it. Then it is carried out on strips that are perpendicular to these strips, hence the term two-way floor system.

![](_page_553_Figure_7.jpeg)

**FI GU RE 17.4** Equivalent frame for the crosshatched strip of Figure 17.3 for vertical loading.

For vertical loads, each floor, together with the columns above and below, is analyzed separately. For such an analysis, the far ends of the columns are considered fixed. Figure 17.4 shows a typical equivalent slab beam as described in this chapter.

Should there be a large number of panels, the moment at a particular joint in a slab beam can be satisfactorily obtained by assuming that the member is fixed two panels away. This simplification is permissible because vertical loads in one panel only appreciably affect the forces in that panel and in the one adjacent to it on each side.

For lateral loads, it is necessary to consider an equivalent frame that extends for the entire height of the building, because the forces in a particular member are affected by the lateral forces on all the stories above the floor being considered. When lateral loads are considered, it will be necessary to analyze the frame for them and combine the results with analyses made for gravity loads (ACI Code 13.5.1.3).

The equivalent frame is made up of the horizontal slab, any beams spanning in the direction of the frame being considered, the columns or other members that provide vertical support above and below the slab, and any parts of the structure that provide moment transfer between the horizontal and vertical members. You can see there will be quite a difference in moment transfer from the case where a column provides this transfer and where there is a monolithic reinforced concrete wall extending over the full length of the frame. For cases in between, the stiffnesses of the torsional members such as edge beams will be estimated.

The same minimum ACI slab thicknesses must be met as in the direct design method. The depths should be checked for shear at columns and other supports, as specified in Section 11.12 of the code. Once the moments have been computed, it will also be necessary to check for moment shear transfer at the supports.

The analysis of the frame is made for the full design live load applied to all spans, unless the actual unfactored live load exceeds 0.75 times the unfactored dead load (ACI Code 13.7.6). When the live load is greater than 0.75 times the dead load, a pattern loading with three-fourths times the live load is used for calculating moments and shears.

The maximum positive moment in the middle of a span is assumed to occur when threefourths of the full design load is applied in that panel and in alternate spans. The maximum negative moment in the slab at a support is assumed to occur when three-fourths of the full design live load is applied only to the adjacent panels. The values so obtained may not be less than those calculated, assuming full live loads in all spans.

### **17.3 Properties of Slab Beams**

The parts of the frame are the slabs, beams, drop panels, columns, and so on. Our first objective is to compute the properties of the slab beams and the columns (i.e., the stiffness factors, distribution factors, carryover factors, and fixed-end moments). To simplify this work, the properties of the members of the frame are permitted by the ACI Code (13.7.3.1) to be based on their gross moments of inertia rather than their transformed or cracked sections. Despite the use of the gross dimensions of members, the calculations involved in determining the properties of nonprismatic members still represent a lengthy task, and we will find the use of available tables very helpful.

Figures 17.5 and 17.6 present sketches of two-way slab structures, together with the equivalent frames that will be used for their analysis. A flat slab with columns is shown in Figure 17.5(a). Cross sections of the structure are shown through the slab in part (b) of the figure and through the column in part (c). In part (d), the equivalent frame that will be used for the actual numerical calculations is shown. In this figure, *Ecs* is the modulus of elasticity of the concrete slab. With section 2-2, a fictitious section is shown that will have a stiffness approximately equivalent to that of the actual slab and column. An expression for *I* for the equivalent section is also given. In this expression, *c*<sup>2</sup> is the width of the column in a direction

![](_page_555_Figure_2.jpeg)

![](_page_555_Figure_3.jpeg)

![](_page_555_Figure_4.jpeg)

(c) Equivalent Section 2-2

![](_page_555_Figure_6.jpeg)

(d) Equivalent slab beam stiffness diagram

**FIGURE 17.5** Slab system without beams.

perpendicular to the direction of the span, and  $\ell_2$  is the width of the slab beam. The gross moment of inertia at the face of the support is calculated and is divided by  $(1 - c_2/\ell_2)^2$ . This approximates the effect of the large increase in depth provided by the column for the distance in which the slab and column are in contact.

In Figure 17.6, similar sketches and I values are shown for a slab with drop panels. Figure 13.7.3 of the 1983 ACI Commentary showed such information for slab systems with beams and for slab systems with column capitals.

![](_page_556_Figure_2.jpeg)

**FIGURE 17.6** Slab systems with drop panels.

With the equivalent slab beam stiffness diagram, it is possible, using the conjugate beam method, column analogy, or some other method, to compute stiffness factors, distribution factors, carryover factors, and fixed-end moments for use in moment distribution. Tables A.16 through A.20 of Appendix A of this text provide tabulated values of these properties for various slab systems. The numerical examples of this chapter make use of this information.

### **17.4 Properties of Columns**

The length of a column is assumed to run from the middepth of the slab on one floor to the middepth of the slab on the next floor. For stiffness calculations, the moments of inertia of columns are based on their gross dimensions. Thus, if capitals are present, the effect of their dimensions must be used for those parts of the columns. Columns are assumed to be infinitely stiff for the depth of the slabs.

Figure 17.7 shows a sample column, together with its column stiffness diagram. Similar diagrams are shown for other columns (where there are drop panels, capitals, etc.) in Figure 13.7.4 of the 1983 ACI Commentary.

With a column stiffness diagram, the column flexural stiffness, *Kc* , can be determined by the conjugate beam procedure or other methods. Tabulated values of *Kc* are given in Table A.20 of the Appendix A of this text for typical column situations.

In applying moment distribution to a particular frame, we need the stiffnesses of the slab beam, the torsional members, and the equivalent column so that the distribution factors can be calculated. For this purpose, the equivalent column, the equivalent slab beam, and the torsional members are needed at a particular joint.

For this discussion, see Figure 17.8, where it is assumed that there is a column above and below the joint in question. Thus, the column stiffness (*Kc* ) here is assumed to include the stiffness of the column above (*Kct*) and the one below (*Kcb* ). Thus, -*Kc* = *Kct* + *Kcb* . In a similar fashion, the total torsional stiffness is assumed to equal that of the torsional members on both sides of the joint (-*Kt* = *Kt*<sup>1</sup> + *Kt*2). For an exterior frame, the torsional member will be located on one side only.

The following approximate expression for the stiffness (*Kt*) of the torsional member was determined using a three-dimensional analysis for various slab configurations (ACI R13.7.5).

$$K_t = \Sigma \frac{9E_{cs}C}{\ell_2 \left(1 - \frac{c_2}{\ell_2}\right)^3}$$

![](_page_557_Figure_10.jpeg)

**FI GU RE 17.7** Equivalent column.

![](_page_558_Figure_2.jpeg)

FIGURE 17.8 Equivalent frame model.

In this formula, C is to be determined with the following expression by dividing the cross section of the torsional member into rectangular parts and summing the C values for the different parts.

$$C = \Sigma \left( 1 - 0.63 \frac{x}{y} \right) \frac{x^3 y}{3}$$
 (ACI Equation 13-6)

If there is no beam framing into the column in question, a part of the slab equal to the width of the column or capital shall be used as the effective beam. If a beam frames into the column, a T beam or L beam will be assumed, with flanges of widths equal to the projection of the beam above or below the slab but not more than four times the slab thickness.

The flexibility of the equivalent column is equal to the reciprocal of its stiffness, as follows:

$$\frac{1}{K_{ec}} = \frac{1}{\Sigma K_c} + \frac{1}{\Sigma K_t}$$
$$\frac{1}{K_{ec}} = \frac{1}{K_{ct} + K_{cb}} + \frac{1}{K_c + K_t}$$

Solving this expression for the equivalent column stiffness and multiplying through by  $K_c$ 

$$K_{ec} = \frac{(K_{ct} + k_{cb})(k_t + k_t)}{(k_{ct} + k_{cb}) + (k_t + k_t)}$$

An examination of this brief derivation shows that the torsional flexibility of the slab column joint reduces the joint's ability to transfer moment.

After the value of  $K_{ec}$  is obtained, the distribution factors can be computed as follows (see Figure 17.8):

DF for beam 
$$2-1 = \frac{K_{b1}}{K_{b1} + K_{b2} + K_{ec}}$$
DF for beam  $2-3 = \frac{K_{b2}}{K_{b1} + K_{b2} + K_{ec}}$ 
DF for column above  $= \frac{K_{ec}/2}{K_{b1} + K_{b2} + K_{ec}}$ 

#### **Example Problem** 17.5

Example 17.2 illustrates the determination of the moments in a flat-plate structure by the equivalent frame method.

#### Example 17.2

Using the equivalent frame method, determine the design moments for the hatched strip of the flat-plate structure shown in Figure 17.9 if  $f_c' = 4000$  psi,  $f_v = 60,000$  psi, and (unfactored dead load)  $q_D = 120$  psf and (unfactored live load)  $q_L = 82.5$  psf. Column lengths = 9 ft 6 in.

#### SOLUTION

- 1. Determine the depth required for ACI depth limitations (9.5.3). Assume that this has been done and that a preliminary slab h = 8 in. (d = 6.75 in.) has been selected.
- 2. Check beam shear for exterior column

$$q_u = 1.2q_D + 1.6q_L = 1.2(120 \text{ psf}) + 1.6(82.5 \text{ psf}) = 276 \text{ psf}$$
 
$$V_u \text{ for 12 in. width} = (0.276 \text{ ksf}) \left(11.0 \text{ ft} - \frac{7.5 \text{ in.}}{12 \text{ in/ft}} - \frac{6.75 \text{ in.}}{12 \text{ in/ft}}\right) = 2.708 \text{ k/ft}$$
 
$$\phi V_c = \frac{(0.75)(2)(1.0)(\sqrt{4000} \text{ psi})(12 \text{ in.})(6.75 \text{ in.})}{1000} = 7.684 \text{ k/ft} > 2.708 \text{ k/ft}$$

3. Check two-way shear around interior columns

$$V_{u} = \left[ (18 \text{ ft}) (22 \text{ ft}) - \left( \frac{15 \text{ in.} + 6.75 \text{ in.}}{12 \text{ in/ft}} \right)^{2} \right] (0.276 \text{ ksf}) = 108.39 \text{ k}$$

$$\phi V_{c} = \frac{(0.75) (4) (1.0) (\sqrt{4000} \text{ psi})(4) (15 \text{ in.} + 6.75 \text{ in.}) (6.75 \text{ in.})}{1000}$$

$$= 111.42 \text{k} > 108.39 \text{k} \quad \underline{OK}$$

![](_page_559_Figure_12.jpeg)

**FIGURE 17.9** Flat plate for Example 17.2.

4. Using tables in Appendix A, determine stiffness factor and fixed-end moments for the 22-foot spans

$$I_{\rm S} = \frac{\ell_2 h^3}{12} = \frac{(12 \text{ in/ft } \times 18 \text{ ft}) (8 \text{ in.})^3}{12} = 9216 \text{ in.}^4$$

$$E_{\rm cs} = 3.64 \times 10^6$$
 psi (from Appendix A, Table A.1)

See Table A.16, notice that C values are column dimensions as shown in the figures accompanying Tables A.16 to A.19. The tables are rather difficult to read.

$$C_{1A} = C_{2A} = C_{1B} = C_{2B} = 15 \text{ in.} = 1.25 \text{ ft}$$

$$\frac{C_{1A}}{\ell_1} = \frac{1.25 \text{ ft}}{22.0 \text{ ft}} = 0.057$$

$$\frac{C_{1B}}{\ell_1} = \frac{1.25 \text{ ft}}{22.0 \text{ ft}} = 0.057$$

By interpolation in the table (noting that A is for near end and B is for far end), the values from the table are very rough.

$$k_{AB} = 4.17$$

$$k_{AB} = \frac{4.17E_{cs}I_{s}}{\ell_{1}} = \frac{(4.17)(3.64 \times 10^{6} \text{ psi})(9216 \text{ in.}^{4})}{(12 \text{ in/ft})(22 \text{ ft})}$$

$$= 529.9 \times 10^6 \text{ in-lb}$$

$$\mathsf{FEM}_{AB} = \mathsf{FEM}_{BA} = 0.084q_u \ell_2 \ell_1^2$$

$$= (0.084) (0.276 \text{ ksf}) (18 \text{ ft}) (22 \text{ ft})^2 = 202 \text{ ft-k}$$

$$C_{AB} = C_{BA} = \text{carryover factor}$$

$$= 0.503$$

5. Determine column stiffness

$$I_c = \left(\frac{1}{12}\right) (15 \text{ in.}) (15 \text{ in.})^3 = 4219 \text{ in.}^4$$

$$E_{cc} = 3.64 \times 10^6 \text{ psi}$$

Using Appendix A, Table A.20

$$\ell_n = 9 \text{ ft 6 in.} = 9.50 \text{ ft}$$

$$\ell_c = 9.50 \text{ ft} - \frac{8 \text{ in.}}{12 \text{ in/ft}} = 8.833 \text{ ft}$$

$$\frac{\ell_n}{\ell_c} = \frac{8.833 \text{ ft}}{9.50 \text{ ft}} = 0.930 = \frac{\ell_u}{\ell_c}$$

With reference to the figure given with Table A.20,

$$\frac{a}{b} = \frac{4 \text{ in.}}{4 \text{ in.}} = 1.00$$

$$k_{AB} = 4.81$$
 by interpolation

![](_page_561_Figure_2.jpeg)

FIGURE 17.10 Torsional member.

$$K_c = \frac{4.81E_{cc}I_c}{H} = \frac{(4.81)(3.64 \times 10^6 \text{ psi})(4219 \text{ in.}^4)}{(9.5 \text{ ft})(12 \text{ in/ft})} = 648 \times 10^6 \text{ in-lb}$$

 $C_{AB} = 0.55$  by interpolation

6. Determine the torsional stiffness of the slab section (see Figure 17.10)

$$C = \Sigma \left( 1 - 0.63 \frac{x}{y} \right) \left( \frac{x^3 y}{3} \right) = \left( 1 - \frac{0.63 \times 8 \text{ in.}}{15 \text{ in.}} \right) \left\lceil \frac{(8 \text{ in.})^3 \times 15 \text{ in.}}{3} \right\rceil = 1700 \text{ in.}^4$$

$$K_{t} = \frac{9E_{cs}C}{\left\lceil \ell_{2} \left(1 - \frac{c_{2}}{\ell_{2}}\right)^{3} \right\rceil} = \frac{(9) \left(3.64 \times 10^{6} \text{ in-lb}\right) (1700 \text{ in.}^{4})}{\left\{ (12 \text{ in/ft}) \left(18 \text{ ft}\right) \left[1 - \frac{15 \text{ in.}}{(12 \text{ in/ft}) \left(22 \text{ ft}\right)}\right]^{3} \right\}} = 307.3 \times 10^{6} \text{ in-lb}$$

7. Compute  $K_{ec}$ , the stiffness of the equivalent column

$$K_{\text{ec}} = \frac{\Sigma K_c \Sigma K_t}{\Sigma K_c + \Sigma K_t} = \frac{(2 \times 648.0) (2 \times 307.3)}{2 \times 648.0 + 2 \times 307.3}$$

$$= 416.9 \times 10^6 \text{ in-lb}$$

A summary of the stiffness values is shown in Figure 17.11.

8. Computing distribution factors and balancing moments (see Figure 17.12): The authors do not show moments at tops and bottoms of columns, but this could easily be done by multiplying the balanced column moments at the joints with the slabs by the carryover factor for the columns, which is 0.55.

![](_page_561_Figure_13.jpeg)

FIGURE 17.11 Equivalent frame with stiffnesses (in-lb).

![](_page_562_Figure_2.jpeg)

FIGURE 17.12 Results of moment distribution (moments, ft-k).

A summary of the moment values for Example 17.2 is given in Figure 17.13. The positive moments shown in each span are assumed to equal the simple beam centerline moments plus the average of the end negative moments. This is correct if the end moments in a particular span are equal and is approximately correct if the end moments are unequal. For span 1,

$$^{+}M = \frac{(0.276 \text{ ksf}) (18 \text{ ft}) (22 \text{ ft})^2}{8} - \left(\frac{94.8 \text{ ft-k} + 235.8 \text{ ft-k}}{2}\right) = 135.3 \text{ ft-k}$$

The negative moments shown in Figures 17.12 and 17.13 were calculated at the centerlines of the supports. At these supports, the cross section of the slab beam is very large because of the presence of the column. At the face of the column, however, the cross section is far smaller, and the code (13.7.7) specifies that negative reinforcing be designed for the moment there. (If the column is not rectangular, it is replaced with a square column of the same total area and the moment is computed at the face of that fictitious column.) Because the ratio of unfactored dead to live load is less than 0.75, ACI Section 13.7.6.2 permits a single analysis with live load for all spans. No pattern load analysis is required.

The design moments shown in Figure 17.14 were determined by drawing the shear diagram and computing the area of that diagram between the centerline of each support and the face of the column.

![](_page_562_Figure_8.jpeg)

FIGURE 17.13 Results of Example 17.2.

| $0.276 \text{ ksf} \times 18$ | 8  ft = 4.968  k/ft |                |         |
|-------------------------------|---------------------|----------------|---------|
|                               |                     |                |         |
| 154.65                        | 54.65 11 54.65      | 54.65 11 54.65 | 54.651  |
| <u> 1 6.41</u>                | 6.41 1              | 6.41           | 6.41    |
| 148.24                        | 61.06 11 54.65      | 54.65 1161.06  | 48.24 † |

![](_page_563_Figure_3.jpeg)

![](_page_563_Figure_4.jpeg)

FIGURE 17.14 Final shear and moment diagrams for Example 17.2.

For interior columns, the critical section (for both column and middle strips) is to be taken at the face of the supports, but not at a distance greater than  $0.175\ell_1$  from the center of the column. At exterior supports with brackets or capitals, the moment used in the span perpendicular to the edge shall be computed at a distance from the face of the support element not greater than one-half of the projection of the bracket or capital beyond the face of the supporting element.

Sometimes the total of the design moments (i.e., the positive moment plus the average of the negative end moments) obtained by the equivalent frame method for a particular span may be greater than  $M_o = q_u \ell_2 \ell_n^2 / 8$ , as used in Chapter 16. Should this happen, the code (13.7.7.4) permits a reduction in those moments proportionately, so their sum does equal  $M_a$ .

#### 17.6 **Computer Analysis**

The equivalent frame method was developed with the intention that the moment distribution method was to be used for the structural analysis. Truthfully, the method is so involved that it is not satisfactory for hand calculations. It is possible, however, to use computers and plane frame analysis programs if the structure is especially modeled. (In other words, we must establish various nodal points in the structure so as to account for the changing moments of inertia along the member axes.) There are also some computer programs on the market especially written for these frames. One of the best known is called ADOSS (analysis and design of concrete floor systems) and was prepared by the Portland Cement Association. The moments shown in

Figure 17.14 can be entered in the Chapter 16 Excel spreadsheet, Two Way Slab, in cells 12C to 12G for interior spans and 45C to 45G for edge spans.

### **17.7 Computer Example**

### Example 17.3

Use the Excel spreadsheet provided for Chapter 17 to solve Example 17.2.

#### **SOLUTION**

Open the Chapter 17 Excel spreadsheet, and open the worksheet Moment Distribution. Enter values only for cells highlighted in yellow (only in the Excel spreadsheets, not the printed example). Results of the moment distribution are shown at the bottom of each column. Note that they are in agreement with those in Example 17.2.

Moment Distribution for User Input Distribution and Carryover Factors and Fixed-End Moments

|                     | A       |         | B       |         | C       | D       |
|---------------------|---------|---------|---------|---------|---------|---------|
| Joint Member        | AB      | BA      | BC      | CB      | CD      | DC      |
| Distribution factor | 0.56    | 0.36    | 0.36    | 0.36    | 0.36    | 0.56    |
| Fixed-end moment    | −202    | 202     | −202    | 202     | −202    | 202     |
| Carryover           | 0.503   | 0.503   | 0.503   | 0.503   | 0.503   | 0.503   |
| Balance             | 113.12  | 0       | 0       | 0       | 0       | −113.12 |
| Carryover           | 0.000   | 56.899  | 0.000   | 0.000   | −56.899 | 0.000   |
| Balance             | 0.000   | −20.484 | −20.484 | 20.484  | 20.484  | 0.000   |
| Carryover           | −10.303 | 0.000   | 10.303  | −10.303 | 0.000   | 10.303  |
| Balance             | 5.770   | −3.709  | −3.709  | 3.709   | 3.709   | −5.770  |
| Carryover           | −1.866  | 2.902   | 1.866   | −1.866  | −2.902  | 1.866   |
| Balance             | 1.045   | −1.716  | −1.716  | 1.716   | 1.716   | −1.045  |
| Carryover           | −0.863  | 0.526   | 0.863   | −0.863  | −0.526  | 0.863   |
| Balance             | 0.483   | −0.500  | −0.500  | 0.500   | 0.500   | −0.483  |
| Carryover           | −0.252  | 0.243   | 0.252   | −0.252  | −0.243  | 0.252   |
| Balance             | 0.141   | −0.178  | −0.178  | 0.178   | 0.178   | −0.141  |
| Carryover           | −0.090  | 0.071   | 0.090   | −0.090  | −0.071  | 0.090   |
| Balance             | 0.050   | −0.058  | −0.058  | 0.058   | 0.058   | −0.050  |
| Carryover           | −0.029  | 0.025   | 0.029   | −0.029  | −0.025  | 0.029   |
| Balance             | 0.016   | −0.020  | −0.020  | 0.020   | 0.020   | −0.016  |
| Final moments, ft-k | −94.78  | 236.00  | −215.26 | 215.26  | −236.00 | 94.78   |

## **PROBLEMS**

**Problem 17.1** Determine the end moments for the beams and columns of the frame shown for which the fixed-end moments, carryover factors, and distribution factors (circled) have been computed. Use the moment distribution method. (*Ans*. 44.9 ft-k, 21.0 ft-k at column bases)

![](_page_565_Figure_3.jpeg)

**Problem 17.2** Repeat Problem 16.4 using the equivalent frame method instead of the direct design method.

**Problem 17.3** Use Chapter 17 spreadsheet to determine the end moments in member *AB* and *BC* of Problem 17.1. (*Ans*. *MAB* = −163.6 ft-k, *MBA* = 307.2 ft-k, *MBC* = −229.7 ft-k, *MCB* = 48.1 ft-k)

Walls **CHA PTER 18**

### **18.1 Introduction**

Before the advent of frame construction during the nineteenth century, most walls were of a load-bearing type. Since the late 1800s, however, the non–load-bearing wall has become quite common because other members of the structural frame can be used to provide stability. As a result, today we have walls that serve all sorts of purposes, such as retaining walls, basement walls, partition walls, fire walls, and so on. These walls may or may not be of a load-bearing type.

In this chapter, the following kinds of concrete walls will be considered: non–loadbearing, load-bearing, and shear walls (the latter being either load-bearing or non–load-bearing).

### **18.2 Non–Load-Bearing Walls**

Non–load-bearing walls are those that support only their own weight and perhaps some lateral loads. Falling into this class are retaining walls, fac¸ade-type walls, and some basement walls. For Non–load-bearing walls, the ACI Code provides several specific limitations, which are listed at the end of this paragraph. The values given for minimum reinforcing quantities and wall thicknesses do not have to be met if lesser values can be proved satisfactory by structural analysis (14.2.7). The numbers given in parentheses are ACI section numbers.

- **1.** The thickness of a Non–load-bearing wall cannot be less than 4 in. or <sup>1</sup> <sup>30</sup> times the least distance between members that provide lateral support (14.6.1).
- **2.** The minimum amount of vertical reinforcement as a percentage of gross concrete area is 0.0012 for deformed bars #5 or smaller with *fy* = at least 60,000 psi, 0.0015 for other deformed bars, and 0.0012 for plain or deformed welded wire fabric not larger than *W* 31 or *D*31—that is, <sup>5</sup> <sup>8</sup> in. in diameter (14.3.2).
- **3.** The vertical reinforcement does not have to be enclosed by ties unless the percentage of vertical reinforcing is greater than 0.01 times the gross concrete area or where the vertical reinforcing is not required as compression reinforcing (14.3.6).
- **4.** The minimum amount of horizontal reinforcing as a percentage of gross concrete area is 0.0020 for deformed bars #5 or smaller with *fy* ≥ 60,000 psi, 0.0025 for other deformed bars, and 0.0020 for plain or deformed welded wire fabric not larger than *W*31 or *D*31 (14.3.3).
- **5.** The spacing of vertical and horizontal reinforcement may not exceed three times the wall thickness, or 18 in. (14.3.5).
- **6.** Reinforcing for walls more than 10 in. thick (not including basement walls) must be placed in two layers as follows: one layer containing from one-half to two-thirds of the total reinforcing placed in the exterior surface not less than 2 in. nor more than one-third

![](_page_567_Picture_2.jpeg)

Retaining wall with stepped wall thickness.

times the wall thickness from the exterior surface; the other layer placed not less than 3 <sup>4</sup> in. nor more than one-third times the wall thickness from the interior surface (14.3.4).

- **7.** For walls less than 10 in. thick, the code does not specify two layers of steel, but to control shrinkage, it is probably a good practice to put one layer on the face of walls exposed to view and one on the nonstressed side of foundation walls 10 ft or more in height.
- **8.** In addition to the reinforcing specified in the preceding paragraphs, at least two #5 bars in walls having two layers of reinforcement in both directions, and one #5 bar in walls having a single layer of reinforcement in both directions, must be provided around all window, door, and similar-sized openings. These bars must be anchored to develop *fy* in tension at the corners of the openings (14.3.7).
- **9.** For cast-in-place walls, the area of reinforcing across the interface between a wall and a footing must be no less than the minimum vertical wall reinforcing given in 14.3.2 (15.8.2.2).
- **10.** For precast, nonprestressed walls, the reinforcement must be designed in accordance with the preceding requirements on this list, as well as the requirements of Chapter 10 or 14 of the code, except that the area of the horizontal and vertical reinforcing must not be less than 0.001 times the gross cross-sectional area of the wall. In addition, the spacing of the reinforcing may not be greater than five times the wall thickness or 30 in. for interior walls, or 18 in. for exterior ones (16.4.2).

### **18.3 Load-Bearing Concrete Walls—Empirical Design Method**

Most of the concrete walls in buildings are load-bearing walls that support not only vertical loads but also some lateral moments. As a result of their considerable in-plane stiffnesses, they are quite important in resisting wind and earthquake forces.

Load-bearing walls with solid rectangular cross sections may be designed as were columns subject to axial load and bending, or they may be designed by an empirical method given in Section 14.5 of the code. The empirical method may be used only if the resultant of all the factored loads falls within the middle third of the wall (i.e., the eccentricity must be equal to or less than one-sixth the thickness of the wall). *Whichever of the two methods is used*, *the design must meet the minimum requirements given in the preceding section of this chapter for non–load-bearing walls*.

This section is devoted to the empirical design method, which is applicable to relatively short vertical walls with approximately concentric loads. The code (14.5.2) provides an empirical formula for calculating the design axial load strength of solid rectangular crosssectional walls with *e* less than one-sixth of wall thicknesses. Should walls have nonrectangular cross sections (such as ribbed wall panels) and/or should *e* be greater than one-sixth of wall thicknesses, the rational design procedure for columns subject to axial load and bending (Section 14.4) must be followed.

The practical use of the empirical wall formula, which is given at the end of this paragraph, is for relatively short walls with small moments. When lateral loads are involved, *e* will quickly exceed one-sixth of wall thicknesses. The number 0.55 in the equation is an eccentricity factor that causes the equation to yield a strength approximately equal to that which

![](_page_568_Picture_7.jpeg)

Thirty-two-foot-tall foundation walls for the MCI Mid-Continent Data Center in Omaha, Nebraska.

**TABLE 18.1** Effective Length Factors for Load-Bearing Walls (14.5.2)

| Walls braced top and bottom against lateral translation and             | . Walls braced top and bottom against lateral translation and |  |  |  |  |  |  |
|-------------------------------------------------------------------------|---------------------------------------------------------------|--|--|--|--|--|--|
| (a) Restrained against rotation at one or both ends (top and/or bottom) | 0.80                                                          |  |  |  |  |  |  |
| (b) Not restrained against rotation at either end                       | 1.0                                                           |  |  |  |  |  |  |
| 2. For walls not braced against lateral translation                     | 2.0                                                           |  |  |  |  |  |  |

would be obtained by the axial load and bending procedure of Chapter 10 of the code if the eccentricity is h/6.

$$\phi P_{nw} = 0.55 \phi f_c' A_g \left[ 1 - \left( \frac{k \ell_c}{32h} \right)^2 \right]$$
 (ACI Equation 14-1)

where

 $\phi = 0.65$ 

 $A_g = \text{gross area of the wall section (in.}^2)$ 

 $\ell_c$  = vertical distance between supports (in.)

h = overall thickness of member (in.)

k = effective length factor determined in accordance with the values given in **Table 18.1** 

Other ACI requirements for load-bearing concrete walls designed by the empirical formula

- 1. The thickness of the walls may not be less than  $\frac{1}{25}$  the supported height or length, whichever is smaller, or less than 4 in. (14.5.3.1).
- 2. The thickness of exterior basement walls and foundation walls may not be less than  $7\frac{1}{2}$ in. (14.5.3.2).
- 3. The horizontal length of a wall that can be considered effective for each concentrated load may not exceed the smaller of the center-to-center distance between loads or the bearing width plus four times the wall thickness. This provision may be waived if a larger value can be proved satisfactory by a detailed analysis (14.2.4).
- **4.** Load-bearing walls must be anchored to intersecting elements, such as floors or roofs, or they should be anchored to columns, pilasters, footings, buttresses, and intersecting walls (14.2.6).

The empirical method is quite easy to apply because only one calculation has to be made to determine the design axial strength of a wall. Example 18.1, which follows, illustrates the design of a bearing wall with a small moment.<sup>1</sup>

#### Example 18.1

Design a concrete-bearing wall using the ACI empirical equation 14-1 to support a set of precast concrete roof beams 7 ft 0 in. on center, as shown in Figure 18.1. The bearing width of each beam is 10 in. The wall is considered to be laterally restrained top and bottom and is further assumed to be restrained against rotation at the footing; thus k = 0.8. Neglect wall weight. Other data:  $f_c' = 3000$  psi,  $f_v = 60,000$  psi, beam reaction, D = 30 k, L = 18 k.

<sup>&</sup>lt;sup>1</sup> For the example problems presented in this chapter, the authors have followed the general procedures used in B. G. Rabbat, et al., ed., Notes on ACI 318-08 Building Code Requirements for Structural Concrete, 2008 (Skokie, IL: Portland Cement Association), pp. 21-17 to 21-18.

Try 8 in.

![](_page_570_Picture_2.jpeg)

**FIGURE 18.1** Empirically designed wall for Example 18.1.

#### SOLUTION

1. Determine minimum wall thickness (14.5.3.1)

(a) 
$$h = (\frac{1}{25})$$
 (12 in/ft × 16 ft) = 7.68 in.  $\leftarrow$ 

**(b)** 
$$h = 4$$
 in.

Compute factored beam reactions

$$P_{ij} = (1.2)(30 \text{ k}) + (1.6)(18 \text{ k}) = 64.8 \text{ k}$$

2. Is the bearing strength of wall concrete satisfactory under beam reactions (10.17.1)?

$$\phi(0.85f_c'A_1) = (0.65)(0.85)(3 \text{ ksi})(8 \text{ in.} \times 10 \text{ in.})$$
$$= 132.6 \text{ k} > 64.8 \text{ k} \quad \underline{\text{OK}}$$

- **3.** Horizontal length of wall to be considered as effective in supporting each concentrated load (14.2.4)
  - (a) Center-to-center spacing of beams 7 ft 0 in. = 84 in.
  - **(b)** Width of bearing +4h = 10 in. +(4)(8 in.) = 42 in.  $\leftarrow$
- 4. Design strength of wall

$$\phi P_{nw} = 0.55 \phi f_c' A_g \left[ 1 - \left( \frac{k \ell_c}{32h} \right)^2 \right]$$
 (ACI Equation 14-1)  
= (0.55) (0.65) (3 ksi) (8 in. × 42 in.) 
$$\left[ 1 - \left( \frac{0.80 \times 12 \text{ in/ft} \times 16 \text{ ft}}{32 \times 8 \text{ in.}} \right)^2 \right]$$
  
= 230.6 k > 64.8 k OK

5. Select reinforcing (14.3.5, 14.3.2, and 14.3.3)

Maximum spacing = (3)(8 in.) = 24 in. or 18 in.

Vertical 
$$A_s = (0.0012)(12 \text{ in.})(8 \text{ in.}) = 0.115 \text{ in}^2/\text{ft}$$
 #4 @ 18 in.  
Horizontal  $A_s = (0.0020)(12 \text{ in.})(8 \text{ in.}) = 0.192 \text{ in}^2/\text{ft}$  #4 @ 12 in.

Although the code is not specific on this issue, it would be prudent to provide continuity of the vertical wall reinforcement into the footing. This is usually accomplished by using a hooked bar embedded in the wall footing that is lap spliced with the vertical wall bars. If a value of k = 1 had been used in this example, there would have been no assumption of continuity at the base of the wall. It would still be necessary to ensure that adequate shear capacity is provided at the base of the wall.

### **18.4 Load-Bearing Concrete Walls—Rational Design**

Reinforced concrete-bearing walls may be designed as columns by the rational method of Chapter 10 of the code whether the eccentricity is smaller or larger than *h*/6 (they must be designed rationally if *e* > *h*/6). The minimum vertical and horizontal reinforcing requirements of Section 14.3 of the code must be met.

The design of walls as columns is difficult unless design aids are available. Various wall design aids are available from the Portland Cement Association, but the designer can prepare his or her own aids, such as axial load and bending interaction diagrams. The designs may be complicated by the fact that walls often will be classified as "long columns" with the result that the slenderness requirements of Section 10.10 of the code will have to be met. An alternative procedure for slender walls is presented in ACI Section 14.8.

Very slender walls are rather common, particularly in tilt-up wall construction. The Portland Cement Association has available a design aid that is particularly useful for such cases.2

The interaction diagrams discussed in Section 10.6 of this text can be used to design walls with steel in two layers and subject to out-of-plane bending combined with axial loads. However, the reinforcement ratio is limited to 0.01, unless the compression reinforcement is laterally tied (ACI Section 14.3.6), which is impractical in many cases. Graphs 2 through 5 in Appendix A are applicable to walls that have two layers of steel. The values of γ for these graphs may be too large, however, especially for thinner walls. Example 18.2 illustrates how to use these design aids when designing walls.

#### Example 18.2

Design the reinforced concrete foundation wall shown in Figure 18.2 that has the following conditions: l = 15 ft between lateral supports, backfill height is also 15 ft, *PD* = 520 plf at *e* = 2 in., *and PL* = 250 plf at *e* = 2 in. Assume the base is pinned.

```
f
c = 4000 psi, normal-weight aggregate concrete, Grade 60 reinforcing steel
Soil properties, ka = 0.40, γ = 100 pcf
```

#### **SOLUTION**

Assuming that the wall is simply supported at both the top and bottom, the soil pressure exerted on the wall increases linearly from zero at the top of backfill to *ka*γ l at the base. The maximum bending moment<sup>3</sup> is

$$M_H = 0.064 k_a \gamma \ell^3 = (0.064) (0.4) (100 \text{ pcf}) (15 \text{ ft})^3$$
  
= 8640 ft-lb/ft = 103,680 in-lb/ft

Maximum moment occurs at 0.577l = 8.66 ft from top of wall or 6.34 ft from the bottom. Note that the eccentric axial loads cause a reduction in the moment. In the case of dead axial load, the moment at the top of the wall is *P* × *e* = 520 plf(2 in.) = 1040 in-lb/ft. This moment varies linearly to zero at the base of the wall, so at the location of maximum soil moment, its value is 1040 in-lb(6.34 ft)/15 ft = 440 in-lb/ft. The same analysis applied to the live load results in a moment of 212 in-lb/ft. In this case, the reduction in moment from eccentric axial load is

<sup>2</sup> Portland Cement Association, 2005. *The Tilt-up Construction and Engineering Manual*, 6th ed. (Skokie, IL), 28 pages. <sup>3</sup> McCormac, J. C., 2006, *Structural Analysis*: *Using Classical and Matrix Methods*, 4th ed. (Hoboken, NJ: John Wiley & Sons), pp. 104–106.

![](_page_572_Figure_2.jpeg)

**FIGURE 18.2** Foundation wall for Example 18.2.

small (less than 3%) and could be ignored. At the location of maximum bending moment, the axial loads are

$$P_D = 520 \text{ plf} + (8.66 \text{ ft}) (150 \text{ pcf}) (8 \text{ in.}) (12 \text{ in.}) / 144 \text{ in}^2/\text{ft}^2$$
  
= 1386 plf (assuming an 8-in. wall thickness)  
 $P_L = 250 \text{ plf}$ 

Three load combinations applicable to this situation are shown in the table below along with  $K_n$  and  $R_n$  values used in conjunction with Graph 2 in Appendix A.

|                        | $P_D$ | $P_L$ | $P_H$ | $M_D$ | $M_L$ | M <sub>H</sub> | $P_U$ | M <sub>U</sub> | $K_n = \frac{PU}{\phi f_C' Ag}$ | $R_n = \frac{MU}{\phi f_C' Agh}$ | $\rho_t$ |
|------------------------|-------|-------|-------|-------|-------|----------------|-------|----------------|---------------------------------|----------------------------------|----------|
| Unfactored             | 1386  | 250   | 0     | 600   | 288   | 103,680        |       |                |                                 |                                  |          |
| U = 1.4D               | 1.4   |       |       | 1.4   |       |                | 1940  | 840            | 0.0056                          | 0.0003                           | < 0.01   |
| U = 1.2D + 1.6L + 1.6H | 1.2   | 1.6   | 1.6   | 1.2   | 1.6   | 1.6            | 2063  | 166,877        | 0.0060                          | 0.0604                           | 0.01     |
| U = 0.9D + 1.6H        | 0.9   |       | 1.6   | 0.9   |       | 1.6            | 1247  | 166,284        | 0.0036                          | 0.0602                           | 0.01     |

There is so little difference between the second and third load case that the difference in  $\rho_t$  is indistinguishable when reading the graph. Also, a value of  $\phi=0.9$  was used because when reading the graph, it is obvious that the controlling points are below the line for  $\epsilon_t=0.005$ . Using the resulting value of  $\rho_t$ ,  $A_{st}=\rho_t bh=0.010(12$  in.) (8 in.) = 0.96 in²/ft, half in each face (0.48 in²/ft). From Appendix A, Table A.6, select #5 at  $7\frac{1}{2}$  in. o.c. vertically in both faces. The #5 bar size was picked because the required cover increases for larger bars from  $1\frac{1}{2}$  to 2 in. Horizontal reinforcing must be provided in accordance with ACI 14.3.3(b),  $A_s \ge 0.0025bh=0.0025(12$  in.) (8 in.) = 0.24 in²/ft. Choose #4 at 18 in. o.c. horizontally in both faces. Since this wall is less than 10 in. thick, ACI 14.3.4 permits the reinforcement to be placed in a single layer. However, Graph 2 is based on having steel in two layers separated by a distance of  $\gamma h=0.6(8)=4.8$  in. Actually, a value of  $\gamma=0.5$  would have been a better choice in this problem in order to provide sufficient cover, but it is not available.

Because the axial load is so small in this case, the wall could have been designed as a vertical beam with compression steel. The beam width would be 12 in., h = 8 in., d = 6.4 in., and the moment taken as 167 in-k. The authors carried out this design approach using the Chapter 5 spreadsheet and calculated a required area of reinforcing steel of 0.98 in<sup>2</sup>/ft (compared with 0.96 in<sup>2</sup>/ft from Graph 2).

The wall exerts reactions at the bottom against the footing and at the top against the floor. The floor system must be designed to resist this horizontal force, which is called a "diaphragm force." At the bottom, the interface of the wall and the footing must be designed for shear transfer between these elements. Shear friction (Section 8.12 of this text) is the best way to accommodate this transfer.

Note that this wall has a slenderness ratio of  $kl_u/r = 1.0(15 \text{ ft})12 \text{ in/ft/}(0.3) (8 \text{ in.}) = 75 > 34 - 12(0/M_2) = 34$ , so slenderness must be considered. However, since the axial loads are so small, the moment magnifier is not greater than 1.0; hence the moment is not magnified.

If this wall were not laterally supported at the top by the floor shown in Figure 18.2, it would be a retaining wall. The bending moment from soil pressure on the retaining wall would be *MH* <sup>=</sup> *ka*<sup>γ</sup> <sup>l</sup>3/6, which is 260% of the moment in Example 18.2. Be sure to use the correct moment for the boundary conditions that apply to your type of construction.

If the reinforcement ratio had exceeded 0.01, this method of solution would not have been valid. It would have been necessary to use mechanics to determine the wall capacity without using steel in compression. The design aids used in this example use the compression force in the reinforcing steel, hence the steel has to be laterally tied for this solution to be valid.

### **18.5 Shear Walls**

For tall buildings, it is necessary to provide adequate stiffness to resist the lateral forces caused by wind and earthquake. When such buildings are not properly designed for these forces, there may be very high stresses, vibrations, and sidesway when the forces occur. The results may include not only severe damages to the buildings but also considerable discomfort for their occupants.

When reinforced concrete walls with their very large in-plane stiffnesses are placed at certain convenient and strategic locations, often they can be economically used to provide the needed resistance to horizontal loads. Such walls, called *shear walls*, are in effect deep vertical cantilever beams that provide lateral stability to structures by resisting the in-plane shears and bending moments caused by the lateral forces.

As the strength of shear walls is almost always controlled by their flexural resistance, their name is something of a misnomer. It is true, however, that on some occasions they may require some shear reinforcing to prevent diagonal tension failures. Indeed, one of the basic requirements of shear walls designed for high seismic forces is to ensure flexure rather than shear-controlled design.

![](_page_573_Picture_8.jpeg)

Shear wall with integral end columns—Rhodes Annex.

![](_page_574_Picture_2.jpeg)

**FI GU RE 18.3** Plan view of a floor supported by shear walls.

The usual practice is to assume that the lateral forces act at the floor levels. The stiffnesses of the floor slabs horizontally are quite large as compared to the stiffnesses of the walls and columns. Thus, it is assumed that each floor is displaced in its horizontal plane as a rigid body.

Figure 18.3 shows the plan of a building that is subjected to horizontal forces. The lateral forces, usually from wind or earthquake loads, are applied to the floor and roof slabs of the building, and those slabs, acting as large beams lying on their sides or diaphragms, transfer the loads primarily to the shear walls A and B. Should the lateral forces be coming from the other (perpendicular) direction, they would be resisted primarily by the shear walls C and D.

The walls must be sufficiently stiff so as to limit deflections to reasonable values.

Shear walls are commonly used for buildings with flat-plate floor slabs. In fact, this combination of slabs and walls is the most common type of construction used today for tall apartment buildings and other residential buildings.

![](_page_574_Picture_8.jpeg)

Buttress shear wall, New York Hilton, New York, New York.

![](_page_575_Figure_2.jpeg)

**FI GU RE 18.4** Shear walls around elevators and stairwells.

Shear walls span the entire vertical distances between floors. If the walls are carefully and symmetrically placed in plan, they will efficiently resist both vertical and lateral loads and do so without interfering substantially with the architectural requirements. Reinforced concrete buildings of up to 70 stories have been constructed with shear walls as their primary source of lateral stiffness. In the horizontal direction, full shear walls may be used—that is, they will run for the full panel or bay lengths. When forces are smaller, they need only run for partial bay lengths.

Shear walls may be used to resist lateral forces only, or they may be used in addition as bearing walls. Furthermore, they may be used to enclose elevators, stairwells, and perhaps restrooms, as shown in Figure 18.4. These box-type structures are very satisfactory for resisting horizontal forces.

Another possible arrangement of shear walls is shown in Figure 18.5. Although shear walls may be also be needed in the long direction of this building, they are not included in this figure.

On most occasions, it is not possible to use shear walls without some openings in them for doors, windows, and penetrations for mechanical services. Usually it is possible, however, with careful planning to place these openings so they do not seriously affect stiffnesses or stresses in the walls. When the openings are small, their overall effect is minor, but this is not the case when large openings are present.

Usually the openings (windows, doors, etc.) are placed in vertical and symmetrical rows in the walls throughout the height of the structure. The wall sections on the sides of these openings

![](_page_575_Figure_9.jpeg)

**FI GU RE 18.5** Building plan having shear walls in only one direction.

are tied together by beams enclosed in the walls, by the floor slabs, or by a combination of both. As you can see, the structural analysis for such a situation is extremely complicated. Although shear wall designs are often handled with empirical equations, they can be appreciably affected by the designer's previous experience.

When earthquake-resistant construction is being considered, note that the relatively stiff parts of a structure will attract much larger forces than will the more flexible parts. A structure with reinforced concrete shear walls is going to be quite stiff and, thus, will attract large seismic forces. If the shear walls are brittle and fail, the rest of the structure may not be able to take the shock. If the shear walls are ductile, however (and they will be if properly reinforced), they will be very effective in resisting seismic forces.

Tall reinforced concrete buildings are often designed with shear walls to resist seismic forces, and such buildings have performed quite well in recent earthquakes. During an earthquake, properly designed shear walls will decidedly limit the amount of damage to the structural frame. They will also minimize damages to the nonstructural parts of a building, such as the windows, doors, ceilings, and partitions.

Figure 18.6 shows a shear wall subjected to a lateral force, *Vu* . The wall is in actuality a cantilever beam of width *h* and overall depth l*w*. In part (a) of the figure, the wall is being bent from left to right by *Vu* , with the result that tensile bars are needed on the left or tensile side. If *Vu* is applied from the right side as shown in part (b) of the figure, tensile bars will be needed on the right-hand end of the wall. Thus, it can be seen that a shear wall needs tensile reinforcing on both sides because *Vu* can come from either direction. For horizontal shear calculations, the depth of the beam from the compression end of the wall to the center of gravity of the tensile bars is estimated to be about 0.8 times the wall length, l*w*, as per ACI Section 11.10.4. (If a larger value of *d* is obtained by a proper strain compatibility analysis, it may be used.)

The shear wall acts as a vertical cantilever beam. In providing lateral support, it is subjected to both bending and shear forces. For such a wall, the maximum shear, *Vu* , and the maximum moment, *Mu* , can be calculated at the base. If flexural stresses are calculated, their magnitude will be affected by the design axial load, *Nu* , and thus its effect should be included in the analysis.

Shear is more important in walls with small height-to-length ratios. Moments will be more important for higher walls, particularly those with uniformly distributed reinforcing.

It is necessary to provide both horizontal and vertical shear reinforcing for shear walls. The commentary (R11.9.9) says that in low walls, the horizontal shear reinforcing is less effective, and the vertical shear reinforcing is more effective. For high walls, the situation is reversed. This situation is reflected in ACI Equation 11-32, which is presented in the next section. The vertical shear reinforcing contributes to the shear strength of a wall by shear friction.

![](_page_576_Figure_9.jpeg)

**FI GU RE 18.6** Shear wall loaded in opposite directions.

Reinforcing bars are placed around all openings, whether or not structural analysis indicates a need for them. Such a practice is deemed necessary to prevent diagonal tension cracks, which tend to develop radiating from the corners of openings.

#### **ACI Provisions for Shear Walls**

1. The factored beam shear must be equal to or less than the design shear strength of the wall.

$$V_u \leq \phi V_n$$

2. The design shear strength of a wall is equal to the design shear strength of the concrete plus that of the shear reinforcing.

$$V_u \leq \phi V_c + \phi V_s$$

- 3. The nominal shear strength,  $V_n$ , at any horizontal section in the plane of the wall may not be taken greater than  $10\sqrt{f_c'}hd$  (11.9.3).
- **4.** In designing for the horizontal shear forces in the plane of a wall, d is to be taken as equal to  $0.8\ell_w$ , where  $\ell_w$  is the horizontal wall length between faces of the supports, unless it can be proved to be larger by a strain compatibility analysis (11.9.4).
- 5. ACI Section 11.10.5 states that unless a more detailed calculation is made (as described in the next paragraph), the value of the nominal shear strength,  $V_c$ , used may not be larger than  $2\lambda \sqrt{f_c'}hd$  for walls subject to a factored axial compressive load,  $N_u$ . Should a wall be subject to a tensile load,  $N_u$ , the value of  $V_c$  may not be larger than the value obtained with the following equation:

$$V_c = 2\left(1 + \frac{N_u}{500A_g}\right)\lambda\sqrt{f_c'}b_w d \ge 0$$
 (ACI Equation 11-8)

**6.** Using a more detailed analysis, the value of  $V_c$  is to be taken as the smaller value obtained by substituting into the two equations that follow, in which  $N_{\mu}$  is the factored axial load normal to the cross section occurring simultaneously with  $V_u$ .  $N_u$  is to be considered positive for compression and negative for tension (11.10.6).

$$V_c = 3.3\lambda \sqrt{f_c'}hd + \frac{N_u d}{4\ell_w}$$
 (ACI Equation 11-29)

or

$$V_{c} = \left[ 0.6\lambda \sqrt{f_{c}'} + \frac{\ell_{w} \left( 1.25\lambda \sqrt{f_{c}'} + 0.2N_{u}/\ell_{w}h \right)}{(M_{u}/V_{u}) - (\ell_{w}/2)} \right] hd \qquad (ACI Equation 11-30)$$

The first of these equations was developed to predict the inclined cracking strength at any section through a shear wall corresponding to a principal tensile stress of about  $4\lambda\sqrt{f_c'}$  at the centroid of the wall cross section. The second equation was developed to correspond to an occurrence of a flexural tensile stress of  $6\lambda\sqrt{f_c'}$  at a section  $\ell_w/2$  above the section being investigated. Should  $M_u/V_u - \ell_w/2$  be negative, the second equation will have no significance and will not be used.

In SI units, these last three equations are as follows:

$$V_c = \left(1 + \frac{0.3N_u}{A_g}\right) \frac{\lambda \sqrt{f_c'}}{6} b_w d \ge 0$$
 (ACI Equation 11-8)

$$V_c = \frac{1}{4}\lambda\sqrt{f_c'}hd + \frac{N_u d}{4\ell_w}$$
 (ACI Equation 11-29)

$$V_c = \left[ \frac{1}{2} \lambda \sqrt{f_c'} + \frac{\ell_w \left( \lambda \sqrt{f_c'} + 2N_u / \ell_w h \right)}{(M_u / V_u) - (\ell_w / 2)} \right] \frac{hd}{10}$$
 (ACI Equation 11-30)

- 7. The values of  $V_c$  computed by the two preceding equations at a distance from the base equal to  $\ell_w/2$  or  $h_w/2$  (whichever is less) are applicable for all sections between this section and one at the wall base (11.9.7).
- 8. Should the factored shear,  $V_u$ , be less than  $\phi V_c/2$  computed as described in the preceding two paragraphs, it will not be necessary to provide a minimum amount of both horizontal and vertical reinforcing, as described in Section 11.9.9 or Chapter 14 of the code.
- 9. Should  $V_u$  be greater than  $\phi V_c$ , shear wall reinforcing must be designed as described in Section 11.9.9 of the code.
- 10. If the factored shear force,  $V_u$ , exceeds the shear strength,  $\phi V_c$ , the value of  $V_s$  is to be determined from the following expression, in which  $A_v$  is the area of the horizontal shear reinforcement and s is the spacing of the shear or torsional reinforcing in a direction perpendicular to the horizontal reinforcing (11.9.9.1).

$$V_s = \frac{A_v f_y d}{s}$$
 (ACI Equation 11-31)

- 11. The amount of horizontal shear reinforcing,  $\rho_t$  (as a percentage of the gross vertical concrete area) shall not be less than 0.0025 (11.9.9.2).
- **12.** The maximum spacing of horizontal shear reinforcing,  $s_2$ , shall not be greater than  $\ell_w/5$ , 3h, or 18 in. (11.9.9.3).
- 13. The amount of vertical shear reinforcing,  $\rho_n$  (as a percentage of the gross horizontal concrete area) shall not be less than the value given by the following equation, in which  $h_w$  is the total height of the wall (11.9.9.4).

$$\rho_{\ell} = 0.0025 + 0.5 \left( 2.5 - \frac{h_w}{\ell_w} \right) (\rho_h - 0.0025)$$
 (ACI Equation 11-32)

It shall not be less than 0.0025 but need not be greater than the required horizontal shear reinforcing,  $\rho_t$ .

For high walls, the vertical reinforcing is much less effective than it is in low walls. This fact is reflected in the preceding equation, where for walls with a height/length ratio less than half, the amount of vertical reinforcing required equals the horizontal reinforcing required. If the ratio is larger than 2.5, only a minimum amount of vertical reinforcing is required (i.e., 0.0025sh).

**14.** The maximum spacing of vertical shear reinforcing shall not be greater than  $\ell_w/3$ , 3h, or 18 in. (11.9.9.5).

#### Example 18.3

Design the reinforced concrete shear wall shown in Figure 18.7 if  $f'_c = 3000 \, \mathrm{psi}$  and  $f_v = 18.7 \, \mathrm{m}$ 60,000 psi.

#### SOLUTION

1. Is the wall thickness satisfactory?

$$\begin{split} V_u &= \phi \, 10 \sqrt{f_c'} hd & \text{(ACI Section 11.9.3)} \\ d &= 0.8 \ell_w = (0.8) \, (12 \times 10 \text{ ft}) = 96 \text{ in.} & \text{(ACI Section 11.9.4)} \\ V_u &= (0.75) \, (10) \, (\sqrt{3000} \text{ psi)} \, (8 \text{ in.}) \, (96 \text{ in.}) \\ V_u &= 315,488 \text{ lb} = 315.5 \text{ k} > 240 \text{ k} & \underline{\text{OK}} \end{split}$$

**2.** Compute  $V_c$  for wall (lesser of two values)

(a) 
$$V_c = 3.3\lambda\sqrt{f_c'}hd + \frac{N_ud}{4\ell_w} = (3.3)(1.0)(\sqrt{3000} \text{ psi}) (8 \text{ in.}) (96 \text{ in.}) + 0$$

$$= 138,815 \text{ lb} = 138.8 \text{ k} \leftarrow \text{ controls} \qquad (ACI \text{ Equation 11-27})$$
(b)  $V_c = \left[ 0.6\lambda\sqrt{f_c'} + \frac{\ell_w\left(1.25\lambda\sqrt{f_c'} + 0.2N_u/\ell_wh\right)}{(M_u/V_u) - (\ell_w/2)} \right] hd \qquad (ACI \text{ Equation 11-28})$ 

Computing  $V_u$  and  $M_u$  at the lesser of  $\ell_w/2=10/2=5$  ft or  $h_w/2=14/2=7$  ft from base (ACI 11.9.7):

$$V_{ij} = 240 \text{ k}$$

$$M_{ij} = 240 \text{ k}(14 \text{ ft} - 5 \text{ ft}) = 2160 \text{ ft-k} = 25,920 \text{ in-k}$$

$$V_{c} = \left[ (0.6) (1.0) (\sqrt{3000} \text{ psi}) + \frac{(12 \text{ in/ft} \times 10 \text{ ft}) (1.25) (1.0) (\sqrt{3000} \text{ psi}) + 0}{\frac{25,920 \text{ in-k}}{240 \text{ k}} - \frac{(12 \text{ in/ft}) (10 \text{ ft})}{2}} \right] (8 \text{ in.}) (96 \text{ in.})$$

$$= 156,692 \text{ lb} = 156.7 \text{ k}$$

![](_page_579_Figure_13.jpeg)

FIGURE 18.7 Shear wall for Example 18.3.

3. Is shear reinforcing needed?

$$\frac{\phi V_c}{2} = \frac{(0.75)(1.0)(138.8 \text{ k})}{2} = 52.05 \text{ k} < 240 \text{ k}$$
 Yes

4. Select horizontal shear reinforcing

$$\begin{split} V_u &= \phi V_c + \phi V_s \\ V_u &= \phi V_c + \phi \frac{A_v f_y d}{s} \\ \frac{A_v}{s} &= \frac{V_u - \phi V_c}{\phi f_v d} = \frac{240 \text{ k} - (0.75) (138.8 \text{ k})}{(0.75) (60 \text{ ksi}) (96 \text{ in.})} = 0.0315 \text{ in.} \end{split}$$

Try different-sized horizontal bars with  $A_{\nu}$  = two-bar cross sectional areas. Two layers of horizontal bars will be placed at the calculated spacing, hence  $A_{\nu}$  = twice the bar area. Compute  $s_2$  = vertical spacing of horizontal shear reinforcing.

Try #3 bars: 
$$s = \frac{(2)(0.11 \text{ in.}^2)}{0.0315 \text{ in.}} = 6.98 \text{ in.}$$

Try #4 bars: 
$$s = \frac{(2)(0.20 \text{ in.}^2)}{0.0315 \text{ in.}} = 12.70 \text{ in.}$$

Maximum vertical spacing of horizontal stirrups

$$\frac{\ell_w}{5} = \frac{\text{(12 in/ft) (10 ft)}}{5} = 24 \text{ in.}$$

$$3h = \text{(3) (8 in.)} = 24 \text{ in.}$$

$$18 \text{ in.} = 18 \text{ in.} \leftarrow$$

$$\rho_t = \frac{A_v}{A_s}$$

$$Use \#4 @ 12 \text{ in.}$$

where  $A_q$  = wall thickness times the vertical spacing of the horizontal stirrups

$$\rho_t = \frac{(2)(0.20)}{(8)(12)} = 0.00417$$

which is greater than the minimum  $\rho_n$  of 0.0025 required by code (11.9.9.2).

Use 2 #4 horizontal bars 12 in. o.c. vertically

5. Design vertical shear reinforcing

$$\begin{aligned} \min \rho_{\ell} &= 0.0025 + 0.5 \left( 2.5 - \frac{h_{w}}{\ell_{w}} \right) (\rho_{h} - 0.0025) \end{aligned} \qquad \text{(ACI Equation 11-30)}$$

$$= 0.0025 + 0.5 \left( 2.5 - \frac{12 \text{ in/ft} \times 14 \text{ ft}}{12 \text{ in/ft} \times 10 \text{ ft}} \right) (0.00417 - 0.0025)$$

$$= 0.00342$$

Assume #4 vertical bars with  $A_v$  = two-bar cross-sectional areas and with s = horizontal spacing of vertical bars.

$$s = \frac{(2)(0.20 \text{ in.}^2)}{(8 \text{ in.})(0.00342)} = 14.62 \text{ in.}$$

![](_page_581_Figure_2.jpeg)

**FIGURE 18.8** Final reinforcing details for Example 18.3.

Maximum horizontal spacing of vertical stirrups

$$\frac{\ell_w}{3} = \frac{\text{(12 in/ft) (10 ft)}}{3} = 40 \text{ in.}$$

$$3h = (3) (8 \text{ in.}) = 24 \text{ in.}$$

$$18 \text{ in.} = 18 \text{ in.} \leftarrow$$

Use 2 #4 vertical bars 14 in. o.c. horizontally

6. Design vertical flexural reinforcing

$$M_u = (240 \text{ k}) (14 \text{ ft}) = 3360 \text{ ft-k} \text{ at base of wall}$$
 
$$\frac{M_u}{\phi b d^2} = \frac{(12 \text{ in/ft}) (3360 \text{ ft-k}) (1000)}{(0.9) (8 \text{ in.}) (96 \text{ in.})^2} = 607.6 \text{ psi}$$
 
$$\rho = 0.0118 \text{ (from Appendix A, Table A.12)}$$
 
$$A_s = \rho b d$$

where b is wall thickness and d is approximated by  $0.80\ell_w = (0.8)(12 \text{ in/ft} \times 10 \text{ ft}) = 96 \text{ in.}$ 

$$A_s = (0.0118)(8 \text{ in.})(96 \text{ in.}) = 9.06 \text{ in.}^2$$

#### Use 10 #9 bars each end (assuming $V_{ij}$ could come from either direction)

7. A sketch of the wall cross section is given in Figure 18.8. If this same wall were subjected to significant axial load, the method used to calculate  $A_s$  for flexure would have to be revised to include its effect. Spreadsheets to calculate the coordinates of the interaction diagram using the assumptions in Chapter 10 can be developed for this purpose.

The centroid of the bar group at either end of the wall is approximately 7 in. from the wall end. Assuming all of the tension bars are yielding, the resultant tension force is also located at 7 in. from the wall end. The assumed value of  $d = 0.8 \ell_w$  was overly conservative. It can be taken as 120 - 7 = 113 in. Revising the calculation for  $A_s$  using this value of d results in a new  $A_s = 7.32$  in.<sup>2</sup> As a result, the bar size can be reduced to #8 with the same number of bars (10 #8 bars at each end).

### **18.7 Economy in Wall Construction**

To achieve economical reinforced concrete walls, it is necessary to consider such items as wall thicknesses, openings, footing elevations, and so on.

The thicknesses of walls should be sufficient to permit the proper placement and vibration of the concrete. All of the walls in a building should have the same thickness if practical. Such a practice will permit the reuse of forms, ties, and other items. Furthermore, it will reduce the possibilities of field mistakes.

As few openings as possible should be placed in concrete walls. Where openings are necessary, it is desirable to repeat the sizes and positions of openings in different walls rather than using different sizes and positions. Furthermore, a few large openings are more economical than a larger number of smaller ones.

Much money can be saved if a footing elevation can be kept constant for any given wall. Such a practice will appreciably simplify the use of wall forms. If steps are required in a footing, their number should be kept to the minimum possible.4

![](_page_582_Picture_7.jpeg)

South Point water facility, Durham, North Carolina.

<sup>4</sup> Neville, G. B., ed., 1984, *Simplified Design Reinforced Concrete Buildings of Moderate Size* (Skokie, IL: Portland Cement Association), pp. 9-12 to 9-13.

#### 18.8 **Computer Example**

Concrete walls can be designed using the Excel spreadsheet provided for Chapters 9 and 10 with appropriate input values and interpretation of results. A value of b = 12 in. is used for walls loaded out-of-plane; thus, the loads per foot of wall length are simply the input loads. Only a value of  $A_{s,1}$  is input, as it is uncommon to have more than two layers of steel in a wall. If only one layer is used, then input a value of  $\gamma = 0$ . In order to avoid having to laterally tie the compression reinforcement, the total vertical reinforcement area is limited to 0.01 times the gross concrete area. The spreadsheet could easily be modified to neglect the contribution of the compression steel, and if this were done, the 0.01 limit would not have to be applied.

#### Example 18.4

Work Example 18.2 using the spreadsheets for Chapters 9 and 10.

#### SOLUTION

Open the Excel spreadsheet for Chapters 9 and 10, and the Rect Col Worksheet. Enter one load case at a time. Refer to the table of load combinations in Example 18.2, and look under the heading  $P_u$  and  $M_u$ . Only the values of  $P_u$  and  $M_u$  for loading combination U = 0.9D + 1.6H are shown in the screenshot below. It is not possible in this example to distinguish between the value of  $A_{\rm s1}$  required for load cases U=0.9D+1.6H and U=1.2D+1.6L+1.6H, so only the former is shown. Once values are entered for  $P_u$ ,  $M_u$ , b (always 12 in. for walls loaded out-of-plane), h,  $f'_{c}$ , and  $f_{y}$ , enter trial values for  $A_{s1}$  ( $A_{s2}$  is always zero for walls loaded out-of-plane). Look at the interaction diagram and see if the loading "dot" is within the contour of the interaction diagram. Use the smaller diagram that has been reduced by the  $\phi$  factor. If the dot falls well outside the contour, you may need to increase the wall thickness. In working this problem with the interaction diagrams in Appendix A, it was necessary to use  $\gamma = 0.6$ . For walls with two steel layers,  $\gamma = 0.5$  is more realistic, and this example could be easily worked using this value. The value of  $A_{s1}$  obtained by trial and error is the total area of steel per foot of wall length. Half goes in each layer, so enter Appendix A, Table A.6, seeking a value close to and exceeding 0.48 in<sup>2</sup>/ft. Select #5 at  $7\frac{1}{2}$  in.  $(A_s = 0.49 \text{ in}^2/\text{ft})$ . If the steel is in only one layer, enter a value of  $\gamma = 0$ . Steel placed in this fashion is less efficient, and often a thicker wall is needed. Refer to Example 18.2 for horizontal steel requirements

#### Rectangular Column Capacity

![](_page_583_Figure_9.jpeg)

![](_page_584_Figure_2.jpeg)

#### **PROBLEMS**

**Problem 18.1** Design a reinforced concrete bearing wall using the ACI empirical formula to support a set of precast concrete roof beams 6 ft 0 in. on center as shown. The bearing width of each beam is 8 in. The wall is considered to be laterally supported at top and bottom and is further assumed to be restrained against rotation at the footing. Neglect wall weight. Other data:  $f_c' = 3000$  psi,  $f_y = 60,000$  psi, beam reaction, D = 35 k, and L = 25 k. (Ans.  $7\frac{1}{2}$ -in. wall with #3 bars @ 12-in. vertical steel)

![](_page_584_Figure_5.jpeg)

**Problem 18.2** Repeat Problem 18.1 if the wall is not restrained against rotation at top or bottom, is 8 ft 0 in. in height, and has an  $f'_c = 4000$  psi.

**Problem 18.3** Design the reinforced concrete wall shown if  $f'_c = 4000$  psi and  $f_y = 60,000$  psi. (*One ans.* 10-in. wall with 8 #9 flexural bars at each end)

![](_page_584_Figure_8.jpeg)

**Problem 18.4** Repeat Problem 18.3 if  $h_w = 15$  ft 0 in. and  $f_c' = 3000$  psi.

**Problem 18.5** Design the wall in Problem 18.1 using the column interaction diagrams (see Example 18.2). Change the 15-ft wall height to 20 ft. Replace the beams with a solid, one-way slab. The slab exerts a dead load of 6 k/ft and a live load of 4 k/ft, both at a 3-in. eccentricity measured from the center of the wall toward the left. Soil backfill is placed to a depth of 20 ft on the right-hand side of the wall.  $\gamma_s = 100 \text{ pcf}$ and  $k_a = 0.33$ . (Ans. 8-in. wall with #7 bars @ 5 in., 2 layers) Problem 18.6 Repeat Problem 18.5 using Chapters 8 and 9 Excel spreadsheets.

**Problem 18.7** Repeat Problem 18.6 using steel in one layer. (Ans. 12-in. wall with #9 @ 3 in.)

#### **Problem in SI Units**

#### Problem 18.8 Design a reinforced concrete

bearing wall using the ACI empirical formula to support a set of precast roof beams 2 m on center as shown. The bearing width of each beam is 200 mm. The wall is considered to be laterally restrained at top and bottom and is further assumed to be restrained against rotation at the footing. Neglect wall weight. Other data:  $f'_c = 21$  MPa,  $f_v = 420$  MPa, beam reaction, D = 120 kN, and L = 100 kN. (Ans. 160-mm-thick wall with #10 bars @ 200 mm o.c. horizontal reinforcing)

![](_page_585_Picture_8.jpeg)

