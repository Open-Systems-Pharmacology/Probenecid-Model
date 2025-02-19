
# Probenecid-Model
Whole-body PBPK model of probenecid.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Probenecid.svg/2560px-Probenecid.svg.png" alt="File:Probenecid.svg" style="zoom:50%;" />





This repository contains:

- a [PK-Sim snapshot (*.json) file](https://docs.open-systems-pharmacology.org/working-with-pk-sim/pk-sim-documentation/importing-exporting-project-data-models#exporting-project-to-snapshot-loading-project-from-snapshot) of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](../../releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**



This probenecid model is intended to be used as perpetrator drug in OAT and OATP1B1-mediated drug-drug interactions (DDI).

This whole-body PBPK model of probenecid has been developed using published pharmacokinetic clinical data by Dayton 1963 [[1](#references)], Emanuelsson 1987 [[2](#references)], Vree 1992 [[3](#references)], Selen 1982 [[4](#references)], Wiebe 2020 [[5](#references)] and Landersdorfer 2009 [[6](#references)]. 
The model has then been evaluated by simulating clinical studies and comparing with respective observed data. 

The presented model includes the following features:

- metabolism by UGT1A9,
- transport by OAT3,
- inhibition of OAT and OATP1B1,
- renal clearance by glomerular filtration and tubular reabsorption modelled by GFR <1,
- oral absorption with dissolution rate assigned to the Weibull function.

For further details, quantitative model evaluation, sensitivity analysis and extensive documentation please refer to [[7](#reference)]

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License

The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References

[1] [PG Dayton, TF Yu, W Chen, L Berger, LA West, and AB Gutman. The physiological disposition of probenecid, including renal clearance, in man, studied by an improved method for its estimation in biological material. The Journal of pharmacology and experimental therapeutics, 140:278-86, 1963.](https://pubmed.ncbi.nlm.nih.gov/14025654/)

[2] [BM Emanuelsson, B. Beermann, and LK Paalzow. Non-linear elimination and protein binding of probenecid. European Journal of Clinical Pharmacology, 32(4):395-401, 1987.](https://pubmed.ncbi.nlm.nih.gov/3609117/)

[3]  [TB Vree, EW Van Ewijk-Beneken Kolmer, EW Wuis, and YA Hekster. Capacity-limited renal glucuronidation of probenecid by humans. A pilot Vmax-finding study. Pharmaceutisch weekblad. Scientific edition, 14(5):325-31, 1992.](https://pubmed.ncbi.nlm.nih.gov/1437517/)

[4] [A Selen, GL Amidon, and PG Wellingx. Pharmacokinetics of probenecid following oral doses to human volunteers. Journal of Pharmaceutical Sciences, 71(11):1238-42, 1982.](https://pubmed.ncbi.nlm.nih.gov/7175716/)

[5] [ST Wiebe, T Giessmann, K Hohl, S Schmidt-Gerets, E Hauel, A Jambrecina, K Bader,N Ishiguro, ME Taub, A Sharma, T Ebner, G Mikus, MF Fromm, F Muller, and P Stopfer.Validation of a drug transporter probe cocktail using the prototypical inhibitors rifampin, probenecid, verapamil, and cimetidine. Clinical Pharmacokinetics, 2020.](https://pubmed.ncbi.nlm.nih.gov/32504272/)

[6] [CB Landersdorfer, CMJ Kirkpatrick, M Kinzig, JB Bulitta, U Holzgrabe, GL Drusano, and F Sorgel. Competitive inhibition of renal tubular secretion of gemifloxacin by probenecid. Antimicrobial Agents and Chemotherapy, 53(9):3902-07, 2009.](https://pubmed.ncbi.nlm.nih.gov/19564368/)

[7] [Britz H, Hanke N, Taub ME, Wang T, Prasad B, Fernandez É, Stopfer P, Nock V, Lehr T. 
Physiologically Based Pharmacokinetic Models of Probenecid and Furosemide to Predict Transporter Mediated Drug-Drug Interactions. Pharm Res. 2020 Nov 25;37(12):250](https://doi.org/10.1007/s11095-020-02964-z)
