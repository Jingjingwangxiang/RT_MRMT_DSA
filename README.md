# RT_MRMT_DSA

This code is developed to account for reactive tansport in heterogeneous media with Multirate Mass Transfer(MRMT) that enbles to simulate non-linear kinetics.

It has be submitted to Journal of Computers & Geosciences on October 3 2020, with manuscript Number: CAGEO-D-20-00371, 
titled "A general and efficient numerical solution of reactive transport with multirate mass transfer", now it is under review.

Name of code: Reactive Transport with Multirate Mass Transfer 

Developer: Jingjing Wang 

Contact detail: Department of Civil and Environmental Engineering, Universitat Politécnica de Catalunya (UPC), Jordi Girona 1-3, 08034 Barcelona, Spain 

Email: jingjing.wang.xiang@gmail.com 

Year first available: October, 2020 

Hardware required: The code is run on a computer with processor Intel® Core™ i5-6500 CPU @ 3.20GHz, 16GB Installed memory (RAM), 64-bit Operating System, x64-based processor. 

Software development platform: Microsoft Visual Studio 2015 

Program language: object-oriented programming FORTRAN 2003 

Compiler: Intel Parallel Studio XE 2017 Cluster Edition for Windows* 

Library: Intel Math Kernel Library (Intel® MKL). 

To solve the system equation (14), we call routine dgbtrf() to compute the LU factorization of the left hand side matrix of system equation (14), then we call routine dgbtrs() to solve the linear system with the LU-factored square coefficient matrix returned by routine dgbtrf(). 

Program size: 4.31 MB 

Details on how to access the open-source code: the source code can be freely download from GitHub on the public repository https://github.com/Jingjingwangxiang/RT_MRMT_DSA
