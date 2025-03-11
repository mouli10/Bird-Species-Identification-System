# Bird Species Identification System

## Project Overview
This project presents a dynamic web application for precise bird species identification, visualization, and geolocation integration. It aims to assist conservationists, researchers, and bird enthusiasts by providing an accurate and interactive tool for bird species recognition and trend analysis.

## Features
- **Machine Learning-Based Identification:** Utilizes a ResNet34-based model for enhanced bird species identification accuracy.
- **Image Upload & Classification:** Users can upload bird images for real-time species identification.
- **Comprehensive Species Information:** Displays habitat, diet, and migration patterns for identified species.
- **Geolocation Mapping:** Enables users to visualize bird sightings on an interactive map.
- **Heatmap Visualization:** Showcases biodiversity hotspots based on collected sighting data.
- **User-Friendly Interface:** Ensures seamless navigation and interactions for users of all levels.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Machine Learning Framework:** PyTorch (ResNet34 model)
- **Database:** MySQL or PostgreSQL
- **Mapping & Visualization:** Google Maps API / Leaflet
- **Other Libraries:** Torchvision, Matplotlib, OpenCV

## Installation & Setup
### Prerequisites
- Python 3.7+
- pip (Python package manager)
- Virtual environment (optional but recommended)
- MySQL/PostgreSQL setup (if using a database)

### Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/bird-identification.git
   cd bird-identification
   ```
2. **Create a Virtual Environment (Optional but Recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Setup Database** (if using a database)
   ```sh
   python manage.py migrate
   ```
5. **Run the Application**
   ```sh
   flask run
   ```
6. **Access the Web App**
   Open `http://127.0.0.1:5000` in your browser.

## Usage
1. Upload a bird image for classification.
2. View the identified species along with detailed information.
3. Explore sightings and hotspots using interactive geolocation mapping.
4. Contribute to the dataset by adding new observations.

## System Architecture
- **Frontend:** Handles user interactions and visualizations.
- **Backend:** Processes images, manages database queries, and communicates with the ML model.
- **ML Model:** ResNet34 processes images and returns predictions.
- **Geolocation Module:** Integrates mapping APIs to display sighting locations.

## Testing
Various testing techniques were applied to ensure system reliability:
- **Unit Testing:** Tested image processing, species identification, and database interactions.
- **Integration Testing:** Validated smooth interaction between modules.
- **Performance Testing:** Ensured quick response times for identification and mapping.
- **Security Testing:** Verified secure storage and handling of user and geolocation data.

## Results
- **High Accuracy in Species Recognition** using ResNet34.
- **Smooth and Responsive UI** for seamless user interactions.
- **Geolocation & Heatmap Features** for detailed biodiversity insights.
- **Successful System Testing** across functional, performance, and security metrics.

## Future Enhancements
- Expand dataset to improve model performance.
- Integrate user authentication for personalized tracking.
- Optimize heatmap generation for larger datasets.
- Add mobile app support for field researchers.

## Contributors
- **Mouli Vunnam**

## Acknowledgments
- **Professor:** Dr. Michael Johnson
- **Mentor:** Dr. Razi Iqbal

## Contact
For any inquiries or contributions, feel free to reach out via GitHub issues or email [moulivunnam100@gmail.com]

