### 2.2.1 In vitro and physicochemical data

A literature search was performed to collect available information on physicochemical properties of probenecid. The obtained information from literature is summarized in the table below, and is used for model building.

| **Parameter**           | **Unit** | **Value** | Source                               | **Description**                                              |
| :---------------------- | -------- | --------- | ------------------------------------ | ------------------------------------------------------------ |
| MW                      | g/mol    | 285.36    | [Wishart 2006](#5-references)        | Molecular weight                                             |
| pK<sub>a</sub> (acid)   |          | 3.01      | [Avdeef 2001](#5-references)         | acid dissociation constant of conjugate acid                 |
|                         |          | 3.7       | [Avdeef 2003](#5-references)         | acid dissociation constant of conjugate acid                 |
| Solubility (HIF)        | mg/mL    | 0.74      | [Söderlind 2010](#5-references)      | Aqueous Solubility in human intestinal fluid                 |
| logP                    |          | -0.52     | [Dayton 1963](#5-references)         | Partition coefficient between octanol and water              |
|                         |          |-0.23      | [Avdeef 2001](#5-references)         | Partition coefficient between octanol and water              |
|                         |          | 0.13      | [Avdeef 2003](#5-references)         | Partition coefficient between octanol and water              |
|                         |          | 3.21      | [Hansch 1995](#5-references)         | Partition coefficient between octanol and water              |
|                         |          | 3.7       | [Hansch 1995](#5-references)         | Partition coefficient between octanol and water              |
| fu                      | %        | 6.2       | [Vree 1992](#5-references)           | Fraction unbound in plasma                                   |
|                         | %        | 7.56      | [Vree 1993](#5-references)           | Fraction unbound in plasma                                   |
|                         | %        | 11.7      | [Shen 2019](#5-references)           | Fraction unbound in plasma                                   |
| K<sub>m</sub> UGT1A9    | µmol/L   | 198.3     | [Ito 2014](#5-references)            | UGT1A9 Michaelis-Menten constant                             |
| Ki UGT1A9               | µmol/L   | 242       | Measured                             | Inhibition of UGT1A9                                         |
| Ki OAT3                 | µmol/L   | 5.41      | [Tsuruya 2016](#5-references)        | Inhibition of OAT3                                           |
| Ki OATP1B1              | µmol/L   | 39.8      | [Izumi 2016](#5-references)          | Inhibition of OATP1B1                                        |
| Ki OATP1B1              | µmol/L   | 17.89      | In vivo Ki estimated based on CP-I data| Inhibition of OATP1B1                                        |

### 2.2.2 Clinical data

A literature search was performed to collect available clinical data on probenecid in adults. 

The following publications were found in adults for model building:

| Publication                   | Arm / Treatment / Information used for model building        |
| :---------------------------- | :----------------------------------------------------------- |
| [Dayton 1963](#5-references)  | Individual plasma PK profiles in healthy subjects after single intravenous administration of 464.20 and 1860 mg probenecid |
| [Emanuelsson 1987](#5-references) | Plasma PK profiles in healthy subjects after single intravenous infusion (15 min) of 500 mg probenecid and single oral administration of 2000 mg probenecid|
| [Vree 1992](#5-references)    | Plasma PK profiles and urine data in healthy subjects after single oral administration of 250 and 1500 mg probenecid |
| [Selen 1992](#5-references)   | Plasma PK profiles in healthy subjects after single oral administration of 500, 1000 and 2000mg probenecid |
| [Wiebe 2020](#5-references)   | Plasma PK profiles in healthy subjects after multiple oral administration of 1000 mg probenecid |
| [Landersdorfer 2009](#5-references)    | Plasma PK profiles in healthy subjects after multiple oral administration of 250, 500 and 1000 mg probenecid |


The following table shows the data from the excretion studies ([Vree 1992](#5-references)) used for model building:

| Observer                                                     | Value |
| ------------------------------------------------------------ | ----- |
| Fraction excreted  to urine of unchanged probenecid after oral administration 1000 mg | 2%   |
| Fraction excreted  to urine of unchanged probenecid after oral administration 1500 mg | 5%   |
| Fraction excreted  to urine of unchanged probenecid after oral administration 500 mg | 0.3%  |
| Fraction excreted  to urine of unchanged probenecid after oral administration 250 mg | 1.1%  |


The following dosing scenarios were simulated and compared to respective data for model verification:

| Scenario                                                     | Data reference                       |
| ------------------------------------------------------------ | ------------------------------------ |
| iv bolus 464.2 mg                         | [Dayton 1963](#5-references) |
| iv bolus 1860 mg                          | [Dayton 1963](#5-references) |
| po 500 mg                                 | [Emanuelsson 1987](#5-references) and [Vree 1992](#5-references) |
| po 1000 mg                                | [Emanuelsson 1987](#5-references), [Shen 2019](#5-references), [Vree 1992](#5-references), [Vree 1993](#5-references)|
| po 2000 mg                                | [Dayton 1963](#5-references)|
| po 1000 mg bid for 1 day                  | [Smith 1980](#5-references) |
| po 500 mg at 0, 1000 mg at 8 h and 500 mg at 14.5, 20.5 and 26.5 h| [Landersdorfer 2010](#5-references) |

