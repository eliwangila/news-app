# NEWS-APP
## By Eli Wangila

## Description

News App is a web appliction that displays a list of news sources from around the world. A user is able to click on a news source and view an abreviated version of the particular news article. Clicking on the news article will then redirect you to the news article's web page.

With the application, a user will be able to:

* See various news sources and select the ones they prefer.
* See all news sources from the source they selected.
* See Image description and time the news article was created.
* Click on an article and read it fully from the news source

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display news sources | **On page load** | List of various news sources is displayed per category |
| Display articles from a news source | **Click a news source** | Redirected to a page with a list of articles from the source |
| Display the preview of an article | **On page load** | Each article displays an image, title, description and publication date |
| Read an entire article | **Click an article** | Redirected to the news source's site to read the entire article |

### Prerequisites

You need the following to start working on the project on your local computer:

* A computer running on either Windows, MacOS or Ubuntu operating system installed with the following:

```
-Python version 3.8
-Flask
-pip install newsapi-python
-virtualenv
-A text  Editor vscode
```

## Getting Started

* Clone this repository to your local computer.
* Ensure you have python3.8 installed in your computer.
* From the terminal navigate to the cloned project folder.
* Create a virtual environment and access the folder via your virtual environment
* Visit https://newsapi.org/ and register for an API key.

* Run```$ export FLASK_APP=run.py
```followed by 
```$ flask run```to start the project.

* Once started, the project can be accessed on your localhost using the address: ```http://127.0.0.1:5000/```.

## Technologies Used

* Python3.8
* Boostrap
* Flask
* newsapi

## License

MIT License
