# PDBspheres

PDBspheres is a structure-based method for finding and evaluating structural similarities in protein regions relevant to 
ligand binding. PDBspheres comprises an exhaustive library of protein structure regions (“spheres”) adjacent to complexed 
ligands derived from the Protein Data Bank (PDB), along with methods to find and evaluate structural matches between a protein 
of interest and spheres in the library. PDBspheres uses the LGA structure alignment algorithm as the main engine for detecting 
structure similarities between the protein of interest and template spheres from the library, which currently contains more 
than 2 million spheres. To assess confidence in structural matches an all-atom-based similarity metric takes sidechain placement 
into account. 

Manuscript submitted to bioRxiv:\
Adam T. Zemla, Jonathan E. Allen, Dan Kirshner, Felice C. Lightstone. (2022) "PDBspheres - a method for finding 3D similarities 
in local regions in proteins", bioRxiv preprint https://doi.org/10.1101/2022.01.04.474934

Correspondence should be addressed to:\
Adam T. Zemla\
Global Security Computing Applications\
Lawrence Livermore National Laboratory\
Livermore, CA, 94550, USA\
Tel: US +1 (925) 423-5571\
Mobile1: (925) 724-7948\
Mobile2: (925) 759-4119\
Fax: US +1 (925) 423-6437\
Email: zemla1@llnl.gov\

Supplemental Data:\
The PDBspheres library and instructions how to use the LGA program are made publicly available for download at 
https://github.com/LLNL/PDBspheres

1. Library of PDBspheres compound binding sites divided into 11 subsets in the folder PDBspheres-Libraries:
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_01.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_02.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_03.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_04.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_05.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_06.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_07.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_08.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_09.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_10.zip                      size  22M
- Pdb_HET.at_least_1_HETATM_and_5_CA.list.Subset_11.zip                      size  22M

2. Library of PDBspheres short-peptide binding sites in the folder PDBspheres-Libraries:
- Library.Pdb_PEP.peptide_25_and_sphere_5_CA.list.txt.zip                    size 7.6M

3. A summary table of predicted pocket-ligands for a structural model of papain-like proteinase (PL2pro model: nCoV_nsp3.6w9c_A.pdb):
- PDBspheres.COVID19_PL2pro.protein_ligand_summary.txt.zip                   size 7.4K

4. Results from PDBspheres analysis of pairwise similarities in binding sites between proteins from PDBbind v.2019: 
- PDBspheres.PDBbind_Binding_sites_similarities.GDC_and_affinities.txt.zip   size  21M

5. Specifics of assigned EC annotations for each member of created clusters of PDBbind: 
- PDBspheres.PDBbind_Clusters.EC_included.txt.zip                            size  37K

6. Specifics of assigned GO annotations for each member of created clusters of PDBbind: 
- PDBspheres.PDBbind_Clusters.GO_included.txt.zip                            size  76K

7. Specifics of assigned SCOP annotations for each member of created clusters of PDBbind: 
- PDBspheres.PDBbind_Clusters.SCOP_included.txt.zip                          size  38K

8. HTML file allowing interactive overview of predicted clusters of proteins from PDBbind: 
- PDBspheres.PDBbind_Clusters.interactive_plot.html.zip                      size 4.0M
