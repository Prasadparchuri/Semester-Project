{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Project title:Assembly of Triacylglycerol (TAG) molecular species using fatty acids\n",
    "**Name**: Prasad Parchuri <br/>\n",
    "**Semester**: Spring 2019 <br/>\n",
    "**Project area**: Lipids"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Objective: \n",
    "To write a Python program to assemble the possible TAG molecular species combinations using neutal loss of fatty acids identified at each TAG mass in the mass spectrometry data."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Outcomes:\n",
    "I want a function to produce a .CSV file with four columns having info about TAG mass, Carbons: Double bonds, fatty acids identified, possible combinations of TAG species.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Rationale:\n",
    "\n",
    "Triacylglycerols are the neutral lipids found in the oils. They have three fatty acids attached to glycerol backbone. The number of fatty acids in seed oils varies from 10 to 15, which results in number of triacylglycerols molecular species (~ 200-300) and is very complex. With growing research interest in undersatnding the triacylglycerol biosynthesis in oilseed crops, many scientist across the globe are using mass spectrometry tool to identify and quantifiy triacylglycerols. Howerver, processing the mass spectrometry data output is very complex and time consuming especially making the possible triacylglycerol molecular species from different fatty acids. Developing a python program to automate the TAG assembly will be an ideal strategy to reduce the complexity and errors in data processing. The main objective of this project is to write a python program to automate the TAG assembly.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Sketch\n",
    "<img src=\"Sketch.jpg\" alt=\"sketch_image\" width=\"500\"/>"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## References:\n",
    "\n",
    "Li, M., Butka, E., & Wang, X. (2014). Comprehensive quantification of triacylglycerols in soybean seeds by electrospray ionization mass spectrometry with multiple neutral loss scans. Scientific reports, 4, 6581.\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.1"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}