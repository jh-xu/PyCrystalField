## Code used to fit the CEF Hamiltonians of Nd3Sb3Mg2O14, Nd3Sb3Zn2O14, and Pr3Sb3Mg2O14

To get the code to run, place the Ipython notebooks in the same directory as the files in the main directory. Then, make sure the parts of the code referencing the data folders have the correct directories.

### Format

For each compound, one file carries out the fits ('NdMg.ipynb') and exports pickle files of the results, and another file plots the results generated by the first file ('NdMg-PlotResults.ipynb'). On my laptop, the fits take about 45 minutes.

The subdirectory 'IntermediateCoupling' has the files used to fit the Nd3Sb3Mg2O14 crystal field levels using the intermediate coupling scheme for Nd (including spin orbit coupling).

The subdirectory 'Data' has three things: (i) neutron scattering data used in the fits, (ii) susceptibility data used in the fits, and (iii) the calculated resolution function for the ARCS spectrometer.
