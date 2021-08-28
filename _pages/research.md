---
title: "Allan Lab - Research"
layout: textlay
excerpt: "Allan Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Cancer is a genetic disease and is fueled by the accumulation of genomic alterations that improve the fitness of the cell. A tumor cell is exposed to a plethora of intrinsic and extrinsic stimuli that can act to stimulate or inhibit the progression of the disease. How a tumor cell escapes and evolves in time and space to cause treatment-resistance and lethal disease is a fundamental question in cancer research. We are interested in the mutational mechanisms during tumor evolution (Figure 1), in particular, the mechanisms and functional consequences of large-scale genomic structural variations (SV) (e.g. deletions, duplications, and translocations) in cancer.

![]({{ site.url }}{{ site.baseurl }}/images/respic/fig2_20201230_weischenfeldt.png){: style="width: 90%; float: center; margin: 0px"}

The formation of SVs is influenced by inherited, acquired, and environmental factors that together shape the (epi-)genomic architecture. We are using computational classification methods to detect and infer patterns of rearrangements (Gerhaüser et al, Cancer Cell, 2018; Rheinbay et al, Nature, 2020; Li et al, Nature, 2020), to study genotype-phenotype associations in cancer and to infer drug-sensitivity from mutational signatures. We found an age-dependent hormone-driven pathomechanism, which led to gross differences in the formation and type of SVs in early versus late-onset cancer patients (Weischenfeldt et al. Cancer Cell, 2013) and we are studying the interplay between mutational mechanisms and disease progression in this context (Figure 1). We develop and apply mathematical models to study how tumors evolve and to predict how mutations can affect the clinical trajectories of the cancer cell. To this end, we have developed PRESCIENT (Gerhaüser et al, Cancer Cell, 2018), a conditional probabilistic framework to predict the molecular changes and associated outcomes in a clinical context. 

We are also using single-cell based methodologies to gain further insight into the clonal evolution and cell-type compositions that influence the tumor cells.
A recurrent observation we made was the importance of chromatin organization and the epigenetic landscape in determining where breakpoints occur (Gerhaüser et al, Cancer Cell, 2018; Rheinbay et al, Nature, 2020). Most SVs occur outside of the protein-coding regions of the genome, but we found that SVs can have a drastic consequence on the 3D chromatin conformation (Figure 2) and that this can directly impact nearby gene expression, for example, by disrupting or altering hard-wired gene regulatory networks (Weischenfeldt et al, Nat Rev Genet, 2013). We developed a computational method termed CESAM (cis-expression structural alteration mapping) to identify the functional consequences of SVs on nearby gene expression. Using this method, we have performed analyses across multiple tumor types which led us to further uncover mechanisms by which distant lineage-specific enhancers get translocated and positioned in front of normally silenced oncogenes, leading to their high-level upregulation, a mechanism termed Enhancer Hijacking (Figure 2; Weischenfeldt et al, Nat Genet, 2017; Northcott et al, Nature, 2017; Rheinbay et al, Nature, 2020). Our ongoing analyses using chromatin conformation capture methodologies and computational approaches are uncovering novel and unexpected mechanisms by which alterations in the 3D chromatin organization impact gene regulation.

![Figure 2]({{ site.url }}{{ site.baseurl }}/images/respic/Fig3_20201230_weischenfeldt.png){: style="width: 100%; float: center; margin: 0px"}

Our aim is to both improve the basic understanding of how changes in the genomic architecture impact on gene (de)regulation and to use this knowledge to prospectively identify specific, targeted therapeutic options based on the mutational profile of the tumor. 
To allow such inferences, we combine data generation from primary tumor samples and model systems together with integrative data analysis. 
Current and future research

#### Main projects

<b>Clonal evolution analysis to identify recurrent mechanisms of treatment resistance and identify novel therapeutic targets</b>

•	Develop and apply methods to reconstruct the clonal evolution and to identify clinical trajectories  
•	Utilizing the clonal reconstruction to Identify therapeutic targets  
•	Pursue analysis at the single-cell level to identify clonal dynamics and interplay with the tumor microenvironment  

<b>How complex structural variants emerge and affect the 3D chromatin architecture in cancer</b>  
• Integrate epigenomic data with somatic alterations and patient-related data using data-driven quantitative genetics-based computational approaches  
• Apply chromatin architecture methodologies such as Hi-C to identify how genomic alterations can impact gene regulation through altered chromatin looping   
• Identify prognostic and/or predictive signatures of complex SVs  

#### Technology
We use a combination of computational and molecular biology technologies to reach our research aims. We have optimized and integrated a range of different sequencing approaches on clinical material including paired-end sequencing, RNA-seq, ATAC-seq, Hi-C, Capture-Hi-C, mate-pair seq, DNA panel seq, single-cell sequencing, long-read sequencing. We carry out our compute on HPC systems, primarily computerome.dk. We use git for code version control and Docker to deploy our code on other systems.


