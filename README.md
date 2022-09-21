## Setup

1. `export PROJECT_NAME=<my-project-name>`

3. Change the Python version in `environment.yml` to suit your needs.

4. Replace `conda` commands below with `mamba` if you have it installed for increased speed.

    ```
    mkdir $PROJECT_NAME
    touch $PROJECT_NAME/__init__.py
    conda env create -f environment.yml -n $PROJECT_NAME
    conda activate $PROJECT_NAME
    poetry init
    ```

5. Use correct Python version during `poetry init`.

6. Replace this `README.md` with your own.

7. Install `pip` packages with `poetry add <package>`

8. Install `conda`-only packages with `conda install <package>` & update the `environment.yml`.