### Wildfire Detection and Alert System

The **Wildfire Detection and Alert System** is designed to predict and manage wildfire occurrences by integrating sensor data analysis with satellite imagery. The system uses advanced machine learning techniques—**Support Vector Machines (SVM)** for sensor data and **Convolutional Neural Networks (CNN)** for satellite imagery—enabling early detection of wildfire events with high accuracy. This system is vital for improving disaster response times and ensuring proactive intervention.

#### Key Features:

- **Sensor Data Integration**: SVM models process sensor data (e.g., temperature, humidity, and smoke levels) to detect unusual patterns indicative of potential wildfires.
- **Satellite Imagery Analysis**: CNN models analyze satellite imagery to identify early signs of fire outbreaks and predict the potential spread of wildfires.
- **Email Alert System**: The system sends automated email alerts to disaster management teams, enabling timely action to mitigate the impact of fires.

#### Datasets Used:

1. **Satellite Imagery Dataset** (from Kaggle)  
   - **Kaggle Link**: [Wildfire Prediction Dataset](https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset)  
   This dataset contains high-resolution satellite images used for identifying wildfire occurrences. It includes:
   - **Satellite Imagery**: High-resolution images of various regions taken by satellites.
   - **Labeling Information**: Data identifying regions affected by wildfires.
   - **Features**: Image pixels, geographical coordinates, and time of capture.

2. **Environmental Sensor Data**  
   This dataset focuses on environmental and sensor data relevant to wildfire detection. It includes:
   - **Temperature**: Recorded temperatures in wildfire-prone areas.
   - **Humidity**: Data on humidity levels, which are important indicators of fire risk.
   - **Vegetation**: Data on vegetation, often associated with the presence of fire.
   

By combining these datasets, the system leverages both visual and environmental data to predict wildfire occurrences and their potential impact, ensuring a more comprehensive detection and alert system.

#### Future Plans:
- **Real-Time Detection**: In future iterations of the system, we plan to modify the solution to integrate real-time satellite imagery and sensor data, enabling continuous wildfire detection and faster response times.
