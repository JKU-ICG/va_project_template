# Visual Analytics Lab Project
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to github for the first and the final deadline.
Change/extend the corresponding sections by replacing the [TODO] markers.
*In order to meet the deadlines make sure you push everything to your Github repository.*
For more details see [Visual Analytics Moodel page](https://moodle.jku.at/jku/course/view.php?id=20471).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information
*Due on 02.12.2022.*

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

[TODO]

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


## Final Submission
*Due on 16.01.2023.*

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your final executed notebooks as html and add them to your repository.  
  Select 'File' -> 'Export Notebook As...' -> 'Export Notebook to HTML'
