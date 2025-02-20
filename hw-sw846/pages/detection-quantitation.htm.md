# Detection & Quantitation  

EPA received many questions about hazardous waste test methods. The questions and responses for this category are listed below.

------------------------------------------------------------------------

## Is the use of weighted least squares regression appropriate for solid and hazardous waste measurements of cyanide and phenol instead of linear regression?  

Is the use of weighted least squares regression appropriate for solid
and hazardous waste measurements of cyanide and phenol instead of linear
regression, specifically as it relates to EPA 9012B and EPA 9066 sample
analyses?

Ordinary least squares (OLS) regression is a specific application of
weighted least squares (WLS) regression in which each of the weighting
factors is assigned a value of unity ("1"). OLS is straightforward --
especially when applied to a linear model -- and the rationale for use
and underlying mathematics are easily understood. However, implicit in
OLS is the assumption that the variance associated with each calibration
level is constant across the entire calibration range. Intuitively, we
know that this assumption is not entirely valid. As a result,
un-weighted OLS regression tends to generate calibration curves that fit
higher concentration points more closely than those at lower
concentrations.

Weighted least squares (WLS) regression would appear to be an attractive
alternative and in principle WLS regression yields more representative
fitting of experimental data when properly applied to a sufficient
number of data points. However, estimation of appropriate weighting
factors is challenging, and poor estimates may significantly impact the
quality of the fitted data to the empirical calibration model.

For example, in the ideal case, WLS requires that replicate calibration
standards be analyzed at each concentration level in order to assess
variance for each concentration value. Clearly, this is not a practical
approach for the production laboratory. SW-846 Method 8000 discusses
approaches to calibration for gas chromatography methods, and provides
example weighting factors that are reciprocal values of either
concentrations, concentrations squared, or of variances themselves (if
available). Each approach has its advantages as well as limitations.

WLS may be an appropriate calibration modeling approach for cyanides and
phenol if supported by the empirical data, characteristics of the
methods, and other program-specific needs. Any model applied to actual
data should do more than just "fit the data" -- it should be supported
by the analytical methodology, detection characteristics, and
physiochemical behavior of the analyte within the measurement system.
For example, in optical absorption spectroscopy, we have a well-defined
physical model that relates the linear relationship between analyte
concentrations to absorption of incident radiation called the
Beer-Lambert Law. If we happened to measure calibration sample responses
and found that a quadratic model yielded an acceptable representation of
those data, use of this model would be in direct contrast to what we
know about absorption of light and would not be valid (even though it
"worked").

A summary overview of various EPA programs' uses and needs for
calibration curve modeling can be found in "[Calibration Curves:
Program
Use/Needs](/measurements-modeling/calibration-curves-program-uses-and-needs)".

Other Category: 9000 Series

------------------------------------------------------------------------

## Use of 2-tailed vs. 1-tailed t-values in SW-846 Chapter 9 formula for calculating confidence limits.  

The Chapter 9 formula for calculating confidence limit appears to use
the 2‐tailed t‐value to evaluate sample data against a regulatory limit
at 80% confidence. However, this type of evaluation involves a one‐sided
hypothesis (sample mean \> regulatory limit) and requires a 1‐tailed
t‐value which is a much smaller value than indicated in the Chapter 9
t‐value table.

Is this a mistake in the text or is there some reason for using the
2‐tailed t‐value when a 1‐tailed t‐value is typically used?

There is no mistake in the Chapter 9 text regarding use of the 2-tailed
t-value. Using a 0.2 probability (80% confidence interval) with the
2-tailed t-value and only looking at the upper end to determine if it
exceeds the hazardous waste level, is in effect, using a 1-tailed
t-value at 0.1 probability (90% confidence interval). The equivalency is
mentioned in the parentheses in footnote b under Table 9.2: "Tabulated
"t" values are for a two-tailed confidence interval and a probability
of 0.20 (the same values are applicable to a one-tailed confidence
interval and a probability of 0.10)."

