# **APPENDIX D** Seismic Design of Reinforced Concrete Structures

### **D.1 Introduction**

Seismic design of reinforced concrete structures is a subject that could easily fill an entire textbook. Many organizations are dedicated to studying the earthquake response and design of structures. Each earthquake teaches us new lessons, and we continually refine our code requirements based on such lessons.

Earthquakes produce horizontal and vertical ground motions that shake the base of a structure. Because the movement of the rest of the structure is resisted by the structure's mass (inertia), ground shaking creates deformations in the structure, and these deformations produce forces in the structure. Earthquake motions produce seismic loads on structures, even those that are not part of the lateral load-resisting system. These forces can be both horizontal and vertical and can subject structural elements to axial forces, moments, and shears whose magnitudes depend on many of the properties of the structure, such as its mass, its stiffness, and its ductility. Also important is the structure's period of vibration (the time that the structure takes to vibrate back and forth laterally). In this appendix, the seismic design of reinforced concrete structures is approached from the viewpoint of code application. Calculation of seismic design forces is discussed, element design and detailing for those forces is explained, and examples are provided.

The seismic design of reinforced concrete structures is addressed by the general design provisions of ACI 318 and also by the special seismic-design provisions of Chapter 21 of ACI 318. Reinforced concrete structures designed and detailed according to ACI 318 are intended to resist earthquakes without structural collapse. In general terms, the strength of an earthquake depends on the accelerations, velocities, and displacements of the ground motion that it produces. Seismic design loads are prescribed by *Minimum Design Loads for Buildings and Other Structures* (ASCE/SEI 7-10).1 In that document, the severity of the design earthquake motion for a concrete structure is described in terms of the structure's *seismic design category* (SDC), which depends on the structure's geographic location and also the soil on which it is built. Structures assigned to the lowest seismic design category, SDC A, must meet only the general design provisions of ACI 318 and do not have to meet the special requirements of Chapter 21 of ACI 318. Structures assigned to higher SDCs (B, C, D, E, or F) have increasing seismic demands, however, and must meet the requirements of Chapter 21 of ACI 318, which increase in severity with higher SDC. For those higher seismic design categories, the requirements of Chapter 21 of ACI 318 are based on the assumption that a reinforced concrete structure responds inelastically. Inelastic behavior is characterized by yielding of the reinforcing steel as described in Chapter 3, Section 3.6 of this textbook. Structural members whose reinforcing steel yields can dissipate some of the energy imparted to the structure by an earthquake, and the forces that develop in such members during an earthquake are less than they would be if the structure responded elastically. Seismic design categories are discussed in more detail in Section D.5 of

<sup>1</sup> American Society of Civil Engineers, *Minimum Design Loads for Buildings and Other Structures* (Reston, VA: ASCE), Chapters 11–23.

this appendix. For now, let's continue with a discussion of the fundamental steps of earthquake design according to the load provisions of ASCE 7-10 and the element design and detailing provisions of Chapter 21 of ACI 318-11.

### **Maximum Considered Earthquake**

Areas with high risk of significant ground motion, such as the West Coast of the United States, have the highest seismic hazard level. Most areas of the United States have at least some level of seismic risk, however. A large part of ASCE 7-10 is dedicated to determining seismic design forces. These forces are based on the "maximum considered earthquake" (MCE), which is an extreme earthquake, considered to occur only once every 2500 years. The severity of MCElevel ground shaking is described in terms of the spectral response acceleration parameters  $S_S$ and S<sub>1</sub>, whose values are given in contour maps provided within ASCE 7 and also available from the United States Geological Service (USGS) website (www.usgs.gov). The parameter  $S_S$  is a measure of how strongly the MCE affects structures with a short period (0.2 sec). The parameter  $S_1$  is a measure of how strongly the MCE affects structures with a longer period (1 sec). These are called spectral response parameters, and their values are provided in Figures 22-1 through 22-14 of ASCE/SEI 7-10.2 If  $S_1$  is less than or equal to 0.04 and  $S_S$  is less than or equal to 0.15, the structure is assigned to SDC A. Higher values of  $S_1$  and  $S_2$ correspond to successively higher seismic design categories.  $S_S$  and  $S_1$  are proportions or ratios of gravity. For example, in parts of southern California, the value of  $S_S$  may be 1.0 (100% of the acceleration of gravity), whereas in parts of the Midwest, it may be only a few percent.

