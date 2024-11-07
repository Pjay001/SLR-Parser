# SLR Parser Web Application

This project implements an **SLR (Simple LR) Parser** using Python and the **Streamlit** framework. It provides a web-based interface that allows users to input a **context-free grammar (CFG)** and a sequence of **tokens**, then processes the input through the SLR parsing algorithm. The application visualizes the parsing process, showing the construction of the **FIRST** and **FOLLOW** sets, the **parsing table**, and the step-by-step parsing results.

## Features

- **Grammar Input**: Enter a context-free grammar in standard form (e.g., `S -> A B | C`).
- **Token Input**: Provide a sequence of tokens (e.g., `a b`).
- **SLR Parsing Process**: Visualize the parsing process step-by-step.
- **FIRST and FOLLOW Sets**: Displays the computed FIRST and FOLLOW sets for the grammar.
- **Parsing Table**: Shows the SLR parsing table, which guides the parser’s decisions.
- **Interactive Interface**: User-friendly web interface with error handling and real-time feedback.
- **Error Handling**: Provides detailed messages if the input format is incorrect.

## Requirements

- Python 3.7+
- Streamlit
- Graphviz
- pandas (for data manipulation)
- Required libraries can be installed via `requirements.txt`.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Pjay001/SLR-Parser.git
    cd slr-parser-streamlit
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Running the Application

To run the Streamlit app, execute the following command:

```bash
streamlit run app.py
