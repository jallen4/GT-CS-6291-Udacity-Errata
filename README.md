# GT-CS-6291-Udacity-Errata

## IPC Quiz
The percentages to the IPC quiz add up to 90%. That implies 10% of instructions take 0 cycles to execute! Not necessarily incorrect, but unrealistic.

## Review of ILP
In the class notes and the video for Review of ILP the instructor says that energy is inversely proportional to clock frequency.
         
Correction: Frequency is proportional to energy.

You would typically see this comparison made to power (even though energy is just power over time). In fact, you usually the see this relationship for dynamic power consumption defined in the form of the following equation:
```
P = CV2f
```

As always Wikipedia usually goes into good detail: https://en.wikipedia.org/wiki/CPU_power_dissipation.

## P1L2
First definition of VLIW, prof. Pande repeats himself on the number of transistors. This is surely an editing issue.

Role of the Compiler, there's a slip up at 0:31.

## VLIW v DSP Quiz
Check shows up in wrong place
Error for checking the bit reverse addressing is confusing

Example Pipeline
Typo in "Example Pipeline Revised by VEX contd."
 
I believe the syllable in instruction 6 should be

	cmpeq $b2 = $r22, 0

instead of

	cmpeq $r2 = $r22, 0

## P3L1
Post pass register allocation. Lecture 18. Bipartite graph creation.

Second graph, top left node v1B5, should be v1B6.

## P3L2
Differential Register Encoding. Lecture 12 Quiz.

Answer should be encoding of 13, not 3, so number of bits should be the same.

## P3L4
Def Use Chains. Lecture 14 Quiz

I believe the following quiz has an error for the DU of instruction 8. It says it is used only on line 6 and 8, but I believe it should be 6, 7, and 8

Motion Range Determination Quiz. Lecture 19 Quiz

I believe the motion range for 7 is wrong. It says it can move from 4-7 but instruction 6 would modify the value of what is in r5 if you move 7 above it.
