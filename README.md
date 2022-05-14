# Earth Analytics Bug Queue
Submit minimum reproducible examples of your bugs/problems with Earth Analytics Foundations Certificate final projects here!

## Purpose
As we transition to work on projects, we want to make sure that any additional curriculum is relevant and useful to the class. This process will 
  1. Help us determine the most up-to-date lecture and online curriculum topics
  2. Provide you (students) with a way to get help with problems remotely
  3. Give you experience writing Minimal Reproducible Examples (MREs)

My bet: Over half of submitters will solve their own problem while creating their MRE.

## How it works
### Who is this for?
Earth Analytics Foundations Certificate students at CU Boulder who are working on final projects.

### When to submit a report
Is your code crashing, too slow, or not doing what you expected? Submit a report here and we will make a short curriculum module demonstrating what we think is best practice. Some examples of the scope of possible bugs are:
  * Large raster files are crashing Python
  * Can't get hdf5 files loaded
  * Can't tile rasters or load multiple files into the same dataset

Any specific problem you have been working on for more than an hour with no progress is a good candidate. **It counts as a problem if your code works but is really slow!**

### How to submit a report
Once you have identified a specific problem you need to solve:
  1. Submit an issue using the bug template to this repository, answering all questions in the template. It is especially important to include a clear description of what is happening when you run your code, including any error messages you receive.
  2. Fork this repository
  3. Produce an MRE in a directory labelled <YYYYMMDD>-<group name>-<short description>. 
  4. Include the smallest amount of data that reproduces a problem (e.g. if you have 500 files, but the problem occurs with 2 files, just include 2 files). If you can't put your data on GitHub because it's too large or sensitive, place it somewhere accessible like OneDrive.
  5. Add and commit your files, and then create a pull request using the template. Pay close attention to the MRE checklist in the PR template.
  6. Send an email to the instructor with a link to your pull request, in case the automated emails don't go through.

### What to expect
We'll try to resolve the issue before the next class period and share the results with the class. The solutions will be presented to the class and posted to earthdatascience.org, with any sensitive information or data removed.
