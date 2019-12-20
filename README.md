# MS-ready
Standardization workflow for MS-ready chemical structures pretreatment.
Starts from structures in SDF or smiles format and produces:
- SDF file with standardized structures in Kekule form (includes provided IDs, original structures, Salts/solvents, Inchi codes and keys)
- CSV file with  structures that failed standardization with a specified error flag (parsing and valence errors, inorganics, mixrutres...)
