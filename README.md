# RoFi_replicabilty_repository
RoFi Mesh Denoising Algorithm 
# RoFi-Mesh-Denoising


Yadav SK, Reitebuch U, Polthier K. "Robust and high fidelity mesh denoising." IEEE Trans Vis Comput Gr 2018. 1–1. doi: 10.1109/TVCG.2018.2828818 .

# Robust and high fidelity mesh denoising

Abstract: This paper presents a simple and effective two-stage mesh denoising algorithm, where in the first stage, face normal filtering is done by using bilateral normal filtering in a robust statistics framework. Tukey’s bi-weight function is used as similarity function in the bilateral weighting, which is a robust estimator and stops the diffusion at sharp edges to retain features and removes noise from flat regions effectively. In the second stage, an edge-weighted Laplace operator is introduced to compute a differential coordinate. This differential coordinate helps the algorithm to produce a high-quality mesh without any face normal flips and makes the method robust against high-intensity noise.

# Requirement:

Java.

# Input Supported File:
obj, off, stl and jvx.

# Instructions:

    To compile the provided source code:
    
    1. Please extract the folder replicabilityData.7z.
    
    2. It has 6 different folders regarding the different models.
    
    3. Each folder has a .bat file for windows users (e.g. launcherBearingWin.bat in bearing_figure-11 folder) and .sh flie for unix users (e.g. launcherBearingUnix.sh in bearing_figure-11 folder).
    
    4. Run the .bat file by double click on windows platform.
    
    5. On Unix system, go to the corresponding folder using terminal and  Run the .sh file using the command "./launcherBearingUnix.sh".
    
    6. It will open a new window with a loaded model.
    
    7. For every model, we fix the parameters in the scroll bars, so you dont have to change them.
    
    8. To compute the noise-free mesh, user has to press the denoising button (RoFi Denoising).
    
    9. After that this button color will change and algorithm started.
    
    10. current status of the algorithm is displayed in lower left corner of the smoothing window.
    
    11. Mesh quality of the mesh can be computed using the mesh quaility button.
   

If you have further questions or not able to compile the algorithm, please write me on following emails:
 
 sunil.yadav@fu-berlin.de
 
 sunil7545@gmail.com



