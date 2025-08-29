# Notes

## Create a new app

1. Create a new folder
2. Add the following files: `.env, requirements.txt, app.py`
3. Add API key to `.env` file: `GROQ_API_KEY=your-api-key`
3. Add list of dependencies to requirements.txt
```
streamlit 
langchain 
langchain-core 
langchain-community 
langchain-groq 
python-dotenv
langchain-tavily
```

4.Open a terminal/powershell or gitbash and change directory to your new folder:
`cd new-directory-name` 
5. Create a new virtual environment:
`python -m venv .venv`
6. Activate virtual environment:
Windows:`.\.venv\bin\activate` Mac: `source .venv/bin/activate`
7. Install dependencies: `pip install -r requirements.txt`
8. Start building your app!
9. Run the app: `python app.py` or `streamlit run app.py`


Product Name: NIKE SHOES 
Company URL: https://www.nike.com/ The URL of the company you are targeting. (Use this to derive the company ID and other metadata.) 
Product Category: SHOES This could be one word or a sentence (e.g., "Data Warehousing" or "Cloud Data Platform"). The LLM should identify the category from the description. 
Competitors: https://www.asics.com/us/en-us/
https://www.newbalance.com/
https://us.puma.com/us/en/
https://hoka.com/en/us



URLs of competitors (similar to the company URL input). 
Value Proposition: “Nike empowers every athlete with innovative, high-performance products that blend cutting-edge technology, style, and inspiration.”A sentence summarizing the product’s value. 
Target Customer: Chad Howard Name of the person you are trying to sell to. 
Optional: Upload a product overview sheet or deck. The system should parse through this document to extract more insights into the product. 