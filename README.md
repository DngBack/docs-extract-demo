# docs-extract-demo

In here, i want to build demo ui ux to test image2text, documents extraction to get information from documents image.

## Description

## To Do List

## Install and run

### Set up

#### Set up env

Using python 3.10.16

```bash
conda create -n doc-extract python==3.10.16 -y

conda activate doc-extract
```

#### Set up pre-commit to format code

    - Install:
    ```bash
    pip install pre-commit
    ```

    - Add pre-commit to git hook:
    ```bash
    pre-commit install
    ```

    - Run pre-commit for formating code (only staged files in git):
    ```bash
    pre-commit run
    ```

    - Run pre-commit for formating code with all files:
    ```bash
    pre-commit run --all-files
