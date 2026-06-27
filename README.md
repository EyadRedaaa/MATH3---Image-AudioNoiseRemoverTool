# Image-AudioNoiseRemoverTool

A comprehensive MATLAB-based toolkit that applies frequency domain filtering to reduce noise in both audio signals and images. By visualizing the Fourier Transform process, it provides interactive control over the filter radius, enabling users to fine-tune the balance between noise reduction and detail preservation.

## 📖 Description

The **Image-Audio Noise Remover Tool** leverages Fourier Transform techniques to process multimedia (images and audio) in the frequency domain. It allows users to apply custom low-pass and high-pass filters to either remove noise or extract fine details. The toolkit also supports comprehensive visualization of key steps throughout the process, including audio signal plotting, image grayscale conversion, Fourier magnitude computation, frequency shifting, and the final filtered results.

## ✨ Features

### 🎵 Audio Processing
* **Read and Plot Audio Signals:** Load audio files and visualize the original noisy signal in the time domain.
* **Spectrum Visualization:** Compute and display the magnitude spectrum of the audio signal.
* **Playback Processed Audio:** Transform the filtered frequency domain back to the time domain (IFFT) and use the sound function for playback.

### 🖼️ Image Processing
* **Grayscale Conversion:** Automatically convert color images into grayscale for optimized processing.
* **Frequency Shifting & Spectra:** Visualize the Fourier Transform and shifted spectra using organized, step-by-step subplots.
* **Noise Simulation:** Add artificial noise (Salt & Pepper) to test and evaluate filtering performance.
* **Median Filtering:** Utilize digital median filtering for additional spatial noise removal.

### ⚙️ Core Filtering & Transformation (Common)
* **Custom Radius-Based Filters:** Apply low-pass and high-pass filters based on user-defined radius values to control noise reduction.
* **Interactive User Inputs:** Allow users to directly specify the filter radius for custom and flexible filtering.
* **Inverse Fast Fourier Transform (IFFT):** Transform the filtered frequency domain back into the original time domain (audio) or spatial domain (image).

## 🛠️ Tools & Technologies

* **MATLAB:** Core programming language for implementation.
* **Fast Fourier Transform (FFT):** The mathematical backbone used to transform audio signals and images into the frequency domain.
* **Frequency Filters:** Logic to isolate low or high-frequency components based on user-defined parameters.
* **Image Processing Toolbox:** Utilized for handling image operations, noise addition, and spatial filtering.
* **Audio Processing Functions:** Utilized for handling audio operations like reading, processing, and playing sound.
