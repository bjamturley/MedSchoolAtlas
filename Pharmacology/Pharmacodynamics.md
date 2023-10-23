What the drug does to the body...

*Assumptions*
- **Dose-dependent**: Response depends on concentration
- **Mass-action relationship**: The rate of the reaction is proportional to the mass of reactants (drug concentration pushes equation right)
- **Occupancy assumption**: Magnitude of response is proportional to the fraction of receptor sites occupied
- **Binding is does not effect drug concentration**: Number of drug molecules is more than enough to occupy all receptors.

*Forces involved in drug-receptor interactions (binding energy)*
- Lipophilic
- Hydrophilic
- Iconic
- Steric hinderance
- Hydrogen bonding
- Electronic effects
- pK effects
# Dose-Response Curve
As concentration increases, the response increases until a maximum is reached, referred to as Emax which is analogous to [[Enzyme Primer#Michaelis-Menten|Vmax]].
## Equilibrium dissociation constant (Kd)
Analogous to [[Enzyme Primer#Michaelis-Menten|Km]], or the binding affinity. At equilibrium, Kd is the ratio of free drug to the bound drug.
### $K_d = \frac{[D] \times [R]}{[DR]}$
**\[D]** = drug concentration
**\[R]** = receptor concentration
**\[DR]** = bound drug/receptor complex
## Fractional Occupancy (FR)
The fraction of receptors occupied at a given drug concentration.
### $FR = \frac{[DR]}{[R] + [DR]} = \frac{[D]}{K_d + [D]}$
**\[D]** = drug concentration
**\[R]** = receptor concentration
**\[DR]** = bound drug/receptor complex
**Kd** = Equilibrium dissociation constant

According to this equation, the maximum possible response (*Emax*) is proportional to the number of receptors, while the maximum observed response (effect *e*) is proportional to the percentage of bound receptors (*FR*).
### $FR = \frac{e}{E_{max}}$
**e** = observed effect size
**Emax** = maximum response
## Plotting
Taking a look at concentration vs. response, the curve is hyperbolic (slope decreases as a function of the concentration). For drugs with a large concentration range, the x-axis is negative log scaled, often resulting in a sigmoid saturation curve.

![[Pasted image 20231017161404.png]]
## Population modeling
**ED50**: Dose to achieve a threshold drug effect in 50% of the population
**TxD50**: Dose which creates toxic effects in 50% of the population
**LD50**: Lethal dose in 50% of the population
**Therapeutic index (TI)**: The margin of safety for a drug. Defined as either *TxD50 / ED50* or *LD50 / ED50*.

The **standard model of safety (SMS)** can be used if the therapeutic and toxicity curves are not parallel with increasing dosage. This is defined as *SMS = TxD1 / ED99*. The larger the SMS (high dosage required to achieve toxic effect, or low effective dose), the safer the drug.

![[Pasted image 20231017174943.png]]
# Efficacy and Potency
**Efficacy** is a term which describes the ability of a drug to produce a response (along with power or intrinsic activity). **Potency** is a term which describe a drugs ability to bind to a receptor (along with affinity, Kd, EC/ED50 ect.).

The **efficacy** can be found by using the Emax. For example, two drugs can have the same efficacy at different concentrations.

The **potency** can be found by using the drug concentration, or the concentration required to reach 50% receptor occupancy. This is referred to as the EC50. In simple systems, Kd will equal EC50.
# Agonism
Agonists bind to receptors and activate them, facilitating a physiological response. An in the **active state** is denoted as **R\***. When two drugs both operate at the same site, but both under their respective Emax's, their effects will be **additive**. If the two drugs bind at different sites but still exhibit a positive effect, the effect is **synergistic**.

**Constitutive activity** pertains to receptors that are capable of activating without a ligand binding. Receptors can exist in an R* state even in the absence of an agonist.

A **full agonist** binds to a receptor and elicits a maximal response. High affinity for R* and low affinity for R.

A **partial agonist** binds to the receptor but elicits a sub-maximal response. High affinity for R* and moderate affinity for R.

A **neutral agonist (antagonist)** produces no response. It has equal affinity for R* and R. This will compete to block agonists.

An **inverse agonist** will bind to the same receptor as an agonist and elicit an opposite response. Therefore, it is *only recognizable at high constitutive activity* by deactivating these default-activated receptors. It will has low affinity for R* and high affinity for R.

![[Pasted image 20231017164211.png]]
# Antagonism
**Pharmacological antagonism** occurs when the agonist and antagonist work on the same receptor, while **physiological antagonism** occurs when the antagonist binds a different receptor and exerts the opposite effect as the agonist. An example would be a beta-adrenergic agonist (increases HR) and a muscarinic cholinergic agonist (decreases HR).

**Chemical antagonism** is when the drug doesn't bind to a receptor, instead interfering with the agonist directly. Heavy metals for instance.
## On-site binding
When an agonist binds at the same location as the antagonist, it is [[Enzyme Primer#Types of enzymatic inhibition|competitive inhibition]]. This will drive the EC50 to the right, requiring more concentration to achieve 50% receptor binding.
## Off-site binding
When a modulator binds off-site, the effect on the drug can be positive or negative.

A **negative allosteric modulator (NAM)** decreases the response, shifting Emax down (lower efficacy) and/or EC50 right.

![[Pasted image 20231017170006.png]]

A **positive allosteric modulator (PAM)** increases receptor activation, shifting Emax up (higher efficacy) and/or EC50 left.

![[Pasted image 20231017170136.png]]
# Major Receptor Classes
|                          | Ligand                                 | Effects                                              |
| ------------------------ | -------------------------------------- | ---------------------------------------------------- |
| *[[Resting Potential#Ion Channels\|Ion Channel]]*              | [[Resting Potential#Structure\|Nicotinic]] cholinergic, glutamate, GABA | Ion flux (Na/K/Ca/Cl)                                |
| *[[Signal Transduction Primer#G-Protein coupled receptors (or seven transmembrane receptors)\|GPCR]]*                     | [[Autonomic Nervous System Effects Primer#Adrenergic Receptor Functions\|Adrenergic]], muscarinic                 | 2nd messengers (cAMP, [[Signal Transduction Primer#IP3 and DAG\|IP3]], prostaglandins, ect.)     |
| *[[Signal Transduction Primer#Receptor tyrosine kinases\|Growth factors/cytokines]]* | EGFs ect., interferons                 | Protein kinases (phosphorylation)                    |
| *Transcription factors*    | Estrogen                               | Transcriptional regulation                           |
| *Enzymes*                  | HMG-CoA, PDE, MEK, cholinesterase      | Enzyme inhibition/activation                         |
| *Protein interactions*     | BCR/ABL, EWS/Flit-1, [[Necrosis and Apoptosis Primer#Intrinsic (mitochondrial) pathway|BCL-2]]/BH3 binding | Example: Venetoclax for chronic lymphocytic leukemia |
| *DNA/RNA*                  | siNRA, antisense                       | Alters coding regions                                |
# Receptor Reserve
Not all receptors need to be occupied to get to Emax. This is why EC50 and Kd are not always equal. Kd is occupancy, which EC50 is function.
# Receptor Regulation
**Disuse sensitivity** occurs when a chronic antagonist leads to an increase in response to an agonist. **Desensitization/downregulation** is the opposite, when chronic agonist leads to a decrease in response.