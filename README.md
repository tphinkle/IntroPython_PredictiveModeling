# CSU-LA/NASA DIRECT-STEM data science workshop
## Introduction to Python and Predictive Modeling

- Instructor: Preston Hinkle ( **email:** thinkle at uci dot edu)
- TAs:
	- 
	- 
	- 
	- 



# Schedule

## Day 1

| Time                       | Activity                                                                    |
| -------------------------- |:----------------------------------------------------------------------------|
| **9:30-10:00 am**          | Sign-in + coffee                                                            |
| **10:00-10:30 am**           | Introductions and course overview                                           |
| **10:30-12:00 pm**          | __Session 1.1__: Coding warm-up                                      |
| **12:00-1:30 pm**          | Lunch
| **1:30-3:00 pm**           | __Session 1.2__: Python's scientific computing infrastructure               |
| **3:00-3:15 pm**           | Break                                                                |
| **3:15-5:00 pm**           | __Session 1.3__: Introducing/loading the data sets for __Session 2__        |

## Day 2

| Time                       | Activity                                                                    |
| -------------------------- |:----------------------------------------------------------------------------|
| **09:30-10:00 am**          | Coffee                                                                      |
| **10:00-12:00 am**           | __Session 2.1__: Linear regression                             |
| **12:00-1:30 pm**          | Lunch                                                                       |
| **1:30-3:00 pm**          | __Session 2.2__: Logistic regression                             |
| **3:00- pm**           | __Session 2.3__: Intro to version control w/ git and closing remarks                        |


# Python download & installation instructions

- For this workshop we will be using the Anaconda distribution of Python 3.6
- Follow these instructions to download and install Python on your local machine, **even if you already have Python installed!**
- If you *really* think you don't need to install Python, please ask first :)

## Workshop preliminaries
1. Go to the [Anaconda download page](https://www.continuum.io/downloads)
2. Click on the link to download **Python 3.6** for your system
	- Make sure you grab the correct version for your operating system! Ask if you have any questions
3. Install Anaconda
4. Install Python packages
	- Windows:
		- Open the **Anaconda Prompt** application
		- Enter `conda update conda`
		- Enter `conda install anaconda`

	- Mac and Linux:
		- Open the shell/terminal
		- Enter `conda update conda`
		- Enter `conda install anaconda`
5. Download the workshop repository from the [github repo](https://github.com/tphinkle/IntroPython_PredictiveModeling)
6. Using your terminal (Mac/Linux) or the Anaconda Prompt (Windows), `cd` to wherever you saved the repository
7. Open Jupyter notebook by typing `jupyter notebook`
8. Click on test_notebook.ipynb to open the test notebook
9. Follow the instructions in the notebook. Contact your instructor if there is an error.


# Convert Jupyter to HTML slideshow
ipython nbconvert your_slides.ipynb --to slides --post serve
