# Shear and Diagonal Tension **CHAPTER 8**

### **8.1 Introduction**

As repeatedly mentioned earlier in this book, the objective of today's reinforced concrete designer is to produce ductile members that provide warning of impending failure. To achieve this goal, the code provides design shear values that have larger safety factors against shear failures than do those provided for bending failures. The failures of reinforced concrete beams in shear are quite different from their failures in bending. Shear failures occur suddenly with little or no advance warning. Therefore, beams are designed to fail in bending under loads that are appreciably smaller than those that would cause shear failures. As a result, those members will fail ductilely. They may crack and sag a great deal if overloaded, but they will not fall apart, as they might if shear failures were possible.

### **8.2 Shear Stresses in Concrete Beams**

Although no one has ever been able to accurately determine the resistance of concrete to pure shearing stress, the matter is not very important because pure shearing stress is probably never encountered in concrete structures. Furthermore, according to engineering mechanics, if pure shear is produced in a member, a principal tensile stress of equal magnitude will be produced on another plane. Because the tensile strength of concrete is less than its shearing strength, the concrete will fail in tension before its shearing strength is reached.

You have previously learned that in elastic homogeneous beams, where stresses are proportional to strains, two kinds of stresses occur (bending and shear), and they can be calculated with the following expressions:

$$f = \frac{Mc}{I}$$

$$v = \frac{VQ}{Ib}$$

An element of a beam not located at an extreme fiber or at the neutral axis is subject to both bending and shear stresses. These stresses combine into inclined compressive and tensile stresses, called *principal stresses*, which can be determined from the following expression:

$$f_p = \frac{f}{2} \pm \sqrt{\left(\frac{f}{2}\right)^2 + v^2}$$

The direction of the principal stresses can be determined with the formula to follow, in which α is the inclination of the stress to the beam's axis:

$$\tan 2\alpha = \frac{2\nu}{f}$$

![](_page_243_Picture_2.jpeg)

Iron grid.

Obviously, at different positions along the beam, the relative magnitudes of v and f change, and thus the directions of the principal stresses change. It can be seen from the preceding equation that at the neutral axis, the principal stresses will be located at a 45° angle with the horizontal.

You understand by this time that tension stresses in concrete are a serious matter. Diagonal principal tensile stresses, called diagonal tension, occur at different places and angles in concrete beams, and they must be carefully considered. If they reach certain values, additional reinforcing, called web reinforcing, must be supplied.

The discussion presented up to this point relating to diagonal tension applies rather well to plain concrete beams. If, however, reinforced concrete beams are being considered, the situation is quite different because the longitudinal bending tension stresses are resisted quite satisfactorily by the longitudinal reinforcing. These bars, however, do not provide significant resistance to the diagonal tension stresses.

### **Lightweight Concrete**

In the 2008 ACI 318 Code, the effect of lightweight aggregate concrete on shear strength was modified by the introduction of the term  $\lambda$  (see Section 1.12). This term was added to most equations containing  $\sqrt{f_c^i}$ . The resulting combined term,  $\lambda \sqrt{f_c^i}$ , appears throughout this chapter as well as in Chapter 7 on development length and Chapter 15 on torsion. If normalweight concrete is used, then  $\lambda$  is simply taken as 1. This unified approach to the effects of lightweight aggregate on the strength and other properties of concrete is a logical and simplifying improvement found in the 2008 ACI Code.

### 8.4 Shear Strength of Concrete

A great deal of research has been done on the subject of shear and diagonal tension for nonhomogeneous reinforced concrete beams, and many theories have been developed. Despite all this work and all the resulting theories, no one has been able to provide a clear explanation of the failure mechanism involved. As a result, design procedures are based primarily on test data.

If  $V_u$  is divided by the effective beam area,  $b_w d$ , the result is what is called an *average shearing stress*. This stress is not equal to the diagonal tension stress but merely serves as an indicator of its magnitude. Should this indicator exceed a certain value, shear or web reinforcing is considered necessary. In the ACI Code, the basic shear equations are presented in terms of shear forces, not shear stresses. In other words, the average shear stresses described in this paragraph are multiplied by the effective beam areas to obtain total shear forces.

For this discussion,  $V_n$  is considered to be the nominal or theoretical shear strength of a member. This strength is provided by the concrete and by the shear reinforcement.

$$V_n = V_c + V_s$$

The design shear strength of a member,  $\phi V_n$ , is equal to  $\phi V_c$  plus  $\phi V_s$ , which must at least equal the factored shear force to be taken,  $V_u$ 

$$V_{\mu} = \phi V_{c} + \phi V_{s}$$

