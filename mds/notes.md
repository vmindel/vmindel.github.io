# Advanced Python Course 2021

## 26.10 Lecture 1 :

### Topics covered:

* Operational things about the course

* GitHub, and VCS

* Markdown basics

* Basic git commands:

  ```git
  git status
  git diff
  git add
  git commit
  git show SHA
  git push
  git remote -v
  ```

* Testing principles in development 

---

### HW:

- [x] Create a notes.md and student.json + send a pull request 
- [x] Accounts and e-mail to Gabor 
- [x] Exercism-10 exercises and mentorings (deadline 1.10)

## 2.11 Lecture 2

* README.md files in GitHub 

* Json data structure, and trailing commas in dictionaries (Python syntaxis). 

* Creating github.pages.io for my username 

* ```git init; git add; git status```

* some vim basics ```esc``` ```:wq``` 

* Authentication with private/public pair of keys in GitHub

* ```git add .``` will add everything on a local repo that was not staged for commit.

* ### Html tags:

* - ```Headers <h1> New h1 Header </h1> ```
  - ```Paragraphs <p> new paragraph</p> ```
  - ```Title of the tabs <title> </title>```
  - ```Favicons in the tabs```

---

### HW:

[x] Create a GitHub repository for your GitHub pages using the USERNAME.github.io repository name. Use Markdown to create your web site.

[x] Add notes from the current doc of the class to the website;  

[x] Add page 'exercism' to the webpage and in it links to solutions and reviewers of the exercises. 

[x] Move over the file you might have created in the notes directory of this repository to your own repository where you can maintain it easily and it can become part of your web site. Send a PR to remove it from this repo.

[x] Make a GitHub html page into a separater repo + config the repo to see it as a webpage.



## 9.11 Lecture 3

### HW:

[x] Send a pull request to add my websites to the README.md of the course's repository in the place where names of all students are. 

[x] Build a Flask website that will have some data and display it upon query. 

---

* Some flask tutorial:

  ```python
  app = Flask(__name__)
  
  
  @app.route("/")
  def main():
      return "Hello World!"
  ```

* Testing:

  ```python
  import app
  
  def test_app():
      web = app.app.test_client()
  
      rv = web.get('/')
      assert rv.status == '200 OK'
      assert rv.data == b'Hello World!'
  ```



* Different methods for accessing forms in HTML via Flask - ```GET``` and ```POST``` . 

## 16.11 Lecture 4

* ```if __name__ == '__main__'``` syntaxis for running the scripts as modules vs as programs. 
* Jinja2 templatig system and integration of conditionals and loops into the html with flask. 
* basics of the CSS and local <style>  in the html docs themselves. 
* styling blocks of html - blocks, classes and ids.

### HW:

[x] List all **interesting** modules you use

[x] Update the README.md of the course repo with my Assignment 3 submission.



## 23.11 Lecture 5

* ```pip freeze -r requirements.txt -c constraints.txt``` 
* Algorithmic complexity:
* * inserting a value n a list is O(1)
  * finding a value in the list is O(n)
  * binary search on sorted list is O(log(n))
  * the complexity of sorting algortihms and different implementations 

## 30.11 Lecture 6

* Basics of the ML; linear regression; saving model and evaluating new data.
* 
