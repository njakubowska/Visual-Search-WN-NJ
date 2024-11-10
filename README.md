# Brainwaves on Battlegrounds: Linking EEG Activity and White Matter Microstructure  to StarCraft II Performance.

## Project Overview
This project investigates the neural and cognitive correlates of visual search skills in the real-time strategy game StarCraft II. The research integrates EEG and MRI data to examine brain structure (white matter integrity) and brain activity during cognitive tasks. The objective is to link these neural measures to participants' performance in a real-time strategy game environment.

## Folder Structure and Data Description
This repository contains raw data from various experiments conducted during the study:
- `SC2-data`: **SC2Replays**, telemetry data extracted from StarCraft II games. These files capture detailed in-game actions and performance metrics.
- `EEG`: Raw EEG data files in **.mat** format, containing recordings of brain activity with a focus on the N2pc component, which is associated with the allocation of visual attention during the visual search task.
- `MRI`: A collection of raw MRI data files, including **bval**, **bvec**, **json**, and other standard neuroimaging formats. These files provide structural images of the brain, used to assess white matter integrity through measures like fractional anisotropy (FA).

### Details of the Data
- **Telemetry Data (SC2-data)**: These files were obtained from 30 hours of StarCraft II gameplay by each participant. The data includes metrics like unit selection, hotkey usage, resource collection rates, and more, offering insights into strategic gameplay.
- **EEG Data**: The EEG recordings were taken during a visual search task in a controlled environment, focusing on the N2pc component to measure attentional processes. The task involved distinguishing target items among distractors, which simulates in-game visual scanning.
- **MRI Data**: Structural brain imaging data captured using a 3T MRI scanner. The scans provide detailed white matter structure, with a specific focus on regions such as the right anterior limb of the internal capsule (ALIC) and the left external capsule (EC), which are associated with cognitive processing and attention.

## Study Design and Procedure
### Participants
A total of **41 right-handed participants** were recruited for the study. The final analysis included **21 participants** who completed the 30-hour StarCraft II training. Participants were:
- Right-handed
- Had normal or corrected-to-normal vision and normal color vision
- Reported playing less than 5 hours of video games per week
- Had no prior experience with real-time strategy (RTS) or first-person shooter (FPS) games
- No history of neurological or psychiatric disorders

### Training Protocol
- **StarCraft II Training**: The training was conducted over a total of 30 hours, divided into an initial 10 hours in the first 1-2 weeks, followed by an additional 20 hours over the next 2-4 weeks.
- Participants were divided into two experimental groups:
  - **Variable Environment Group (VEG)**: Played against different AI-controlled opponent races (Terran, Zerg, Protoss) with varying strategies.
  - **Fixed Environment Group (FEG)**: Consistently played against a Terran opponent using an Economic Focus strategy.
- Training sessions took place in the controlled setting of the SWPS University laboratories with standardized equipment (24" monitors, high-performance PCs).

### Data Collection
1. **EEG Recording**: Conducted during a visual search task with participants using a chinrest to minimize movement. The task involved detecting a target among distractors, measuring visual attention through N2pc component analysis.
2. **MRI Scans**: Structural scans were performed before the training to assess baseline white matter integrity.

## Funding and Acknowledgments
This project was funded by the **Polish National Science Centre (NCN)** under the grant **2016/23/B/HS6/03843**.

### Authors and Contributions
- **W. Nieciecka**: Formal analysis, visualization, original draft writing
- **P. Lewandowska**: Formal analysis, writing
- **S. Adamczyk**: Investigation, original draft writing
- **A. A. Binkowska**: Methodology, review and editing
- **A. Brzezicka**: Conceptualization, supervision, project administration
- **P. Szczeciński**: Investigation, formal analysis
- **N. Jakubowska** (Corresponding Author): Conceptualization, supervision, methodology, writing

## How to Use the Data
The data in this repository can be used to explore the relationship between cognitive performance and neural measures in a real-time strategy gaming context. Due to the raw nature of the data, preprocessing steps will be required to prepare the EEG and MRI data for analysis.

*Note*: Ensure appropriate software (e.g., MATLAB, EEGlab, FSL) is used for preprocessing EEG and MRI data.

## License and Citation
If you use this data in your research, please cite the corresponding publication and acknowledge the funding grant.
