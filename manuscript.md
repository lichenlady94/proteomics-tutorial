---
title: A Practical Beginner's Guide to Proteomics
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2022-02-01'
author-meta:
- Dina Schuster
- Devasahayam Arokia Balaya Rex
- Jesse G. Meyer
- Muralidharan Vanuopadath
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta name="citation_title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta property="og:title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta property="twitter:title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta name="dc.date" content="2022-02-01" />
  <meta name="citation_publication_date" content="2022-02-01" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Dina Schuster" />
  <meta name="citation_author_institution" content="Department of Biology, Institute of Molecular Systems Biology, ETH Zurich, Zurich 8093, Switzerland" />
  <meta name="citation_author_institution" content="Department of Biology, Institute of Molecular Biology and Biophysics, ETH Zurich, Zurich 8093, Switzerland" />
  <meta name="citation_author_institution" content="Laboratory of Biomolecular Research, Division of Biology and Chemistry, Paul Scherrer Institute, Villigen 5232, Switzerland" />
  <meta name="citation_author_orcid" content="0000-0001-6611-8237" />
  <meta name="twitter:creator" content="@dina_sch" />
  <meta name="citation_author" content="Devasahayam Arokia Balaya Rex" />
  <meta name="citation_author_institution" content="-Center for Systems Biology and Molecular Medicine, Yenepoya Research Centre, Yenepoya (Deemed to be University), Mangalore 575018, India" />
  <meta name="citation_author_orcid" content="0000-0002-9556-3150" />
  <meta name="twitter:creator" content="@rexprem" />
  <meta name="citation_author" content="Jesse G. Meyer" />
  <meta name="citation_author_institution" content="Department of Biochemistry, Medical College of Wisconsin" />
  <meta name="citation_author_orcid" content="0000-0003-2753-3926" />
  <meta name="twitter:creator" content="@j_my_sci" />
  <meta name="citation_author" content="Muralidharan Vanuopadath" />
  <meta name="citation_author_institution" content="School of Biotechnology, Amrita Vishwa Vidyapeetham, Kollam-690 525, Kerala, India" />
  <meta name="citation_author_orcid" content="0000-0002-9364-917X" />
  <meta name="twitter:creator" content="@V_MuraleeDhar" />
  <link rel="canonical" href="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta property="og:url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta property="twitter:url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta name="citation_fulltext_html_url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta name="citation_pdf_url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://jessegmeyerlab.github.io/proteomics-tutorial/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://jessegmeyerlab.github.io/proteomics-tutorial/v/f2239dc5649357a462b4e7ae84f47f33ff92a0fa/" />
  <meta name="manubot_html_url_versioned" content="https://jessegmeyerlab.github.io/proteomics-tutorial/v/f2239dc5649357a462b4e7ae84f47f33ff92a0fa/" />
  <meta name="manubot_pdf_url_versioned" content="https://jessegmeyerlab.github.io/proteomics-tutorial/v/f2239dc5649357a462b4e7ae84f47f33ff92a0fa/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://jessegmeyerlab.github.io/proteomics-tutorial/v/f2239dc5649357a462b4e7ae84f47f33ff92a0fa/))
