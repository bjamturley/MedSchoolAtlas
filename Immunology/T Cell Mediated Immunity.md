# Secondary Lymph Organs
## Spleen
Lymphocytes enter from the blood via the [[Humoral Immune Response#Germinal Center|marginal sinus]]. T cells move to the T cell zone while B cells move to the B cell follicle.

![[Pasted image 20231101161310.png]]
## Lymph nodes
Naive T cells arrive at lymph nodes through the blood and enter via the **high endothelial venule (HEV)**. They then move into the **paracortex (T cell zone)**.

Activated dendritic cells enter via the afferent lymphatic. The move to the T cell zone

![[Pasted image 20231101161408.png]]
## Peyer's Patches
Naive T cells arrive at Peyer's Patches through the blood and enter via the **high endothelial venule (HEV)**. Activation does not occur in Peyer's Patches and **will move to the lymph node for activation**.

Dendritic cells arrive via the lumen.

![[Pasted image 20231101161804.png]]
# Entry into Tissues
## 1. Rolling
Naive T cells in HEV express **lectins** which interact with **L-selectin**, allowing T cells to roll on the surface.
## 2. Activation
Chemokine receptors (**CCR7**) on T cells recognize **CCL21** on HEV, changing conformation to bind **integrins** on the T cells. The T cells can then enter the lymph node paracortex, following the cytokine gradient.
# Survival Signals
T cells which do not encounter an antigen in the lymph node paracortex receive a **survival signal**, or a signal from the host peptide which keeps the T cell alive in the lymph node indefinitely.

When there is a TCR/dendritic cell antigen match in lymph nodes, MHC triggers a confirmational change in **LFA1**, leading to a stronger interaction. This leads to clonal expansion over 2-3 days.
# Exit from Tissues
Controlled by **sphingosine 1-phosphate (S1P)** which is in high concentration in lymph and blood. Lymph nodes keeps the concentration low internally using **S1P lyase**.

Without an antigen encounter, S1PR1 (a [[Signal Transduction Primer#G-Protein coupled receptors (or seven transmembrane receptors)|GPCR]] for S1P) is upregulated and T cells will follow the S1P gradient to the plasma.

If an antigen is encountered, **CD69** is upregulated which results in proliferation of effector (activated) T cells. Eventually CD69 is downregulated and S1PR1 is upregulated, which suggests to the T cell it is time to leave.
## Clinical pearl: FTY20
FTY20 inhibits immune response by trapping lymphocytes in the lymph node. This is a useful therapy for **multiple sclerosis**, **chronic infections (e.g., HIV/SIV)**, and **cancer**.
# T Cell Activation
T cells receive three types of signals, all three of which activate the T cell.

1. Specificity for TCR (ability to recognize MHC antigen)
2. Co-stimulatory signal (amplifies signal 1)
3. Cytokine signaling

Upon activation, T cells switch from [[Oxidative phosphorylation and the ETC#Oxidative phosphorylation|oxidative phosphorylation]] to [[Glycolysis and Pentose Phosphate|aerobic glycolysis]].
## Signaling Cascade
After activation, resulting in clonal expansion. After the threat is eliminated, effector (activated) T cells are removed (clonal contraction) and those remaining become **memory cells**.

**Akt**: Switches T cell to anerobic glycolysis
**Il-2**: Growth factor sustaining clonal expansion
**Il-2R alpha**: Allows T-cells to respond to low IL-2
**CD69**: Receptor for lymph node retention.
### IL-2
A growth factor for **sustaining clonal expansion**. Its receptor (**IL-2R**) responds to low concentrations of IL-2. This is important for T regulatory cell survival.
### Control of Clonal Expansion
Inhibitory receptors (checkpoint receptors). Are sometimes used for cancer therapy.

**CTLA4**: Restricts activation of T cells through higher affinity for B7 than CD28.
**PD1**: Binds Programmed Death Protein Ligand 1 and 2 (PDL1 and 2).
# T Cell Differentiation
## CD8 Cytotoxic (Killer)
Defends against intracellular pathogens (e.g. viruses). Requires co-stimulatory activity.

CD4 cells, activated by dendritic cells, help CD8 expansion through **IL-2 secretion**.
## CD4 Helper
Cytokines induce the expression of transcription factors for T cell subtype differentiation via the **JAK-STAT** pathway, upregulating **master regulator genes** which control what the T cell secretes.

*Master Regulator Genes*
**TH1**: *STAT1* (IFN-gamma), *STAT4* (IL-12) → *T-BET*
**TH2**: *STAT6* (IL-4) → *GATA3*
**TH17**: *STAT3* (TGF-beta, IL-6, IL-23) → *BCL6*
**TFH**: *STAT5* (IL-2) → *FOXP3*

*Secretions*
**TH1**: Produces IFN-gamma (Macrophage mediated destruction of pathogens) and IL-2 (T-Cell Growth Factor)
**TH2**: Produces IgE (parasites), as well as IL-4, IL-5, and IL-13
**TH17**: Produces [[Hypersensitivity#Mechanism 1 CD4+|IL-17]] (neutrophil recruitment) and IL-22 (stimulates antimicrobial peptide release)
**TFH**: Produces IL-21 ([[Humoral Immune Response#Class Switch Recombination|isotype switching]])
**T-reg**: Produces IL-10 and TGF-beta ([[Inflammation and Repair#Healing and Repair|mucosal homeostasis]] and T cell response regulation)
# Dendritic Cells (DCs)
The main goal of these is to activate naive T cells. Upregulation of CCR7 receptors on DCs with antigen presentation cause their migration into the lymph node.
## Conventional DCs
Detects a variety of pathogens.

**cDC1** is specialized in activation in CD8 T cells
**cDC2** is specialized in activation of CD4 T cells
## Plasmacytoid DCs
Detects specifically viral infections.

They express **TLR-7, TLR-9, and IFN-alpha** which help produce **type I interferons** (anti-viral cytokines).
## Antigen processing
### Receptor-mediated phagocytosis
Pathogen engulfed after MHC II presentation. Activates **CD4 T cells**.
### Viral infection
Degraded by cytoplasmic proteosomes. Peptide loaded onto MHC I. Activates **CD8 T cells**.
### Cross-presentation
When the virus has not directly infected the cell, but still contacted. Peptide loaded onto MHC I. Activates **CD8 T cells**.
### Transfer between DCs
Pathogen is exchanged between DCs. This is used for self-antigens and will be presented on both MHC I and MHC II. Activates both CD8 and CD4 T cells.
### Autophagy
When naturally recycling organelles, internally created peptides are presented on MHC II. This maintains tolerance to self-antigens.