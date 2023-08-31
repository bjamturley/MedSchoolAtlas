# Glycolysis steps
| Step | Reactant                 | Product                                                              | Enzyme                                       | Energy                      | dG (kJ/mol) | Notes                                                                                                                                            |
| ---- | ------------------------ | -------------------------------------------------------------------- | -------------------------------------------- | --------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1    | glucose                  | glucose-6-phosphate (G6P)                                            | **Hexokinase**                               | Irreversible (ATP consumed) | -20.9       | First waterfall step                                                                                                                             |
| 2    | G6P                      | Fructose-6-P (F6P)                                                   | **Phosphohexose isomerase**                  |                             | 2.2         |                                                                                                                                                  |
| 3a   | F6P                      | fructose 1,6-bisphosphate (F1,6BP)                                   | **Phosphofructokinase-1 (PFK-1)**            | Irreversible (ATP consumed) | -17.2       | Second waterfall step. This step guarentees the sugar will proceed down glycolysis. Alternatively, G6P may have been shuttled to other pathways. |
| 3b   | F1,6BP                   | glyceraldehyde 3-phosphate (GAP) & dihydroxyacetone phosphate (DHAP) | **Aldolase**                                 | Reversible                  | 22.8        | GAP and DHAP concentration generally remain low                                                                                                  |
| 3c   | DHAP                     | GAP                                                                  | **Triose Phosphate Isomerase**               |                             | 7.9         | Only GAP can be used in step 6, so DHAP has to be converted                                                                                      |
| 4    | G6P, NAD+                | 1,3-bisphosphoglycerate (1,3-BPG), NADH                              | **Glyceraldehyde 3-phosphate dehydrogenase** |                             | 12.2        |                                                                                                                                                  |
| 5    | 1,3-BPG, ADP             | 3-phosphoglycerate, ATP                                              | **Phosphoglycerate kinase**                  |                             | -18.5       | 1 ATP is generated per GAP, so we are now net 0 energy wise                                                                                      |
| 6    |                          |                                                                      |                                              |                             |             | NOT IMPORTANT                                                                                                                                    |
| 7    |                          |                                                                      |                                              |                             |             | NOT IMPORTANT                                                                                                                                    |
| 8    | Phosphoenolpyruvate, ADP | Pyruvate, ATP                                                        | **Pyruvate kinase**                          | Irreversible                | -31.4       | Third waterfall step                                                                                                                             |

**Changes**:
- 2 ADP + 2 Pi → 2 ATP
- Glucose → 2 Pyruvate
- 2 NAD+ → 2NADH
- Also produces 2 H+, 2 H2O

Pyruvate is sent to [[PDC and KREBS (TCA)]].
## Regulators of PFK-1
Step 3 is the rate limiting step of glycolysis.

Too much ATP production will inhibit PFK-1
Too much AMP/ADP will activate PFK-1
F2,6BP, stimulated by [[Hormonal Regulation of Metabolism#Glucagon|glucagon]], will activate PFK-1
Pyruvate goes on to create citrate in oxidative phosphorylation, which provides negative feedback

![[Pasted image 20230821010200.png]]

# Anaerobic metabolism
**Lactate dehydrogenate** will oxidize NADH/H+ in anaerobic conditions. This is often conducted by fast-twitch muscle fibers.
# Pentose phosphate pathway
PPP reduces NADP+ to NADPH+ (occurs twice) and produce ribose 5-phosphate for biosynthesis.

High NADPH relative to NADP+ will drive the biosynthesis of fatty acids and nucleotides. ribose 5-phosphate is used to make DNA/RNA.

Oxidative phase: NADP+ is reduced (twice) to NADPH
Non-oxidative phase: Rebuild a 6-carbon molecule from the 5-carbon form if it isn't used to make ribose 5-phosphate
## NADPH is important in radical cell defense
Reduced glutathione will use its unpaired S-H from cystine to match the unpaired electron in a reactive oxygen species (ROS) which would otherwise harm the cell. NADPH will reduce glutathione for this purpose.
### Clinical pearl: Favism
For people with a G6P deficiency, the PPP cannot produce NADPH. Because red blood cells do not have mitochondria which would otherwise provide extra NADPH, ROSs represent a serious threat.

People with Favism require **supplementation with G6PDH**.