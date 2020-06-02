# <h1> CMake tutorial
# <h2> Introduction

This an easy intoduction about cmake tool , i will talk about 
* <h6> Introduction
* <h6>chap.1 - Why we should use cmake tool 
* <h6>chap.2 - Hello-world : the simplest CMake project. 
* <h6>chap.3 - Build steps & cmake version   
* <h6>chap.4 - Best proctise 
* <h6> Conclusion 

# <h2> Introduction
Cmake is a tool used to generate Makefiles , a script used to automate project compilation.  
In this tutorial we will interest in compiling C & C++ (legacy & modern) project.  
The importance of this tool the large and the easy use (compare to autotools) encourage me to write this tutorial.
This tutorial contains some feedbucks and best practises in how we should use cmake and how to write an awsame CmakeLists.txt files.  
We will start by the simplest project and step by step , we will add modules to our project and enhance our cmake files

![GitHub Logo](/images/CMake-Logo-and-Text.png)

written by Adib HANNACHI , adib.hannachi.eng@gmail.com @paris-France

* <h2>chap.1 - Why we should use cmake tool 
   
   
 CMake is a suite of open source and cross-platform tools designed to build, test and package software.  
CMake is used to control the software compilation process via independent configuration files (independant from the compiler and platform), and generates native makefiles or projects that can be used with the compiler environment of your choice.

So with the same CMake files we can compile a project to diffrent platfome (linux , windows ...)
To compile a project, we generally use a script called Makefile, quite simply this file contains a set of commands to execute in order to compile the project  
 
 
So to compile a project we need to create a Makefile, but writing this file manually is no longer a good idea, it's a bit complicated for large projects. That's why and for a long time, there are tools / system to generate makefiles like for example: Autotools, Premake, CMake .

* <h2>chap.2 - Hello-world : the simplest CMake project. 
* <h2>chap.3 - Build Steps & cmake version   
* <h2>chap.4 - Best proctise 
