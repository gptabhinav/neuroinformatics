learnings in neuro informatics

### IMAGING TYPES (Not an exhaustive list)
Focuses on the physical anatomy and hardware of brain 
* sMRI (Structural MRI): Using strong magnetic fields to create high resolution 3D images of brain tissue.
* DTI (Diffusion Tensor Imaging): Specialized MRI that tracks water movement to map white matter tracts.
* CT (Computed Tomography): Use X-ray to see the brain. Faster and cheaper than MRI.

Focuses on the actual "firing" of neurons
* EEG (Electroencephalography): Records electrical activity from scalp. (Good speed, non invasive, blurry spatial resolution because of skull -- cannot see deep brain structures)
* ECoG (Electrocorticography): Electrodes placed directly on brain surface (usually during surgery) (Highly invasive, gold standard for clear signals and precise location of signals)
* LFP (Local Field Potential): Similar to ECoG but recorded via microelectrodes inside the brain tissue rather than on the surface. (This is common in deep brain simulation (DBS) research)
* MEG (Magnetoencephalography): Measures magnetic fields produced by brain electricity. (Better spatial accuracy than EEG, since magnetic fields arent distorted by skull. Extremely expensive; requires a room shielded by Earth's magnetic field)

Indirect Activity - these track "where the blood goes," assuming active neurons need more energy (oxygen and glucose)
* fMRI (Functional MRI): Measures the BOLD (Blood Oxygen Level Dependent) signal. (Excellent spatial resolution, can see activity in a 1mm cube. Its slow though, since it tracks blood flow, which lags behind actual thought by several seconds)
* PET (Positron Emission Tomography): Involves a radioactive tracer (Can target specific chemicals, like dopamine or amyloid plaques. It requires injection and is thus invasive. Also, it has lower resolution than fMRI)
* fNIRS (Functional Near-Infrarer Spectroscopy): Uses infrared light to measure blood oxygen through the skin. (The nice thing here is its portable and wearable. The con is that we can only "see" the surface of the brain (the cortex))

| Category | Modality | Primary Signal | Spatial Resolution | Temporal Resolution | Invasive? | Key Strength / Use Case |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Structural** | **sMRI** | Hydrogen Proton Density | **High** (~1mm) | N/A (Static) | No | Gold standard for anatomy & volume. |
| (Hardware) | **DTI** | Water Diffusion | **High** | N/A (Static) | No | Maps white matter "highways." |
| | **CT** | X-Ray Absorption | Medium | N/A (Static) | No | Fast; emergency/trauma imaging. |
| **Direct** | **EEG** | Scalp Electricity | **Low** (~cm) | **High** (ms) | No | Real-time tracking; portable. |
| (Firing) | **ECoG** | Surface Electricity | **High** (~mm) | **High** (ms) | **Yes** | Clear signal; surgical mapping. |
| | **LFP** | Deep Tissue Electricity | **Very High** | **High** (ms) | **Yes** | Local circuit activity (DBS). |
| | **MEG** | Magnetic Fields | Medium | **High** (ms) | No | High-speed data without skull distortion. |
| **Indirect** | **fMRI** | Blood Oxygen (BOLD) | **High** (~mm) | **Low** (sec) | No | Identifying "where" thoughts occur. |
| (Metabolic) | **PET** | Radioactive Tracers | Medium | **Very Low** | **Yes** | Neurochemistry (Dopamine/Amyloid). |
| | **fNIRS** | Infrared Light | Medium | Medium | No | "Portable fMRI" for moving subjects. |


