# Scrape To Share

## Description
**TecNews Post** is a web application built with Flask that allows users to display news headlines over a customizable background image. Users can download their created posts as images, making it easy to share news content on social media.

## Features
- **Dynamic Backgrounds**: The application randomly selects a background image from a predefined set.
- **Customizable News Headlines**: Users can inject news headlines into the post using Flask’s Jinja template engine.
- **Image Downloading**: Users can download the created posts as image files with a single click.
- **Web Scraping**: The app scrapes technology news from [Business Today](https://www.businesstoday.in/technology/news).

## Technologies Used
- **Flask**: A micro web framework for Python.
- **BeautifulSoup**: A library for parsing HTML and extracting data from web pages. [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- **Requests**: A simple HTTP library for making requests.
- **html2canvas**: A JavaScript library that allows you to take "screenshots" of web pages or specific elements and convert them into images. [html2canvas Documentation](https://html2canvas.hertzen.com/)
- **HTML/CSS**: For structuring and styling the web application.
- **JavaScript**: For handling the download functionality using the html2canvas library.
- **Tailwind CSS**: A utility-first CSS framework for styling.


