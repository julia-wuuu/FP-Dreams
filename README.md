# FP-Dreams
Final project for CS32!

We will be parsing through all the antigens on the WHO virus priority list to calculate their epitopes (where the virus binds to the antibody). I will do this by working with PDB files of structures that are in complex with an antigen and antibody, then calculating the distances between each atom to see which amino acids are involved in antigen binding.

Update: Running the epitope calculator

To run the function epitope_calculator, you must input a PDB (Protein Data Bank) ID that corresponds to a structure that is:
  1. In complex with an antibody
  2. Existing in the Sabdab database (databse of antibody-antigen sequence structures)

