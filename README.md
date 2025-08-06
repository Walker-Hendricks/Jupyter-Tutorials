# Jupyter Tutorials
## Welcome to Jupyter!
---
Welcome to the exciting world of Jupyter! Jupyter is all about inline coding contained within nicely compartmentalized blocks surrounded by fancy Markdown text. It's an awesome environment for anything you may need to do coding-related: homework, project development, or analysis, Jupyter can handle it all! Its format makes it incredibly easy to test and devlop code, as well as present your results to others. And its many kernels developed by an involved community make it compatible with so many different programming langugaes. So what are you waiting for? Get started learnign Jupyter today!

This repo contains a series of notebooks designed to walk you through using Jupyter. You could just look at them through the GitHub page I guess, but I strongly suggest following the instructions below to download Jupyter on your own computer and engage with these notebooks. My goal is to include several practice assignments for you to develop your Jupyter skills as you progress. Some of these features even people who have used Jupyter for years don't know, so get ready for an exciting ride!

*Note: users of these notebooks are expected to have some basic familiarity with Python, but nothing especially advanced.

## Installing Jupyter
---
I will now walk you through the steps you need in order to set up Jupyter on your personal machine. There are two major interfaces for Jupyter: Jupyter Notebook, and Jupyter Lab. I am preferential to Jupyter Lab, but **a.)** there's no difference between the two, and **b.)** I'll explain when we get to the critical junctures where you can install one or the other.

### Windows
For Windows, this is relatively straightforward, and there are several ways to do this. Perhaps the easiest method is installing **Visual Studio Code (VSCode)**; this already has Jupyter built in! If you want the actual Jupyter IDE, you can download [Anaconda](https://www.anaconda.com/download), a package manager, from their website. Once you follow the installation setup steps, Jupyter Notebook and Lab should appear in the navigator when you open Anaconda.

### Apple
I'll have to look into this; I ain't got no idea.

### Unix/Linux
I suppose there's really two ways to do this: with or without a package manager. Personally, I'm preferential to managing my own environments, but you do you fam. I'll include instructions for both.

#### With a Package Manager


#### Without a Package Manager
First, you will need to create a new Python virtual environment. Navigate to the directory where you want to create your environment and run the code below. Give it any name you like; it doesn't have to be Jupyter.
```bash
python -m venv jupyter
```
Next, you'll want to activate your environment before you begin installing Python packages:
```bash
# Replace '~' with the path to your virtual environment and 'jupyter' with the nane of your virtual environment
source ~/jupyter/bin/activate
```
Once you have the virtual environment activated, you should see the environment's name next to your username in the command line, like so:
```bash
(jupyter) [user@mycomputer ~]$
```
Next, you'll need to install the requisite packages. This is where you can choose between Jupyter Notebook or Jupyter Lab.
```bash
# Note that only one of the packages below is required; you can probabaly guess which is which
pip install jupyterlab notebook
```
From there, depending on whether you're running Jupyter Notebook or Jupyter Lab, you will run one of the following (respectively):
```bash
# For Jupyter Lab
(jupyter) [user@mycomputer ~]$ jupyter lab

# For Jupyter Notebook
(jupyter) [user@mycomputer ~] jupyter notebook
```
And that's it! From there the application should start up in your browser.

---

## Setting Up the Repository
---
Once you've followed the installation steps above, you'll want to set up the repository. For those unfamiliar with how to do this, the steps are given here.

