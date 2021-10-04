### ECE444 Lab 3 Docker

#### Completed by Jay Bihola
This repo is a clone of https://github.com/nelaturuk/education_pathways

#### Activity 1
Docker version shown in image below:

<img width="543" alt="Docker Activity 1" src="https://user-images.githubusercontent.com/39041724/135783390-7d4980bb-2edc-4f56-9f54-d518e3784f7b.png">

#### Activity 2
Education pathways repo running successfully on github
<img width="958" alt="Docker Activity 2" src="https://user-images.githubusercontent.com/39041724/135783415-42fa574d-cacf-45ab-98de-463aff25f500.png">

#### Activity 3
Docker command to build education pathways app
<img width="1348" alt="CleanShot 2021-09-30 at 12 38 38@2x" src="https://user-images.githubusercontent.com/39041724/135783456-c19ebf83-41f3-473b-8f43-5a76d9ecaac6.png">

#### Activity 4
Screenshot of running flask app
<img width="958" alt="CleanShot 2021-09-30 at 12 37 55@2x" src="https://user-images.githubusercontent.com/39041724/135783517-34a34312-229c-4426-a983-9dd00311a650.png">

Screenshot of running docker images
<img width="1386" alt="CleanShot 2021-09-30 at 12 38 53@2x" src="https://user-images.githubusercontent.com/39041724/135783560-0f1e0cb0-48f1-4f9f-b627-e8946c07c0ed.png">



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
