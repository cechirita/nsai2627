# Seminar 03 -- Logici temporale

## 1. LTL vs CTL vs CTL* 

a. Considerăm că "P" înseamnă "Îmi place să citesc" și Q înseamnă "E soare afară". Exprimați în limbaj natural următoarele formule în CTL:

	- AG.P

	- EF.P

	- AF.EG.P

	- EG.AF.P

	- AG(PUQ)

	- EF((EX.P)∨(AG.Q))

b. În ce logică sunt scrise următoarele formule? Putem găsi formule echivalente în LTL pentru cele scrise în CTL? Dar invers? Dar în CTL*? 

	- F(G p)

	- AG(EF(p))

	- AFG(p)

	- AG( p → (EXq ∧ EX¬q) )

	- EX(p)
	
	- EX(p)	∧ AFG(p)

## 2. To infinity and beyond: [automate Büchi](https://en.wikipedia.org/wiki/B%C3%BCchi_automaton)

a. Cum transformăm formule LTL în automate Büchi?

- [Automate Büchi, LTL](https://spot.lre.epita.fr/concepts.html)

- [Algoritmi de transformare](https://en.wikipedia.org/wiki/Linear_temporal_logic_to_B%C3%BCchi_automaton)

b. Dați 3 exemple de propoziții în LTL și obțineți automatele Büchi corespunzătoare folosind cod într-un limbaj la alegere. Inspo: 

- [SPOT - C++ library for LTL2TGBA translations](https://spot.lre.epita.fr/index.html)

- [Fast LTL to BA translator via alternating automata](https://lsv.ens-paris-saclay.fr/~gastin/ltl2ba/)


## 3. Model checking: [SPIN](https://en.wikipedia.org/wiki/SPIN_model_checker) vs [NuSMV](https://nusmv.fbk.eu/overview.html)

- What is [SPIN](https://spinroot.com/spin/whatispin.html)?
Citiți [aici.](https://spinroot.com/spin/Doc/p40-ben-ari.pdf)

- Dar [NuSMV](https://nusmv.fbk.eu/tutorial/v27/tutorial.pdf)?

Alegeți un tool și testați-l pe un exemplu din tutoriale.
