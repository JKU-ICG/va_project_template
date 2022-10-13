# Visual Analytics Lab Project
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to GitHub.
Change/extend the corresponding sections by replacing the [TODO] markers.

For a detailed project spezification look up the [Visual Analytics Moodel page](https://moodle.jku.at/jku/course/view.php?id=20471).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information

### Group Members

| Student ID    | First Name  | Last Name      | E-Mail | Workload [%]  |
| --------------|-------------|----------------|--------|---------------|
| [TODO]        | [TODO]      | [TODO]         |[TODO]  |[TODO]         |
| [TODO]        | [TODO]      | [TODO]         |[TODO]  |[TODO]         |
| [TODO]        | [TODO]      | [TODO]         |[TODO]  |[TODO]         |
| [TODO]        | [TODO]      | [TODO]         |[TODO]  |[TODO]         |

### Dataset

* What is the dataset about?
* Where did you get this dataset from (i.e., source of the dataset)?
* How big is the dataset?

**Description:**
[TODO]


## General Submission Information

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your executed submission notebooks as HTML and add them to your repository.  
  * Select 'File' -> 'Export Notebook As...' -> 'Export Notebook to HTML'
* Upload the exported HTML file on Moodle, if it is required for the submission.

## Usage

### Locally
Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/va-project-2022-<GROUP_NAME>.git
cd va-project-2022-<GROUP_NAME>
```

Load the conda environment from the `environment.yml` file, if you haven't already in previous assignments:

```sh
conda env create -f environment.yml
```

Activate the loaded conda environment:

```sh
conda activate python-tutorial
```

Install Jupyter Lab extension to use *ipywidgets* in JupyterLab:

```sh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should open a new tab with url http://localhost:8888/ and display the tutorial files.



