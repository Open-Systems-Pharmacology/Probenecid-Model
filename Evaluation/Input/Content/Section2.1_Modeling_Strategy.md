The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#5-references)). Relevant information on anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-references)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-references)) or otherwise referenced for the specific process.

A mean model was built based on clinical data from studies with intravenous and oral administration of probenecid by Dayton 1963 ([Dayton 1963](#5-references)), Emanuelsson 1987 ([Emanuelsson 1987](#5-references)), Vree 1992 ([Vree 1992](#5-references)), Selen 1982 ([Selen 1982](#5-references)), Wiebe 2020 ([Wiebe 2020](#5-references)) and Landersdorfer 2009 [Landersdorfer 2009](#5-references). The studies reported individual (Dayton 1963 ([Dayton 1963](#5-references))) or mean (Emanuelsson 1987 ([Emanuelsson 1987](#5-references)), Vree 1992 ([Vree 1992](#5-references)), Selen 1982 ([Selen 1982](#5-references)), Wiebe 2020 ([Wiebe 2020](#5-references)) and Landersdorfer 2009 ([Landersdorfer 2009](#5-references))) plasma concentrations of probenecid. The studies by Vree 1992 also reported individual urine fraction of unchanged probenecid. The mean PBPK model was developed using a mean individual based on the demographic data for each study and if no demographic data were provided the following values were used; male, European, 30 years of age, 73 kg body weight and 176 cm body height. The relative tissue-specific expressions of the enzyme and transporter predominantly being involved in the metabolism/transport of probenecid (UGT1A9 and OAT3) were considered ([Meyer 2012](#5-references)). A Weibull function was fitted to describe the oral dissolution of probenecid. For the studies conducted by Vree, the tablet was broken in half and a shorter time to maximum concentration was observed and therefore a different Weibull function was fitted for these data. 

A specific set of parameters (see below) was optimized to describe the disposition of probenecid using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection and total error of the resulting description of data, 95% confidence interval of the identified parameter values and biological plausibility.

The model was then verified by simulating further clinical studies reporting pharmacokinetic concentration-time profiles after intravenous and oral administration of probenecid.

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#22-data-used).

Details about the structural model and its parameters can be found in [Section 2.3](#23-model-parameters-and-assumptions).




