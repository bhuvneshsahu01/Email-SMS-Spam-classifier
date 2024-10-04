# SMS/Email Spam Classifier

This project is a simple web application for classifying SMS or email messages as spam or ham (non-spam). It utilizes machine learning techniques, specifically a Naive Bayes classifier, trained on a dataset of labeled messages. The application is built using Streamlit and provides an interactive interface for users to input messages and receive predictions.
try it yourself https://email-sms-spam-classifier-y.streamlit.app/

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- User-friendly interface to input SMS or email messages.
- Predicts whether the input message is spam or ham.
- Displays prediction results clearly.
- Supports natural language processing (NLP) for text preprocessing.

## Technologies Used

- Python
- Streamlit
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Pickle (for model serialization)

## Model Performance

The following table shows the performance comparison of various models used in this project:

| Model                | Accuracy | Precision | Recall | F1-Score |
|----------------------|----------|-----------|--------|----------|
| Naive Bayes          | 95%      | 94%       | 96%    | 95%      |
| Logistic Regression   | 93%      | 92%       | 94%    | 93%      |
| Random Forest         | 94%      | 93%       | 95%    | 94%      |

## Screenshots

Below are some screenshots of the application showcasing the interface and performance comparisons of different models.

### Model Performance Comparison
![Model Performance Comparison](path/to/your/model_performance_comparison_screenshot.png)

### App Interface
![App Interface](path/to/your/app_interface_screenshot.png)

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/bhuvneshsahu01/Email-SMS-Spam-classifier.git
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Download the required NLTK resources (optional if already done):

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

## Usage

1. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to `http://localhost:8501`.

3. Enter a message in the text area and click the "Predict" button to see if it is spam or not.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
