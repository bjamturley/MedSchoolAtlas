# Germinal Center
A specialized microstructure that forms in secondary lymphoid tissues, producing long-lived antibody secreting plasma cells and memory B cells

The **dark zone** is where B cells undergo rapid division and mutation.
The **light zone** is where T cells and FDCs reside and where B cells test antigen affinity.
The **mantle zone** is the edge of the germinal center, full of naive B cells.
The **marginal zone** is outside of the germinal center in which naive B cells undergo T cell independent activation.
# B cell activation
## T-cell dependent activation 
The most common form. When activated, B cells will present the antigen on their own MHC-II molecules and will try to present the antigen to CD4 Helper T cells. They will move to the margin of the B cell zone within lymphoid tissue to do so. 

Activated Helper T cells which have recognized the same antigen on a different APC will move to the margin of the T cell zone. When these mobile cells finally connect, it is called **linked recognition.** In linked recognition, the antigen is shared, but not necessarily the same [[Immune Diversity and Recognition of Antigens#Antigen Binding|epitope]].

The B cell MHC-II binds to the T cell receptor, and the T cell CD40 ligand binds the B cell CD40 receptor. The T cell will secrete cytokines to induce B cell **Class Switch Recombination**.

Now, the B cells proliferate. Some become low-affinity plasma cells, which secrete IgM, while others form a **Germinal Center** which can become memory B cells or high-affinity plasma cells (IgG, IgA, or IgE).
### Innate Natural Killer T cells (iNKTs)
These recognize glycolipid antigens rather than normal proteins. They do not have MHC, and **present using the CD1 molecule**. They can cause class switching but **not affinity maturation or memory**.
## T-cell independent activation
Some B cells can become plasma cells without being activated by Helper T cells. This is useful for non-protein antigens like glycolipids and polysaccharides. It's weaker, has no affinity maturation or memory, and is mostly IgM.

*Via TI-1 antigens:*
**TI-1 antigens** (**mitogens**) are [[Immune Function Primer#Innate immunity|MAMPs]] which will stimulate B cell **Toll-Like Receptors (TLRs)**. At **high concentrations** TI-1 antigens stimulate all B cells to proliferate for a non-specific response. At **low concentrations**, TI-1 antigens stimulate only the specialized B cell receptor.

*Via TI-2 antigens:*
**TI-2 antigens** are polysaccharide units with **repeating epitopes** derived from bacterial capsules. These antigens stimulate B cells to secrete IgM. They can also be presented by dendritic cells which secrete **B Cell Activating Factor (BAFF)**.

**BAFF** induces class switching to IgG 2, which only forms without T cell activation. Because young children do not have a well developed TI-2 response, **vaccines made form capsular polysaccharides do not work for them**.
# Activation Induced Deaminase (AID)
Used by B cells to undergo Somatic Hypermutation (SMH) and Class Switch Recombination (CSR). The enzyme converts **Cytosine to Uracil** and is **only expressed during activation** of the B cell.
## Somatic Hypermutation
The B cell rapidly divides to produce new variations in its antibodies. AID converts C to U in hypervariable regions.

*Mechanisms of mutation*
- U residues are removed by **Base Excision Repair (BER)** proteins and **DNA glycosylase**. The openings sites are repaired by translation synthesis (insertion of a random base).
- **Mismatch Repair (MMR)** proteins cleave DNA segments around the U error and DNA polymerase replaces it, with a [[DNA Repair#Cytosine is a mutation hotspot|preference for A-T]].
- Mismatches which are missed by the above mechanisms result in two different daughter strands, increasing diversity.
## Class Switch Recombination
When a B cell switches classes, it changes the isotype of Ig is secretes. This alters the function of the B cell antibodies (not the affinity). AID converts C to U in **switch regions** of introns encoding the constant regions.

*Mutation mechanism*
1. U residues are excised by [the BER](https://www.imdb.com/title/tt14452776/) protein Uracil-N-Glycosidase. 
2. AP endonuclease creates multiple nicks, leading to double strand breaks
3. Breaks are **repaired by [[Homologous Recombination#Non-homologous end joining|non-homologous end joining]]**, resulting of the permeant loss of excised DNA, and the switch of the Ig
# Neutralization
Antibodies bind to viral, bacterial, and toxic antigens to block them from entering cells.
## Toxins
When a toxin ligand binds a cellular receptor, the toxin is endocytosed and the toxin dissociates from the binding portion within the cell. Antibodies bind and prevent entry, neutralizing it.
## Viruses
Similarly to toxins, antibodies block endocytosis of the virus into the cell. However, the antibody/virus complex can also activate [[Innate Immunity and the Complement System#Opsonization|C3b]].
## Bacteria
Will colonize the cell surface via adhesions, which others are internalized. **Antibodies against adhesions** block the uptake.
# Complement Activation
Via both IgM and IgG.

IgM is more potent for complement activation. Only one pentamer is required to activate complement by binding C1. IgM undergoes confirmational change upon binding, increasing affinity for [[Innate Immunity and the Complement System#Classical Pathway|C1q]].

IgG is less potent for complement activation, requiring 2 monomers to bind C1. This makes sense as IgG is more present on high affinity plasma cells which target specific antigens.
# Fc Receptors
## Mast cell activation
Mast cells are coated in IgE which are bound to **Fc-epsilon** receptors.
## Phagocytosis
IgG binds pathogens with complement proteins. These are recognized by **Fc-gamma** receptors on phagocytes.
## Antibody cell-mediated toxicity
IgG binds pathogens with complement proteins. These are recognized by **Fc-gamma** receptors on Natural Killer cells.
## Naive B cell inhibition
Not yet activated B cells have **Fc-gamma** receptors inhibit them when contacted by specialized IgG, preventing a primary immune response from unspecialized B cells with low-affinity IgM. This creates a preference for high affinity IgG to predominate.

This is why there isn't an IgM spike after the first immune response to a new pathogen.