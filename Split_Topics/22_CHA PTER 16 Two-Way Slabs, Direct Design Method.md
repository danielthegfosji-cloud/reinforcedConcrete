# **CHA PTER 16** Two-Way Slabs, Direct Design Method

### **16.1 Introduction**

In general, slabs are classified as being one way or two way. Slabs that primarily deflect in one direction are referred to as *one-way slabs*; see Figure 16.1(a). Simple-span, one-way slabs have been discussed previously in Section 4.7 of this text, while the design of continuous one-way slabs was considered in Section 14.7. When slabs are supported by columns arranged generally in rows so that the slabs can deflect in two directions, they are usually referred to as *two-way slabs*.

Two-way slabs can be strengthened by the addition of beams between the columns, by thickening the slabs around the columns (*drop panels*), and by flaring the columns under the slabs (*column capitals*). These situations are shown in Figure 16.1 and discussed in the next several paragraphs.

*Flat plates*, Figure 16.1(b), are solid concrete slabs of uniform depths that transfer loads directly to the supporting columns without the aid of beams or capitals or drop panels. Flat plates can be constructed quickly because of their simple formwork and reinforcing bar arrangements. They need the smallest overall story heights to provide specified headroom requirements, and they give the most flexibility in the arrangement of columns and partitions. They also provide little obstruction to light and have high fire resistance because there are few sharp corners where spalling of the concrete might occur. Flat plates are probably the most commonly used slab system today for multistory reinforced concrete hotels, motels, apartment houses, hospitals, and dormitories.

Flat plates present a possible problem in transferring the shear at the perimeter of the columns. In other words, there is a danger that the columns may punch through the slabs. As a result, it is frequently necessary to increase column sizes or slab thicknesses or to use *shearheads*. Shearheads consist of steel I or channel shapes placed in the slab over the columns, as discussed in Section 16.5 of this chapter. Although such procedures may seem expensive, the simple formwork required for flat plates will usually result in such economical construction that the extra costs required for shearheads are more than canceled. For heavy industrial loads or long spans, however, some other type of floor system may be required.

*Flat slabs*, shown in Figure 16.1(c), include two-way reinforced concrete slabs with capitals, drop panels, or both. These slabs are very satisfactory for heavy loads and long spans. Although the formwork is more expensive than for flat plates, flat slabs will require less concrete and reinforcing than would be required for flat plates with the same loads and spans. They are particularly economical for warehouses, parking and industrial buildings, and similar structures, where exposed drop panels or capitals are acceptable.

In Figure 16.1(d), a *two-way slab with beams* is shown. This type of floor system is used where its cost is less than the costs of flat plates or flat slabs. In other words, when the loads or spans or both become quite large, the slab thickness and column sizes required for flat plates or flat slabs are of such magnitude that it is more economical to use two-way slabs with beams, despite the higher formwork costs.

Another type of floor system is the *waffle slab*. The floor is constructed by arranging square fiberglass or metal pans with tapered sides with spaces. When the concrete is placed over and between the pans and the forms are removed, the waffle shape is obtained. The intervals or gaps between the pans form the beam webs. These webs are rather deep and provide large moment arms for the reinforcing bars. With waffle slabs, the weight of the concrete is greatly reduced without significantly changing the moment resistance of the floor system. As in flat plates, shear can be a problem near columns. Consequently, waffle floors are usually made solid in those areas to increase shear resistance.

![](_page_512_Picture_3.jpeg)

**FI GU RE 16.1** Slabs.

![](_page_513_Picture_2.jpeg)

**FI GU RE 16.1** (*continued*)

![](_page_513_Picture_4.jpeg)

Flat plate without edge beams. (Buckley Gray Yeoman, Fashion Street, London, 2010)

### **16.2 Analysis of Two-Way Slabs**

Two-way slabs bend under load into dish-shaped surfaces, so there is bending in both principal directions. As a result, they must be reinforced in both directions by layers of bars that are perpendicular to each other. A theoretical elastic analysis for such slabs is a very complex problem because of their highly indeterminate nature. Numerical techniques such as finite difference and finite elements are required, but such methods require sophisticated software to be practical in design. The methods described in this chapter can be done by hand or with simple spreadsheets, and are sufficiently accurate for most design problems.

Actually, the fact that a great deal of stress redistribution can occur in such slabs at high loads makes it unnecessary to make designs based on theoretical analyses. Therefore, the design of two-way slabs is generally based on empirical moment coefficients, which, although they might not accurately predict stress variations, result in slabs with satisfactory overall safety factors. In other words, if too much reinforcing is placed in one part of a slab and too little somewhere else, the resulting slab behavior will probably still be satisfactory. *The total amount of reinforcement in a slab seems more important than its exact placement.*

You should clearly understand that, although this chapter and the next are devoted to two-way slab design based on approximate methods of analysis, there is no intent to prevent the designer from using more exact methods. Designers may design slabs on the basis of numerical solutions, yield-line analysis, or other theoretical methods, provided that it can be clearly demonstrated that they have met all the necessary safety and service ability criteria required by the ACI Code.

Although it has been the practice of designers for many years to use approximate analyses for design and to use average moments rather than maximum ones, two-way slabs so designed have proved to be very satisfactory under service loads. Furthermore, they have been proved to have appreciable overload capacity.

### **16.3 Design of Two-Way Slabs by the ACI Code**

The ACI Code (13.5.1.1) specifies two methods for designing two-way slabs for gravity loads. These are the direct design method and the equivalent frame method.

#### **Direct Design Method**

The code (13.6) provides a procedure with which a set of moment coefficients can be determined. The method, in effect, involves a single-cycle moment distribution analysis of the structure based on (a) the estimated flexural stiffnesses of the slabs, beams (if any), and columns and (b) the torsional stiffnesses of the slabs and beams (if any) transverse to the direction in which flexural moments are being determined. Some types of moment coefficients have been used satisfactorily for many years for slab design. They do not, however, give very satisfactory results for slabs with unsymmetrical dimensions and loading patterns.

#### **Equivalent Frame Method**

In this method, a portion of a structure is taken out by itself, as shown in Figure 16.2, and analyzed much as a portion of a building frame was handled in Example 14.2. The same stiffness values used for the direct design method are used for the equivalent frame method. This latter method, which is very satisfactory for symmetrical frames as well as for those with unusual dimensions or loadings, is discussed in Chapter 17 of this text.

![](_page_515_Picture_2.jpeg)

FIGURE 16.2 Equivalent frame method.

#### **Design for Lateral Loads**

The ACI Code permits considerable freedom for the designer to model two-way slab systems for lateral loads. The method must satisfy equilibrium and geometric compatibility and be in reasonable agreement with test data. The effects of cracking and such parameters as the slab aspect ratio and ratio of column-to-slab span dimensions should be considered (ACI Section R13.5.1.2).

### **Column and Middle Strips**

After the design moments have been determined by either the direct design method or the equivalent frame method, they are distributed across each panel. The panels are divided into column and middle strips, as shown in Figure 16.3, and positive and negative moments are estimated in each strip. The column strip is a slab with a width on each side of the column

![](_page_515_Picture_8.jpeg)

FIGURE 16.3 Column and middle strips.

<sup>&</sup>lt;sup>1</sup> Vanderbilt, M. D., and Corley, W. G., 1983. "Frame Analysis of Concrete Buildings," Concrete International: Design and Construction, Vol. 5, No. 12, pp. 33-43.

![](_page_516_Picture_2.jpeg)

Flat Plate Construction—Pharr Road Condominiums, Atlanta, Georgia.

centerline equal to one-fourth the smaller of the panel dimensions l <sup>1</sup> or l 2 . It includes beams if they are present. The middle strip is the part of the slab between the two column strips.

The part of the moments assigned to the column and middle strips may be assumed to be uniformly spread over the strips. As will be described later in this chapter, the percentage of the moment assigned to a column strip depends on the effective stiffness of that strip and on its *aspect ratio* , l 2 / l <sup>1</sup> (where l <sup>1</sup> is the length of span, center to center, of supports in the direction in which moments are being determined and l <sup>2</sup> is the span length, center to center, of supports in the direction transverse to l 1). Note that Figure 16.3 shows column and middle strips in only one direction. A similar analysis must be performed in the perpendicular direction. The resulting analysis will result in moments in both directions.

### **16.5 Shear Resistance of Slabs**

For two-way slabs supported by beams or walls, shears are calculated at a distance *d* from the faces of the walls or beams. The value of φ *Vc* is, as for beams, φ 2 λ *f c b w d* . Shear is not usually a problem for these types of slabs.

For flat slabs and flat plates supported directly by columns, shear may be the critical factor in design. In almost all tests of such structures, failures have been the result of shear or perhaps shear and torsion. These conditions are particularly serious around exterior columns.

Two kinds of shear must be considered in the design of flat slabs and flat plates. These are the same two that were considered in column footings—one-way and two-way shears (i.e., beam shear and punching shear). For beam shear analysis, the slab is considered to act as a wide beam running between the supports. The critical sections are taken at a distance *d* from