#### **Soil Site Class D.3**

The spectral response parameters determined above are modified based on the structure's soil site class. The soil at the site is classified into soil site class A through F in accordance with Table 20.3-1 and Section 20.3 of ASCE/SEI 7, using only the upper 100 ft of the site profile. The lowest soil site class, site class A (hard rock), gives a relatively low seismic design force. Higher soil site classes give higher seismic design forces. If such site-specific data are not available, ASCE/SEI 7 permits the registered design professional preparing the soil investigation report to estimate soil properties from known geologic conditions. If the soil properties are not sufficiently known, site class D is used unless the authority having jurisdiction or geotechnical data determines that site class E or F is appropriate. Once the soil site class is assigned, the corresponding site coefficients for short and long periods,  $F_a$  and  $F_v$ , respectively, are determined using Table D.1 and the values of  $S_S$  and  $S_1$  as described above.

### MCE Spectral Response Accelerations and **Design Response Accelerations**

The MCE spectral response accelerations (related to design forces) for short periods  $(S_{MS})$  and for longer (1-s) periods  $(S_{M1})$  are obtained by multiplying each spectral response acceleration parameter  $(S_S \text{ and } S_1)$  by its corresponding site coefficient:

$$S_{MS} = F_a S_S$$
 (ASCE/SEI Equation 11.4-1)

$$S_{M1} = F_v S_1$$
 (ASCE/SEI Equation 11.4-2)

<sup>&</sup>lt;sup>2</sup> ASCE/SEI 7-10, pp. 210-227.

**TABLE D.1** Maximum Considered Earthquake Spectral Response Acceleration Parameters

|            | Mapped Maximum Considered Earthquake<br>Spectral Response Acceleration Parameter at Short Period |             |              |             |              |
|------------|--------------------------------------------------------------------------------------------------|-------------|--------------|-------------|--------------|
| Site Class | SS<br>≤ 0.25                                                                                     | SS<br>= 0.5 | SS<br>= 0.75 | SS<br>= 1.0 | SS<br>≥ 1.25 |
| A          | 0.8                                                                                              | 0.8         | 0.8          | 0.8         | 0.8          |
| B          | 1.0                                                                                              | 1.0         | 1.0          | 1.0         | 1.0          |
| C          | 1.2                                                                                              | 1.2         | 1.1          | 1.0         | 1.0          |
| D          | 1.6                                                                                              | 1.4         | 1.2          | 1.1         | 1.0          |
| E          | 2.5                                                                                              | 1.7         | 1.2          | 0.9         | 0.9          |
| F          | A site response analysis must be performed (see Section 11.4.7, ASCI/ACI 7-10).                  |             |              |             |              |

*Note:* Use straight-line interpolation for intermediate values of *SS* .

**(a)** Site Coefficient, *Fa* , based on Site Class and Mapped Maximum Considered Earthquake Spectral Response Acceleration Parameter at Short Period [from American Society of Civil Engineers/Structural Engineers Institute, *Minimum Design Loads for Buildings and Other Structures*. ASCE/SEI 7-10 (Reston, VA: American Society of Civil Engineers), Table 11.4-1].

|            |             |             | Mapped Maximum Considered Earthquake | Spectral Response Acceleration Parameter at One-Second Period                   |             |
|------------|-------------|-------------|--------------------------------------|---------------------------------------------------------------------------------|-------------|
| Site Class | S1<br>≤ 0.1 | S1<br>= 0.2 | S1<br>= 0.3                          | S1<br>= 0.4                                                                     | S1<br>≥ 0.5 |
| A          | 0.8         | 0.8         | 0.8                                  | 0.8                                                                             | 0.8         |
| B          | 1.0         | 1.0         | 1.0                                  | 1.0                                                                             | 1.0         |
| C          | 1.7         | 1.6         | 1.5                                  | 1.4                                                                             | 1.3         |
| D          | 2.4         | 2.0         | 1.8                                  | 1.6                                                                             | 1.5         |
| E          | 3.5         | 3.2         | 2.8                                  | 2.4                                                                             | 2.4         |
| F          |             |             |                                      | A site response analysis must be performed (see Section 11.4.7, ASCI/ACI 7-10). |             |

