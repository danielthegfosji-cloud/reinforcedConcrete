# Continuous Reinforced **CHA PTER 14** Concrete Structures

### **14.1 Introduction**

During the construction of reinforced concrete structures, as much concrete as possible is placed in each pour. For instance, the concrete for a whole floor or for a large part of it, including the supporting beams and girders and parts of the columns, may be placed at the same time. The reinforcing bars extend from member to member, as from one span of a beam into the next. When there are construction joints, the reinforcing bars are left protruding from the older concrete, so they may be lapped or spliced to the bars in the newer concrete. In addition, the old concrete is cleaned so that the newer concrete will bond to it as well as possible. The result of all these facts is that reinforced concrete structures are generally monolithic or continuous and, thus, statically indeterminate.

A load placed in one span of a continuous structure will cause shears, moments, and deflections in the other spans of that structure. Not only are the beams of a reinforced concrete structure continuous, but the entire structure is also continuous. In other words, loads applied to a column affect the beams, slabs, and other columns, and vice versa.

The result is that more economical structures are obtained because the bending moments are smaller, and thus member sizes are smaller. Although the analyses and designs of continuous structures are more complicated than they are for statically determinate structures, this fact has become less important because of the constantly increasing availability of good software.

### **14.2 General Discussion of Analysis Methods**

In reinforced concrete design today, we use elastic methods to analyze structures loaded with factored or ultimate loads. Such a procedure probably doesn't seem quite correct to the reader, but it does yield satisfactory results. The reader might very well ask, "Why don't we use ultimate or inelastic analyses for reinforced concrete structures?" The answer is that our theory and tests are just not sufficiently advanced.

It is true that under certain circumstances, some modifications of moments are permitted to recognize ultimate or inelastic behavior as described in Section 14.5 of this chapter. In general, however, we will discuss elastic analyses for reinforced concrete structures. Actually, no method of analysis, elastic or inelastic, will give exact results because of the unknown effects of creep, settlement, shrinkage, workmanship, and so on.

### **14.3 Qualitative Influence Lines**

Many methods might be used to analyze continuous structures. The most common hand calculation method is moment distribution, but other methods are frequently used, such as matrix methods, computer solutions, and others. Whichever method is used, you should understand that to determine maximum shears and moments at different sections in the structure, it is necessary to consider different positions of the live loads. As a background for this material, a brief review of *qualitative influence lines* is presented.

![](_page_451_Picture_2.jpeg)

Confinazas Financial Center, Caracas, Venezuela.

Qualitative influence lines are based on a principle introduced by the German professor Heinrich M¨uller-Breslau. This principle is as follows: *The deflected shape of a structure represents to some scale the influence line for a function such as reaction*, *shear*, *or moment if the function in question is allowed to act through a small distance*. In other words, the structure draws its own influence line when the proper displacement is made.

The shape of the usual influence line needed for continuous structures is so simple to obtain with the M¨uller-Breslau principle that, in many situations, it is unnecessary to compute the numerical values of the coordinates. It is possible to sketch the diagram roughly with sufficient accuracy to locate the critical positions for live loads for various functions of the structure. These diagrams are referred to as *qualitative* influence lines, whereas those with numerical values are referred to as *quantitative* influence lines.1

If the influence line is desired for the left reaction of the continuous beam of Figure 14.1(a), its general shape can be determined by letting the reaction act upward through a unit distance, as shown in Figure 14.1(b). If the left end of the beam is pushed up, the beam will take the shape shown. This distorted shape can be sketched easily by remembering that the other supports are considered to be unyielding. The influence line for *Vc* , drawn in a similar manner, is shown in Figure 14.1(c).

Figure 14.1(d) shows the influence line for positive moment at point *x* near the center of the left-hand span. The beam is assumed to have a pin or hinge inserted at *x* and a couple is applied adjacent to each side of the pin, which will cause compression in the top fibers. Bending the beam on each side of the pin causes the left span to take the shape indicated, and the deflected shape of the remainder of the beam may be roughly sketched. A similar procedure

<sup>1</sup> McCormac, J. C., 2007, *Structural Analysis*: *Using Classical and Matrix Methods*, 4th ed. (Hoboken, NJ: John Wiley & Sons), pp. 189–194.

![](_page_452_Figure_2.jpeg)

**FI GU RE 14.1** Qualitative influence lines.

