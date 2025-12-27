# The Strut-and-Tie Method of Design

#### C.1 Introduction

This appendix presents an alternative method for designing reinforced concrete members with force and geometric discontinuities. The method is also very useful for designing deep beams for which the usual assumption of linear strain distribution is not valid. This method of design, commonly referred to as strut-and-tie design, is briefly introduced.

### C.2 Deep Beams

Section 10.7 of the ACI Code defines a deep beam as a member that

- (a) Is loaded on one face and supported on the opposite face so that compression struts can develop between the load and the supports.
- **(b)** Has a clear span not more than four times its overall depth or that has regions where concentrated loads are located within two times the member depth from the support.

*Transfer girders* are one type of deep beam that occur rather frequently. Such members are used to transfer loads laterally from one or more columns to other columns. Sometimes bearing walls also exhibit deep beam action.

Deep beams begin to crack at loads ranging from  $\frac{1}{3}P_u$  to  $\frac{1}{2}P_u$ . As a result, elastic analyses are not of much value to us except in one regard: the cracks tell us something about the way the stresses that cause the cracks are distributed. In other words, they provide information as to how the loads will be carried after cracking.

### C.3 Shear Span and Behavior Regions

The ratio of the shear span of a beam to its effective depth determines how the beam will fail when overloaded. The shear span for a particular beam is shown in Figure C.1, where it is represented by the symbol a. This is the distance from the concentrated load shown to the face of the support. Should the beam be supporting only a uniform load, the shear span is the clear span of the beam.

When shear spans are long, they are referred to as B regions. These are regions for which the usual beam theory applies—plane sections remain plain before and after bending. The letter B stands for beam or for Bernoulli (he is the one who presented the linear strain theory for beams).

In some situations, the usual beam theory does not apply. When shear spans are short, loads are primarily resisted by arch action rather than beam action. Locations where this occurs are called D regions. The letter D represents discontinuity or disturbance. In such regions, plane

![](_page_695_Picture_2.jpeg)

**FI GU RE C.1** Shear span.

sections before bending do not remain plane after bending, and the forces obtained with the usual shear and moment diagrams and first-order beam theory are incorrect.

D regions are those parts of members located near concentrated loads and reactions. They also include joints and corbels and other locations where sudden changes in member cross section occur, such as where holes are present in members.

According to the St. Venant principle, local disturbances such as those caused by concentrated loads tend to dissipate within a distance approximately equal to the member depth. Figure C.2 shows several typical B and D regions. You should note that the authors used the St. Venant principle in this figure to show the extent of the D regions. For more examples, the reader should also examine Figures R.A.1.1 and R.A.1.2 in Appendix A of the ACI Code.

![](_page_695_Figure_7.jpeg)

**FI GU RE C.2** B and D regions.

### **C.4 Truss Analogy**

If shear spans are very short, inclined cracks extending from the concentrated loads to the supports tend to develop. This situation is illustrated in Figure C.3. In effect, the flow of horizontal shear from the longitudinal reinforcement to the compression zone has been interrupted. As a result, the behavior of the member has been changed from that of a beam to that of a tied arch where the reinforcing bars act as the ties of an arch.

In Chapter 8, Section 8.7 of this text, reference was made to the description of reinforced concrete beams by Ritter-Morsch with the truss analogy method. According to that theory, a reinforced concrete beam with shear reinforcement behaves much like a statically determinate parallel chord truss with pinned joints. The concrete compression block is considered to be the top chord of the fictitious "truss," while the tensile reinforcement is considered to act as the bottom chord. The "truss" web is said to consist of the stirrups acting as vertical tension members, while the portions of the concrete between the diagonal cracks are assumed to act as diagonal compression members. Such a "truss" is shown in Figure C.4, which is a copy of Figure 8.4 presented in Chapter 8.

In this figure, the compression concrete and the stirrups are shown with dashed lines. These lines represent the estimated centers of gravity of those forces. The tensile forces are represented with solid lines because those forces clearly act along the reinforcing bar lines.

![](_page_696_Figure_6.jpeg)

**FI GU RE C.3** A very short shear span.

![](_page_696_Figure_8.jpeg)

**FI GU RE C.4** Truss analogy.

#### C.5 Definitions

A strut-and-tie model is a truss model of a D region where the member is represented by an idealized truss of struts and ties.

A tie is a tension member in a strut-and-tie model.

A strut is a compression member in a strut-and-tie model that represents the resultant of the compression field.

A node in a strut-and-tie model is the point in a joint where the struts, ties, and concentrated forces at the joint intersect.

The *nodal zone* is the volume of concrete around a node that is assumed to transfer the forces from the struts and ties through the node.

### C.6 ACI Code Requirements for Strut-and-Tie Design

Several of the more important code requirements for strut-and-tie-design are as follows.

