# 3D-Corpus-Navigator
Concatenative Synthesis in an FPS-style 3D interface. Made with Unreal Enginge 5 and FluCoMa (Max/MSP) with bi-directional OSC communication.

# Download and Install Instructions

The .zip file contains the Windows application made in Unreal Engine 5 to run the virtual environment.

The Max collective file (.mxf) requires Max runtime and FluCoMa toolkit installed.

# Using the Max patch
![3d-corpusnav-max-02](https://github.com/user-attachments/assets/c83e0017-739d-4ab7-8256-5e5dd9ecf4a2)

1) Drag and drop folder with sound corpus in purple box, select preset if desired

2) Adjust the slicing algorithm (novelty slice or onset slice) and threshold, hit bang to slice. When the process is over the number box will indicate the number of slices in the sound corpus.

3) Descriptor analysis of the sound corpus. Select algorithm to generate data to plot in XY plane and Z axis respectively, hit bang to start the analysis. When the process is over, the matrix of data should appear in the Max console.

4) Plot in 2D. Select between PCA and UMAP for dimensionality reduction, adjust parameters for UMAP if selected. Hit bang to plot, the result is shown in the graph in the middle of the patch. 

5) Plot 3D. Start with the default parameters: xyz, and scale of 1000 units for each axis.

6) Turn the audio on, click and drag cursor on the graph to activate different slices and test the audio output.

7) Select a preset in the movement preset area.

# Controls in the virtual environment
