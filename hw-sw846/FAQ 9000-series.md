#  9000 Series: Miscellaneous Test Methods

EPA received many questions about hazardous waste test methods. The questions and responses for this category are listed below.

## Is SW-846 Method 9045D (pH of solids) applicable to organic liquid waste matrices?

Section 1.1 of Method 9045D states that the pH of non-aqueous liquids can be determined by the procedure. Water should be added to the non-aqueous liquid and mixed, because pH cannot be determined without the presence of water. The non-aqueous liquid should be separated from the water [aqueous phase] and the water analyzed. The pH of the water is representative of the pH of the waste thereby, the waste is not directly measured. Liquid organic wastes, such as oily wastes, may damage the pH electrode if the electrode is exposed directly to the oil.

Note: This does not mean that you must use Method 9045D to evaluate non-aqueous liquids to see if they exhibit the RCRA characteristic of corrosivity (40 CFR §261.22).

First, the characteristic of corrosivity is limited to wastes that are aqueous with pH less than or equal to 2 or greater than or equal to 12.5 using Method 9040C; OR any liquid that corrodes steel at a rate greater than 6.35 mm per year using Method 1110A.

A clarification was written to explain “aqueous” as a waste that is amenable to pH measurement. It is accepted that this can include liquids, gels, and sols. The inclusion of Method 1110(A) in the regulation was discussed in the original background document. The intention was to regulate liquids that have pH between 2 and 4, but can corrode steal at a rate that can cause harm to humans and/or the environment in a relatively short period of time.

When a sample is so corrosive that it exceeds the capacity of the electrode and/or the meter (for both high and low pH), the analyst may want to include additional testing to support Method 9040C. Diluting the waste in water (similar to Method 9045D) and measuring the pH again can demonstrate that the original pH is much less than 2 or much greater than 12.5. Additionally, millivolt readings can be used to calculate pH values in support of Method 9040C.

Method 9045D may be used to evaluate pH properties of non-aqueous liquids, solids, and sludges, but not for the RCRA characteristic of corrosivity. Organic liquids may be diluted/extracted in water according to Method 9045D, and the pH of the aqueous phase can be measured. If the organic liquid (such as organic acids) contributes hydronium ions to the solution, the measured pH is reflective of the pH of the organic liquid. However, if the organic liquid (such as hexane) does not contribute hydronium ions, the pH being measured is that of the water that was used for the dilution/extraction. It should be noted that many organic liquids (even those miscible with water) may interfere with and/or damage pH electrodes.

Other Categories: Hazardous Waste Characteristics

## Is the use of weighted least squares regression appropriate for solid and hazardous waste measurements of cyanide and phenol instead of linear regression?

Is the use of weighted least squares regression appropriate for solid and hazardous waste measurements of cyanide and phenol instead of linear regression, specifically as it relates to EPA 9012B and EPA 9066 sample analyses?

Ordinary least squares (OLS) regression is a specific application of weighted least squares (WLS) regression in which each of the weighting factors is assigned a value of unity (“1”). OLS is straightforward – especially when applied to a linear model – and the rationale for use and underlying mathematics are easily understood. However, implicit in OLS is the assumption that the variance associated with each calibration level is constant across the entire calibration range. Intuitively, we know that this assumption is not entirely valid. As a result, un-weighted OLS regression tends to generate calibration curves that fit higher concentration points more closely than those at lower concentrations.

Weighted least squares (WLS) regression would appear to be an attractive alternative and, in principle, would yield more representative fitting of experimental data when properly applied to a sufficient number of data points. However, estimation of appropriate weighting factors is challenging, and poor estimates may significantly impact the quality of the fitted data to the empirical calibration model.

For example, WLS requires that replicate calibration standards be analyzed at each concentration level in order to assess variance for each concentration value. Clearly, this is not a practical approach for a production laboratory. SW-846 Method 8000 discusses approaches to calibration for gas chromatography methods, and provides example weighting factors that are reciprocal values of either concentrations, concentrations squared, or of variances themselves (if available). Each approach has its advantages as well as limitations.

WLS may be an appropriate calibration modeling approach for cyanides and phenol if supported by the empirical data, characteristics of the methods, and other program-specific needs. Any model applied to actual data should do more than just “fit the data” – it should be supported by the analytical methodology, detection characteristics, and physiochemical behavior of the analyte within the measurement system. For example, in optical absorption spectroscopy, we have a well-defined physical model, called the Beer-Lambert Law, which describes the linear relationship between analyte concentration and absorption of incident radiation. If we happened to measure calibration sample responses and found that a quadratic model yielded an acceptable representation of those data, use of this model would be in direct contrast to what we know about absorption of light and would not be valid (even though it “worked”).

You can find a summary overview of various EPA programs’ uses and needs for calibration curve modeling in "Calibration Curves: Program Use/Needs".

Other Category: Detection & Quantitation

## Can you provide more definitive guidance regarding the interpretation of “as soon as possible” in SW-846 Methods 9040 and 9045?

