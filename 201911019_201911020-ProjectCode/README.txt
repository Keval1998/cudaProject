	Here Files those are used for the project includes external python libraries those are not part of cuda computing 
and for the purpose of simplicity and arrangements of code such that it demonstrates all the parameters and 
functionality properly we have divided code in different files.

	Different files conains simillar code but for the demonstration of tasks we are creating separate files.And so each 
file can be compiled and run by nvcc.

	As we have used implementation Enviornment Google Colaboratory all the files can be a separate cell of Jupyter 
notebook. To run it on jupyter notebook nvcc plugins must be installed on it.For that installation guidelines are 
there in modules/cudainstall.txt folder.

	maincode directory contains main flow of code with a file that is giving execution flow.
	
	module directory has each file with its description at the beginning of all the files and that is only 
for some analysis purpose.

	Here we have used google colab as a runtime so, all the constraints of google colab may be included in some description
that is just for testing purpose, that doen't mean that code will only work with google colab.But Compute cpability of 
cuda architecture might be needed 3.7 or higher as (i.e. Kepler or MaxWell MicroArch. support).

	All the files are in txt format ,it can directly converted in cuda file by just changing an extension.
	
	input and output images are given as a sample image: 1.jpg,grescale.png,new.png.