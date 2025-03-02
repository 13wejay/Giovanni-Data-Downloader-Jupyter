# Giovanni Data Downloader 📡🌍  

![Python](https://img.shields.io/badge/Python-3.x-blue)  
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)  
![License](https://img.shields.io/badge/License-MIT-green)  

A Jupyter notebook for downloading and processing data from **NASA Giovanni** using Python. This tool automates the retrieval of geospatial data and enables efficient analysis.  

---  

## **Table of Contents**  
1. [Overview](#overview)  
2. [Features](#features)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Data Requirements](#data-requirements)  
6. [Output](#output)  
7. [Contributing](#contributing)  
8. [License](#license)  
9. [Acknowledgments](#acknowledgments)  

---  

## **Overview**  
This project provides a Python-based solution for downloading and analyzing **NASA Giovanni** data. Implemented as a Jupyter Notebook, the script simplifies access to Earth science data and enables users to automate data retrieval, processing, and visualization.  

---  

## **Features**  
- **Automated Data Retrieval**: Fetches datasets from **NASA Giovanni** seamlessly.  
- **Batch Processing**: Supports downloading multiple datasets efficiently.  

---  

## **Installation**  

To use this script, follow these steps:  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/Giovanni-Data-Downloader.git

2. **Navigate to the project folder:**
   ```bash
   cd Giovanni-Data-Downloader

3. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   
4. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt

---

## **Usage**

1. Open Jupyter Notebook or Visual Studio Code Editor.
2. Open **Giovanni_Data_Downloader.ipynb** in Jupyter.
3. Set Up Authorization:
   - Enter your NASA Earthdata Username & Password.
   - Provide your NASA User Token for authentication.

5. Configure Download Settings:
   - Specify the directory containing the .txt file with Giovanni data URLs.
   - Set the output directory where the downloaded files will be saved.

6. Run the Script

---

## **Data Requirements**

1. **NASA Giovanni .TXT file of direct links** (i put the example: **00to24_Kalimantan.txt**)

---

## **Output**

1. **.nc** raw data for further analysis process

---

## **Contributing**
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (**feature-branch**).
3. Commit your changes and push.
4. Open a Pull Request.

---

## **License**
This project is licensed under the **MIT License**.

---

## **Acknowledgments**  
This project utilizes several powerful Python libraries to streamline the Giovanni data download process:  

- **os** – For handling file paths and directory operations.  
- **requests** – For making HTTP requests to NASA Giovanni to download data.  
- **concurrent.futures** – For enabling **multithreading** to speed up downloads.  
- **tqdm** – For displaying a progress bar to track download completion.  

Special thanks to **NASA Giovanni** and **Earthdata** for providing access to valuable geospatial datasets. 🚀  

---
