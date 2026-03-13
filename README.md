<div id="top"></div>

# Digital-Communication-Modulation-and-Software-Defined-Radio-Laboratory

This repository presents a collection of laboratory experiments related to digital communication systems and modern radio signal processing. The project investigates several modulation techniques including ASK, FSK, BPSK, and QPSK, as well as Direct Sequence Spread Spectrum (DSSS) and Software-Defined Radio (SDR) concepts. Experimental setups, waveform observations, and signal analysis are documented to illustrate how digital information is transmitted, processed, and recovered in practical communication systems.

## Table of Contents
- [Part 1: Carrier-Based Amplitude and Frequency Modulation](https://github.com/Justine2323/Digital-Communication-Modulation-and-Software-Defined-Radio-Laboratory?tab=readme-ov-file#part-1-carrier-based-amplitude-and-frequency-modulation)
- [Part 2: Binary and Quadrature Phase Modulation](https://github.com/Justine2323/Digital-Communication-Modulation-and-Software-Defined-Radio-Laboratory?tab=readme-ov-file#part-2-binary-and-quadrature-phase-modulation)
- [Part 3: Spread Spectrum Communication Techniques](https://github.com/Justine2323/Digital-Communication-Modulation-and-Software-Defined-Radio-Laboratory?tab=readme-ov-file#part-3-spread-spectrum-communication-techniques)
- [Part 4: Software-Defined Radio and Sub-Nyquist Sampling](https://github.com/Justine2323/Digital-Communication-Modulation-and-Software-Defined-Radio-Laboratory?tab=readme-ov-file#part-4-software-defined-radio-and-sub-nyquist-sampling)

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

<img width="765" height="680" alt="Image" src="https://github.com/user-attachments/assets/3c41a853-43f8-4897-a45f-1ceea9bd3ae3" />

<img width="765" height="676" alt="Image" src="https://github.com/user-attachments/assets/654c3bc9-bb18-4bdd-b9e6-32d69fe866de" />

<img width="765" height="674" alt="Image" src="https://github.com/user-attachments/assets/1de9c20b-f4e0-4833-a1f0-83922b6e6e8e" />

<img width="765" height="620" alt="Image" src="https://github.com/user-attachments/assets/249c6f70-169c-4ac3-9af6-d469f37f3ef0" />

<img width="765" height="721" alt="Image" src="https://github.com/user-attachments/assets/5754c21a-9679-4755-a80a-47a1a883127f" />

<img width="765" height="665" alt="Image" src="https://github.com/user-attachments/assets/2ed119aa-8611-42e1-8b66-a5b4085d6811" />


  
</details>

### 1.3 Results
<details>
  <summary>Press the button </summary>

<img width="765" height="406" alt="Image" src="https://github.com/user-attachments/assets/db107c78-7fbd-4649-ae38-55d7e7a22e1b" />

<img width="765" height="416" alt="Image" src="https://github.com/user-attachments/assets/edbc81d1-edaa-468e-b82a-659732188deb" />

<img width="765" height="765" alt="Image" src="https://github.com/user-attachments/assets/094e8fec-0029-4b21-bc4e-62107fe2d920" />

<img width="765" height="405" alt="Image" src="https://github.com/user-attachments/assets/76eaa166-60f5-4090-994b-0ac0a223204c" />

<img width="765" height="529" alt="Image" src="https://github.com/user-attachments/assets/b4589438-b3df-401f-9254-d79c0aaf52ae" />

<img width="765" height="514" alt="Image" src="https://github.com/user-attachments/assets/138102ed-82e2-4050-9f70-93db1e8fa542" />

<img width="765" height="528" alt="Image" src="https://github.com/user-attachments/assets/9946cfb2-e0a5-41ba-b734-9fe767bea67d" />

<img width="765" height="524" alt="Image" src="https://github.com/user-attachments/assets/07530c28-c0b4-4db7-9395-ef4b1c00878a" />

<img width="765" height="533" alt="Image" src="https://github.com/user-attachments/assets/5dd4f873-5fe8-48be-b96e-b105094762f4" />

</details>

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
<details>
  <summary>Press the button </summary>

<img width="765" height="657" alt="Image" src="https://github.com/user-attachments/assets/8f074c9c-9ddc-42dd-ab03-65dfa3fcf8f6" />

<img width="765" height="632" alt="Image" src="https://github.com/user-attachments/assets/74f932e6-6c34-440e-9214-5c7c286c9c34" />

<img width="765" height="673" alt="Image" src="https://github.com/user-attachments/assets/c3f2dec8-1562-4cd0-be09-32efeb4b916a" />

<img width="765" height="663" alt="Image" src="https://github.com/user-attachments/assets/55551b28-a705-435b-8960-48ee09ff95d3" />

<img width="765" height="650" alt="Image" src="https://github.com/user-attachments/assets/d7326eae-283c-44e8-9a79-ea9e666a0015" />

<img width="765" height="658" alt="Image" src="https://github.com/user-attachments/assets/dce98aa3-587f-49de-acee-983910a301d9" />

<img width="765" height="667" alt="Image" src="https://github.com/user-attachments/assets/e6062271-232f-439b-b520-9b0be42f9d99" />

<img width="765" height="679" alt="Image" src="https://github.com/user-attachments/assets/ab237e8f-a14d-4cab-b60b-f766b1626518" />

<img width="765" height="680" alt="Image" src="https://github.com/user-attachments/assets/861e74d4-84e1-427a-bbac-2276cbc0d349" />

<img width="765" height="655" alt="Image" src="https://github.com/user-attachments/assets/1667b578-bb09-437b-abe3-7222b3165588" />

<img width="765" height="737" alt="Image" src="https://github.com/user-attachments/assets/413458c5-c075-4e20-b886-94bc817174c4" />

<img width="765" height="680" alt="Image" src="https://github.com/user-attachments/assets/70bbe148-3e73-49b6-9995-3d0d33ff1df6" />

<img width="765" height="669" alt="Image" src="https://github.com/user-attachments/assets/043abb69-0699-4cfb-a896-a272a4089a9c" />

<img width="765" height="671" alt="Image" src="https://github.com/user-attachments/assets/500f35de-3cdd-4d54-8c5f-2f50880b8d51" />

<img width="765" height="680" alt="Image" src="https://github.com/user-attachments/assets/9c9b8b94-5707-46f2-b941-404f9302a303" />

<img width="765" height="700" alt="Image" src="https://github.com/user-attachments/assets/3ed82aa7-db6f-4b56-8eb9-1ff9e4181b44" />

<img width="765" height="667" alt="Image" src="https://github.com/user-attachments/assets/2df2b1b1-4c68-4d40-bc19-f3a859e63147" />

<img width="765" height="665" alt="Image" src="https://github.com/user-attachments/assets/7e22fa42-54ff-46d5-bd26-c31220c242c1" />

<img width="765" height="670" alt="Image" src="https://github.com/user-attachments/assets/747300f3-a329-4593-b4a9-bda8e5568734" />

</details>

### 2.3 Results
<details>
  <summary>Press the button </summary>

  <img width="765" height="419" alt="Image" src="https://github.com/user-attachments/assets/75cfa9f0-aa3e-4136-9ff6-7fffd82907f7" />

<img width="765" height="401" alt="Image" src="https://github.com/user-attachments/assets/cf294339-5e8e-4141-9ec4-4b871b320ef6" />

<img width="765" height="400" alt="Image" src="https://github.com/user-attachments/assets/d7a3ac1a-8567-4181-bfb1-fb274e926a4d" />

<img width="765" height="262" alt="Image" src="https://github.com/user-attachments/assets/ffee93a9-dbf0-4c08-92a0-cbd503177a0a" />

<img width="765" height="257" alt="Image" src="https://github.com/user-attachments/assets/63cb4a78-a92e-4de3-9cb5-f1edcaece7e6" />

<img width="765" height="259" alt="Image" src="https://github.com/user-attachments/assets/13ad7676-150d-46f4-85a2-bb3e5af0c4a2" />

<img width="765" height="243" alt="Image" src="https://github.com/user-attachments/assets/13d6fbf5-59ae-4720-b8be-9352f0918b6c" />

<img width="765" height="240" alt="Image" src="https://github.com/user-attachments/assets/05eb0b8e-3f3e-45b4-bc29-1d209a037fa3" />

<img width="765" height="248" alt="Image" src="https://github.com/user-attachments/assets/3b6cb315-0ec3-480e-bff5-5efd1d29e0ec" />

<img width="765" height="252" alt="Image" src="https://github.com/user-attachments/assets/e3e363fd-ffbf-4812-a50c-4e212e681d0f" />

<img width="765" height="273" alt="Image" src="https://github.com/user-attachments/assets/36f2957e-5806-4f22-a599-4a39ecb4be67" />

<img width="765" height="244" alt="Image" src="https://github.com/user-attachments/assets/0dc7319f-f7df-4040-8e98-1f028cea7eb3" />

<img width="765" height="238" alt="Image" src="https://github.com/user-attachments/assets/0921ad4b-6d0d-4c79-8763-372fd88eb38b" />

<img width="765" height="259" alt="Image" src="https://github.com/user-attachments/assets/2eeb3dc5-89b2-406d-adf5-edc106e3fc6f" />

  </details>

## Part 3: Spread Spectrum Communication Techniques
<p align="justify">
This section focuses on Direct Sequence Spread Spectrum, a technique used to enhance communication reliability and security. The method spreads the transmitted signal over a wide frequency range by combining the message signal with a high-rate pseudo-random sequence. As a result, the transmitted waveform appears noise-like and becomes more resistant to interference and signal interception. The experiment demonstrates both the spreading process at the transmitter and the correlation-based despreading mechanism used to recover the original message.
</p>

### 3.0 Block Diagram
<details>
  <summary>Press the button </summary>

<img width="765" height="646" alt="Image" src="https://github.com/user-attachments/assets/135e6973-dcf8-4693-8bf4-60b0e726a3c2" />

<img width="765" height="659" alt="Image" src="https://github.com/user-attachments/assets/d2654620-a629-4d25-8b2d-4a2889b818c5" />

<img width="765" height="673" alt="Image" src="https://github.com/user-attachments/assets/11059087-e2cd-455f-bbdf-1fe50b43e883" />

<img width="765" height="677" alt="Image" src="https://github.com/user-attachments/assets/a3962154-025d-4678-816f-6a0bc0019d54" />

<img width="765" height="696" alt="Image" src="https://github.com/user-attachments/assets/4819af63-5cc1-4804-b292-5b1ef58d94e7" />

<img width="765" height="647" alt="Image" src="https://github.com/user-attachments/assets/5cf9e1e3-4059-42bc-a267-fd4a2d163e88" />

<img width="765" height="686" alt="Image" src="https://github.com/user-attachments/assets/8c23201f-4e8a-4fcd-a389-b49e323ef573" />

<img width="765" height="660" alt="Image" src="https://github.com/user-attachments/assets/dda3beb5-40f9-415b-99d1-557c4d6354d3" />

  </details>

### 3.1 Results

<details>
  <summary>Press the button </summary>

  <img width="765" height="348" alt="Image" src="https://github.com/user-attachments/assets/682e8cc3-c153-4f4e-8bcc-c5752fb7ec98" />

<img width="765" height="337" alt="Image" src="https://github.com/user-attachments/assets/3744baa5-5299-421a-8de0-7316243b59ca" />

<img width="765" height="420" alt="Image" src="https://github.com/user-attachments/assets/2d81cf74-1f2e-480d-8f63-af2748cf49ae" />

<img width="765" height="339" alt="Image" src="https://github.com/user-attachments/assets/6fbd9bcc-69f7-4c73-abca-ac9a6665fdeb" />

<img width="765" height="282" alt="Image" src="https://github.com/user-attachments/assets/29151e57-a23f-4dc2-83bf-626c9ac6aa5c" />

<img width="765" height="347" alt="Image" src="https://github.com/user-attachments/assets/6efe2026-b4b4-43ec-afa0-8693a68673eb" />

  </details>


## Part 4: Software-Defined Radio and Sub-Nyquist Sampling
<p align="justify">
This section introduces the principles of Software-Defined Radio, where many traditional radio functions are implemented through digital processing rather than fixed analog hardware. The experiment investigates undersampling, also known as sub-Nyquist sampling, where bandpass signals can be sampled at rates lower than twice the highest carrier frequency by intentionally utilizing aliasing. The results illustrate how digital processing techniques can perform frequency translation and signal recovery using flexible software-based architectures.
</p>

### 4.0 Block Diagram

<details>
  <summary>Press the button </summary>

<img width="765" height="649" alt="Image" src="https://github.com/user-attachments/assets/89dfb333-9a3c-4af5-9996-927c72725be1" />

<img width="765" height="644" alt="Image" src="https://github.com/user-attachments/assets/d01cc575-2f39-4bf1-94aa-7cd1d5c9289e" />

<img width="765" height="670" alt="Image" src="https://github.com/user-attachments/assets/549d7b9c-d448-4c03-bd27-952862d3f00f" />

<img width="765" height="665" alt="Image" src="https://github.com/user-attachments/assets/4f5e46db-78dd-4534-8ab8-03c9a3004770" />

<img width="765" height="676" alt="Image" src="https://github.com/user-attachments/assets/346d00c1-35d1-463c-8c4a-37509235da90" />

<img width="765" height="676" alt="Image" src="https://github.com/user-attachments/assets/352042cf-44bc-48cf-a5fa-94f756ec75e9" />

<img width="765" height="645" alt="Image" src="https://github.com/user-attachments/assets/b9ef00d0-02b4-44de-b020-179b94f7fe1b" />

  </details>


### 4.1 Results

<details>
  <summary>Press the button </summary>

<img width="765" height="515" alt="Image" src="https://github.com/user-attachments/assets/d7bcad4e-2fef-475f-b731-2552adc3bdb0" />

<img width="765" height="557" alt="Image" src="https://github.com/user-attachments/assets/1806206d-c1d0-4976-8b9d-88d60c4d1479" />

<img width="765" height="535" alt="Image" src="https://github.com/user-attachments/assets/d5b20f61-afad-4d36-b212-14e83aca2300" />

<img width="765" height="550" alt="Image" src="https://github.com/user-attachments/assets/e9050de5-a929-49b0-b5ef-eae078c107ec" />

  </details>


[Go back to the top](#top)

