Here's a README file to illustre how to use the MATLAB code in order to read The Dry ECG Data

-"ECG Signal Dataset and MATLAB Code"-

**Description**


This repository contains a dataset of 149 ECG signals and MATLAB code*** to import, process, and visualize these signals***. 


-The ECG signals were sampled at a frequency of 100 Hz using a single lead and recorded using the Orbital 90 dry electrode.

**Dataset Details**


-Number of Signals: 149


-Sampling Frequency: 100 Hz


-Electrode Used: Orbital 90 dry electrode with a 25 mm conductive area diameter


-Electrode Configuration: Measurement of the potential difference between two arms, with the right leg serving as the reference
Objective


**The main objective** of this dataset is to **identify and differentiate** 


-normal-recorded ECG signals from those affected by two common types of interference:


1-50/60 Hz power line interference


2-Electrode contact noise caused by unstable movement


**Signal Processing**

To improve signal quality, the following filters were used:

1-Fourth-Order Butterworth Low-Pass Filter: For smooth frequency response and minimal phase distortion

2-Notch Filter: To eliminate 50 Hz power line noise

These filtering processes significantly enhance the ECG signal quality by reducing noise and interference while preserving important cardiac information.

**Data Format**

The recorded data is stored in CSV format using UART communication via a USB connected to a computer.

**Usage**

1-Clone this repository to your local machine **download it**.

2-Open MATLAB and navigate to **the directory** containing the **downloaded files**.

3-Replace **the file path** in the MATLAB script to point to **the desired CSV file from the dataset**.

4-Run the MATLAB script to import and plot the ECG signal.

**Data link to download**

==> " https://doi.org/10.5281/zenodo.12812762 ""

-For more details please feel free to **contact us** :
*Kharziwisseme@hotmail.com
*kerdjidjoussama@gmail.com
*malikakedir@gmail.com
*nac.meziane@gmail.com
