# Allen Coral Atlas Coding Tutorials

This repository contains interactive coding tutorials for the [Allen Coral Atlas](https://allencoralatlas.org).  These tutorials provide concrete examples of how Allen Coral Atlas map data can be downloaded, analyzed, and visualized programmatically.

### Requirements

These tutorials are written in Python and run in [Jupyter Notebooks](https://jupyter-notebook.readthedocs.io/en/latest/index.html).  If you're using a Mac, the easiest way to get started is:

1. Install [Anaconda](https://docs.anaconda.com/)
1. Create the Conda environment with the environment file included with these tutorials
    ```
    conda create --name tutorials --file aca-tutorials-conda-env-osx-64.txt
    ```
1. Activate the Conda environment
    ```
    conda activate tutorials
    ```
1. Start the Jupyter notebook
    ```
    jupyter notebook
    ```

If you're using Windows or Linux, you can still use Anaconda, but install the dependencies using the included `requirements.txt` file instead.

If you'd prefer not to use Anaconda, required dependencies can be installed manually using [pip](https://packaging.python.org/tutorials/installing-packages/).

These tutorials were tested on Mac OS 11.3, with Anaconda 4.10.1 running Python 3.7.7.

### Tutorials

Tutorial notebooks demonstrate use of the Allen Coral Atlas's Web Map Service (WMS) for data exploration and are located in the `WMS/` directory.

#### EEZ Percent Distribution Tutorial

The `eez_percent_distribution_tutorial.ipynb` notebook demonstrates how to calculate and visualze the distribution of different benthic and geomorphic habitat classes in the exclusive economic zone (EEZ) of Tonga.

#### Marine Protected Areas Percent Distribution Tutorial

Similar to the previous totorial, the `protected_areas_tutorial.ipynb` notebook retrieves benthic and geomorphic habitat data for the Tonga EEZ, but also computes and visualizes the distribution of habitat data both inside and outside established Marine Protected Areas (MPAs).

#### Acknowledgements

Many thanks to our outstanding intern [Diana Nguyen](https://github.com/dnguye2) for creating these tutorials.
