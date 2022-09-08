<div align="center">
<h1>
  awsome-rna-3d-tools
</h1>
awesome tools for RNA 3D

for more robust list of tools see https://bio.tools/

here we try to make a quick and dirty dump of tools, by Category or by Labs, to be cleaned and improved over time
</div>

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [RNA Toolbox](#rna-toolbox)
- [RNA structural databases](#rna-structural-databases)
- [RNA 2D structure prediction](#rna-2d-structure-prediction)
- [RNA 2.5D structure predictions](#rna-25d-structure-predictions)
- [RNA 3D contacts predictions from alignments](#rna-3d-contacts-predictions-from-alignments)
- [RNA 3D contacts annotation](#rna-3d-contacts-annotation)
- [RNA 3D annotation](#rna-3d-annotation)
- [RNA-Protein Docking](#rna-protein-docking)
- [RNA Minimization/Optimize/Refinement](#rna-minimizationoptimizerefinement)
- [List of tools (per labs)](#list-of-tools-per-labs)
    - [RNApolis](#rnapolis)
        - [RNApolis – a virtual laboratory of RNA bioinformatics](#rnapolis--a-virtual-laboratory-of-rna-bioinformatics)
        - [Computational systems for quadruplexes](#computational-systems-for-quadruplexes)
        - [Other computational tools](#other-computational-tools)
    - [bgsu.edu](#bgsuedu)
    - [pylelab.org](#pylelaborg)
    - [bujnickilab](#bujnickilab)


<!-- markdown-toc end -->

# RNA Toolbox

- rna-tools: a toolbox to analyze sequences, structures and simulations of RNA (and more) docs @ http://rna-tools.rtfd.io web @ http://rna-tools.online https://github.com/mmagnus/rna-tools `pip install rna-tools`
  
# RNA structural databases

- http://rna.bgsu.edu/rna3dhub
- RNAsolo - database of cleaned PDB-derived RNA 3D structures https://rnasolo.cs.put.poznan.pl

# RNA 2D structure prediction

- RNAfold - is one of the core programs of the Vienna RNA package. It can be used to predict the minimum free energy (MFE) secondary structure of single sequences using the dynamic programming algorithm originally proposed by Zuker and Stiegler.  http://rna.tbi.univie.ac.at/cgi-bin/RNAWebSuite/RNAfold.cgi

# RNA 2.5D structure predictions
Tools that predict other types of contacts in RNA structures, including non-canonical base
pairs.

- MC-Fold (Parisien and Major, 2008)
- RNAwolf (zu Siederdissen et al., 2011)

# RNA 3D contacts predictions from alignments

- SHEVEK [^2]
- ISFOLD
- https://marks.hms.harvard.edu/ev_rna/
- Direct-Coupling Analysis of nucleotide coevolution facilitates RNA secondary and tertiary structure prediction by (...), Alexander Schug and Martin Weigt, DCA+Rosetta

# RNA 3D contacts annotation

- ClaRNA Contacts classifier for RNA 3D http://iimcb.genesilico.pl/clarna/
- MC-Annotate http://major.iric.ca/MajorLabEn/MC-Tools.html
- RNApdbee - multifunctional webserver tool for RNA structure annotation http://rnapdbee.cs.put.poznan.pl
- CSSR - Assignment of secondary structure to coarse-grain RNA 3D structures https://github.com/pylelab/CSSR [^3]

# RNA 3D annotation

- RNAspider A webserver to analyze entanglements in RNA 3D structures https://rnaspider.cs.put.poznan.pl/

# RNA-Protein Docking

- NPDock (Nucleic acid-Protein Dock) is a web server for modeling of RNA-protein and DNA-protein complex structures http://genesilico.pl/NPDock

# RNA Minimization/Optimize/Refinement

- BRiQ - Xiong, P., Wu, R., Zhan, J. & Zhou, Y. Pairing a high-resolution statistical potential with a nucleobase-centric sampling algorithm for improving RNA model refinement. Nat Commun 12, 2777 (2021). https://www.nature.com/articles/s41467-021-23100-4 https://github.com/Jian-Zhan/RNA-BRiQ

- QRNAS - Stasiewicz, J., Mukherjee, S., Nithin, C. & Bujnicki, J. M. QRNAS: software tool for refinement of nucleic acid structures. BMC Struct. Biol. 19, 5 (2019). http://genesilico.pl/qrnas https://bmcstructbiol.biomedcentral.com/articles/10.1186/s12900-019-0103-1 https://github.com/sunandanmukherjee/QRNAS

> CYANA (Güntert and Buchner 2015), NAMD (Phillips et al. 2020), XPLOR-NIH (Schwieters et al. 2003)—for the preliminary models or ensuring a proper stereochemistry from the early stages of prediction. One can also process the predicted RNA structures using tools—for example, RNAfitme (Zok et al. 2015; Antczak et al. 2018) or QRNAS (Stasiewicz et al. 2019)—having the potential to refine the nucleic acid structure. [^1]

- PYMOL https://pymolwiki.org/index.php/Optimize https://pymolwiki.org/index.php/Molecular_Sculpting 

- Chimera https://www.cgl.ucsf.edu/chimera/current/docs/ContributedSoftware/minimize/minimize.html

# List of tools (per labs)

## RNApolis

- https://github.com/RNApolis
- https://www.cs.put.poznan.pl/mszachniuk/site/research-grants/

### RNApolis – a virtual laboratory of RNA bioinformatics

- RNAssess	webserver for quality assessment of RNA 3D structures 
- RNAComposer	fully automated RNA structure prediction server
- RNAfitme	webserver for modeling nucleobase and nucleoside residue conformation in fixed-backbone RNA structures 
- RNA FRABASE	RNA FRAgments dataBASE and search engine
- RNAhugs*	webserver for RNA 3D structure alignment 
- RNAloops	database of RNA multiloops 
- RNAlyzer	framework for quality analysis of RNA models 
- RNApdbee	multifunctional webserver tool for RNA structure annotation
- RNAQUA	computational tool for RNA QUality Assessment 
- RNAspider	webserver to analyze entanglements in RNA 3D structures 
- RNAsolo	database of cleaned PDB-derived RNA 3D structures 
- RNAtango*	webserver for torsion-angle based similarity analysis of RNA 3D structures 
- RNAthor	webserver for the automatic normalization of RNA probing data 
- RNAtive	webserver to rank 3D RNA models and infer the native 
- RNAvista	webserver to assess RNA secondary structures with non-canonical base pairs 
- MCQ4Structures  standalone app to compute torsion angle-based similarity of molecule structures 

### Computational systems for quadruplexes

- DrawTetrado	standalone app to draw layer diagrams representing quadruplex structures 
- ElTetrado	standalone app for identification and classification of tetrads and quadruplexes 
- ONQUADRO	database of tetrads, quadruplexes, and G4-helices 
- WebTetrado*	webserver to annotate and visualize quadruplexes in nucleic acid 3D structures 

### Other computational tools

- SMERFA*	structural, muscular and elastic RNA finder and aligner 
- Virxicon	a lexicon of viral sequences 

## bgsu.edu

https://www.bgsu.edu/research/rna/web-applications.html

Currently we are hosting 4 web applications for analyzing RNA 3D structure:

- WebFR3D - server for finding and superimposing RNA 3D motifs
- R3D Align -  global pairwise alignment of RNA 3D structures using local superpositions
- JAR3D - predicting RNA 3D motifs in sequences
- R3D-2-MSA Server - server for accessing alignments from 3d structures


## pylelab.org

https://pylelab.org/software https://github.com/pylelab

- SHEVEK predicts long-range tertiary interactions within RNAs, between RNA-protein and protein-protein interactions from sequence alignments. https://github.com/pylelab/SHEVEK/releases [^2] 
- Qnifft utilizes the non-linear Poisson-Boltzmann (NLPB) equation to calculate the electrostatic potentials of nucleic acids. http://crystal.med.upenn.edu/kaslab_software.html 

## bujnickilab

http://genesilico.pl/

(ref in Nature style + misc)

[^1]: Carrascoza, F., Antczak, M., Miao, Z., Westhof, E. & Szachniuk, M. Evaluation of the stereochemical quality of predicted RNA 3D models in the RNA-Puzzles submissions. Rna 28, 250–262 (2022)

[^2]: Prediction of Functional Tertiary Interactions and Intermolecular Interfaces From Primary Sequence Data", PS Pang, E Jankowsky, LM Wadley and AM Pyle, J of Experimental Zoology (Mol Dev Evol) (2005), 000, 1-14.

[^3]: Chengxin Zhang, Anna Marie Pyle (2022) "CSSR: assignment of secondary structure to coarse-grained RNA tertiary structures." Acta Crystallogr D. In press.
