# System Software (C Programming)

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue" alt="C"/>
  <img src="https://img.shields.io/badge/Build-Makefile%20%7C%20CMake-slateblue" />
  <img src="https://img.shields.io/badge/Scripting-Python-yellowgreen" alt="Python"/>
  <img src="https://img.shields.io/badge/Data-CSV-orange" alt="CSV"/>
</p>

## Overview

This repository contains a set of **C-based system software projects** focused on low-level programming, file I/O, data processing, and control logic.

The goal is to practice practical C development: working with memory, structs, files, simple algorithms, and small standalone tools.

## Topics Covered

- File I/O and persistent storage
- Structs, arrays, and memory management
- Data filtering and signal smoothing
- State machines and control logic
- Makefile and CMake build systems
- Python scripts for visualization

## Projects

### [Library Manager](01-library-manager/)

Command-line **library management system written in C** that demonstrates structured data handling and persistent storage using file I/O.  
The application manages a small database of books and supports basic CRUD-style operations.

**Features**

- Add, delete, search, and loan books
- Store records using structs
- Persistent save/load from file
- Built with Makefile

---

### [Moving Average and Low-Pass Filtering](02-moving-average-filter/)

A **data processing tool for smoothing temperature measurements** using moving average and low-pass filters.  
The project focuses on CSV parsing, numerical processing, and implementing basic signal filtering algorithms in pure C.

**Features**

- Read and write CSV datasets
- Moving average and low-pass filtering algorithms
- Noise reduction for sensor data
- Python scripts for plotting and comparison

---

### [Traffic Light Controller](03-traffic-light-controller/)

A **state-machine–based traffic light simulation** that models real intersection behavior.  
The system manages timed transitions, pedestrian requests, and night modes while demonstrating control logic and finite state machines in C.

**Features**

- Finite state machine implementation
- Timed RED / YELLOW / GREEN transitions
- Pedestrian button handling
- Night mode with blinking yellow
- Built with CMake/Makefile
