
# Two-Stage Classification Model for Scanning Electron Microscope Images in Materials Science
 Repository For our Paper Two-Stage Classification Model for Scanning Electron Microscope Images in Materials Science
 
 ### Training The Model:
 Steps : <br>
        1. Download The Dataset From ___ <br>
        2. Extract the Zip Folder in /Dataset<br>
        3. Run Train.py
            
```
            python train.py d_opt
```
            
 <strong>When d_opt =0 it would Train on the SEM Dataset</strong> <br>
 <strong> When d_opt =1 it would Train on the Particle Datset.</strong>
    
 <i> The Models Thus Generated Would Be Stored in the Models Folder <\br> The Plots Generated would be stored in Plots Folder. </i>
 ### Options.py
 Options.py Contains the training options for both SEM and Particle Dataset . To change any parameter in training process update the options.py.
 
 ### Dependencies
 Refer Requirements.txt for required dependencies.
 
