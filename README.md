

 Named Entity Recognition (NER) App

This is a simple web application built using Streamlit and spaCy to perform Named Entity Recognition (NER) on user-inputted text. The app highlights and classifies named entities such as persons, organizations, locations, dates, and more.

 Features

* Input any block of English text.
* Detect and highlight named entities in real-time.
* Uses spaCy's pre-trained model `en_core_web_sm`.
* Clean and interactive web interface via Streamlit.

 Demo

![NER Demo](https://github.com/yourusername/ner-app/assets/demo.gif)

(Optional: Add a real screenshot or GIF if hosted)

 Installation

 1. Clone the Repository

bash
git clone https://github.com/yourusername/ner-app.git
cd ner-app


 2. Create a Virtual Environment (Optional but Recommended)
bash
python -m venv venv
source venv/bin/activate  On Windows use: venv\Scripts\activate


 3. Install Dependencies

bash
pip install -r requirements.txt


If `requirements.txt` is not available, install manually:
`bash
pip install streamlit spacy
python -m spacy download en_core_web_sm




  Run the App
 bash
streamlit run NER.py


Then open your browser at: `http://localhost:8501`


 Project Structure


ner-app/
│
├── NER.py                # Main Streamlit app
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies (optional)




 About spaCy's NER

spaCy’s `en_core_web_sm` model supports recognition of the following entities:

* `PERSON` – People, including fictional.
* `ORG` – Organizations.
* `GPE` – Countries, cities, states.
* `DATE`, `TIME`, `MONEY`, `LOC`, etc.



