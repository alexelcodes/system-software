# System Software (C Programming)

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue" alt="C"/>
  <img src="https://img.shields.io/badge/Build-Makefile%20%7C%20CMake-slateblue" />
  <img src="https://img.shields.io/badge/Scripting-Python-yellowgreen" alt="Python"/>
  <img src="https://img.shields.io/badge/Data-CSV-orange" alt="CSV"/>
</p>

## Overview

This repository contains a collection of **C-based system software projects** focused on file I/O, data processing, and control-oriented logic, demonstrating practical application of core C concepts such as data structures and memory management.

## Topics Covered

- File I/O and data persistence in C
- Structs, arrays, and memory management
- Data smoothing filters (moving average, low-pass)
- Makefile and CMake-based builds
- Python scripting for post-processing and visualization
- State machines and control logic simulation

The repository includes three main projects:

1. A **Library Manager** application for managing book records with file I/O operations.
2. A **Moving Average Filter** to process temperature data from CSV files using smoothing techniques.
3. A **Traffic Light Controller** that simulates traffic light operations with various states and pedestrian request handling.

## Table of Contents

- [Project 1: Library Manager](#project-1-library-manager)
- [Project 2: Moving Average and Low-Pass Filtering](#project-2-moving-average-and-low-pass-filtering)
- [Project 3: Traffic Light Controller](#project-3-traffic-light-controller)
- [Building the Projects](#building-the-projects)

## Project 1: Library Manager

### Project Overview

This project implements a **Library Manager** in C that manages a collection of books, providing basic CRUD functionality with persistent storage via file I/O.

### Key Features:

- Add, delete, loan, and search for books
- Save and load library data from a file
- Built using a **Makefile**

**[Detailed README](01-library-manager/README.md)**

---

## Project 2: Moving Average and Low-Pass Filtering

### Project Overview

This project applies **moving average** and **low-pass** filters to temperature data stored in CSV files, smoothing noisy measurements and exporting the results for further analysis.

### Key Features:

- Moving average and low-pass filtering
- CSV-based input and output
- Python scripts for plotting and result comparison

**[Detailed README](02-moving-average-filter/README.md)**

---

## Project 3: Traffic Light Controller

### Project Overview

This project implements a traffic light simulation system that manages traffic light states **(RED, YELLOW, GREEN)** as well as special periods such as **BLINKING YELLOW** and **OFF** during night operation. The system also handles pedestrian requests by switching to **GREEN** for crossings.

### Key Features:

- Simulates **traffic light state transitions**
- Handles **pedestrian requests** (button press)
- Supports **night period** and **blinking yellow transitions**

**[Detailed README](03-traffic-light-controller/README.md)**

---

## Building the Projects

Build and usage instructions are provided in each project’s dedicated `README.md`.
