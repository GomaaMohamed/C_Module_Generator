# C_Module_Generator
  Bash Script generates a well structured C Software Component 


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
1- MODULENAME_program.c    >>> this file will contain the implementation of the module
2- MODULENAME_interface.h  >>> this file will contain the provided functionalities
                               for the other modules
3- MODULENAME_config.h     >>> this file will contain the configuration parameters of
                               the module to enable and disable the provided features
4- MODULENAME_private.h    >>> this file will contain the private functionalities that
                               will be restricted for the module
```

## License
```
This library is released under the GNU GPL License ↗. Feel free to use it in your own projects, 
modify it, and distribute it as needed. If you find any issues or have suggestions for
improvement, please open an issue or submit a pull request.
```

