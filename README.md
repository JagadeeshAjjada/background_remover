# Background Remover
A web app built with Python and Streamlit that removes backgrounds from images using pre-trained ML models.

It works well for most images with simple backgrounds, but don’t expect Photoshop-level results! 😊

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo and navigate to ```background-remover``` directory 
   ```
   git clone git@github.com:JagadeeshAjjada/background_remover.git
   ```
   ```
   cd background_remover
   ```
2. Install required packages (virtual environments recommended)
   ```
   python3 -m venv venv && source venv/bin/activate
   ```
   ```
   pip install -r requirements.txt
   ```
3. Run the app using streamlit
   ```
   streamlit run app.py
   ```
4. Goto http://localhost:8501 on your browser