*Note:* Use straight-line interpolation for intermediate values of *S*1.

**(b)** Site Coefficient, *Fv* , based on Mapped Maximum Considered Earthquake Spectral Response Acceleration Parameter at One-Second Period [from American Society of Civil Engineers/Structural Engineers Institute, *Minimum Design Loads for Buildings and Other Structures*. ASCE/SEI 7-10 (Reston, VA: American Society of Civil Engineers), Table 11.4-2].

The site coefficients can be as high as 2.5 for *SS* , and as high as 3.5 for *S*<sup>1</sup> (site class E). If the designer uses the default site class D instead of a lower site class to avoid the expense of a soil report, the required seismic design forces may be significantly increased.

Design forces are based on a design earthquake (less severe than the maximum considered earthquake, considered to occur only once every 500 years). The design spectral acceleration parameters, *SDS* and *SD*1, are obtained by multiplying the values of *SMS* and *SM*<sup>1</sup> by <sup>2</sup> 3 :

$$S_{DS} = \frac{2}{3}S_{MS}$$
 (ASCE/SEI Equation 11.4-3)  
 $S_{D1} = \frac{2}{3}S_{M1}$  (ASCE/SEI Equation 11.4-4)

### **D.4 Risk and Importance Factors**

The occupancy of a building is an important consideration in determining its SDC. A leanto shed on a farm is obviously less important than a hospital, fire station, or police station. Chapter 1 of ASCE/SEI 7 lists four risk categories in Table 1.5-1. These risk categories are correlated to importance factors that range from 1.0 to 1.5 (ASCE/SEI 7-10, Table 11.5-2). Risk categories and importance factors are combined into a single table (Table D.2) below.

**TABLE D.2** Risk Category of Buildings and Other Structures for Earthquake Loads*<sup>a</sup>* (from ASCE/SEI 7-10, Tables 1.5-1 and 1.5-2)

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |               | Seismic<br>Importance |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|-----------------------|
| Use or Occupancy of Buildings and Structures                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Risk Category | Factor, I<br>e        |
| Buildings and other structures that represent a low risk to human<br>life in the event of failure                                                                                                                                                                                                                                                                                                                                                                                                          | I             | 1.00                  |
| All buildings and other structures except those listed in Risk Cate<br>gories I, III, and IV                                                                                                                                                                                                                                                                                                                                                                                                               | II            | 1.00                  |
| Buildings and other structures, the failure of which could pose a<br>substantial risk to human life                                                                                                                                                                                                                                                                                                                                                                                                        | III           | 1.25                  |
| Buildings and other structures, not included in Risk Category IV,<br>with potential to cause a substantial economic impact and/or mass<br>disruption of day-to-day civilian life in the event of failure                                                                                                                                                                                                                                                                                                   |               |                       |
| Buildings and other structures not included in Risk Category IV<br>(including, but not limited to, facilities that manufacture, process,<br>handle, store, use, or dispose of such substances as hazardous<br>fuels, hazardous chemicals, hazardous waste, or explosives) con<br>taining toxic or explosive substances where their quantity exceeds<br>a threshold quantity established by the authority having jurisdiction<br>and is sufficient to pose a threat to the public if released               |               |                       |
| Buildings and other structures designated as essential facilities                                                                                                                                                                                                                                                                                                                                                                                                                                          | IV            | 1.50                  |
| Buildings and other structures, the failure of which could pose a<br>substantial hazard to the community                                                                                                                                                                                                                                                                                                                                                                                                   |               |                       |
| Buildings and other structures (including, but not limited to, facilities<br>that manufacture, process, handle, store, use, or dispose of such<br>substances as hazardous fuels, hazardous chemicals, or hazardous<br>waste) containing sufficient quantities of highly toxic substances<br>where the quantity exceeds a threshold quantity established by the<br>authority having jurisdiction to be dangerous to the public if released<br>and is sufficient to pose a threat to the public if releasedb |               |                       |
| Buildings and other structures required to maintain the functionality<br>of other Risk Category IV structures                                                                                                                                                                                                                                                                                                                                                                                              |               |                       |

