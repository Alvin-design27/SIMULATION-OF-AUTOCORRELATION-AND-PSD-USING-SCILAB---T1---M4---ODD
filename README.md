# SIMULATION-OF-AUTOCORRELATION-AND-PSD-USING-SCILAB---T1---M4---ODD
# SIMULATION OF AUTOCORRELATION AND PSD USING SCILAB

## AIM

Write a program for Autocorrelation and PSD of signals in SCILAB and verify Wiener-Khinchin relation.

## EQUIPMENTS NEEDED

- Computer with i3 Processor
- SCI LAB

## THEORY

The Wiener-Khinchin theorem states that the power spectral density of a wide sense stationary random process is the Fourier transform of the corresponding autocorrelation function.

### Power Spectral Density (PSD)

$$
S_{XX}(\omega)=FT[R_{XX}(\tau)]
=\int_{-\infty}^{\infty}R_{XX}(\tau)e^{-j\omega\tau}d\tau
$$

### Autocorrelation Function (ACF)

$$
R_{XX}(\tau)=IFT[S_{XX}(\omega)]
=\frac{1}{2\pi}\int_{-\infty}^{\infty}S_{XX}(\omega)e^{j\omega\tau}d\omega
$$

## ALGORITHM

### 1. Load or Define the Signal:

Input your time-domain signal.

### 2. Compute Autocorrelation:

Calculate the autocorrelation function of the signal.

### 3. Compute Power Spectral Density (PSD):

Estimate the PSD of the signal, either directly using a method like Welch’s periodogram or by using the Fourier transform of the autocorrelation.

### 4. Plot Results:

Visualize the autocorrelation function and PSD.

## PROCEDURE

- Refer Algorithms and write code for the experiment.
- Open SCILAB in System.
- Type your code in New Editor.
- Save the file.
- Execute the code.
- If any Error, correct it in code and execute again.
- Verify the generated waveform using Tabulation and Model Waveform.

# CODE
<img width="1077" height="905" alt="image" src="https://github.com/user-attachments/assets/d8beebc6-cd65-48f9-ac6a-719b4f3aba80" />
<img width="870" height="1280" alt="image" src="https://github.com/user-attachments/assets/f1ab0eb2-58e4-4453-848d-f0a218b05321" />
<img width="1080" height="491" alt="image" src="https://github.com/user-attachments/assets/4bd576b2-a3f6-4751-bfa5-435d06482fdd" />

# OUTPUT
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/9be0bb01-7e44-4c3d-a4dc-975516c5115f" />

# MARK SPLIT-UP
<img width="1080" height="534" alt="image" src="https://github.com/user-attachments/assets/8a36373e-730b-4b95-a786-dc95e8f6a604" />


# RESULT
<img width="1080" height="542" alt="image" src="https://github.com/user-attachments/assets/45fbd309-0bcc-412a-a803-a9840a764ade" />


