# 759-FinalProject
Fina Project for ME759

In order to successfully compile the code, you need to installed OpenMM Package.
I have installed it in euler. But because of some reason, the complier counldn't
find the -lOpenMM library. So the compiling may not be successful.

But I have tested all codes in my own machine where I installed OpenMM properly.


To compile and run:

#c++code
cd c++_code
make 
./argon

#c++-opemMP_code
cd c++_openMP_code
make 
./argon N
(N is the number of threads)

#python_code
cd python_code
python3 argon.py

All of them would print 2 lines results,
First line is time for DFS cluster searching
Second line is time for Finding neighboring list 
