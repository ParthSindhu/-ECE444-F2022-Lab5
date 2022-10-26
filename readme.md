# CARTE Education Pathways

Parth Sindhu

Alexandre Gouveia

this repo is a clone of <https://github.com/nelaturuk/education_pathways>.

## Lab 5 Activities

### Activity 1

![activity 1](images/lab5_Act1.png)

### Activity 4

![activity 4](images/Activity4Screenshot1.png)
![activity 4](images/Activity4Screenshot2.png)

### Activity 6

#### User story 2 - Course Packages

![user story 2](images/userstory2.png)

#### User story 4 - Course Ratings

![user story 4 Explanation](images/story-4.png)
![user story 4](images/userstory4.png)

#### User story 5 - Course Recommendations

![user story 5 Explanation](images/story-5.png)
![user story 5](images/userstory5.png)

## Description

Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker

## Repository files

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
