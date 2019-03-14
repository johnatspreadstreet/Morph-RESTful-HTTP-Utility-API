<h1 align="center"> 
  <br>
  <a href="https://morphapi.com/">
    <img src="./Morph.svg" width="200" height="200">
  </a>
  <br>
  Morph
  <br>
</h1>

<h4 align="center">
  A standardized RESTful utility microservice.
</h4>

<p align="center">
  <a href="https://morphapi.com">
    <img alt="Website" src="https://img.shields.io/website/https/morphapi.com.svg?up_message=up%20and%20running">
  </a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#api">API</a> •
  <a href="#the-stack">The Stack</a> •
  <a href="#a-special-thank-you">A Special Thank You</a> •
  <a href="#lessons-learned">Lessons Learned</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://github.com/johnatspreadstreet/morph/blob/master/Morph-Demo.gif?raw=true)

Website: https://morphapi.com

API: https://morph.now.sh

## Key Features

- Data manipulation using real language
- Quickly and easily navigate query parameters
- GUI to test how the API interprets human language
- Fully documented back-end with all available manipulation methods

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Python](https://www.python.org/downloads/) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

The application can be run in two different ways:
1. Back-end API only
2. Full application

Back-end API only
```bash
# Clone this repository
$ git clone https://github.com/johnatspreadstreet/morph.git

# Go into the repository
$ cd morph

# Install dependencies
$ pip install -r requirements.txt

# Run the backend api
$ python3 index.py
```

Full application
```bash
# Clone this repository
$ git clone https://github.com/johnatspreadstreet/morph.git

# Go into the repository
$ cd morph

# Install dependencies, or use venv
$ pip install -r requirements.txt
$ cd client/
$ npm install

# Run the backend api locally
$ python3 index.py

# Run the front end React app
$ cd client/
$ npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## API
API Documentation can be found at the following link: https://morph.now.sh

## The Stack

### Front-end
- React
- Axios
- Tailwindcss

### Back-end
- Now 2.0
- Python
- Flask
- Flask Rest Plus

### NLP
- Wit.ai

## Lessons Learned

This project was my first foray into switching programming languages. It is amazing how quickly you can forget how comfortable you are in your own domain (for me, JavaScript).

Here are some lessons learned:
- CORS (Cross Origin Resource Sharing) is a giant headache in ANY language
- Now 2.0 (formerly Zeit) is an incredibly cool concept, but should not be used for a Python backend just yet (~March 2019)
- Wit.ai makes NLP significantly easier to understand and implement

## A Special Thank You
A very big thank you goes out to the following individuals who helped me create Morph. It would not have been possible without you:

- [Chris Angelico, aka 'Rosuav'](https://github.com/rosuav)
- All my partners in crime in [Thinkful EI-27](https://github.com/thinkful-ei27)


## License
Creative Commons Attribution 4.0

Built by: John Young, Full-Stack Engineer
