# Spectral-data

Data Description:
Spectral data, acquired through a low-cost spectrometer, was obtained from cassava leaves at various stages of growth within a controlled environment, specifically a screen house. This data collection period spanned from week 1 to week 16 of plant growth. During this window, the plants were inoculated with a virus at week 4. This deliberate early inoculation was designed to capture features that can aid in the detection of disease even before visible symptoms manifest in the later weeks of data collection.
Concurrently, RGB image data was captured using a smartphone over the same period, offering a visual representation of the cassava leaf's appearance until the onset of visible symptoms. The experiments took place in a controlled environment termed as screenhouse, with 3 class partitions( control, cbsd and cmd). The following data was captured 


Spectral data: acquired by a low cost spectrometer.

Leaf image data(RGB image data): A corresponding image of a plant leaf was captured using a smartphone (infinix HOT 10i, camera resolution 4160x3120= 13 mega pixels ).

Biochemical data: The lab picked chlorophyll data as a ground truth on disease spreading


Methods
Data acquisition: Data was acquired using a smartphone add-on spectrometer integrated with software application to analyze visible spectrum per leaf and capture information across various wavelengths of electromagnetic spectrum in range of 400 to 700 (nm). A region of interest was defined from which features were extracted by analyzing the pixel intensity values in the region of interest. Further exploratory measures such as mean were traversed to look for spectral characteristics.
Calibration: Calibration line is first created before anything.With absorbance calibration we measure the light absorption of several standard samples of different known concentrations at defined wavelengths.We calibrate low cost with out sample and get intensity (Io) then get intensity with sample (I), from these we measure our transmittance and absorption 

Tool Design: The spectrometer is designed with a consistent light source powered by an LED. This emitted light passes through a narrow slit and is subsequently dispersed by a grating. The dispersed light is then captured by the camera sensor integrated into the smartphone where we utilise its processor to analyse the spectral data captured.


Data Summary


| Left |  Center  | Right |
|:-----|:--------:|------:|
| L0   | **bold** | $1600 |
| L1   |  `code`  |   $12 |
| L2   | _italic_ |    $1 |
Spectral data
Bio Chemical
Image data
HLT
1167
582
1167
CBSD
582
582
582
CMD
564
564
564
Total
2313
1728
2313

|         | Spectral | BioChemical | Image data |
|:-------------:|:-------------:|:----------------:|
| HLT      | 1167 | 582 | 1167 |
| CBSD     | 582     |  582 | 582 |
| CMD |  564   |  564  |  564 |
| Total |  2313   |  1728  | 2313 |


Spectral data points


Labeling
Every data point collected is tagged using a standard method ‘’A1HLT1a. This naming format is used for all the data types (image, Biochemical, spectral data) to distinguish each data point by class, week, variety and leaf. The tagged label is converted as: A for a variety ranging from A to C (A,B,C). The figure 1 means week 1 which goes up to week 15. HLT is a short form for class health, and this can be either CMD(cassava mosaic disease) or CBSD(cassava brown streak disease). The 1 after class type is leaf, this can be read from 1, 2 and 3. The data is collected and combined and saved in csv format as shown above in spectral data points.

Experimental results of this dataset are being worked on by the Master's students under his dissertation and findings will be shared as publications through the project website.
Dataset and further results can be found at: https://github.com/bu-ai/low_cost_spectral







