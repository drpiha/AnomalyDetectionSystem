# Anomaly Detection System

## Overview
This project presents a comprehensive Anomaly Detection System designed to identify and analyze anomalies within time-series data. Utilizing a blend of rule-based algorithms, univariate and multivariate techniques, the system offers an effective approach to detect outliers. With the integration of KMeans clustering and DBSCAN methods, it caters to diverse datasets, highlighting its adaptability and robustness in handling real-world data challenges.

## Features
- **Preprocessing:** Handles missing values and normalizes the dataset to ensure quality analysis.
- **Rule-based Detection:** Implements basic anomaly detection based on predefined thresholds.
- **Univariate Analysis:** Uses Isolation Forest for detecting anomalies within individual data features.
- **Multivariate Analysis:** Employs KMeans and DBSCAN for comprehensive anomaly detection across multiple features.
- **Visualization:** Provides insightful visualizations of the data and detected anomalies using Matplotlib and Plotly.

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your system along with pip for package management.

### Installation
1. Clone the repository to your local machine:
git clone https://github.com/drpiha/AnomalyDetectionSystem.git
2. Navigate to the project directory and install the required dependencies:
cd AnomalyDetectionSystem
pip install -r requirements.txt


## Usage
To use the Anomaly Detection System, follow these steps:

1. Load your dataset into the system. The project supports CSV and Excel formats for input data.
2. Apply preprocessing to handle missing values and normalize the data.
3. Select the desired anomaly detection technique and run the analysis.
4. Visualize the results to interpret and understand the detected anomalies.

## Contributing
Contributions to improve the Anomaly Detection System are welcome. To contribute:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
- Hasan Dönmez - drhasanhd@gmail.com
- Project Link: [https://github.com/drpiha/AnomalyDetectionSystem](https://github.com/drpiha/AnomalyDetectionSystem)

## Acknowledgments
- Thanks to the open-source community for providing invaluable resources and support.
- Special thanks to everyone who contributes to improving this project.
