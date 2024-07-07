# Medical-Chatbot-with-Advanced-AI-Capabilities

A sophisticated medical chatbot application powered by advanced AI models and natural language processing techniques. This project utilizes the MedQuad dataset, featuring over 43,000 real-life patient inquiries categorized into 31 types of medical questions. Built with a focus on accuracy, efficiency, and user interaction, it aims to provide reliable medical information and support to healthcare professionals and patients alike.

## Features
- Natural Language Understanding: Processes diverse medical queries using the Hugging Face PLM2 model for accurate comprehension.

- Multi-professional Responses: Incorporates responses from doctors, nurses, and pharmacists for comprehensive and reliable information retrieval.

- Customized User Interaction: Tailors responses based on query context and user preferences, enhancing user experience and satisfaction.

- Insights and Analytics: Extracts correlations between treatments, chronic diseases, and medical protocols to provide deeper insights for healthcare research.

## Technologies Used
- LangChain: For data preprocessing and cleaning.
- Chroma: For enhanced visualization and data analytics.
- Hugging Face Transformers: Utilized the PLM2 model for advanced natural language understanding.
- Python: Programming language used for implementation.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/pinilDissanayaka/Medical-Chatbot-with-Advanced-AI-Capabilities.git
cd medical-chatbot
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Run the application:
```
python app.py
```

## Dataset
The [MedQuad dataset](https://www.kaggle.com/datasets/thedevastator/comprehensive-medical-q-a-dataset?resource=download) is used for training and testing the chatbot. It includes a vast collection of medical questions and expert responses, essential for building a robust healthcare AI application.

### Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Special thanks to the creators of the MedQuad dataset for providing valuable medical question-answer pairs.
Inspiration and initial setup guidance from the open-source community.
