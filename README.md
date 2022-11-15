<div align="center">
<h1>
  awsome-rna-3d-tools
</h1>
awesome tools for RNA 3D

for more robust list of tools see https://bio.tools/

here we try to make a quick and dirty dump of tools, by Category or by Labs, to be cleaned and improved over time

https://github.com/mmagnus/awesome-rna-3D-tools

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
  
# Deep Learning for RNA #
[...]

# RNA structural databases

- http://rna.bgsu.edu/rna3dhub
- RNAsolo - database of cleaned PDB-derived RNA 3D structures https://rnasolo.cs.put.poznan.pl

# RNA 2D structure prediction

- RNAfold - is one of the core programs of the Vienna RNA package. It can be used to predict the minimum free energy (MFE) secondary structure of single sequences using the dynamic programming algorithm originally proposed by Zuker and Stiegler.  http://rna.tbi.univie.ac.at/cgi-bin/RNAWebSuite/RNAfold.cgi

See for "Recent papers that used machine learning for RNA secondary structure prediction":

      Name	Authors	Year	Method	Intra-family	Inter-family	Re-trained
      CROSS 	Delli Ponti et al. 	2017 	ANNa 	✓ 	✗ 	✗ 
      DMfold 	Wang et al. 	2019 	LSTMb 	✓ 	✗ 	✗ 
      SPOT-RNA 	Singh et al. 	2019 	CNNc + BLSTMd 	✓ 	✗ 	✗ 
      E2Efold 	Chen et al. 	2019 	CNNc + Transformere 	✓ 	✗ 	✗ 
      RNA-state-inf 	Willmott et al. 	2020 	BLSTMd 	✓ 	✓ 	✗ 
      RPRes 	Wang et al. 	2021 	BLSTMd + ResNetf 	✓ 	✗ 	✗ 
      MXfold2 	Sato et al. 	2021 	BLSTMd + ResNetc 	✓ 	✓ 	✓ 
      UFold 	Fu et al. 	2021 	CNNc 

Szikszai, M., Wise, M., Datta, A., Ward, M. & Mathews, D. H. Deep learning models for RNA secondary structure prediction (probably) do not generalize across families. Bioinformatics 38, 3892–3899 (2022). https://academic.oup.com/bioinformatics/article/38/16/3892/6617348
  
  
# RNA 2.5D structure predictions
Tools that predict other types of contacts in RNA structures, including non-canonical base
pairs.

- MC-Fold (Parisien and Major, 2008)
- RNAwolf (zu Siederdissen et al., 2011)

# RNA 3D contacts predictions from alignments

- SHEVEK
- ISFOLD
- https://marks.hms.harvard.edu/ev_rna/
- Direct-Coupling Analysis of nucleotide coevolution facilitates RNA secondary and tertiary structure prediction by (...), Alexander Schug and Martin Weigt, DCA+Rosetta [^4]

# RNA 3D contacts annotation

- ClaRNA Contacts classifier for RNA 3D http://iimcb.genesilico.pl/clarna/
- MC-Annotate http://major.iric.ca/MajorLabEn/MC-Tools.html
- RNApdbee - multifunctional webserver tool for RNA structure annotation http://rnapdbee.cs.put.poznan.pl
- CSSR - Assignment of secondary structure to coarse-grain RNA 3D structures https://github.com/pylelab/CSSR [^3]
- bpnet -  This software is for computing base pair networks found in DNA/RNA. The software also calculates the overlap based network computations - https://github.com/computational-biology/bpnet [does not compile on mac @mmagnus as of 220913]

# RNA 3D annotation
(not as "simple" as contact, for contacts see above)

- RNAspider A webserver to analyze entanglements in RNA 3D structures https://rnaspider.cs.put.poznan.pl/

# RNA 3D comparison metrics

> There are also other novel metrics being developed in recent years, including the mean of circular quantities (MCQ) and the Longest Continuous Segments in Torsion Angle space (LCS-TA), which measure the structural similarity in the torsion angle space.

# RNA 3D structure prediction

> During the last decade, a good number of RNA 3D structure prediction algorithms have been actively developed and improved. These prediction methods cover approaches similar to protein structure prediction, including comparative modeling (e.g., ModeRNA), fragment assembly (e.g., RNAComposer, 3dRNA, and VfoldLA), and de novo modeling (e.g., NAST, iFoldRNA, and SimRNA/SimRNAweb).