<!-- Our overarching goal is to explore and understand new quantum states of electronic matter on the atomic scale. To do so, we use and develop novel spectroscopic-imaging scanning tunneling microscopy (SI-STM) tools to visualize the relevant quantum mechanical degrees of freedom.

Our goal is to build instruments and develop techniques that enable us to address the questions we find most interesting. This is possible thanks also to Milan's broad background with different research themes and technologies: he learned his trade in [Seamus Davis’ SI-STM lab](http://davisgroup.lassp.cornell.edu/) and with [Felix Baumberger](http://dpmc.unige.ch/gr_baumberger/index.html), and later moved as an [ETH fellow](http://www.ethfellows.ethz.ch/) to [Andreas Wallraff’s qudev lab](http://www.qudev.ethz.ch/) where he investigated coupled cavity arrays in circuit QED. We further have group members with different background and interests, working together on physics and instrumentation.

Here are some themes and techniques that we currently work on:

**Scanning tunneling noise spectroscopy (STNS).** We have developed a novel cryogenic MHz amplifier that allows us to measure not only the average tunneling current, but also its fluctuation! This has many applications: one can detect the fluctuations of the electronic states, peculiar tunneling processes, and shot noise. We have used this instrument to discover charge trapping in the insulating layer of the cuprates, connected to the c-axis mystery, and to measure the doubling of the charge due to Andreev processes to the superfluid in a lead sample.


**Mott physics and high-temperature superconductivity.** Questions of interest include: (i), How does the Mott state collapse upon doping and how is this related to the complex phase diagram of high-temperature superconductors? (ii), What is the strange metal phase seen in correlated electron systems? Is this an exotic long-range entangled state? What is the mechanism of dissipation in that state? (iii), Why is the transition temperature in high-temperature superconductors so high? We have worked on iridates, rhodates, and cuprates.

**Nanofabricated "Smart Tips"**.
![]({{ site.url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}
One of the  projects back from my job-proposal is to develop nanofabricated STM tips. The idea behind these “smart tips” is to use the technologies that were developed over decades in nanofabrication and make them available for scanning probe by using a nano-device instead of the traditional STM tungsten tip. One gains the flexibility of using different functionalities that are known from the fields of nanofabrication and mesoscopic physics. We are collaborating with the group Simon Groeblacher at TU Delft to realize this concept, benefitting from their unparalleled micro/nano fabrication know how.  A prototype of a smart tip is shown to the left. See publications in Microsyst Nanoeng, Nanotechnology, and PRB.

**Josephson STM.** Josephson STM has the ability to gain insight into spatial variations of the order parameter, or superfluid density. We have managed to, for the first time, use JSTM with atomic resolution on a quantum material.
We have used atomic-resolution Josephson scanning tunneling microscopy to reveal a strongly inhomogeneous superfluid in the iron-based superconductor FeTe0.55Se0.45. The results and their implications are published in Nature.

We also detected and investigated a quite particular YSR state in the same material.

**Ultra-stable SI-STM instrument.**  ![]({{ site.url }}{{ site.baseurl }}/images/respic/STMHead.png){: style="width: 250px; float: right; margin: 0px 10px"}
For SI-STM, having the most stable STM head is key. We have used finite element simulations, good choices in material science, and craftsmanship to build the most stable STM head in the world, to our knowledge. See publication in RSI.


**Strange Metals.** The strange metal phase might be the most mysterious phase of high-temperature superconductors. Here, the electrical resistivity grows linearly with temperature T in large areas of the phase diagram, with a mean free path that diminishes to a fraction of the interatomic distance. T-linear resistivity is often associated with quantum critical points and marginal-Fermi-liquid physics. In strange metals, the mystery seems to go even further: we deal with something that looks like a quantum critical phase over an extended range of the phase diagram instead of cumulating in a point. There exists no consistent theory for strange metals, leading to more adventurous new approaches including the holographic theories that use insights from quantum gravity to explain strange metals (a recent textbook on this was written by our colleagues at Leiden University, Schalm and Zaanen).
We are part of the 'Strange Metal consortium NL' that includes the groups of Hussey, Golden, van Heumen, Zaanen, Schalm, Stoof and Vandoren. 

**Magnetic fluctuations and electron spin resonance.**
![]({{ site.url }}{{ site.baseurl }}/images/respic/SpinFluc.png){: style="width: 70%; float: center; margin: 10px"}

**Twisted bilayer graphene and other material with super-periodicities.**
We have proposed that artificial super-periodicities can lead to improved superconductivity, both because of increased density of states and because of phase space arguments (see image from our SciPost publication below). Perhaps for different reasons, twisted bilayer graphene has been shown to superconduct! We are investigate this material with the groups of Efetov, Baumberger, and van der Molen.
 -->
<!-- ![]({{ site.url }}{{ site.baseurl }}/images/respic/SciPost.png){: style="width: 70%; float: center; margin: 0px"} -->


