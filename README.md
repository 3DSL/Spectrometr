# Spectrometr
3DSL Spectrometer is a web application for analyzing optical spectra using your device's camera. The program captures, processes, and visualizes spectra in real-time, detects peaks and valleys, compares multiple measurements, and exports data.
🚀 Key Features
Operation Modes:

📊 Transmission - analyzes light transmission through samples

⚫ Absorption - analyzes light absorption

🌗 Dark/Light Theme - customizable interface

Camera Control:

Automatic camera connection

Custom analysis area selection

Sensitivity adjustment slider

Spectral Analysis:

Automatic peak detection (green markers)

Valley detection (red markers)

Detection threshold customization

Data smoothing slider

Calibration:

Pixel → nanometer conversion

Two-point calibration system

Linear wavelength interpolation

Data Management:

Save multiple spectra

Compare up to 16 spectra with color coding

Export to PNG, SVG, SPC, CSV formats

🛠️ How to Use
Step 1: Setup
Open the app in Chrome/Firefox

Allow camera access when prompted

Point camera at light spectrum (e.g., through diffraction grating)
Step 3: Calibration (Optional)
Enter two known wavelengths (nm)

Click "Start Calibration"

Click corresponding points on the chart

Step 4: Spectrum Analysis
Real-time parameter adjustment:

Sensitivity - signal amplification

Smoothing - noise reduction

Peak/Valley Threshold - detection sensitivity

Step 5: Save & Compare
Click "Save Spectrum" to store current plot

Switch between spectra using colored tabs

Export: "Export" → select format → "Confirm"

📁 Export Formats
Format	Purpose	Special Features
PNG	Visualization	Bitmap image of graph
SVG	Publications	Vector image with high quality
SPC	SpectraLab	Professional spectroscopy format
CSV	Data analysis	Raw values (wavelength, intensity)
🌐 Localization
The RU/EN toggle in the top-right corner switches interface languages. Settings are saved in browser's local storage.

⚙️ Technical Requirements
Modern browser (Chrome 90+, Firefox 88+)

Device camera access

Minimum screen resolution: 1024×768

🧪 Application Examples
Optical filter analysis

Liquid absorption spectroscopy

Light source comparison

Educational optics experiments

Tip: For accurate measurements, stabilize your device and work in low-light conditions.

The project is ready to use - just open index.html in your browser! Developers note: No dependencies required except Chart.js (loaded via CDN).
