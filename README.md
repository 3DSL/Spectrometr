3DSL Spectrometer (from the Creative Science Workshop - 3D Science Laboratory)
3DSL Spectrometer is a web application for analyzing optical spectra using your device's camera. Capture, process, and visualize light spectra in real-time with this browser-based tool.

![image](https://github.com/user-attachments/assets/325a8daa-e072-4a59-944c-ba919567d4e1)


Key Features ✨
📷 Real-time camera spectrum analysis

📊 Transmission and absorption modes

🔍 Automatic peak/valley detection

⚙️ Two-point wavelength calibration


![image](https://github.com/user-attachments/assets/0b3e8467-2b6b-4c53-b2a9-e09a1e3a7da7)


💾 Save and compare multiple spectra

![image](https://github.com/user-attachments/assets/c4c691f3-68e0-45f5-ab8b-54d035a7f8f2)


🌐 Multi-language support (English/Russian)

📁 Export to PNG, SVG, SPC, CSV formats

![image](https://github.com/user-attachments/assets/c0d3c13e-7a4e-4a69-9d69-6bbfcbfb381e)


How to Use 🛠️
1. Setup
bash
git clone https://github.com/your-username/3dsl-spectrometer.git
cd 3dsl-spectrometer
# Open index.html in browser
2. Basic Operation
Allow camera access when prompted

Point camera at light spectrum (e.g., through diffraction grating)

Click camera icon (📷) to enable video feed

Use "Select Area" to define analysis region

3. Calibration (Optional)
Enter two known wavelengths in calibration section

Click "Start Calibration"

Click corresponding points on the chart

4. Analysis
Adjust parameters in real-time:

Sensitivity: Signal amplification

Smoothing: Noise reduction

Thresholds: Detection sensitivity

Toggle between Transmission/Absorption modes

Save spectra with "Save Spectrum" button

5. Export Data
Click "Export" button

Select spectra to export

Choose format: PNG, SVG, SPC, or CSV

Click "Confirm Export"

Export Formats 📁
Format	Purpose	Best For
PNG	Image export	Reports, presentations
SVG	Vector graphics	Publications, printing
SPC	Spectral data	Professional analysis
CSV	Raw values	Spreadsheet analysis
Requirements ⚙️
Modern browser (Chrome, Firefox, Edge)

Camera access

Screen resolution: 1024×768+

Internet connection (for Chart.js CDN)

Application Examples 🧪
Optical filter analysis - Measure transmission spectra

Liquid spectroscopy - Analyze absorption properties

Light source comparison - Compare LED vs. incandescent spectra

Educational demonstrations - Teach principles of optics

Tip: For best results, stabilize your device and work in low-light conditions.

Development Setup 💻
No dependencies required! Just open index.html in your browser. The app uses:

Chart.js for visualization

Native browser APIs for camera access

Pure JavaScript/CSS/HTML

License 📄
This project is licensed under the MIT License - see the LICENSE file for details.

Support 🌐
Switch between English/Russian using the RU/EN toggle in the top-right corner.

Educational optics experiments

Tip: For accurate measurements, stabilize your device and work in low-light conditions.

The project is ready to use - just open index.html in your browser! Developers note: No dependencies required except Chart.js (loaded via CDN).
