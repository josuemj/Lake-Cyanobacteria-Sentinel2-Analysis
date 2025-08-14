# Lake Cyanobacteria Sentinel-2 Analysis

## Overview
This project analyzes cyanobacteria blooms in Guatemalan lakes (Atitlán and Amatitlán) using Sentinel-2 satellite imagery. It automates the download, processing, and visualization of multiband TIFF images, applying robust cloud filtering and spectral indices to detect and quantify cyanobacteria presence over time and space.

## Usage
- Clone the repository and install requirements:
  ```bash
  pip install -r requirements.txt
  ```
- Configure Sentinel Hub credentials in a `.env` file:
  ```env
  CLIENT_ID=your_client_id
  CLIENT_SECRET=your_client_secret
  ```
- Run the Jupyter notebooks in `lab/` for step-by-step analysis:
  - `sentinel_api.ipynb`: Data download and API setup (test)
  - `geo.ipynb`: Image download
    - `analysis.ipynb`: Filtering, indices calculation, temporal analysis, models

## References
- [Sentinel Hub Documentation](https://docs.sentinel-hub.com/api/latest/)
- [NDCI and Chlorophyll-a estimation](https://www.sciencedirect.com/science/article/pii/S0034425718302362)

## License
MIT