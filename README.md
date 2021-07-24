# JUCE_CLion

"Juce_CLion" allows plugins to be created in juce library.

# Requirement

JUCE >= 6.0.0 (supports CMake after v6.)
CMake >= 3.15
CLion 

# Features
 
JUCE_CLion allows you to create a project by simply opening CmakeLists.txt in CLion.

https://user-images.githubusercontent.com/63702646/126873953-461b2abf-5ae0-4c85-a7aa-ac3c90a4d0ba.jpg

## Getting Started

### macOS

Please Install CLion.
Also instal Homebrew

``` Script
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
and Install CMake

``` Script
brew install cmake
```

### Windows

Install CLion.
And Install Cmake
https://cmake.org/download/
Select Windows x64 Installer and Install.

### Setup - common

Clone this repository. 

```sh
git clone https://github.com/tomoyanonymous/juce_cmake_vscode_example --recursive
```
or download as zip. 
 
# How to use

You can start the project by opening CmakeLists.txt in CLion.

Also, if you want to load an existing PluginEditor.cpp, etc., replace the file. 

Also, if you want to add files, please add them from CLion.

# Warning.

For now, it is not possible to migrate code created using this project to JUCE.
Most software that can use CMakeLists.txt will support it, but there are some exceptions.
