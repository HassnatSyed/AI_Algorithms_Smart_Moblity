To get the file to run without issues you will have to install somethings first.

Download/Install the Conda from Anaconda website: https://www.anaconda.com/products/individual)

Create an enviornment using:
	conda create --name my_env
Replace my_env with a name of your choice for the environment.

Install OSMnx and create a new conda enviornment ox using commands below
	conda config --prepend channels conda-forge
	conda create -n ox --strict-channel-priority osmnx

Clone the smart_mobility_utilities repository using:
	git clone https://github.com/SmartMobilityAlgorithms/smart_mobility_utilities.git.

Activate the Conda environment by running:
	conda activate /path/to/myenv, where /path/to/myenv is the path to your Conda environment.

Change your current working directory to the cloned repository using:
	cd smart_mobility_utilities.

Install the smart_mobility_utilities package in the environment using:
	python setup.py install.

Verify that the package is installed and can be imported by running:
	python -c "import smart_mobility_utilities".




Activate the environment: Activate the environment using the following command in the enviornment path:
conda activate my_env
Deactivate the environment using: 
conda dactivate 


Make sure to change the interpreter to the one you created(ox enviornment) in VS Code.


Resources to help with installation:
https://github.com/gboeing/osmnx
https://osmnx.readthedocs.io/en/stable/#installation


