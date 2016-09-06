# Solidworks Functions

This is a collection of Solidworks marcos to preform task that I have required before.


## What It Does
The main function to be ran is called main. There is a number of things that will be done when this function is ran.

- The layers that have been configured in the config file gets loaded into drawing layers
- All the annotation on all the drawing sheets gets changed to the layer that is stated but the other config file.
- Then any extra layers are removed.

The macro is by far not finished and there is may issue that still need to be fixed. Below is a list of annotation it currently will work with.

## Setup
When setting up the macros there is one module that will need to be edited. This contains the path  to where the config files are stored. The module that is required to be edited is "Config_Docs" and the path that is need to be changed is in the function "configFolderPath" which should still be the very first function. This will need to point to where you store the config files.

In Solidworks its self you will need to set a customs launcher that calls the main method. It may be best to set up your own command tab to hold the marcos. 

## Version

### V0.2
- More default layers added.
- Center Lines get placed on the configured layer.
- New functions added to help with the config file path.

### V0.1
- Dimensions, it will change all types of dimensions to the same layer. There function to distinguee between dimensions is not there yet.

## To conclude
As you may see there is a lot of annotation's missing as of yet but it is a depth rabbit hole trying to find ID numbers for the annotation's
