# ATS Analyser

Live --: https://ats-analyser.streamlit.app/

## Steps to Run the Project

1. **Clone the Repository**: Clone the project repository to your local machine.
   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Set Up a Virtual Environment**: Create and activate a virtual environment.
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**: Install the required Python packages.
   ```sh
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**: Create a `.env` file in the project root directory and add your Google API key.
   ```
   GOOGLE_API_KEY=your_google_api_key
   ```

5. **Run the Streamlit Application**: Start the Streamlit application.
   ```sh
   streamlit run app.py
   ```

6. **Access the Application**: Open your web browser and go to `http://localhost:8501` to access the application.

## Steps to Run the Jupyter Notebook

1. **Install Jupyter Notebook**: If you don't have Jupyter Notebook installed, you can install it using pip.
   ```sh
   pip install notebook
   ```

2. **Run the Jupyter Notebook**: Start the Jupyter Notebook server.
   ```sh
   jupyter notebook
   ```

3. **Open the Notebook**: In the Jupyter Notebook interface, navigate to the `research.ipynb` file and open it.
