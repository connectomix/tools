# tools lab
In this lab you will acquiant yourself with a set of tools that are of value when
working on creating accessible, reproducible, and well-documented code and data
products.

### Part 1: Install some tools
Here, we will be working with the following tools:

- Python:
  - Python 2.7
  - Jupyter
  - Plotly
- R:
  - RStudio
  - RMarkdown/Knitr
  - Plotly
  - ggplot
- Docker

To install each of these, simply google the phrase "`install <tool_name> <language_name>
<operating_system>`" and follow probably the top link. For Docker, leave the `<language_name>`
blank as that does not apply. Installation should not take very long for any of these,
and if you are unable to succeed at this step first confer with classmates using the same
operating system as you, and then ask the instructors for help if you still haven't been
able to make it work.

### Part 2: Reproducible Python
First, we will be playing at making a reproducible notebook in which we plot of some
arbitrary analysis, in Python. This process is intentionally not described by us, as
we believe it is a valuable exercise to be able to maneuver through a package's documentation
as opposed to copy-pasting from a lab manual. You are to complete the following steps
in order:

1. Launch a jupyter notebook server
2. Create a new notebook
3. Import packages and generate some data
4. Plot the data using plotly
5. Perform some transformation on the data (i.e. histogram, cluster, etc.)
6. Plot the newly-transformed data in a different way than the original
7. Save and upload the notebook (.ipynb with outputs) to your Github repo.

### Part 3: Reproducible R
Just like we did above, we will now be completing this exercise in R, through the GUI
RStudio and the packages RMarkdown/Knitr to compile our code into notebooks. The process
is slighlty different to complete this exercise in R, so we've tweaked the instructions
below:

1. Open R-Studio
2. Create a new RNotebook file, and set output to be both `md` and `html`
3. Generate some data
4. Plot the data using plotly or ggplot
5. Perform some transformation on the data (i.e. histogram, cluster, etc.)
6. Plot the newly-transformed data in a different way than the original
7. Compile the notebook
8. Save and upload the notebook (.Rmd, .md, .html, and all figure files) to your Github repo.
