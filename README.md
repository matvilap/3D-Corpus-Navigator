# 3D-Corpus-Navigator
Concatenative Synthesis in an FPS-style 3D interface. Made with Unreal Enginge 5 and FluCoMa (Max/MSP) with bi-directional OSC communication.

# Download and Install Instructions

The .zip file contains the Windows application made in Unreal Engine 5 to run the virtual environment.

The Max collective file (.mxf) requires Max runtime and FluCoMa toolkit installed.

# Using the Max patch for sound analysis
![3d-corpusnav-max-02](https://github.com/user-attachments/assets/c83e0017-739d-4ab7-8256-5e5dd9ecf4a2)

0) Setup IP address for communication with the virtual environment. By default it is set to local host IP address, send port 8001, and receive port 1234.

1) Drag and drop folder with multiple or a single sound file in the purple box.

2) Select between FluCoMa's novelty slice or onset slice and set the threshold for the selected algorithm, then hit bang to slice. When the process is over the number box labeled 'Total slices' will indicate the number of slices generated, and you should be able to see the waveform of your sound collection as a single buffer at the top center of the patch. Adjust setting and repeat to get a different number of slices, these are not all the same length.

3) Select what types of descriptor analysis to apply to the sound corpus. Select the algorithm to generate data to plot in XY plane and Z axis respectively, hit bang to start the analysis. When the process is over, the data matrix should appear in the Max console.

4) Once the descriptor analysis data has been generated plot the XY analysis in the 2D graph. Select between PCA and UMAP for dimensionality reduction, adjust parameters for UMAP if selected. Hit bang to plot, the result is shown in the graph in the middle of the patch. 

5) Select the scale and orientation that will be used to plot the descriptor analysis data in 3D space. The default parameters are: xyz, and scale of 1000 units for each axis. **Do not hit the spawn button without having opened the 3D environment** 

6) Turn the audio on, click and drag cursor on the graph to activate different slices to test the audio output.

# Running the virtual environment
Download the 3DCorpusNavigator.zip file on a Windows machine and unzip, the current version does not run on OSX. Inside the 'Windows' folder run the .exe file to run the virtual environment. 

# Controls in the virtual environment
In order to visualize the point and interact with it, be sure to follow all the steps to run the analysis in the Max patch first. Once you have run the sound descriptor analysis in Max, and in the virtual environment, you can use a mouse and keyboard or a game controller (Xbox, PS, Switch, etc) to move and interact in virtual space.

<img width="1083" alt="controller_pointcloud_v3" src="https://github.com/user-attachments/assets/4b5e1aed-5dc9-46d9-a8e3-86693d876aeb" />




