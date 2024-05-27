# fly-on-the-ball-recording-app
MATLAB app for recording fly-on-the-ball experiments.

Currently, the app is set up to interact with a NI-DAQ system that triggers and logs two cameras and a light source for optogenetic stimulation. The settings are specified in `config.toml`.   

## Requirements 
The code was tested with MATLAB R2023a. It requires the Data Acquisition Toolbox and the package [matlab-toml](https://www.mathworks.com/matlabcentral/fileexchange/67858-matlab-toml) in the MATLAB path.