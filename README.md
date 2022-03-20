# View-Thin-Section-Images-from-a-Porosity-Permeability-Cross-Plot-using-Python-Altair
We have used some very simple python code to view thin sections from a porosity vs. permeability cross plot using python's Altair and Pane.

Many of us make a living at characterizing reservoirs and yet sometimes we can get seperated from the rock itself. Do we truly understand the textural differences in the reservoir? Do we know what is controlling reservoir quality? In the past we have used Spotfire to integrate our Routine Core Analysis (RCA) with the SCAL, but we have found new ways to use python to accomplish the same task. We are using Altair and Panes for our python coding. 

The workflow is simple. We read in an Excel file as shown below that links the name of the thin section images to our RCA, and then let python do the rest. 

This clastic example is just a combination of a few samples that had porosity, permeability and thin section photo micorgraphs, and the workflow is just as simple:

1) We read an Excel file as shown below to create a pandas DataFrame:

![Geolog_Image](Excel.png)

2) we run the Jupyter Notebook to get the following output:

![Geolog_Image](sqrt_k_phi.gif)

We have put all of our images in a data subdirectory.

The next phase of this GitHub repository is to integrate the High Pressure Mercurn Inject (HPMI) data too. Stay tuned in to observe how the Capillary Pressure curves change with the texture of the rock. 