The shear strength provided by the concrete,  $V_c$ , is considered to equal an average shear stress strength (normally  $2\lambda\sqrt{f_c'}$ ) times the effective cross-sectional area of the member,  $b_w d$ , where  $b_w$  is the width of a rectangular beam or of the web of a T beam or an I beam.

$$V_c = 2\lambda \sqrt{f_c'} b_w d$$
 (ACI Equation 11-3)

Or in SI units with  $f_c'$  in MPa

$$V_c = \left(\frac{\lambda\sqrt{f_c'}}{6}\right)b_w d$$

Beam tests have shown some interesting facts about the occurrence of cracks at different average shear stress values. For instance, where large moments occur even though appropriate longitudinal steel has been selected, extensive flexural cracks will be evident. As a result, the uncracked area of the beam cross section will be greatly reduced, and the nominal shear strength,  $V_c$ , can be as low as  $1.9\lambda\sqrt{f_c'}b_wd$ . In regions where the moment is small, however, the cross section will be either uncracked or slightly cracked, and a large portion of the cross section is available to resist shear. For such a case, tests show that a  $V_c$  of about  $3.5\lambda\sqrt{f_c'}b_wd$  can be developed before shear failure occurs.<sup>1</sup>

Based on this information, the code (11.2.1.1) suggests that, conservatively,  $V_c$  (the shear force that the concrete can resist without web reinforcing) can go as high as  $2\lambda\sqrt{f_c'}b_wd$ . As an alternative, the following shear force (from Section 11.2.1.2 of the code) may be used, which takes into account the effects of the longitudinal reinforcing and the moment and shear

<sup>&</sup>lt;sup>1</sup> ACI-ASCE Committee 326, 1962, "Shear and Diagonal Tension," part 2, *Journal ACI*, 59, p. 277.

magnitudes. This value must be calculated separately for each point being considered in the

$$V_c = \left(1.9\lambda\sqrt{f_c'} + 2500\rho_w \frac{V_u d}{M_u}\right) b_w d \le 3.5\lambda\sqrt{f_c'} b_w d \qquad (ACI Equation 11-5)$$

In SI units 
$$V_c = \left(\lambda\sqrt{f_c'} + 120\rho_w\frac{V_ud}{M_u}\right)\frac{b_wd}{7} \le 0.3\lambda\sqrt{f_c'}b_wd$$

In these expressions,  $\rho_w = A_s/b_w d$  and  $M_u$  are the factored moment occurring simultaneously with  $V_u$ , the factored shear at the section considered. The quantity  $V_u d/M_u$  cannot be taken to be greater than unity in computing  $V_c$  by means of the above expressions.

From these expressions, it can be seen that  $V_c$  increases as the amount of reinforcing (represented by  $\rho_w$ ) is increased. As the amount of steel is increased, the length and width of cracks will be reduced. If the cracks are kept narrower, more concrete is left to resist shear, and there will be closer contact between the concrete on opposite sides of the cracks. Hence there will be more resistance to shear by friction (called *aggregate interlock*) on the two sides of cracks.

Although this more complicated expression for  $V_c$  can easily be used for computer designs, it is quite tedious to apply when handheld calculators are used. The reason is that the values of  $\rho_w$ ,  $V_u$ , and  $M_u$  are constantly changing as we move along the span, requiring the computation of  $V_c$  at numerous positions. As a result, the alternate value  $2\lambda \sqrt{f_c'b_w}d$  is normally used. If the same member is to be constructed many times, the use of the more complex expression may be justified.

### **Shear Cracking of Reinforced Concrete Beams**

Inclined cracks can develop in the webs of reinforced concrete beams, either as extensions of flexural cracks or occasionally as independent cracks. The first of these two types is the flexure-shear crack, an example of which is shown in Figure 8.1. These are the ordinary types of shear cracks found in both prestressed and nonprestressed beams. For them to occur, the moment must be larger than the cracking moment, and the shear must be rather large. The cracks run at angles of about 45° with the beam axis and probably start at the top of a flexure crack. The approximately vertical flexure cracks shown are not dangerous unless a critical combination of shear stress and flexure stress occurs at the top of one of the flexure cracks.

Occasionally, an inclined crack will develop independently in a beam, even though no flexure cracks are in that locality. Such cracks, which are called web-shear cracks, will

![](_page_245_Figure_11.jpeg)

**FIGURE 8.1** Flexure—shear crack.

![](_page_246_Figure_2.jpeg)

**FI GU RE 8.2** Web–shear cracks.

sometimes occur in the webs of prestressed sections, particularly those with large flanges and thin webs. They also sometimes occur near the points of inflection of continuous beams or near simple supports. At such locations, small moments and high shear often occur. These types of cracks will form near the mid-depth of sections and will move on a diagonal path to the tension surface. Web–shear cracks are illustrated in Figure 8.2.

As a crack moves up to the neutral axis, the result will be a reduced amount of concrete left to resist shear—meaning that shear stresses will increase on the concrete above the crack.

It will be remembered that at the neutral axis, the bending stresses are zero, and the shear stresses are at their maximum values. The shear stresses will therefore determine what happens to the crack there.

After a crack has developed, the member will fail unless the cracked concrete section can resist the applied forces. If web reinforcing is not present, the items that are available to transfer the shear are as follows: (1) the shear resistance of the uncracked section above the crack (estimated to be 20% to 40% of the total resistance); (2) the aggregate interlock, that is, the friction developed due to the interlocking of the aggregate on the concrete surfaces on opposite sides of the crack (estimated to be 33% to 50% of the total); (3) the resistance of the longitudinal reinforcing to a frictional force, often called *dowel action* (estimated to be 15% to 25%); and (4) a tied-arch type of behavior that exists in rather deep beams produced by the longitudinal bars acting as the tie and by the uncracked concrete above and to the sides of the crack acting as the arch above.2

### **8.6 Web Reinforcement**

When the factored shear, *Vu* , is high, it shows that large cracks are going to occur unless some type of additional reinforcing is provided. This reinforcing usually takes the form of stirrups that enclose the longitudinal reinforcing along the faces of the beam. The most common stirrups are shaped, but they can be shaped or perhaps have only a single vertical prong, as shown in Figure 8.3(c). Multiple stirrups such as the ones shown in Figure 8.3(e) are considered to inhibit splitting in the plane of the longitudinal bars. As a consequence, they are generally more desirable for wide beams than the ones shown in Figure 8.3(d). Sometimes it is rather convenient to use lap spliced stirrups, such as the ones shown in Figure 8.3(g). These stirrups, which are described in ACI Section 12.13.5, are occasionally useful for deep members, particularly those with gradually varying depths. *However, they are considered to be unsatisfactory in seismic areas*.

Bars called *hangers* (usually with about the same diameter as that of the stirrups) are placed on the compression sides of beams to support the stirrups, as illustrated in

<sup>2</sup> Taylor, H. P. J., 1974, "The Fundamental Behavior of Reinforced Concrete Beams in Bending and Shear," *Shearin Reinforced Concrete*, Vol. 1, SP-42 (Detroit: American Concrete Institute), pp. 43–47.

(a) (b) (c) (d) (e) hangers Open stirrups for beams with negligible torsion (ACI 11.5.1)

Closed stirrups for beams with significant torsion (see ACI 11.5.2.1)

![](_page_247_Picture_4.jpeg)

**FI GU RE 8.3** Types of stirrups.

Figure 8.3(a) to (j). The stirrups are passed around the tensile steel and, to meet anchorage requirements, they are run as far into the compression side of the beam as practical and hooked around the hangers. Bending of the stirrups around the hangers reduces the bearing stresses under the hooks. If these bearing stresses are too high, the concrete will crush and the stirrups will tear out. When a significant amount of torsion is present in a member, it will be necessary to use closed stirrups as shown in parts (f) through (j) of Figure 8.3 and as discussed in Chapter 15.

The width of diagonal cracks is directly related to the strain in the stirrups. Consequently, the ACI 11.4.2 does not permit the design yield stress of the stirrups to exceed 60 ksi. This requirement limits the width of cracks that can develop. Such a result is important from the standpoint of both appearance and aggregate interlock. When the width of cracks is limited, it enables more aggregate interlock to develop. A further advantage of a limited yield stress is that the anchorage requirements at the top of the stirrups are not quite as stringent as they would be for stirrups with greater yield strengths.

The 60,000-psi limitation does not apply to deformed welded wire fabric because recent research has shown that the use of higher-strength wires has been quite satisfactory. Tests have shown that the width of inclined shear cracks at service load conditions is less for high-strength wire fabric than for those occurring in beams reinforced with deformed Grade 60 stirrups. The maximum stress permitted for deformed welded wire fabric is 80,000 psi (ACI 11.4.2).

In SI units, the maximum design yield stress values that may be used are 420 MPa for regular shear reinforcing and 550 MPa for welded deformed wire fabric.

#### 8.7 Behavior of Beams with Web Reinforcement

The actual behavior of beams with web reinforcement is not really understood, although several theories have been presented through the years. One theory, which has been widely used for 100 years, is the so-called truss analogy, wherein a reinforced concrete beam with shear reinforcing is said to behave much like a statically determinate parallel chord truss with pinned joints. The flexural compression concrete is thought of as the top chord of the truss, whereas the tensile reinforcing is said to be the bottom chord. The truss web is made up of stirrups acting as vertical tension members and pieces of concrete between the approximately 45° diagonal tension cracks acting as diagonal compression members.<sup>3,4</sup> The shear reinforcing used is similar in its action to the web members of a truss. For this reason, the term *web reinforcement* is used when referring to shear reinforcing. A "truss" of the type described here is shown in Figure 8.4.

Although the truss analogy has been used for many years to describe the behavior of reinforced concrete beams with web reinforcing, it does not accurately describe the manner in which shear forces are transmitted. For example, the web reinforcing does increase the shearing strength of a beam, but it has little to do with shear transfer in a beam before inclined cracks form.

The code requires web reinforcement for all major beams. In Section 11.4.6.1, a minimum area of web reinforcing is required for all concrete flexural members except (a) footings and solid slabs; (b) certain hollow-core units; (c) concrete floor joists; (d) shallow beams with h not more than 10 in.; (e) beams integral with slabs with h less than 24 in. and h not greater than the larger of two and a half times their flange thicknesses or one-half their web widths; or (f) beams constructed with steel fiber—reinforced, normal-weight concrete with  $f_c'$  not exceeding 6000 psi, h not greater than 24 in., and  $V_u$  not greater than  $2\phi\sqrt{f_c'}b_wd$ . Various tests have shown that shear failures do not occur before bending failures in shallow members. Shear forces are

![](_page_248_Figure_8.jpeg)

FIGURE 8.4 Truss analogy.

<sup>&</sup>lt;sup>3</sup> Ritter, W., 1899, "Die Bauweise Hennebique," Schweizerische Bauzeitung, Vol. 33, No. 7.

<sup>&</sup>lt;sup>4</sup> Mörsch, E., 1912, Der Eisenbetenbau, seine Theorie und Anwendung (Stuttgart: Verlag Konrad Wittwer).

![](_page_249_Picture_2.jpeg)

**FI GU RE 8.5** Bent-up bar web reinforcing.

distributed across these wide sections. For joists, the redistribution is via the slabs to adjacent joists. Hooked or crimped steel fibers in dosages ≥100 lb per cubic yard exhibit higher shear strengths in laboratory tests. However, use of such fibers is not recommended when the concrete is exposed to chlorides, such as deicing salts.

Inclined or diagonal stirrups lined up approximately with the principal stress directions are more efficient in carrying the shears and preventing or delaying the formation of diagonal cracks. Such stirrups, however, are not usually considered to be very practical in the United States because of the high labor costs required for positioning them. Actually, they can be rather practical for precast concrete beams where the bars and stirrups are preassembled into cages before being used and where the same beams are duplicated many times.

Bent-up bars (usually at 45◦ angles) are another satisfactory type of web reinforcing (see Figure 8.5). Although bent-up bars are commonly used in flexural members in the United States, the average designer seldom considers the fact that they can resist diagonal tension. Two reasons for not counting their contribution to diagonal tension resistance are that there are only a few, if any, bent-up bars in a beam and that they may not be conveniently located for use as web reinforcement.

Diagonal cracks will occur in beams with shear reinforcing at almost the same loads at which they occur in beams of the same size without shear reinforcing. The shear reinforcing makes its presence known only after the cracks begin to form. At that time, beams must have sufficient shear reinforcing to resist the shear force not resisted by the concrete.

After a shear crack has developed in a beam, only a little shear can be transferred across the crack unless web reinforcing is used to bridge the gap. When such reinforcing is present, it keeps the pieces of concrete on the two sides of the crack from separating. Several benefits result. These include:

- **1.** The steel reinforcing passing across the cracks carries shear directly.
- **2.** The reinforcing keeps the cracks from becoming larger, and this enables the concrete to transfer shear across the cracks by aggregate interlock.
- **3.** The stirrups wrapped around the core of concrete act like hoops and thus increase the beam's strength and ductility. In a related fashion, the stirrups tie the longitudinal bars into the concrete core of the beam and restrain them from prying off the covering concrete.
- **4.** The holding together of the concrete on the two sides of the cracks helps keep the cracks from moving into the compression zone of the beam. Remember that other than for deformed wire fabric, the yield stress of the web reinforcing is limited to 60 ksi to limit the width of the cracks.

### **8.8 Design for Shear**

The maximum shear, *Vu* , in a beam must not exceed the design shear capacity of the beam cross section, φ*Vn* , where φ is 0.75 and *Vn* is the nominal shear strength of the concrete and the shear reinforcing.

$$V_u \leq \phi V_n$$

The value of φ*Vn* can be broken down into the design shear strength of the concrete, φ*Vc* , plus the design shear strength of the shear reinforcing, φ*Vs*. The value of φ*Vc* is provided in the code for different situations, and thus we are able to compute the required value of φ*Vs* for each situation:

$$V_u \le \phi V_c + \phi V_s$$

For this derivation, an equal sign is used:

$$V_u = \phi V_c + \phi V_s$$

The purpose of stirrups is to minimize the size of diagonal tension cracks or to carry the diagonal tension stress from one side of the crack to the other. Very little tension is carried by the stirrups until after a crack begins to form. Before the inclined cracks begin to form, the strain in the stirrups is equal to the strain in the adjacent concrete. Because this concrete cracks at very low diagonal tensile stresses, the stresses in the stirrups at that time are very small, perhaps only 3 ksi to 6 ksi. You can see that these stirrups do not prevent inclined cracks and that they really aren't a significant factor until the cracks begin to develop.

Tests made on reinforced concrete beams show that they will not fail by the widening of the diagonal tension cracks until the stirrups going across the cracks have been stressed to their yield stresses. For the derivation to follow, it is assumed that a diagonal tension crack has developed and has run up into the compression zone but not all the way to the top, as shown in Figure 8.6. It is further assumed that the stirrups crossing the crack have yielded.

The nominal shear strength of the stirrups, *Vs*, crossing the crack can be calculated from the following expression, where *n* is the number of stirrups crossing the crack and *Av* is the cross-sectional area each stirrup has crossing the crack. If a stirrup is used, *Av* equals two times the cross-sectional area of the stirrup bar. If it is a stirrup, *Av* equals four times the cross-sectional area of the stirrup bar. The term *fyt* is the specified yield strength of transverse reinforcement, or stirrups in this case.

$$V_s = A_v f_{yt} n$$

If it is conservatively assumed that the horizontal projection of the crack equals the effective depth, *d*, of the section (thus a 45◦ crack), the number of stirrups crossing the crack can be determined from the expression to follow, in which *s* is the center-to-center spacing of the stirrups:

$$n = \frac{d}{s}$$

![](_page_250_Picture_15.jpeg)

**FI GU RE 8.6** Beam with diagonal crack and vertical stirrups.

Then

$$V_s = A_v f_{yt} \frac{d}{s}$$
 (ACI Equation 11-15)

From this expression, the required spacing of vertical stirrups is

$$s = \frac{A_{v} f_{yt} d}{V_{s}}$$

and the value of  $V_s$  can be determined as follows:

$$V_u = \phi V_c + \phi V_s$$

$$V_s = \frac{V_u - \phi V_c}{\phi}$$

Going through a similar derivation, the following expression can be determined for the required area for inclined stirrups, in which  $\alpha$  is the angle between the stirrups and the longitudinal axis of the member. Inclined stirrups should be placed so they form an angle of at least 45° with respect to the longitudinal bars, and they must be securely tied in place.

$$V_s = \frac{A_v f_{yt}(\sin\alpha + \cos\alpha)d}{s}$$
 (ACI Equation 11-16)

And for a bent-up bar or a group of bent-up bars at the same distance from the support, we have

$$V_s = A_v f_{vt} \sin \alpha \le 3\sqrt{f_c'} b_w d$$
 (ACI Equation 11-17)

### **ACI Code Requirements**

This section presents a detailed list of the code requirements controlling the design of web reinforcing, even though some of these items have been previously mentioned in this chapter:

1. When the factored shear,  $V_{\mu}$ , exceeds one-half the shear design strength,  $\phi V_{c}$ , the code (11.4.6.1) requires the use of web reinforcing. The value of  $V_c$  is normally taken as  $2\lambda\sqrt{f_c'}b_wd$ , but the code (11.2.2.1) permits the use of the following less conservative value:

$$V_c = \left(1.9\lambda\sqrt{f_c'} + 2500\rho_w \frac{V_u d}{M_u}\right) b_w d \le 3.5\lambda\sqrt{f_c'} b_w d \qquad (ACI Equation 11-5)$$

As previously mentioned,  $M_u$  is the moment occurring simultaneously with  $V_u$  at the section in question. The value of  $V_u d/M_u$  must not be taken as greater than 1.0 in calculating  $V_c$ , according to the code.

2. When shear reinforcing is required, the code states that the amount provided must fall between certain clearly specified lower and upper limits. If the amount of reinforcing is too low, it may yield or even snap immediately after the formation of an inclined crack. As soon as a diagonal crack develops, the tension previously carried by the concrete is transferred to the web reinforcing. To prevent the stirrups (or other web reinforcing) from snapping at that time, their area is limited to the minimum value provided at the end of the next paragraph.

ACI Section 11.4.6.3 specifies a minimum amount of web reinforcing so as to provide an ultimate shear strength no less than  $0.75\lambda\sqrt{f_c}b_w s$ . Using this provision of the code should prevent a sudden shear failure of the beam when inclined cracks occur.

The shear strength calculated with this expression may not be less than  $50b_w s$ . If a  $0.75\lambda\sqrt{f_c'}$  psi strength is available for a web width  $b_w$  and a length of beam s equal to the stirrup spacing, we will have

$$0.75\sqrt{f_c'}b_w s = A_v f_{yt}$$

$$A_{v \text{ min}} = \frac{0.75\sqrt{f_c'}b_w s}{f_{vt}}$$
(ACI Equation 11-13)

but not less than the value obtained with a 50-psi strength  $50b_w s/f_{vr}$ 

If  $\sqrt{f_c'}$  is greater than 4444 psi, the minimum value of  $A_v$  is controlled by the expression  $0.75\sqrt{f_c'}b_ws/f_{yt}$ . Should  $f_c'$  be less than 4444 psi, the minimum  $A_v$  value will be controlled by the  $50b_ws/f_{yt}$  expression.

In SI units 
$$A_{v \text{ min}} = \frac{1}{16} \sqrt{f_c'} \frac{b_w s}{f_{vt}} \ge \frac{0.33 b_w s}{f_{vt}}$$

This expression from ACI Section 11.4.6.3 provides the minimum area of web reinforcing,  $A_v$ , that is to be used as long as the factored torsional moment,  $T_u$ , does not exceed one-fourth of the cracking torque,  $T_{cr}$ . Such a torque will not cause an appreciable reduction in the flexural or shear strength of a member and may be neglected (ACI Section 11.5.1). For nonprestressed members, this limiting value is

$$\phi \lambda \sqrt{f_c'} \left( \frac{A_{cp}^2}{p_{cp}} \right)$$

In SI units 
$$\frac{\phi \lambda \sqrt{f_c'}}{12} \frac{A_{cp}^2}{p_{cp}}$$

In this expression,  $\phi = 0.75$ ,  $A_{cp}$  is the area enclosed by the outside perimeter of the concrete cross section, and  $p_{cp}$  is the outside perimeter of the concrete cross section. The computation of  $T_u$  and  $T_{cr}$  for various situations is presented in Chapter 15.

Although you may feel that the use of such minimum shear reinforcing is not necessary, studies of earthquake damage in recent years have shown very large amounts of shear damage occurring in reinforced concrete structures, and it is felt that the use of this minimum value will greatly improve the resistance of such structures to seismic forces. Actually, many designers believe that the minimum area of web reinforcing should be used throughout beams, not just where  $V_u$  is greater than  $\phi V_c/2$ .

This requirement for a minimum amount of shear reinforcing may be waived if tests have been conducted showing that the required bending and shear strengths can be met without the shear reinforcing (ACI 11.4.6.2).

3. As previously described, stirrups cannot resist appreciable shear unless they are crossed by an inclined crack. Thus, to make sure that each  $45^{\circ}$  crack is intercepted by at least one stirrup, the maximum spacing of vertical stirrups permitted by the code (11.4.5.1) is the lesser of d/2 or 24 in. for nonprestressed members and  $\frac{3}{4}h$  for prestressed members or 24 in. where h is the overall thickness of a member. Should, however,  $V_s$  exceed  $4\sqrt{f_c'}b_wd_s^{5}$ 

<sup>&</sup>lt;sup>5</sup> In SI,  $V_s = \frac{1}{3} \sqrt{f_c'} b_w d$ .

![](_page_253_Picture_2.jpeg)

Nuclear power plant construction.

these maximum spacings are to be reduced by one-half (ACI 11.4.5.3). These closer spacings will lead to narrower inclined cracks.

Another advantage of limiting maximum spacing values for stirrups is that closely spaced stirrups will hold the longitudinal bars in the beam. They reduce the chance that the steel may tear or buckle through the concrete cover or possibly slip on the concrete.

Under no circumstances may  $V_s$  be allowed to exceed  $8\sqrt{f_c'}b_wd$  (Code 11.4.7.9).<sup>6</sup> The shear strength of a beam cannot be increased indefinitely by adding more and more shear reinforcing, because the concrete will eventually disintegrate no matter how much shear reinforcing is added. The reader can understand the presence of an upper limit if he or she thinks for a little while about the concrete above the crack. The greater the shear in the member that is transferred by the shear reinforcing to the concrete above, the greater will be the chance of a combination shear and compression failure of that concrete.

- **4.** Section 11.1.2 of the code states that the values of  $\sqrt{f_c'}$  used for the design of web reinforcing may not exceed 100 psi<sup>7</sup> except for certain cases listed in Section 11.1.2.1. In that section, permission is given to use a larger value for members having the minimum reinforcing specified in ACI Sections 11.4.6.3, 11.4.6.4, and 11.5.5.2. Members meeting these requirements for extra shear reinforcing have sufficient postcrack capacities to prevent diagonal tension failures.
- 5. Section 12.13 of the code provides requirements about dimensions, development lengths, and so forth. For stirrups to develop their design strengths, they must be adequately anchored. Stirrups may be crossed by diagonal tension cracks at various points along their depths. Since these cracks may cross very close to the tension or compression edges of the

<sup>&</sup>lt;sup>6</sup> It's  $\frac{2}{3}\sqrt{f_c'}b_w d$  in SI units.

<sup>&</sup>lt;sup>7</sup> It's  $\frac{25}{3}$  MPa in SI units.

members, the stirrups must be able to develop their yield strengths along the full extent of their lengths. It can then be seen why they should be bent around longitudinal bars of greater diameters than their own and extended beyond by adequate development lengths. Should there be compression reinforcing, the hooking of the stirrups around them will help prevent them from buckling.

Stirrups should be carried as close to the compression and tension faces of beams as the specified cover and longitudinal reinforcing will permit. The ends of stirrup legs should ideally have 135° or 180° hooks bent around longitudinal bars, with development lengths as specified in ACI Sections 8.1 and 12.13. Detailed information on stirrups follows:

- (a) Stirrups with  $90^{\circ}$  bends and  $6d_b$  extensions at their free ends may be used for #5 and smaller bars, as shown in Figure 8.7(a). Tests have shown that  $90^{\circ}$  bends with  $6d_b$  extensions should not be used for #6 or larger bars (unless  $f_y$  is 40,000 psi or less) because they tend to pop out under high loads.
- (b) If  $f_y$  is greater than 40,000 psi, #6, #7, and #8 bars with 90° bends may be used if the extensions are  $12d_b$  [see Figure 8.7(b)]. The reason for this specification is that it is not possible to bend these higher-strength bars tightly around the longitudinal bars.
- (c) Stirrups with  $135^{\circ}$  bends and  $6d_b$  extensions may be used for #8 and smaller bars, as shown in Figure 8.7(c).
- **6.** When a beam reaction causes compression in the end of a member in the same direction as the external shear, the shearing strength of that part of the member is increased. Tests of such reinforced concrete members have shown that, in general, as long as a gradually varying shear is present (as with a uniformly loaded member), the first crack will occur at a distance d from the face of the support. It is therefore permissible, according to the code (11.1.3.1), to decrease somewhat the calculated shearing force for a distance d from the face of the support. This is done by using a  $V_u$  in that range equal to the calculated  $V_u$  at a distance d from the face of the support. Should a concentrated load be applied in this region, no such

![](_page_254_Figure_8.jpeg)

Note: Fit stirrups as close to compression and tension surfaces as cover and other reinforcing permits.

FIGURE 8.7 Stirrup details.

shear reduction is permitted. Such loads will be transmitted directly to the support above the 45◦ cracks, with the result that we are not permitted a reduction in the end shear for design purposes.

Should the reaction tend to produce tension in this zone, no shear stress reduction is permitted, because tests have shown that cracking may occur at the face of the support or even inside it. Figure 8.8 shows two cases where the end shear reduction is not permitted. In the situation shown in Figure 8.8(a), the critical section will be at the face of the support. In Figure 8.8(b), an I-shaped section is shown, with the load applied to its tension flange. The loads have to be transferred across the inclined crack before they reach the support. Another crack problem like this one occurs in retaining wall footings and is discussed in Section 13.10 of this text.

**7.** Various tests of reinforced concrete beams of normal proportions with sufficient web reinforcing have shown that shearing forces have no significant effect on the flexural capacities of the beams. Experiments with deep beams, however, show that large shears will often keep those members from developing their full flexural capacities. As a result, the code requirements given in the preceding paragraphs are not applicable to beams whose clear spans divided by their effective depths are less than four or for regions of beams that are loaded with concentrated loads within a distance from the support equal to the member depth and that are loaded on one face and supported on the opposite face. Such a situation permits the development of compression struts between the loads and the supports. For such members as these, the code in its Appendix A provides an alternate method of design, which is referred to as "strut and tie" design. This method is briefly described in Appendix C of this text. Should the loads be applied through the sides or bottom of such members, their shear design should be handled as it is for ordinary beams. Members falling into this class include beams, short cantilevers, and corbels. Corbels are brackets that project from the sides of columns and are used to support beams and girders, as shown in Figure 8.9. They are quite commonly used in precast construction. Special web reinforcing provisions are made for such members in Section 11.7 of the code and are considered in Section 8.12 of this chapter.

**8.** Section 8.11.8 of the ACI Code permits a shear of 1.1*Vc* for the ribs of joist construction, as where we have closely spaced T beams with tapered webs. For the 10% increase in *Vc* , the joist proportions must meet the provisions of ACI Section 8.11. In ACI Section 8.11.2, it is stated that the ribs must be no less than 4 in. wide, must have depths not more than three and a half times the minimum width of the ribs, and may not have clear spacings between the ribs greater than 30 in.

![](_page_255_Figure_6.jpeg)

**FI GU RE 8.8** Two situations where end shear reduction is not permitted.

![](_page_256_Picture_2.jpeg)

FIGURE 8.9 Corbel supporting beam reaction.

### 8.10 Shear Design Example Problems

Example 8.1 illustrates the selection of a beam with a sufficiently large cross section so that no web reinforcing is required. The resulting beam is unusually large. It is normally considered much better practice to use appreciably smaller sections constructed with web reinforcing. The reader should also realize that it is good construction practice to use some stirrups in all reinforced concrete beams (even though they may not be required by shear) because they enable the workers to build for each beam a cage of steel that can be conveniently handled.

#### Example 8.1

Determine the minimum cross section required for a rectangular beam from a shear standpoint so that no web reinforcing is required by the ACI Code if  $V_u = 38$  k and  $f_c' = 4000$  psi. Use the conservative value of  $V_c = 2\lambda \sqrt{f_c'} b_w d$ .

#### SOLUTION

Shear strength provided by concrete is determined by the equation

$$\phi V_c = (0.75) \left[ 2 (1.0) \left( \sqrt{4000} \text{ psi} \right) b_w d \right] = 94.87 b_w d$$

But the ACI Code 11.4.6.1 states that a minimum area of shear reinforcement is to be provided if  $V_u$  exceeds  $\frac{1}{2}\phi V_c$ 

38,000 lb = 
$$\frac{1}{2}$$
 (94.87 $b_w d$ )  
 $b_w d = 801.1 \text{ in.}^2$ 

Use 24-in.  $\times$  36-in. beam (d = 33.5 in.)

The design of web reinforcing is illustrated by Examples 8.2 through 8.6. Maximum vertical stirrup spacings have been given previously, whereas no comment has been made about minimum spacings. Stirrups must be spaced far enough apart to permit the aggregate to pass through, and, in addition, they must be reasonably few in number so as to keep within reason the amount of labor involved in fabricating and placing them. Accordingly, minimum spacings of 3 in. or 4 in. are normally used. Usually #3 stirrups are assumed, and if the

calculated design spacings are less than d/4, larger-diameter stirrups can be used. Another alternative is to use ⊔¬⊔ stirrups instead of ⊔ stirrups. Different diameter stirrups should not be used in the same beam, or confusion will result.

As is illustrated in Examples 8.3, 8.5, and 8.6, it is quite convenient to draw the  $V_u$ diagram and carefully label it with values of such items as  $\phi V_c$ ,  $\phi V_c/2$ , and  $V_u$  at a distance d from the face of the support and to show the dimensions involved.

Some designers place their first stirrup a distance of one-half of the end-calculated spacing requirement from the face. Others put the first stirrup 2 in. or 3 in. from the support.

From a practical viewpoint, stirrups are usually spaced with center-to-center dimensions that are multiples of 3 in. or 4 in. to simplify the fieldwork. Although this procedure may require an additional stirrup or two, total costs should be less because of reduced labor costs. A common field procedure is to place chalk marks at 2-ft intervals on the forms and to place the stirrups by eye in between those marks. This practice is combined with a somewhat violent placing of the heavy concrete in the forms, followed by vigorous vibration. These field practices should clearly show the student that it is foolish to specify odd theoretical stirrup spacings such as  $4 @ 6 \frac{7}{16}$  in. and  $6 @ 5 \frac{3}{8}$  in., because such careful positioning will not be achieved in the actual members. Thus, the designer will normally specify stirrup spacings in multiples of whole inches and perhaps in multiples of 3 in. or 4 in.

With available computer programs, it is easily possible to obtain theoretical arrangements of stirrups with which the least total amounts of shear reinforcing will be required. The use of such programs is certainly useful to the designer, but he or she needs to take the resulting values and revise them into simple economical patterns with simple spacing arrangements—as in multiples of 3 in., for example.

A summary of the steps required to design vertical stirrups is presented in Table 8.1. For each step, the applicable section number of the code is provided. The authors have found this to be a very useful table for students to refer to while designing stirrups.

| TABLE 8.1 | Summar | of Steps | Involved in | Vertical Stirrup | Design |
|-----------|--------|----------|-------------|------------------|--------|
|           |        |          |             |                  |        |

| Is Shear Reinforcing Necessary?                                                                                                                                               |                                           |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|
| 1. Draw $V_u$ diagram.                                                                                                                                                        | 11.1.3.1 and<br>Commentary<br>(R11.1.3.1) |
| 2. Calculate $V_u$ at a distance $d$ from the support (with certain exceptions).                                                                                              | 11.2.1.1                                  |
| 3. Calculate $\phi V_c = 2\phi \lambda \sqrt{f_c'} b_w d$ (or use the alternate method).                                                                                      | 11.2.2.1                                  |
| 4. Stirrups are needed if $V_u>\frac{1}{2}\phi V_c$ (with some exceptions for slabs, footings, shallow members, hollow-core units, steel fiber–reinforced beams, and joists). | 11.4.6.1                                  |
| Design of Stirrups                                                                                                                                                            |                                           |
| 1. Calculate theoretical stirrup spacing, $s=A_vf_{yt}d/V_s$ where $V_s=(V_u-\phi V_c)/\phi$ .                                                                                | 11.4.7.2                                  |
| 2. Determine maximum spacing to provide minimum area of shear reinforcement, $s = A_v f_{yt}/0.75 \sqrt{f_c'} b_w$ but not more than $A_v f_{yt}/50 b_w$ .                    | 11.4.6.3                                  |
| 3. Compute maximum spacing: $d/2 \le 24$ in. if $V_s \le 4\sqrt{f_c'}b_wd$ .                                                                                                  | 11.4.5.1                                  |
| 4. Compute maximum spacing: $d/4 \le 12$ in. if $V_s > 4\sqrt{f_c'}b_wd$ .                                                                                                    | 11.4.5.3                                  |
| 5. $V_{\rm S}$ may not be $> 8\sqrt{f_{\rm C}^{\prime}}b_{\rm w}d$ .                                                                                                          | 11.4.7.9                                  |
| 6. Minimum practical spacing $pprox$ 3 in. or 4 in.                                                                                                                           |                                           |

#### Example 8.2

The beam shown in Figure 8.10 was selected using  $f_y = 60,000$  psi and  $f_c' = 3000$  psi, normal weight. Determine the theoretical spacing of #3  $\sqcup$  stirrups for each of the following shears:

- (a)  $V_{ij} = 12,000 \text{ lb}$
- **(b)**  $V_u = 40,000 \text{ lb}$
- (c)  $V_u = 60,000 \text{ lb}$
- (d)  $V_{ij} = 150,000 \text{ lb}$

#### SOLUTION

(a)  $V_{ij} = 12,000$  lb (using  $\lambda = 1.0$  for normal-weight concrete)

$$\phi V_c = \phi 2\lambda \sqrt{f_c'} b_w d = (0.75) [2(1.0)\sqrt{3000} \text{ psi}](14 \text{ in.})(24 \text{ in.}) = 27,605 \text{ lb}$$

$$\frac{1}{2}\phi V_c = 13,803 \text{ lb} > 12,000 \text{ lb}$$
  $\therefore$  Stirrups not required

**(b)**  $V_u = 40,000 \text{ lb}$ 

Stirrups needed because  $V_u > \frac{1}{2}\phi V_c$ .

Theoretical spacing

$$\begin{split} \phi V_c + \phi V_s &= V_u \\ V_s &= \frac{V_u - \phi V_c}{\phi} = \frac{40,000 \text{ lb} - 27,605 \text{ lb}}{0.75} = 16,527 \text{ lb} \\ s &= \frac{A_v f_{yt} d}{V_s} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi}) (24 \text{ in.})}{16,527 \text{ lb}} = 19.17 \text{ in.} \leftarrow 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi} + 0.000 \text{ psi$$

Maximum spacing to provide minimum  $A_{\nu}$ 

$$s = \frac{A_v f_{yt}}{0.75 \sqrt{f_c'} b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(0.75 \sqrt{3000} \text{ psi}) (14 \text{ in.})} = 22.95 \text{ in.}$$

$$s = \frac{A_v f_{yt}}{50 b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(50) (14 \text{ in.})} = 18.86 \text{ in.}$$

$$V_s = 16,527 \text{ lb} < (4) (\sqrt{3000} \text{ psi}) (14 \text{ in.}) (24 \text{ in.}) = 73,614 \text{ lb}$$
  
 $\therefore$  Maximum  $s = \frac{d}{2} = 12 \text{ in.}$   $\underline{s = 12.0 \text{ in.}}$ 

![](_page_258_Figure_19.jpeg)

**FIGURE 8.10** Beam cross section for Example 8.2.

(c) 
$$V_{ij} = 60,000 \text{ lb}$$

Theoretical spacing

$$V_{s} = \frac{V_{u} - \phi V_{c}}{\phi} = \frac{60,000 \text{ lb} - 27,605 \text{ lb}}{0.75} = 43,193 \text{ lb}$$

$$s = \frac{A_{v}f_{yt}d}{V_{c}} = \frac{(2)(0.11 \text{ in.}^{2})(60,000 \text{ psi})(24 \text{ in.})}{43,193 \text{ lb}} = 7.33 \text{ in.} \leftarrow$$

Maximum spacing to provide minimum A

$$s = \frac{A_v f_{yt}}{0.75 \sqrt{f_c'} b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(0.75 \sqrt{3000} \text{ psi}) (14 \text{ in.})} = 22.95 \text{ in.}$$

$$s = \frac{A_v f_{yt}}{50 b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(50) (14 \text{ in.})} = 18.86 \text{ in.}$$

$$V_s = 43,193 \text{ lb} < (4) (\sqrt{3000} \text{ psi}) (14 \text{ in.}) (24 \text{ in.}) = 73,614 \text{ lb}$$

$$\therefore \text{ Maximum } s = \frac{d}{2} = 12 \text{ in.}$$

$$\underline{s} = 7.33 \text{ in}$$

(d)  $V_{ij} = 150,000 \text{ lb}$ 

$$V_{\rm s} = \frac{150,000~{\rm lb} - 27,605~{\rm lb}}{0.75} = 163,193~{\rm lb}$$

 $163,193 \text{ lb} > (8) (\sqrt{3000} \text{ psi}) (14 \text{ in.}) (24 \text{ in.}) = 147,228 \text{ lb}$ 

 $V_s$  may not be taken  $> 8\sqrt{f_c'}b_wd$ 

 $\therefore$  Need larger beam and/or one with larger  $f_{\mathcal{C}}'$  value

#### Example 8.3

Select #3  $\sqcup$  stirrups for the beam shown in Figure 8.11, for which  $w_D = 4$  k/ft and  $w_L = 6$  k/ft.  $f_{\rm c}'=4000$  psi, normal weight, and  $f_{\rm vt}=60{,}000$  psi.

#### SOLUTION

 $V_{u}$  at the face of the left support = (7 ft) (1.2 × 4 klf + 1.6 × 6 klf) = 100.8 k = 100,800 lb

$$V_u$$
 at a distance  $d$  from face of support =  $\left(\frac{84 \text{ in.} - 22.5 \text{ in.}}{84 \text{ in.}}\right) (100,800 \text{ lb}) = 73,800 \text{ lb}$ 

$$\phi V_c = \phi 2\lambda \sqrt{f_c'} b_w d = (0.75) [2(1.0)\sqrt{4000} \text{ psi}] (15 \text{ in.}) (22.5 \text{ in.}) = 32,018 \text{ lb}$$

These values are shown in Figure 8.12.

$$V_u = \phi V_c + \phi V_s$$
  $\phi V_s = V_u - \phi V_c = 73,800 \text{ lb} - 32,018 \text{ lb} = 41,782 \text{ lb}$   $V_s = \frac{41,782 \text{ lb}}{0.75} = 55,709 \text{ lb}$ 

Maximum spacing of stirrups = d/2 = 11.25 in., since  $V_s$  is  $< 4\sqrt{f_c'}b_wd$  = 85,382 lb. Maximum theoretical spacing at left end

$$s = \frac{A_v f_{yt} d}{V_s} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi}) (22.5 \text{ in.})}{(55,709 \text{ lb})} = 5.33 \text{ in.} \leftarrow$$

![](_page_260_Figure_2.jpeg)

**FI GU RE 8.11** Given information for Example 8.3.

![](_page_260_Figure_4.jpeg)

**FI GU RE 8.12** Shear diagram for Example 8.3.

Maximum spacing to provide minimum  $A_{\nu}$  of stirrups

$$s = \frac{A_v f_{yt}}{0.75 \sqrt{f_c'} b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(0.75 \sqrt{4000} \text{ psi}) (15 \text{ in.})} = 18.55 \text{ in.}$$

$$s = \frac{A_v f_{yt}}{50 b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(50) (15 \text{ in.})} = 17.6 \text{ in.}$$

At what location is s = 9 in. OK?

$$\begin{split} V_u &= \phi V_c + \phi V_s = 32,018 \text{ lb} + 0.75 \left[ \frac{A_v f_y d}{s} \right] \\ &= 32,018 \text{ lb} + \frac{(0.75)(2)(0.11 \text{ in.}^2)(60,000 \text{ psi})(22.5 \text{ in.})}{9 \text{ in.}} \\ &= 56,768 \text{ lb} \\ V_u &= 100,800 \text{ lb} - 14,400x = 56,768 \text{ lb}, \, x = 3.058 \text{ ft} = 36.69 \text{ in.} \end{split}$$

Results of similar calculations that relate the value of x to stirrup spacing, s, are shown in the table.

| Distance from Face of Support (ft) | <i>V<sub>u</sub></i> (lb) | $V_s = \frac{V_u - \phi V_c}{\phi}$ (lb) | Theoretical $s = \frac{A_v f_{yt} d}{V_s}$ (in.) |
|------------------------------------|---------------------------|------------------------------------------|--------------------------------------------------|
| 0 to $d = 1.875$                   | 73,800                    | 55,709                                   | 5.33                                             |
| 2                                  | 72,000                    | 53,309                                   | 5.57                                             |
| 3                                  | 57,600                    | 34,109                                   | 8.71                                             |
| 3.058                              | 56,768                    | 33,000                                   | 9                                                |
| 4                                  | 43,200                    | 14,909                                   | > Maximum of $d/2 = 11.25$                       |

Spacings selected

As previously mentioned, it is a good practice to space stirrups at multiples of 3 in. or 4 in. on center. As an illustration, it is quite reasonable to select for Example 8.3 the following spacings: 1 @ 2 in., 7 @ 5 in., and 4 @ 9 in. In rounding off the spacings to multiples of 3 in., it was necessary to exceed the theoretical spacings by a small amount near the end of the beam. However, the values are quite close to the required ones, and the overall number of stirrups used in the beam is more than adequate.

In Example 8.4, which follows, the value of  $V_c$  for the beam of Example 8.3 is computed by the alternate method of Section 11.2.2.1 of the code.

#### Example 8.4

Compute the value of  $V_c$  at a distance 3 ft from the face of the left support of the beam of Example 8.3 and Figure 8.11 by using ACI Equation 11-5.

$$V_c = \left(1.9\lambda\sqrt{f_c'} + 2500\rho_w \frac{V_u d}{M_u}\right) b_w d \le 3.5\lambda\sqrt{f_c'} b_w d$$

#### SOLUTION

$$\lambda = 1.0$$
 (normal-weight aggregate)  
 $w_{ij} = (1.2)(4 \text{ klf}) + (1.6)(6 \text{ klf}) = 14.4 \text{ k/ft}$ 

Measuring *x* from the center of the left support, the value of *x* corresponding to 3 ft from the face is 3.5 ft.

$$\begin{split} V_u &= \frac{w_u I}{2} - w_u x = \frac{(14.4 \text{ k/ft}) (15 \text{ft})}{2} - (14.4 \text{ k/ft}) (x) \\ &= 57.6 \text{ k (at } x = 3.5 \text{ ft from center of the left support)} \\ M_u &= \frac{w_u I x}{2} - \frac{w_u x^2}{2} = \frac{(14.4 \text{ k/ft}) (15 \text{ ft}) (3.5 \text{ ft})}{2} - \frac{(14.4 \text{ k/ft}) (3.5 \text{ ft})^2}{2} \\ &= (14.4 \text{ k/ft}) (100.8 \text{ k}) - (3 \text{ ft}) (1.5 \text{ ft}) (14.4 \text{ k/ft}) = 289.8 \text{ ft-k} \\ \rho_w &= \frac{5.06 \text{ in.}^2}{(15 \text{ in.}) (22.5 \text{ in.})} = 0.0150 \\ \frac{V_u d}{M_u} &= \frac{(57.6 \text{ k}) (22.5 \text{ in.})}{(12) (289.8 \text{ ft-k})} = 0.374 < 1.0 \\ V_c &= [1.9 (1.0) \sqrt{4000} \text{ psi} + (2500) (0.0150) (0.374)] (15 \text{ in.}) (22.5 \text{ in.}) \\ &= 45,290 \text{ lb} < (3.5 \sqrt{4000} \text{ psi}) (15 \text{ in.}) (22.5 \text{ in.}) = 74,709 \text{ lb} \end{split}$$

For the uniformly loaded beams considered up to this point, it has been assumed that both dead and live loads extended from end to end of the spans. Although this practice will produce the maximum  $V_u$  at the ends of simple spans, it will not produce maximums at interior points. For such points, maximum shears will be obtained when the uniform live load is placed from the point in question to the most distant end support. For Example 8.5, shear is determined at the beam end (live load running for entire span) and then at the beam centerline (live load to one side only), and a straight-line relationship is assumed in between. Although the ACI does not specifically comment on the variable positioning of live load to produce maximum shears, it certainly is their intent for engineers to position loads so as to maximize design shear forces.

#### Example 8.5

Select #3  $\sqcup$  stirrups for the beam of Example 8.3, assuming the live load is placed to produce maximum shear at beam end and centerline.

#### SOLUTION

Maximum  $V_u$  at left end = (7 ft) (1.2  $\times$  4 klf + 1.6  $\times$  6 klf) = 110.8 k = 100,800 lb. For maximum  $V_u$  at centerline, the live load is placed as shown in Figure 8.13.

$$V_u$$
 at centerline = 50,400 lb  $-$  (7 ft) (1.2  $\times$  4 klf) = 16.8 k = 16,800 lb 
$$V_c = 2(1.0)\,(\sqrt{4000}~{\rm psi})\,(15~{\rm in.})\,(22.5~{\rm in.}) = 42,691~{\rm lb}$$

 $V_u$  at a distance d from face of support = 78,300 lb as determined by proportions from Figure 8.14.  $V_- = \phi V_- + \phi V_+$ 

$$\phi V_s = V_u - \phi V_c = 78,300 \text{ lb} - (0.75) (42,691 \text{ lb}) = 46,282 \text{ lb}$$
 at left end 
$$V_s = \frac{46,282 \text{ lb}}{0.75} = 61,709 \text{ lb}$$

At what location is *s* = 9 in. OK?

$$\begin{split} V_u &= \phi V_c + \phi V_s = 32,018 + 0.75 \left(\frac{A_v f_{yt} d}{s}\right) = 32,016 + \frac{(0.75) \, (2) \, (0.11 \, \text{in.}^2) \, (60,000 \, \text{psi}) \, (22.5 \, \text{in.})}{9 \, \text{in.}} \\ &= 56,768 \, \text{lb} \end{split}$$

$$V_u = 100,800 - 12,000x = 56,768, x = 3.67 \text{ ft} = 44.0 \text{ in}.$$

Results of similar calculations that relate the value of *x* to stirrup spacing, *s*, are shown in the table.

![](_page_263_Figure_6.jpeg)

**FI GU RE 8.13** Load arrangement for maximum shear at beam midspan.

![](_page_263_Figure_8.jpeg)

**FI GU RE 8.14** Shear diagram for Example 8.5.

The limiting spacings are the same as in Example 8.3. The theoretical spacings are given in the following table:

| Distance from Face of Support (ft) | V <sub>u</sub> (lb) | $V_s = rac{V_u - \phi  V_c}{\phi}$ (lb) | Theoretical Spacing Required $s = \frac{A_v f_{yt} d}{V_s}$ (in.) |
|------------------------------------|---------------------|------------------------------------------|-------------------------------------------------------------------|
| 0 to $d = 1.875$                   | 78,300              | 61,709                                   | 4.81                                                              |
| 2                                  | 76,800              | 59,709                                   | 4.97                                                              |
| 2.638                              | 69,143              | 49,500                                   | 6                                                                 |
| 3.67                               | 56,768              | 33,000                                   | 9                                                                 |
| 5                                  | 40,800              | 11,709                                   | > Maximum 11.25                                                   |

One possible arrangement (#4 stirrups might be better)

$$1@2 \text{ in.} = 2 \text{ in.}$$

$$8@4 \text{ in.} = 32 \text{ in.}$$

$$2@6 \text{ in.} = 12 \text{ in.}$$

$$5@9 \text{ in.} = 45 \text{ in.}$$

Symmetrical about centerline

#### Example 8.6

Select spacings for #3  $\sqcup$  stirrups for a T beam with  $b_w=10$  in. and d=20 in. for the  $V_u$  diagram shown in Figure 8.15, with  $f_y=60{,}000$  psi and  $f_c'=3000$  psi, normal-weight concrete.

#### SOLUTION

#### (with reference to Figure 8.16)

 $V_u$  at a distance d from face of support

$$=44,000 \text{ lb} + \left(\frac{72 \text{ in.} - 20 \text{ in.}}{72 \text{ in.}}\right) (68,000 \text{ lb} - 44,000 \text{ lb}) = 61,333 \text{ lb}$$

 $\lambda = 1.0$  for normal-weight concrete

$$\phi V_c = (0.75) [2(1.0)\sqrt{3000} \text{ psi}] (10 \text{ in.}) (20 \text{ in.}) = 16,432 \text{ lb}$$

$$\frac{\phi V_c}{2} = \frac{16,432 \text{ lb}}{2} = 8216 \text{ lb}$$

Stirrups are needed for a distance = 72 in. 
$$+\left(\frac{24,000 \text{ lb} - 8216 \text{ lb}}{24,000 \text{ lb}}\right)$$
 (72 in.) = 119.5 in.

 $V_s$  at left end  $(V_u-\phi V_c)/\phi=(61,333\ \text{lb}-16,432\ \text{lb})/0.75=59,868\ \text{lb},$  which is larger than  $4\sqrt{f_c'}b_wd=(4\sqrt{3000}\ \text{psi})$  (10 in.) (20 in.) = 43,818 lb but less than  $8\sqrt{f_c'}b_wd$ . Therefore, the maximum spacing of stirrups in that range is d/4=5 in.

![](_page_265_Figure_2.jpeg)

FIGURE 8.15 Shear diagram for Example 8.6.

![](_page_265_Figure_4.jpeg)

**FIGURE 8.16** More detailed shear diagram for Example 8.6.

Maximum spacing of stirrups =d/4=20/4=5 in. when  $V_s>4\sqrt{f_c'}b_wd=(4\sqrt{3000} \text{ psi})$  (10 in.) (20 in.) =43,818 lb. By proportions from the  $V_s$  column in the table,  $V_s$  falls to 43,818 lb at approximately 4.66 ft, or 56 in., from the left end of the beam.

Maximum spacing permitted to provide minimum  $A_{\nu}$  of stirrups is the smaller of the two following values of s.

$$s = \frac{A_v f_{yt}}{0.75 \sqrt{f_c'} b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(0.75 \sqrt{3000} \text{ psi}) (10 \text{ in.})} = 32.13 \text{ in.}$$

$$s = \frac{A_v f_{yt}}{50 b_w} = \frac{(2) (0.11 \text{ in.}^2) (60,000 \text{ psi})}{(50) (10 \text{ in.})} = 26.4 \text{ in.}$$

![](_page_266_Figure_2.jpeg)

FIGURE 8.17 Detailed shear diagram for Example 8.6.

The theoretical spacings at various points in the beam are computed in the following table:

| Distance from Face of Support (ft) | V <sub>u</sub> (lb) | $V_s = rac{V_u - \phi V_c}{\phi}$ (lb) | Theoretical Spacing $ \text{Required } s = \frac{A_{\nu} f_{yt} d}{V_{s}} \text{ (in.)} $ | Maximum<br>Spacing (in.) |
|------------------------------------|---------------------|-----------------------------------------|-------------------------------------------------------------------------------------------|--------------------------|
| 0 to $d = 1.667$                   | 61,333              | 59,868                                  | 4.41                                                                                      | 4.41                     |
| 3                                  | 56,000              | 52,758                                  | 5.00                                                                                      | 5.00                     |
| 6-                                 | 44,000              | 36,757                                  | 7.18                                                                                      | 5.00                     |
| 6+                                 | 24,000              | 10,091                                  | 26.16                                                                                     | 10.00                    |

A summary of the results of the preceding calculations is shown in Figure 8.17, where the solid dark line represents the maximum stirrup spacings permitted by the code and the dashed line represents the calculated theoretical spacings required for  $V_{\mu} - \phi V_{c}$ .

From this information, the authors selected the following spacings:

1 @ 3 in. = 3 in.  
17 @ 4 in. = 68 in.  
$$5$$
 @ 10 in. = 50 in.

121 in.

Symmetrical about centerline

### 8.11 Economical Spacing of Stirrups

When stirrups are required in a reinforced concrete member, the code specifies maximum permissible spacings varying from d/4 to d/2. However, it is usually thought that stirrup spacings less than d/4 are rather uneconomical. Many designers use a maximum of three

| s           | $\phi V_s$ for #3 $\sqcup$ Stirrups (k) | $\phi V_s$ for #4 $\sqcup$ Stirrups (k) |
|-------------|-----------------------------------------|-----------------------------------------|
| d/2         | 19.8                                    | 36                                      |
| <i>d</i> /3 | 29.7                                    | 54                                      |
| d/4         | 39.6                                    | 72                                      |

**TABLE 8.2** Values for 60-ksi Stirrups

different spacings in a beam. These are d/4, d/3, and d/2. It is easily possible to derive a value of  $\phi V_s$  for each size and style of stirrups for each of these spacings.<sup>8</sup>

Note that the number of stirrups is equal to d/s and that if we use spacings of d/4, d/3, and d/2 we can see that n equals 4, 3, or 2. Then the value of  $\phi V_s$  can be calculated for any particular spacing, size, and style of stirrup. For instance, for #3  $\sqcup$  stirrups spaced at d/2 with  $\phi = 0.75 \text{ and } f_{v} = 60 \text{ ksi},$ 

$$\phi V_s = \frac{\phi A_v f_{yt} d}{s} = \frac{(0.75) (2 \times 0.11 \text{ in.}^2) (60 \text{ ksi}) (d)}{d/2} = 19.8 \text{ k}$$

The values shown in Table 8.2 were computed in this way for 60-ksi stirrups.

For an example using this table, reference is made to the beam and  $V_{\mu}$  diagram of Example 8.3, which was shown in Figure 8.12 where 60-ksi #3 ⊔ stirrups were selected for a beam with a d of  $22\frac{1}{2}$  in. For our closest spacing, d/4, we can calculate  $\phi V_c + 39.6$  k = 32.018 k + 39.6 k = 71.6 k. Similar calculations are made for d/3 and d/2 spacings, and we obtain, respectively, 61.7 k and 51.8 k. The shear diagram is repeated in Figure 8.18, and the preceding values are located on the diagram by proportions or by scaling.

![](_page_267_Figure_9.jpeg)

**FIGURE 8.18** Application of Table 8.2 to Example 8.3.

<sup>&</sup>lt;sup>8</sup> Neville, B. B., ed., 1984, Simplified Design Reinforced Concrete Buildings of Moderate Size and Height (Skokie, IL: Portland Cement Association), pp. 3-12 to 3-16.

From this information, we can see that we can use *d*/4 for the first 2.72 ft, *d*/3 for the next 0.68 ft, and *d*/2 for the remaining 2.49 ft. Then the spacings are smoothed (preferably to multiples of 3 in.). Also, for this particular beam, we would probably use the *d*/4 spacing on through the 0.68-ft section and then use *d*/2 the rest of the required distance.

### **8.12 Shear Friction and Corbels**

If a crack occurs in a reinforced concrete member (whether caused by shear, flexure, shrinkage, etc.) and if the concrete pieces on opposite sides of the crack are prevented from moving apart, there will be a great deal of resistance to slipping along the crack due to the rough and irregular concrete surfaces. If reinforcement is provided across the crack to prevent relative displacement along the crack, shear will be resisted by friction between the faces, by resistance to shearing off of protruding portions of the concrete, and by dowel action of the reinforcing crossing the crack. The transfer of shear under these circumstances is called *shear friction*.

Shear friction failures are most likely to occur in short, deep members subject to high shears and small bending moments. These are the situations where the most nearly vertical cracks will occur. If moment and shear are both large, diagonal tension cracks will occur at rather large angles from the vertical. This situation has been discussed in Sections 8.1 through 8.11.

A short cantilever member having a ratio of clear span to depth (*a*/*d*) of 1.0 or less is often called a *bracket* or *corbel*. One such member is shown in Figure 8.19. The shear friction concept provides a convenient method for designing for cases where diagonal tension design is not applicable. The most common locations where shear friction design is used are for brackets, corbels, and precast connections, but it may also be applied to the interfaces between concretes cast at different times, to the interfaces between concrete and steel sections, and so on.

When brackets or corbels or short, overhanging ends or precast connections support heavy concentrated loads, they are subject to possible shear friction failures. The dashed lines in Figure 8.19 show the probable locations of these failures. It will be noted that for the endbearing situations, the cracks tend to occur at angles of about 20◦ from the direction of the force application.

Space is not taken in this chapter to provide an example of shear friction design, but a few general remarks are presented. (In Section 12.13 of this text, a numerical shear friction

![](_page_268_Picture_9.jpeg)

**FI GU RE 8.19** Possible shear friction failures.

example is presented in relation to the transfer of horizontal forces at the base of a column to a footing.) It is first assumed that a crack has occurred, as shown by the dashed lines of Figure 8.19. As slip begins to occur along the cracked surface, the roughness of the concrete surfaces tends to cause the opposing faces of the concrete to separate.

As the concrete separates, it is resisted by the tensile reinforcement  $(A_{vf})$  provided across the crack. It is assumed that this steel is stretched until it yields. (An opening of the crack of 0.01 in. will probably be sufficient to develop the yield strength of the bars.) The clamping force developed in the bars  $A_{vf}f_{v}$  will provide a frictional resistance equal to  $A_{vf}f_{v}\mu$ , where  $\mu$ is the coefficient of friction (values of which are provided for different situations in Section 11.6.4.3 of the code).

Then the design shear strength of the member must at least equal the shear, to be taken as

$$\phi V_n = V_u = \phi A_{vf} f_v \mu$$

The value of  $f_v$  used in this equation cannot exceed 60 ksi, and the shear friction reinforcement across or perpendicular to the shear crack may be obtained by

$$A_{vf} = \frac{V_u}{\phi f_v \mu}$$

This reinforcing should be appropriately placed along the shear plane. If there is no calculated bending moment, the bars will be uniformly spaced. If there is a calculated moment, it will be necessary to distribute the bars in the flexural tension area of the shear plane. The bars must be anchored sufficiently on both sides of the crack to develop their yield strength by means of embedment, hooks, headed bars, or other methods. Since space is often limited in these situations, it is often necessary to weld the bars to special devices, such as crossbars or steel angles. The bars should be anchored in confined concrete (i.e., column ties or external concrete or other reinforcing shall be used).

When beams are supported on brackets or corbels, there may be a problem with shrinkage and expansion of the beams, producing horizontal forces on the bracket or corbel. When such forces are present, the bearing plate under the concentrated load should be welded down to the tensile steel. Based on various tests, the ACI Code (11.8.3.4) says that the horizontal force used must be at least equal to  $0.2V_u$  unless special provisions are made to avoid tensile forces.

The presence of direct tension across a cracked surface obviously reduces the sheartransfer strength. Thus direct compression will increase its strength. As a result, Section 11.6.7 of the code permits the use of a permanent compressive load to increase the shear friction clamping force. A typical corbel design and its reinforcing are shown in Figure 8.20.

Enough concrete area must also be provided, and Section 11.6.5 of the code gives the upper limits on the shear force,  $V_n$ , transferred across a shear-friction failure surface based on concrete strength and contact area. For normal-weight concrete placed monolithically or placed against intentionally roughened concrete,  $V_n$  cannot exceed the smaller of

$$\begin{split} V_n &\leq 0.2 f_c' A_c \\ &\leq (480 + 0.08 f_c') A_c \\ &\leq 1600 A_c \end{split}$$

For all other cases,

$$V_n \le 0.2 f_c' A_c$$
$$\le 800 A_c$$

where  $A_c$  is the concrete contact area along the shear-friction failure surface. Units for these equations are:  $V_n(lb)$ ,  $f'_c(lb/in.^2)$ , and  $A_c(in.^2)$ .

![](_page_270_Picture_2.jpeg)

FIGURE 8.20 Example of corbel.

### 8.13 Shear Strength of Members Subjected to Axial Forces

Reinforced concrete members subjected to shear forces can at the same time be loaded with axial compression or axial tension forces due to wind, earthquake, gravity loads applied to horizontal or inclined members, shrinkage in restrained members, and so on. These forces can affect the shear design of our members. Compressive loads tend to prevent cracks from developing. As a result, they provide members with larger compressive areas and thus greater shear strengths. Tensile forces exaggerate cracks and reduce shear resistances because they will decrease compression areas.

When we have appreciable axial compression, the following equation can be used to compute the shear-carrying capacity of a concrete member:

$$V_c = 2\left(1 + \frac{N_u}{2000A_g}\right)\lambda\sqrt{f_c'}b_w d \qquad (ACI Equation 11-4)$$

For a member subjected to a significant axial tensile force, the shear capacity of the concrete may be determined from the following expression:

$$V_c = 2\left(1 + \frac{N_u}{500A_g}\right)\lambda\sqrt{f_c}b_w d \qquad (ACI Equation 11-8)$$

In this expression,  $N_u$ , the axial load, is minus if the load is tensile. You might note that if the computed value of  $N_u/A_g$  for use in this equation is 500 psi or more, the concrete will have lost its capacity to carry shear. (The value of  $V_c$  used need not be taken as less than zero.)

The SI values for ACI Equations 11-4 and 11-8 are, respectively,

$$\begin{split} V_c &= \left(1 + \frac{N_u}{14A_g}\right) \left(\frac{\lambda \sqrt{f_c'}}{6}\right) b_w d \\ V_c &= \left(1 + \frac{0.3N_u}{A_g}\right) \left(\frac{\lambda \sqrt{f_c'}}{6}\right) b_w d \end{split}$$

Instead of using ACI Equation 11-4 to compute the shear capacity of sections subject to axial compressive loads, ACI Equation 11-5 may be used. In this equation, a revised moment,  $M_m$ , may be substituted for  $M_u$  at the section in question, and  $V_u d/M_u$  is not limited to 1.0 as it normally is. For this case,  $V_c$  may not be larger than the value obtained with ACI Equation 11-7.

$$V_c = \left(1.9\lambda\sqrt{f_c'} + 2500\rho_w \frac{V_u d}{M_u}\right) b_w d \le 3.5\lambda\sqrt{f_c'} b_w d$$
 (ACI Equation 11-6)

$$M_m = M_u - N_u \left(\frac{4h - d}{8}\right)$$
 (ACI Equation 11-7)

$$V_c$$
 may not be  $> 3.5\lambda \sqrt{f_c'} b_w d \sqrt{1 + \frac{N_u}{500 A_g}}$  (ACI Equation 11-8)

In SI units, ACI Equation 11-5 is

$$V_c = \left(\lambda \sqrt{f_c'} + 120\rho_w \frac{V_u d}{M_u}\right) \frac{b_w d}{7} \le 0.3\lambda \sqrt{f_c'} b_w d$$

Equation 11-7 is

$$V_c = 0.3\lambda \sqrt{f_c'} b_w d\sqrt{1 + \frac{0.3N_u}{A_g}}$$

Example 8.7, which follows, illustrates the computation of the shear strength of an axially loaded concrete member.

#### Example 8.7

For the concrete section shown in Figure 8.21 for which  $f'_c$  is 3000 psi, normal weight ( $\lambda = 1.0$ ),

- (a) Determine  $V_c$  if no axial load is present using ACI Equation 11-3.
- (b) Compute V<sub>c</sub> using ACI Equation 11-4 if the member is subjected to an axial compression load of 12,000 lb.
- (c) Repeat part (b) using revised ACI Equation 11-5. At the section in question, assume  $M_u = 30$  ft-k and  $V_u = 40$  k. Use  $M_m$  in place of  $M_u$ .
- (d) Compute  $V_c$  if the 12,000-lb load is tensile.

![](_page_271_Figure_17.jpeg)

**FIGURE 8.21** Beam cross section for Example 8.7.

#### SOLUTION

(a) 
$$V_c = 2(1.0)\sqrt{3000} \text{ psi} (14 \text{ in.}) (23 \text{ in.}) = 35,273 \text{ lb}$$

**(b)** 
$$V_c = 2 \left[ 1 + \frac{20,000 \text{ lb}}{(2000) (14 \text{ in.}) (26 \text{ in.})} \right] [(1.0)\sqrt{3000} \text{ psi}] (14 \text{ in.}) (23 \text{ in.}) = 36,242 \text{ lb}  $< 3.5(1.0)\sqrt{3000} \text{ psi} (14 \text{ in.}) (23 \text{ in.}) = 61,728 \text{ lb}$$$

(c) 
$$M_m = (12 \text{ in/ft}) (30,000 \text{ ft-lb}) - 12,000 \text{ lb} \left(\frac{4 \times 26 \text{ in.} - 23 \text{ in.}}{8}\right) = 238,500 \text{ in-lb}$$
 
$$\frac{V_u d}{M_m} = \frac{(40 \text{ k}) (23 \text{ in.})}{238.5 \text{ in-k}} = 3.857 > 1.00, \quad \text{however, it is not limited to 1.0}$$
 
$$V_c = \left[1.9 (1.0) \sqrt{3000} \text{ psi} + (2500) \left(\frac{3.00 \text{ in.}^2}{(14 \text{ in.}) (23 \text{ in.})}\right) (3.857)\right] (14 \text{ in.}) (23 \text{ in.})$$
 
$$= \underline{62,437 \text{ lb}}$$

But not 
$$> 3.5(1.0)\sqrt{3000}$$
 psi (14 in.) (23 in.)  $\sqrt{1 + \frac{12,000 \text{ lb}}{(500 \text{ psi}) (14 \text{ in.}) (26 \text{ in.})}}$  = 63,731 lb OK

(d) 
$$V_c = 2 \left[ 1 + \frac{-12,000 \text{ lb}}{(500) (14 \text{ in.}) (26 \text{ in.})} \right] [(1.0)\sqrt{3000} \text{ psi}(14 \text{ in.}) (23 \text{ in.})]$$

$$= 32,950 \text{ lb}$$

### 8.14 Shear Design Provisions for Deep Beams

There are some special shear design provisions given in Section 11.7 of the code for deep flexural members with  $\ell_n/d$  values equal to or less than four that are loaded on one face and supported on the other face, so that compression struts can develop between the loads and the supports. Such a member is shown in Figure 8.22(a). Some members falling into this class are short, deep, heavily loaded beams; wall slabs under vertical loads; shear walls; and perhaps floor slabs subjected to horizontal loads.

If the loads are applied through the sides or the bottom (as where beams are framing into its sides or bottom) of the member, as illustrated in Figure 8.22(b) and (c), the usual shear design provisions described earlier in this chapter are to be followed, whether or not the member is deep.

![](_page_272_Figure_11.jpeg)

FIGURE 8.22 Deep beam configurations.

The angles at which inclined cracks develop in deep flexural members (measured from the vertical) are usually much smaller than 45°—on some occasions being very nearly vertical. As a result, web reinforcing when needed has to be more closely spaced than for beams of regular depths. Furthermore, the web reinforcing needed is in the form of both horizontal and vertical reinforcing. These almost vertical cracks indicate that the principal tensile forces are primarily horizontal, and thus horizontal reinforcing is particularly effective in resisting them.

The detailed provisions of the code relating to shear design for deep beams, together with the applicable ACI Section numbers, are as follows:

- 1. Deep beams are to be designed using the procedure described in Appendix A of the code (Appendix C in this textbook) or by using a nonlinear analysis (ACI 11.7.2).
- **2.** The nominal shear strength,  $V_n$ , for deep beams shall not exceed  $10\sqrt{f_c'}b_wd$  (ACI 11.7.3).
- 3. The area of shear reinforcing,  $A_{\nu}$ , perpendicular to the span must at least equal  $0.0025 \ b_w s$ , and s may not be greater than d/5 or 12 in. (ACI 11.7.4.1). s is the spacing of the shear or torsion reinforcing measured in a direction parallel to the logitudinal reinforcing.
- **4.** The area of shear reinforcing parallel to the span must not be less than  $0.0015b_w s_2$ , and  $s_2$ may not be greater than d/5 or 12 in. (ACI 11.7.4.2).  $s_2$  is the spacing of shear reinforcing measured in a direction perpendicular to the beam's longitudinal reinforcement.

You will note that more vertical than horizontal shear reinforcing is required because vertical reinforcing has been shown to be more effective than horizontal reinforcing. The subject of deep beams is continued in Appendix C of this textbook.

#### **Introductory Comments on Torsion** 8.15

Until recent years, the safety factors required by design codes for proportioning members for bending and shear were very large, and the resulting large members could almost always be depended upon to resist all but the very largest torsional moments. Today, however, with the smaller members selected using the strength design procedure, this is no longer true, and torsion needs to be considered much more frequently.

Torsion may be very significant for curved beams, spiral staircases, beams that have large loads applied laterally off center, and even spandrel beams running between exterior building columns. These latter beams support the edges of floor slabs, floor beams, curtain walls, and façades, and they are loaded laterally on one side. Several situations where torsion can be a problem are shown in Figure 8.23.

When plain concrete members are subjected to pure torsion, they will crack along 45° spiral lines when the resulting diagonal tension exceeds the design strength of the concrete. Although these diagonal tension stresses produced by twisting are very similar to those caused by shear, they will occur on all faces of a member. As a result, they add to the stresses caused by shear on one side of the beam and subtract from them on the other.

Reinforced concrete members subjected to large torsional forces may fail quite suddenly if they are not provided with torsional reinforcing. The addition of torsional reinforcing does not change the magnitude of the torsion that will cause diagonal cracks, but it does prevent the members from tearing apart. As a result, they will be able to resist substantial torsional moments without failure. Tests have shown that both longitudinal bars and closed stirrups or spirals are necessary to intercept the numerous diagonal tension cracks that occur on all surfaces of beams subject to appreciable torsional forces. There must be a longitudinal bar in each corner of the stirrups to resist the horizontal components of the diagonal tension caused by torsion. Chapter 15 of this text is completely devoted to torsion.

![](_page_274_Picture_2.jpeg)

**FI GU RE 8.23** Some situations where torsion stresses may be significant.

### SI Example

### Example 8.8

Determine required spacing of #10 stirrups at the left end of the beam shown in Figure 8.24 if  $f_c' = 21$  MPa, normal weight, and  $f_v = 420$  MPa.

![](_page_275_Figure_5.jpeg)

#### SOLUTION

$$V_{II}$$
 @ left end = (4 m)(84.6 kN/m) = 338.4 kN

 $V_{\mu}$  @ a distance d from left end

$$= 338.4 \text{ kN} - \left(\frac{750 \text{ mm}}{1000 \text{ mm}}\right) (84.6 \text{ kN/m}) = 274.95 \text{ kN}$$
 
$$\phi V_c = (\phi) \left(\frac{\lambda \sqrt{f_c'}}{6}\right) b_w d = (0.75) \left[\frac{(1.0) \left(\sqrt{21} \text{ MPa}\right)}{6}\right] (400 \text{ mm}) (750 \text{ mm})$$
 
$$= 171 \quad 847 \quad \text{N} = 171.85 \text{ kN}$$
 
$$V_u = \phi V_c + \phi V_s$$
 
$$V_s = \frac{V_u - \phi V_c}{\phi} = \frac{274.95 \text{ kN} - 171.85 \text{ kN}}{0.75} = 137.47 \text{ kN}$$

#### **Assuming #10 Stirrups**

Theoretical 
$$s = \frac{A_v f_{yt} d}{V_s} = \frac{(2) (71 \text{ mm}^2) (420 \text{ MPa}) (750 \text{ mm})}{(137.47 \text{ kN}) (10^3)} = 325 \text{ mm}$$

Maximum s to provide minimum  $A_{\nu}$  for stirrups

$$s = \frac{3A_v f_{yt}}{b_w} = \frac{(3)(2 \times 71 \text{ mm}^2)(420 \text{ MPa})}{400 \text{ mm}} = 447 \text{ mm}$$
 (ACI Equation 11-13)

$$V_s = 137.47 \text{ kN} < \frac{1}{3} \sqrt{f_c'} b_w d \qquad \text{(From ACI metric Section 11.4.4.3)}$$

$$= \frac{1}{3} \sqrt{21} \text{ MPa}(400 \text{ mm}) (750 \text{ mm}) = 458,257 \text{ N} = 458.26 \text{ kN} \qquad \underline{OK}$$

$$\therefore \text{ Maximum s} = \frac{d}{2} = \frac{700 \text{ mm}}{2} = 375 \text{ mm} \leftarrow$$

$$\text{Use s} = 325 \text{ mm}.$$

$$W_u = 84.6 \text{ kN/m}$$

$$W_u = 84.6 \text{ kN/m}$$

$$0 \text{ Maximum s} = \frac{d}{2} = \frac{700 \text{ mm}}{2} = 375 \text{ mm} \leftarrow$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ Maximum s} = \frac{d}{2} = \frac{700 \text{ mm}}{2} = 375 \text{ mm} \leftarrow$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

$$0 \text{ How metric Section 11.4.4.3}$$

### 8.17 Computer Example

#### Example 8.9

Repeat Example 8.2(c) using the Excel spreadsheet provided for Chapter 8.

#### SOLUTION

Open the spreadsheet and enter values in the cells highlighted in yellow (only in the Excel spreadsheets, not the printed example). These include values for  $V_u$ ,  $f_c'$ ,  $\lambda$ ,  $b_w$ , d,  $A_v$ , and  $f_{yt}$ . The required stirrup spacing s is shown in cell C19 (s=7.33 in.). Use good judgment to enter an actual value for spacing in the cell (choose s). A value of choose s=7.00 in. is shown. This value must not exceed the calculated value of s as well as the "Controlling  $s_{max}$ " listed a few cells. In the cell labeled "Check  $\phi V_c + \phi V_s$ " is the shear capacity of the section with the actual stirrup spacing you entered in "choose s." It will exceed the input value of  $V_u$  if the design is OK. In this case, the capacity is 61,548 lb, which exceeds  $V_u$  of 60,000 lb. Several warnings will appear if your "choose s=" value is too large.

### **Shear Design—Beams**

| $V_u =$                             | 60,000 | lb               |             |              |           |  |
|-------------------------------------|--------|------------------|-------------|--------------|-----------|--|
| $V_u = f'_c = \lambda = \lambda$    | 3000   | psi              |             |              |           |  |
| $\lambda =$                         | 1      |                  |             |              |           |  |
| $b_w =$                             | 14     | in.              |             |              |           |  |
| d =                                 | 24     | in.              |             |              |           |  |
| $A_{v} =$                           | 0.22   | in. <sup>2</sup> |             |              |           |  |
| $f_{yt} =$                          | 60,000 | psi              |             |              |           |  |
| $\phi =$                            | 0.75   |                  |             |              |           |  |
| $V_c =$                             | 36,807 | lb               |             |              |           |  |
| $\phi V_c =$                        | 27,605 | lb               | -           |              |           |  |
| $\phi V_c = \frac{1}{2} \phi V_c =$ | 13,803 | lb               |             |              |           |  |
| $V_s = (V_u - \phi V_c)/\phi =$     | 43,193 | lb               |             |              |           |  |
|                                     |        |                  | -           |              |           |  |
| Required $\phi V_s =$               | 32,395 | lb               |             |              |           |  |
| s =                                 | 7.33   | in.              |             |              |           |  |
| choose s =                          | 7.00   | in.              | -           |              |           |  |
|                                     |        |                  |             |              |           |  |
| $s_{\text{max}} =$                  | 12     | in.              | Code Sectio | n 11.4.5     | -         |  |
| A <sub>v min</sub> =                | 0.082  | in. <sup>2</sup> | Code Eq. 11 | 1-13         | -         |  |
| $s_{\text{max}} =$                  | 22.95  | in.              | also Code E | q. 11-13     |           |  |
| $s_{\text{max}} =$                  | 18.86  | in.              | Code Eq. 11 | 1-13 with 50 | psi limit |  |
| Controlling s <sub>max</sub> =      | 12.00  | in.              |             |              |           |  |
| Actual $\phi V_s =$                 | 33,943 | lb               |             |              |           |  |
| Check $\phi V_c - \phi V_s =$       | 61,548 | lb               |             |              |           |  |

#### **PROBLEMS**

**Problem 8.1** The ACI Code provides the following limiting shear values for members subject only to shear and flexure:  $2\sqrt{f_c'}$ ,  $4\sqrt{f_c'}$ , and  $8\sqrt{f_c'}$ . What is the significance of each of these limits?

**Problem 8.2** If the maximum shear force in a member occurs at a support, the code permits the designer to calculate the shear at a distance d from the face of the support in the presence of a certain condition. Describe the situation when this reduced shear may be used.

**Problem 8.3** Why does the code limit the maximum design yield stress that may be used in the design calculations for shear reinforcing to 60,000 psi (not including welded wire fabric)?

**Problem 8.4** What is shear friction and where is it most likely to be considered in reinforced concrete design?

#### **Shear Analysis**

**Problem 8.5** What is the design shear strength of the beam shown if  $f'_c = 4000$  psi and  $f_v = 60,000$  psi? No shear reinforcing is provided. (Ans. theoretical  $\phi V_c = 31,876$  lb,  $\phi V_c/2 = 15,938 \text{ lb controls}$ 

![](_page_277_Figure_11.jpeg)

**Problem 8.6** Repeat Problem 8.5 if the total depth of the beam is 32 in. and  $f'_c = 3000$  psi.

For Problems 8.7 to 8.9, compute  $\phi V_n$  for the sections shown if **Problem 8.9** (Ans. 38,331 lb)  $f_{yt}$  of stirrups is 60 ksi and  $f_c' = 4000$  psi.

**Problem 8.7** (Ans. 79,519 lb)

![](_page_278_Figure_3.jpeg)

![](_page_278_Figure_4.jpeg)

#### Problem 8.8

![](_page_278_Picture_6.jpeg)

#### **Shear Design**

**Problem 8.10** If  $f_c' = 3000$  psi,  $V_u = 60$  k, and  $b_w = \frac{1}{2}d$ , select a rectangular beam section if no web reinforcing is used. Use sand-lightweight concrete.  $b_w$  is an integer inch.

For Problems 8.11 to 8.19, for the beams and loads given, select stirrup spacings if  $f'_c = 4000$  psi normal-weight concrete and  $f_{yt} = 60,000$  psi. The dead loads shown include beam weights. Do not consider movement of live loads unless specifically requested. Assume #3  $\sqcup$  stirrups unless given otherwise.

**Problem 8.11** (One ans. 1 @ 6 in., 10 @ 12 in.)

![](_page_278_Figure_11.jpeg)

**Problem 8.12**

![](_page_279_Picture_3.jpeg)

**Problem 8.13** Repeat Problem 8.12 if live load positions are considered to cause maximum end and centerline shear. (*One ans*. 1 @ 4 in., 4 @ 8 in., 2 @ 10 in., 4 @ 13 in.)

**Problem 8.14**

![](_page_279_Figure_6.jpeg)

**Problem 8.15** (*One ans*. 1 @ 6 in., 8 @ 12 in.)

![](_page_279_Figure_8.jpeg)

**Problem 8.16** Use #4 stirrups.

![](_page_279_Figure_10.jpeg)

**Problem 8.17** Use #4 ⊔ stirrups. (*One ans.* 1 @ 3 in., 8 @ 5 in., 2 @ 8 in., 5 @ 10 in.)

![](_page_280_Figure_2.jpeg)

#### Problem 8.18

![](_page_280_Figure_4.jpeg)

**Problem 8.19** If the beam of Problem 8.14 has a factored axial compression load of 120 k in addition to other loads, calculate  $\phi V_c$  and redesign the stirrups. (*One ans.* 3 stirrups, 1 @ 4 in., 3 @ 10 in., 4 @ 12 in.)

**Problem 8.20** Repeat Problem 8.19 if the axial load is tensile. Use #4  $\sqcup$  stirrups.

For Problems 8.21 and 8.22, repeat the problems given using the Chapter 8 Excel spreadsheet.

**Problem 8.21** If  $V_u = 56,400$  lb at a particular section, determine the theoretical spacing of #3  $\sqcup$  stirrups for the beam of Problem 8.11. (*Ans.* Theoretical s = 10.68 in., use maximum = 10 in.)

**Problem 8.22** If  $V_u = \text{equals } 79,600 \text{ lb}$  at a particular section, determine the spacing of #4  $\sqcup$  stirrups for the beam of Problem 8.12.

**Problem 8.23** Prepare a flowchart for the design of stirrups for rectangular T or I beams.

#### **Problems in SI Units**

For Problems 8.24 to 8.26, for the beams and loads given, select stirrup spacings if  $f'_c = 21$  MPa and  $f_{yt} = 420$  MPa. The dead loads shown include beam weights. Do not consider movement of live loads. Use #10 ⊔ stirrups.

#### Problem 8.24

![](_page_281_Figure_5.jpeg)

**Problem 8.25** (*One ans.* #10 stirrups, 1 @ 100 mm, 13 @ 300 mm)

![](_page_281_Figure_7.jpeg)

#### Problem 8.26

![](_page_281_Figure_9.jpeg)

