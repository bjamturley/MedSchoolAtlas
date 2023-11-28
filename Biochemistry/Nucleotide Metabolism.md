# Synthesis
## Purine Synthesis
Occurs in the cytosol of hepatocytes.

1. In the [[Glycolysis and Pentose Phosphate#Pentose phosphate pathway|pentose phosphate pathway]], ribose 5-P is converted to PRPP (via **PRPP synthase**)
	- **Activators**: Phosphate (indicates the cell is consuming ATP, requiring more nucleotides)
	- **Inhibitors**: GMP, AMP, and IMP
2. PRPP is converted to PRA (via **PRPP aminotransferase**)
	- **Activators**: PRPP
	- **Inhibitors**: GMP, AMP, IMP
3. PRA is converted to IMP (and 4 ATP is consumed). **Folate (Vitamin B9)** donates two carbons for this step.
4. IMP is converted to nucleotides (two options)
	- → XMP → GMP (requires ATP)
	- → Adenylosuccinate → AMP (requires GTP)

Each of these formation steps are inhibited by different combinations of substances. Adenylosuccinate synthetase, for example, is inhibited by just AMP whereas PRPP amidotransferase requires both GMP and AMP to be inhibited. This means purine levels can be regulated by partial inhibition.
## Pyrimidine Synthesis
This one isn't as important.

1. Fabrication of pyrimidine ring as orotate
2. Orotate is attached to PRPP to generate Uridine Monophosphate
3. Uridine Monophosphate converted to Cytosine and Thymidine (deoxy) nucleotides
# Degradation
## Catabolism of purines
- GMP → guanosine via **nucleotidase**
- AMP (two options)
	- → adenosine (via **nucleotidase**) → inosine (via dephosphorylation)
	- → IMP (via **AMP deaminase**) → inosine (via dephosphorylation)

We now have guanosine and inosine.

- Guanosine → guanine (via **Purine Nucleoside Phosphorylase**) → Xanthine (via **guanine deaminase**)
- Inosine → hypoxanthine (via **Purine Nucleoside Phosphorylase**) → Xanthine (via **Xanthine Oxidase**)

Xanthine can then be converted to uric acid via **Xanthine Oxidase**.
## Catabolism of pyrimidines
This is straightforward. Pyrimidines are converted directly to malonyl-CoA, methylmalonyl CoA, and succinyl CoA.
## Clinical Pearls
### AMP deaminase
Mutations in this enzyme can lead to myoadenylate deaminase deficiency (MADD)
### Adenosine deaminase
Too much of this enzyme will deplete the total amount of adenine nucleotide (leading to **anemia**). 

Too little will cause **Severe Combined Immunodeficiency (SCID)**. This is an X-linked disorder which will lower the number of T/B cells.

**Low adenosine deaminase**
→ more adenosine 
→ more dATP 
→ inhibits ribonucleotide reductase 
→ blocks formation of dNDPs (inhibits RNR, see below)
→ impaired DNA synthesis in lymphocytes
### Gout
A painful form of arthritis. Results from high levels of uric acid. Diets containing high levels of purines (beans, lentils, spinach) eaten with meat, seafood, or alcohol can also result in gout.

Treated with **inhibitors of xanthine oxidase** (**allopurinol**) which will prevent buildup of uric acid and increase levels of soluble purines (guanine and hypoxanthine). Blocking conversion of folate to THF ([[Cancer Drugs#Methotrexate & Leucovorin|methotrexate]]), inhibiting purine synthesis, can also help with this condition (but is generally combined with a second drug).
# Purine Salvage Pathway
A backdoor allowing purines to be recycled without having to be broken down all the way. Uses PRPP as the recycled material. This process is not immediately important clinically.

1. **Adenine Phosphoribosyltransferase (APRT)** transfers Adenine onto PRPP, generating AMP
2. **Hypoxanthine-guanine phosphoribosyltransferase (HGPRT)** transfers guanine or hypoxanthine onto PRPP, generating GMP or IMP
## Clinical pearls
Deficits in HGPRT can lead to excess uric acid, leading to gout.

**Lesch-Nyhan syndrome** (<1.5% HGPRT): Neurological problems like cerebral palsy, choreoathetosis, self-destructive biting (woah)
**Kelley-Seegmiller syndrome** (~8% HGPRT): Gout, kidney destruction, mild neurological problems
**Variant Lesch-Nyhan syndrome** (8-15% HGPRT): Mild neurologic problems (some motor dysfunction)
# Ribonucleotide Reductase (RNR)
Converts ribonucleoside diphosphates to deoxyribonucleotides. RNR has one subunit with 2 allosteric binding sites (specificity site and activity control site), 1 catalytic site, and one final unit which forms the tyrosine radical necessary for forming thymidine. **The energy for this reaction comes from 2 cysteines and 1 NADPH**.

ADP → dADP
GDP → dGDP
CDP → dCDP
UDP → dUDP (thymidine precursor)
## Tyrosine radical formation
**Ferrous iron center** which loses an electron to generate the tyrosine radical. Only works in aerobic conditions. It will receive an electron from NADPH either via [[Glycolysis and Pentose Phosphate#NADPH is important in radical cell defense|glutathione]], or via FAD.

This electron transfer results in a reduction of sulfhydryl in RNR.
## Substrate specificity site
dNTPs will bind, determining which substrates (ADP/GDP/CDP/UDP) will attach to the catalytic site.

**Binding at the specificity site**
dTTP → inhibits reduction of CDP, UDP, and GDP
ATP/dATP → stimulates reduction of CDP and UDP
dGTP → stimulates reduction of ADP
## Activity control site
This is distinct from the specificity site and controls enzyme activity. High levels of dATP indicate there is a high concentration of dNTPs, and will inhibit RNR.

dATP bound → Inactivation
ATP bound → Catalysis

RNR can also be inhibited by hydroxyurea.
# dTTP Synthesis
Pathway:
*UDP → dUDP → dUTP → dUMP (via **dUTPase**) → dTMP (via **thymidylate synthase**) → dTTP*

Thymidylate synthase is a common target for anti-cancer therapies, preventing cells from dividing. **5-fluorouracil** is one such drug, which is a suicide inhibitor of the enzyme (destroying it). Without dTTP, no DNA synthesis will take place.

**Methotrexate**, mentioned above, is another anti-cancer pharmaceutical which will stop the regeneration of tetrahydrofolate (THF) from folate and therefore block dTMP (thymidylate) synthesis.