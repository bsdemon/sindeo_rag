# sindeo_rag
Sindeo RAG

## Instalation

1. Install system requirements
    ```bash
    sudo dnf install gcc gcc-c++ make
    ```
    or on debian base systems:
    ```bash
    sudo apt install build-essential
    ```

1. Install UV packet manager
    ```bash
    pip install uv
    ```

1. Clone project
    ```bash
    git clone https://github.com/bsdemon/sindeo_rag
    ```

1. Create vitual environment
    ```bash
    cd sindeo_rag
    uv venv
    source .venv/bin/activate
    ```

1. Install requirements
    ```bash
    uv sync
    ```

1. Install precomit hooks
    ```bash
    pre-commit install
    ```
