# C_Module_Generator:
This is a bash script used to generate a well structured C Software Component 


## Getting Started
clone the file to any location on your machine


## Usage:
- ### through the terminal type the next 
```
  $ ./modulegenerator 
  $ enter your name 
  $ enter the name of the module
  $ enter the version of module
```


## Output:
- ### this module will generate 4 files
```
1- MODULENAME_program.c  >>> this file will contain the implementation of the module
2- MODULENAME_interface.h  >>> this file will contain the provided functionalities for the other modules
3- MODULENAME_config.h  >>> this file will contain the configuration parameters of the module to enable and disable the provided features
4- MODULENAME_private.h  >>> this file will contain the private functionalities that will be restricted for the module
```
