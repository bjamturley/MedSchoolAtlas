# Triacylglycerols (TAGs)
How [[Lipids, Membranes, and Membrane Proteins|fatty acids]] are stored in the body. Only found in organs which perform gluconeogenesis (liver and kidneys). Starts with glycerol-3-phosphate (G3P), which can come from [[Glycolysis and Pentose Phosphate#Glycolysis steps|DHAP]] or by phosphorylating glycerol. Adipocytes rely on DHAP → G3P as they do not perform gluconeogenesis.

TAG generation occurs in the endoplasmic reticulum of hepatocytes and adipocytes, in which fatty acids are esterified into glycerol (costs 1 ATP). TAG is an energetic investment made when energy is abundant. TAGs are always being made, even when starving, but the balance of catabolism and anabolism changes.

**Palmitic acid (16C)** is the primary fatty acid stored.

![[Pasted image 20230831201855.png]]
# Storage of Fatty Acids
## Intestines
Fatty acids are reformed into TAGs within intestinal cells. They are packed in **chylomicrons** with cholesterol and apolipoproteins. These are transported via the lymphatic system and dumped into blood circulation. Blood enzymes will break down the TAGs in chylomicrons, releasing the individual fatty acids. Individual fatty acids will cross straight through cell membranes.
## Liver
The liver has its own chylomicrons called VLDL. This contains apolipoproteins and TAGs produced from the liver's conversion of glucose to fatty acids. These liver chylomicrons will also enter the blood.
## Adipose tissue
Catecholamine receptors on adipose will signal cyclic AMP and Protein Kinase A (PKA). PKA phosphorylates **hormone-sensitive lipase (HSL)** and **perilipin**.

Perilipin is a protein which studs the outside of a fat droplet to encapsulate it. When phosphorylated, it allows HSL to free the TAGs in the droplet which will diffuse them into capillaries. Adipose fats will bind to albumin which provide an escort to cells.
# Fatty acid (beta) oxidation
## 1. Acyl-CoA dehydrogenase
Palmitoyl-CoA is oxidized into trans-delta 2-enoyl-CoA, yielding FADH2.

Electrons are delivered from FADH2 to Coenzyme Q. This bypasses [[Oxidative phosphorylation and the ETC#Complex I NADH dehydrogenase|Complex I]]. 
## 2. Addition of water
Water is added to the double bond on trans-delta-enoyl-CoA, yielding L-beta-hydroxyaryl-CoA. This step primes the release of acetyl CoA.
## 3. Dehydration of L-beta-hydroxyaryl-CoA
The OH group is oxidized via beta-hydroxyacyl-CoA dehydrogenase, reducing NAD+ into NADH and beta-ketoacyl-CoA
## 4. Release of acetyl-CoA
Thiolase adds CoA to the beta carbon and acetyl-CoA is released. This results in an n-2 fatty acid chain. Steps 1-4 repeat until all carbons have been converted to acetyl-CoA. The last round will split the last 4C molecule into two acetyl-CoA, meaning there are n+1 acetyl-CoA molecules generated for the total number of beta oxidation rounds.

> **PROBLEM**
> How much ATP generated from a 16C fatty acid?
> 
> **SOLUTION**
> 7 rounds of beta oxidation → 8 acetyl-CoA, 7 FADH2, and 7 NADH
> 8 acetyl-CoA → 8 FADH2, 24 NADH, and *8 ATP*
> 15 FADH2 = 22.5 ATP
> 31 NADH = 77.5 ATP
> **Total: 100 + 8 ATP**

Acetyl-CoA: [[PDC and Krebs (TCA)#Pyruvate Dehydrogenase Complex (PDC)]]
NADH/FADH: [[Oxidative phosphorylation and the ETC]]
# Beta oxidation considerations
## Odd number fatty acids
In this case, the last round of beta oxidation will result in a 3 carbon molecule called **Propionyl-CoA**. To this, a carbon is added via **Propionyl-CoA Carboxylase**, creating Methylmalonyl-CoA. Eventually, through a few rearrangements, [[PDC and Krebs (TCA)#4. Succinyl-CoA (4C)|Succinyl-CoA]] is generated, which means odd number fatty acids can be slightly anapleurotic for the TCA cycle.
## Unsaturated fatty acids
When there is a double bond present, beta oxidation will proceed normally, removing 2 carbons at a time until the double bond is reached. Double bonds on fatty acids are naturally in the *cis* configuration and must be *trans* to continue oxidizing. 

**Solution**: The enzyme **delta 3, delta 2-enoyl-CoA isomerase** will preposition the double bond.
# Comparison to Glucose Metabolism
[[Glycolysis and Pentose Phosphate#Glycolysis steps|Glycolysis]] yields less ATP per carbon and is bulkier when stored as glycogen as compared to triacylglycerols. However, beta oxidation yields a higher proportion of FADH2 relative to NADH as compared to glycolysis. Therefore, glycolysis will yield more ATP molecules per molecule of oxygen.

Additionally, beta oxidation produces reactive oxygen species (ROS) on net, whereas glycolysis will share products with the [[Glycolysis and Pentose Phosphate#NADPH is important in radical cell defense|Pentose Phosphate Pathway]] to produce NADPH which counteract ROS formation.
# Fatty Acid Synthesis
Occurs in the cytosol, using acetyl-CoA produced in the mitochondria. Acetyl-CoA is transported into the cytosol by combining it with oxaloacetate (OAA) which forms citrate. The citrate shuttle will move (via malate conversion) which can be delivered to the cytosol and later converted back to acetyl-CoA and OAA.

**Malate in the cytosol has two pathways:**
- Return to the mitochondria (via [[Delivery of Fuel to the Mitochondria|malate-alpha ketoglutarate]] transporter)
- Malic enzyme: Converts malate into pyruvate, forming NADPH. This is an alternate way a patient with [[Glycolysis and Pentose Phosphate#Clinical pearl Favism|Favism]] can form NADPH.
## Source of acetyl-CoA
***Acetyl-CoA for fatty acid synthesis comes from glucose catabolism, NOT beta-oxidation.*** When acetyl-CoA accumulates from beta oxidation, OAA concentrations will not increase (no pathway). Conversely, in glycolysis pyruvate can be shunted through pyruvate carboxylase to form OAA. Therefore, without the TCA intermediate in beta oxidation, citrate will not be generated and fats will not be synthesized.

![[Pasted image 20230826230913.png]]
## Part 1. Acetyl-CoA carboxylase
This is the regulatory step of fatty acid synthesis and produces malonyl-CoA ([[Delivery of Fuel to the Mitochondria#Carnitine Shuttle|inhibits CAT I]]). This insures fatty acid synthesis and fatty acid breakdown cannot happen simultaneously. 

It will also be inactivated by Protein Kinase A (PKA) upstream of [[Hormonal Regulation of Metabolism#Glucagon|glucagon]] binding when hypoglycemic.
## Part 2. Fatty acid synthase
This is largely the reverse of beta oxidation. Fatty acid synthase (ACP) will bind an acetyl-CoA and a malonyl-CoA. The carboxylic group of malonyl-CoA then leaves as CO2, creating a binding point for acetyl-CoA. The resulting condensation reaction forms a 4 carbon beta keto ACP (opposite of thiolase).

*Note: The electron carrier for these steps is NADPH rather than NADH.*
# Ketogenesis
Ketone bodies are produced only in the liver from fatty acids when starving. These must be converted into acetyl-CoA in other tissues around the body as the liver does not have the necessary enzyme, **beta-ketoacyl-CoA transferase**. The brain will also express this enzyme when starving to use ketone bodies as fuel. This process uses Succinyl-CoA to transfer the Coenzyme A to Acetoacetate, bypassing the succinyl-CoA synthase step of the TCA.

Ketone bodies also serve as a way to **get rid of excess acetyl-CoA**, which is converted to acetone and exhaled.

**Ketone bodies produced by the liver**
- Acetoacetate
- Beta-hydroxybutyrate
- Acetone

*Note: Acetoacetate and beta-hydroxybutyrate are negatively charged and will create acidic conditions when produced.*
## 1. Thiolase
Two molecules of acetyl-CoA are combined to produce acetoacetyl-CoA
## 2. HMG-CoA synthesis
This is the regulatory step of ketogenesis. The intermediate HMG-CoA is formed by adding a second acetoacetyl-CoA.

This step insures ketone bodies are only produced under excess acetyl-CoA conditions
## 3. HMG-CoA Lyase
An acetyl-CoA is cleaved from the molecule, forming acetoacetate
## 4. Formation of beta-hydroxybutyrate
The keto group on acetoacetate can be reduced to form beta-hydroxybutyrate via beta-hydroxybutyrate dehydrogenase. NADH is the cofactor.