# Feed Reader Testing Project Overview
I was given a web-based application that reads RSS feeds and asked to write a test suite using [Jasmine](http://jasmine.github.io/). The idea is to get a grasp of test-driven development.

## How to run the application locally
1. Go to the following github page: https://github.com/stefets42/feed_reader_testing
2. Click on the green "Clone or download" button
3. Copy the address: https://github.com/stefets42/feed_reader_testing.git
4. Open the terminal
5. Go to the folder where you want to copy this project
6. Run the server
    1. If you have Python 2, run: python -m SimpleHTTPServer 8000
    2. If you have Python 3, run: python -m http.server 8000
7. On your browser, navigate to: http://localhost:8000/
    1. As there is a file called index.html in the directory, it should automatically show up
    2. If not, you should see the files in that directory listed: click on the index.html file and watch it load

## Jasmine framework presentation
The project uses [Jasmine](http://jasmine.github.io/), a behavior-driven development framework for testing JavaScript code. It does not depend on any other JavaScript frameworks, does not require a DOM, and has a clean, obvious syntax.