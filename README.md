# esdtowim

ESD to WIM is a tool that allows you to convert individual Index files within an ESD to a WIM file so that you can work with it within commands like DISM or apps like NTLite. It is a pretty straightforward tool and is well documented by Microsoft. 

This tool is licensed under GNU GPLv3, you can share, modify, fork and use this tool for commercial use. For more information see the LICENSE file included in this project. 

-- How to use this tool --

1. Download the files in the "Release" section. Read this README file before running this script. If you would like to work out of the same folder, copy install.esd to the same folder as this script, it makes it easier to work with.
2. This script identifies the Index of the ESD file you wish to extract. You should check before continuing. By default it chooses 6 for the value (which can be changed by right-clicking the esdtowim.bat file and clicking on Edit. Change the Index value to be whichever version you choose. 
3. For the sake of convenience, two versions of the script have been provided. One that selects an Index and one that does not. Choose which one works best for you.
4. Allow time for the files to extract. Once finished, you can now use the WIM file.

-- DISCLAIMER --

This tool is being provided AS IS, without warranty or support, any data loss that occurs as a result of this tool is not my responsibility. I will not be held liable for any damages to your system.
