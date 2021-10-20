# Visual Analytics Lab Project 2020/21
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to github for the first and the final deadline.
Change/extend the corresponding sections by replacing the [TODO] markers.
*In order to meet the deadlines make sure you push everything to your Github repository.*
For more details see [Visual Analytics Moodel page](https://moodle.jku.at/jku/course/view.php?id=15596).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information
*Due on 07.12.2021.*

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
git clone https://github.com/jku-icg-classroom/va-project-2021-<GROUP_NAME>.git
cd va-project-2021-<GROUP_NAME>
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

### MyBinder
Go to: https://mybinder.org/ and paste your repository url to work online.
MyBinder installs the dependencies specified inside of the `environment.yml` for you.

By default, it will launch to Jupyter Notebook, but you can switch to Jupyter Lab by simply appending `?urlpath=lab` to the URL.

Note: MyBinder can not save to your repository, you need to download the notebooks and update the repository yourself!

## Final Submission
*Due on 17.01.2022.*

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your final executed notebooks as html and add them to your repository.  
  Select 'File' -> 'Export Notebook As...' -> 'Export Notebook to HTML'