# RNA-Protein Docking

- NPDock (Nucleic acid-Protein Dock) is a web server for modeling of RNA-protein and DNA-protein complex structures http://genesilico.pl/NPDock

# RNA Minimization/Optimize/Refinement
> CYANA (Güntert and Buchner 2015), NAMD (Phillips et al. 2020), XPLOR-NIH (Schwieters et al. 2003)—for the preliminary models or ensuring a proper stereochemistry from the early stages of prediction. One can also process the predicted RNA structures using tools—for example, RNAfitme (Zok et al. 2015; Antczak et al. 2018) or QRNAS (Stasiewicz et al. 2019)—having the potential to refine the nucleic acid structure. [^1]

- BRiQ - Xiong, P., Wu, R., Zhan, J. & Zhou, Y. Pairing a high-resolution statistical potential with a nucleobase-centric sampling algorithm for improving RNA model refinement. Nat Commun 12, 2777 (2021). https://www.nature.com/articles/s41467-021-23100-4 https://github.com/Jian-Zhan/RNA-BRiQ

- QRNAS - Stasiewicz, J., Mukherjee, S., Nithin, C. & Bujnicki, J. M. QRNAS: software tool for refinement of nucleic acid structures. BMC Struct. Biol. 19, 5 (2019). http://genesilico.pl/qrnas https://bmcstructbiol.biomedcentral.com/articles/10.1186/s12900-019-0103-1 https://github.com/sunandanmukherjee/QRNAS

- rnafitme - M. Antczak, T. Zok, M. Osowiecki, M. Popenda, R.W. Adamiak, M. Szachniuk. RNAfitme: a webserver for modeling nucleobase and nucleoside residue conformation in fixed-backbone RNA structures, BMC Bioinformatics, 2018, 19, pp. 304 10.1186/s12859-018-2317-9. https://rnafitme.cs.put.poznan.pl

-------------------------------------------------------------------------------

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

- ModeRNA - We developed a method for 3D homology modeling of RNA structures. It requires a pairwise sequence alignment and a structural template to generate a 3D structural model of the target RNA sequence via either a fully automated or script-based approaches. ModeRNA is capable of handling 115 different nucleotide modifications and bridging gaps using fragments derived from an extensive fragment library.

- RNAmap2D - RNAmap2D is a software tool for calculation of contact and distance maps based on user-defined criteria, and to some extent, quantitative comparison of pairs or series of contact maps and visualization of the results.
 
- FILTREST3D - Filtrest3D is a program for discrimination of a large number of alternative models of protein structure or protein-ligand structure against a set of restraints derived from low-resolution experimental analyses (such as cross-linking, mutagenesis, circular dichrosm etc.) as well as from computational predictions (e.g. solvent accessibility, amino acid contact maps).

- DARS-RNP and QUASI-RNP, potentials for protein-RNA docking - We developed two medium-resolution, knowledge-based potentials for scoring protein-RNA models obtained by docking: the quasi-chemical potential (QUASI-RNP) and the Decoys As the Reference State potential (DARS-RNP). Both potentials use a coarse-grained representation for both RNA and protein molecules and are capable of dealing with RNA structures with posttranscriptionally modified residues. In our tests that compared these methods to other published potentials, DARS-RNP showed the highest ability to identify native-like structures.

- QRNAS - QRNAS is an extension of the AMBER simulation method with additional terms associated with explicit hydrogen bonds, co-planarity base pairs, backbone regularization, and custom restraints. QRNAS is capable of handling RNA, DNA, chimeras and hybrids thereof, and enables modeling of nucleic acids containing modified residues.

(ref in Nature style + misc)

[^1]: Carrascoza, F., Antczak, M., Miao, Z., Westhof, E. & Szachniuk, M. Evaluation of the stereochemical quality of predicted RNA 3D models in the RNA-Puzzles submissions. Rna 28, 250–262 (2022)

[^2]: Prediction of Functional Tertiary Interactions and Intermolecular Interfaces From Primary Sequence Data", PS Pang, E Jankowsky, LM Wadley and AM Pyle, J of Experimental Zoology (Mol Dev Evol) (2005), 000, 1-14.

[^3]: Chengxin Zhang, Anna Marie Pyle (2022) "CSSR: assignment of secondary structure to coarse-grained RNA tertiary structures." Acta Crystallogr D. In press.

[^4]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4666395/
