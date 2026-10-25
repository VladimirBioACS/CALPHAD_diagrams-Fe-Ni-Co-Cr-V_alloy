## CALPHAD binary phase diagram

# General description

This repository contains a Python Jupyter notebook that generates a binary phase diagram using the CALPHAD method. The notebook utilizes the `pycalphad` library to perform thermodynamic calculations and visualize the results.

The following binary system were analyzed: 

- Co-Cr;
- Co-Fe;
- Co-Ni;
- Co-V;
- Cr-Fe;
- Cr-Ni;
- Cr-V;
- Fe-Ni;
- Fe-V;
- Ni-V.


# Project Structure

All databases used in this project are available in the `database` folder. The Jupyter notebook that performs the calculations and generates the phase diagram is located in the `root` folder.

- database: Contains the necessary thermodynamic database files for the CALPHAD calculations.
- root: Contains the Jupyter notebook that performs the calculations and generates the phase diagram.

The TDB files used in this project were obtained from the PhaseDiagram.org website (https://www.phasediagram.org/).
