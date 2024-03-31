Langchain Linkedin Profile Searcher:
Here's how it works:

1. Input: Users provide a name via our user-friendly Flask-based web application.
2. SerpAPI: The provided name is seamlessly processed by SerpAPI, which scours the internet to locate a corresponding LinkedIn profile.
3. OpenAI API: The transformed data is then fed into OpenAI API, where our custom Langchain agent generates a comprehensive summary. This includes key insights, interesting facts, potential conversation starters, and the individual's interests.

All of these steps are seamlessly orchestrated by our Langchain agent, ensuring a streamlined and efficient process.

Setup:


   ```
1. Create a virtual environment using:
   ```
   pipenv shell
   ```
2. Install necessary libraries:
   ```
   pipenv install
   ```
3. Create an environmental variable file (.env) and link it.
4. Add your API keys for the following APIs:
   - OpenAI API
   - SerpAPI
5. Run the app.py file.

Experience the power of Langchain Profile Summariser