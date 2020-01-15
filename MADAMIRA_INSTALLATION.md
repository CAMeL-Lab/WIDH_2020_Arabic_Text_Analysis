# MADAMIRA Installation

Below are instructions for downloading MADAMIRA and running it with a provided
sample file.

## Pre-requisites

You will need the following to be able to run MADAMIRA:

- A machine with at least 1GB of available disk space and 2.5GB of available
  RAM.
- Java version 7 or 8. Older and newer versions may not work. If you do not
   have Java, or the right Java version, please download and install it from
   [here](https://java.com/en/download/).

## Download Instructions for Research Non-Commercial Use

Please follow the below instructions to obtain a research copy of MADAMIRA:

1) Go to the [MADAMIRA project page](http://innovation.columbia.edu/technologies/cu14012_arabic-language-disambiguation-for-natural-language-processing-applications).
2) Click on **Express Licensing**.
3) Register (if this is your first time) to get the latest version.
4) **Make sure to use an academic email account (edu or .ac.uk... etc.)**
5) The download instructions will be in the package you will receive in
   one to two days.
6) **Check the spam folder as sometimes the answer from Columbia ends up
   there.**

## Running MADAMIRA

To make sure MADAMIRA is able to run on your machine, please do the following:

1) Unzip the MADAMIRA file that you downloaded.
2) Open a terminal window and navigate to the MADAMIRA unzipped folder by
   running:
   ```
   cd /path/to/MADAMIRA
   ```
3) Call MADAMIRA using the provided sample files by running:
   ```
   java -Xmx2500m -Xms2500m -XX:NewRatio=3 -jar MADAMIRA-release-20170403-2.1.jar -rawinput samples/raw/SampleTextInput.txt -rawoutdir . -rawconfig samples/sampleConfigFile.xml
   ```
4) Check the `/samples/raw/` directory to view the output of MADAMIRA.
