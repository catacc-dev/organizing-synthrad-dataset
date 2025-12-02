# Organising SynthRAD2023 dataset

Generation of a JSON file and visualisation of slices.

<details>
<summary>Table of Contents</summary>

1. [About the Project](#about-the-project)
2. [Getting Started](#getting-started)
   - [Installation](#installation)
3. [Contributing](#contributing)

</details>

## About the Project
This project aims to generate a JSON dataset file and visualise the 2D slices of MRI and CT images from the SynthRad2023 dataset ([download the dataset](https://zenodo.org/records/7260705)).

## Getting Started

### Installation
1. Clone the repository:
```bash
git clone https://github.com/catacc-dev/organizing-synthrad-dataset.git
cd organizing-synthrad-dataset
```

2. Create a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate      # Linux or macOS
venv\Scripts\activate         # Windows
```

3. Install packages
```bash
pip install -r requirements.txt
```

## Usage
To run the project, use the following command:
```bash
   python generate_json.py --input_path /folder/of/pelvis
   python load_and_display_nifti.py --input_path /folder/of/each/patient --modality ct
```

## Contributing
learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
