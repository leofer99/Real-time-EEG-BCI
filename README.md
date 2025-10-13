## Overview

This project is a Python-based brain-computer interface to control a robot via EEG signals, covering signal processing, command classification, and Bluetooth navigation with obstacle detection.

## Objectives

- EEG signals were acquired using OpenBCI GUI software.
- Pre-processing of signals, using FIR filtering and data segmentation based on photoresistor signalling.
- Feature extraction using Linear Discrimant Analysis (LDA).
- Classification of the signal into 4 movement commands.
- Implement a Bluetooth-controlled navigation with obstacle detection on a Freenove Dog Robot.

## Repository Structure

- Dog_Walkers_EEG_Analysis.ipynb
  
- _receive_dataNEW.py
  
- send_data.py
  
- Dog_Code.ipynb
