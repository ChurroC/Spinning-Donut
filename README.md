First c++ project have done rust for a bit so hopefully not too bad but I've heard it's better to go from c++ to rust than other way around

Also finally understand the linear algebra after last summer and I was planning on doing this afterwards

g++ main.cpp -o my_program - to compile
./my_program - just a executable to run

Gonna try to use CMake from now on though
mkdir build #makes folder
cd build #cd's into it
cmake .. #.. is the project folder and telling cmake on that path
make #then make - basically cmake --build .

This is what I'm going usually do
cmake -B build #this configure the project and starts it
cmake --build build #build the already-configured project
cmake --build build && ./build/spinning_donut #use and to say if build works then run code - GONNA USE THIS

Using this https://cliutils.gitlab.io/modern-cmake/chapters/intro/running.html

Actual explanation for https://www.a1k0n.net/2011/07/20/donut-math.html

But will try to make it myself rn
Lets say we create a circle 