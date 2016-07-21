This is a stand-alone version of ProMol, the protein characterization tool. 
It requires the numpy package installed and part of the pythonpath variable.
To run it, from a command line, navigate to the installation folder, and run
the command: "python ProMol.py", no quotes. There are four tabs, welcome,
motiffinder, motifmaker and database. The welcome tab, as its name implies, 
is a welcome screen, includes any errors with loading the motif library.
The Motiffinder is used to search user-given query PDB's for the existance of
any motifs from ProMol's motif library. It also has an option for calculating
the RMSD between the motif and its match within the protein as well as the 
ability to export the query matches as PDB files that can be exported and opened
in any visualization tool the user desires. The Motifmaker can be used by users
to create their own motifs based off of existing PDB's. The database can be used 
to save results so tht they can be quickly loaded in motiffinder.