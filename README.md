# Input Tutorials for RV Orbit Fitting

This repository contains **seven example input files** for demonstrating how to fit combined visual & radial-velocity (RV) orbits of binary stars using a Python orbital-fitting tool. The files and instructions here assume you have:

- **Anaconda** (Python 3.9 or higher) installed on Windows.  
- **Git** installed (so you can clone/pull this repository).  
- A working installation of the RV‐orbit fitting Streamlit Visualisation script (`streamlit_app.py`) which expects input files in the formats shown below.

## Table of Contents

1. [Overview of Input Files](#overview-of-input-files)  
2. [Directory Structure](#directory-structure)  
3. [Format of Each `.csv` File](#format-of-each-csv-file)   
4. [Detailed Explanation of Each Example](#detailed-explanation-of-each-example)    

---

## 1. Overview of Input Files

This folder contains seven sample input csv files, each representing a slightly different scenario:

- **`example1_GL765_Test1.inp`**  
  A.  

- **`example2_HD_New.inp`**  
  A.  

- **`example3_HIP12780 _FIN379_Parallax1.inp`**  
  A.  

- **`example4_HIP51360.inp`**  
  A.  

- **`example5_HIP53206.inp`**  
  A.  

- **`example6_HIP72217_parallax1.inp`**  
  A. 

- **`example7_HIP72217_parallax2.inp`**  
  A. 

Each file can be loaded into the fitting script (streamlit_app.py) to see how the code handles different tutorial data regimes or users can also upload csv files to run and visualize as well.

---

## 2. Directory Structure

In this repository, you should see:

---

## 3. Format of Each `.csv` File
---
########################################
#Object info
Object:,Mlr 224 = GL 765.2
R.A.:,19.404
Dec:,76.1812
Parallax:,54.27

#Orbital elements
P,11.769
T,1993.513
e,0.224
a,0.225
W,106.34
w,89.4
i,82.56
K1,7.54
K2,6.96
V0,-3.91

# RV1 Measurements
45533.4644,-10.69,0.51,Va,COR
45543.4416,-11.25,0.51,Va,COR
45584.3576,-11.11,0.52,Va,COR
45620.2818,-11.08,0.46,Va,COR
45868.5758,-12.14,0.5,Va,COR
45969.2988,-11.1,0.5,Va,COR
45976.2986,-10.58,0.46,Va,COR
......

# RV2 Measurements
45533.4644,2.81,0.66,Vb,COR
45543.4416,2.9,0.66,Vb,COR
45584.3576,3.15,0.67,Vb,COR
45620.2818,2.89,0.55,Vb,COR
45868.5758,2.16,0.63,Vb,COR
45969.2988,2.14,0.62,Vb,COR
45976.2986,3.37,0.55,Vb,COR
.....

# Visual Measurements
1971.6,275.6,0.21,0.04,I1,M1
1971.57,275.6,0.17,0.04,I1,M1
1971.67,280,0.21,0.04,I1,M1
1972.65,288.6,0.2,0.04,I1,M3
....

########################################

## 4. Detailed Explanation of Each Example

---
