Appendix A.5 indicates a minimum beam width of 9.8 in. for interior exposure for three #9 bars. If five #7 bars had been selected, a minimum width of 12.8 in. would be required. Either choice would be acceptable since the beam width of 14 in. exceeds either requirement. If we had selected a beam width of 12 in. earlier in the design process, we might have been limited to the larger #9 bars because of this minimum beam width requirement.

#### **Checking Solution**

$$\rho = \frac{A_s}{bd} = \frac{3.00 \, \text{in.}^2}{(14 \, \text{in.})(24.5 \, \text{in.})} = 0.00875 > \rho_{\text{min}} = 0.0033$$

 $<
ho_{\rm max}=$  0.0181 (ho values from Appendix A, Table A.7).

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{(3.00 \text{ in.}^2) (60 \text{ ksi})}{(0.85) (4 \text{ ksi}) (14 \text{ in.})} = 3.78 \text{ in.}$$

$$\phi M_n = \phi A_s f_y \left( d - \frac{a}{2} \right) = (0.90) (3.00 \text{ in.}^2) (60 \text{ ksi}) \left( 24.5 \text{ in.} - \frac{3.78 \text{ in.}}{2} \right)$$

$$= 3662 \text{ in-k} = 305.2 \text{ ft-k} > 294.8 \text{ ft-k} \qquad \underline{OK}$$

#### Final Section (Figure 4.2)

![](_page_109_Figure_10.jpeg)

**FIGURE 4.2** Final beam cross section for Example 4.2.

#### **Use of Graphs and Tables**

In Section 3.4, the following equation was derived:

