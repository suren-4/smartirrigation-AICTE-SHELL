# Smart Irrigation System

A machine learning-powered smart irrigation system for efficient water management in agriculture.

## Project Overview

This project uses sensor data and predictive modeling to automate irrigation, optimizing water usage and improving crop yield. The system leverages a trained model to determine when and how much to irrigate, based on real-time environmental data.

## Features

- Predictive irrigation scheduling using machine learning
- Data-driven decision making for water conservation
- Easy integration with existing farm infrastructure

## Repository Structure

- `app.py` — Main application script for running the irrigation system.
- `Farm_Irrigation_System.pkl` — Pre-trained machine learning model for irrigation prediction.
- `irrigation_machine.csv` — Sample dataset containing sensor and irrigation data.
- `Irrigation_System.ipynb` — Jupyter notebook for data analysis, model training, and experimentation.
- `README.md` — Project documentation.

## Getting Started

1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/smartirrigation-AICTE-SHELL.git
   cd smartirrigation-AICTE-SHELL
   ```

2. **Install dependencies**
   ```sh
   pip install streamlit
   pip install pyngrok
   ```

3. **Run the application**
   ```sh
   streamlit run app.py
   ```

## Usage

- Use `Irrigation_System.ipynb` to explore the data and retrain the model if needed.
- The main logic is in `app.py`, which loads the model and makes irrigation decisions based on input data.

## Model

The model (`Farm_Irrigation_System.pkl`) is trained on historical irrigation data (`irrigation_machine.csv`). You can retrain or fine-tune the model using the notebook.

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License.

## Acknowledgements

- AICTE Internship Program
- SHELL
