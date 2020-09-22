# Visual Analytics Lab Project 2020/21
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to github for the first and the final deadline.
Change/extend the corresponding sections by replacing the [TODO] markers.
*In order to meet the deadlines make sure you push everything to your Github repository.*
For more details see [_Lab Project_ document in the Google Drive folder](https://www.cg.jku.at/teaching/visualanalytics/slides).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information
*Due on 07.12.2020.*

### Group Members

| Student ID    | First Name  | Last Name      |
| --------------|-------------|----------------|
| [TODO]        | [TODO]      | [TODO]         |
| [TODO]        | [TODO]      | [TODO]         |
| [TODO]        | [TODO]      | [TODO]         |
| [TODO]        | [TODO]      | [TODO]         |

### Dataset

* What is the dataset about?
* Where did you get this dataset from (i.e., source of the dataset)?

[TODO]

## Usage

### Locally
Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/va-project-2020-<GROUP_NAME>.git
cd va-project-2020-<GROUP_NAME>
```

Create a new environemnt and install the packages needed in the tutorial:

```shell
conda create --name va-project
conda activate va-project
conda install -c conda-forge --yes --file requirements.txt
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should open a new tab with url http://localhost:8888/ and display the tutorial files.

### MyBinder
Go to: https://mybinder.org/ and paste your repository url to work online.
MyBinder installs the dependencies specified inside of the `requirements.txt` for you.

Note: MyBinder can not save to your repository, you need to download the notebooks and update the repository yourself!

## Final Submission
*Due on 18.01.2021.*

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *requirements.txt* file if you need additional libraries, otherwise the code is not executeable.
* Save your final executed notebooks as html (File > Download as > HTML) and add them to your repository.
