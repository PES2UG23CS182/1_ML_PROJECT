Project Title:
Traffic Flow Prediction with Machine Learning

Team: <br>
Diya Chandrashekhar (PES2UG23CS182)<br>
Eshwar R A (PES2UG23CS188)

Project Description: <br>
This project predicts vehicle counts at city junctions using historical traffic data and advanced machine learning algorithms. The workflow includes data cleaning, feature engineering, model training (Neural Network, Decision Tree, Random Forest, K-Nearest Neighbors, Spiking Neural Network), ensemble learning, and visualization. An interactive Gradio dashboard lets users input junction/time info and get predictions from all models for side-by-side comparison.​

Prerequisites:
Python 3.8+<br>
pip for package installation
<br>

Main Dependencies:<br>
Install the following packages:<br>
  -pandas<br>
  -numpy<br>
  -scikit-learn<br>
  -torch<br>
  -snntorch<br>
  -matplotlib<br>
  -gradio<br>
<br>
Installation Steps:<br>
-Clone the Repository<br>
-Install Python Libraries (pip install pandas numpy scikit-learn torch snntorch matplotlib gradio)<br>
-Prepare the Data. Place your data file (traffic.csv) in the root directory.<br>


Running the Project:<br>
1. Run Model Training and Evaluation<br>
Execute the main Python script to preprocess data, train models, and generate performance visualizations.

2. Launch the Gradio Dashboard<br>
Input junction, month, day, and hour to see predictions from all individual models and ensemble methods.

3. View Outputs<br>

Key Features:<br>
-End-to-end pipeline: Data loading, preprocessing, training, visualization, and prediction are fully automated.
-Multiple model support (NN, DT, RF, KNN, SNN) and stacking/weighted ensemble integration.
-Early stopping and best-model selection.
-User-friendly Gradio interface for predictions.

Contact:<br>
For questions, open an issue or email: [eshwarra5@gmail.com] | [diyac.1005@gmail.com]
