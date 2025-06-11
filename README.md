# Low-Pass Filter (Active)

This project simulates an Active Low-Pass Filter using Op-Amp 741 in NI Multisim.

---

## 🧠 Working Principle

A Low-Pass Filter allows signals with a frequency lower than a certain cutoff frequency to pass and attenuates frequencies higher than the cutoff.

- The cutoff frequency `Fc` is given by:  
  `Fc = 1 / (2 * π * R * C)`

In this simulation:
- R = 2kΩ  
- C = 20nF  
- Hence, `Fc ≈ 4 kHz`

---

## 🖼️ Circuit and Simulation Screenshots

### 🧪 Circuit Diagram and Bode Plot
![Circuit and Plot](<replace-with-your-uploaded-path>)

*(To update: Click “Add file” → “Upload files” → upload your screenshot and copy its path here)*

---

## 📊 Output Observation Table

| Frequency (Hz) | Output (Magnitude) | Output (Phase) |
|----------------|--------------------|----------------|
| 10             | ~9.5 dB            | ~180°          |
| 1k             | ~8.9 dB            | ~165°          |
| 4k (cutoff)    | ~6 dB              | ~135°          |
| 10k            | ~0 dB              | ~90°           |
| 100k           | -20 dB             | ~45°           |

---

## 📁 Files Included
- Multisim design file (`.ms14`)
- Simulation screenshots


## 🙋‍♂️ Author

Mohammad Suhel  
2nd Year Electrical Engineering Student  
Simulation done using Multisim
