# R-Studio

Statistics Module 0-1: R Programming and Descriptive Statistics

📋 Project Overview
This repository contains R code implementations for Module 0 (Basic R Operations) and Module 1 (Descriptive Statistics and Data Visualization) from the Statistics course. The project demonstrates fundamental statistical concepts and various data visualization techniques using R programming.

📚 Contents
Module 0: Basic R Operations

Arithmetic Operations: Addition, subtraction, multiplication, division, exponentiation, modulo
Variables and Assignment: Creating and manipulating variables
Vectors: Creating vectors, vector operations, and sequence generation
Basic Statistical Functions: Mean, median, standard deviation, variance, sum, min, max, range


Module 1: Descriptive Statistics and Visualizations

1.3.1 Dot Plots

Base R dot plots using stripchart()
Advanced ggplot2 dot plots with multiple stacking options:

Default stacking
Center stacking (stackdir = "center")
Centerwhole stacking (stackdir = "centerwhole")

Example: Head breadth measurements of Modern Englishmen


1.3.2 Histogram

Multiple histogram variations:

Default bins
Custom bin widths
Histogram with density curve overlay
Different number of bins

Example: Height distribution of students

1.3.3 Stem-and-Leaf Plot

Traditional stem-and-leaf displays using stem()
Multiple examples with different datasets:

Test scores
Temperature readings
Sales data


Various scaling options

1.3.4 Boxplot and Box-Whisker Plot

Single and multiple boxplot comparisons
Horizontal and vertical orientations
Boxplots with notches (confidence intervals)
Complete five-number summary (Min, Q1, Median, Q3, Max)
Interquartile Range (IQR) calculations
Example: Comparison of exam scores across three classes

🚀 Getting Started
Prerequisites

R (version 4.0.0 or higher recommended)
RStudio (optional but recommended)

Required R Packages
The script will automatically install missing packages:

ggplot2 - For advanced data visualizations
gridExtra - For arranging multiple plots



Installation

1. Clone this repository:
git clone https://github.com/yourusername/statistics-module-0-1.git
cd statistics-module-0-1

2. Open R or RStudio

3. Run the main script:

🙏 Acknowledgments

Course materials from Statistics Module 0-1
R Documentation and community resources
ggplot2 package by Hadley Wickham
RStudio Team for the excellent IDE
