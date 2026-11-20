# Active Band-Pass Filter Using LM358 and Arduino Square Wave signal

## Project Overview

This project involves the design, construction, and experimental analysis of an active band-pass filter using the LM358 operational amplifier and an Arduino Uno microcontroller generating Square wave signals.

The filter combines active high-pass and low-pass filter stages to allow signals within a selected frequency range to pass while attenuating frequencies outside that range.

The project explores the practical behavior of active filters, including frequency response, cutoff frequencies, center frequency, bandwidth, and gain.

## Technologies and Components
- LM358 Operational Amplifier
- Arduino Uno
- Resistors and Capacitors
- Breadboard and Connecting Wires
- Arduino-based Signal Generation and Measurement
- Discrete Fourier Transform (DFT)

## Design Specifications

| Parameter              |  Designed Value |
| ---------------------- | --------------: |
| Lower Cutoff Frequency |         1.59 Hz |
| Upper Cutoff Frequency |         15.9 Hz |
| Centre Frequency       |         5.03 Hz |
| High-Pass Stage Gain   | Approximately 2 |
| Low-Pass Stage Gain    | Approximately 2 |

## Project Objectives
- Design and construct an active band-pass filter.
- Investigate the individual high-pass and low-pass stages.
- Experimentally characterize the overall frequency response.
- Measure and analyze the filter's gain at different frequencies.
- Compare theoretical design values with experimental results.
- Explore fundamental frequency extraction from sampled signals using the Discrete Fourier Transform (DFT).

## Experimental Analysis
The filter was tested across a range of frequencies to investigate its response within and outside the intended passband.

The experimental investigation included fundamental amplitude extraction using DFT to analyze the response to square-wave test signals.

## Results

Experimental measurements, frequency-response plots, circuit photographs, and detailed calculations will be documented in this repository.

## Documentation

The complete technical report will be added here.

## Project Status

Physical construction and experimental testing completed. Technical documentation and final presentation are in progress.
