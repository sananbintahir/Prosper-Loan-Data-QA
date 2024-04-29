# About The Project

This project uses Text-to-Pandas to execute queries and answer questions about the Prosper Loan Dataset. The dataset is available on Kaggle and can be accessed [here](https://www.kaggle.com/datasets/henryokam/prosper-loan-data/data).

The project uses the LLAMAIndex to execute queries and the TogetherAPI to answer questions. The project also uses the LLAMA 3 70B model to generate the queries and the Arize Phoenix for observability and evaluation.

## Built With

- [LLAMAIndex](https://www.llamaindex.ai/)
- [TogetherAPI](https://api.together.xyz/)
- [LLAMA 3 70B](https://huggingface.co/docs/transformers/main/en/model_doc/llama3)
- [Arize Phoenix](https://phoenix.arize.com/)

## Getting Started

You will need a python environment to run this notebook.

### Prerequisites

- Python 3.12 or higher
- Jupyter Notebook
- TogetherAPI key - you can get one [here](https://api.together.xyz)
- Create a .env file in the root directory and add the following line:

  ```bash
  TOGETHER_API_KEY=your_api_key
  ```

### Installation

```bash
python -m venv llama-index-env   # Create a virtual environment
```

```bash
source llama-index-env/bin/activate
```

```bash
pip install -r requirements.txt   
```

Select the correct kernel in the Jupyter Notebook and run the cells.
