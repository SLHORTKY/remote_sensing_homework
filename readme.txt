Before being able to run these notebooks

1 - configure the pyvenv.cfg configuration file left unchanged 
in this state it cannot see the python executable in your system

2 - you need to install the dependencies, i have removed them because ninova only excepts 50 mb for an upload
    1 - activate the virtual environment by running the activate.bat
        open the terminal and type ./Scripts/activate
        then you need to install the following dependencies using pip install

        1- numpy
        2- pillow
        3- rasterio
        4- scipy 

then you can run the files another alternative is to extract the notebook and configure dependencies and source the images
and run it that way. 

Additional info this code runs successfully in Python 3.11.4



