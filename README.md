**2020**: [GitHub](https://github.com/astropgh/astropgh-boot-camp-2020) / [website](https://astropgh.github.io/astropgh-boot-camp-2020/) (inc., Astropy, Pandas, Altair, Git/Github, linear regression, resampling, and debugging)

**2021**: [GitHub](https://github.com/astropgh/python-boot-camp-2021) / [website](https://astropgh.github.io/python-boot-camp-2021/) (inc., Astropy and Pandas)

**2022**: [GitHub](https://github.com/astropgh/python-boot-camp-2022) / [website](https://astropgh.github.io/python-boot-camp-2022/) (inc., Astropy and Pandas)

**2023**: [GitHub](https://github.com/astropgh/python-boot-camp-2023) / [website](https://astropgh.github.io/python-boot-camp-2023/)

**2024**: [GitHub](https://github.com/astropgh/python-boot-camp-2024) / [website](https://astropgh.github.io/python-boot-camp-2024/)

Welcome to the 2024 AstroPGH Python Boot Camp for summer undergraduate students and early PhD students new to Python.  This 3 day program is designed to help you learn the basics of using Python for astrophysics and physics research.


## Boot Camp
### Installation and Setup
#### Python
Please install Python 3 before the Boot Camp. I recommend using the [Anaconda](https://www.anaconda.com/products/individual) package manager **_for Python 3.12_**. Here are Anaconda installation guides:
- [Windows](https://conda.io/projects/conda/en/stable/user-guide/install/windows.html)
- [macOS](https://conda.io/projects/conda/en/stable/user-guide/install/macos.html)
- [linux](https://conda.io/projects/conda/en/stable/user-guide/install/linux.html)


Next you need to start conda (which depends on your OS), so I suggest following this guide: [How to start Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html#starting-conda)


Then install the following packages by copy and pasting the following lines into the Anaconda prompt (search for ''Anaconda Navigator'') or terminal:
```bash
conda install numpy scipy pandas matplotlib astropy jupyter ipython
conda install -c conda-forge jupyterlab
pip install ipympl
```

If you have trouble with installing Jupyter Lab, see [Jupyter Lab installation guide](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html).

From the Anaconda prompt or terminal, launch Jupyter Lab (see [Staring Jupyter Lab guide](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) for more details):
```bash
jupyter lab
```

#### Test Your Conda Installation

1. Open a new Anaconda prompt or terminal.
2. Type `ipython` into the terminal to open an interactive python session (the prompt should say `In [1]:`).
3. Copy this code:
```python
import numpy
import scipy
import matplotlib
import astropy
import pandas
```
4. Type into the iPython shell the word `paste`, and press enter.
5. If no errors are raised, you're ready for bootcamp. You may close the terminal window.

If you are having difficulties with installation, please do not hesitate to reach out to Brett Andrews on Slack or via email.

### Instructors
- [Helena Richie](https://helenarichie.github.io/): Python Basics
- [Morgana Iacocca](https://morganafayeiacocca.github.io/): Data Structures, Functions and Modules
- [Brett Andrews](https://bretthandrews.github.io/): Organizer, Matplotlib
- Julissa Sarmiento: Numpy 1a
- Finian Ashmead: Numpy 1b
- [Ashod Khederlarian](https://ashodkh.github.io/): Numpy 2a
- [Sedona Price](https://sedonaprice.github.io/): Numpy 2b
- Cullen Abelson: Numpy 3a
- [Collin McLeod](https://collinmcleod.github.io/): Numpy 3b
- Chris Hernandez: Numpy 4a
- [Yoki Salcedo](https://yoquelbinsalcedo.github.io/): Numpy 4b

### Schedule

| Time (EDT) | Monday (5/20) | Tuesday (5/21) | Wednesday (5/22) |
|:-----:|:-----:|:-----:|:-----:|
| 10:00-11:15 | Python Basics | Numpy 1a | Numpy 3a |
| 11:45-1:00 | Data Structures | Numpy 1b | Numpy 3b |
| 2:00-3:15 | Functions and Modules | Numpy 2a | Numpy 4a |
| 3:45-5:00 | Matplotlib | Numpy 2b | Numpy 4b |


<a href="url"><img style="padding: 0px 20px;" src="https://github.com/astropgh/python-boot-camp-2021/blob/main/etc/NSF_4-Color_bitmap_Logo.png?raw=true" align="left" height="128" width="128"></a>

This material is based upon work supported by the National Science Foundation grant number AST-2009251. Any opinions, findings, and conclusions or recommendations expressed on this website are those of the participants and do not necessarily reflect the views of the National Science Foundation or the participating institutions.