$$M_u = \phi A_s f_y d \left( 1 - \frac{1}{1.7} \frac{\rho f_y}{f_c'} \right)$$

If  $A_s$  in this equation is replaced with  $\rho bd$ , the resulting expression can be solved for  $M_u/\phi bd^2$ .

$$M_u = \phi \rho b df_y d \left( 1 - \frac{1}{1.7} \frac{\rho f_y}{f_c'} \right)$$

and dividing both sides of the equation by  $\phi bd^2$ ,

$$\frac{M_u}{\phi b d^2} = \rho f_y \left( 1 - \frac{1}{1.7} \frac{\rho f_y}{f_c'} \right)$$

For a given steel percentage,  $\rho$ , certain concrete,  $f_c$ , and certain steel,  $f_v$ , the value of  $M_u/\phi bd^2$  can be calculated and listed in tables, as is illustrated in Appendix A, Tables A.8

![](_page_110_Picture_2.jpeg)

Barnes Meadow Interchange, Northampton, England

through A.13, or in graphs (see Graph 1 of Appendix A). SI values are provided in Appendix Tables B.8 through B.9. It is much easier to accurately read the tables than the graphs (at least to the scale to which the graphs are shown in this text). For this reason, the tables are used for the examples here. The units for  $M_u/\phi b d^2$  in both the tables and the graphs of Appendix A are pounds per square inch. In Appendix B, the units are MPa.

Once  $M_u/\phi bd^2$  is determined for a particular beam, the value of  $M_u$  can be calculated as illustrated in the alternate solution for Example 3.1. The same tables and graphs can be used for either the design or analysis of beams.

The value of  $\rho$ , determined in Example 4.2 by substituting into that long and tedious equation, can be directly selected from Appendix A, Table A.13. We enter that table with the  $M_u/\phi b d^2$  value previously calculated in the example, and we read a value of  $\rho$  between 0.0084 and 0.0085. Interpolation can be used to find the actual value of 0.00842, but such accuracy is not really necessary. It is conservative to use the higher value (0.0085) to calculate the steel area.

In Example 4.3, which follows, a value of  $\rho$  was specified in the problem statement, and the long equation was used to determine the required dimensions of the structure as represented by  $bd^2$ . Again, it is much easier to use the appropriate appendix table to determine this value. In nearly every other case in this textbook, the tables are used for design or analysis purposes.

Once the numerical value of  $bd^2$  is determined, the authors take what seems to be reasonable values for b (in this case 12 in., 14 in., and 16 in.) and compute the required d for each width so that the required  $bd^2$  is satisfied. Finally, a section is selected in which b is roughly  $\frac{1}{2}$  to  $\frac{2}{3}$  of d. (For long spans, d may be two and a half or three or more times b for economical reasons.)

#### Example 4.3

A beam is to be selected with  $\rho \approx 0.0120$ ,  $M_u = 600$  ft-k,  $f_v = 60,000$  psi, and  $f_c' = 4000$  psi.

#### SOLUTION

Assuming  $\phi = 0.90$  and substituting into the following equation from Section 3.4:

$$\frac{M_u}{\phi b d^2} = \rho f_y \left( 1 - \frac{1}{1.7} \frac{\rho f_y}{f_c'} \right)$$

$$\frac{(12 \text{ in/ft) } (600,000 \text{ ft-lb})}{(0.9) (bd^2)} = (0.0120) (60,000 \text{ psi}) \left[1 - \left(\frac{1}{1.7}\right) \frac{(0.0120) (60,000 \text{ psi})}{4000 \text{ psi}}\right]$$

$$bd^2 = 12,427 \text{ in.}^3 \begin{cases} b \times d \\ 12 \text{ in.} \times 32.18 \text{ in.} \\ 14 \text{ in.} \times 29.79 \text{ in.} \leftarrow \\ 16 \text{ in.} \times 27.87 \text{ in.} \end{cases}$$
This one seems pretty reasonable to the authors.

Note: Alternatively, we could have used tables to help calculate  $bd^2$ . Upon entering Appendix A, Table A.13, we find  $M_{\nu}/\phi b d^2 = 643.5$  psi when  $\rho = 0.0120$ .

$$\therefore bd^2 = \frac{(12 \text{ in/ft) } (600,000 \text{ ft-lb})}{(0.90) (643.5 \text{ psi})} = 12,432 \text{ in.}^3 \quad \underline{OK}$$

$$\underline{\text{Try 14 in.} \times 33 \text{ in. } (d = 30.00 \text{ in.})}$$

$$A_s = \rho bd = (0.0120) (14 \text{ in.}) (30 \text{ in.}) = 5.04 \text{ in.}^2$$

Use 4 #10 (
$$A_a = 5.06 \,\text{in}.^2$$

Note: Appendix A.5 indicates a minimum beam width of 12.9 in. for this bar selection. Since our width is 14 in., the bars will fit.

#### **Checking Solution**

$$\rho = \frac{A_s}{bd} = \frac{5.06 \text{ in.}^2}{(14 \text{ in.})(30 \text{ in.})} = 0.01205 > \rho_{\text{min}} = 0.0033$$
$$< \rho_{\text{max}} = 0.0181 \text{ (from Appendix A, Table A.7)}$$

*Note*: A value of  $\rho = 0.0206$  is permitted by the code, but the corresponding value of  $\phi$  would be less than 0.9 (see Figure 3.5 and Table A.7). Since a value of  $\phi$  of 0.9 was used in the above calculations, it is necessary to use a maximum value of  $\rho = 0.0181$ .

With  $\rho = 0.01205$ ,  $M_{\nu}/\phi b d^2$  by interpolation from Table A.13 equals 645.85.

$$\phi M_n = (645.85 \text{ psi}) (\phi b d^2) = (645.85 \text{ psi}) (0.9) (14 \text{ in.}) (30 \text{ in.})^2$$
  
= 7.323.939 in-lb = 610.3 ft-k > 600 ft-k

#### Final Section (Figure 4.3)

![](_page_111_Figure_13.jpeg)

**FIGURE 4.3** Final cross section for Example 4.3.

Through quite a few decades of reinforced concrete design experience, it has been found that if steel percentages are kept fairly small, say roughly  $0.18f_c'/f_y$  or perhaps  $0.375\rho_b$ , beam cross sections will be sufficiently large so that deflections will seldom be a problem. As the areas of steel required will be fairly small, there will be little problem fitting them into beams without crowding.

If these relatively small percentages of steel are used, there will be little difficulty in placing the bars and in getting the concrete between them. Of course, from the standpoint of deflection, higher percentages of steel, and thus smaller beams, can be used for short spans where deflections present no problem. Whatever steel percentages are used, the resulting members will have to be carefully checked for deflections, particularly for long-span beams, cantilever beams, and shallow beams and slabs. Of course, such deflection checks are not required if the minimum depths specified in Table 4.1 of this chapter are met.

Another reason for using smaller percentages of steel is given in ACI Section 8.4, where a plastic redistribution of moments (a subject to be discussed in Chapter 14) is permitted in continuous members whose  $\epsilon_t$  values are 0.0075 or greater. Such tensile strains will occur when smaller percentages of steel are used. For the several reasons mentioned here, structural designers believe that keeping steel percentages fairly low will result in good economy.

#### Example 4.4

A rectangular beam is to be sized with  $f_y=60{,}000$  psi,  $f_c'=3000$  psi, and a  $\rho$  approximately equal to  $0.18f_c'/f_y$ . It is to have a 25-ft simple span and to support a dead load, in addition to its own weight, equal to 2 k/ft and a live load equal to 3 k/ft.

#### **SOLUTION**

Assume Beam wt = 400 lb/ft

$$\begin{split} w_u &= (1.2) \, (2 \text{ klf} + 0.400 \text{ klf}) + (1.6) \, (3 \text{ klf}) = 7.68 \text{ klf} \, (\text{k/ft}) \\ M_u &= \frac{(7.68 \text{ klf}) \, (25 \text{ ft})^2}{8} = 600 \text{ ft-k} \\ \rho &= \frac{(0.18) \, (3 \text{ ksi})}{60 \text{ ksi}} = 0.009 \\ \frac{M_u}{\phi b d^2} &= 482.6 \text{ psi} \, (\text{from Appendix A, Table A.12}) \\ b d^2 &= \frac{M_u}{\phi (482.6 \text{ psi})} = \frac{(12 \text{ in/ft}) \, (600,000 \text{ ft-lb})}{(0.9) \, (482.6 \text{ psi})} \end{split}$$

Solving this expression for  $bd^2$  and trying varying values of b and d.

$$b \times d$$

$$bd^{2} = 16,577 \text{ in.}^{3} \begin{cases} 16 \text{ in.} \times 32.19 \text{ in.} \\ 18 \text{ in.} \times 30.35 \text{ in.} \end{cases} \leftarrow \text{ seems reasonable}$$

$$20 \text{ in.} \times 28.79 \text{ in.}$$

Try 18-in.  $\times$  33-in. Beam (d = 30.50 in.)

Bm wt = 
$$\frac{(18 \text{ in.})(33 \text{ in.})}{144 \text{ in}^2/\text{ft}^2} (150 \text{ lb/ft}^3) = 619 \text{ lb/ft}$$
  
> the estimated 400 lb/ft No good

#### Assume Beam wt a Little Higher Than 619 lb/ft

Estimate wt = 650 lb/ft 
$$w_u = (1.2) (2 \text{ klf} + 0.650 \text{ klf}) + (1.6) (3 \text{ klf}) = 7.98 \text{ klf}$$
 
$$M_u = \frac{(7.98 \text{ klf}) (25 \text{ ft})^2}{8} = 623.4 \text{ ft-k}$$
 
$$bd^2 = \frac{M_u}{\phi (482.6 \text{ psi})} = \frac{(12 \text{ in/ft}) (623,400 \text{ ft-lb})}{(0.9) (482.6 \text{ psi})}$$
 
$$= 17,223 \text{ in.}^3 \begin{cases} 16 \text{ in.} \times 32.81 \text{ in.} \\ 18 \text{ in.} \times 30.93 \text{ in.} & \leftarrow \text{ seems reasonable} \\ 20 \text{ in.} \times 29.35 \text{ in.} \end{cases}$$

Try 18-in.  $\times$  34-in. Beam (d = 31.00 in.)

Bm wt = 
$$\frac{(18 \text{ in.})(34 \text{ in.})}{144 \text{ in}^2/\text{ft}^2}$$
 (150 lb/ft<sup>3</sup>) = 637.5 lb/ft < 650 lb/ft OK  
 $A_0 = \rho bd = (0.009)(18 \text{ in.})(31 \text{ in.}) = 5.02 \text{ in.}^2$ 

Try five #9 bars (minimum width is 14.3 in. from Appendix A, Table A.5) OK

Normally a bar selection should exceed the theoretical value of  $A_s$ . In this case, the area chosen was less than, but very close to, the theoretical area, and it will be checked to be sure it has enough capacity.

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{5.00 \,\text{in.}^2 (60 \,\text{ksi})}{(0.85) \,(3 \,\text{ksi}) \,(18 \,\text{in.})} = 6.54 \,\text{in.}$$

$$\phi M_n = \phi A_s f_y \left( d - \frac{a}{2} \right) = 0.9 (5.00 \,\text{in.}^2) \,(60 \,\text{ksi}) \,\left( 31 \,\text{in.} - \frac{6.54 \,\text{in.}}{2} \right)$$

$$= 7487.6 \,\text{in-lb} = 623.9 \,\text{ft-k} > M_u$$

The reason a beam with less reinforcing steel than calculated is acceptable is that a value of d exceeding the theoretical value was selected (d = 31 in. > 30.93 in.). Whenever the value of b and d selected results in a  $bd^2$  that exceeds the calculated value based on the assumed  $\rho$ , the actual value of  $\rho$  will be lower than the assumed value.

If a value of b = 18 in. and d = 30 in. had been selected, the result would have been that the actual value of  $\rho$  would be greater than the assumed value of 0.009. Using the actual values of b and d to recalculate  $\rho$ 

$$\frac{M_u}{\phi b d^2} = \frac{\text{(12 in/ft) (623,400 ft-lb)}}{\text{(0.9) (18 in.) (30 in.)}^2} = 513.1 \text{ psi}$$

From Appendix A, Table A.12,  $\rho = 0.00965$ , which exceeds the assumed value of 0.009. The required value of  $A_s$  will be larger than that required for d=31 in.

$$A_s = \rho bd = (0.00965) (18 \text{ in.}) (30 \text{ in.}) = 5.21 \text{ in.}^2$$
 (Use 7 #8 bars,  $A_s = 5.50 \text{ in.}^2$ )

Either design is acceptable. This kind of flexibility is sometimes perplexing to the student who simply wants to know the right answer. One of the best features of reinforced concrete is that there is so much flexibility in the choices that can be made.

### **4.4 Miscellaneous Beam Considerations**

This section introduces two general limitations relating to beam design: lateral bracing and deep beams.

### **Lateral Support**

It is unlikely that laterally unbraced reinforced concrete beams of any normal proportions will buckle laterally, even if they are deep and narrow, unless they are subject to appreciable lateral torsion. As a result, the ACI Code (10.4.1) states that lateral bracing for a beam is not required closer than 50 times the least width, *b*, of the compression flange or face. Should appreciable torsion be present, however, it must be considered in determining the maximum spacing for lateral support.

### **Skin Reinforcement for Deep Beams**

Beams with web depths that exceed 3 ft have a tendency to develop excessively wide cracks in the upper parts of their tension zones. To reduce these cracks, it is necessary to add some additional longitudinal reinforcing in the zone of flexural tension near the vertical side faces of their webs, as shown in Figure 4.4. The code (10.6.7) states that additional skin reinforcement must be uniformly distributed along both side faces of members with *h*> 36 in. for distances equal to *h*/2 nearest the flexural reinforcing.

The spacing, *s*, between this skin reinforcement shall be as provided in ACI 10.6.4. These additional bars may be used in computing the bending strengths of members only if appropriate strains for their positions relative to neutral axes are used to determine bar stresses. The total area of the skin reinforcement in both side faces of the beam does not have to exceed one-half of the required bending tensile reinforcement in the beam. The ACI does not specify the actual area of skin reinforcing; it merely states that some additional reinforcement should be placed near the vertical faces of the tension zone to prevent cracking in the beam webs.

Some special requirements must be considered relating to shear in deep beams, as described in the ACI Code (11.7) and in Section 8.14 of this text. Should these latter provisions require more reinforcing than required by ACI Section 10.6.7, the larger values will govern.

For a beam designed in SI units with an effective depth > 1 m, additional skin reinforcement must be determined with the following expression, in which *Ask* is the area of skin reinforcement per meter of height on each side of the beam:

Its maximum spacing may not exceed *d*/6 on 300 mm or 1000*Ab*/(*d*− 750).

![](_page_114_Figure_12.jpeg)

**FI GU RE 4.4** Skin reinforcement for deep beams with *h* > 36 in., as required by ACI Code Section 10.6.7.

#### Other Items

The next four chapters of this book are devoted to several other important items relating to beams. These include different shaped beams, compression reinforcing, cracks, bar development lengths, and shear.

#### Further Notes on Beam Sizes

From the standpoints of economy and appearance, only a few different sizes of beams should be used in a particular floor system. Such a practice will save appreciable amounts of money by simplifying the formwork and at the same time will provide a floor system that has a more uniform and attractive appearance.

If a group of college students studying the subject of reinforced concrete were to design a floor system and then compare their work with a design of the same floor system made by an experienced structural designer, the odds are that the major difference between the two designs would be in the number of beam sizes. The practicing designer would probably use only a few different sizes, whereas the average student would probably use a larger number.

The designer would probably examine the building layout to decide where to place the beams and then would make the beam subject to the largest bending moment as small as practically possible (i.e., with a fairly high percentage of reinforcing). Then he or she would proportion as many as possible of the other similar beams with the same outside dimensions. The reinforcing percentages of these latter beams might vary quite a bit because of their different moments.

#### 4.5 **Determining Steel Area When Beam Dimensions Are Predetermined**

Sometimes the external dimensions of a beam are predetermined by factors other than moments and shears. The depth of a member may have been selected on the basis of the minimum thickness requirements discussed in Section 4.2 for deflections. The size of a whole group of beams may have been selected to simplify the formwork, as discussed in Section 4.4. Finally, a specific size may have been chosen for architectural reasons. Next we briefly mention three methods for computing the reinforcing required. Example 4.5 illustrates the application of each of these methods.

#### **Appendix Tables**

The value of  $M_u/\phi bd^2$  can be computed, and  $\rho$  can be selected from the tables. For most situations this is the quickest and most practical method. The tables given in Appendices A and B of this text apply only to tensilely reinforced rectangular sections. Furthermore, we must remember to check  $\phi$  values.

#### Use of $\rho$ Formula

The following equation was previously developed in Section 3.4 for rectangular sections.

$$\rho = \frac{0.85f_c'}{f_y} \left( 1 - \sqrt{1 - \frac{2R_n}{0.85f_c'}} \right)$$

#### **Trial-and-Error (Iterative) Method**

A value of a can be assumed, the value of  $A_s$  computed, the value of a determined for that value of  $A_s$ , another value of a calculated, and so on. Alternatively, a value of the lever arm from C to T (it's d-a/2 for rectangular sections) can be estimated and used in the trial-and-error procedure. This method is a general one that will work for all cross sections with tensile reinforcing. It is particularly useful for T beams, as will be illustrated in the next chapter.

#### Example 4.5

The dimensions of the beam shown in Figure 4.5 have been selected for architectural reasons. Determine the reinforcing steel area by each of the methods described in this section.

#### SOLUTION

#### **Using Appendix Tables**

$$\frac{M_u}{\phi b d^2} = \frac{(12 \text{ in/ft}) (160,000 \text{ ft-lb})}{(0.9) (16 \text{ in.}) (21 \text{ in.})^2} = 302.3 \text{ psi}$$
 
$$\rho \text{ (from Appendix A, Table A.12)} = 0.00538 \text{ (by interpolation)}$$
 
$$A_s = (0.00538) (16 \text{ in.}) (21 \text{ in.}) = 1.81 \text{ in.}^2$$
 Use 6 #5 bars (1.84 in.²)

#### Using $\rho$ Formula

$$R_n = \frac{M_u}{\phi b d^2} = 302.3 \text{ psi}$$

$$\rho = \frac{(0.85) (3000 \text{ psi})}{60,000 \text{ psi}} \left[ 1 - \sqrt{1 - \frac{(2) (302.3 \text{ psi})}{(0.85) (3000 \text{ psi})}} \right]$$

$$= 0.00538 \quad \text{(same as obtained from Appendix A)}$$

#### Trial-and-Error (Iterative) Method

Here it is necessary to estimate the value of a. The student probably has no idea of a reasonable value for this quantity, but the accuracy of the estimate is not a matter of importance. He or she can assume some value probably considerably less than d/2 and then compute d-a/2 and  $A_s$ . With this value of  $A_s$ , a new value of a can be computed and the cycle repeated. After two or three cycles, a very good value of a will be obtained.

![](_page_116_Figure_13.jpeg)

**FIGURE 4.5** Beam cross section for Example 4.5.

Assume a = 2 in.:

$$A_s = \frac{M_u}{\phi f_y \left(d - \frac{a}{2}\right)} = \frac{(12 \text{ in/ft}) (160,000 \text{ ft-lb})}{(0.9) (60,000 \text{ psi}) \left(21 \text{ in.} - \frac{2 \text{ in.}}{2}\right)} = 1.78 \text{ in.}^2$$

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{(1.78 \text{ in.}^2) (60,000 \text{ psi})}{(0.85) (3000 \text{ psi}) (16 \text{ in.})} = 2.62 \text{ in.}$$

Assume a = 2.6 in.:

$$A_{s} = \frac{(12 \text{ in/ft}) (160,000 \text{ ft-lb})}{(0.9) (60,000 \text{ psi}) \left(21 \text{ in.} - \frac{2.62 \text{ in.}}{2}\right)} = 1.81 \text{ in.}^{2}$$

$$a = \frac{(1.81 \text{ in.}^{2}) (60,000 \text{ psi})}{(0.85) (3000 \text{ psi}) (16 \text{ in.})} = 2.66 \text{ in.} \quad \underline{\text{(close enough)}}$$

Based on this method, use a theoretical value of  $A_s = 1.81$  in.<sup>2</sup>

#### **Bundled Bars**

Sometimes when large amounts of steel reinforcing are required in a beam or column, it is very difficult to fit all the bars in the cross section. For such situations, groups of parallel bars may be bundled together. Up to four bars can be bundled, provided they are enclosed by stirrups or ties. The ACI Code (7.6.6.3) states that bars larger than #11 shall not be bundled in beams or girders. This is primarily because of crack control problems, a subject discussed in Chapter 6 of this text. That is, if the ACI crack control provisions are to be met, bars larger than #11 cannot practically be used. The AASHTO permits the use of two-, three-, and four-bar bundles for bars up through the #11 size. For bars larger than #11, however, AASHTO limits the bundles to two bars (AASHTO Sections 8.21.5 ASD and 5.10.3.1.5 strength design).

Typical configurations for two-, three-, and four-bar bundles are shown in Figure 4.6. When bundles of more than one bar deep vertically are used in the plane of bending, they may not practically be hooked or bent as a unit. If end hooks are required, it is preferable to stagger the hooks of the individual bars within the bundle.

Although the ACI permits the use of bundled bars, their use in the tension areas of beams may very well be counterproductive because of the other applicable code restrictions that are brought into play as a result of their use.

When spacing limitations and cover requirements are based on bar sizes, the bundled bars may be treated as a single bar for computation purposes; the diameter of the fictitious bar is to be calculated from the total equivalent area of the group. When individual bars in a bundle are cut off within the span of beams or girders, they should terminate at different points. The code (7.6.6.4) requires that there be a stagger of at least 40 bar diameters.

![](_page_117_Picture_12.jpeg)

### **4.7 One-Way Slabs**

Reinforced concrete slabs are large flat plates that are supported by reinforced concrete beams, walls, or columns; by masonry walls; by structural steel beams or columns; or by the ground. If they are supported on two opposite sides only, they are referred to as *one-way slabs* because the bending is in one direction only—that is, perpendicular to the supported edges. Should the slab be supported by beams on all four edges, it is referred to as a *two-way slab* because the bending is in both directions. Actually, if a rectangular slab is supported on all four sides, but the long side is two or more times as long as the short side, the slab will, for all practical purposes, act as a one-way slab, with bending primarily occurring in the short direction. Such slabs are designed as one-way slabs. You can easily verify these bending moment ideas by supporting a sheet of paper on two opposite sides or on four sides with the support situation described. This section is concerned with one-way slabs; two-way slabs are considered in Chapters 16 and 17. It should be realized that a large percentage of reinforced concrete slabs fall into the one-way class.

A one-way slab is assumed to be a rectangular beam with a large ratio of width to depth. Normally, a 12-in.-wide piece of such a slab is designed as a beam (see Figure 4.7), the slab being assumed to consist of a series of such beams side by side. The method of analysis is somewhat conservative because of the lateral restraint provided by the adjacent parts of the slab. Normally, a beam will tend to expand laterally somewhat as it bends, but this tendency to expand by each of the 12-in. strips is resisted by the adjacent 12-in.-wide strips, which tend to expand also. In other words, Poisson's ratio is assumed to be zero. Actually, the lateral expansion tendency results in a very slight stiffening of the beam strips, which is neglected in the design procedure used here.

The 12-in.-wide beam is quite convenient when thinking of the load calculations because loads are normally specified as so many pounds per square foot, and thus the load carried per foot of length of the 12-in.-wide beam is the load supported per square foot by the slab. The load supported by the one-way slab, including its own weight, is transferred to the members supporting the edges of the slab. Obviously, the reinforcing for flexure is placed perpendicular to these supports—that is, parallel to the long direction of the 12-in.-wide beams. This flexural reinforcing may not be spaced farther on center than three times the slab thickness, or 18 in., according to the ACI Code (7.6.5). Of course, there will be some reinforcing placed in the other direction to resist shrinkage and temperature stresses.

![](_page_118_Figure_6.jpeg)

**FI GU RE 4.7** A 12-in. strip in a simply supported one-way slab.

The thickness required for a particular one-way slab depends on the bending, the deflection, and shear requirements. As described in Section 4.2, the ACI Code (9.5.2.1) provides certain span/depth limitations for concrete flexural members where deflections are not calculated.

Because of the quantities of concrete involved in floor slabs, their depths are rounded off to closer values than are used for beam depths. Slab thicknesses are usually rounded off to the nearest  $\frac{1}{4}$  in. on the high side for slabs of 6 in. or less in thickness and to the nearest  $\frac{1}{2}$  in. on the high side for slabs thicker than 6 in.

As concrete hardens, it shrinks. In addition, temperature changes occur that cause expansion and contraction of the concrete. When cooling occurs, the shrinkage effect and the shortening due to cooling add together. The code (7.12) states that shrinkage and temperature reinforcement must be provided in a direction perpendicular to the main reinforcement for one-way slabs. (For two-way slabs, reinforcement is provided in both directions for bending.) The code states that for Grade 40 or 50 deformed bars, the minimum percentage of this steel is 0.002 times the gross cross-sectional area of the slab. Notice that the gross cross-sectional area is bh (where h is the slab thickness). The code (7.12.2.2) states that shrinkage and temperature reinforcement may not be spaced farther apart than five times the slab thickness, or 18 in. When Grade 60 deformed bars or welded wire fabric is used, the minimum area is 0.0018bh. For slabs with  $f_v > 60,000$  psi, the minimum value is  $(0.0018 \times 60,000)/f_v \ge 0.0014$ .

In SI units, the minimum percentages of reinforcing are 0.002 for Grades 300 and 350 steels and 0.0018 for Grade 420 steel. When  $f_v > 420$  MPa, the minimum percentage equals  $(0.0018 \times 420)/f_v$ . The reinforcing may not be spaced farther apart than five times the slab thickness, or 500 mm.

Should structural walls or large columns provide appreciable resistance to shrinkage and temperature movements, it may very well be necessary to increase the minimum amounts listed.

Shrinkage and temperature steel serves as mat steel in that it is tied perpendicular to the main flexural reinforcing and holds it firmly in place as a mat. This steel also helps to distribute concentrated loads transversely in the slab. (In a similar manner, the AASHTO gives minimum permissible amounts of reinforcing in slabs transverse to the main flexural reinforcing for lateral distribution of wheel loads.)

Areas of steel are often determined for 1-ft widths of reinforced concrete slabs, footings, and walls. A table of areas of bars in slabs such as Appendix A, Table A.6 is very useful in such cases for selecting the specific bars to be used. A brief explanation of the preparation of this table is provided here.

For a 1 ft width of concrete, the total steel area obviously equals the total or average number of bars in a 1-ft width times the cross-sectional area of one bar. This can be expressed as (12 in./bar spacing c. to c.)(area of 1 bar). Some examples follow, and the values obtained can be checked in the table. Understanding these calculations enables one to expand the table as desired.

- **1.** #9 bars, 6-in. o.c. total area in 1-ft width =  $\left(\frac{12}{6}\right)$  (1.00) = 2.00 in.<sup>2</sup>
- **2.** #9 bars, 5-in. o.c. total area in 1-ft width =  $\left(\frac{12}{5}\right)$  (1.00) = 2.40 in.<sup>2</sup>

Example 4.6 illustrates the design of a one-way slab. It will be noted that the code (7.7.1.c) cover requirement for reinforcement in slabs (#11 and smaller bars) is  $\frac{3}{4}$  in. clear, unless corrosion or fire protection requirements are more severe.

#### Example 4.6

Design a one-way slab for the inside of a building using the span, loads, and other data given in Figure 4.8. Normal-weight aggregate concrete is specified with a density of 145 pcf.

#### SOLUTION

Minimum Total Slab Thickness h If Deflections Are Not Computed (See Table 4.1)

$$h = \frac{\ell}{20} = \frac{\text{(12 in/ft) (10 ft)}}{20} = 6 \text{ in.}$$

Assume 6-in. slab (with  $d = \text{approximately 6 in.} - \frac{3}{4} \text{ in. Cover } -\frac{1}{4} \text{ in. for estimated half-diameter of bar size} = 5.0 in.)$ . The moment is calculated, and then the amount of steel required is determined. If this value seems unreasonable, a different thickness is tried.

Design a 12-in.-wide strip of the slab. Thus, b=12 in., and the load on the slab in units of lb/ft<sup>2</sup> becomes lb/ft. Usually 5 pcf is added to account for the weight of reinforcement, so 150 pcf is used in calculating the weight of a normal-weight concrete member.

$$DL = \text{slab wt} = \left(\frac{6 \text{ in.}}{12 \text{ in/ft}}\right) (150 \text{ pcf}) = 75 \text{ psf}$$

$$LL = 200 \text{ psf}$$

$$w_u = (1.2) (75 \text{ psf}) + (1.6) (200 \text{ psf}) = 410 \text{ psf}$$

$$M_u = \frac{(0.410 \text{ klf}) (10 \text{ ft})^2}{8} = 5.125 \text{ ft-k}$$

$$\frac{M_u}{\phi b d^2} = \frac{(12 \text{ in/ft}) (5125 \text{ ft-lb})}{(0.9) (12 \text{ in.}) (5.00 \text{ in.})^2} = 227.8 \text{ psi}$$

$$\rho = 0.00393 \text{ (from Appendix A, Table A.13)}$$

$$\rho_{\text{min}} = 0.0033$$

$$A_s = \rho b d = (0.00393) (12 \text{ in.}) (5.0 \text{ in.}) = 0.236 \text{ in}^2/\text{ft}$$

Use #4 @ 10 in. from Table A.6 ( $A_s = 0.24 \text{ in}^2/\text{ft}$ )

Spacing < maximum of 18 in. as per ACI 7.6.5

#### Transverse Direction - Shrinkage and Temperature Steel

$$A_s = 0.0018bd = (0.0018)(12 \text{ in.})(6 \text{ in.}) = 0.1296 \text{ in}^2/\text{ft}$$

Use #3 @ 10 in. (0.13 in<sup>2</sup>/ft) as selected from Table A.6

The #4 bars are placed below the #3 bars in this case. The #4 bars are the primary flexural reinforcing, and the value of *d* is based on this assumption. The #3 bars are for temperature and shrinkage control, and their depth within the slab is not as critical.

![](_page_120_Figure_17.jpeg)

**FIGURE 4.8** Given information for Example 4.6.

The designers of reinforced concrete structures must be very careful to comply with building code requirements for fire resistance. If the applicable code requires a certain fire resistance rating for floor systems, that requirement may very well cause the designer to use thicker slabs than might otherwise be required to meet the ACI strength design requirements. *In other words, the designer of a building should study carefully the fire resistance provisions of the governing building code before proceeding with the design*. Section 7.7.8 of ACI 318-11 includes such a requirement.

### **4.8 Cantilever Beams and Continuous Beams**

Cantilever beams supporting gravity loads are subject to negative moments throughout their lengths. As a result, their reinforcement is placed in their top or tensile sides, as shown in Figures 4.9 and 4.10(a). The reader will note that for such members the maximum moments occur at the faces of the fixed supports. As a result, the largest amounts of reinforcing are required at those points. You should also note that the bars cannot be stopped at the support faces. They must be extended or anchored in the concrete beyond the support face. We will later call this development length. The *development length* does not have to be straight as shown in the figure, because the bars may be hooked at 90◦ or 180◦ . Development lengths and hooked bars are discussed in depth in Chapter 7.

Up to this point, only statically determinate members have been considered. The very common situation, however, is for beams and slabs to be continuous over several supports, as shown in Figure 4.10. Because reinforcing is needed on the tensile sides of the beams, we will place it in the bottoms when we have positive moments and in the tops when we have negative moments. There are several ways in which the reinforcing bars can be arranged to resist the positive and negative moments in continuous members. One possible arrangement is shown in Figure 4.10(a). These members, including bar arrangements, are discussed in detail in Chapter 14.

![](_page_121_Figure_6.jpeg)

**FI GU RE 4.10** Continuous slab showing theoretical placement of bars for given moment diagram.

![](_page_122_Picture_2.jpeg)

Workers pour the first concrete of the new clubhouse during the TPC Sawgrass renovation (May 10, 2006).

### 4.9 SI Example

Example 4.7 illustrates the design of a beam using SI units.

#### Example 4.7

Design a rectangular beam for a 10-m simple span to support a dead load of 20 kN/m (not including beam weight) and a live load of 30 kN/m. Use  $\rho=0.5\rho_b$ ,  $f_c'=28\,\mathrm{MPa}$ , and  $f_y=420\,\mathrm{MPa}$ , and concrete weight is 23.5 kN/m³. Do not use the ACI thickness limitation.

#### SOLUTION

Assume that the beam weight is 10 kN/m and  $\phi = 0.90$ .

$$\begin{split} w_u &= (1.2) \, (30 \text{ kN/m}) + (1.6) \, (30 \text{ kN/m}) = 84 \text{ kN/m} \\ M_u &= \frac{(84 \text{ kN/m}) \, (10 \text{ m})^2}{8} = 1050 \text{ kN·m} \\ \rho &= \left(\frac{1}{2}\right) (0.0283) = 0.01415 \, (\text{from Appendix B, Table B.7}) \\ M_u &= \phi \rho f_y b d^2 \left(1 - \frac{1}{1.7} \rho \frac{f_y}{f_c'}\right) \end{split}$$

$$(10^6)\,(1050\;\text{kN}\cdot\text{m}) = (0.9)\,(0.01415)\,(420\;\text{MPa})\,(bd^{\;2}) \left[1\;-\;\left(\frac{1}{1.7}\right)\,(0.01415)\left(\frac{420\;\text{MPa}}{28\;\text{MPa}}\right)\right]$$

$$bd^{2} = 2.2432 \times 10^{8} \,\text{mm}^{3} \begin{cases} 400 \,\text{mm} \times 749 \,\text{mm} \\ 450 \,\text{mm} \times 706 \,\text{mm} \\ 500 \,\text{mm} \times 670 \,\text{mm} \leftarrow 670 \,\text{mm} \end{cases}$$

#### Use 500-mm $\times$ 800-mm Section (d = 680 mm)

Beam wt = 
$$\frac{(500 \text{ mm}) (800 \text{ mm})}{10^6 \text{ mm}^2/\text{m}^2} (23.5 \text{ kN/m}^3) = 9.4 \text{ kN/m}$$
< 10 kN/m assumed

 $A_s = (0.01415) (500 \text{ mm}) (680 \text{ mm}) = 4811 \text{ mm}^2$  OF

Use six #32 bars in two rows (4914 mm<sup>2</sup>). One row could be used here.

$$a = \frac{A_s f_y}{0.85 f_c' b} = \frac{(4914 \text{ mm}^2) (420 \text{ MPa})}{(0.85) (28 \text{ MPa}) (500 \text{ mm})} = 173 \text{ mm}$$

$$c = \frac{a}{\beta_1} = \frac{173 \text{ mm}}{0.85} = 204 \text{ mm}$$

$$\epsilon_t = \frac{680 \text{ mm} - 204 \text{ mm}}{204 \text{ mm}} (0.003) = 0.0070 > 0.005$$

$$\underline{\cdot \cdot \phi} = 0.900$$

*Note*: Can more easily be checked with  $\rho$  values.

$$b_{\rm min} =$$
 267 mm (from Appendix B, Table B.5 for three bars in a layer)  $<$  500 mm  $\,$  OK

The final section is shown in Figure 4.11.

Note: This problem can be solved more quickly by making use of the Appendix tables. In Table B.9 with  $f_V = 420$  MPa,  $f_C' = 28$  MPa, and  $\rho = 0.01415$ .

$$\frac{M_u}{\phi b d^2} = 5.201 \,\text{MPa}$$
 (by interpolation)  
 $bd^2 = \frac{M_u}{\phi(5.201 \,\text{MPa})} = \frac{(1050 \,\text{kN} \cdot \text{m})(10)^3}{(0.9)(5.201 \,\text{MPa})} = 2.2432 \times 10^8 \,\text{mm}^3$ 

After this step, proceed as shown above, when bd<sup>2</sup> was found using equations.

![](_page_123_Figure_12.jpeg)

**FIGURE 4.11** Beam cross section for Example 4.7.

### **4.10 Computer Example**

#### Example 4.8

Repeat Example 4.4 using the Excel spreadsheet for Chapter 4.

#### **SOLUTION**

Use the worksheet called Beam Design. Enter material properties (*f <sup>c</sup>*, *fy*) and *Mu* (can be taken from the bottom part of the spreadsheet or just entered if you already know it). Input ρ = 0.009 (given in the example). The two tables with headings *b* and *d* give some choices for *b* and *d* based on the ρ value you picked. Larger assumed values of ρ result in smaller values of *b* and *d* and vice versa. Select *b* = 18 in. and *d* = 31 in. (many other choices are also correct). Add 2.5 in. or more to *d* to get *h*, and enter that value (used only to find beam weight below). The spreadsheet recalculates ρ and *As* from actual values of *b* and *d* chosen, so note that ρ is not the same as originally assumed (0.00895 instead of 0.009). This results in a slightly smaller calculated steel area than in Example 4.4. You can also enter the number of bars and size to get a value for *As*. This value must exceed the theoretical value or an error message will appear. You should check to see if this bar selection will fit within the width selected.

At the bottom of the spreadsheet, the design moment *Mu* can be obtained if the beam is simply supported and uniformly loaded with only dead and live loads. The beam self-weight is calculated based on the input values for *b* and *h* (Cells D23 and D25). You may have to iterate a few times before these values all agree. In this example, the dead load is 2 klf plus self-weight. The input value for *wD* is 2.0 + 0.65 plf, with the second term being taken from the spreadsheet. In working this problem the first time, you probably would not have these dimensions for *b* and *h*, hence the self-weight would not be correct. Iteration as done in Example 4.4 is also required with the spreadsheet, although it is much faster.

#### Design of singly reinforced rectangular beams

$$f'_c = 3$$
 ksi  
 $f_y = 60$  ksi  
 $\beta_1 = 0.85$   
 $M_u = 623.4$  ft-k

*Instructions***: Enter values only in cells that are highlighted in yellow. Other values calculated from those input values.**

Assume 
$$\rho = 0.009$$

$$bd^2 = \frac{M_u}{\phi f_y \rho \frac{1 - \rho f_y}{1.7 f_c'}} = 17,215 \text{ in.}^3$$

| R = d⏐R                                               | R           | b                | d     |                          | b                 | d                              |             |
|-------------------------------------------------------|-------------|------------------|-------|--------------------------|-------------------|--------------------------------|-------------|
|                                                       | 1           | 25.82            | 25.82 |                          | 14                | 35.07                          |             |
|                                                       | 1.2         | 22.86            | 27.44 |                          | 15                | 33.88                          |             |
|                                                       | 1.4         | 20.63            | 28.88 |                          | 16                | 32.80                          |             |
|                                                       | 1.5         | 19.70            | 29.56 |                          | 17                | 31.82                          |             |
|                                                       | 1.6         | 18.87            | 30.20 |                          | 18                | 30.93                          |             |
|                                                       | 1.7         | 18.13            | 30.82 |                          | 19                | 30.10                          |             |
|                                                       | 1.8         | 17.45            | 31.41 |                          | 20                | 29.34                          |             |
|                                                       | 1.9         | 16.83            | 31.98 |                          | 21                | 28.63                          |             |
|                                                       | 2           | 16.27            | 32.53 |                          | 22                | 27.97                          |             |
|                                                       |             |                  |       |                          |                   |                                |             |
| Select b and d                                        | b =         | 18 in.           |       |                          |                   |                                |             |
|                                                       | d =         | 31 in.           |       |                          |                   | These tables give some choices |             |
|                                                       | h =         | 34 in.           |       |                          |                   | for b and d that you may round |             |
|                                                       | Rn<br>=     | 480.5            |       |                          | up to enter here. |                                |             |
| 1– [1–2Rn⏐(.85f'c)]0.5<br>r = 0.85f'c⏐fy<br>= 0.00895 |             |                  |       |                          |                   |                                |             |
| As = rbd = 4.99 in.2                                  |             |                  |       | < theoretical steel area |                   |                                |             |
|                                                       | select bars | No. of bars<br>5 |       |                          | Bar size<br># 9   | —<br>As                        | = 5.00 in.2 |
|                                                       |             |                  |       |                          |                   |                                |             |

#### **Calculation of** *Mu* **for simply supported beam with** *D* **and** *L* **uniformly distributed loads**

| wD =      | 2.65   | klf  |
|-----------|--------|------|
| wL =      | 3      | klf  |
| span =    | 25     | ft   |
| wu<br>=   | 7.980  | klf  |
| Mu =      | 623.4  | ft-k |
| γc =      | 145    | pcf  |
| self wt = | 0.6375 | klf  |

#### **PROBLEMS**

**Problem 4.1** The estimated service or working axial loads and bending moments for a particular column are as follows: *PD* = 100 k, *PL* = 40 k, *MD* = 30 ft-k, and *ML* = 16 ft-k. Compute the axial load and moment values that must be used in the design. (*Ans. Pu* = 184 k, *Mu* = 61.6 ft-k)

**Problem 4.2** Determine the required design strength for a column for which *PD* = 120 k, *PL* = 40 k, and wind *PW* = 60 k compression or 80 k tension.

**Problem 4.3** A reinforced concrete slab must support a dead working floor load of 80 psf, which includes the weight of the concrete slab and a live working load of 40 psf. Determine the factored uniform load for which the slab must be designed. (*Ans. wu* = 160 psf)

**Problem 4.4** Using the Chapter 4 spreadsheet, Load Combination worksheet, repeat the following problems:

- **(a)** Problem 4.1
- **(b)** Problem 4.2
- **(c)** Problem 4.3

For Problems 4.5 to 4.9, design rectangular sections for the beams, loads, and values given. Beam weights are not included in the given loads. Show sketches of beam cross sections, including bar sizes, arrangement, and spacing. Assume concrete weighs  $150 \text{ lb/ft}^3$ . Use h = d + 2.5 in.

![](_page_126_Picture_2.jpeg)

| Problem |             | 2/ ( )      | G 4 (0)     |                                | a. (a.)               |                       |
|---------|-------------|-------------|-------------|--------------------------------|-----------------------|-----------------------|
| No.     | $f_y$ (psi) | $f_c'(psi)$ | Span ℓ (ft) | $w_D$ not incl. beam wt (k/ft) | w <sub>L</sub> (k/ft) | ρ*                    |
| 4.5     | 60,000      | 4000        | 30          | 2                              | 1                     | $0.18f_c'/f_y$        |
| 4.6     | 60,000      | 4000        | 30          | 2                              | 2                     | $0.18f_c'/f_y$        |
| 4.7     | 50,000      | 3000        | 18          | 3                              | 4                     | $\frac{1}{2}\rho_b$   |
| 4.8     | 60,000      | 4000        | 32          | 2                              | 1.8                   | $\frac{1}{2}\rho_b$   |
| 4.9     | 60,000      | 3000        | 25          | 1.8                            | 1.5                   | $\epsilon_t = 0.0075$ |

\*See Appendix A, Table A.7 for  $\rho$  values that correspond to the  $\epsilon$ , values listed.

One ans. Problem 4.5: 16 in. × 29 in. with 4 #10 bars.

One ans. Problem 4.7: 16 in. × 28 in. with 4 #11 bars.

One ans. Problem 4.9: 18 in.  $\times$  26 in. with 6 #8 bars.

For Problems 4.10 to 4.22, design rectangular sections for the beams, loads, and  $\rho$  values shown. Beam weights are not included in the loads shown. Show sketches of cross sections, including bar sizes, arrangement, and spacing. Assume concrete weighs 150 lb/ft<sup>3</sup>,  $f_y=60{,}000$  psi, and  $f_c'=4000$  psi, unless given otherwise.

#### Problem 4.10

![](_page_126_Figure_10.jpeg)

**Problem 4.11** Repeat Problem 4.10, if  $w_D = 2$  k/ft and if  $P_L = 20$  k. (*One ans.* 14 in.  $\times$  28 in. with 3 #11 bars)

#### Problem 4.12

![](_page_126_Figure_13.jpeg)

**Problem 4.13** Repeat Problem 4.12 if  $w_D = 2.0$  k/ft and  $P_L = 20$  k. (*One ans.* 16 in.  $\times$  33 in. with 4 #11 bars)

#### Problem 4.14

![](_page_127_Figure_3.jpeg)

**Problem 4.15** Repeat Problem 4.14 if  $w_D = 3$  k/ft,  $P_L = 40 \text{ k}, f_c' = 3000 \text{ psi}, \text{ and } \rho = 0.5 \rho_b$ . (*One ans.* 18 in. × 37 in. with 5 #11 bars)

#### Problem 4.16

![](_page_127_Figure_6.jpeg)

**Problem 4.17** Repeat Problem 4.16 if the beam span = 12 ft. (One ans. 14 in.  $\times$  31 in. with 4 #10 bars in top)

#### Problem 4.18

![](_page_127_Figure_9.jpeg)

**Problem 4.19** Repeat Problem 4.18 if  $P_L = 20 \text{ k}$ ,  $\ell = 12 \text{ ft}$ , and  $\rho = \frac{1}{2}\rho_b$ . (One ans. 20 in.  $\times$  26 in. with 7 #9 in top)

#### Problem 4.20

![](_page_127_Figure_12.jpeg)

Problem 4.21 Select reinforcing bars for the beam shown if  $M_u = 250 \text{ ft-k}, f_v = 60,000 \text{ psi, and } f_c' = 4000 \text{ psi. (Hint: } f_c' = 4000 \text{ psi.})$ Assume that the distance from the c.g. of the tensile steel to the c.g. of the compression block equals 0.9 times the effective depth, d, of the beam.) After a steel area is computed, check the assumed distance and revise the steel area if necessary. Is  $\epsilon_t \ge 0.005$ ? (Ans.  $A_s = 2.84 \text{ in.}^2$ ,  $\epsilon_t = 0.00538 > 0.005$ )

![](_page_127_Figure_14.jpeg)

**Problem 4.22** Repeat Problem 4.21 for  $M_u = 150$  ft-k.

For Problems 4.23 and 4.24, design rectangular sections for the beams and loads shown. Beam weights are not included in the given loads.  $f_y = 60,000$  psi and  $f_c' = 4000$  psi. Live loads are to be placed where they will cause the most severe conditions at the sections being considered. Select beam size for the largest moment (positive or negative), and then select the steel required for maximum positive and negative moment. Finally, sketch the beam and show approximate bar locations.

**Problem 4.23** (One ans. 12 in. × 28 in. with 3 #10 bars negative reinforcement and 3 #9 bars positive reinforcement)

![](_page_128_Figure_3.jpeg)

Problem 4.24

![](_page_128_Figure_5.jpeg)

For Problems 4.25 and 4.26, design interior one-way slabs for the situations shown. Concrete weight=150 lb/ft<sup>3</sup>,  $f_y = 60,000$  psi, and  $f_c' = 4000$  psi. Do not use the ACI Code's minimum thickness for deflections (Table 4.1). Steel percentages are given in the figures. The only dead load is the weight of the slab.

**Problem 4.25** (*One ans.* 7.5-in. slab with #8 @ 9 in. main reinf.)

![](_page_128_Figure_8.jpeg)

Problem 4.26

![](_page_128_Figure_10.jpeg)

**Problem 4.27** Repeat Problem 4.25 using the ACI Code's minimum thickness requirement for cases where deflections are not computed (Table 4.1). Do not use the  $\rho$  given in Problem 4.26. (*Ans.* 14.5-in. slab with #6 @ 9 in. main reinf.)

**Problem 4.28** Using  $f_c' = 3000 \, \mathrm{psi}$ ,  $f_y = 60,000 \, \mathrm{psi}$ , and  $\rho$  corresponding to  $\epsilon_t = 0.005$ , determine the depth required for a simple beam to support itself for a 200-ft simple span.

**Problem 4.29** Determine the depth required for a beam to support itself only for a 100-ft span. Neglect concrete cover in self-weight calculations. Given  $f_c'=4000\,\mathrm{psi}, f_y=60,\!000\,\mathrm{psi},$  and  $\rho\cong0.5\,\rho_b$ . (Ans.  $d=32.5\,\mathrm{in.}$ )

**Problem 4.30** Determine the stem thickness for maximum moment for the retaining wall shown in the accompanying illustration. Also, determine the steel area required at the bottom and mid-depth of the stem if  $f_c' = 4000 \, \mathrm{psi}$  and  $f_y = 60,000 \, \mathrm{psi}$ . Assume that #8 bars are to be used and that the stem thickness is constant for the 18-ft height. Also, assume that the clear cover required is 2 in. and  $\rho = 0.5 \, \rho_h$ .

![](_page_128_Figure_15.jpeg)

![](_page_128_Figure_16.jpeg)

500 psf = asssumed lateral liquid pressure

\_

#### Problem 4.31

- (a) Design a 24-in.-wide precast concrete slab to support a 60-psf live load for a simple span of 15 ft. Assume minimum concrete cover required is  $\frac{5}{8}$  in. as per Section 7.7.3 of the code. Use welded wire fabric for reinforcing.  $f_y = 60,000 \text{ psi}, f_c' = 3000 \text{ psi}, \text{ and } \rho = 0.18 f_c'/f_y$ . (Ans. 4-in. slab with  $4 \times 8 \text{ D12/D6}$ )
- (b) Can a 300-lb football tackle walk across the center of the span when the other live load is not present? Assume 100% impact. (*Ans.* yes)

**Problem 4.32** Prepare a flow chart for the design of tensilely reinforced rectangular beams.

**Problem 4.33** Using the Chapter 4 spreadsheets, solve the following problems.

- (a) Problem 4.6. (Ans. 16 in. × 33 in. with 5 #10 bars)
- **(b)** Problem 4.18. (Ans. 18 in.  $\times$  39 in. with 8 #10 bars)

#### **Problems in SI Units**

For Problems 4.34 to 4.39, design rectangular sections for the beams, loads, and  $\rho$  values shown. Beam weights are not included in the loads given. Show sketches of cross sections including bar sizes, arrangements, and spacing. Assume concrete weighs 23.5 kN/m<sup>3</sup>.  $f_{\nu} = 420$  MPa and  $f_{c}' = 28$  MPa.

**Problem 4.35** (*One ans.* 450 mm  $\times$  890 mm with 6 #32 bars)

![](_page_129_Figure_11.jpeg)

#### Problem 4.34

![](_page_129_Figure_13.jpeg)

#### Problem 4.36

![](_page_129_Figure_15.jpeg)

**Problem 4.37** Place live loads to cause maximum positive and negative moments.  $\rho = 0.18 f_c^{\prime}/f_v$ . (One ans.  $450 \text{ mm} \times 900 \text{ mm}$  with 6 #32 bars positive reinf.)

![](_page_130_Figure_3.jpeg)

#### Problem 4.38

![](_page_130_Figure_5.jpeg)

Problem 4.39 Design the one-way slab shown in the accompanying figure to support a live load of 12 kN/m<sup>2</sup>. Do not use the ACI thickness limitation for deflections. Assume concrete weighs 23.5 kN/m³.  $f_c'=28$  MPa and  $f_y=420$  MPa. Use  $\rho=\rho_{\rm max}$ . (*One ans.* 240-mm slab with #25 @ 140-mm main steel)

![](_page_130_Figure_7.jpeg)

### **CHAPTER 5**

