---
technique: OP solid phase peptide synthesis
variant: OP microwave
category: peptide synthesis
tags:
  - microwave
  - spps
  - protein
status: complete
last_updated: May 25, 2025
---

# One Pot Solid Phase Peptide Synthesis - Microwave
## Summary
Procedure for one-pot solid phase peptide synthesis at elevated temperature. Best for smaller peptides <60 amino acids long
## Materials
- 1 lb. dry ice
- Small stir bar
- 10 ml filtered syringe
- Vacuum manifold
- Programmable Microwave
## Reagents
- [[DCM]]
- [[DMF|DMF]]
- [[Amino Acid Preparation - OP|OP Amino acid solution]]
- [[Piperadine Preparation|Piperadine]] or [[Piperazine Preparation|piperazine]] deprotection solution*
\* See notes for reagent amounts*
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
3. Ensure that the [[Amino Acid Preparation - OP|OP amino acid]] coupling solutions are fresh. **[[DIC Preparation|Activated DIC]] and [[Oxyma Preparation|activated oxyma]] only have a shelf life of around 24 hours**
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
2. Place capped syringe and microwave with *low stirring.* 
	1. Ramp to 75°C for 30 seconds
	2. Hold at 90°C for 120 seconds
	- While waiting, [[Amino Acid Preparation - H_TU|consider preparing your next amino acid solution]]
3. Drain deprotection solution on the vacuum manifold
4. Wash resin 5x with [[DMF]] on the vacuum manifold
### Coupling
1. Add sufficient prepared [[Amino Acid Preparation - OP|amino acid solution]] to your capped syringe
2. Place capped syringe in microwave with *low stirring* and perform the following an all amino acids *except histidine (see notes)*.
	1. Ramp to 75°C for 30 seconds
	2. Hold at 90°C for 120 seconds
3. Drain amino acid solution on the vacuum manifold
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

## Notes
### Melting your peptide
***DO NOT FORGET YOUR TEMPERATURE PROBE WHEN MICROWAVING YOUR PEPTIDE!*** If the temperature of your peptide solution is not monitored, it may rise to high enough temperatures that your protein may denature, side products can form, or may even cleave from your resin. If the temperature of your solution ever exceeds 95°C then you should not continue synthesis and may need to start over from the beginning.

### Coupling Histidine
Histidine is susceptible to *epimerization* at elevated temperatures. If normal microwaving procedures are performed, you may inadvertently racemize your histidine stereocenters through the following rough mechanism:

![[histidine.png]]

Therefore when coupling *histidine (His, H)*, instead do the following:
	1. Ramp to 25°C for 120 seconds
	2. Hold at 50°C for 480 seconds

Note that this issue only exists in the *activated histidine*, or when in the [[Amino Acid Preparation - OP|oxyma/DIC]] solution (*i.e.* in its reactive ester form).
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