#### Strength of Struts

1. The design strength of a strut, tie, or nodal zone,  $\phi F_n$ , must be at least as large as the force in the strut or tie or nodal zone.

$$\phi F_n \ge F_n$$
 (ACI Equation A-1)

In Section 9.3.2 of the ACI Code,  $\phi$  is specified to be 0.75 for strut-and-tie members.

2. The nominal compression strength of a strut that contains no longitudinal reinforcing is to be taken as the smaller value at the two ends of the strut of

$$F_{ns} = f_{ce}A_{cs}$$
 (ACI Equation A-2)

where  $A_{cs}$  is the cross-sectional area at one end of a strut taken perpendicular to the axis and  $f_{co}$  is the effective compression strength of the concrete (psi) in a strut or nodal zone. Its value is to be taken as the lesser of (a) and (b) to follow:

(a) Effective concrete compression strength in struts

$$f_{ce} = 0.85 \beta_s f_c'$$
 (ACI Equation A-3)

 $\beta_{\rm s}$  is a factor used to estimate the effect of cracking and confining the reinforcing on the strength of the strut concrete. Values of  $\beta_s$  are given in Appendix Section A.3.2 of the ACI Code for different situations. They vary from 0.4 to 0.75, and their meaning and effect are similar to  $\beta_1$  on the rectangular stress blocks so frequently discussed for beams and columns earlier in this text. For a strut having uniform cross-sectional area over its length,  $\beta_s = 1.0$ . For struts in tension members of tension flanges,  $\beta_s = 0.40$ .

For bottle-shaped struts (width at midsection greater than width at nodes),  $\beta_s =$ 0.75 if  $f_c' \le 6000$  psi and if the axis of the strut is crossed by layers of reinforcement that satisfy ACI Equation A-4

$$\sum \frac{A_{si}}{B_s S_i} \sin \alpha_i \ge 0.003$$
 (ACI Equation A-4)

where  $A_{si}$  is the total area of surface reinforcement at spacing  $S_i$  in the *i*th layer of reinforcement, crossing a strut at an angle  $\alpha_i$  to the axis of the strut. For bottle-shaped struts not satisfying ACI Equation A-4,  $\beta_s = 0.60\lambda$ . Finally, for all other struts,  $\beta_s = 0.60\lambda$ .

(b) The nominal compression strength of a nodal zone,  $F_{nn}$ , is

$$F_{nn} = f_{ce} A_{nr}$$

where  $A_{nz}$  is the smaller of

- (i) the area of the face of the nodal zone on which  $F_u$  acts, taken perpendicular to the line of action of  $F_u$ , or
- (ii) the area of a section through the nodal zone, taken perpendicular to the line of action of  $F_n$ .

Effective concrete compression strength in nodal zones

$$f_{ce} = 0.85 \beta_n f_c'$$
 (ACI Equation A-8)

 $\beta_n$  is a factor used to estimate the effect of the anchorage of ties on the effective compression strength of the nodal zone. Values are specified for different situations in ACI Appendix Section A.5.2 and vary from 0.6 to 1.0, depending on the number of ties and on what bounds the nodal zone.

#### **Strength of Ties**

Following the provisions of ACI 318 in its Appendix A-4, the nominal strength of a tie is to be determined with the following expression:

$$F_{nt} = A_{ts} f_{v} + A_{tp} (f_{se} + \Delta f_{p})$$
 (ACI Equation A-6)

where

 $A_{ts}$  = area of nonprestressed reinforcing in a tie

 $f_{\rm v}=$  yield strength of the nonprestressed reinforcement

 $A_{tp}$  = area of prestressing steel in a tie

 $f_{se}$  = effective stress in prestressed reinforcement after losses

 $\Delta f_p$  = increase in stress in prestress steel due to factored loads. The code in its Section A.4.1 states that it is permissible to use  $\Delta f_p = 60,000$  psi for bonded prestressed reinforcement and 10,000 psi for nonbonded prestressed reinforcement. Other values can be used if they can be justified by analysis.

 $f_{se} + \Delta f_p$  shall not exceed  $f_{py}$ .

### C.7 Selecting a Truss Model

When the strut-and-tie method is used for D regions, the results are thought to be more conservative but more realistic than the results obtained with the usual beam theory. To design for a D region of a beam, it is necessary to isolate the region as a free body, determine the forces acting on that body, and then select a system or truss model to transfer the forces through the region.

Once the D region has been identified and its dimensions have been determined, it is assumed to extend a distance h on each side of the discontinuity or to the face of the support if that value is less than the depth.

![](_page_699_Figure_2.jpeg)

**FI GU RE C.5** A beam showing shear and tensile reinforcing.

