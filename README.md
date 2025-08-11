# LangSmith Evaluation Quick Start

This project demonstrates how to evaluate language model responses using LangSmith's evaluation framework. It provides a simple example of setting up evaluation for a question-answering system.

## Features

- Create and manage evaluation datasets in LangSmith
- Define custom evaluation metrics
- Run evaluations on language model responses
- Analyze evaluation results

## Prerequisites

- Python 3.8+
- LangSmith account and API key
- OpenAI API key

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/jameskanyiri/LangSmith-Evaluation-Quick-Start.git
   cd LangSmith-Evaluation-Quick-Start
   ```

2. Install dependencies using UV (recommended):
   ```bash
   # Install UV if you haven't already
   curl -sSf https://astral.sh/uv/install.sh | sh
   
   # Create and activate virtual environment
   uv venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   
   # Install dependencies
   uv sync
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Add your LangSmith and OpenAI API keys to the `.env` file

## Project Structure

- `noteboook/evaluation_quick_start.ipynb`: Jupyter notebook containing the evaluation workflow
- `pyproject.toml`: Project dependencies and configuration
- `.env`: Environment variables (not committed to version control)

## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook noteboook/evaluation_quick_start.ipynb
   ```

2. Follow the notebook to:
   - Create a dataset of example questions and reference answers
   - Define your evaluation function
   - Run evaluations on your language model
   - Analyze the results

## Evaluation Metrics

The example includes basic evaluation metrics, but you can customize these based on your needs:

- Exact match comparison
- Semantic similarity
- Custom scoring functions

## Contributing

Feel free to submit issues and enhancement requests. Pull requests are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [LangSmith Documentation](https://docs.smith.langchain.com/)
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)
