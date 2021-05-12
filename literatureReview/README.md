# Machine Learning and Fluid Dynamics: Literature Review

Literature review of theory and applications of machine learning algorithms tackling fluid dynamic tasks.


## Usage
* Clone this part of the repo
* Enter the repo `cd LiteratureReview`
* Create a virtual environment `python -m venv venv`
* Activate the virtual environment `source venv/bin/activate`
* Install dependencies `pip install -r requirements.txt`
* Build the book `jupyter-book build LiteratureReview`
* Open generated document `open  LiteratureReview/_build/html/index.html`


## Online Hosting
Additional setup needed for hosting the jupyter-book online (via continuous integration).

### GitLab
* Add .gitlab-ci.yml
### GitHub
* Add .github/workflows/deploy.yml
* Activate publishing under Settings->Pages via setting Source to "Branch: gh-pages"


## Disclaimer
The views and opinions expressed in this work are solely the ones of the author and do not necessarily represent the opinions of any entity whatsoever with which the author has been, is now or will be affiliated. 
