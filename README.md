# ECG-Signal-Processing
This is a basic python program that processes ***raw ECG signals*** to obtain a ***smoothened*** signal, enabling the calculation of heartbeats from the peaks.

An ECG signal is a special type of biological signal which is basically a representation of the electrical activity of the heart.

The code is written in Python and includes various packages such as csv, math, pandas, numpy, matplotlib.pyplot, scipy.fftpack, and scipy.signal.

Also, since the waveform is *denoised* to obtain a *processed* waveform, medical examinations can be conducted on it that can help in the detection of certain types of diseases/disorders .

## Frequency filtered

<img src = freq.PNG width = 400>

## Time filtered

<img src = time.PNG width = 400>

## Heart rate calculation via peaks

<img src = heart-rate.PNG width = 400>

## Number of heart peaks and calculated heart rate

<img src = result.PNG width = 400>
