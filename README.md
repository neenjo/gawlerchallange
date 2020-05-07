EXPLORESA #Gawler Challenge 
==============================

Trainings, materials and template implementations for the ExploreSA Gawler Challenge.

Team "RocketScience" is proud to present this solution as part of the student community.

Please let us know if you liked our simple tutorial on our data cleaning process by voting for us ;) as Team No. 1.

As we joined around 4 days before the preprocessed data submission, we are still trying to analyse more on data. We will keep updating our changes here.

# Environment Setup

* Please install Python 3.6.8 as appropriate for your local OS.
    * OSX: https://www.chrisjmendez.com/2017/08/03/installing-multiple-versions-of-python-on-your-mac-using-homebrew/

* Ensure to use virtualenv to not pollute your local OS  
* Open a terminal, cd to your repository folder  

Ensure you are using the correct Python version 

    $ python --version  
    Python 3.6.8    

Create a new virtualenv. Ensure to point the python arg to the right interpreter. In my case I can rely on the fact, that I overrid my standard Python (in my current shell).  

    $ virtualenv --python=python VENV  
    Running virtualenv with interpreter /Users/foo/.pyenv/shims/python  
    Already using interpreter /Users/foo/.pyenv/versions/3.6.8/bin/python  
    Using base prefix '/Users/foo/.pyenv/versions/3.6.8'  
    New python executable in /Users/foo/src/gdsc/VENV/bin/python  
    Installing setuptools, pip, wheel...  
    done.  

Activate the virtualenv and install jupyter, folium and so forth locally into the environment.

    $ source VENV/bin/activate  

To start the jupyter notebook server

    $ jupyter notebook

Your browser will automatically be opened and redirected to the locally running notebook web gui from where you can open the notebooks.


Project Organization
--------
 
    ├── README.md                          <- The top-level README for developers using this project.
                         
    ├── Notebooks                          <- Tutorial notebooks   
    │   ├── MineralDepositsPreprocessing   <- MineralDeposit Data Engineering Jupyter Notebook
    │   ├── data     
    |   |   └── SARIG_Data_Package         <- Data from SARIG Package
    │   └── Figures                        <- Analysis Figures
    |        ├── Gold Bar graph            <- Gold on SA Map
    |        └── map gold  
    ├── cleaned_datasets                   <- 10 different CSVs for top 10 elements
    │   ├── Calcrete   
    │   ├── Clay 
    │   ├── Copper    
    │   ├── Gold  
    │   ├── Limestone  
    │   ├── Sand      
    │   ├── SandStone  
    │   ├── Silver  
    │   ├── Uranium  
    │   └── Lead


--------