*<sup>a</sup>*The component importance factor, *I <sup>p</sup>* , applicable to earthquake loads is not included in this table because it is dependent on the importance of the individual component rather than that of the building as a whole or its occupancy.

*<sup>b</sup>*Buildings and other structures containing toxic, highly toxic, or explosive substances shall be eligible for classification to a lower Risk Category if it can be demonstrated to the satisfaction of the authority having jurisdiction by a hazard assessment as described in Section 1.5.2 that a release of the substances is commensurate with the risk associated with that Risk Category.

**TABLE D.3** Seismic Design Category (SDC) Based on Risk Category and Response Acceleration Parameter

|                             | Risk Category |     |    |  |  |
|-----------------------------|---------------|-----|----|--|--|
| Value of $\mathcal{S}_{DS}$ | l or II       | III | IV |  |  |
| S <sub>DS</sub> < 0.167     | А             | Α   | А  |  |  |
| $0.167 \le S_{DS} < 0.33$   | В             | В   | С  |  |  |
| $0.33 \le S_{DS} < 0.50$    | С             | С   | D  |  |  |
| $0.50 = S_{DS}$             | D             | D   | D  |  |  |

(a) Based on Short-Period Response Acceleration Parameter (from ASCE/SEI 7-10, Table 11.6-1).

|                            | Risk Category |     |    |  |  |
|----------------------------|---------------|-----|----|--|--|
| Value of $S_{D1}$          | l or II       | III | IV |  |  |
| S <sub>D1</sub> < 0.067    | А             | А   | А  |  |  |
| $0.067 \le S_{D1} < 0.133$ | В             | В   | С  |  |  |
| $0.133 \le S_{D1} < 0.20$  | С             | С   | D  |  |  |
| $0.20 \le S_{D1}$          | D             | D   | D  |  |  |

<sup>(</sup>b) Based on One-Second Period Response Acceleration Parameter (from ASCE/SEI 7-10, Table 11.6-2).

### D.5 Seismic Design Categories

Seismic design categories are assigned using Table D.3 of this text and depend on the *seismic hazard level*, *soil type*, *risk*, and *use*. The seismic hazard level depends on the geographic location of the structure. Where  $S_1$  is less than 0.75, the seismic design category can be determined from Table D.3(a) alone where certain conditions apply.<sup>3</sup> When Table D.3(a) and (b) give different results for the same structure, the more severe SDC is used. Table D.3 does not contain SDC E or SDC F. Structures with risk category I, II, or III that are located where the mapped spectral response acceleration parameter at 1-s period,  $S_1$ , is greater than or equal to 0.75 are assigned to SDC E. Structures with risk category IV that are located where  $S_1 \ge 0.75$  are assigned to SDC F.

### D.6 Seismic Design Loads

#### **Vertical Forces**

Vertical seismic loads,  $E_v$ , are based on the value of  $S_{DS}$  (the design spectral response acceleration parameter) and the dead load, D.

$$E_{v} = 0.2S_{DS}D$$
 (ASCE/SEI 7-10 Equation 12.4-4)

<sup>&</sup>lt;sup>3</sup> ASCE/SEI 7-10 Section 11.4.

The vertical seismic load must be considered to act either upward or downward, whichever is more critical for design. The critical design load combination for most reinforced concrete columns usually occurs below their balanced point. In this region, columns generally have less moment capacity if axial compression is decreased (see Figures 10.4 and 10.8 in Chapter 10 of this textbook). Hence, an upward seismic load would result in reduced moment capacity.

#### **Lateral Forces**

Structures assigned to seismic design category A are designed for the effects of static lateral forces applied independently in each of two orthogonal plan directions. In each direction, the design lateral forces are applied simultaneously at all levels. The design lateral force at each level is determined as follows:

$$F_x = 0.01W_x$$
 (ASCE/SEI 7-10 Equation 1.4-1)

where

 $F_x$  = the design lateral force applied at story x

 $W_x$  = the portion of the total dead load of the structure, D, located or assigned to level

Quite simply, a structure assigned to SDC A is designed for a lateral seismic load equal to 1% of its design dead load. Structures assigned to SDC A must also meet requirements for load path connections, connection to supports, and anchorage of concrete or masonry walls.<sup>4</sup>

