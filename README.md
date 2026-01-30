![License: MIT](https://img.shields.io/badge/license-MIT-green)

Copyright (c) 2022 Jingjing Wang

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

# RT_MRMT_DSA

This code is developed to account for reactive transport in heterogeneous media with Multirate Mass Transfer(MRMT) that enables to simulate non-linear kinetics.

It was published on Computers & Geosciences in January 2022, with the title "A general and efficient numerical solution of reactive transport with multirate mass transfer", https://doi.org/10.1016/j.cageo.2021.104953 

We referenced the book of Istok, J. (1989) for the FEM implementation. 
**_Groundwater Modeling by the Finite Element Method. In Water Resources Monograph (Vol. 13)._**

Name of code: Reactive Transport with Multirate Mass Transfer 

Developer: Jingjing Wang 

Contact detail: Department of Civil and Environmental Engineering, Universitat Politécnica de Catalunya (UPC), Jordi Girona 1-3, 08034 Barcelona, Spain 

Email: jingjingwangxiang@126.com or jingjing.wang.xiang@gmail.com 

Year first available: October, 2020 

Latest version: updated on March, 2022 

Hardware required: The code is run on a computer with processor Intel® Core™ i5-6500 CPU @ 3.20GHz, 16GB Installed memory (RAM), 64-bit Operating System, x64-based processor. 

Software development platform: Microsoft Visual Studio 2015 

Program language: object-oriented programming FORTRAN 2003 

Compiler: Intel Parallel Studio XE 2017 Cluster Edition for Windows* 

Library: Intel Math Kernel Library (Intel® MKL). 

To solve the system equation (14), we call routine dgbtrf() to compute the LU factorization of the left-hand side matrix of system equation (14), then we call routine dgbtrs() to solve the linear system with the LU-factored square coefficient matrix returned by routine dgbtrf(). 

Details on how to access the open-source code: the source code can be freely downloaded from GitHub on the public repository https://github.com/Jingjingwangxiang/RT_MRMT_DSA