Calculation wise, use Equation 6 where the confidence interval is
expressed as the mean plus or minus the 0.2 t-statistic times the
standard deviation. For hazardous waste determination, we are only using
the mean plus the 0.2 t-statistic times the standard deviation and
ignoring the mean minus the 0.2 t-statistic times the standard
deviation.

Finally, Section 9.1.1.1 states, "For the purposes of evaluating solid
wastes, the probability level (confidence interval) of 80% has been
selected. That is, for each chemical contaminant of concern, a
confidence interval (CI) is described within which μ occurs if the
sample is representative, which is expected of about 80 out of 100
samples. The upper limit of the 80% CI is then compared with the
appropriate regulatory threshold. If the upper limit is less than the
threshold, the chemical contaminant is not considered to be present in
the waste at a hazardous level; otherwise, the opposite conclusion is
drawn. One last point merits explanation. Even if the upper limit of an
estimated 80% CI is only slightly less than the regulatory threshold
(the worst case of chemical contamination that would be judged
acceptable), there is only a 10% (not 20%) chance that the threshold is
equaled or exceeded. That is because values of a normally distributed
contaminant that are outside the limits of an 80% CI are equally
distributed between the left (lower) and right (upper) tails of the
normal curve. Consequently, the CI employed to evaluate solid wastes is,
for all practical purposes, a 90% interval." In other words, the 80%
two-tailed value effectively becomes a 90% one-tailed value when we only
consider the upper end.

------------------------------------------------------------------------

## How should the lower limit of quantitation (LLOQ) for total Xylenes be reported for SW-846 test methods?  

How should the LLOQ for total Xylenes be reported, i.e., a sum of the
LLOQ for the 3 isomers?

Unless a separate integration for total xylenes is performed, the xylene
isomer LLOQs should be added together. Similarly, when reporting total
xylenes, the results of m&p xylene and o-xylene should be added
together.

It is important to point out that m- and p-xylene are difficult to
chromatographically separate under the conditions described in methods
8015 and 8260, while separation of the o-xylene peak from m+p-xylenes is
easier to achieve. If both m- and p-xylenes are present in a mixed stock
solution at the same concentration, then the calibration range for the
peak representing m- and p-xylene would be twice as high as for other
target analytes. Along with their corresponding lower limit of
quantitation (based on the low standard concentration).

Other category: 8000 Series

------------------------------------------------------------------------

## What is meant by the Lower Limit Of Quantitation (LLOQ) for SW-846 test methods?  

What is LLOQ?

SW-846 Chapter One defines the Lower Limit Of Quantitation (LLOQ) as:
The lowest point of quantitation which, in most cases, is the lowest
concentration in the calibration curve. The LLOQ is initially verified
by spiking a clean control material (e.g., reagent water, method blanks,
Ottawa sand, diatomaceous earth, etc.) at the LLOQ and processing
through all preparation and determinative steps of the method.
Laboratory-specific LLOQ recovery limits should be established when
sufficient data points exist. See Section 9 of Methods 8000D and
6010D/6020B for additional guidance in establishing, implementing and
verifying LLOQs for organic and inorganic analytes. LLOQs should be
determined at a frequency established by the method, laboratory's
quality system, or project.

Other category: QA/QC

------------------------------------------------------------------------

## Are Method Detection Limit (MDL) studies required for SW-846 test methods?  

Method Detection Limit is no longer defined in Chapter One, nor is it
referenced in the SW-846 methods. Does that mean that MDL studies are no
longer required?

The EPA Office of Resource Conservation and Recovery (ORCR) that
publishes the SW‐846 test methods manual no longer uses the MDL, and
promotes the use of the Lower Limit of Quantitation (LLOQ) approach for
establishing the reporting limit for a respective test method or
laboratory SOP. EPA ORCR is in the process of transitioning existing
SW‐846 methods and preparing new methods to specifically address the
LLOQ approach and procedures for establishing, implementing, and
verifying it.

Other EPA programs (e.g., the Clean Water Act (CWA)) and projects still
utilize the MDL concept. In those cases when an MDL is needed, method
users may follow the procedure stipulated in Appendix B to 40 CFR Part
136 for determining an MDL.

Other Category: QA/QC

Last updated on September 26, 2024
