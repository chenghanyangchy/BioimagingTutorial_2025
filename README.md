# BioimagingTutorial_2025
IT introduction for BioimagingTutorial (summer 2025)

## Installation of Miniconda

<ol>
<li> Open a web browser and visit https://docs.conda.io/en/latest/miniconda.html.</li>
<li> Download the correct software version for your operating system.</li>
<li> Start the installation and follow the instructions</li>
</ol>

## Create a virtual environment for Python

Windows user should execute conda commands from the anaconda prompt (has been installed together with miniconda).
Linux and macOS users may use their default terminals

<ul>
<li> Windows: From the start menu, search for "Anaconda Prompt" and open it.</li>
<li> macOS and Linux: Open a terminal</li>
</ul>

Execute the following command in your command prompt:

    conda create -n napari python=3.9

Once the virtual environment has been generated, activate it with this command:

    conda activate napari


## Access to BioimagingTutorial_2025 folder and install the requirements

Make sure that your virtual environment is activated.
Execute the following commands in your command prompt:


    cd BioimagingTutorial_2025
    pip install -r requirements.txt


all the required python packages listed in the file "requirements.txt" will be installed.


## Start Jupyter Lab
Start jupyter lab from the console within the bio325_2024 folder:

    jupyter-lab
