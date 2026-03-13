# Digital-Communication-Modulation-and-Software-Defined-Radio-Laboratory

This repository presents a collection of laboratory experiments related to digital communication systems and modern radio signal processing. The project investigates several modulation techniques including ASK, FSK, BPSK, and QPSK, as well as Direct Sequence Spread Spectrum (DSSS) and Software-Defined Radio (SDR) concepts. Experimental setups, waveform observations, and signal analysis are documented to illustrate how digital information is transmitted, processed, and recovered in practical communication systems.

## Table of Contents
- [Part 1: Carrier-Based Amplitude and Frequency Modulation]()
- [Part 2: Binary and Quadrature Phase Modulation]()
- [Part 3: Spread Spectrum Communication Techniques]()
- [Part 4: Software-Defined Radio and Sub-Nyquist Sampling]()

---

## Part 1: Carrier-Based Amplitude and Frequency Modulation
<p align="justify">
This section examines two essential modulation techniques used for transmitting digital data over bandpass channels. The experiments illustrate how binary information alters the amplitude or frequency of a carrier signal to create distinct modulated waveforms. Hardware circuits were built to investigate the generation, detection, and reconstruction of the transmitted signals, while their behavior was observed through waveform measurements and signal analysis.</p>

### 1.0 Amplitude Shift Keying (ASK)
<p align="justify">
Amplitude Shift Keying (ASK) is a fundamental digital modulation technique in which the amplitude of a carrier signal varies based on binary input data. In this method, the presence or absence of the carrier signal indicates different logic states. The experiment showcases the generation of signals through controlled switching of the carrier and explores the demodulation process using envelope detection, followed by signal conditioning to restore the original digital waveform.</p>

### 1.1 Frequency Shift Keying (FSK)
<p align="justify">
Frequency Shift Keying (FSK) transmits digital information by switching the carrier signal between two distinct frequencies while maintaining a constant amplitude. Since the information is encoded in changes in frequency rather than in amplitude levels, FSK offers better resistance to amplitude noise and interference. In experimental implementations, a Voltage Controlled Oscillator (VCO) is utilized to produce the frequency variations, and signal recovery is accomplished through frequency-sensitive detection methods such as zero-crossing analysis.
</p>

### 1.2 Block Diagram
<details>
  <summary>Press the button </summary>

<img width="765" height="658" alt="Image" src="https://github.com/user-attachments/assets/d6965e31-6206-4c16-bf98-9287d4637141" />

<img width="765" height="664" alt="Image" src="https://github.com/user-attachments/assets/ec066c04-326b-4a8f-bd00-7499a62504f6" />

<img width="765" height="656" alt="Image" src="https://github.com/user-attachments/assets/6434ee69-aa2a-4852-9f28-995d2116be9b" />

<img width="765" height="682" alt="Image" src="https://github.com/user-attachments/assets/2c594665-1768-413b-b9ef-8e065ad97607" />

<img width="765" height="677" alt="Image" src="https://github.com/user-attachments/assets/a1b5ccc7-51a6-4b09-95c3-86fffcbe7787" />

<img width="765" height="643" alt="Image" src="https://github.com/user-attachments/assets/f1e9801b-6933-4fbd-8fd1-3d9452d74bb0" />

<img width="765" height="677" alt="Image" src="https://github.com/user-attachments/assets/a7c11d89-be64-409f-8eb5-8de8c4dc6134" />

<img width="765" height="636" alt="Image" src="https://github.com/user-attachments/assets/b0219900-e88d-44d7-87a3-c542b852f315" />
  
</details>

### 1.3 Results

---

## Part 2: Binary and Quadrature Phase Modulation
<p align="justify">
This section investigates phase-based digital modulation methods commonly used in modern communication systems. By altering the phase of a carrier signal instead of its amplitude or frequency, these techniques achieve improved noise immunity and efficient bandwidth utilization. The experiments demonstrate both binary phase modulation and multi-level phase encoding through practical circuit implementations and waveform analysis.
</p>

### 2.0 Binary Phase Shift Keying (BPSK)
<p align="justify">
Binary Phase Shift Keying encodes digital data by switching the phase of a carrier signal between two states separated by 180 degrees. This large phase difference allows reliable signal detection even in environments with low signal-to-noise ratios. In this experiment, the modulation process is implemented using a balanced modulation technique, while the receiver utilizes coherent detection to recover the transmitted binary information.
</p>

### 2.1 Quadrature Phase Shift Keying (QPSK)
<p align="justify">
Quadrature Phase Shift Keying increases transmission efficiency by representing two bits of data within a single symbol. This is achieved by combining two orthogonal carrier components known as the in-phase (I) and quadrature (Q) channels. The experimental setup demonstrates how the incoming bitstream is separated into parallel components, modulated independently, and later recombined at the receiver through synchronized demodulation processes.
</p>

### 2.2 Block Diagram


### 2.3 Results

---

## Part 3: Spread Spectrum Communication Techniques
<p align="justify">
This section focuses on Direct Sequence Spread Spectrum, a technique used to enhance communication reliability and security. The method spreads the transmitted signal over a wide frequency range by combining the message signal with a high-rate pseudo-random sequence. As a result, the transmitted waveform appears noise-like and becomes more resistant to interference and signal interception. The experiment demonstrates both the spreading process at the transmitter and the correlation-based despreading mechanism used to recover the original message.
</p>

### 3.0 Block Diagram


### 3.1 Results

---

## Part 4: Software-Defined Radio and Sub-Nyquist Sampling
<p align="justify">
This section introduces the principles of Software-Defined Radio, where many traditional radio functions are implemented through digital processing rather than fixed analog hardware. The experiment investigates undersampling, also known as sub-Nyquist sampling, where bandpass signals can be sampled at rates lower than twice the highest carrier frequency by intentionally utilizing aliasing. The results illustrate how digital processing techniques can perform frequency translation and signal recovery using flexible software-based architectures.
</p>

### 4.0 Block Diagram


### 4.1 Results



