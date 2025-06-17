<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Sentinel-2 L2A Interactive Dashboard

[![nightly-build](https://github.com/pritamd47/interactive-sentinel-2/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/pritamd47/interactive-sentinel-2/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/pritamd47/interactive-sentinel-2/main?labpath=notebooks)

This Project Pythia Cookbook provides a recipe for building an interactive dashboard for the Sentinel-2 L2A satellite imagery using the holoviews ecosystem.

## Authors

[Pritam Das](@pritamd47)

### Contributors

<a href="https://github.com/ProjectPythia/interactive-sentinel-2-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/interactive-sentinel-2-cookbook" />
</a>

## Structure

This cookbook currently has one recipe in the Introduction section.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:


1. Clone the `https://github.com/pritamd47/interactive-sentinel-2` repository:

   ```bash
    git clone https://github.com/pritamd47/interactive-sentinel-2.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd interactive-sentinel-2
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate interactive-sentinel-2
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
