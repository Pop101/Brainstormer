# Brainstormer

Enter a research topic and get related phrases you can explore next. This is an older web prototype; its search backend is retired.

![Brainstormer project cover](.github/readme-cover.svg)

## Table of Contents

- [Project status](#project-status)
- [Technologies](#technologies)

## Project status

The app uses Bing Web Search results to suggest related noun phrases. [Microsoft retired Bing Search APIs](https://learn.microsoft.com/lifecycle/announcements/bing-search-api-retirement) in August 2025, so the checked-in backend no longer offers a working setup. Running the full app requires replacing the search integration in `bing.py`.

## Technologies

- [Flask](https://flask.palletsprojects.com/) and [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/) serve the prototype.
- [NLTK](https://www.nltk.org/) handles language processing.
- [Requests](https://requests.readthedocs.io/) calls the original search API.