The stresses on the boundaries of the region are computed with the usual expression for combined axial load and bending, *P*/*A* ± *Mc*/*I* . The resulting values must be divided by the capacity reduction factor φ for shearing forces (0.75) to obtain the required nominal stresses.

The designer needs to represent the D regions of members, which fail in shear, with some type of model before beginning the design. The model selected for beams with shear reinforcement is the truss model, as it is the best one available at this time.

For this discussion, the beam of Figure C.5 is considered. The internal and external forces acting on this beam, which is assumed to be cracked, are shown. To select a strut-and-tie model for such a beam, all the stirrups cut by the imaginary section (see Figure C.5) are lumped into one. In a similar fashion, the concrete parallel to a diagonal is also lumped together in one member.

With the strut-and-tie method, forces are resisted by an idealized internal truss such as the triangular one sketched in Figure C.6. The member and joints of this truss are designed so that they will be able to resist the computed forces. The truss selected must, of course, be smaller than the beam that encloses it, and any reinforcing steel must be given adequate cover. For a first illustration, a short deep beam supporting a concentrated load is shown in Figure C.6.

Various types of nodes are shown in Figure C.7. You should observe that there have to be at least three forces at each joint for equilibrium. This is the number of forces necessary for static equilibrium as well as the largest number that can occur in a state of determinate static equilibrium.

If more than three forces meet at a joint when a truss is laid out, the designer will need to make combinations of them in some way so that only three forces are considered to meet at the node. Two possible strut-and-tie models for a deep beam supporting two concentrated loads are shown in Figure C.8. In part (a) of the figure, four forces meet at the location of

![](_page_699_Figure_10.jpeg)

**FI GU RE C.6** A short deep beam with the truss model shown.

![](_page_700_Figure_2.jpeg)

FIGURE C.7 Various types of truss joints.

![](_page_700_Figure_4.jpeg)

FIGURE C.8 Two more assumed strut-and-tie trusses.

each concentrated load. As such, we cannot determine all of the forces. An alternative truss is shown in part (b) of the figure in which only three forces meet at each joint.

You can see that the assumptions of the paths of the forces involved in the trusses described might vary quite a bit among different designers. As a result, there is no one correct solution for a particular member designed by the strut-and-tie method.

### C.8 Angles of Struts in Truss Models

To lay out the truss, it is necessary to establish the slope of the diagonals (angle  $\theta$  in Figure C.8 that is measured from the tension chord—the tension reinforcement). According to Schlaich and Weischede, the angle of stress trajectories varies from about  $68^{\circ}$  if  $l/d \geq 10$  to about  $55^{\circ}$  if  $l/d = 2.0.^{1}$  A rather common practice, and one that is used in this appendix and is usually satisfactory, is to assume a 2 vertical to 1 horizontal slope for the struts. This will result in a value of  $\theta = 63^{\circ}56'$ . The dimensions selected for the truss model must fit into the D region involved, so the angles may need to be adjusted.

<sup>&</sup>lt;sup>1</sup> Jörg Schlaich and Dieter Weischede, *Detailing of Concrete Structures*, Bulletin d'Information 150, Comité Euro-International 'du Béton, Paris (March 1982), 163 pages.

### **C.9 Design Procedure**

Following is a step-by-step procedure for using the strut-and-tie design method.

- **1.** *Selection of strut-and-tie model*—A truss is selected to support the concentrated loads, and that truss is analyzed.
- **2.** *Design of vertical stirrups*—A stirrup bar size is assumed, and its strength is assumed to equal its cross-sectional area times its yield stress. The number of stirrups required equals the vertical force divided by the strength of one of the stirrups. The required spacing of these stirrups is determined. If it is too large or too small, a different stirrup size is assumed, and the procedure is repeated.
- **3.** *Selection of horizontal reinforcing across beam perpendicular to span*—The appendix to the code does not require that reinforcing such as this be used, but it is likely that its use will appreciably reduce cracking. As a result, we can select an amount of steel equal to that listed in ACI Section 11.7.4 for regular deep beam design. There the equation *Avh* = 0.0025*bwsh* is given, and it is specified that the spacing of such reinforcing not exceed *d*/5 or 12 in.
- **4.** *Computing the strength of struts*—Next ACI Equation A-3 is applied to check needed strut sizes. In actual problems, these struts are the diagonals. As a part of the calculation, the spaces available are compared to the required sizes.
- **5.** *Design of ties parallel to beam span*—Horizontal ties parallel to the beam span are needed to resist the horizontal forces in the struts and keep them from cracking. The design strength of such ties is provided by ACI Appendix Equation A-6.
- **6.** *Analysis of nodal zones*—Finally, ACI Appendix Equation A-8 is used to determine the strength of the nodal zones. The reader should note that ACI Appendix Section A.5.2 states that no confinement of the nodal zones is required.

