# instructor-search-metadata-demo
Demo using instructor to extract metadata from search queries

## Setup

### Secrets

Create a `.env` file in the root of the repository with the following content:

1. set LLM-specific environment variables in the `.env` file as explained here: https://litellm.vercel.app/#basic-usage
2. if you are using Langfuse, set up the environment variables as explained here: https://langfuse.com/docs/get-started

Afterwards, your `.env` might look like this (using Azure OpenAI and Langfuse):

```
AZURE_API_KEY = ""
AZURE_API_BASE = ""
AZURE_API_VERSION = ""
LANGFUSE_SECRET_KEY = ""
LANGFUSE_PUBLIC_KEY = ""
LANGFUSE_HOST = ""
```

### Python

1. Clone the repository
2. Create a Python virtual environment
3. Install the requirements: `python -m pip install -r requirements.txt`


## Execution 

Run through the Jupyter notebook `instructor_search_metadata_demo.ipynb`. Do the suggested exercises.

## Feedback

Please open an issue if you have any questions, feedback or suggestions.
