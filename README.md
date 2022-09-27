# AMBER application : G Protein-coupled receptors (GPCRs)

Tutorial on the setup and simulation of a membrane protein with AMBER Lipid21 and PACKMOL-Memgen

G protein-coupled receptors (GPCRs) play a major role in intercellular communication by binding small diffusible ligands (agonists) at the extracellular surface. Agonist-binding induces a conformational change in the receptor, which results in the binding and activation of heterotrimeric G proteins within the cell.

![Alt text](https://github.com/Jahan08/Amber-tutorial/blob/main/m2_setup.png "M2_IXO")

# Introduction:

This tutorial describes how to construct and simulate a GPCR membrane protein system using AMBER. In this case, we will setup and simulate the agonist bound, active state of the M2 muscarinic receptor, the structure of which was solved in 2013 (https://www.nature.com/articles/nature12735). The PDB code is 4MQS - active human M2 muscarinic acetylcholine receptor bound to the agonist iperoxo.

Muscarinic acetylcholine receptors (M1–M5) are GPCRs that regulate the activity of a diverse array of central and peripheral functions in the human body, including the parasympathetic actions of acetylcholine1. The M2 muscarinic receptor subtype has a key role in modulating cardiac function and many important central processes, such as cog- nition and pain perception

An agonist is a drug that binds to the receptor, producing a similar response to the intended chemical and receptor. Whereas an antagonist is a drug that binds to the receptor either on the primary site, or on another site, which all together stops the receptor from producing a response.

The main difference between these two drugs is that one simulates the intended reaction, where as an antagonist binds to the receptor, and stops/ slows responses.