Structures assigned to SDC B through SDC F must be designed using a more detailed method. One such method is the equivalent lateral force procedure, in which the design seismic base shear, V, in each principal plan direction is determined as:

$$V = C_s W$$
 (ASCE/SEI 7-10 Equation 12.8-1)

where

 $C_s$  = the seismic response coefficient determined in accordance with ASCE/SEI Section

W = the effective seismic weight (ASCE/SEI Section 12.7.2)

It includes the total dead load and other loads that are likely to be present during an earthquake. For example, at least 25% of the floor live load in storage areas must be included. Where partitions are present, the larger of the actual partition weight or 10 psf (0.48 kN/m<sup>2</sup>) must be included. The total operating weight of permanent equipment must be included. Where the flat roof snow load,  $P_f$ , exceeds 30 psf (1.44 kN/m<sup>2</sup>), 20% of the uniform design snow load, regardless of actual roof slope, is included.

The seismic response coefficient,  $C_s$ , is determined by

$$C_S = \frac{S_{DS}}{R/I_a}$$
 (ASCE/SEI 7-10 Equation 12.8-2)

and need not exceed

$$C_S = \frac{S_{DI}}{T(R/I_e)}$$
 for  $T \le T_L$  (ASCE/SEI 7-10 Equation 12.8-3)

<sup>&</sup>lt;sup>4</sup> ASCE/SEI 7-10 Section 11.7.

or

$$C_S = \frac{S_{D1}T_L}{T^2(R/I_a)}$$
 for  $T > T_L$  (ASCE/SEI 7-10 Equation 12.8-4)

In no case is  $C_S$  permitted to be less than  $0.044I_eS_{DS}$  or less than 0.01.

When  $S_1 \ge 0.6$  g,

$$C_S = \frac{0.5S_1}{R/I}$$
 (ASCE/SEI 7-10 Equation 12.8-6)

The fundamental period of the structure, T, in the direction under consideration is established using the structural properties of the resisting elements in a properly substantiated analysis. The fundamental period, T, must not exceed the product of the coefficient for upper limit on calculated period ( $C_u$ ) from Table 12.8-1 and the approximate fundamental period,  $T_a$ , determined from Equation 12.8-7. As an alternative to performing an analysis to determine the fundamental period, T, it is permitted to use the approximate building period,  $T_a$ , calculated in accordance with Section 12.8.2.1, directly.

The approximate fundamental period  $(T_a)$ , in s, can be determined from the following equation:

$$T_a = C_t h_n^x$$
 (ASCE/SEI 7-10 Equation 12.8-7)

where  $h_n$  is the height in feet above the base to the highest level of the structure. For concrete moment resisting frames, the coefficient  $C_t$  is 0.016 (0.0466 in SI units) and x is 0.9.

As an alternative, the approximate fundamental period  $(T_a)$ , in seconds, can be found from the following equation for structures not exceeding 12 stories in height in which the seismic force-resisting system consists entirely of concrete moment resisting frames and the story height is at least 10 ft (3 m):

$$T_a = 0.1N$$
 (ASCE/SEI 7-10 Equation 12.8-8)

where N = number of stories.

Whereas  $T_a$  for concrete shear wall structures can be determined by

$$T_a = \frac{0.0019}{\sqrt{C_w}} h_n \qquad (ASCE/SEI 7-10 Equation 12.8-9)$$

where  $h_n$  is as defined previously and  $C_w$  is calculated as follows:

$$C_{w} = \frac{100}{A_{B}} \sum_{i=1}^{x} \left(\frac{h_{n}}{h_{i}}\right)^{2} \frac{A_{i}}{\left[1 + 0.83 \left(h_{i}/D_{i}\right)^{2}\right]}$$
 (ASCE/SEI 7-10 Equation 12.8-10)

where

 $A_{R}$  = area of base of structure, ft<sup>2</sup>

 $A_i$  = web area of shear wall "i" in ft<sup>2</sup>

 $D_i = \text{length of shear wall "i" in ft}$ 

 $h_i$  = height of shear wall "i" in ft

x = number of shear walls in the building effective in resisting lateral forces in the direction under consideration

The total design seismic base shear, V, is distributed to each building level in accordance with the following expressions:

