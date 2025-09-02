# Blurry-hologram-reconstruction

##  Introduction
Digital holography offers a computational pathway for capturing and reconstructing optical wavefronts using intensity-only measurements. By encoding both amplitude and phase information through interference with a reference wave, holography enables full-field recovery of object structures, making it a powerful tool in imaging, metrology, and optical encryption. While many implementations rely on complex object fields and phase sensitive detection, simplified models using amplitude-only inputs remain valuable for educational, prototyping, and low-cost applications.
This project presents a streamlined simulation of digital holography using Fresnel diffraction theory and a grayscale image treated as an amplitude-only object field. The object wave is propagated to a virtual sensor plane using a Fourier-based Fresnel transfer function, where it interferes with a unit-amplitude reference wave to produce a synthetic hologram. The resulting intensity pattern encodes spatial information about the object and is normalized for display and reconstruction.
Reconstruction is performed by treating the square root of the hologram intensity as the input field and back-propagating it using the conjugate Fresnel kernel. This approach assumes zero phase in the recorded field, offering a simplified yet effective method for visualizing wavefront recovery. The simulation displays the original object, the hologram, and the reconstructed amplitude side-by-side, highlighting the fidelity and limitations of amplitude-only holography.
This work demonstrates key principles of scalar diffraction, interference, and inverse imaging, and provides a reproducible framework for exploring digital holography in constrained or pedagogical settings. It reflects foundational skills in wave optics, numerical modeling, and scientific visualization, and serves as a stepping stone toward more advanced phase retrieval and holographic reconstruction techniques.

This project simulates the formation and reconstruction of digital holograms using a simplified amplitude-only model and Fresnel diffraction theory. A grayscale image is treated as a complex object field with zero phase, propagated to a virtual sensor plane, and interfered with a unit-amplitude reference wave to generate a synthetic hologram. The hologram is then back-propagated to reconstruct the original object field.

## 🧠 Physics Context
- **Fresnel Propagation**: Models near-field wavefront evolution using Fourier optics.
- **Digital Holography**: Encodes object information via interference with a reference wave.
- **Inverse Imaging**: Reconstructs object amplitude from hologram intensity using backward propagation.
- **Simplified Assumptions**: Assumes zero phase in both object and recorded field for clarity and speed.

## 🚀 Features
- Load and preprocess any grayscale image as an object field.
- Simulate hologram formation using Fresnel propagation and interference.
- Reconstruct object amplitude via backward Fresnel propagation.
- Visualize original object, hologram, and reconstruction side-by-side.
- Save final figure automatically for documentation or presentation.

## 🎯 Educational & Research Value
## Ideal for:
• 	Teaching the fundamentals of digital holography and scalar diffraction.

• 	Demonstrating simplified wavefront reconstruction techniques.

• 	Prototyping low-cost or pedagogical holography models.

## 👤 Author
Developed by Alhassan Kpahambang Fuseini.
📄 License
MIT License.

