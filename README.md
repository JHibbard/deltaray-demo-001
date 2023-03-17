# ![deltaray-header](./assets/deltaray-header.png)

# Environment Creation and Setup

1. Open a bash shell (if on Windows use git bash, WSL, or any shell configured for bash commands).

2. Clone this repo and navigate to the cloned folder.

3. Create a conda environment from the `environment.yml` file:

    ```shell
    conda env create -f ./envs/environment.yml
    ```

4. Activate conda environment:

    ```shell
    conda activate deltaray-demo-001
    ```

5. Create Jupyterlab kernel from activated environment:

    ```shell
    ipython kernel install --user --name=deltaray-demo-001
    ```

6. Start JupyterLab server:

    ```shell
    jupyter lab
    ```
