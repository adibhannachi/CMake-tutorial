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

## <h2>chap.1 - Why we should use cmake tool 
   
 To compile a project, we generally use a script called Makefile, quite simply this file contains a set of commands to execute in order to compile the project 
 
  
So to compile a project we need to create a Makefile, but writing this file manually is no longer a good idea, it's a bit complicated for large projects. That's why and for a long time, there are tools / system to generate makefiles like autotools, premake, cmake ...


What convinced me to use cmake that it is fast and it perfectly manages the rules of target reconstruction. For example, if I add a command line parameter for link editing, then the link editing will be redone. If I modify a CMakeLists.txt file and I execute make without relaunching CMake, then CMake relaunches itself (Makefiles have a dependency rule on CMakeLists.txt, not stupid!) I can also simply define the directories headers, compilation options and other parameters specific to each project, specifying whether the parameter should be visible from dependent projects or not.

CMake is pretty well done and is very popular in the C ++ community.

CMake is a suite of open source and cross-platform tools designed to build, test and package a portable software.  
CMake is used to control the software compilation process via independent configuration files (independant from the compiler and platform) named CMakefiles.txt, and generates native Makefiles that can be used with the compiler environment of your choice.

So with the same CMake files we can compile a project for different workspace (linux , windows ...) 
 
## <h6> Chap. 1 resumé </h6>  
* To compile a project we use a script named Makefile
* Writing Makefile manually is no longer a good idea , it's recommand to use a build system like autotools, premake, cmake..
* CMake is a suite of open source and cross-platform tools designed to build, test and package a portable software.
* CMake perfectly manages the rules of target : CMake relaunches itself if detect a modify file  


##<h2>chap.2 - Hello-world : the simplest CMake project. 

##<h2>chap.3 - Build Steps & cmake version   

##<h2>chap.4 - Best proctise 