was automatically generated
from [jessegmeyerlab/proteomics-tutorial@f2239dc](https://github.com/jessegmeyerlab/proteomics-tutorial/tree/f2239dc5649357a462b4e7ae84f47f33ff92a0fa)
on February 1, 2022.
</em></small>

## Authors



+ **Dina Schuster**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-6611-8237](https://orcid.org/0000-0001-6611-8237)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [dschust-r](https://github.com/dschust-r)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [dina_sch](https://twitter.com/dina_sch)<br>
  <small>
     Department of Biology, Institute of Molecular Systems Biology, ETH Zurich, Zurich 8093, Switzerland; Department of Biology, Institute of Molecular Biology and Biophysics, ETH Zurich, Zurich 8093, Switzerland; Laboratory of Biomolecular Research, Division of Biology and Chemistry, Paul Scherrer Institute, Villigen 5232, Switzerland
  </small>

+ **Devasahayam Arokia Balaya Rex**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-9556-3150](https://orcid.org/0000-0002-9556-3150)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [ArokiaRex](https://github.com/ArokiaRex)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [rexprem](https://twitter.com/rexprem)<br>
  <small>
     -Center for Systems Biology and Molecular Medicine, Yenepoya Research Centre, Yenepoya (Deemed to be University), Mangalore 575018, India
  </small>

+ **Jesse G. Meyer**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-2753-3926](https://orcid.org/0000-0003-2753-3926)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [jessegmeyerlab](https://github.com/jessegmeyerlab)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [j_my_sci](https://twitter.com/j_my_sci)<br>
  <small>
     Department of Biochemistry, Medical College of Wisconsin
     · Funded by Grant R21 AG074234; Grant R35 GM142502
  </small>

+ **Muralidharan Vanuopadath**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-9364-917X](https://orcid.org/0000-0002-9364-917X)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [vanuopadathmurali](https://github.com/vanuopadathmurali)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [V_MuraleeDhar](https://twitter.com/V_MuraleeDhar)<br>
  <small>
     School of Biotechnology, Amrita Vishwa Vidyapeetham, Kollam-690 525, Kerala, India
  </small>



## Abstract {.page_break_before}

Proteomics is the large scale study of protein structure and function from biological systems.  
"Shotgun proteomics" or "bottom-up proteomics" is the prevailing strategy, in which proteins are hydrolyzed into peptide that are analyzed by mass spectrometry.
Proteomics studies can be applied to diverse studies ranging from simple protein identification to studies of protein-protein interactions, absolute and relative protein quantification, post-translational modifications, and protein stability. 
To enable this range of different experiments, there are diverse strategies for proteome analysis. 
The nuances of how proteomic workflows differ may be difficult to understand for new practitioners. 
Here, we provide a comprehensive tutorial of different proteomics methods. 
Our tutorial covers all necessary steps starting from protein extraction and ending with biological interpretation. 
We expect that this work will serve as a basic resource for new practitioners of the field of shotgun or bottom-up proteomics. 


## Introduction {.page_break_before}

Proteomics is the large scale study of protein structure and function. 
Proteins are translated from mRNAs that are transcribed from the genome. 
Although the genome encodes potential cellular functions and states, the study of proteins is necessary to truly understand biology. 
Currently, proteomic studies are facilitated by mass spectrometry, although alternative methods are being developed.

Modern proteomics started around the year 1990 with the introduction of soft ionization methods that enabled, for the first time, transfer of large biomolecules into the gas phase without destroying them [@DOI:10.1126/science.2675315; @DOI:10.1002/rcm.1290020802]. 
Shortly afterward, the first computer algorithm for matching peptides to a database was introduced [@PMID:24226387]. 
Another major milestone that allowed identification of over 1000 proteins were actually improvements to chromatography [@DOI:10.1021/ac010617e]. 
As the volume of data exploded, methods for statistical analysis transitioned use from the wild west to modern informatics based on statistical models [@DOI:10.1021/ac0341261] and the false discovery rate [@DOI:https://doi.org/10.1038/nmeth1019]. 
<!-- Todo: figure 1: major milestones in proteomics technology since 1990 -->

Two strategies of mass spectrometry-based proteomics differ fundamentally by whether proteins are cleaved into peptides before analysis: "top-down" and "bottom-up". 
Bottom-up proteomics (also refered to as shotgun proteomics) is defined by the hydrolysis of proteins into peptide pieces [@DOI:10.1038/nature19949]. 
Therefore, bottom-up proteomics does not actually measure proteins, but must infer their presence [@URL:https://doi.org/10.1021/ac0341261]. 
Sometimes proteins are infered from only one peptide sequence representing a small fraction of the total protein sequence predicted from the genome. 
In contrast, top-down proteomics attempts to measure all proteins intact [@DOI:10.1039/C9MO00154A]. 
The potential benefit of top-down proteomics is the ability to measure proteoforms [@DOI:10.1126/science.aat1884]. 
However, due to analytical challenges, the depth of protein coverage that is achievable by top-down proteomics is less than the depth that is achievable by bottom-up proteomics. 

In this tutorial we focus on the bottom-up proteomics workflow. 
The most common version of this workflow is generally comprised of the following steps. 
First, proteins in a biological sample must be extracted. 
Usually this is done by denaturing and solubilizing the proteins while disrupting DNA and tissue. 
Next, proteins are hydrolyzed into peptides, usually using a protease like trypsin. 
Peptides from proteome hydrolysis must be purified.
Most often this is done with reversed phase chromatography cartridges or tips. 
The peptides are then almost always separated by liquid chromatography before they are ionized and introduced into a mass spectrometer. 
The mass spectrometer then collects precursor and fragment ion data from those peptides. 
The data analysis is usually the rate limiting step.
Peptides must be identified, and proteins are inferred and quantities are assigned. 
Changes in proteins across conditions are determined with statistical tests, and results must be interpreted in the context of the relevant biology.

There are many variations on this workflow. The wide variety of experimental goals that are achievable with proteomics technology leads to a wide variety of potential proteomics workflows. Even choice is important and every choice will affect the results. In this tutorial, we cover all of the required steps in detail to serve as a tutorial for new proteomics practioners.


1. Types of experiments enabled by proteomics
2. Protein extraction
3. proteolysis
4. Isotopic Labeling
5. Enrichments
6. Peptide purification
7. Mass Spectrometry
8. Peptide Ionization
9. Data Acquisition
10. Basic Data Analysis
11. Biological Interpretation
12. Experimental considerations and design




## Types of Experiments {.page_break_before}
A wide range of questions are addressable with proteomics technology, which translates to a wide range of variations of proteomics workflows. 
Sometimes identifying what proteins are present is desired, and sometimes the quantities of as many proteins as possible are desired. 
Proteomics experiments can be both qualitative and quantitative. 

### Qualitative experiments
- Identifying proteins 
- Identifying post translational modifications
- Identifying protein isoforms

### Quantitative experiments
- Protein abundance changes
- Phosphoproteomics
- Glycoproteomics
- Structural techniques (XL-MS, HDX-MS, FPOP, protein-painting, LiP-MS, radical footprinting, ion mobility)
- Protein stability and small molecule binding (Thermal proteome profiling, TPP, or cellular thermal shift assay, CETSA)
- Protein-protein interactions (PPIs): AP-MS, APEX, BioID




## Protein Extraction {.page_break_before}

First, proteins must be isolated from the sample matrix. Because some proteins alter other proteins, the goal is to simultaneously solubilizw and denature proteins. This is achieved with a combination of salt and chaotropic agent. 

1. Choice of Lysis buffer
* Urea can cause chemical modifications 
2. Sample type and homogenisation methods
* specialised sample preparation protocols for non-denaturing protein isolation (i.e. for LiP-MS, HDMX-MS etc) 
4. chemicals to avoid: PEGs, detergents etc
5. removal of contaminations, Protein Precipitation
* detergent reomoval resins, S-TRAP (Protifi) etc
7. protein alkylation
* choices of reduction and alkylation reagents, TCEP/DTT/2BME, Chloroacetamide/iodoacetamide, n-ethyl maleimide



## Proteolysis {.page_break_before}

Proteolysis is the defining step that differentiates bottom-up or shotgun proteomics from top-down proteomics. 
Hydrolysis of proteins is extremely important because it defines the population of potentially identifyable peptides. 
Generally peptides between a length of 7-35 amino acid are considered useful for mass spectrometry analysis.
Peptides that are too long are difficult to identify by tandem mass spectrometry, or may be lost during sample preparation due to 
Peptides that are too short are less likely to uniquely match to a single protein. 
There are many choices of enzymes and chemicals that hydrolyze proteins into peptides. 
This section summarizes potential choices and their strengths and weaknesses. 

Trypsin is the most common choice of protease for proteome hydrolysis [@DOI:10.1002/mas.21376].
Trypsin is favorable because of its specificity, availability, efficiency and low cost. 
Trypsin cleaves at the C-terminus of basic amino acids, arginine and lysine. 
Many of the peptides generated from trypsin are short in length (less than ~ 20 amino acids), which is ideal for chromatographic separation, MS-based peptide fragmentation and identification by database search.
The main drawback of trypsin is that majority (56%) of the tryptic peptides are ≤ 6 amino acids, and hence using trypsin alone limits the observable proteome [@PMID:20113005; @PMID:25823410; @PMID:30687733].
This limits the number of identifiable protein isoforms and post translational modifications.


3. theoretical studies of proteolysis enzymes [@DOI:10.1155/2014/960902]
4. Challenges associated with alternative enzyme choices (non-specific and semi-specific enzymes)

Many alternative proteases are available with different specificities that complement trypsin to reveal different proteomic sequences [@PMID:12643544; @PMID:20113005], which can help distinguish protein isoforms [@PMID:27123950].
The enzyme choice mostly depends on the application.
In general, for a mere protein identification mostly trypsin is the choice due to the reasons aforementioned.
However, alternative enzymes can facilitate _de novo_ assembly when the genomic data information is limited in the public database repositories [@pmid:31615963; @pmid:30622160; @pmid:29990557; @doi:10.1016/j.actatropica.2022.106324; @DOI:10.1021/pr400173d].
Use of multiple proteases for proteome digestion also can improve the sensitivity and accuracy of protein quantification [@PMID:30336047].

Lysyl endopeptidase (Lys-C) obtained from  _Lysobacter enzymogenesis_ is a serine protease invloved in cleaving carboxyl terminus of lysine [@PMID:6359954, @PMID:25823410].
Like trypsin, the optimum pH required for its activity is from pH 7-9. 
One among the major advantage of Lys-C is that it is resistant to denaturing agents, including 8 M urea [@PMID:27123950].
Compared to Arginine, trypsin is less efficient in cleaving Lysine, which could limit the quality of quantitation from tryptic peptides.
Hence to achieve complete protein digestion with minimal missed cleavages, Lys-C is often used in parallel to complement tryspin digestion [@PMID:23017020].

Alpha-lytic protease (aLP) is also secreted by the soil bacterial _Lysobacter enzymogenesis_ [@PMID:3053694].
Wild-type aLP (WaLP) and an active site mutant of aLP, M190A (MaLP), have been used to expand proteome coverage [@DOI:10.1074/mcp.m113.034710].
Based on observed peptide sequences from yeast proteome digestion, WaLP showed a specificity for small aliphatic amino acids like alanine, valine, and glycine, but also threonine and serine. 
MaLP showed a specificity for slightly larger amino acids like methionine, phenylalanine, and surprisingly, a preference for leucine over isoleucine. 
The specificity of WaLP for threonine enabled the first method for mapping endogenous human SUMO sites [@PMID:29079793].

Glutamyl peptidase I, commonly known as Glu-C or V8 protease, is a serine protease obtained from _Staphyloccous aureus_ [@PMID:4627743].
Glu-C cleaves at the C-terimus of glutamate, but also after aspartate [@PMID:4627743; @PMID:26748652].

Peptidyl-Asp metallopeptidase, commonly known as Asp-N, is a metalloprotease obtained from _Pseudomonas fragi_ [@PMID:2669754].
Asp-N catalyzes the hydrolysis of peptide bonds at the N-terminal of aspartate residues. 
The optimum activity of this enzyme is between pH 4 and 9.  
As with any metalloprotease, chelators like EDTA should be avoided for digestion buffers when using Asp-N.
Studies also suggests that Asp-N cleaves at the amino terminus of glutamate when a detergent is present in the proteolysis buffer [@PMID:2669754]. 
Asp-N often leaves many missed cleavages [@PMID:27123950].

Chymotrypsin or Chymotrypsinogen A is a serine protease obtained from porcine or bovine pancreas with an optimum pH range from 7.8 to 8.0 [@PMID:3555886]. 
It cleaves at the C-terminus of hydrphobic amino acids Phe, Trp, Tyr and barely Met and Leu residues.
Since the transmembrane region of membrance proteins lacks tryptic cleavage sites, this enzyme works well with membrane proteins having more hydrophobic residues [@PMID:24870543; @PMID:24696503; @PMID:27123950].
Also, the chymotryptic peptides generated after proteolysis will cover the proteome space orthogonal to that of tryptic peptides both in a quantitative and qualitative manner [@PMID:24290761; @PMID:22669647; @PMID:24696503]

Clostripain, commonly known as Arg-C, is a cysteine protease obtained from _Clostridium histolyticum_ [@PMID:4332560].
It hydrolyse mostly the C-terminal Arg residues and sometimes Lys residues, but with less efficiency.
The peptides generated are generally longer than that of tryptic peptides.
Arg-C is often used with other proteases for improving qualitative proteome data and also for investigating PTMs [@PMID:25823410]. 

LysargiNase, also known as Ulilysin, is a recently discovered protease belonging to the metalloprotease family. 
It is a thermophilic protease derived from _Methanosarcina acetivorans_ that specifically cleaves at the N-terminus of Lys and Arg residues [@PMID:25419962].
Hence, it enabled discovery of C-terminal peptides that were not observed using trypsin.
In addition, it also can cleave modified amino acids such as methylated or dimethylated arginine and lysine [@PMID:25419962].

Peptidyl-Lys metalloendopeptidase, or Lys-N, is an metalloprotease obtained from _Grifola frondosa_ [@PMID:19195997]. 
It cleaves at N-terminal of Lys and has an optimal activity at pH 9.0.
Unlike trypsin, Lys-N is more resistant to denaturing agents and can be heated up to 70 °C [@PMID:25823410].
Reports suggests that the peptides generated after Lys-N digestion produces more of c-type ions in a ETD-based mass spectrometer [@PMID:18425140]. 
Hence this can be used for analysing PTMs, identification of C-terminal peptides and also for de novo sequencing strategies [@PMID:18425140; @PMID:20953479].

Pepsin A, commonly known as pepsin, is an aspartic protease obtained from bovine or porcrine pancreas [@PMID:12089768]. 
This was the first protease that was identified and crystallized and was awarded the Nobel prize [@PMID: 19872561;@PMID:19872562; @PMID:17758437].
Pepsin works at an optimum pH from 1-4 and, in a pH depended manner it specifically cleaves Trp, Phe, Tyr and  Leu [@PMID:25823410]. 
Since it possess high enzyme activity and broad specificity at lower pH, it is preferred over other proteases for MS-based disulphide mapping [@PMID:12476442; @PMID:24980484].
Pepsin is also used extensively for structural mass spectrometry studies with hydrogen-deuterium exchange (HDX) because the rate of back exchange of the amide deuteron is minimized at low pH [@DOI:10.1021/ac902477u; @DOI:10.1002/mas.21565].  
 



## Peptide and Protein Labeling {.page_break_before}

Discussion of methods to isotopically label peptides or proteins that enable quantification

1. SILAC/SILAM
2. iTRAQ
3. TMT
4. dimethyl labeling

<!-- todo: not sure if this is the best place for this figure about quantification strategies, do we need a whole section on quant? -->

![**Quantitative strategies commonly used in proteomics.**
A) Label-free quantitation. 
Proteins are extracted from samples, enzymatically hydrolyzed into peptides and analyzed by mass spectrometry.
Chromatographic peak areas from peptides are compared across samples that are analyzed sequentially. 
B) Metabolic labelling. 
Stable isotope labeling with amino acids in cell culture (SILAC) is based on feeding cells stable isotope labeled amino acids (“light” or “heavy”). 
Samples grown with heavy or light amino acids are mixed before cell lysis.
The relative intensities of the heavy and light peptide are used to compute protein changes between samples.
C) Isobaric or chemical labelling. 
Proteins are isolated separately from samples, enzymatically hydrolyzed into peptides, and then chemically tagged with isobaric stable isotope labels. 
These isobaric tags produce unique reporter mass-to-charge (m/z) signals that are produced upon fragmentation with MS/MS. 
Peptide fragment ions are used to identify peptides, and the relative reporter ion signals are used for quantification.
](images/Summay_peptide-protein-labeling_.svg){#fig:quant-summary tag="1" width="100%"}




## Peptide or Protein Enrichment

### Protein enrichment (e.g. for protein protein interactions)
* coIP
* APEX
* bioID
* bioplex


### Peptide enrichment 
* antibody enrichments of modifications, e.g. lysine acetylation [@DOI:10.1002/pmic.201800123].
* TiO2 and Fe enrichment of phosphorylation
* Glycosylation
* SISCAPA



## Methods for Peptide Purification {.page_break_before}

1. Reverse phase including tips and cartridges
2. stage tips
3. in stage tip (iST)
4. SP2, SP3
5. s traps



## Types of Mass Spectrometers used for Proteomics {.page_break_before}

1. QQQ
2. Q-TOF
3. Q-Orbitrap
4. LTQ-Orbitrap
5. TOF/TOF
6. FT-ICR
7. types of ion mobility
* SLIM
* FAIMS
* traveling wave
* tims


## Peptide Ionization {.page_break_before}

The 2002 Nobel Prize in Chemistry was awarded to partially to John Fenn and Koichi Tanaka "for their development of soft desorption ionisation methods for mass spectrometric analyses of biological macromolecules" [@URL:https://www.nobelprize.org/prizes/chemistry/2002/summary/].

### MALDI

### Electrospray Ionization


## Data Acquisition

Data acquisition strategies for proteomics fall generally within targeted or untargeted, and they can depend on the data (data dependent acquisition or DDA) or be data independent (data-independent acquisition or DIA). 


### DDA

#### Targeted DDA

#### Untargeted DIA


### DIA

#### Targeted DIA

#### Untargeted DIA




## Analysis of Raw Data {.page_break_before}

The goal of basic data analysis is to convert raw spectral data into identities and quantities of peptides and proteins that can be used for biologically-focused analysis. 
This step may often include measures of quality control, cross-run data normalization, quantification on different levels (precursor, peptide, protein), protein inference, PTM (post translational modification) localization and also first steps of data analysis, such as statistical hypothesis tests. 

In typical bottom-up proteomics experiments, proteins are digested into peptides and further analyzed with LC-MS/MS systems. 
Peptides can have different PTMs and ionize differently depending on their length and amino acid distributions. 
Therefore, mass spectrometers often record different charge and modification states of one single peptide. 
The entity that is recorded on a mass spectrometer is usually referred to as a precursor ion (peptide with its modification and charge state). 
This precursor ion is fragmented and the precursor or peptide sequences are obtained though spectral matching. 
The quantity of a precursor is estimated with various methods.
The measured precursor quantities are combined to generate a peptide quantity. 
Peptides are also often combined into a protein group through protein inference, which combines multiple peptide identifications into a single protein identification [@DOI:https://doi.org/10.1074/mcp.R500012-MCP200] [@DOI:10.1016/j.jprot.2016.08.002].
Protein inference is still a challenge in bottom-up proteomics. 

Due to the inherent differences in the data structures of DDA and DIA measurements, there exist different types of software that can facilitate the steps mentioned above. 
The existing software for DDA and DIA analysis can be further divided into freeware and non-freeware:

#### DDA freeware 

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| MaxQuant |Cox and Mann, 2008[@DOI:10.1038/nbt.1511]|[MaxQuant](https://www.maxquant.org/)    |
| MSFragger|   Kong et al., 2017[@DOI:10.1038/nmeth.4256]    |    [MSFragger](https://msfragger.nesvilab.org/) |
| Mascot   |Perkins et al., 1999[@PMID:10612281]             |    [Mascot](https://www.matrixscience.com/)     |
| MS-GF+   |Kim et al., [@DOI:10.1038/ncomms6277]            | [MS-GF+](https://github.com/MSGFPlus/msgfplus)  |


#### DIA freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| MaxDIA |Cox and Mann, 2008[@DOI:10.1038/nbt.1511]|        [MaxQuant](https://www.maxquant.org/)    |
| Skyline|MacLean et al., 2010[@DOI:10.1093/bioinformatics/btq054]|[Skyline](https://skyline.ms/project/home/software/Skyline/begin.view) |
| DIA-NN|Demichev et al., 2019[@DOI:10.1038/s41592-019-0638-x]  |    [DIA-NN](https://github.com/vdemichev/DiaNN)     |


#### Targeted proteomics freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| Skyline|MacLean et al., 2010[@DOI:10.1093/bioinformatics/btq054]|[Skyline](https://skyline.ms/project/home/software/Skyline/begin.view) |


#### DDA non-freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| ProteomeDiscoverer ||[ProteomeDiscoverer](https://www.thermofisher.com/ch/en/home/industrial/mass-spectrometry/liquid-chromatography-mass-spectrometry-lc-ms/lc-ms-software/multi-omics-data-analysis/proteome-discoverer-software.html)|
| Mascot             |Perkins et al., 1999[@PMID:10612281]             |    [Mascot](https://www.matrixscience.com/)     |
| Spectromine   |           |    [Spectromine](ttps://biognosys.com/software/spectromine/?gclid=Cj0KCQiAoY-PBhCNARIsABcz770mjUz6iavBr9Ql7RPUdMvaHu9RYgPNrEfZco1wExEeoFwnQXuCHscaAlgBEALw_wcB)     |
| PEAKS   |Tran et al., 2018[@DOI:10.1038/s41592-018-0260-3] | [PEAKS](https://www.bioinfor.com/peaks-studio/)  |


#### DIA non-freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| Spectronaut |Bruderer et al., 2015[@DOI:10.1074/mcp.M114.044305]|[ProteomeDiscoverer](https://www.thermofisher.com/ch/en/home/industrial/mass-spectrometry/liquid-chromatography-mass-spectrometry-lc-ms/lc-ms-software/multi-omics-data-analysis/proteome-discoverer-software.html)|
| PEAKS   |Tran et al., 2018[@DOI:10.1038/s41592-018-0260-3] | [PEAKS](https://www.bioinfor.com/peaks-studio/)  |


### Analysis of DDA data

### Strategies for analysis of DIA data

### Targeted proteomics data analysis

### Quality control

### Statistical hypothesis testing




## Biological Interpretation {.page_break_before}


1. term enrichment analysis (KEGG, GO)
2. network analysis methods
3. structure analysis
4. isoform analysis
5. follow-up experiments


## Experiment Design

This section should discuss trade offs and balancing them to design an experiment. 
1. constraints: Each experiment will have different constraints, which may include the number of samples needed for analysis, or desire to quantify a specific subset of proteins within a sample.
2. sample size
3. statistics
4. costs


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>