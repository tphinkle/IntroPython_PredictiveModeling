# CSU-LA/NASA DIRECT-STEM data science workshop
## Introduction to Python and Predictive Modeling

- Instructor: Preston Hinkle (** email: ** thinkle at uci dot edu)
- TAs:
	- 
	- 
	- 
	- 



# Document overview:

- [Schedule](# Schedule)

- [Python download & installation instructions](# Python download & installation instructions)

- [Workshop repository download instructions](# Workshop repository download instructions)

- [Data set information](# Dataset information)

# Schedule

## Day 1

| Time                       | Activity                                                                    |
| -------------------------- |:----------------------------------------------------------------------------|
| **9:00-9:30 am**          | Sign-in + coffee                                                            |
| **9:30-10:00 am**           | Introductions and course overview                                           |
| **10:00-12:00 pm**          | __Session 1.1__: Coding warm-up                                      |
| **12:00-1:30 pm**          | Lunch + student/instruction Q&A                                             |
| **1:30-3:00 pm**           | __Session 1.2__: Python's scientific computing infrastructure               |
| **3:00-3:15 pm**           | Coffee break                                                                |
| **3:15-5:00 pm**           | __Session 1.3__: Introducing/loading the data sets for __Session 2__        |

## Day 2

| Time                       | Activity                                                                    |
| -------------------------- |:----------------------------------------------------------------------------|
| **08:30-9:00 am**          | Coffee                                                                      |
| **9:00-9:30 am**           | __Session 2__ overview                                                      |
| **9:30-12:00 pm**          | __Session 2.1__: Linear regression                                          |
| **12:00-1:00 pm**          | Lunch                                                                       |
| **1:00-3:00 pm**           | __Session 2.2__: Time-series analysis                                       |
| **3:00-3:15 pm**           | Coffee break                                                                |
| **3:15-5:00 pm**           | __Session 2.3__: Logistic regression                                        |

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
		- Enter `conda install anaconda
5. (Download the workshop repository)[# Workshop repository download instructions]
6. Navigate to workshop repository
7. Open Jupyter notebook by typing `jupyter notebook`
8. Click on test_notebook.ipynb to open the test notebook
9. Run the notebook. Contact your instructor if there is an error.



# Workshop repository download instructions
1. Go to the Github repository: (DIRECT-STEM Intro to Python + Predictive Modeling workshop)[https://github.com/UCIDataScienceInitiative]

# Dataset information

# Convert Jupyter to HTML slideshow
ipython nbconvert your_slides.ipynb --to slides --post serve
