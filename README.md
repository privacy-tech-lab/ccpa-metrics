<p align="center">
  <a href="https://nbviewer.jupyter.org/github/privacy-tech-lab/gpc-ccpa-metrics/blob/main/gpc-ccpa-metrics.ipynb"><img alt="nbviewer" src="https://img.shields.io/badge/jupyter_notebooks-nbviewer-purple.svg"></a>
  <a href="https://github.com/privacy-tech-lab/gpc-ccpa-metrics/commits/main"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/privacy-tech-lab/gpc-ccpa-metrics"></a>
  <a href="https://github.com/privacy-tech-lab/gpc-ccpa-metrics/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/privacy-tech-lab/gpc-ccpa-metrics"></a>
  <a href="https://github.com/privacy-tech-lab/gpc-ccpa-metrics/issues?q=is%3Aissue+is%3Aclosed+"><img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed-raw/privacy-tech-lab/gpc-ccpa-metrics"></a>
  <a href="https://github.com/privacy-tech-lab/gpc-ccpa-metrics/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/privacy-tech-lab/gpc-ccpa-metrics"></a>
  <a href="https://github.com/privacy-tech-lab/gpc-ccpa-metrics/watchers"><img alt="GitHub watchers" src="https://img.shields.io/github/watchers/privacy-tech-lab/gpc-ccpa-metrics?style=social"></a>
  <a href="https://github.com/privacy-tech-lab/gpc-ccpa-metrics/stargazers"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/privacy-tech-lab/gpc-ccpa-metrics?style=social"></a>
  <a href="https://github.com/privacy-tech-lab/gpc-ccpa-metrics/network/members"><img alt="GitHub forks" src="https://img.shields.io/github/forks/privacy-tech-lab/gpc-ccpa-metrics?style=social"></a>
</p>

# GPC CCPA Metrics and Visualizations

**Note**: Under development.

## View Metrics and Visualizations

This repo contains CCPA metrics and visualizations. To see the data and code, check the [readme](https://github.com/privacy-tech-lab/gpc-ccpa-metrics/blob/main/gpc-ccpa-metrics.ipynb) or the [Jupyter nbviewer](https://nbviewer.jupyter.org/github/privacy-tech-lab/gpc-ccpa-metrics/blob/main/gpc-ccpa-metrics.ipynb).

## Development

The data is analyzed with Python 3 on a Jupyter Notebook. To recreate the Notebook locally, clone this repo.

```bash
git clone https://github.com/privacy-tech-lab/gpc-ccpa-metrics.git
```

Install Jupyter Notebook.

```bash
pip3 install jupyter
```

Install the dependencies of the GPC CCPA Metrics Notebook.

```bash
pip3 install numpy
pip3 install pandas
pip3 install mathplotlib
```

Start your local GPC CCPA Metrics Notebook from within the directory to which you cloned the repo.

```bash
jupyter notebook
```

This command will start up Jupyter and your default browser should display the Notebook at <http://localhost:8888/tree>.

## Contribution

Contribute by opening an issue or pull request.

All code is contained in gpc-ccpa-metrics.ipynb and you can modify it once you created a local copy as described in the Development section.
All data is contained in the csv file.
