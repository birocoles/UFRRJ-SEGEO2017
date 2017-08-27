# Métodos potenciais e suas aplicações

[Vanderlei C. Oliveira Jr.](http://www.pinga-lab.org/people/oliveira-jr.html)
([*Observatório Nacional*](http://www.on.br/index.php/pt-br/))

Apresentação feita na XXVII Semana de Estudos Geológicos da [Universidade
Federal Rural do Rio de Janeiro](http://portal.ufrrj.br/).

### Resumo

Em breve


### Reproducing the results

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    git clone https://github.com/birocoles/UFRRJ-SEGEO2017.git


All source code used to generate the results and figures in the paper are in
the `code` folder. The sources for the manuscript text and figures are in `manuscript`.
See the `README.md` files in each directory for a full description.

The calculations and figure generation are all run inside
[Jupyter notebooks](http://jupyter.org/).
You can view a static (non-executable) version of the notebooks in the
[nbviewer](https://nbviewer.jupyter.org/) webservice:

http://nbviewer.jupyter.org/github/birocoles/UFRRJ-SEGEO2017

See sections below for instructions on executing the code.


### Setting up your environment

You'll need a working Python **2.7** environment with all the standard
scientific packages installed (numpy, scipy, matplotlib, etc).  The easiest
(and recommended) way to get this is to download and install the
[Anaconda Python distribution](http://continuum.io/downloads#all).
Make sure you get the **Python 2.7** version.

Use `conda` package manager (included in Anaconda) to create a
[virtual environment](https://conda.io/docs/using/envs.html) with
all the required packages installed.
Run the following command in this folder (where `environment.yml`
is located):

    conda env create

To activate the conda environment, run

    source activate ellipsoids

or, if you're on Windows,

    activate ellipsoids

This will enable the environment for your current terminal session.
After running the code, deactivate the environment with the following
commands:

    source deactivate

or, if you're on Windows,

    deactivate


**Windows users:** We recommend having a bash shell and the `make` installed
to run the code, produce the results and check the code. You may download the
[*Git for Windows*](https://git-for-windows.github.io/) and the
[*Software Carpentry Windows Installer*](https://github.com/swcarpentry/windows-installer/releases).


### Running the code

To execute the code in the Jupyter notebooks, you must first start the
notebook server by going into the repository folder and running:

    jupyter notebook

Make sure you have the `conda` environment enabled first.

This will start the server and open your default web browser to the Jupyter
interface. In the page, go into the `code` folder and select the
notebook that you wish to view/run.

The notebook is divided into cells (some have text while other have code).
Each cell can be executed using `Shift + Enter`.
Executing text cells does nothing while executing code cells runs the code
and produces it's output.
To execute the whole notebook, run all cells in order or use "Cell -> Run All"
from the menu bar.


### Licença

Todo o conteúdo deste repositório está disponibilizado sob a [BSD 3-Clause](https://github.com/birocoles/UFRRJ-SEGEO2017/blob/master/LICENSE).
