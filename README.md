# Assignment-9

# House Price Prediction

This is a web application for predicting house prices using a machine learning model. The application is built with Flask and deployed on Google Cloud Platform (GCP).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
   ```

2. **Create a virtual environment:**
   ```bash
   python3.12 -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Ensure the trained model file `model.pkl` is present in the root directory.**

## Usage

1. **Run the Flask application locally:**
   ```bash
   python main.py
   ```

2. **Open your browser and go to:**
   ```
   http://127.0.0.1:8080
   ```

3. **Enter the features and click on "Predict" to get the house price prediction.**

## Deployment

### Deploying to Google Cloud Platform (GCP)

1. **Install and initialize the Google Cloud SDK:**
   ```bash
   curl https://sdk.cloud.google.com | bash
   exec -l $SHELL
   gcloud init
   ```

2. **Navigate to the project directory:**
   ```bash
   cd /path/to/project-root
   ```

3. **Deploy the application:**
   ```bash
   gcloud app deploy
   ```

4. **View your application in the browser:**
   ```bash
   gcloud app browse
   ```

## File Structure

```
/project-root
    /static
        /css
            style.css
        /js
            script.js
        index.html
    main.py
    app.yaml
    requirements.txt
    model.pkl
```

- **`main.py`**: The main Flask application file.
- **`app.yaml`**: Configuration file for Google App Engine.
- **`requirements.txt`**: Python dependencies.
- **`static/index.html`**: HTML file for the web interface.
- **`static/css/style.css`**: CSS file for styling the web interface.
- **`static/js/script.js`**: JavaScript file for client-side logic.
- **`model.pkl`**: Pre-trained machine learning model.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```

### Save this content as `README.md` in the root directory of your project.

This `README.md` file provides an overview of the project, instructions for installation, usage, and deployment, a description of the file structure, and guidelines for contributing. If you need any further customization or details, feel free to let me know!
