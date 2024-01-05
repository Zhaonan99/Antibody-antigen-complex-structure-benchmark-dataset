The repository contains 112 antibody-antigen docking test cases, with bound and unbound structures, stored in the ABAG-Docking_benchmark_dataset folder. Users can download the set to test and benchmark their prediction algorithms. Each folder is a test case, and the folder contains four pdb files. Their nomenclature and meaning are as follows:
PDBID_r_b.pdb: Bound antibody structure;
PDBID_l_b.pdb: Bound antigen structure;
PDBID_r_u.pdb: Unbound antibody structure;
PDBID_l_u.pdb: Unbound antigen structure.

The bound structures of antibody and antigen are derived from the same protein complex PDB, and the unbound structures of antibody and antigen are derived from other proteins that can align with the protein complex. For example, 6OEJ_r_b.pdb and 6OEJ_l_b.pdb are from the antibody-antigen complex in 6OEJ, but 6OEJ_r_u.pdb is the structure from 4FZ8 and 6OEJ_l_u.pdb is the structure from 3TGT. Here the bound and unbound structures have been pre-aligned to facilitate visualization of conformational changes.

Note: The file "ABAG-Docking_benchmark_dataset_PDBID.txt" lists all PDB IDs in the ABAG-Docking benchmark dataset. Among these 112 antibody-antigen docking test cases, there are 25 cases where the antigen unbound structure is looking for a longer amino acid sequence than the bound structure. Therefore, for these 25 cases, we provide both truncated and untruned versions of data.

