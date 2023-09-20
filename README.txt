====AI-based T1D simulator====

====System Requirements====
Windows 10
Python 3.8.8
Tensorflow 2.13.0
Keras 2.13.1

====Installation Guide====
The folder contains the executable file named "simulation_environment"
Double clicking on this file will open the simulation environment.
It doesn't need to explicitly installed.

====Demo====
The simulation environment contains a sample of insulin and carbohydrates data for one randomly selected patient of the Ohio T1DM cohort.
The user needs to specify the type of simulation (open-loop/closed-loop) by typing either "open" or "closed" in the simulation environment.
The simulation environment also includes a randomly selected pretrained model.
One execution of the simulation environment will generate 24 hours of blood glucose data.
The expected time to run a simulation that would generate 24 hours of blood glucose data is 40 seconds.

====Instruction for Use====
If the user wants to simulate blood glucose data with inputs of their own choice, they can introduce the inputs in the form of excel files in the "patient_data" folder.
The name of the excel files should be the same as those of existing files.
The inputs include plasma insulin approximation and carbohydrates rate of appearance.
For the closed-loop simulation, meal labels should be included for the controller to compute boluses.



