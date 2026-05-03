# FP-Dreams
Final project for CS32!

We will be parsing through all the antigens on the WHO virus priority list to calculate their epitopes (where the virus binds to the antibody). I will do this by working with PDB files of structures that are in complex with an antigen and antibody, then calculating the distances between each atom to see which amino acids are involved in antigen binding.

We use the opensource package BioPython to help parse through PDB files.
We also use the opensource library "Tqdm" to visualize a progress bar for especially large dataframes. 

Update: Running the epitope calculator

To run the function epitope_calculator, you must input a PDB (Protein Data Bank) ID that corresponds to a structure that is:
  1. In complex with an antibody
  2. Existing in the Sabdab database (databse of antibody-antigen sequence structures)

To run the full function parsing_data, you must input a dataframe with your PDB IDs in the 5th column of your dataframe. Refer to the 3rd cell "df_who" as an example. This function will return a dataframe with an extra column titled "epitopes" with the epitopes in a string joined by '+' signs. 

