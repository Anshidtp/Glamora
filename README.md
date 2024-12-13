# Glamora
An AI powered Fashion Style Assistant

The AI recommends personalized outfits based on your preferences, style trends, and fashion data.

## Requirements:
 * Python 3.8+ or later
 * Streamlit
 * Google Generative AI
 * OPENCLIP Embedding
 * Chroma DB
 * HuggingFace


## Steps To Run

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. **Create and activate a virtual environment:**

    ```bash
    conda activate -n <env_name> python=3.11 -y
    conda activate <env_name>
    ```
    Repalce the <env_name> with the name of your environment 

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**

    Create a `.env` file in the root directory of the project and add Following Details

    ```env
    API_KEY = "Your_Google_API_KEY"
    

    ```

5. **Running the Application:**
    Launch your terminal and execute the following command:

   1.  Run the Data Ingestion Pipeline

        ```bash
        python load_data.py
        ```

   2.  Run the Data Embedding Pipeline
        ```bash
        python embed.py
        ```
        
   3. Run the Application
        ```bash
        streamlit run main.py
        ```
