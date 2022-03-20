# View-Thin-Section-Images-from-a-Porosity-Permeability-Cross-Plot-using-Python-Altair
We have used some very simple python code to view thin sections from a porosity vs. permeability cross plot using python's Altair and Pane.

Many of us make a living at characterizing reservoirs and yet sometimes we can get separated from the rock itself. Do we truly understand the textural differences in the reservoir? Do we know what is controlling reservoir quality? In the past we have used Spotfire to integrate our Routine Core Analysis (RCA) with the SCAL, but we have found new ways to use python to accomplish the same task. We are using Altair and Panes for our python coding. 

There is an added bonus in that we can also select the samples from the cross plot and a table to the right of the cross plot shows us the RCA data associated with the selected samples. We are searching for a method to actually show the thumbnails of the thin section image in the same table of selected data too. More to come. 

The workflow is simple. We read in an Excel file as shown below that links the name of the thin section images to our RCA data, and then we let python do the rest. 

This clastic example is a combination of a few samples where we had porosity, permeability and thin section photomicrographs, and the workflow is as easy as it gets:

1) We read an Excel file as shown below to create a pandas DataFrame in python:

![Geolog_Image](Excel.png)

2) We use our Jupyter Notebook to obtain the following output:

![Geolog_Image](sqrt_k_phi.gif)

In this GitHub repository we have placed our images in a ./data subdirectory to reduce the clutter and organize our data.

The next phase of this GitHub repository is to integrate the High Pressure Mercury Inject (HPMI) data too. Stay tuned in to observe how the Capillary Pressure curves vary with the texture of the rock. 
