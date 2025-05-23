<h3 align="center">!! Diving deep into computational neuroscience!</h3>

#### Libraries:
- [MNE](https://mne.tools/stable/index.html)

### projects:
- **Generalized Neuroscience Library**:  
    A modular Python library designed to streamline data analysis, visualization, and modeling in neuroscience research.  
    - **Features**:
        - Unified data loaders for EEG, MEG, fMRI, and spike data
        - Preprocessing pipelines (filtering, artifact rejection, normalization)
        - Statistical analysis and machine learning tools
        - Interactive visualization modules
      
   

        ### Neuroscience Data Types

        Computational neuroscience leverages a variety of data types, each providing unique insights into brain function. Below are some of the most common data modalities:

        #### 1. EEG (Electroencephalography)
        - **Description**: Measures electrical activity of the brain via electrodes placed on the scalp.
        - **Applications**: Sleep studies, epilepsy diagnosis, cognitive neuroscience, brain-computer interfaces.
        - **Data Characteristics**:
            - High temporal resolution (milliseconds)
            - Low spatial resolution
            - Susceptible to noise and artifacts (e.g., eye blinks, muscle activity)
        - **Typical File Formats**: `.edf`, `.bdf`, `.set`, `.fif`

        #### 2. MEG (Magnetoencephalography)
        - **Description**: Detects magnetic fields produced by neural activity.
        - **Applications**: Functional brain mapping, epilepsy localization, cognitive studies.
        - **Data Characteristics**:
            - High temporal resolution
            - Better spatial resolution than EEG
            - Requires magnetically shielded rooms
        - **Typical File Formats**: `.fif`, `.ds`, `.meg4`

        #### 3. fMRI (Functional Magnetic Resonance Imaging)
        - **Description**: Measures brain activity by detecting changes in blood oxygenation (BOLD signal).
        - **Applications**: Mapping brain function, connectivity analysis, clinical research.
        - **Data Characteristics**:
            - High spatial resolution (millimeters)
            - Low temporal resolution (seconds)
            - Sensitive to motion artifacts
        - **Typical File Formats**: `.nii`, `.nii.gz`, `.img`, `.hdr`

        #### 4. Structural MRI
        - **Description**: Provides detailed images of brain anatomy.
        - **Applications**: Morphometric analysis, lesion detection, anatomical mapping.
        - **Data Characteristics**:
            - High spatial resolution
            - No temporal information
        - **Typical File Formats**: `.nii`, `.dcm`, `.img`

        #### 5. Spike Data (Electrophysiology)
        - **Description**: Records action potentials from individual neurons using microelectrodes.
        - **Applications**: Neural coding, brain-machine interfaces, animal studies.
        - **Data Characteristics**:
            - Very high temporal resolution (microseconds)
            - Single-unit or multi-unit recordings
            - Large data volumes
        - **Typical File Formats**: `.mat`, `.nwb`, `.h5`, proprietary formats

        #### 6. LFP (Local Field Potentials)
        - **Description**: Measures summed electrical activity from groups of neurons.
        - **Applications**: Oscillation analysis, circuit dynamics, animal models.
        - **Data Characteristics**:
            - Intermediate spatial and temporal resolution
            - Often recorded alongside spike data
        - **Typical File Formats**: `.mat`, `.nwb`, `.h5`

        #### 7. Calcium Imaging
        - **Description**: Uses fluorescent indicators to visualize neuronal activity via calcium influx.
        - **Applications**: Population activity mapping, circuit analysis, in vivo imaging.
        - **Data Characteristics**:
            - High spatial resolution
            - Slower temporal resolution compared to electrophysiology
            - Large image sequences
        - **Typical File Formats**: `.tif`, `.h5`, `.nwb`

        #### 8. Behavioral Data
        - **Description**: Tracks animal or human behavior during experiments.
        - **Applications**: Correlating neural activity with behavior, cognitive studies.
        - **Data Characteristics**:
            - Video, sensor, or event-based data
            - Often synchronized with neural recordings
        - **Typical File Formats**: `.csv`, `.json`, `.mp4`, `.avi`

        #### 9. Genomic and Transcriptomic Data
        - **Description**: Analyzes gene expression and genetic variation in neural tissue.
        - **Applications**: Neurogenetics, disease studies, developmental neuroscience.
        - **Data Characteristics**:
            - High dimensionality
            - Requires specialized analysis pipelines
        - **Typical File Formats**: `.fastq`, `.bam`, `.vcf`, `.csv`

        ---

        ```

       

         **Further Reading**

        - [MNE-Python Documentation](https://mne.tools/stable/index.html)
        - [BIDS Specification](https://bids.neuroimaging.io/)
        - [Neurodata Without Borders](https://www.nwb.org/)
        - [Allen Brain Atlas](https://portal.brain-map.org/)

     ```


```

        Books and Articles:
        1. https://neuraldatascience.io/intro.html
        2. https://www.statisticsdonewrong.com/significant-differences.html
        3. https://goodresearch.dev/
        4. https://ebatty.github.io/MathToolsforNeuroscience/intro.html
        5. https://stevensonlab.github.io/teaching/sand/reading/sdt-advanced.pdf
        6. https://stevensonlab.github.io/teaching/sand/reading/aliasing.pdf
        7. https://stevensonlab.github.io/teaching/sand/reading/pubo08.pdf
        8. https://stevensonlab.github.io/teaching/sand/reading/convolution.pdf
```



## Authors:

* **Sanjay Singh** - *Initial work* 

#### Contributors:

<a href="https://github.com/MimoHasPurpose/brain-tumour-detection/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MimoHasPurpose/brain-tumour-detection" />
</a>


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



![GitHub watchers](https://img.shields.io/github/watchers/MimoHasPurpose/brain-tumour-detection)