the face of the column or capital. For punching shear, the critical section is taken at a distance d/2 from the face of the column, capital, or drop panel and the shear strength, as usually used in footings, is  $\phi 4\lambda \sqrt{f_c'} b_w d$ .

If shear stresses are too large around interior columns, it is possible to increase the shearing strength of the slabs by as much as 75% by using shearheads. A shearhead, as defined in Section 11.11.4 of the code, consists of four steel I or channel shapes fabricated into cross arms and placed in the slabs, as shown in Figure 16.4(a). The code states that shearhead designs of this type do not apply at exterior columns. Thus, special designs are required, and the code does not provide specific requirements. Shearheads increase the effective  $b_a$  for two-way shear, and they also increase the negative moment resistance of the slab, as described in the code (11.11.4.9). The negative moment reinforcing bars in the slab are usually run over the top of the steel shapes, while the positive reinforcing is normally stopped short of the shapes.

Another type of shear reinforcement permitted in slabs by the code (11.11.3) involves the use of groups of bent bars or wires. One possible arrangement of such bars is shown in Figure 16.4(b). The bars are bent across the potential diagonal tension cracks at 45° angles, and they are run along the bottoms of the slabs for the distances needed to fully develop the

![](_page_517_Figure_5.jpeg)

**FIGURE 16.4** Shear reinforcement for slabs at columns.

bar strengths. Another type of bar arrangement that might be used is shown in Figure 16.4(c). When bars (or wires) are used as shear reinforcement, the code (11.11.3.2) states that the nominal two-way shear strength permitted on the critical section at a distance d/2 from the face of the column may be increased from  $4\sqrt{f_c'}b_ad$  to  $6\sqrt{f_c'}b_ad$ .

The main advantage of shearheads is that they push the critical sections for shear farther out from the columns, thus giving a larger perimeter to resist the shear, as illustrated in Figure 16.5. In this figure,  $\ell_v$  is the length of the shearhead arm from the centroid of the concentrated load or reaction, and  $c_1$  is the dimension of the rectangular or equivalent rectangular column or capital or bracket, measured in the direction in which moments are being calculated. The code (11.11.4.7) states that the critical section for shear shall cross the shearhead arm at a distance equal to  $\frac{3}{4}[\ell_v - (c_1/2)]$  from the column face, as shown in Figure 16.5(b). Although this critical section is to be located so that its perimeter is a minimum, it does not have to be located closer to the column face or edges of capitals or drop panels than d/2 at any point. When shearhead reinforcing is provided with reinforcing bars or steel I or channel shapes, the maximum shear strength can be increased to  $7\sqrt{f_c'}b_o d$  at a distance d/2 from the column. According to the code (11.11.4.8), this is permissible only if the maximum computed shear does not exceed  $4\sqrt{f_c'}b_o d$  along the dashed critical section for shear shown in Figure 16.5(b).

![](_page_518_Figure_4.jpeg)

FIGURE 16.5 Critical sections for shear.

In Section 16.12, the subject of shear stresses is continued with a consideration of the transfer of moments and shears between slabs and columns. The maximum load that a two-way slab can support is often controlled by this transfer strength.

### **16.6 Depth Limitations and Stiffness Requirements**

It is obviously very important to keep the various panels of a two-way slab relatively level (i.e., with reasonably small deflections). Thin reinforced two-way slabs have quite a bit of moment resistance, but deflections are often large. As a consequence, their depths are very carefully controlled by the ACI Code so as to limit these deflections. This is accomplished by requiring the designer to either (a) compute deflections and make sure they are within certain limitations or (b) use certain minimum thicknesses as specified in Section 9.5.3 of the code. Deflection computations for two-way slabs are rather complicated, so the average designer usually uses the minimum ACI thickness values, presented in the next few paragraphs of this chapter.

### **Slabs without Interior Beams**

For a slab without interior beams spanning between its supports and with a ratio of its long span to short span not greater than 2.0, the minimum thickness can be taken from Table 16.1 of this chapter [Table 9.5(c) in the code]. The values selected from the table, however, must not be less than the following values (ACI 9.5.3.2):

- **1.** Slabs without drop panels 5 in.
- **2.** Thickness of those slabs with drop panels outside the panels 4 in.

In Table 16.1, some of the values are given for slabs with drop panels. To be classified as a drop panel, according to Sections 13.3.7 and 13.2.5 of the code, a panel must (a) extend horizontally in each direction from the centerline of the support no less than one-sixth the

|                                  |                       | Without Drop Panels† |                    |                       | With Drop Panels†   |          |  |  |
|----------------------------------|-----------------------|----------------------|--------------------|-----------------------|---------------------|----------|--|--|
|                                  | Exterior Panels       |                      | Interior<br>Panels |                       | Exterior Panels     |          |  |  |
| Yield strength,<br>f y<br>, psi∗ | Without edge<br>beams | With edge<br>beams‡  |                    | Without edge<br>beams | With edge<br>beams‡ |          |  |  |
| 40,000                           | [§]<br>ln<br>33       | ln<br>36             | ln<br>36           | ln<br>36              | ln<br>40            | ln<br>40 |  |  |
| 60,000                           | ln<br>30              | ln<br>33             | ln<br>33           | ln<br>33              | ln<br>36            | ln<br>36 |  |  |
| 75,000                           | ln<br>28              | ln<br>31             | ln<br>31           | ln<br>31              | ln<br>34            | ln<br>34 |  |  |

**TABLE 16.1** Minimum Thickness of Slabs without Interior Beams

<sup>∗</sup>For values of reinforcement yield strength between the values given in the table, minimum thickness shall be determined by linear interpolation.

<sup>†</sup>Drop panel is defined in ACI Sections 13.3.7 and 13.2.5.

<sup>‡</sup>Slabs with beams between columns along exterior edges. The value of <sup>α</sup>*<sup>f</sup>* for the edge beam shall not be less than 0.8.

<sup>§</sup>For two-way construction, <sup>l</sup>*<sup>n</sup>* is the length of the clear span in the long direction, measured face to face of the supports in slabs without beams and face to face of beams or other supports in other cases.

distance, center to center, of supports in that direction and (b) project vertically below the slab a distance no less than one-fourth the thickness of the slab away from the drop panel. In this table,  $\ell_n$  is the length of the clear span in the long direction of two-way construction, measured face to face of the supports in slabs without beams and face to face of beams or other supports in other cases.

Very often slabs are built without interior beams between the columns but with edge beams running around the perimeter of the building. These beams are very helpful in stiffening the slabs and reducing the deflections in the exterior slab panels. The stiffness of slabs with edge beams is expressed as a function of  $\alpha_f$ , which follows.

Throughout this chapter, the letter  $\alpha_f$  is used to represent the ratio of the flexural stiffness  $(E_{cb}I_b)$  of a beam section to the flexural stiffness of the slab  $(E_{cs}I_s)$  whose width equals the distance between the centerlines of the panels on each side of the beam. If no beams are used, as is the case for the flat plate,  $\alpha$  will equal 0. For slabs with beams between columns along exterior edges,  $\alpha$  for the edge beams may not be < 0.8, as specified in a footnote to Table 16.1.

$$\alpha_f = \frac{E_{cb}I_b}{E_{cs}I_s}$$
 (ACI Equation 13-3)

where

 $E_{cb}$  = the modulus of elasticity of the beam concrete

 $E_{cs}$  = the modulus of elasticity of the column concrete

 $I_b$  = the gross moment of inertia about the centroidal axis of a section made up of the beam and the slab on each side of the beam extending a distance equal to the projection of the beam above or below the slab (whichever is greater) but not exceeding four times the slab thickness (ACI 13.2.4)

 $I_s$  = the moment of inertia of the gross section of the slab taken about the centroidal axis and equal to  $h^3/12$  times the slab width, where the width is the same as for  $\alpha$ 

#### Example 16.1

Using the ACI Code, determine the minimum permissible total thicknesses required for the slabs in panels 3 and 2 for the floor system shown in Figure 16.6. Edge beams are used around the building perimeter, and they are 12 in. wide and extend vertically for 8 in. below the slab, as shown in Figure 16.7. They also extend 8 in. out into the slab as required by ACI Section 13.2.4. No drop panels are used, and the concrete in the slab is the same as that used in the edge beams.  $f_{V} = 60,000$  psi.

#### SOLUTION

#### For Interior Panel 3

$$lpha_f=0$$
 (since the interior panels have no perimeter beams) 
$$\ell_n=20~{\rm ft}-\frac{16~{\rm in.}}{12~{\rm in/ft}}=18.67~{\rm ft}~{\rm (clear~distance~between~columns)}$$
 
$${\rm Min}~h=\frac{\ell_n}{33}~{\rm (from~Table~16.1)}$$
 
$$=\frac{18.67~{\rm ft}}{33}=0.566~{\rm ft}=6.79~{\rm in.}$$

May not be less than 5 in., according to Section 9.5.3.2.

![](_page_521_Figure_2.jpeg)

**FIGURE 16.6** Flat-plate floor slab for Example 16.1.

#### For Exterior Panel (2)

Assume h=7 in. and compute  $\alpha_f$  with reference made to Figure 16.7(a). Centroid of crosshatched beam section located by statics 6.55 in. from top.

$$I_b = \left(\frac{1}{3}\right) (20 \text{ in.}) (6.55 \text{ in.})^3 + \left(\frac{1}{3}\right) (12 \text{ in.}) (8.45 \text{ in.})^3 + \left(\frac{1}{3}\right) (8 \text{ in.}) (0.45 \text{ in.})^3$$

$$= 4287 \text{ in.}^4$$

$$I_s = \left(\frac{1}{12}\right) (102 \text{ in.}) (7 \text{ in.})^3 = 2915.5 \text{ in.}^4 \quad \text{See Figure 16.7(b)}$$

$$\alpha = \frac{EI_b}{EI_s} = \frac{(E) (4287 \text{ in.}^4)}{(E) (2915.5 \text{ in.}^4)} = 1.47 > 0.8$$

... This is an edge beam as defined in the footnote of Table 16.1.

Min 
$$h = \frac{\ell_n}{33} = \frac{20 \text{ ft} - \frac{16 \text{ in.}}{12 \text{ in/ft}}}{33} = 0.566 \text{ ft} = 6.79 \text{ in.}$$
Try 7 in.

![](_page_521_Figure_9.jpeg)

**FIGURE 16.7** Sections for edge beam and slab.

#### **Slabs with Interior Beams**

To determine the minimum thickness of slabs with beams spanning between their supports on all sides, Section 9.5.3.3 of the code must be followed. Involved in the expressions presented there are span lengths, panel shapes, flexural stiffness of beams if they are used, steel yield stresses, and so on. In these equations, the following terms are used:

 $\ell_n$  = the clear span in the long direction, measured face to face, of (a) columns for slabs without beams and (b) beams for slab with beams

 $\beta$  = the ratio of the long to the short clear spain

 $\alpha_{fm}$  = the average value of the ratios of beam-to-slab stiffness on all sides of a panel

The minimum thickness of slabs or other two-way construction may be obtained by substituting into the equations to follow, which are given in Section 9.5.3.3 of the code. In the equations, the quantity  $\beta$  is used to take into account the effect of the shape of the panel on its deflection, while the effect of beams (if any) is represented by  $\alpha_{fm}$ . If there are no beams present (as is the case for flat slabs),  $\alpha_{fm}$  will equal 0.

- 1. For  $\alpha_{fin} \leq 0.2$ , the minimum thicknesses are obtained as they were for slabs without interior beams spanning between their supports.
- **2.** For  $0.2 \le \alpha_{fm} \le 2.0$ , the thickness may not be less than 5 in. or

$$h = \frac{\ell_n \left( 0.8 + \frac{f_y}{200,000} \right)}{36 + 5\beta (\alpha_{fin} - 0.2)}$$
 (ACI Equation 9-12)

**3.** For  $\alpha_{fm} > 2.0$ , the thickness may not be less than 3.5 in. or

$$h = \frac{\ell_n \left( 0.8 + \frac{f_y}{200,000} \right)}{36 + 9\beta}$$
 (ACI Equation 9-13)

where  $\ell_n$  and  $f_v$  are in inches and psi, respectively.

For panels with discontinuous edges, the code (9.5.3.3d) requires that edge beams be used, which have a minimum stiffness ratio  $\alpha_f$  equal to 0.8, or else that the minimum slab thicknesses, as determined by ACI Equations 9-12 and 9-13, must be increased by 10%.

The designer may use slabs of lesser thicknesses than those required by the ACI Code, as described in the preceding paragraphs, if deflections are computed and found to be equal to or less than the limiting values given in Table 9.5(b) of the ACI Code (Table 6.1 in this text).

Should the various rules for minimum thickness be followed but the resulting slab be insufficient to provide the shear capacity required for the particular column size, column capitals will probably be required. Beams running between the columns may be used for some slabs where partitions or heavy equipment loads are placed near column lines. A very common case of this type occurs where exterior beams are used when the exterior walls are supported directly by the slab. Another situation where beams may be used occurs where there is concern about the magnitude of slab vibrations. Example 16.2 illustrates the application of the minimum slab thickness rules for a two-way slab with beams.

#### Example 16.2

The two-way slab shown in Figure 16.8 has been assumed to have a thickness of 7 in. Section A–A in the figure shows the beam cross section. Check the ACI equations to determine if the slab thickness is satisfactory for an interior panel. *f <sup>c</sup>* = 3000 psi, *fy* = 60,000 psi, and normal-weight concrete.

#### **SOLUTION**

**(Using the Same Concrete for Beams and Slabs)**

**Computing** *α***<sup>1</sup> for Long (Horizontal) Span for Interior Beams**

*I <sup>s</sup>* = gross moment of inertia of slab 20 ft wide

$$= \left(\frac{1}{12}\right) (12 \text{ in/ft} \times 20 \text{ in.}) (7 \text{ in.})^3 = 6860 \text{ in.}^4$$

*Ib* = gross *I* of T-beam cross section shown in Figure 16.8 about centroidal axis = 18,060 in. 4

$$\alpha_1 = \frac{El_b}{El_s} = \frac{(E)(18,060 \text{ in.}^4)}{(E)(6860 \text{ in.}^4)} = 2.63$$

![](_page_523_Figure_11.jpeg)

**FI GU RE 16.8** A two-way slab.

#### Computing $\alpha_2$ for Long Interior Beams

$$I_s$$
 for 24-ft-wide slab =  $\left(\frac{1}{12}\right)$  (12 in/ft × 24 in.) (7 in.)<sup>3</sup> = 8232 in.<sup>4</sup>

$$I_b = 18,060 \text{ in.}^4$$

$$\alpha_2 = \frac{(E) (18,060 \text{ in.}^4)}{(E) (8232 \text{ in.}^4)} = 2.19$$

$$\alpha_{fm} = \frac{\alpha_1 + \alpha_2}{2} = \frac{2.63 + 2.19}{2} = 2.41$$

#### **Determining Slab Thickness per ACI Section 9.5.3.3**

$$\alpha_{fm} = 2.41 > 2$$

$$h = \frac{\ell_n \left( 0.8 + \frac{f_y}{200,000 \text{ psi}} \right)}{36 + 9\beta}$$

$$\ell_{n \text{ long}} = 24 \text{ ft} - 1 \text{ ft} = 23 \text{ ft}$$

$$\ell_{n \text{ short}} = 20 \text{ ft} - 1 \text{ ft} = 19 \text{ ft}$$

$$\beta = \frac{23 \text{ ft}}{19 \text{ ft}} = 1.21$$

$$h = \frac{(23 \text{ ft}) \left( 0.8 + \frac{60,000 \text{ psi}}{200,000 \text{ psi}} \right)}{36 + (9)(1.21)} = 0.540 \text{ ft} = 6.47 \text{ in.}$$
Use 7-in. slab

Note that the interior panel will generally not control the required slab thickness. Usually it will be an edge or corner panel. The interior panel was chosen here to illustrate the calculations and to avoid excess complexity. Had a corner panel been selected, each edge of the panel would have had a different  $\alpha_f$ .

### 16.7 Limitations of Direct Design Method

For the moment coefficients determined by the direct design method to be applicable, the code (13.6.1) says that the following limitations must be met, unless a theoretical analysis shows that the strength furnished after the appropriate capacity reduction or  $\phi$  factors are applied is sufficient to support the anticipated loads and provided that all serviceability conditions, such as deflection limitations, are met:

- 1. There must be at least three continuous spans in each direction.
- 2. The panels must be rectangular, with the length of the longer side of any panel not being more than two times the length of its shorter side lengths being measured c to c of supports.
- Span lengths of successive spans in each direction may not differ in length by more than one-third of the longer span.
- **4.** Columns may not be offset by more than 10% of the span length in the direction of the offset from either axis between center lines of successive columns.
- **5.** The unfactored live load must not be more than two times the unfactored dead load. All loads must be the result of gravity and must be uniformly distributed over an entire panel.

**6.** If a panel is supported on all sides by beams, the relative stiffness of those beams in the two perpendicular directions, as measured by the following expression, shall not be less than 0.2 or greater than 5.0.

$$\frac{\alpha_{f1}\ell_2^2}{\alpha_{f2}\ell_1^2}$$

The terms  $\ell_1$  and  $\ell_2$  were shown in Figure 16.3.

#### **Distribution of Moments in Slabs** 16.8

The total moment,  $M_o$ , that is resisted by a slab equals the sum of the maximum positive and negative moments in the span. It is the same as the total moment that occurs in a simply supported beam. For a uniform load per unit area,  $q_u$ , it is as follows:

$$M_o = \frac{(q_u \ell_2) (\ell_1)^2}{8}$$

In this expression,  $\ell_1$  is the span length, center to center, of supports in the direction in which moments are being taken and  $\ell_2$  is the length of the span transverse to  $\ell_1$ , measured center to center of the supports.

The moment that actually occurs in such a slab has been shown by experience and tests to be somewhat less than the value determined by the above  $M_o$  expression. For this reason,  $\ell_1$  is replaced with  $\ell_n$ , the clear span measured face to face of the supports in the direction in which moments are taken. The code (13.6.2.5) states that  $\ell_n$  may not be taken to be less than 65% of the span  $\ell_1$  measured center to center of supports. If  $\ell_1$  is replaced with  $\ell_n$ , the expression for  $M_o$ , which is called the *static moment*, becomes

$$M_o = \frac{(q_u \ell_2) (\ell_n)^2}{8}$$
 (ACI Equation 13-4)

When the static moment is being calculated in the long direction, it is convenient to write it as  $M_{ol}$ , and in the short direction as  $M_{os}$ .

It is next necessary to know what proportions of these total moments are positive and what proportions are negative. If a slab was completely fixed at the end of each panel, the division would be as it is in a fixed-end beam, two-thirds negative and one-third positive, as shown in Figure 16.9.

This division is reasonably accurate for interior panels where the slab is continuous for several spans in each direction with equal span lengths and loads. In effect, the rotation of the

![](_page_525_Figure_14.jpeg)

**FIGURE 16.9** Distribution of positive and negative moments.

interior columns is assumed to be small, and moment values of 0.65*Mo* for negative moment and 0.35*Mo* for positive moment are specified by the code (13.6.3.2). For cases where the span lengths and loadings are different, the proportion of positive and negative moments may vary appreciably, and the use of a more detailed method of analysis is desirable. The equivalent frame method (Chapter 17) will provide rather good approximations for such situations.

The relative stiffnesses of the columns and slabs of exterior panels are of far greater significance in their effect on the moments than is the case for interior panels. The magnitudes of the moments are very sensitive to the amount of torsional restraint supplied at the discontinuous edges. This restraint is provided both by the flexural stiffness of the slab and by the flexural stiffness of the exterior column.

Should the stiffness of an exterior column be quite small, the end negative moment will be very close to zero. If the stiffness of the exterior column is very large, the positive and negative moments will still not be the same as those in an interior panel unless an edge beam with a very large torsional stiffness is provided that will substantially prevent rotation of the discontinuous edge of the slab.

If a 2-ft-wide beam were to be framed into a 2-ft-wide column of infinite flexural stiffness in the plane of the beam, the joint would behave as would a perfectly fixed end, and the negative beam moment would equal the fixed-end moment.

If a two-way slab 24 ft wide were to be framed into this same 2-ft-wide column of infinite stiffness, the situation of no rotation would occur along the part of the slab at the column. For the remaining 11 ft widths of slab on each side of the column, there would be rotation varying from zero at the side face of the column to maximums 11 ft on each side of the column. As a result of this rotation, the negative moment at the face of the column would be less than the fixed-end moment. Thus, the stiffness of the exterior column is reduced by the rotation of the attached transverse slab.

To take into account the fact that the rotation of the edge of the slab is different at different distances from the column, the exterior columns and slab edge beam are replaced with an equivalent column that has the same estimated flexibility as the column plus the edge beam. It can be seen that this is quite an involved process; therefore, instead of requiring a complicated analysis, the code (13.6.3.3) provides a set of percentages for dividing the total factored static moment into its positive and negative parts in an end span. These divisions, which are shown in Table 16.2, include values for unrestrained edges (where the slab is simply supported on a masonry or concrete wall) and for restrained edges (where the slab is constructed integrally with a very stiff reinforced concrete wall so that the little rotation occurs at the slab-to-wall connection).

In Figure 16.10, the distribution of the total factored moment for the interior and exterior spans of a flat-plate structure is shown. The plate is assumed to be constructed without beams between interior supports and without edge beams.

| TABLE<br>16.2 |  | Distribution of Total Span Moment in an End Span (ACI Code 13.6.3.3) |  |  |
|---------------|--|----------------------------------------------------------------------|--|--|
|               |  |                                                                      |  |  |

|                                      | (1)                           | (2)                                     | (3)                                             | (4)               | (5)                               |
|--------------------------------------|-------------------------------|-----------------------------------------|-------------------------------------------------|-------------------|-----------------------------------|
|                                      |                               |                                         | Slab Without Beams<br>between Interior Supports |                   |                                   |
|                                      | Exterior Edge<br>Unrestrained | Slab with Beams<br>between All Supports | Without<br>Edge Beam                            | With Edge<br>Beam | Exterior Edge<br>Fully Restrained |
| Interior negative<br>factored moment | 0.75                          | 0.70                                    | 0.70                                            | 0.70              | 0.65                              |
| Positive factored<br>moment          | 0.63                          | 0.57                                    | 0.52                                            | 0.50              | 0.35                              |
| Exterior negative<br>factored moment | 0                             | 0.16                                    | 0.26                                            | 0.30              | 0.65                              |

![](_page_527_Figure_2.jpeg)

**FI GU RE 16.10** Sample moments for a flat plate with no edge beams.

The next problem is to estimate what proportion of these moments is taken by the column strips and what proportion is taken by the middle strips. For this discussion, a flat-plate structure is assumed, and the moment resisted by the column strip is estimated by considering the tributary areas shown in Figure 16.11.

To simplify the mathematics, the load to be supported is assumed to fall within the dashed lines shown in either part (a) or (b) of Figure 16.12. The corresponding load is placed on the simple span, and its centerline moment is determined as an estimate of the portion of the static moment taken by the column strip.2

In Figure 16.12(a), the load is spread uniformly over a length near the midspan of the beam, thus causing the moment to be overestimated a little, while in Figure 16.12(b), the load is spread uniformly from end to end, causing the moment to be underestimated. Based on these approximations, the estimated moments in the column strips for square panels will vary from

<sup>2</sup> White, R. N., Gergely, P., and Sexsmith, R. G., 1974, *Structural Engineering*, Vol. 3: *Behavior of Members and Systems* (Hoboken, NJ: John Wiley & Sons), pp. 456–461.

![](_page_528_Figure_2.jpeg)

FIGURE 16.11 Tributary areas for a flat plate.

![](_page_528_Figure_4.jpeg)

FIGURE 16.12 Load distribution.

|                                            | ·   | · · |     |
|--------------------------------------------|-----|-----|-----|
| $\frac{\ell_2}{\ell_1}$                    | 0.5 | 1.0 | 2.0 |
| $\frac{\alpha_{f1}\ell_2}{\ell_1}=0$       | 75  | 75  | 75  |
| $\frac{\alpha_{f1}\ell_2}{\ell_1} \ge 1.0$ | 90  | 75  | 45  |

**TABLE 16.3** Percentages of Interior Negative Design Moments to Be Resisted by Column Strip

 $0.5M_o$  to  $0.75M_o$ , where  $M_o$  equals the absolute sum of the positive and average negative factored moments in each direction equals  $q_u \ell_2 \ell_n^2 / 8$ . As  $\ell_1$  becomes larger than  $\ell_2$ , the column strip takes a larger proportion of the moment. For such cases, about 60% to 70% of  $M_o$  will be resisted by the column strip.

If you sketch in the approximate deflected shape of a panel, you will see that a larger portion of the positive moment is carried by the middle strip than by the column strip, and vice versa for the negative moments. As a result, about 60% of the positive  $M_o$  and about 70% of the negative  $M_o$  are expected to be resisted by the column strip.<sup>3</sup>

Section 13.6.4.1 of the code states that the column strip shall be proportioned to resist the percentages of the total interior negative design moment given in Table 16.3.

In the table,  $\alpha_1$  is again the ratio of the stiffness of a beam section to the stiffness of a width of slab bounded laterally by the centerline of the adjacent panel, if any, on each side of the beam and equals  $E_{ch}I_h/E_{cs}I_s$ .

Section 13.6.4.2 of the code states that the column strip is to be assumed to resist percentages of the exterior negative design moment, as given in Table 16.4. In this table,  $\beta_{\ell}$  is the ratio of the torsional stiffness of an edge beam section to the flexural stiffness of a width of slab equal to the span length of the beam center to center of supports  $(\beta_t = E_{cb} C/2E_{cs} I_s)$ . The computation of the cross-sectional constant C is described in Section 16.11 of this chapter.

The column strip (Section 13.6.4.4 of the code) is to be proportioned to resist the portion of the positive moments given in Table 16.5.

Equations can be used instead of the two-way interpolation sometimes required by Tables 16.3, 16.4, and 16.5. Instead of Table 16.3, the percentage of interior negative moment to be resisted by the column strip  $(\%_{int col}^{-})$  can be determined by

$$\%_{\text{int col}}^{-} = 75 + 30 \left( \frac{\alpha_{f1} \ell_2}{\ell_1} \right) \left( 1 - \frac{\ell_2}{\ell_1} \right)$$

**TABLE 16.4** Percentages of Exterior Negative Design Moment to Be Resisted by Column Strip

| $\frac{\ell_2}{\ell_1}$                    |                   | 0.5 | 1.0 | 2.0 |
|--------------------------------------------|-------------------|-----|-----|-----|
| $\alpha_{i1}l_{2}$                         | $\beta_t = 0$     | 100 | 100 | 100 |
| $\frac{\alpha_{f1}\ell_2}{\ell_1} = 0$     | $\beta_t \ge 2.5$ | 75  | 75  | 75  |
| $\frac{\alpha_{f1}\ell_2}{\ell_1} \ge 1.0$ | $\beta_t = 0$     | 100 | 100 | 100 |
|                                            | $\beta_t \ge 2.5$ | 90  | 75  | 75  |

<sup>&</sup>lt;sup>3</sup> Ibid.

 $\frac{\ell_2}{\ell_1} \qquad 0.5 \qquad 1.0 \qquad 2.0$   $\frac{\alpha_{f1}\ell_2}{\ell_1} = 0 \qquad 60 \qquad 60$   $\frac{\alpha_{f1}\ell_2}{\ell_1} \ge 1.0 \qquad 90 \qquad 75 \qquad 45$ 

**TABLE 16.5** Percentages of Positive Design Moment to Be Resisted by Column Strip

The percentage of exterior negative design moment resisted by the column ( $\%_{\text{ext col}}^-$ ) strip given in Table 16.4 can be found by

$$%_{\text{ext col}}^{-} = 100 - 10\beta_t + 12\left(\frac{\alpha_{f1}\ell_2}{\ell_1}\right)\left(1 - \frac{\ell_2}{\ell_1}\right)$$

Finally, for positive design moment in either an interior or exterior span (Table 16.5), the percentage resisted by the column strip (%<sup>+</sup>) is

$$\%^{+} = 60 + 30 \left( \frac{\alpha_{f1} \ell_2}{\ell_1} \right) \left( 1.5 - \frac{\ell_2}{\ell_1} \right)$$

In the preceding three equations, if  $\beta_t > 2.5$ , use 2.5, and if  $\alpha_{f1} \ell_2 / \ell_1 > 1$ , use 1.

In Section 13.6.5, the code requires that the beam be allotted 85% of the column strip moment if  $\alpha_{f1}(\ell_2/\ell_1) \ge 1.0$ . Should  $\alpha_{f1}(\ell_2/\ell_1)$  be between 1.0 and 0, the moment allotted to the beam is determined by linear interpolation from 85% to 0%. The part of the moment not given to the beam is allotted to the slab in the column strip.

Finally, the code (13.6.6) requires that the portion of the design moments not resisted by the column strips, as previously described, is to be allotted to the corresponding half middle strip. The middle strip will be designed to resist the total of the moments assigned to its two half middle strips.

### 16.9 Design of an Interior Flat Plate

In this section, an interior flat plate is designed by the direct design method. The procedure specified in Chapter 13 of the ACI Code is applicable not only to flat plates but also to flat slabs, waffle slabs, and two-way slabs with beams. The steps necessary to perform the designs are briefly summarized at the end of this paragraph. The order of the steps may have to be varied somewhat for different types of slab designs. Either the direct design method or the equivalent frame method may be used to determine the design moments. The design steps are as follows:

- **1.** Estimate the slab thickness to meet the code requirements.
- **2.** Determine the depth required for shear.
- 3. Calculate the total static moments to be resisted in the two directions.
- **4.** Estimate the percentages of the static moments that are positive and negative, and proportion the resulting values between the column and middle strips.
- **5.** Select the reinforcing

Example 16.3 illustrates this method of design applied to a flat plate.

#### Example 16.3

Design an interior flat plate for the structure considered in Example 16.1. This plate is shown in Figure 16.13. Assume a service live load equal to 80 psf, a service dead load equal to 110 psf (including slab weight),  $f_v = 60,000$  psi,  $f_c' = 3000$  psi, normal-weight concrete, and column heights of 12 ft.

#### SOLUTION

#### **Estimate Slab Thickness**

When shear is checked, the 7-in. slab estimated in Example 16.1 is not quite sufficient. One alternative is to increase  $f'_c$  from 3000 psi, which is a fairly low strength. However, we will increase the slab thickness. The calculations for the 7-in. thick slab are the same as those that follow for the 7.5-in. slab thickness with the exception of the slab thickness change.

 $\therefore$  Try  $7\frac{1}{2}$ -in. slab

#### **Determine Depth Required for Shear**

Using d for shear equal to the estimated average of the d values in the two directions, we obtain

$$d = 7.50 \text{ in.} - \frac{3 \text{ in.}}{4} \text{ cover} - 0.50 \text{ in.} = 6.25 \text{ in.}$$

$$q_u = (1.2)(110 \text{ psf}) + (1.6)(80 \text{ psf}) = 260 \text{ psf}$$

#### Checking One-Way or Beam Shear (Seldom Controls in Two-Way Floor Systems)

Using the dimensions shown in Figure 16.14, we obtain

$$V_{u1}=$$
 (8.81 ft) (260 psf) = 2291 lb for a 12 in. width  $\phi V_c=\phi 2\lambda \sqrt{f_c'}bd$  = (0.75) (1.0) (2 $\sqrt{3000}$  psi) (12 in.) (6.25 in.) = 6162 lb > 2291 lb OK

![](_page_531_Figure_15.jpeg)

FIGURE 16.13 Interior panel of flat-plate structure of Example 16.1.

![](_page_532_Figure_2.jpeg)

**FIGURE 16.14** Dimensions for Example 16.3.

#### Checking Two-Way or Punching Shear around the Column

$$\begin{split} b_o &= (2) \, (16 \text{ in.} + 6.25 \text{ in.}) + (2) \, (12 \text{ in.} + 6.25 \text{ in.}) = 81 \text{ in.} \\ V_{u2} &= \left[ (20 \text{ ft}) \, (16 \text{ ft}) - \left( \frac{16 \text{ in.} + 6.25 \text{ in.}}{12 \text{ in/ft}} \right) \left( \frac{12 \text{ in.} + 6.25 \text{ in.}}{12 \text{ in/ft}} \right) \right] \, (0.260 \text{ ksf}) \\ &= 82.47 \text{ k} = 82,470 \text{ lb} \\ \phi V_c &= (0.75) \, (1.0) \, (4 \sqrt{3000} \text{ psi}) \, (81 \text{ in.}) \, (6.25 \text{ in.}) \\ &= 83,185 \text{ lb} > 82,470 \text{ lb} \quad \text{OK} \end{split}$$

Use 
$$h = 7\frac{1}{2}$$
 in.

#### Calculate Static Moments in the Long and Short Directions

$$M_{o\ell} = \frac{q_u \ell_2 \ell_n^2}{8} = \frac{(0.260 \text{ ksf}) (16 \text{ ft}) (20 \text{ ft} - \frac{16}{12} \text{ ft})^2}{8} = 181.2 \text{ ft-k}$$

$$M_{os} = \frac{q_u \ell_1 \ell_n^2}{8} = \frac{(0.260 \text{ ksf}) (20 \text{ ft}) (16 \text{ ft} - \frac{12}{12} \text{ ft})^2}{8} = 146.2 \text{ ft-k}$$
(ACI Equation 13-4)

#### Proportion the Static Moments to the Column and Middle Strips and Select the Reinforcing

The static moment is divided into positive and negative moments in accordance with ACI 13.6.2. Since this is an interior span, 65% of the total static moment is negative and 35% is positive. See also the right side of Figure 16.10(c). If this example were an end span, then the total static moment would be divided into positive and negative values in accordance with Table 16.2.

The next step is to divide the moments determined in the previous paragraph into column and middle strips. Again, since this is an interior span, Table 16.3 applies. Since  $\alpha_{f1}=0$  (no interior beams), 75% of the moment goes to the column strip. This value is independent of  $\ell_2/\ell_1$  for the case where there are no interior beams. The remaining 25% of the moment is assigned to the middle strip, half on each side of the column strip. Table 16.5 is used to determine how much of the total positive moment is assigned to the column strip. In this case, since  $\alpha_{f1}=0$ , 60% goes to the column strip, and the remaining 40% is assigned to the middle strip, half on each side of the column strip.

These calculations can be conveniently arranged, as in Table 16.6. This table is very similar to the one used for the design of the continuous one-way slab in Chapter 14. To assist in the interpretation of Table 16.6, the numbers in the first column will be discussed. The first is the determination of  $M_u$ . This calculation uses the 0.65 factor from ACI 13.6.3.2 and the 0.75 factor from Table 16.3, both applied to the total static moment of 181.2 ft-k. Dividing this value of  $M_u = -88.4$  ft-k by  $\phi b d^2$  ( $\phi = 0.9$ , b = 8 ft = 96 in., d = 6.5 in.)

|                          | Long Span (estimate $d = 6.50$ in.) |                       |                       |                           |                       | Short Span (e         | stimate $d = 6.00$ in. | )                     |
|--------------------------|-------------------------------------|-----------------------|-----------------------|---------------------------|-----------------------|-----------------------|------------------------|-----------------------|
|                          | Column Strip (8 ft) Middl           |                       | Middle S              | lle Strip (8 ft) Column S |                       | Strip (8 ft)          | Middle Strip (12 ft)   |                       |
|                          | _                                   | +                     | _                     | +                         | _                     | +                     | _                      | +                     |
| $M_u$                    | (0.65)(0.75)                        | (0.35)(0.60)          | (0.65)(181.2 ft-k)    | (0.35)(181.2 ft-k)        | (0.65)(0.75)          | (0.35)(0.60)          | (0.65)(146.2 ft-k)     | (0.35)(146.2ft-k)     |
|                          | (181.2 ft-k)                        | (181.2 ft-k)          | -88.4 ft-k            | −38.1 ft-k                | (146.2 ft-k)          | (146.2 ft-k)          | −71.3 ft-k             | -30.7 ft-k            |
|                          | = -88.4  ft-k                       | = +38.1 ft-k          | = -29.4  ft-k         | = +25.3 ft-k              | = -71.3  ft-k         | = +30.7 ft-k          | = -23.8  ft-k          | = +20.5 ft-k          |
| $\frac{M_u}{\phi b d^2}$ | 290.6 psi                           | 125.2 psi             | 97.6 psi              | 83.2 psi                  | 275.1 psi             | 118.4 psi             | 61.2 psi               | 52.7 psi              |
| ho *                     | 0.00516bd                           | 0.00214bd             | 0.0018 <i>bh</i>      | 0.0018 <i>bh</i>          | 0.00486bd             | 0.00202bd             | 0.0018 <i>bh</i>       | 0.0018 <i>bh</i>      |
| $A_s$                    | 3.22 in. <sup>2</sup>               | 13.4 in. <sup>2</sup> | 1.30 in. <sup>2</sup> | 1.30 in. <sup>2</sup>     | 2.80 in. <sup>2</sup> | 1.16 in. <sup>2</sup> | 1.94 in. <sup>2</sup>  | 1.94 in. <sup>2</sup> |
| Bars                     |                                     |                       |                       |                           |                       |                       |                        |                       |
| selected                 | 17 #4                               | 7 #4                  | 7 #4                  | 7 #4                      | 15 #4                 | 6 #4                  | 10 #4                  | 10 #4                 |

**TABLE 16.6** Summary of Moments and Steel Selections for Example 16.3

results in  $M_u/\phi bd^2 = 290.6$  psi. From Appendix A, Table A.12,  $\rho = 0.00516$  (by interpolation). The area of reinforcing steel in the column strip is  $A_s = \rho bd = 0.00516(96 \text{ in.})(6.5 \text{ in.}) = 3.22 \text{ in.}^2$ . A bar selection of 17 #4 bars is chosen, having a total  $A_s = 3.34$  in.<sup>2</sup>. The remaining entries in Table 16.6 follow a similar procedure.

As the different percentages of moments are selected from the tables for the column and middle strips of this slab, it will be noted that  $\alpha_f = 0$ .

In the solution to Example 16.3, it will be noted that the  $M_u/\phi b d^2$  values are sometimes quite small, and thus most of the  $\rho$  values do not fall within Table A.12 (see Appendix A). For such cases, the authors use the temperature and shrinkage minimum 0.0018bh.

Actually, the temperature reinforcing includes bars in the top and bottom of the slab. In the negative moment region, some of the positive steel bars have been extended into the support region and are also available for temperature and shrinkage steel. If desirable, these positive bars can be lapped instead of being stopped in the support.

The selection of the reinforcing bars is the final step taken in the design of this flat plate. The code Figure 13.3.8 (given as Figure 16.15 here) shows the minimum lengths of slab reinforcing bars for flat plates and for flat slabs with drop panels. This figure shows that some of the positive reinforcing must be run into the support area.

The bars selected for this flat plate are shown in Figure 16.16. Bent bars are used in this example, but straight bars could have been used just as well. There seems to be a trend among designers in the direction of using more straight bars in slabs and fewer bent bars.

#### 16.10 Placing of Live Loads

The moments in a continuous floor slab are appreciably affected by different positions or patterns of the live loads. The usual procedure, however, is to calculate the total static moments, assuming that all panels are subjected to full live load. When different loading patterns are used, the moments can be changed so much that overstressing may occur in the slab.

Section 13.7.6.2 of the code states that if a variable unfactored live load does not exceed three-fourths of the unfactored dead load, or if it is of a type such that all panels will be loaded simultaneously, it is permissible to assume that full live load placed over the entire area will cause maximum moment values throughout the entire slab system.

For other loading conditions, it may be assumed (according to ACI Section 13.7.6.3) that maximum positive moment at the midspan of a panel will occur when three-fourths of the full factored live load is placed on the panel in question and on alternate spans. It may be further

<sup>\*</sup>Values may not be less than the temperature and shrinkage minimum 0.0018bh.

![](_page_534_Figure_2.jpeg)

FIGURE 16.15 Minimum extensions for reinforcement in slabs without beams (see ACI Section 12.11.1 for reinforcement extension into supports).

![](_page_535_Figure_2.jpeg)

**FI GU RE 16.16** Bar details.

assumed that the maximum negative moment at a support will occur when three-fourths of the full factored live load is placed only on the adjacent spans.

The code permits the use of the three-fourths factor because the absolute maximum positive and negative moments cannot occur simultaneously under a single loading condition and also because some redistribution of moments is possible before failure will occur. Although some local overstress may be the result of this procedure, it is felt that the ultimate capacity of the system after redistribution will be sufficient to resist the full factored dead and live loads in every panel.

The moment determined as described in the last paragraph may not be less than moments obtained when full factored live loads are placed in every panel (ACI 13.7.6.4).

### **16.11 Analysis of Two-Way Slabs with Beams**

In this section, the moments are determined by the direct design method for an exterior panel of a two-way slab with beams. The example problem presented in this section is about as complex as any that may arise in flat plates, flat slabs, or two-way slabs with beams, using the direct design method.

The requirements of the code are so lengthy and complex that in Example 16.4, which follows, the steps and appropriate code sections are spelled out in detail. The practicing designer should obtain a copy of the *CRSI Design Handbook*, because the tables therein will be of tremendous help in slab design.

#### Example 16.4

Determine the negative and positive moments required for the design of the exterior panel of the two-way slab with beam structure shown in Figure 16.17. The slab is to support a live load of 120 psf and a dead load of 100 psf, including the slab weight. The columns are 15 in. × 15 in. and 12 ft long. The slab is supported by beams along the column line with the cross section shown. Determine the slab thickness and check the shear stress if *f <sup>c</sup>* = 3000 psi and *fy* = 60,000 psi.

#### **SOLUTION**

**1.** Check ACI Code limitations (13.6.1). These conditions, which are discussed in Section 16.7 of this text, are met. The first five of these criteria are easily satisfied by inspection. The sixth requires calculations that follow.

![](_page_536_Figure_9.jpeg)

**FI GU RE 16.17** Two-way slab for Example 16.4.

- 2. Minimum thickness as required by code (9.5.3)
  - (a) Assume h = 6 in.
  - (b) Effective flange projection of column line beam as specified by the code (13.2.4)

$$=4h_f=(4)$$
 (6 in.) = 24 in. or  $h-h_f=20$  in.  $-6$  in.  $=14$  in.

(c) Gross moments of inertia of T beams. The following values are the gross moments of inertia of the edge and interior beams computed, respectively, about their centroidal axes. Many designers use approximate values for these moments of inertia,  $I_s$ , with almost identical results for slab thicknesses. One common practice is to use two times the gross moment of inertia of the stem (using a depth of stem running from top of slab to bottom of stem) for interior beams and one and a half times the stem gross moment of inertia for edge beams.

(d) Calculating  $\alpha$  values (where  $\alpha$  is the ratio of the stiffness of the beam section to the stiffness of a width of slab bounded laterally by the centerline of the adjacent panel, if any, on each side of the beam).

For edge beam 
$$\left(\text{width} = \frac{1}{2} \times 22 \text{ ft} + \frac{7.5 \text{ in.}}{12 \text{ in/ft}} = 11.625 \text{ ft}\right)$$

$$I_s = \left(\frac{1}{12}\right) (12 \text{ in/ft} \times 11.625 \text{ ft}) (6 \text{ in.})^3 = 2511 \text{ in.}^4$$

$$\alpha_f = \frac{13,468 \text{ in.}^4}{2511 \text{ in.}^4} = 5.36$$

For 18-ft interior beam (with 22-ft slab width)

$$I_s = \left(\frac{1}{12}\right) (12 \text{ in/ft} \times 22 \text{ ft}) (6 \text{ in.})^3 = 4752 \text{ in.}^4$$

$$\alpha_f = \frac{15,781 \text{ in.}^4}{4752 \text{ in.}^4} = 3.32$$

For 22-ft interior beam (with 18-ft slab width)

$$I_{s} = \left(\frac{1}{12}\right) (12 \text{ in/ft} \times 18 \text{ ft}) (6 \text{ in.})^{3} = 3888 \text{ in.}^{4}$$

$$\alpha_{f} = \frac{15,781 \text{ in.}^{4}}{3888 \text{ in.}^{4}} = 4.06$$
Avg.  $\alpha_{f} = \alpha_{fm} = \frac{5.36 + 3.32 + (2) (4.06)}{4} = 4.20$ 

$$\beta = \text{ratio of long to short clear span} = \frac{22 \text{ ft} - \frac{15 \text{ in.}}{12 \text{ in/ft}}}{18 \text{ ft} - \frac{15 \text{ in.}}{12 \text{ in/ft}}} = 1.24$$

(e) Now that we have determined the values of  $\alpha_f$  in the two perpendicular directions, the sixth and final limitation for use of the direct design method (ACI 13.6.1.6) can be checked.

$$\frac{\alpha_{f1}\ell_2^2}{\alpha_{f2}\ell_1^2} = \frac{4.06(18 \text{ ft})^2}{3.32(22 \text{ ft})^2} = 0.818$$

Since this value is between 0.2 and 5.0, this condition is satisfied. Note that the directions that are designated as  $\ell_1$  and  $\ell_2$  are arbitrary. Had the short direction been used as  $\ell_1$ , the preceding calculation would simply have been inverted, and the ratio would have been 1.22 instead of 0.818. This value would also have been between the limits of 0.2 and 5.0.

(f) Thickness limits by ACI Section 9.5.3

$$\ell_n = 22.0 \text{ ft} - \frac{15 \text{ in.}}{12 \text{ in/ft}} = 20.75 \text{ ft}$$

As  $\alpha_{fm} > 2.0$ , use ACI Equation 9-13

$$h = \frac{\ell_n \left( 0.8 + \frac{f_y}{200,000} \right)}{36 + 9\beta}$$

$$= \frac{(12 \text{ in/ft}) (20.75 \text{ ft}) \left( 0.8 + \frac{60,000 \text{ psi}}{200,000 \text{ psi}} \right)}{36 + (9) (1.24)} = 5.81 \text{ in.} \leftarrow$$

h not less than 3.5 in. as per ACI Section 9.5.3.3(c)

Try h = 6 in. (shear checked later)

3. Moments for the short-span direction centered on interior column line

$$q_u = (1.2)(100 \text{ psf}) + (1.6)(120 \text{ psf}) = 312 \text{ psf}$$
  
 $M_o = \frac{(q_u \ell_2)(\ell_n)^2}{8} = \frac{(0.312 \text{ ksf})(22 \text{ ft})(16.75 \text{ ft})^2}{8} = 241 \text{ ft-k}$ 

(a) Dividing this static design moment into negative and positive portions, per Section 13.6.3.2 of the code

Negative design moment = 
$$(0.65)(241 \text{ ft-k}) = -157 \text{ ft-k}$$
  
Positive design moment =  $(0.35)(241 \text{ ft-k}) = +84 \text{ ft-k}$ 

(b) Allotting these interior moments to beam and column strips, per Section 13.6.4 of the code

$$\frac{\ell_2}{\ell_1} = \frac{22 \text{ ft}}{18 \text{ ft}} = 1.22$$

 $\alpha_{f1} = \alpha_f$  in direction of short span = 3.32

$$\alpha_{f1} \frac{\ell_2}{\ell_1} = (3.32)(1.22) = 4.05$$

The portion of the interior negative moment to be resisted by the column strip, per Table 16.3 of this chapter, by interpolation is (0.68)(-157) = -107 ft-k. This result can also be obtained from the equation

$$\%_{\rm intcol}^{-} = 75 + 30 \ \left(\frac{\alpha_{\rm f1}\ell_2}{\ell_1}\right) \left(1 - \frac{\ell_2}{\ell_1}\right) = 75 + 30(1) \left(1 - \frac{22 \ \rm ft}{18 \ \rm ft}\right) = 68.3\%$$
 
$$M_{\rm int\ col}^{-} = 0.683(157 \ \rm ft-k) = 107 \ \rm ft-k$$

Note that since  $\alpha_{f1}\ell_2/\ell_1=4.05>1$ , a value of 1 was used in the preceding equation.

This -107 ft-k is allotted 85% to the beam (ACI 13.6.5), or -91 ft-k, and 15% to the slab, or -16 ft-k. The remaining negative moment, 157 ft-k - 107 ft-k = 50 ft-k, is allotted to the middle strip.

The portion of the interior positive moment to be resisted by the column strip, per Table 16.5 of this chapter, by interpolation is (0.68)(+84 ft-k) = +57 ft-k. The 68% value can also be obtained from the equation for Table 16.5. This 57 ft-k is allotted 85% to the beam (ACI 13.6.5), or +48 ft-k, and 15% to the slab, or +9 ft-k. The remaining positive moment, 84 ft-k - 57 ft-k = 27 ft-k, goes to the middle strip.

4. Moments for the short-span direction centered on the edge beam

$$M_o = \frac{(q_u \ell_2) (\ell_n)^2}{8} = \frac{(0.312 \text{ ksf}) (11.625 \text{ ft}) (16.75 \text{ ft})^2}{8} = 127 \text{ ft-k}$$

(a) Dividing this static design moment into negative and positive portions, per Section 13.6.3.2 of the code

Negative design moment = 
$$(0.65)(127 \text{ ft-k}) = -83 \text{ ft-k}$$
  
Positive design moment =  $(0.35)(127 \text{ ft-k}) = +44 \text{ ft-k}$ 

(b) Allotting these exterior moments to beam and column strips, per Section 13.6.4 of the code

$$\frac{\ell_2}{\ell_1} = \frac{22 \text{ ft}}{18 \text{ ft}} = 1.22$$

$$\alpha_{f1} = \alpha_{f1} \text{ for edge beam} = 5.36$$

$$\alpha_{f1} \frac{\ell_2}{\ell_1} = (5.36)(1.22) = 6.54$$

5. The portion of the exterior negative moment going to the column strip, from Table 16.4 of this chapter, by interpolation is (0.68)(-83 ft-k) = -56 ft-k. This -56 ft-k is allotted 85% to the beam (ACI 13.6.5), or -48 ft-k, and 15% to the slab, or -8 ft-k. The remaining negative moment, 83 ft-k - 56 ft-k = -27 ft-k, is allotted to the middle strip.

The portion of the exterior positive moment to be resisted by the column strip, per Table 16.5 or the equation for Table 16.5, is (0.68)(+44 ft-k) = +30 ft-k. This 30 ft-k is allotted 85% to the beam, or +26 ft-k, and 15% to the slab, or +5 ft-k. The remaining positive moment, 44 ft-k - 30 ft-k = +14 ft-k, goes to the middle strip.

A summary of the short-span moments is presented in Table 16.7.

6. Moments for the long-span direction

$$M_o = \frac{(q_u \ell_2) (\ell_n)^2}{8} = \frac{(0.312 \text{ ksf}) (18 \text{ ft}) (20.75 \text{ ft})^2}{8} = 302.3 \text{ ft-k}$$

(a) From Table 16.2 of this chapter (ACI 13.6.3.3) for an end span with beams between all interior supports:

Interior negative factored moment =  $0.70M_o = -(0.70)$  (302.3 ft-k) = -212 ft-k Positive factored moment =  $0.57M_0 = +(0.57)(302.3 \text{ ft-k}) = 172 \text{ ft-k}$ Exterior negative factored moment =  $0.16M_o = -(0.16)(302.3 \text{ ft-k}) = -48 \text{ ft-k}$ 

These factored moments may be modified by 10%, according to Section 13.6.7 of the code, but this reduction is neglected here.

(b) Allotting these moments to beam and column strips

$$\frac{\ell_2}{\ell_1} = \frac{18 \text{ ft}}{22 \text{ ft}} = 0.818$$

$$\alpha_{f1} = \alpha_{f1} \text{ (for the 22-ft beam)} = 4.06$$

$$\alpha_{f1} \frac{\ell_2}{\ell_1} = (4.08)(0.818) = 3.32$$

|                          | Column St | rip Moments | Middle Strip |  |
|--------------------------|-----------|-------------|--------------|--|
|                          | Beam Slab |             | Slab Moments |  |
| Interior slab-beam strip |           |             |              |  |
| Negative                 | -91       | -16         | -50          |  |
| Positive                 | +48       | +9          | +30          |  |
| Exterior slab-beam strip |           |             |              |  |
| Negative                 | -48       | -9          | -27          |  |
| Positive                 | +26       | +5          | +16          |  |

TABLE 16.7 Short-Span Moments (ft-k)

Next an expression is given for  $\beta_t$ . It is the ratio of the torsional stiffness of an edge beam section to the flexural stiffness of a width of slab equal to the span length of the beam measured center to center of supports.

$$\beta_t = \frac{E_{cb}C}{2E_{cs}I_s}$$

Involved in the equation is a term *C*, which is a property of the cross-sectional area of the torsion arm estimating the resistance to twist.

$$C = \Sigma \left( 1 - 0.63 \frac{x}{y} \right) \frac{x^3 y}{3}$$

where x is the length of the short side of each rectangle and y is the length of the long side of each rectangle. The exterior beam considered here is described in ACI Section 13.2.4 and is shown in Figure 16.18, together with the calculation of C. The beam cross section could be divided into rectangles in other ways, but the configuration shown results in the greatest value for C.

$$\beta_t = \frac{E_{cb}C}{2E_{cs}I_s} = \frac{(E_c)(12,605 \text{ in.}^4)}{(2)(E_c)(3888 \text{ in.}^4)} = 1.62$$

The portion of the interior negative design moment allotted to the column strip, from Table 16.3, by interpolation or by equation is (0.80)(-212 ft-k) = -170 ft-k. This -170 ft-k is allotted 85% to the beam (ACI 13.6.5), or -145 ft-k, and 15% to the slab, or -26 ft-k. The remaining negative moment, -212 ft-k + 170 ft-k = -42 ft-k, is allotted to the middle strip.

The portion of the positive design moment to be resisted by the column strip, per Table 16.5, is (0.80)(172 ft-k) = +138 ft-k. This 138 ft-k is allotted 85% to the beam, or (0.85)(138 ft-k) = 177 ft-k, and 15% to the slab, or +21 ft-k. The remaining positive moment, 172 ft-k - 138 ft-k = 34 ft-k, goes to the middle strip.

![](_page_540_Figure_12.jpeg)

**FIGURE 16.18** Evaluation of C.

|                   | Column | Strip Moments | Middle Strip |
|-------------------|--------|---------------|--------------|
|                   | Beam   | Slab          | Slab Moments |
| Interior negative | -145   | -26           | -42          |
| Positive          | +117   | +21           | +34          |
| Exterior negative | -36    | -6            | -6           |

TABLE 16.8 Long-Span Moments (ft-k)

![](_page_541_Figure_4.jpeg)

FIGURE 16.19 Load distribution to beams.

The portion of the exterior negative moment allotted to the column strip is obtained by double interpolation from Table 16.4 and is (0.86)(-48 ft-k) = -42 ft-k. This -42 ft-k is allotted 85% to the beam, or -36 ft-k, and 15% to the slab, or -6 ft-k. The remaining negative moment, -6 ft-k, is allotted to the middle strip.

A summary of the long-span moments is presented in Table 16.8.

7. Check shear strength in the slab at a distance d from the face of the beam. Shear is assumed to be produced by the load on the tributary area shown in Figure 16.19, working with a 12-in.-wide strip as shown.

average 
$$d=h-{\rm cover}-{\rm one}$$
 bar diam.  $=6.00$  in.  $-\frac{3}{4}$  in.  $-\frac{1}{2}$  in.  $=4.75$  in. 
$$V_u=(0.312~{\rm ksf})\left(9~{\rm ft}-\frac{7.5~{\rm in.}}{12~{\rm in/ft}}-\frac{4.75~{\rm in.}}{12~{\rm in/ft}}\right)=2.49~{\rm k}=2490~{\rm lb}$$
 
$$\phi V_c=(0.75)\,(1.0)\,(2\sqrt{3000}~{\rm psi})\,(12~{\rm in.})\,(4.75~{\rm in.})=4684~{\rm lb}>2490~{\rm lb}$$
 OK

### **Transfer of Moments and Shears between** Slabs and Columns

On many occasions, the maximum load that a two-way slab can support is dependent upon the strength of the joint between the column and the slab. Not only is the load transferred by shear from the slab to the column along an area around the column, but also there may be moments that have to be transferred. The moment situation is usually most critical at the exterior columns.

If there are moments to be transferred, they will cause shear stresses of their own in the slabs, as will be described in this section. Furthermore, shear forces resulting from moment transfer must be considered in the design of the lateral column reinforcement (i.e., ties and spirals), as stated in Section 11.10.1 of the code.

When columns are supporting slabs without beams (i.e., flat plates or flat slabs), the load transfer situation between the slabs and columns is extremely critical. If we don't have

the exact areas and positions of the flexural reinforcing designed just right throughout the slab, inelastic redistribution of moments (ACI 13.6.7) may still allow the system to perform adequately; however, if we handle the shear strength situation incorrectly, the results may very well be disastrous.

The serious nature of this problem is shown in Figure 16.20, where it can be seen that if there is no spandrel beam, all of the total exterior slab moment has to be transferred to the column. The transfer is made by both flexure and eccentric shear, the latter being located at a distance of about d/2 from the column face.

Section 13.6.3.6 of the code states that for moment transfer between the slab and edge column, the gravity load moment to be transferred shall be  $0.3M_o$  (where  $M_o$  is the factored statical moment).

When gravity loads, wind or earthquake loads, or other lateral forces cause a transfer of an unbalanced moment between a slab and a column, a part of the moment equal to  $\gamma_f M_u$  shall be transferred by flexure, according to ACI Section 13.5.3.2. Based on both tests and experience, this transfer is to be considered to be made within an effective slab width between lines that are located one and a half times the slab or drop panel thickness outside opposite faces of the column or capital. The value  $\gamma_f$  is to be taken as

$$\gamma_f = \frac{1}{1 + \frac{2}{3}\sqrt{\frac{b_1}{b_2}}}$$
 (ACI Equation 13-1)

In Figure 16.21,  $b_1$  is the length of the shear perimeter, which is perpendicular to the axis of bending  $(c_1 + d)$ , and  $b_2$  is the length of the shear perimeter parallel to the axis of bending  $(c_2 + d)$ . Also,  $c_1$  is the width of the column perpendicular to the axis of bending, while  $c_2$  is the column width parallel to the axis of bending.

The remainder of the unbalanced moment, referred to as  $\gamma_{\nu}M_{u}$  by the code, is to be transferred by eccentricity of shear about the centroid of the critical section.

$$\gamma_v = 1 - \gamma_f$$
 (ACI Equation 11-39)

From this information, the shear stresses due to moment transfer by eccentricity of shear are assumed to vary linearly about the centroid of the critical section described in the last paragraph and are to be added to the usual factored shear forces. (In other words, there is the usual punching shear situation plus a twisting because of the moment transfer that increases the shear.) The resulting shear stresses may not exceed  $\phi V_n = \phi V_c/b_o d$  for members without

![](_page_542_Picture_11.jpeg)

**FIGURE 16.20** Illustration showing need for transfer of moments to columns.

![](_page_543_Picture_2.jpeg)

(a) Interior column

![](_page_543_Picture_4.jpeg)

(b) Edge column

FIGURE 16.21 Assumed distribution of shear stress (ACI Figure R11.11.7.2).

shear reinforcement, and  $\phi V_n = \phi (V_c + V_s)/b_o d$  for members with shear reinforcement other than shear heads.  $V_c$  in the two previous equations is the lesser of ACI Equations 11-33, 11-34, or 11-35 (Section 12.6 of this text).

The combined stresses are calculated by the expressions to follow, with reference being made to Figure 16.21 and ACI Commentary R11.11.7.2:

$$v_u$$
 along  $AB = \frac{V_u}{A_c} + \frac{\gamma_v M_u c_{AB}}{J_c}$   
 $v_u$  along  $CD = \frac{V_u}{A_c} - \frac{\gamma_v M_u c_{CD}}{J_c}$ 

In these expressions,  $A_c$  is the area of the concrete along the assumed critical section. For instance, for the interior column of Figure 16.21(a), it would be equal to (2a + 2b)d, and for the edge column of Figure 16.21(b), it would equal (2a + b)d.

 $J_c$  is a property analogous to the polar moment of inertia about the z-z axis of the shear areas located around the periphery of the critical section. First, the centroid of the shear area  $A_f$  is located by taking moments. The centroid is shown with the distances  $c_{AB}$  and  $c_{CD}$  in both parts (a) and (b) of Figure 16.21. The value of  $J_c$  is then computed for the shear areas. For the interior column of part (a), it is

$$J_c = d\left(\frac{a^3}{6} + \frac{ba^2}{2}\right) + \frac{ad^3}{6}$$

and for the edge column of part (b), it is

$$J_c = d \left[ \frac{2a^3}{3} - (2a + b) (c_{AB})^2 \right] + \frac{ad^3}{6}$$

Example 16.5 shows the calculations involved for shear and moment transfer for an exterior column.

The commentary (R11.11.7.3) states that the critical section described for two-way action for slabs located at d/2 from the perimeter of the column is appropriate for the calculation of shear stresses caused by moment transfer even when shearheads are used. Thus, the critical sections for direct shear and shear resulting from moment transfer will be different from each other.

The total reinforcing that will be provided in the column strip must include additional reinforcing concentrated over the column to resist the part of the bending moment transferred by flexure =  $\gamma_f M_u$ .

#### Example 16.5

For the flat slab of Figure 16.22, compute the negative steel required in the column strip for the exterior edge indicated. Also check the slab for moment and shear transfer at the exterior column;  $f'_c = 3000$  psi,  $f_y = 60,000$  psi, and LL = 100 psf. An 8-in. slab has already been selected with d = 6.75 in.

#### SOLUTION

**1.** Compute  $w_u$  and  $M_{ol}$ .

$$w_d = \left(\frac{8 \text{ in.}}{12 \text{ in/ft}}\right) (150 \text{ pcf}) = 100 \text{ psf}$$

$$w_\ell = 100 \text{ psf}$$

$$w_u = (1.2) (100 \text{ psf}) + (1.6) (100 \text{ psf}) = 280 \text{ psf}$$

$$M_{o\ell} = \frac{q_u \ell_2 \ell_n^2}{8} = \frac{(0.280 \text{ ksf}) (18 \text{ ft}) (18.75 \text{ ft})^2}{8} = 221.5 \text{ ft-k}$$

![](_page_544_Figure_10.jpeg)

**FIGURE 16.22** Dimensions of flat slab in Example 16.5.

2. Determine the exterior negative moment as per ACI Section 13.6.3.3.

$$-0.26M_{o\ell} = -(0.26)$$
 (221.5 ft-k) = 57.6 ft-k  
Width of column strip = (0.50) (18 ft) = 9 ft - 0 in. = 108 in.

- 3. ACI Section 13.6.4.2 shows that 100% of the exterior negative moment is to be resisted by the column strip.
- 4. Design of steel in column strip.

$$\frac{M_u}{\phi b d^2} = \frac{(12 \text{ in/ft}) (57,600 \text{ ft-lb})}{(0.9) (108 \text{ in.}) (6.75 \text{ in.})^2} = 156.1 \text{ psi}$$

$$\rho = 0.0027 \text{ (from Appendix A, Table A.12)}$$

$$A_s = \rho b d = (0.0027) (108 \text{ in.}) (6.75 \text{ in.}) = 1.97 \text{ in.}^2$$
Use 10 #4

- 5. Moment transfer design.
  - (a) The code (13.5.3.2) states that additional bars must be added over the column in a width = column width +(2)(1.5h) = 15 in.  $+(2)(1.5 \times 8$  in.) = 39 in.
  - (b) The additional reinforcing needed over the columns is to be designed for a moment =  $\gamma_f M_{ii}$ . In ACI Equation 13-1 below,  $b_1$  and  $b_2$  are the side dimensions of the perimeter  $b_0$  in ACI Section 11.11.1.2 (see Figure 16.21). In this case,  $b_1 = c_1 + d/2 = 15$  in. + 6.75 in./2 = 18.375 in. In the perpendicular direction,  $b_2 = c_2 + d = 15$  in. + 6.75 in. = 21.75 in.

$$\gamma_f = \frac{1}{1 + \frac{2}{3}\sqrt{\frac{b_1}{b_2}}} = \frac{1}{1 + \frac{2}{3}\sqrt{\frac{18.375 \text{ in.}}{21.75 \text{ in.}}}} = 0.62$$
 (ACI Equation 13-1)  
$$\gamma_f M_{tt} = (0.62) (57.6 \text{ ft-k}) = 35.7 \text{ ft-k}$$

(c) Add four #4 bars in the 39 in. width and check to see whether the moment transfer situation is satisfactory. To resist the 35.7 ft-k, we now have the four #4 bars just added plus four #4. This number of bars is obtained by taking the ratio of 39 in./108 in. times 10 bars to get 3.6 bars and rounding to 4. The total number of bars put in for the column strip design is eight #4 bars (1.60 in.2).

$$\begin{split} a &= \frac{A_{s}f_{y}}{0.85f_{c}'b} = \frac{(1.57 \text{ in.}^{2}) (60 \text{ ksi})}{(0.85) (3 \text{ ksi}) (39 \text{ in.})} = 0.947 \text{ in.} \\ \phi M_{n} &= M_{u} = \phi A_{s}f_{y} \left( d - \frac{a}{2} \right) \\ &= \frac{(0.9) (1.57 \text{ in.}^{2}) (60 \text{ ksi}) \left( 6.75 \text{ in.} - \frac{0.947 \text{ in.}}{2} \right)}{12} \\ &= 44.3 \text{ ft-k} > 35.7 \text{ ft-k} \qquad \underline{OK} \end{split}$$

- 6. Compute combined shear stress at exterior column due to shear and moment transfer.
  - (a) ACI Section 13.6.3.5 requires that a moment of  $(0.3M_o)(\gamma_v)$  be transferred from the slab to the column by eccentricity of shear. The total moment to be transferred is  $0.3(M_{\odot}) = 0.3(221.5 \text{ ft-k}) = 66.45 \text{ ft-k}.$

$$a = 15 + \frac{6.75}{2} = 18.375$$
 in.
$$b = 15 + 6.75 = 21.75$$
 in.

**FIGURE 16.23** Dimensions of critical section for shear.

**(b)** Fraction of unbalanced moment carried by eccentricity of shear =  $\gamma_{\nu}$  (0.3 $M_{o}$ ).

$$\gamma_{v} = 1 - \frac{1}{1 + \frac{2}{3}\sqrt{\frac{18.375 \text{ in.}}{21.75 \text{ in.}}}} = 0.38$$

$$\gamma_{\nu}M_{p} = (0.38)(66.45 \text{ ft-k}) = 25.25 \text{ ft-k}$$

(c) Compute properties of critical section for shear (Figure 16.23).

$$A_c = (2a+b)d = (2 \times 18.375 \text{ in.} + 21.75 \text{ in.}) (6.75 \text{ in.}) = 394.875 \text{ in.}^2$$

$$c_{AB} = \frac{(2)(18.375 \text{ in.}) (6.75 \text{ in.}) \left(\frac{18.375 \text{ in.}}{2}\right)}{394.875 \text{ in.}^2} = 5.77 \text{ in.}$$

$$J_c = d \left[\frac{2a^3}{3} - (2a+b) (c_{AB})^2\right] + \frac{ad^3}{6}$$

$$= 6.75 \text{ in.} \left[\frac{(2) (18.375 \text{ in.})^3}{3} - (2 \times 18.375 \text{ in.} + 21.75 \text{ in.}) (5.77 \text{ in.})^2\right]$$

$$+ \frac{(18.375 \text{ in.}) (6.75 \text{ in.})^3}{6}$$

$$= 15,714 \text{ in.}^4$$

(d) Compute gravity load shear to be transferred at the exterior column.

$$V_u = \frac{q_u \ell_1 \ell_2}{2} = \frac{(0.280 \text{ ksf}) (18 \text{ ft}) (20 \text{ ft})}{2} = 50.4 \text{ k}$$

(e) Combined stresses

$$\begin{aligned} v_u &= \frac{V_u}{A_c} + \frac{\gamma_v M_n c_{AB}}{J_c} \\ &= \frac{50,400 \text{ lb}}{394.875 \text{ in.}^2} + \frac{(12 \text{ in/ft} \times 25,250 \text{ ft-lb}) (5.77 \text{ in.})}{15,714 \text{ in.}^4} \\ &= 128 \text{ psi} + 111 \text{ psi} = 239 \text{ psi} \\ &> 4\sqrt{3000} \text{ psi} = 219 \text{ psi} \quad \text{No good} \end{aligned}$$

.: It is necessary to do one or more of the following: increase depth of slab, use higher-strength concrete, use drop panel, or install shearhead reinforcing.

#### **Factored Moments in Columns and Walls**

If there is an unbalanced loading of two adjoining spans, the result will be an additional moment at the connection of walls and columns to slabs. The code (13.6.9.2) provides the approximate equation listed at the end of this paragraph to consider the effects of such situations. This particular equation was derived for two adjoining spans, one longer than the other. It was assumed that the longer span was loaded with dead load plus one-half live load and that only dead load was applied to the shorter span.

$$M_u = 0.07[(q_{du} + 0.5q_{\ell u})\ell_2\ell_n^2 - q_{Du'}\ell_2'(\ell_n')^2]$$
 (ACI Equation 13-7)

In this expression,  $q'_{du}$ ,  $\ell'_2$ , and  $\ell'_n$  are for the shorter spans. The resulting approximate value should be used for unbalanced moment transfer by gravity loading at interior columns unless a more theoretical analysis is used.

#### 16.13 **Openings in Slab Systems**

According to the code (13.4), openings can be used in slab systems if adequate strength is provided and if all serviceability conditions of the ACI, including deflections, are met.

- 1. If openings are located in the area common to intersecting middle strips, it will be necessary to provide the same total amount of reinforcing in the slab that would have been there without the opening.
- 2. For openings in intersecting column strips, the width of the openings may not be more than one-eighth the width of the column strip in either span. An amount of reinforcing equal to that interrupted by the opening must be placed on the sides of the opening.
- 3. Openings in an area common to one column strip and one middle strip may not interrupt more than one-fourth of the reinforcing in either strip. An amount of reinforcing equal to that interrupted shall be placed around the sides of the opening.
- **4.** The shear requirements of Section 11.11.6 of the code must be met.

### **Computer Example**

#### Example 16.6

Use the Chapter 16 Excel spreadsheet to solve Example 16.4.

#### SOLUTION

Open the Excel spreadsheet provided for Chapter 16 and open the worksheet Two-Way Slabs. Enter values only for cells highlighted in yellow (only in the Excel spreadsheets, not the printed example). Note that values for  $\beta_t$  and  $\alpha_{t1}$  must be entered. To obtain  $\beta_t$ , open the worksheet C Torsional Constant. Enter values for cells highlighted in yellow.

![](_page_548_Figure_2.jpeg)

If there are flanges on both sides of the web, a third value of x and y can be entered. In this case, their values are zero.

The value of  $\alpha_f$  is obtained from the worksheet Alpha T Beam. Results of the  $\alpha_f$  calculations in step 2(d) of Example 16.4 are shown below.

#### Interior Beam (flange on both sides)

![](_page_548_Figure_6.jpeg)

#### **Edge Beam**

| $b_E =$         | 29     | in.  |
|-----------------|--------|------|
| $b_W =$         | 15     | in.  |
| t =             | 6      | in.  |
| h =             | 20     | in.  |
| $\ell_2$ =      | 22     | ft   |
| k =             | 1.347  |      |
| $I_b =$         | 13,468 | in.4 |
| $I_s =$         | 2511   | in.4 |
| $\alpha_{f1} =$ | 5.363  |      |

$$\frac{b_E}{b_W} = 1.933$$

$$\frac{t}{h} = 0.3$$

![](_page_548_Figure_10.jpeg)

The other  $\alpha_f$  values are obtained simply by changing  $\ell_2$  from 22 ft to 18 ft. Return to the Example 16.6 worksheet and enter  $\beta_t=1.62$  and  $\alpha_{f1}=3.32$ . Now determine from Table 16.2 which case (1 through 5) applies to your example. In this situation, case (2) applies since there are beams between all supports. Enter 0.16, 0.57, and 0.70 in the highlighted cells in row 11. In addition to the information determined in Example 16.4, the spreadsheet also determines the required area of reinforcing steel throughout the slab.

#### Two-way slab

![](_page_549_Figure_3.jpeg)

The edge span part of the spreadsheet is set up for edge spans (part 4 of Example 16.4). Enter information the same way as for the upper part of the worksheet.

#### **PROBLEMS**

**Problem 16.1** Using the ACI Code, determine the minimum thickness required for panels 1 and 3 of the flat plate floor shown. Edge beams are not used along the exterior floor edges.  $f'_c = 3000 \text{ psi and } f_v = 60,000 \text{ psi. } (Ans. 9.07 \text{ in., } 8.12 \text{ in.)}$ 

![](_page_549_Figure_7.jpeg)

**Problem 16.2** Assume that the floor system of Problem 16.1 is to support a service live load of 80 psf and a service dead load of 60 psf in addition to its own weight. If the columns are 10 ft long, determine depth required for an interior flat plate for panel <sup>3</sup> .

**Problem 16.3** Repeat Problem 16.2 for panel <sup>1</sup> in the structure of Problem 16.1. Include depth required for one-way and two-way shear. (*Ans*. Use 10-in. slab)

**Problem 16.4** Determine the required reinforcing in the column strip and middle strips for column line <sup>B</sup> in Problem 16.1. Use a slab thickness of 10 in. and #6 bars. Determine theoretical and practical spacings in the exterior span (from column line <sup>1</sup> to <sup>2</sup> ) and the interior span (from column line <sup>2</sup> to <sup>3</sup> ).

**Problem 16.5** Use the Flat Plate worksheet of Chapter 16 spreadsheet to work Problem 16.4. (*Ans*. *As* <sup>=</sup> 6.53 in.2 in column strip at column line <sup>2</sup> ∴ use #6 @ 8 in. in top of slab)

### **CHAPTER 17**

