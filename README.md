<p align="center">
  <img src="Tutorial/logo.png" width="125" height="125"
</p>
<p align="center">
  <a href="https://github.com/MShawon/Truss-101/releases/latest"><img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/MShawon/Truss-101?color=success"></a>
  <a href="https://github.com/MShawon/Truss-101/releases/latest"><img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/MShawon/Truss-101?color=success"></a>
  <a href="https://github.com/MShawon/Truss-101/"><img alt="GitHub Downloads" src="https://img.shields.io/github/downloads/MShawon/Truss-101/total?label=GitHub%20downloads&color=success"></a>
  <a href="https://sourceforge.net/projects/truss-101/"><img alt="SourceForge Downloads" src="https://img.shields.io/sourceforge/dt/truss-101?label=SourceForge%20downloads&color=success"></a>
  <img alt="OS" src="https://img.shields.io/badge/OS-Windows-success">
</p>
<p align="center">
  <a href="https://github.com/MShawon/Truss-101/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/MShawon/Truss-101?color=important"></a>
  <a href="https://github.com/MShawon/Truss-101/blob/main/DONATE.md"><img alt="Donate" src="https://img.shields.io/badge/Donate-PayPal / Crypto-green.svg"></a>
</p>

<p align='center'><img src='Tutorial/gif.gif' width='90%' height='90%' ></p>

# Truss 101
A desktop application to solve statically determinate and indeterminate 2D truss structures using Matrix Displacement Method (aka Finite Element Method).

## Where to download?
<p align='left'>
  <a href="https://github.com/MShawon/Truss-101/releases/download/1.1.3/Truss.101_win_Setup_v1.1.3.exe">
  <img src="https://img.shields.io/badge/v1.1.3-Download%20Truss%20101-green?logo=github&logoWidth=10&flat&logoColor=black" width="450" height="55">
  </a>
</p>


## Why Truss 101?
* Develop Structures using Nodes and Members
* Unit conversion
* Supports
  * Pinned and Roller support 
  * Stability check
* Multiple loads at the same point
* Individual property for members 
  * Modulus of Elasticity (E)
  * Area (A)
* Nodal displacements
  * Graphs
  * Tabulated
  * Animation
* Member forces and support reactions
  * Force and stress
  * Graphs showing members relative strength
  * Tension, compression value in Tabulated form
* Influence line for a unit load
* Multiple projects
* Beautiful Report 
  * Input-Output data
  * Member Stiffness Matrices
  * Global Stiffness Matrix
  * Force Matrix

# Tutorial 
**1) Analysis of Truss Structures**

[![YouTube video](Tutorial/YouTube_photo.png)](https://www.youtube.com/watch?v=5yi33cXewrU)

**2) Truss Influence Line**

[![YouTube video 2](Tutorial/tutorial2.png)](https://www.youtube.com/watch?v=7H7eLLeZys8)

# TO DO
* Release cross-platform compatible code

# Changelog
## v1.0.0
Initial release

## v1.0.2
Application startup time is improved

## v1.1.0
* Influence line for a unit load is added.
* Automatic table update due to spinbox value change is deprecated. Now the update button must be used.
* Matrices bug in Report is fixed. 
* Application startup and closing time is improved.
* Few other bug fixes.

## v1.1.1
* wrong reaction calculation fixes
* UI improved for 1280*720 resolution
* overall UI improvement
* debug window is added
* Added few other features

## v1.1.2
* up to 1000 nodes, members, supports, loads, and properties are now possible
* setting unit before creating a new file
* stress calculation is now available on the force page
* showing force or stress value directly on the graph instead of a number is available by force checkbox
* better font in debug window and naming convention in code
* report bug fixes

## v1.1.3
* fix large truss report bug

# License
* This software is under GPL v3 license. See more https://github.com/MShawon/Truss-101/blob/main/LICENSE
* Some icons are from icons8.  https://icons8.com
* This program uses Qt Version 5.15.1. Please see http://qt.io/licensing/ for an overview of Qt licensing.
