# Docking-Ligand-File-formatting-conversion
Automating Ligand Conversion – GitHub Repository This Python script automates the conversion of molecular ligand files between different formats using Open Babel. Developed by Dr. Fatima, it is designed for computational chemists and bioinformaticians involved in molecular docking and virtual screening.
Features
Batch Processing: Converts multiple ligand files at once based on an input list.
Flexible Format Support: Allows conversion between various molecular file formats such as .sdf, .pdbqt, and others supported by Open Babel.
3D Structure Generation: Uses Open Babel’s --gen3d flag to generate 3D molecular structures.
Error Handling: Provides basic error messages for troubleshooting installation and input issues.
Usage
Run the script using the following command:

bash
Copy
Edit
python3 Automating_ligand_conversion.py input_file.txt input_format output_format
Example command to convert .sdf files to .pdbqt:

bash
Copy
Edit
python3 Automating_ligand_conversion.py input_list.txt sdf pdbqt
where input_list.txt contains:

Copy
Edit
1.sdf
2.sdf
3.sdf
This will generate 1.pdbqt, 2.pdbqt, etc.

Dependencies
Python 3
Open Babel (Ensure it is installed and accessible via the command line)
OS and SYS libraries (Included in Python’s standard library)
Error Handling
If you encounter issues:

Verify that Open Babel is installed and properly configured.
Ensure the input file is formatted correctly.
Check that Python’s os and sys libraries are properly installed.
This script is useful for computational chemists and bioinformaticians working on molecular docking, virtual screening, and ligand preparation. 🚀