Methods 9040 and 9045 for pH both say that samples should be analyzed as soon as possible. 40 CFR 136 Table II defines the maximum holding time for Hydrogen ion (pH) as 15 minutes.

Can you provide more definitive guidance regarding the interpretation of “as soon as possible”?

Methods 9045D and 9040C can be done in the field, but often field conditions cannot be controlled and may be unfavorable for accurate analyses. The methods are generally meant to be used in a laboratory setting under controlled conditions.

Because of potential changes from microbial activity, or shifts in chemical equilibrium, sample pH should be taken as soon as possible upon receipt at the laboratory. It is expected pH of collected samples would be analyzed within a few hours of laboratory receipt, and not the next day. The method is written to be followed sequentially with no undue delay between steps, except for the one hour settling time for soils in Section 7.2.2 or 15 minutes settling time for wastes in Section 7.3.2 of 9045D. Also, keep in mind that Methods 9045D and 9040C are Method Defined Parameter (MDP) methods that must be followed exactly as written with no modifications.

The holding time of "Analyze as soon as possible" is not clearly defined for SW-846, but is only recommended as a qualitative goal. In 2007, the definition for “immediately” was established as 15 minutes for the NPDES Program (40 CFR 136, Table II), however, that does not apply to the RCRA program and SW-846. Even though SW-846 Method 9040C (and Method 9045D) are MDP methods and must be followed prescriptively, Section 6.0 of Method 9040C on holding time is not prescriptive. The method authors recognized changes in pH begin as soon as a sample is put into a container and specified that samples should be analyzed as soon as possible. If they meant to analyze by an exact time, the method authors would have put that time into the method. Instead, they left it up to the user to do what is feasible as soon as possible. SW-846 also makes a distinction between "must" or "shall" language that is mandatory, as opposed to guidance language like "should" or "may". Note that Section 6.0 of Method 9040C uses the word "should".

The actual holding time for pH analysis should be specified in the quality assurance plan under which the sample was collected and agreed‐upon by all stakeholders involved, including those who have to measure the pH (be it in the laboratory or in the field). In the laboratory, we recommend performing the analysis within a few hours of receipt, and not the next day.

Other Categories: Holding Time & Preservation, Hazardous Waste Characteristics

## Can H3PO4 be used for preservation for SW-846 Method 9060A?

Method 9060A states, “In instances where analysis cannot be performed within 2 hr from time of sampling, the sample is acidified (pH < 2) with HCl or H2SO4.” However, our instrument manufacturer recommends using H3PO4 for preservation. Can H3PO4 be used for preservation for Method 9060A?

Method 9060A is on the list of method defined parameters (MDPs). Therefore, it must be followed exactly as written without deviation, even if substituting H2SO4 with H3PO4 is recommended by the instrument manufacturer. That being said, you can always seek permission for the substitution from your regulator or client. It will be rare that they grant permission, but depending on the circumstances for using the method, they may allow it. Be prepared to show equivalency data that the substitution works.

Other category: Holding Time & Preservation

## SW-846 Test Methods 9012B and 9010C and compliance with 40 CFR 268.40 footnote 7.

40 CFR 268.40 footnote 7 for cyanide analysis states you may use the test Methods 9010C or 9012B with the sample weight of 10 g with the distillation time of 1 hour and 15 minutes. Can a lab run test Method 9012B or 9010C and use 1 gram sample weight using the midi‐vap distillation and still be compliant with footnote 7?

Both Methods 9012B and 9010C are method defined parameters (MDPs) and must be followed prescriptively as written, with no exceptions. The text “are to be” in footnote 7 is synonymous with “must”. Therefore, use of a 10 gram of sample and distilling for 1 hour and 15 minutes is required to be compliant.

Other category: Inorganic

## For SW-846 test methods, what is the recommended holding time for nitrate in soil?

SW-846 Chapter 3 and Method 9056A don’t address holding time for nitrate in soil; what is the recommended holding time?

If nitrogen speciation in soil is needed (i.e., nitrite and nitrate), it is important to analyze as soon as possible because of the possibility of conversion from nitrite to nitrate. Microbial activity can cause changes over time.

Method 9056A is not clear on the holding time for solid matrices. Some holding times for solids are based simply on holding times for aqueous matrices (e.g., metals holding time for soils and waters is 180 days) and others are based on assumptions about constituent stability in solid versus aqueous matrices (e.g., holding time to extraction for semivolatile organic compounds is 7 days for waters and 14 days for soils).

For analysis of nitrogen as nitrate using either SW‐846 Method 9056 or EPA Methods for the Chemical Analysis of Water and Waste (MCAWW) Method 300.0, a holding time not to exceed 48 hours from collection through extraction and analysis for speciation of inorganic nitrogen is recommended, considering that nitrogen species conversion can happen relatively quickly regardless of the matrix.

Other category: Holding Time & Preservation

Last updated on September 26, 2024
Retrieved February 20, 2025
