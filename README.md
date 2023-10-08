# Guidance

There are 3 files you can execute to learn more about Guidance.

1. [simple-example.py](simple-example.py): Shows you how a simple call is implemented.

2. [my-tutorial.ipynb](my-tutorial.ipynb): Notebook that shows you various features of guidance.

3. [app.py](app.py): Small app built with Guidance 

## Run locally

To run the `app.py` script locally, follow these steps:

1. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

2. Create a `.env` file in the root directory of the project and add the necessary environment variables. For example:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```
   Replace `your_openai_api_key` with your actual OpenAI API key.

3. Start the application by running the following command:
   ```
   streamlit run app.py
   ```

4. Open your web browser and navigate to `http://localhost:8502` to access the application.