is used to draw the influence line for negative moment at point *y* in the third span, except that a moment couple is applied at the assumed pins, which will tend to cause compression in the bottom beam fibers, corresponding with negative moment.

Finally, qualitative influence lines are drawn for positive shear at points *x* and *y*. At point *x*, the beam is assumed to be cut, and the two vertical forces of the nature required to give positive shear are applied to the beam on the sides of the cut section. The beam will take the shape shown in Figure 14.1(f). The same procedure is used in Figure 14.1(g) to draw a diagram for positive shear at point *y*. (Theoretically, for qualitative shear influence lines, it is necessary to have a moment on each side of the cut section sufficient to maintain equal slopes. Such moments are indicated in parts (f) and (g) of the figure by the letter *M*.)

From these diagrams, considerable information is available concerning critical live loading conditions. If a maximum positive value of *VA* were desired for a uniform live load, the load would be placed in spans 1 and 3, where the diagram has positive ordinates; if maximum negative moment were required at point *y*, spans 2 and 4 would be loaded, and so on.

Qualitative influence lines are particularly valuable for determining critical load positions for buildings, as illustrated by the moment influence line for the building of Figure 14.2. In

![](_page_452_Picture_8.jpeg)

**FI GU RE 14.2** Qualitative influence line for moment in a frame.

![](_page_453_Picture_2.jpeg)

**FI GU RE 14.3** Load positions for maximum moments.

drawing diagrams for an entire frame, the joints are assumed to be free to rotate, but the members at each joint are assumed to be rigidly connected to each other so that the angles between them do not change during rotation. The influence line shown in the figure is for positive moment at the center of beam *AB*.

The spans that should be loaded to cause maximum positive moment are obvious from the diagram. It should be realized that loads on a member more than approximately three spans away have little effect on the function under consideration.

In the last few paragraphs, influence lines have been used to determine the critical positions for placing live loads to cause maximum moments. The same results can be obtained (and perhaps more easily) by considering the deflected shape or curvature of a member under load. If the live loads are placed so that they cause the greatest curvature at a particular point, they will have bent the structure the greatest amount at that point, which means that the greatest moment will have been obtained.

For the continuous beam of Figure 14.3(a), it is desired to cause the maximum negative moment at support *B* by the proper placement of a uniform live load. In part (b) of the figure, the deflected shape of the beam is sketched as it would be when a negative moment occurs at *B*, and the rest of the beam's deflected shape is drawn as shown by the dashed line. The live uniform load is then placed in the locations that would exaggerate that deflected shape. This is done by placing the load in spans 1, 2, and 4.

A similar situation is shown in Figure 14.3(c), where it is desired to obtain maximum positive moment at the middle of the second span. The deflected shape of the beam is sketched as it would be when a positive moment occurs in that span, and the rest of the beam's deflected shape is drawn in. To exaggerate this positive or downward bending in the second span, it can be seen that the live load should be placed in spans 2 and 4.

### **14.4 Limit Design**

It can be clearly shown that a statically indeterminate beam or frame normally will not collapse when its ultimate moment capacity is reached at just one section. Instead, there is a redistribution of the moments in the structure. Its behavior is rather similar to the case where three men

are walking along with a log on their shoulders and one of the men gets tired and lowers his shoulder just a little. The result is a redistribution of loads to the other men and, thus, changes in the shears and moments throughout the log.

It might be well at this point to attempt to distinguish between the terms *plastic design* as used in structural steel and *limit design* as used in reinforced concrete. In structural steel, plastic design involves both (a) the increased resisting moment of a member after the extreme fiber of the member is stressed to its yield point and (b) the redistribution or change in the moment pattern in the member. (Load and resistance factor design [LRFD] is a steel design method that incorporates much of the theory associated with plastic design.) In reinforced concrete, the increase in resisting moment of a section after part of the section has been stressed to its yield point has already been accounted for in the strength design procedure. Therefore, limit design for reinforced concrete structures is concerned only with the change in the moment pattern after the steel reinforcing at some cross section is stressed to its yield point.

The basic assumption used for limit design of reinforced concrete structures and for plastic design of steel structures is the ability of these materials to resist a so-called yield moment while an appreciable increase in local curvature occurs. In effect, if one section of a statically indeterminate member reaches this moment, it begins to yield but does not fail. Rather, it acts like a hinge (called a *plastic hinge*) and throws the excess load off to sections of the members that have lesser stresses. The resulting behavior is much like that of the log supported by three men when one man lowered his shoulder.

