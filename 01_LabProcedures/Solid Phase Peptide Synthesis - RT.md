---
technique: RT solid phase peptide synthesis
variant: room temperature
category: peptide synthesis
tags:
  - spps
  - room-temp
  - protein
status: 
last_updated: May 25, 2025
---

# Solid-Phase Peptide Synthesis (Room Temperature)
## Summary
Solid-phase peptide synthesis at room temperature on a resin. Best for smaller peptides <60 amino acids long
## Materials
- 1 lb. dry ice
- Small stir bar
- 10 ml filtered syringe
- Vacuum manifold
## Reagents
- [[Rink Amide|Rink Amide resin]] or other appropriate solid resin \*
- [[DCM]]
- [[DMF|DMF]]
- [[Piperidine Preparation|Piperidine]] or [[Piperazine]] (*see notes*)
- [[Amino Acid Preparation - H_TU|H*TU Amino acid solution]]
\* *See notes for resin amounts* 

## Procedure
### Workflow
Solid-phase peptide synthesis follows a few basic steps described below:
1. [[#Beginning a Peptide |Begin]] or [[#Continuing a Peptide|continue]] a peptide
2. Repeat for each amino acid until [[#Halting and Completion|completed or halting]]:
	1. [[#Deprotection|Deprotect]]
	2. [[#Coupling|Couple]]
### Before Synthesis
1. Ensure that the vacuum manifold is properly set with the *lab vacuum* turned on and dry ice in the capture container.
2. Ensure that the [[Piperidine]] and/or [[Piperazine]] are fresh enough to use. Though not strictly mandatory, they should be made fresh every 2-3 weeks
### Beginning a Peptide
1. Add stir bar and necessary amount of resin to syringe and cap
2. Add [[DCM]] to fully submerge the resin (*approx.* 5ml - 6ml)
	- Anticipate that the resin may expand to 2-3 times its original size, and should *remain fully submerged while swelling*
3. After swelling in [[DCM]] for **10 minutes**, drain on the vacuum manifold, and recap the syringe.
4. Add [[DMF]] to fully submerge the resin (*approx.* 5ml - 6ml)
	- Anticipate that the resin may expand slightly and should *remain fully submerged while swelling*
5. After swelling in [[DMF]] for **3 minutes**, drain on the vacuum manifold, and recap the syringe.
### Deprotection
1. Add sufficient deprotection solution (*see notes*) for scale to your capped syringe.
2. Place capped syringe on a stir plate for **20 minutes** on low stirring
	- While waiting, [[Amino Acid Preparation - H_TU|consider preparing your next amino acid solution]]
3. Drain deprotection solution on the vacuum manifold
4. Wash resin 5x with [[DMF]] on the vacuum manifold
### Coupling
1. Add sufficient prepared [[Amino Acid Preparation - H_TU|amino acid solution]] to your capped syringe
2. Place capped syringe on stir plate for **15 minutes**.
3. Drain [[Amino Acid Preparation - H_TU|amino acid solution]] on the vacuum manifold
4. Wash resin 5x with [[DMF]] on the vacuum manifold
\* If performing a *double couple*, perform this procedure twice
### Halting and Completion
**Ensure that you have last performed a coupling step!*** Halting after a deprotection may result in the destruction of your peptide.
1. Wash resin 5x with [[DMF]]
2. Wash resin 10x with [[DCM]]
3. Stop and cap your syringe/peptide resin and place in designated storage area
### Continuing a Peptide
**These steps are identical to beginning a peptide***
 1. Add [[DCM]] to fully submerge the resin (*approx.* 5ml - 6ml)
	- Anticipate that the resin may expand to 2-3 times its original size, and should *remain fully submerged while swelling*
2. After swelling in [[DCM]] for **10 minutes**, drain on the vacuum manifold, and recap the syringe.
3. Add [[DMF]] to fully submerge the resin (*approx.* 5ml - 6ml)
	- Anticipate that the resin may expand slightly and should *remain fully submerged while swelling*
4. After swelling in [[DMF]] for **3 minutes**, drain on the vacuum manifold, and recap the syringe.
## Related Techniques
- [[Solid Phase Peptide Synthesis - OP Microwave]]
- [[Amino Acid Preparation - H_TU]]

## Notes
### Resin Measurement
The amount of resin necessary can be calculated using the following formula:
$$
ResinAmount(mg)=\frac{SynthesisScale(µM)}{ResinLoading(g)}
$$
The *ResinLoading* value can be found on the stock container or wherever chemical details are found.

For example, if synthesizing a peptide at a 75µM scale with a resin with a loading of *.42g*, you would use
$$
\frac{75(µM)}{0.42(g)} = 178.6(mg)
$$

### Piperidine *vs.* Piperazine
[[Piperazine Preparation|Piperazine]] is always appropriate to use, but is more expensive that [[Piperidine Preparation|piperidine]]. It is common to use piperidine when synthesizing a peptide **up to and until the first appearance of an aspartic acid (Asp, D).** After coupling an aspartic acid, piperazine *must be used for the remainder of the peptide.*

Since this reaction is performed in excess, generally, about 1.0ml to 1.5ml should be used for every 25µM of scale. For example, if synthesizing at a 75µM scale, one would use 3ml to 4.5ml of deprotection solution.

### Pausing Work
Manual peptide synthesis can require tens of hours of work to complete. Therefore, when work must be paused, **ensure that your last procedure was a *coupling* step.** You never want to pause work on a peptide with a deprotected terminus.
