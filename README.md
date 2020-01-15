# Winter Institute in Digital Humanities 2020 - Text Analysis of Arabic

This repository contains material for the *Text Analysis of Arabic* course
taught at the NYU Abu Dhabi Winter Institute in Digital Humanities 2020.
Below are instructions on how to setup the working environment used in this
course. We will be using [Jupyter Lab](https://jupyter.org/) as our programming
environment as well as the
[CAMeL Tools](https://github.com/CAMeL-Lab/CAMeL_Tools) Python library and the
[MADAMIRA](http://innovation.columbia.edu/technologies/cu14012_arabic-language-disambiguation-for-natural-language-processing-applications)
command-line tools.

## Installing Pre-requisites

We assume Python 3.5+ and Java 8 are installed on your machine.

To install *Jupyter Lab* and *CAMeL Tools*, run the following command in a
terminal window:

```
pip install jupyterlab camel-tools
```

To install MADAMIRA, please follow the
[MADAMIRA installation instructions](MADAMIRA_INSTALLATION.md).

## Running Jupyter Lab

Download the zip archive for this repository from *GitHub* and unzip it, or,
clone the repository using *git* by running in a terminal window:

```
git clone https://github.com/CAMeL-Lab/WIDH_2020_Arabic_Text_Analysis.git
```

Then, navigate to the project directory:

```
cd /path/to/WIDH_2020_Arabic_Text_Analysis
```

Finally, start Jupyter Lab by running:

```
jupyter lab
```
