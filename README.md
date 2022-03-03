# Intro-To-Parallel-Programming - Udacity Course
Course Link : 
https://classroom.udacity.com/courses/cs344 <br/>
This course teaches the parallel programming techniques using CUDA language that uses the power of Nvidia GPUs in general purpose programming.</br>
This repo contains the solutions done by me to the problem sets of the course. The problem sets focus in the Image Processing techniques </br>
### Used Enviornment
1- WIN 10 <br/>
2- MS VS 2019 C++ Package <br/>
3- CUDA toolkit 10.1 <br/>
4- OPEN CV 2 <br/>

## Setting The Enviornment and Running The Codes
1- Setup MS VS 2019 with (Desktop development with C++) package. <br/>
2- Setup CUDA toolkit 10.1. <br/>
3- Download Git bash for windows. <br/> 
4- Install OPEN CV 2 library. <br/>
   best way to do this is to use VCPKG <br/>
   steps: <br/>
   a- open git bash<br/>
   b- run these commands <br/>
     `cd /c/` <br/>
     `git clone https://github.com/microsoft/vcpkg` <br/>
     `cd vcpkg` <br/>
     `bootstrap-vcpkg.ba` <br/>
     `vcpkg integrate install` <br/>
     `vcpkg install opencv2:x64-windows` <br/>
5- Clone the codes <br/> 
6- Open VS 2019 and open the codes <br/>
7- You need to Exclude HW1.cpp file from build <br/>
8- Build The Project <br/>
9- Go to x64/release folder in the project <br/>
10- open git bash or cmd <br/>
11- write the name of the .exe file and the image you want to process <br/>
 `problemSet1.exe viva.jpg`<br/>
12- Check The output image and the reference `HW1_output.png`<br/>
13- HW2-reference is auto generated by the course code to check the correctness of the output. <br/>

## Assignments Done So Far
1- Problem Set 1 - RGB2Gray <br/>
2- Problem Set 2 - Blur <br/>
3- Problem Set 3 - ToneMapping <br/>
4- Problem Set 4 - RedEyeRemoval