$$F_r = C_{vr}V$$
 (ASCE/SEI 7-10 Equation 12.8-11)

$$C_{vx} = \frac{w_x h_x^k}{\sum_{i=1}^n w_i h_i^k}$$
 (ASCE/SEI 7-10 Equation 12.8-12)

where

 $w_r$  or  $w_i$  = the portion of the total effective weight of the structure, W, assigned to level x or i, respectively

k = an exponent related to the structure period as follows:

for structures having a period of 0.5 sec or less, k = 1

for structures having a period of 2.5 sec or more, k = 2

for structures having a period between 0.5 sec and 2.5 sec, k shall be 2 or shall be determined by linear interpolation between 1 and 2

Structures that respond elastically to earthquakes generally incur large seismic forces. If a structure is designed and detailed to be capable of nonlinear inelastic response, it will be subjected to lower seismic forces, however, even for the same earthquake at the same site. The response modification coefficient, R, reduces the design seismic force for structures capable of responding inelastically. As shown in Table D.4, this coefficient is 3.0 for ordinary concrete moment frames, 5.0 for intermediate concrete moment frames, and 8.0 for special concrete moment frames. In this table, the terms ordinary, intermediate, and special refer to increasingly severe levels of seismic detailing and are discussed later in this appendix. Higher values of R correspond to lower seismic design forces, since R appears in the denominator of the equation for seismic design base shear. A special concrete moment frame must be designed for only  $\frac{3}{8}$  the seismic base shear of a geometrically identical ordinary concrete moment frame.

Structures assigned to SDC A need not comply with the requirements of Chapter 21 of ACI 318. Structures assigned to SDC B and higher must comply with successively more severe requirements within that chapter. For example, structures assigned to SDC B must satisfy ACI 318 Section 21.1.2; structures assigned to SDC C must satisfy ACI 318 Sections 21.1.2 and 21.1.8; and structures assigned to SDC D through F must satisfy ACI 318 Sections 21.1.2 through 21.1.8 and Sections 21.11 through 21.13.

More complex structures must be designed using the general response spectra method or site-specific, ground-motion procedures. In the general response spectra method, the design

 
 TABLE D.4
 Response Modification Coefficients for Different Seismic Force–Resisting Systems
 (from ASCE/SEI 7-10, Table 12.2-1, Abridged)

|                         | Seismic Force-Resisting System                 | R*  |
|-------------------------|------------------------------------------------|-----|
|                         | Special Reinforced Concrete Shearwall          | 5   |
| Design Well Order       | Ordinary Reinforced Concrete Shearwall         | 4   |
| Bearing Wall System     | Detailed Plain Concrete Shearwall              | 2   |
|                         | Ordinary Plain Concrete Shearwall              | 1.5 |
|                         | Special Reinforced Concrete Shearwall          | 6   |
|                         | Ordinary Reinforced Concrete Shearwall         | 5   |
|                         | Detailed Plain Concrete Shearwall              | 2   |
| Building Frame System   | Ordinary Plain Concrete Shearwall              | 1.5 |
|                         | Special Reinforced Concrete Moment Frames      | 8   |
|                         | Intermediate Reinforced Concrete Moment Frames | 5   |
| Moment Resistant Frames | Ordinary Reinforced Concrete Moment Frames     | 3   |

<sup>\*</sup>Response Modification Coefficient, R.

![](_page_710_Figure_2.jpeg)

**FIGURE D.1** Design response spectrum (from ASCE/SEI 7-10, Figure 11.4-1).

response acceleration,  $S_a$ , depends on the fundamental building period, T, as shown in Figure D.1. That figure has four distinct regions, each with its own equation relating  $S_a$  to  $S_{DS}$  or  $S_{D1}$  and to T

where

 $S_{DS}=$  the design spectral response acceleration parameter at short periods

 $S_{D1}$  = the design spectral response acceleration parameter at 1-s period

T = the fundamental period of the structure, seconds

 $T_0 = 0.2S_{D1}/S_{DS}$ 

 $T_{\rm S} = S_{D1}/S_{DS}$ 

 $T_L = \text{long-period transition period(s)}$  shown in Chapter 22 of ASCE/SEI 7-10

