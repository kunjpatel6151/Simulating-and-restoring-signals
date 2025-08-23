# Signal Impairment and Restoration Simulator

Link : 

A web-based simulator that demonstrates the effects of common signal impairments during data transmission and applies restoration techniques to recover the original signal. The simulator is designed to help visualize how attenuation, distortion, noise, and interference affect signals and how different algorithms can mitigate these impairments.

## Features

- Simulates four major signal impairments:
  - Attenuation
  - Distortion
  - Noise
  - Interference
- Interactive controls to adjust impairment strength.
- Visual comparison of:
  - Original Signal
  - Impaired Signal
  - Restored Signal
- Real-time graphical visualization.
- Educational demonstration of signal restoration techniques.

## Signal Impairments

### Attenuation
- Reduces signal amplitude during transmission.
- Restoration using adaptive gain compensation based on signal energy.

### Distortion
- Introduces nonlinear harmonic and intermodulation distortion.
- Restoration using:
  - Power-law transformation
  - Multi-stage smoothing
  - Phase correction

### Noise
- Adds random variations to the signal.
- Restoration using:
  - Wavelet Denoising
  - Kalman Filtering
  - Gaussian Smoothing

### Interference
- Introduces unwanted periodic signals at specific frequencies.
- Restoration using:
  - Dual Notch Filtering
  - Adaptive LMS Filtering

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Chart.js
- Tailwind CSS

## Project Structure

```
Signal-Impairment-Restoration-Simulator/
│
├── index.html
└── README.md
```

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

2. Open the project directory.

3. Launch `index.html` in any modern web browser.

No installation or additional dependencies are required.

## Educational Objective

This simulator was developed as part of the **Data Communication** course to provide an interactive understanding of signal degradation during transmission and the restoration techniques used in communication systems.

## Future Enhancements

- Additional signal impairment models.
- More restoration algorithms.
- Performance metrics (SNR, MSE, RMSE).
- Export graphs and simulation results.

## License

This project is intended for educational purposes only.