# Setting up a local environment to run the code

## Prerequisites

Absolutely necessary:

- [Python](https://www.python.org/downloads/)

- [Git](https://git-scm.com/downloads)

Suggested:

- [VSCode](https://code.visualstudio.com/download)

## Local setup

1. Open your folder of choice in a terminal (e.g. PowerShell)

2. Clone this repo:
    ```shell
    git clone https://github.com/harrow-css/2023-multithreading/
    ```

3. Go into the `2023-multithreading/ai` directory:
    ```shell
    cd 2023-multithreading/ai
    ```

4. Create a new Python environment:
    ```shell
    python -m venv .venv
    ```

5. Activate your new Python environment:
    ```shell
    .venv/Scripts/Activate.ps1
    ```

6. Install required Python packages:
    ```shell
    pip install -r requirements.txt
    ```

7. **[Optional if using VSCode]** Register a notebook kernel:
    ```shell
    python -m ipykernel install --user --name="2023.3-ai-thread"
    ```

## In the future

To sync your local copy of the code with Vincent's version, run: `git pull origin`

Once you've set things up, every time you want to run an example, just do the following:

1. Activate your new Python environment:
    ```shell
    .venv/Scripts/Activate.ps1
    ```

2. Go into the relevant week. For example, to access code examples for week 2:
    ```shell
    cd week-2
    ```

3. Depending on the filetype, do one of:
    - For Python files with a name in the format of `<filename>.py`, run:
        ```shell
        python <filename>.py
        ```
    - For IPython notebooks with a name in the format of `<filename>.ipynb`, run:
        ```shell
        jupyter lab
        ```
