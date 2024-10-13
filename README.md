# 🎵 Music Player Using Mood and Face Detection

This project leverages emotion and face detection to provide a personalized music experience. By analyzing the user's facial expressions and mood, it suggests music that matches their current emotional state. The goal is to create a seamless, mood-based music player that enhances the listening experience.

## 🎯 Objectives
- **Mood and Face Detection**: Analyze the user's facial expressions to determine their current emotional state (happy, sad, relaxed, etc.).
- **Music Recommendations**: Play music that aligns with the detected mood.
- **User Interaction**: Provide an option for users to manually select their mood if desired.
- **Performance Analysis**: Track resource usage and performance of the system.
- **Recommendations**: Propose enhancements to improve mood detection accuracy.

## 🛠 Methodology
1. **Facial Expression Detection**: Real-time analysis of facial features using machine learning algorithms.
2. **Music Classification**: Music is categorized based on mood, and appropriate tracks are played based on detected emotions.
3. **System Data Collection**: Use system performance data (CPU, memory) to ensure efficient processing.
4. **Visualization**: Generate graphs showing resource usage and mood detection performance.

## ⚙️ Tools and Technologies
- **Python**: Core language for implementing the facial recognition and mood detection algorithms.
- **OpenCV**: Used for facial expression recognition.
- **TensorFlow/Keras**: For training models on emotion detection.
- **Spotify API**: Music streaming and recommendation engine.
- **Node.js**: For gathering system performance data.
- **MySQL**: Database for managing user data and mood history.
- **Pandas & Matplotlib**: Data analysis and visualization.
  
## 📦 Installation

### Prerequisites
- Python 3.x
- Node.js
- MySQL

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/music-player-mood-detection.git
    cd music-player-mood-detection
    ```

2. **Install Python dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Install Node.js dependencies**:
    ```bash
    cd js
    npm install
    cd ..
    ```

4. **Set up the MySQL database**:
    - Create a new database.
    - Import the provided SQL script to create necessary tables.
    - Configure the database connection in the Python script:
    ```python
    db_connection = mysql.connector.connect(
        host="your_host",
        user="your_user",
        password="your_password",
        database="your_database"
    )
    ```

5. **Run the JavaScript data collector**:
    ```bash
    node js/collectData.js
    ```

6. **Run the Python script for mood detection and music recommendation**:
    ```bash
    python app.py
    ```

## 📄 Usage

1. **System Data Collection**: The JavaScript script (`collectData.js`) gathers system performance information and writes it to a CSV file (`system_data.csv`).
2. **Mood Detection and Music Playback**: The Python script (`app.py`) reads facial expressions, detects mood, and selects appropriate music from a playlist based on the user's emotional state.
3. **Visualization**: The results, including system performance data and detected moods, are visualized using Matplotlib and saved as graphs.

## 📊 Results

- **Insights**: The project compares the effectiveness of mood detection based on facial expressions and evaluates the performance of the system on different hardware configurations.
- **Improvements**: Identified opportunities for improving the accuracy of mood detection, such as enhancing facial recognition models and incorporating more complex emotional states.
- **Report**: Detailed findings and recommendations are presented in the project report.

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## 📧 Contact

For any questions or discussions, feel free to reach out via [LinkedIn](# 🎵 Music Player Using Mood and Face Detection

This project leverages emotion and face detection to provide a personalized music experience. By analyzing the user's facial expressions and mood, it suggests music that matches their current emotional state. The goal is to create a seamless, mood-based music player that enhances the listening experience.

## 🎯 Objectives
- **Mood and Face Detection**: Analyze the user's facial expressions to determine their current emotional state (happy, sad, relaxed, etc.).
- **Music Recommendations**: Play music that aligns with the detected mood.
- **User Interaction**: Provide an option for users to manually select their mood if desired.
- **Performance Analysis**: Track resource usage and performance of the system.
- **Recommendations**: Propose enhancements to improve mood detection accuracy.

## 🛠 Methodology
1. **Facial Expression Detection**: Real-time analysis of facial features using machine learning algorithms.
2. **Music Classification**: Music is categorized based on mood, and appropriate tracks are played based on detected emotions.
3. **System Data Collection**: Use system performance data (CPU, memory) to ensure efficient processing.
4. **Visualization**: Generate graphs showing resource usage and mood detection performance.

## ⚙️ Tools and Technologies
- **Python**: Core language for implementing the facial recognition and mood detection algorithms.
- **OpenCV**: Used for facial expression recognition.
- **TensorFlow/Keras**: For training models on emotion detection.
- **Spotify API**: Music streaming and recommendation engine.
- **Node.js**: For gathering system performance data.
- **MySQL**: Database for managing user data and mood history.
- **Pandas & Matplotlib**: Data analysis and visualization.
  
## 📦 Installation

### Prerequisites
- Python 3.x
- Node.js
- MySQL

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/music-player-mood-detection.git
    cd music-player-mood-detection
    ```

2. **Install Python dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Install Node.js dependencies**:
    ```bash
    cd js
    npm install
    cd ..
    ```

4. **Set up the MySQL database**:
    - Create a new database.
    - Import the provided SQL script to create necessary tables.
    - Configure the database connection in the Python script:
    ```python
    db_connection = mysql.connector.connect(
        host="your_host",
        user="your_user",
        password="your_password",
        database="your_database"
    )
    ```

5. **Run the JavaScript data collector**:
    ```bash
    node js/collectData.js
    ```

6. **Run the Python script for mood detection and music recommendation**:
    ```bash
    python app.py
    ```

## 📄 Usage

1. **System Data Collection**: The JavaScript script (`collectData.js`) gathers system performance information and writes it to a CSV file (`system_data.csv`).
2. **Mood Detection and Music Playback**: The Python script (`app.py`) reads facial expressions, detects mood, and selects appropriate music from a playlist based on the user's emotional state.
3. **Visualization**: The results, including system performance data and detected moods, are visualized using Matplotlib and saved as graphs.

## 📊 Results

- **Insights**: The project compares the effectiveness of mood detection based on facial expressions and evaluates the performance of the system on different hardware configurations.
- **Improvements**: Identified opportunities for improving the accuracy of mood detection, such as enhancing facial recognition models and incorporating more complex emotional states.
- **Report**: Detailed findings and recommendations are presented in the project report.

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## 📧 Contact

For any questions or discussions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/atul-raj-a1238225a/).



