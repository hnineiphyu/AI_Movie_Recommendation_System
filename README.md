1. Run "24249917_PHYU_AI_Project.ipynb" in google colab. 
2. No dataset is required as all dataset have been uploaded to googledrive and accessible by everyone. 
3. Notes: Need to run below pip installed and install numpy if the python version is not compatible (before importing surprise library). 
   !pip install scikit-surprise
   !pip uninstall -y numpy
   !pip install numpy==1.26.4 # if python version is not compatible 

P.S. Please ignore below error as numpy 1.26.4 is successfully installed and subsequence code sections will be running successfully. 

Installing collected packages: numpy
----- ignore below error 
" ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
jaxlib 0.7.2 requires numpy>=2.0, but you have numpy 1.26.4 which is incompatible.
opencv-python-headless 4.12.0.88 requires numpy<2.3.0,>=2; python_version >= "3.9", but you have numpy 1.26.4 which is incompatible.
jax 0.7.2 requires numpy>=2.0, but you have numpy 1.26.4 which is incompatible.
pytensor 2.35.1 requires numpy>=2.0, but you have numpy 1.26.4 which is incompatible.
opencv-python 4.12.0.88 requires numpy<2.3.0,>=2; python_version >= "3.9", but you have numpy 1.26.4 which is incompatible.
opencv-contrib-python 4.12.0.88 requires numpy<2.3.0,>=2; python_version >= "3.9", but you have numpy 1.26.4 which is incompatible.
thinc 8.3.6 requires numpy<3.0.0,>=2.0.0, but you have numpy 1.26.4 which is incompatible." 
-----------------------

Successfully installed numpy-1.26.4


However, all the codes section will be successfully run after successfully installed compatible numpy version. 
