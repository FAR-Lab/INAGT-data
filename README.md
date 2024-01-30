# Is Now a Good Time? Dataset

## Overview
The Is Now a Good Time (INAGT) dataset consists of automotive, physiological, and visual data collected from drivers who self-annotated responses to the question "Is now a good time?" indicating the opportunity to receive non-driving information during a 50-minute drive. We augment this original driver-annotated data with third-party annotations of perceived safety to explore potential driver overconfidence. The dataset includes data from up to 61 drivers.

## Data
- 1915 samples across 46 drivers during a 28.5 km route
- Yes / No annotations from drivers if it is a good or bad time to interact
- 3rd part rating of Safe / Unsafe moments (from MTurk raters)
- Road video, driver face video, driver side video, and driver over shoulder video
- Automotive data (CAN) from a 2015 Toyota Prius
- Physiological data from the driver
- Pre-computed road object detection (via I3D Inception V1)
- Pre-computed Font body pose (via OpenPose)
- Pre-computed facial landmarks (via OpenPose)
- Pre-computed side body pose (via OpenPose)

[Sample data from participants 40 and 76](https://drive.google.com/drive/folders/1HwHeOLscfIPqvY04ezRSmqfggp_NSlve?usp=sharing)

## Public Dataset
We provide an [anonymized, publicly available dataset](https://purl.stanford.edu/gj863qr6417) where 61 participant videos have been blurred and pre-computed video data (i.e., road objects, body pose, facial landmarks) is provided for 6 seconds before and 6 seconds after each "Is Now A Good Time?" query. The dataset is provided as-is and without warranty of any kind. If you use the data in your work, please take a look at the Recommended Citation Guidelines below to cite and acknowledge.

## Requesting the Full Dataset
The full, non-anonymized dataset is available for research use. Interested parties must have IRB approval and/or agree to our Data Use Agreement to use the data. Please fill out our [dataset request form](https://forms.gle/SNCH4YCy79JL5VZH8) to contact us about downloading the full dataset. The dataset is provided as-is and without warranty of any kind. If you use the data in your work, please take a look at the Recommended Citation Guidelines below to cite and acknowledge.

## Related Research
Rob Semmens, Nikolas Martelaro, Pushyami Kaveti, Simon Stent, and Wendy Ju. 2019. Is Now A Good Time? [**An Empirical Study of Vehicle-Driver Communication Timing.**](https://dl.acm.org/doi/10.1145/3290605.3300867) In <i>Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems</i> (<i>CHI '19</i>). Association for Computing Machinery, New York, NY, USA, Paper 637, 1–12. DOI:[https://doi.org/10.1145/3290605.3300867](https://doi.org/10.1145/3290605.3300867)

[![IMAGE ALT TEXT](http://img.youtube.com/vi/AHhaJ4DMoV8/0.jpg)](http://www.youtube.com/watch?v=AHhaJ4DMoV8 "Is Now A Good Time? An Empirical Study of Vehicle-Driver Communication Timing")

Tong Wu, Nikolas Martelaro, Simon Stent, Jorge Ortiz, and Wendy Ju. 2021. [**Learning When Agents Can Talk to Drivers Using the INAGT Dataset and Multisensor Fusion.**](https://dl.acm.org/doi/abs/10.1145/3478125) <i>Proc. ACM Interact. Mob. Wearable Ubiquitous Technol.</i> 5, 3, Article 133 (Sept 2021), 28 pages. DOI:[https://doi.org/10.1145/3478125](https://doi.org/10.1145/3478125)

[![IMAGE ALT TEXT](http://img.youtube.com/vi/1bOl--Lsjbs/0.jpg)](http://www.youtube.com/watch?v=1bOl--Lsjbs "Learning When Agents Can Talk to Drivers Using the INAGT Dataset and Multisensor Fusion")

## Recommended Citation Guidelines

> @article{wu_martelaro_2021, 
>  author = {Wu, Tong and Martelaro, Nikolas and Stent, Simon and Ortiz, Jorge and Ju, Wendy},
>  title = {Learning When Agents Can Talk to Drivers Using the INAGT Dataset and Multisensor Fusion},
>  year = {2021},
>  issue_date = {Sept 2021},
>  publisher = {Association for Computing Machinery},
>  address = {New York, NY, USA},
>  volume = {5},
>  number = {3},
>  url = {https://doi.org/10.1145/3478125},
>  doi = {10.1145/3478125},
>  journal = {Proc. ACM Interact. Mob. Wearable Ubiquitous Technol.},
>  month = sep,
>  articleno = {133},
>  numpages = {28},
>  keywords = {multi-modal learning, dataset, interaction timing, deep convolutional network, vehicle}
>}

In the Acknowledgements section, please include: "The data were collected by the Is Now A Good Time Research team under the directorship of Wendy Ju. The original data collection was supported by funding from the Toyota Research Institute. Data were accessed via request at the Is Now a Good Time Dataset website (https://far-lab.github.io/INAGT-data/)."
