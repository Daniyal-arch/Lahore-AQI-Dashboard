# Lahore Air Quality Index (AQI) Visualization Dashboard

A real-time visualization and analysis tool for monitoring the Air Quality Index (AQI) of Lahore district using Sentinel-5P satellite data. The dashboard provides dynamic visualizations for gases like NO₂, SO₂, CO, O₃, and Aerosols with an interactive interface built in Python.

---

## Features

- **Sentinel-5P Data Integration**: Visualizes real-time air quality data using Sentinel-5P satellite data processed via Google Earth Engine.
- **Dynamic Visualization**: Interactive maps for NO₂, SO₂, CO, O₃, and Aerosols across Lahore.
- **Toolbox for Interaction**: Allows users to zoom, pan, and interact with the AQI layers.
- **Individual Gas Statistics**: Provides detailed statistics and plots for each specific pollutant.
- **Area-specific AQI Stats**: Ability to select areas and view AQI statistics over time.
- **Python-based Frontend**: Developed using geemap, ipywidgets, folium, and Google Earth Engine Python API.

---

## Visual Preview

| AQI Visualization Dashboard | Individual Gas Statistics | Toolbox |  
|-----------------------------|---------------------------|--------|  
| ![Frontend](./images/Frontend.jpg) | ![Statistics](./images/Option%20to%20identify%20statistics%20per%20Gas.jpg) | ![Toolbox](./images/ToolBox%20To%20Interact%20with%20AQI.jpg) |

| NO₂ | SO₂ | CO | O₃ | Aerosols |
|-----|-----|----|----|---------|
| ![NO2](./images/NO2.jpg) | ![SO2](./images/SO2.jpg) | ![CO](./images/CO.jpg) | ![O3](./images/O3.jpg) | ![Aerosol](./images/aerosol.jpg) |

| Obtained Statistics in Lahore |
|-------------------------------|
| ![Stats](./images/Obtained%20Statistics%20at%20Some%20Area%20in%20Lahore%20of%20AQI.jpg) |

---

## Technologies Used

- **Google Earth Engine (GEE)**: For accessing and processing Sentinel-5P datasets.
- **geemap & folium**: For interactive map visualizations.
- **ipywidgets**: For building user interface widgets.
- **Python**: Core programming language for implementation.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Authenticate with Google Earth Engine:

```bash
earthengine authenticate
```

---

## Usage

1. Run the Python notebook or script:

```bash
jupyter notebook AQI_Visualization.ipynb
```

2. Interact with the AQI dashboard using the provided widgets and map interface.

---

## Project Structure

```
├── images/                             # Contains dashboard and result visualizations
├── requirements.txt                   # Required Python libraries
├── AQI_Visualization.ipynb            # Main notebook
├── README.md                          # Documentation
```

---

## Contributing

Contributions are welcome! Feel free to fork this repo, open issues, or submit pull requests.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- Sentinel-5P Satellite Data (European Space Agency)
- Google Earth Engine

---

## Contact

Daniyal Khan   
Email: daniyalnahk@gmail.com

