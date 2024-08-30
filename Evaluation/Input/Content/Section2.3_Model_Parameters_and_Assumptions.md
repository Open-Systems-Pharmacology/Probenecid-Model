### 2.3.1 Absorption

The parameter value for  `Specific intestinal permeability`  was optimized based on clinical oral data, see results of optimization in [Section 2.3.4](#234-automated-parameter-identification). The measured solubility in human intestinal fluid (HIF) was used in the model (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data))

The dissolution of tablets was implemented via empirical Weibull dissolution. A different Weibull function was used for the studies by Vree ([Vree 1992](#5-references)), as the tablets were broken in half and an shorter time to reach maximum concentration was observed, see results of optimization in [Section 2.3.4](#234-automated-parameter-identification).

### 2.3.2 Distribution

Probenecid is highly bound to plasma proteins (approx. 88 %) (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). A value of 12% was used in this PBPK model for `Fraction unbound (plasma, reference value)`. The major binding partner was set to albumin (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)).

An important parameter influencing the resulting volume of distribution is lipophilicity. The reported experimental logP values are in the range of -0.52 to 3.7 (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)) which served as a starting value. Finally, the model parameter `Lipophilicity` was optimized to match clinical data (see also [Section 2.3.4](#234-automated-parameter-identification)).

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `PK-Sim Standard` and cellular permeability calculation by `Charge dependent Schmitt normalized to PK-Sim`.

### 2.3.3 Metabolism and Elimination

One metabolic pathway was implement into the model via Michaelis-Menten kinetics 

* UGT1A9

The UGT1A9 expression profiles is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#5-references)). Metabolic enzyme activity was described as saturable process following Michaelis-Menten kinetics, were the `Km` was taken from literature measured in liver microsomes and the `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

And one transport protein was implemented into the model via Michaelis-Menten kinetics 

* OAT3

The OAT3 expression profiles is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#5-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, were both `Km` and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

Additionally, renal clearance assumed to be mainly driven by glomerular filtration and tubular reabsorption modelled as GFR <1 was implemented. The `GFR fraction` was identified to best describe the observed fraction of unchanged probenecid that was renally excreted (see [Section 2.3.4](#234-automated-parameter-identification)).


### 2.3.4 Automated Parameter Identification

These are the parameters estimated in the final parameter identification:

| Model Parameter                | 
| ------------------------------ | 
| `Lipophilicity`                | 
| `GFR fraction`                 |
| `kcat` (UGT1A9)                | 
| `km` (OAT3)                    |
| `kcat` (OAT3)                  | 
| `Specific intestinal permeability`|
| `Dissolution time (50% dissolved)`| 
| `Dissolution shape`               | 
| `Dissolution time (50% dissolved)` (Broken tablet)|
| `Dissolution shape` (broken tablet) | 

 