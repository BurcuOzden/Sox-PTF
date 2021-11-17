![github_title](https://user-images.githubusercontent.com/64282221/142176560-b259676e-5268-469e-8a33-4d07f6b33e8a.png)

Pioneer transcription factors (PTFs) directly bind to the nucleosomally organized DNA to stimulate vital cellular processes. Up to date, several studies have been carried out to dissect the interaction landscape between PTFs and chromatin. However, the precise invasion mechanism of chromatin by PTFs is yet to be resolved. Expanding on this, we carried out dynamic ingtegrative modeling approach (integrative modeling and molecular dynamics simulations) concentrating on three super helical locations (SHLs) as binding sites, namely SHL0, SHL+2, SHL+4. Our dynamic integrative modeling steps are as follow:

* First, we have structurally modeled 601-SHL024 nucleosome by inserting cognate sequence "TTGT" at SHL0, SHL2 and SHL4 regions to 601-NCP structure (pdb id:3lz0). 
* We have performed molecular dynamics simulations of 601-SHL024 nucleosome to accomodate the Sox at SHL0, SHL2 and SHL4 regions. We have traced the conformational profile of Sox binding sequences with two measures to find the most appropriate conformation to generate Sox:Nucleosome complexes: (i) The P-RMSD (Root Mean Square Deviation of the DNA Phosphorus atoms to the reference DNA), and (ii) the minor groove widening calculated for the probed SHLs. 
* Then, we have docked Sox to its cognate sequence "TTGT" by integrative modeling and performed second cycle of molecular dynamics simulations. At the end of these simulations, we have obtained final models as Sox:dyad, Sox:SHL2 and Sox:SHL4. 

Initial 601-SHL024 model and final Sox:dyad, Sox:SHL2 and Sox:SHL4 models are given in **_Models_** directory and sample trajectories are given in **_Trajectories_** directory.

### Acknowlegnments
This study is the part of the integrative approach, where we have combined cutting-edge experimental (•OH and UV laser footprinting) and _in silico_ (integrative modeling and molecular dynamics simulations) approaches. The article will be published very soon.

### Contact
Ezgi Karaca ezgi.karaca@ibg.edu.tr

Burcu Ozden burcu.ozden@ibg.edu.tr
