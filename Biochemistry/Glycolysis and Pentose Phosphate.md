# Glycolysis steps
| Step | Reactant                 | Product                                                              | Enzyme                                       | dG (kJ/mol) | Notes                                                                                                                                                  |
| ---- | ------------------------ | -------------------------------------------------------------------- | -------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1    | glucose                  | glucose-6-phosphate (G6P)                                            | **Hexokinase**                               | -20.9       | **Irreversible** (ATP consumed)                                                                                                                            |
| 2    | G6P                      | Fructose-6-P (F6P)                                                   | **Phosphohexose isomerase**                  | 2.2         |                                                                                                                                                        |
| 3    | F6P                      | fructose 1,6-bisphosphate (F1,6BP)                                   | **Phosphofructokinase-1 (PFK-1)**            | -17.2       | **Irreversible** (ATP consumed). This step guarantees the sugar will proceed down glycolysis. Alternatively, G6P may have been shuttled to other pathways. |
| 4a   | F1,6BP                   | glyceraldehyde 3-phosphate (GAP) & dihydroxyacetone phosphate (DHAP) | **Aldolase**                                 | 22.8        | Reversible. GAP and DHAP concentration generally remain low                                                                                            |
| 4b   | DHAP                     | GAP                                                                  | **Triose Phosphate Isomerase**               | 7.9         | Only GAP can be used in step 6, so DHAP has to be converted                                                                                            |
| 5    | GAP, NAD+                | 1,3-bisphosphoglycerate (1,3-BPG), NADH                              | **Glyceraldehyde 3-phosphate dehydrogenase** | 12.2        |                                                                                                                                                        |
| 6    | 1,3-BPG, ADP             | 3-phosphoglycerate, ATP                                              | **Phosphoglycerate kinase**                  | -18.5       | 1 ATP is generated per GAP, so we are now net 0 energy wise                                                                                            |
| 7    |                          |                                                                      |                                              |             | NOT IMPORTANT                                                                                                                                          |
| 8    |                          |                                                                      |                                              |             | NOT IMPORTANT                                                                                                                                          |
| 9    | Phosphoenolpyruvate, ADP | Pyruvate, ATP                                                        | **Pyruvate kinase**                          | -31.4       | **Irreversible**                                                                                                                                           |

**Changes**:
- 2 ADP + 2 Pi → 2 ATP
- Glucose → 2 Pyruvate
- 2 NAD+ → 2NADH
- Also produces 2 H+, 2 H2O

Pyruvate is sent to [[PDC and Krebs (TCA)]].
## Regulators of PFK-1
Step 3 is the rate limiting step of glycolysis.

**Inhibitors**: ATP, Pyruvate (via citrate from oxidative phosphorylation)
**Activators**: AMP/ADP, F2,6BP, stimulated by [[Hormonal Regulation of Metabolism#Glucagon|glucagon]]

![[Pasted image 20230821010200.png]]
# Pentose phosphate pathway
PPP reduces NADP+ to NADPH+ (occurs twice) and produce **ribose 5-phosphate** which is used to make DNA/RNA. High NADPH relative to NADP+ will drive the biosynthesis of fatty acids and nucleotides.

**Oxidative phase**: NADP+ is reduced (twice) to NADPH
**Non-oxidative phase**: Rebuild a 6-carbon molecule from the 5-carbon form if it isn't used to make ribose 5-phosphate
## NADPH is important in radical cell defense
Reduced **glutathione** will use its unpaired S-H from cystine to match the unpaired electron in a reactive oxygen species (ROS) which would otherwise harm the cell. NADPH will reduce glutathione for this purpose.
### Clinical pearl: Favism
For people with a G6P deficiency, the PPP cannot produce NADPH. Because red blood cells do not have mitochondria for making oxaloacetate which would otherwise converted to extra NADPH, ROSs represent a serious threat.

People with Favism require supplementation with **Glucose-6-phosphate dehydrogenase (G6PDH).**