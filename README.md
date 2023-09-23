# Databricks_LLM101x

This project contains the lab notebooks from course: Large Language Models: Application through Production by Databricks

## Modules

1. LLMs with Hugging Face
2. Embeddings, Vector DBs, and Search
3. Building LLM Chains
4. LLM Evaluation

## Usage

To run Databricks' labs you can leverage Docker with the instructions below:

1. For first time usage, you need to build the Docker image:

    ```bash
    docker compose build .
    ```

2. After that you can start the container with:

    ```bash
    docker compose up -d
    ```

3. Go to Docker desktop, to retrieve your jupyterlab access URL.

    - Click the container name, to open the logs.
    - Retrive the jupyterlab URL, it should look like: `http://127.0.0.1:8888/lab?token=4150032f3603c85febf54b8b40bb761a2eb46e2fb593d5dc`

    ![image](https://github.com/kevinknights29/Airflow_Docs_LLM_App/assets/74464814/661f3747-2b2e-4387-9c79-64af1d8bc56e)

4. To stop the container, run:

    ```bash
    docker compose down
    ```
