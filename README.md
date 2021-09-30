### ECE444 Lab 3 Docker

#### Completed by Jay Bihola
This repo is a clone of https://github.com/nelaturuk/education_pathways


#### Activity 5: Feedback
##### Functional Feedback
One functional improvement is the search process. Currently, search only works based on course names. For example, the term engineering works and will yield software engineering as one result.
I would improve it so that search can find courses based on course codes. For example, entering ECE444 must yield software engineering as well.
##### Non functional Feedback
One non functional improvement is the usability of the search results. The results appear cluttered and there is minimal spacing between column entries. Column headers aren't fully lined up with the column entries and the data takes time to understand.
I would improve it so that the table entries dynamically resizes itself to fit the screen with 12+ pixel spacing between entries to make the content easier to read.





# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
