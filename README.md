
This is an instruction how to install and setup PROJ for testing.


## Download

Clone Proj from github. Select Master branch.

https://github.com/OSGeo/PROJ


If you like to test new functionalities from NMA, clone the Github repository:

https://github.com/himsve/PROJ/tree/NMA 


Additonal resource files from NMA are available at this repository:

https://github.com/himsve/PROJ_Resources


For Norkart, select the branch:

https://github.com/himsve/PROJ_Resources/tree/Norkart


## Installation and building

Follow the instruction at:

https://proj.org/install.html#compilation-and-installation-from-source-code



## Add resources

 - Windows:
  
   Copy NMA resource files to the folder C:\OSGeo4W\share\proj\
  
  File Contents:
  
     * NO | Init file for Norway    
     * EUREF89_NGO48_20081014.cpt | Binary list with point pairs in EUREF89 and NGO. Both in Geographic 3D. 
     * Flater.geojson | Area file               
     * href2008a.tif | GeoTiff grid ETRS89 to NN1954 height 
     * HREF2018B_NN2000_EUREF89.tif | GeoTiff grid ETRS89 to NN2000 height 
     * NNTrans2018B.tif | GeoTiff grid NN2000 height to NN1954
    
 
## Running tests

 -- Under construction
 


 
