# HW2
## About
We need to creat a triangle signal wave that rise to the peak(3V) in half of the period by using DAC. Also, shown the current condition on uLCD. Then use ADC to
detect it and sample it. Then plot out the ADC data points by Matplotlib.
## Build with
C++, Python

## Inputs
Three buttons as DigitalIn that can select the current frequency of the signal wave and confirm it, which have "up", "down", and "confirm".

# Display
Create a display on uLCD that can show the selection od the frequency.

# Generate waveform 
Use DAC to generate a triangle signal wave of the selected frequency and need to pass the low pass filter.

# Measure
Use picoscope to measure the output signal wave.

# Sample
As the signal is generated, save the data points to a ADC matrix and save it.

# Analysis
Then plot the data points by Matplotlib and we can see the wave is different when the frequency is high.
