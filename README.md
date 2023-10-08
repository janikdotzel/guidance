# Guidance

There are 3 files you can execute to learn more about Guidance.

1. [simple-example.py](simple-example.py): Shows you how a simple call is implemented.

2. [my-tutorial.ipynb](my-tutorial.ipynb): Notebook that shows you various features of guidance.

3. [app.py](app.py): Content Generator app built with Guidance 

## Content Generator

The Content Generator (`app.py`) is a tool built with Guidance that allows you to generate various types of content. 
It provides the following generators:

1. Prompt Generator: Generates a prompt based on a given query.

2. Chart Generator: Generates a chart based on data input.

3. Story Generator: Generates a story based on a given query.

4. Email Generator: Generates a response to a customer email.

5. Image Generator: Generates an image based on a prompt.


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
