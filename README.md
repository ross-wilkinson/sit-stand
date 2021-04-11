# Sit-stand cycling project

## Author

Ross Wilkinson, Ph.D.

## Overview

This repository contains the data and processing files for the sit-stand project.

The **aim** of this project was to compare the  distribution of joint power, muscle-activity, and effective mechanical advantage (EMA) within the lower-limb during seated and standing cycling at a variety of power outputs and cadences.

## Data collection

* 3-D motion capture at 200 Hz.
* Radial and tangential force on the left and right crank at 100 Hz.
* Surface EMG of eight lower limb muscles at 2 kHz.

## Subjects

* n=24. Subject details are contained in the ./data/dataTable.csv file.

## Conditions

| Condition ID | Posture | Cadence (RPM) | Power output (% of P<sub>max) |
| --- | --- | --- | --- |
| 00 | static | -- | -- |
| 01 | seated | 70 | 10 |
| 02 | seated | 70 | 30 |
| 03 | seated | 70 | 50 |
| 04 | seated | 120 | 10 |
| 05 | seated | 120 | 30 |
| 06 | seated | 120 | 50 |
| 07 | standing | 70 | 10 |
| 08 | standing | 70 | 30 |
| 09 | standing | 70 | 50 |
| 10 | standing | 120 | 10 |
| 11 | standing | 120 | 30 |
| 12 | standing | 120 | 50 |
| 13 | seated | 120 | 100 |
| 14 | standing | 120 | 100 |
| 15 | trunk movement | -- | -- |
| 16 | counter movement jump | -- | -- |

*Note:* Filenames = s01c0101, s01c0201, etc.

## Trials

* 1 x conditions 00 to 15
* 3 x condition 16

## Data analysis

* OpenSim
  * Inverse kinematics
  * Inverse dynamics
  * Muscle-tendon unit lengths
  * Point kinematics

* Model
  * Full-body model created by Rajagopal et al. (2016) and adapted by Lai et al. (2017).

## Publication(s)

Please cite the following publications if using code or data from this repository:

1. Wilkinson, Ross D., Glen A. Lichtwark, and Andrew G. Cresswell. 2020. “The Mechanics of Seated and Nonseated Cycling at Very-High-Power Output: A Joint-Level Analysis.” Medicine & Science in Sports & Exercise 52 (7): 1585–94. <https://doi.org/10.1249/MSS.0000000000002285>.
2. Wilkinson, Ross D., Andrew G. Cresswell, and Glen A. Lichtwark. 2020. “Riders Use Their Body Mass to Amplify Crank Power during Nonseated Ergometer Cycling.” Medicine & Science in Sports & Exercise 52 (12): 2599–2607. <https://doi.org/10.1249/MSS.0000000000002408.>
3. Wilkinson, Ross D., and Glen A. Lichtwark. 2020. “A Method for Tracking Centre of Mass Displacement during Non-Seated Cycling Using an Inertial Sensor.” SportRxiv. <http://dx.doi.org/10.31236/OSF.IO/HTR4K.>

## Subject ID within publications

| Subject ID | ID in 1 | ID in 2 | ID in 3 |
| --- | --- | --- | --- |
| 01 | 01 | 01 | -- |
| 02 | -- | -- | -- |
| 03 | -- | -- | 01 |
| 04 | 02 | 02 | 02 |
| 05 | -- | -- | 03 |
| 06 | 03 | 03 | -- |
| 07 | -- | -- | 04 |
| 08 | 04 | 04 | 05 |
| 09 | 05 | 05 | -- |
| 10 | -- | -- | 06 |
| 11 | 06 | 06 | -- |
| 12 | 07 | 07 | 07 |
| 13 | 08 | 08 | -- |
| 14 | 09 | 09 | -- |
| 15 | 10 | 10 | -- |
| 16 | -- | -- | -- |
| 17 | 11 | 11 | -- |
| 18 | -- | -- | 08 |
| 19 | -- | -- | -- |
| 20 | 12 | 12 | -- |
| 21 | -- | -- | -- |
| 22 | 13 | 13 | -- |
| 23 | 14 | 14 | 09 |
| 24 | 15 | 15 | -- |

*Note:* Due to the repeated-measures study design, subjects were omitted from a study if the data from any of the conditions or outcome measures were not collected or the collected data was unusable.
