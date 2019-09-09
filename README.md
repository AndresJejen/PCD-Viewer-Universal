# PCD-Viewer-Universal

In this Repo you can find a simple code based on Examples of PCL library 

Visualization: http://pointclouds.org/documentation/tutorials/cloud_viewer.php#cloud-viewer

## How to use?

- 1. Install all libraries on your ubuntu PC. (i'm using WSL on Ubuntu 18 LTS)
  
  - a. ```sudo apt get update```
  - b. Install CMake
     https://www.youtube.com/watch?v=HKPAmqDXbms
  - c. ```apt-cache search libpcl```  (Search all libraries)
        - (Result)  
        - ```
                  libpcl-apps1.8 - Point Cloud Library - apps library   
                  libpcl-common1.8 - Point Cloud Library - common library   
                  libpcl-conversions-dev - Robot OS library to convert from/to PCL data types   
                  libpcl-dev - Point Cloud Library - development files   
                  libpcl-doc - Point Cloud Library - documentation   
                  libpcl-features1.8 - Point Cloud Library - features library   
                  libpcl-filters1.8 - Point Cloud Library - filters library   
                  libpcl-io1.8 - Point Cloud Library - I/O library   
                  libpcl-kdtree1.8 - Point Cloud Library - kdtree library   
                  libpcl-keypoints1.8 - Point Cloud Library - keypoints library   
                  libpcl-ml1.8 - Point Cloud Library - ml library   
                  libpcl-msgs-dev - C/C++ headers for PCL-related Robot OS Messages   
                  libpcl-octree1.8 - Point Cloud Library - octree library   
                  libpcl-outofcore1.8 - Point Cloud Library - outofcore library   
                  libpcl-people1.8 - Point Cloud Library - people library   
                  libpcl-recognition1.8 - Point Cloud Library - recognition library   
                  libpcl-registration1.8 - Point Cloud Library - registration library          
                  libpcl-sample-consensus1.8 - Point Cloud Library - sample consensus library   
                  libpcl-search1.8 - Point Cloud Library - search library   
                  libpcl-segmentation1.8 - Point Cloud Library - segmentation library         
                  libpcl-stereo1.8 - Point Cloud Library - stereo library  
                  libpcl-surface1.8 - Point Cloud Library - surface library   
                  libpcl-tracking1.8 - Point Cloud Library - tracking library   
                  libpcl-visualization1.8 - Point Cloud Library - visualization library        
                  libpcl1 - Portable Coroutine Library (PCL)   
                  libpcl1-dev - Portable Coroutine Library (PCL), development files  
                  ```   
  - d. install one by one   
        - using this command   
        - ```sudo apt-get install libpcl-apps1.8 libpcl-common1.8 libpcl-conversions-dev libpcl-dev libpcl-doc libpcl-features1.8 libpcl-filters1.8```   
        - ```sudo apt.get install libpcl-io1.8 libpcl-kdtree1.8 libpcl-keypoints1.8 libpcl-ml1.8 libpcl-msgs-dev libpcl-octree1.8 libpcl-outofcore1.8```   
        - ```sudo apt-get install libpcl-people1.8 libpcl-recognition1.8 libpcl-registration1.8 libpcl-sample-consensus1.8 libpcl-search1.8```   
        - ```sudo apt-get install libpcl-segmentation1.8 libpcl-stereo1.8 libpcl-surface1.8 libpcl-tracking1.8 libpcl-visualization1.8```   
        - ```sudo apt-get install libpcl1 libpcl1-dev```       
 - 2. If you are using WSL like me :D, you need install a GUI interface for Ubuntu WSL   
     - https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/   
 - 3. clone repository   
     - ```git clone https://github.com/AndresJejen/PCD-Viewer-Universal.git ```   
 - 4. ```cd PCD-Viewer-Universal```   
 - 5. Execute this command   
          - ```./cloud_viewer NAME_OF_YOUR_PCD_FILE.pcd```   
 
 - That´s All   
 
## Editing and compiling the code   
 
 1. Edit the file ```cloud_viewer.cpp```   
 2. in bash execute on root project folder   
        ```cmake .```   
        ```make```   
        ```./cloud_viewer NAME_OF_YOUR_PCD_FILE.pcd```   
 
 Enjoy it
 
 ## Twitter: @andres_jejen
 ## Medium Articles: https://medium.com/@andresjejen
      
  
  
  
  