To apply the limit design or plastic theory to a particular structure, it is necessary for that structure to behave plastically. For this initial discussion, it is assumed that an ideal plastic material, such as a ductile structural steel, is involved. Figure 14.4 shows the relationship of moment to the resulting curvature of a short length of a ductile steel member. The theoretical ultimate or nominal resisting moment of a section is referred to in this text as *Mn* (it's the same as the plastic moment *Mp* ).

Although the moment-to-curvature relationship for reinforced concrete is quite different from the ideal one pictured in Figure 14.4, the actual curve can be approximated reasonably well by the ideal one, as shown in Figure 14.5. The dashed line in the figure represents the ideal curve, while the solid line is a typical one for reinforced concrete. Tests have shown that the lower the reinforcing percentage in the concrete ρ or ρ − ρ (where ρ is the percentage of compressive reinforcing), the closer will the concrete curve approach the ideal curve. This is particularly true when very ductile reinforcing steels, such as Grade 40, are used. Should a large percentage of steel be present in a reinforced concrete member, the yielding that actually occurs before failure will be so limited that the ultimate or limit behavior of the member will not be greatly affected by yielding.

![](_page_454_Figure_7.jpeg)

**FI GU RE 14.4** Moment–curvature relationship for an ideal plastic material.

![](_page_455_Figure_2.jpeg)

**FI GU RE 14.5** Typical moment–curvature relationship for a reinforced concrete member.

### **The Collapse Mechanism**

To understand moment redistribution in steel or reinforced concrete structures, it is necessary first to consider the location and number of plastic hinges required to cause a structure to collapse. A statically determinate beam will fail if one plastic hinge develops. To illustrate this fact, the simple beam of constant cross section loaded with a concentrated load at midspan shown in Figure 14.6(a) is considered. Should the load be increased until a plastic hinge is developed at the point of maximum moment (underneath the load in this case), an unstable structure will have been created, as shown in Figure 14.6(b). Any further increase in load will cause collapse.

The plastic theory is of little advantage for statically determinate beams and frames, but it may be of decided advantage for statically indeterminate beams and frames. For a statically indeterminate structure to fail, it is necessary for more than one plastic hinge to form. The number of plastic hinges required for failure of statically indeterminate structures will be

![](_page_455_Figure_7.jpeg)

**FI GU RE 14.6** Plastic hinge formation in a statically determinate beam.

![](_page_456_Figure_2.jpeg)

**FI GU RE 14.7** Plastic hinge formation in a fixed-fixed statically indeterminate beam.

shown to vary from structure to structure but can never be less than two. The fixed-end beam of Figure 14.7 cannot fail unless the three plastic hinges shown in the figure are developed.

Although a plastic hinge may be formed in a statically indeterminate structure, the load can still be increased without causing failure if the geometry of the structure permits. The plastic hinge will act like a real hinge insofar as increased loading is concerned. As the load is increased, there is a redistribution of moment because the plastic hinge can resist no more moment. As more plastic hinges are formed in the structure, there will eventually be a sufficient number of them to cause collapse.

The propped beam of Figure 14.8 is an example of a structure that will fail after two plastic hinges develop. Three hinges are required for collapse, but there is a real hinge at the right end. In this beam, the largest elastic moment caused by the design-concentrated load is at the fixed end. As the magnitude of the load is increased, a plastic hinge will form at that point.

The load may be further increased until the moment at some other point (here it will be at the concentrated load) reaches the plastic moment. Additional load will cause the beam to collapse. The arrangement of plastic hinges, and perhaps real hinges that permit collapse in a structure, is called the *mechanism*. Parts (b) of Figures 14.6, 14.7, and 14.8 show mechanisms for various beams.

![](_page_456_Picture_8.jpeg)

**FI GU RE 14.8** Plastic hinge formation in a propped cantilever statically indeterminate beam.

#### Plastic Analysis by the Equilibrium Method

To analyze a structure plastically, it is necessary to compute the plastic or ultimate moments of the sections, to consider the moment redistribution after the ultimate moments develop, and finally to determine the ultimate loads that exist when the collapse mechanism is created. The method of plastic analysis known as the equilibrium method will be illustrated in this section.

The fixed-end beam of Figure 14.9 is considered first. It is desired to determine the value of  $w_n$ , the theoretical ultimate load the beam can support. The maximum moments in a uniformly loaded fixed-end beam in the elastic range occur at the fixed ends, as shown in the figure.

If the magnitude of the uniform load is increased, the moments in the beam will be increased proportionately until a plastic moment eventually develops at some point. Because of symmetry, plastic moments will be developed at the beam ends, as shown in Figure 14.10(b). Should the loads be further increased, the beam will be unable to resist moments larger than  $M_n$ at its ends. Those points will rotate through large angles, and thus the beam will be permitted to

![](_page_457_Figure_6.jpeg)

FIGURE 14.9 Elastic moment diagram in a fixed-fixed statically indeterminate beam.

![](_page_457_Figure_8.jpeg)

FIGURE 14.10 Moment diagram after hinge formation at supports in a fixed-fixed beam.

deflect more and allow the moments to increase out in the span. Although the plastic moment has been reached at the ends and plastic hinges are formed, the beam cannot fail because it has, in effect, become a simple end-supported beam for further load increases, as shown in Figure 14.10(c).

The load can now be increased on this "simple" beam, and the moments at the ends will remain constant; however, the moment out in the span will increase as it would in a uniformly loaded simple beam. This increase is shown by the dashed line in Figure 14.11(b). The load can be increased until the moment at some other point (here the beam centerline) reaches the plastic moment. When this happens, a third plastic hinge will have developed and a mechanism will have been created, permitting collapse.

One method of determining the value of  $w_n$  is to take moments at the centerline of the beam (knowing the moment there is  $M_n$  at collapse). Reference is made here to Figure 14.11(a) for the beam reactions.

$$M_n = -M_n + \left(w_n \frac{\ell}{2}\right) \left(\frac{\ell}{2} - \frac{\ell}{4}\right) = -M_n + \frac{w_n \ell^2}{8}$$

$$w_n = \frac{16M_n}{\ell^2}$$

The same value could be obtained by considering the diagrams shown in Figure 14.12. You will remember that a fixed-end beam can be replaced with a simply supported beam plus a beam with end moments. Thus, the final moment diagram for the fixed-end beam equals the moment diagram if the beam had been simply supported plus the end moment diagram.

![](_page_458_Figure_7.jpeg)

FIGURE 14.11 Formation of a collapse mechanism in a fixed-fixed beam.

![](_page_459_Figure_2.jpeg)

**FIGURE 14.12** Moment superposition.

For the fixed-fixed beam under consideration, the value of  $M_n$  can be calculated as follows (see Figure 14.13):

$$2M_n = \frac{w_n \ell^2}{8}$$

$$M_n = \frac{w_n \ell^2}{16}$$

The propped beam of Figure 14.14, which supports a concentrated load, is presented as a second illustration of plastic analysis. The goal is to determine the value of  $P_n$ , the theoretical ultimate load the beam can support before collapse. The maximum moment in this beam in the elastic range occurs at the fixed end, as shown in the figure. If the magnitude of the concentrated load is increased, the moments in the beam will increase proportionately until a plastic moment is eventually developed at some point. This point will be at the fixed end, where the elastic moment diagram has its largest ordinate.

After this plastic hinge is formed, the beam will act as though it is simply supported insofar as load increases are concerned, because it will have a plastic hinge at the left end and a real hinge at the right end. An increase in the magnitude of the load P will not increase the moment at the left end but will increase the moment out in the beam, as it would in a simple beam. The increasing simple beam moment is indicated by the dashed line in Figure 14.14(c). Eventually, the moment at the concentrated load will reach  $M_n$  and a mechanism will form, consisting of two plastic hinges and one real hinge, as shown in Figure 14.14(d).

The value of the theoretical maximum concentrated load,  $P_n$ , that the beam can support can be determined by taking moments to the right or left of the load. Figure 14.14(e) shows the beam reactions for the conditions existing just before collapse. Moments are taken to the right of the load as follows:

$$M_n = \left(\frac{P_n}{2} - \frac{M_n}{20}\right) 10$$

$$P_n = 0.3M_n$$

![](_page_459_Figure_10.jpeg)

**FIGURE 14.13** Determination of required  $M_n$  from fixed-fixed beam with hinges forming mechanism.

![](_page_460_Figure_2.jpeg)

**FI GU RE 14.14** Hinge formation sequence in a propped cantilever beam.

The subject of plastic analysis can be continued for different types of structures and loadings, as described in several textbooks on structural analysis or steel design.2 The method has been proved to be satisfactory for ductile structural steels by many tests. Concrete, however, is a relatively brittle material, and the limit design theory has not been fully accepted by the ACI Code. The code does recognize that there is some redistribution of moments and permits partial redistribution based on a rule of thumb that is presented in the next section of this chapter.

<sup>2</sup> McCormac, J. C. and Csernak, S. F., 2011, *Structural Steel Design*, 5th ed. (Hoboken, NJ: Pearson Prentice Hall), pp. 240–244.

### **14.5 Limit Design under the ACI Code**

Tests of reinforced concrete frames have shown that under certain conditions, there is definitely a redistribution of moments before collapse occurs. Recognizing this fact, the ACI Code (8.4.1) permits factored moments calculated by elastic theory (*not by an approximate analysis*) to be decreased at locations of maximum negative or positive moment in any span of a continuous structure for any loading arrangement. The amount by which moments can be decreased cannot exceed 1000*<sup>t</sup>*% with a maximum of 20%. Redistribution of moments as described herein is not permissible unless *<sup>t</sup>* is equal to or greater than 0.0075 at the section where moment is reduced (ACI Section 8.4.2). Appendix A, Table A.7 and Appendix B, Table B.7 of this book provide percentages of steel for which *<sup>t</sup>* will be equal to 0.0075. If ρ is greater than these values, redistribution is not permitted, because *<sup>t</sup>* will be less than 0.0075. The values given in the table are for rectangular sections with tensile reinforcing.

According to ACI Section 18.10.4.1, negative or positive moments may be decreased for prestressed sections, using the same rules, if bonded reinforcing (as described in Chapter 19 herein) is used.

The ACI Code's percentage of moment redistribution has purposely been limited to a very conservative value to be sure that excessively large concrete cracks do not occur at high steel stresses and to ensure adequate ductility for moment redistribution at the plastic hinges. The ACI Code likely will expand its presently conservative redistribution method after the behavior of plastic hinges is better understood, particularly in regard to shears, deflections, and development of reinforcing. It is assumed here that the sections are satisfactorily reinforced for shears so that the ultimate moments can be reached without shear failure occurring. The adjustments are applied to the moments resulting from each of the different loading conditions. The member in question will then be proportioned on the basis of the resulting moment envelope. Figures 14.15 through 14.18 illustrate the application of the moment redistribution permitted by the code to a three-span continuous beam. It will be noted in these figures that factored loads and elastic analyses are used for all the calculations.

Three different live-load conditions are considered in these figures. To determine the maximum positive moment in span 1, the live load is placed in spans 1 and 3 (Figure 14.15). Similarly, to produce maximum positive moment in span 2, the live load is placed in that span only (Figure 14.16). Finally, maximum negative moment at the first interior support from the left end is caused by placing the live load in spans 1 and 2 (Figure 14.17).

For this particular beam, it is assumed that the code permits a 10% decrease in the negative or positive moments. This will require that 1000*<sup>t</sup>* exceed 10 at the sections where the moment is reduced to provide the needed ductility. The result will be smaller design moments at the critical sections. Initially, the loading for maximum positive moment in span 1 is considered as shown in Figure 14.15. If the maximum calculated positive moments of 425 ft-k near midspan of the end spans are each decreased by 10% to 383 ft-k, the negative moments at both interior supports will be increased to 406 ft-k. Even though the negative moment has increased significantly, from 308 ft-k to 406 ft-k, this higher value still will not control the required moment capacity at this location. Hence, the positive design moment is decreased, but the negative moment is not increased.

In the same fashion, in Figure 14.16, where the beam is loaded to produce maximum positive moment in span 2, a 10% decrease in positive moment from 261 ft-k to 235 ft-k will increase the negative moment at both interior supports from 339 ft-k to 365 ft-k.

Finally, in Figure 14.17, the live-load placement causes a maximum negative moment at the first interior support of 504 ft-k. If this value is reduced by 10%, the maximum moment there will be −454 ft-k. In this figure, the authors have reduced the negative moment at the other interior support by 10% also.

It will be noticed that the net result of all of the various decreases in the positive or negative moments is a net reduction in both the maximum positive and the maximum negative

![](_page_462_Figure_2.jpeg)

**FIGURE 14.15** Maximum positive moment in end spans. (a) Loading patterns for maximum positive moment in both end spans. (b) Moment diagram before and after reducing positive moment in end spans. (c) Shears and moments in left span after  $M^+$  is reduced 10% in end spans.

![](_page_462_Figure_4.jpeg)

**FIGURE 14.16** Maximum positive moment in span 2.

![](_page_463_Figure_2.jpeg)

**FI GU RE 14.17** Maximum negative moment at support *B*.

values. The result of these various redistributions is actually an envelope of the extreme values of the moments at the critical sections. The envelope for the three-span beam considered in this section is presented in Figure 14.18. You can see at a glance the parts of the beams that need positive reinforcement, negative reinforcement, or both.

*The reductions in bending moments because of moment redistribution as described here do not mean that the safety factors for continuous members will be less than those for simple spans. Rather, the excess strength that such members have because of this continuity is reduced so that the overall factors of safety are nearer but not less than those of simple spans.*

Various studies have shown that cracking and deflection of members selected by the limit design process are no more severe than those for the same members designed without taking advantage of the permissible redistributions.3,4

(Appendix B of the ACI Code presents quite a few variations that can be used in design for flexure and axial loads. There are changes in the moment redistribution percentages permitted for continuous members, in the reinforcing limits and in the strength reduction or φ factors. These latter changes are dependent on the strain conditions, including whether the sections are compression or tension controlled.)

![](_page_463_Figure_8.jpeg)

**FI GU RE 14.18** Moment envelope.

<sup>3</sup> Cohn, M. Z., 1964, "Rotational Compatibility in the Limit Design of Reinforced Concrete Continuous Beams," *Proceedings of the International Symposium on the Flexural Mechanics of Reinforced Concrete* (Miami, FL: ASCE-ACI), pp. 359–382. <sup>4</sup> Mattock, A. H., 1959, "Redistribution of Design Bending Moments in Reinforced Concrete Continuous Beams," *Proceedings of the Institution of Civil Engineers*, 113, pp. 35–46.

### 14.6 Preliminary Design of Members

Before an "exact" analysis of a building frame can be made, it is necessary to estimate the sizes of the members. Even if a computer design is used, it is often economically advisable to make some preliminary estimates as to sizes. If an approximate analysis of the structure has been made, it will be possible to make very reasonable member size estimates. The result will be appreciable saving of both computer time and money.

An experienced designer can usually make very satisfactory preliminary size estimates based on previous experience. In the absence of such experience, however, the designer can still make quite reasonable size estimates based on knowledge of structural analysis. For instance, to size columns approximately, a designer can neglect moments and assume an average axial stress, or  $P_u/A_g$ , value of about  $0.4f_c'$  to  $0.6f_c'$ . This rough value can be divided into the estimated column load to obtain its estimated area. If moments are large, lower values of average stress  $(0.4f_c'$  to  $0.5f_c'$ ) can be used; if moments are small, higher values  $(0.55f_c'$  to  $0.6f_c'$ ) can be used.

Preliminary beam sizes can be obtained by considering their approximate moments. A uniformly loaded simple beam will have a maximum bending moment equal to  $w_u \ell^2/8$ , whereas a uniformly loaded fixed-end beam will have a maximum moment of  $w_u \ell^2/12$ . For a continuous uniformly loaded beam, the designer might very well estimate a maximum moment somewhere between the values given, perhaps  $w_u \ell^2/10$ , and use that value to estimate the beam size.

For many structures, it is necessary to conduct at least two different analyses. One analysis is made to consider the effect of gravity loads as described in Section 14.7 of this chapter, while another might be made to consider the effect of lateral loads as discussed in Section 14.8. For the gravity loads only, U usually equals 1.2D + 1.6L.

Because the gravity loads affect only the floor to which they are applied, each floor can be analyzed independently of the others. Such is not the case for lateral loads because lateral loads applied anywhere on the frame affect the lateral displacements throughout the frame and, thus, affect the forces in the frame below. For this situation, the load factor equations involving lateral forces (ACI Equations 9-3, 9-4, etc.) must be applied.

Sometimes a third analysis should be made—one that involves the possibility of force reversals on the windward side or even overturning of the structure. If overturning is being considered, the dead and live gravity loads should be reduced to their smallest possible values (i.e., zero live load and 0.9D, in case the dead loads have been overestimated a little) while the lateral loads are acting. For this case, ACI load factor equations 9-6 and 9-7 must be considered.

