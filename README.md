<<<<<<< HEAD
# Tendie-Tracker
A (deprecated) web app for tracking expenses and budgets.

What are tendies?
Basically, money. Internet people call money 'tendies' and it's a word play on 'tender' (i.e. legal currency) and chicken tenders the food 

## Features
  * Quick and bulk expensing
  * Budget creation and automatic tracking of expenses per budget
  * Custom spend categories
  * Dashboard with dynamic reporting
  * Detailed reports that break down spending
  * Add additional payers for tracking expenses across multiple people
  * Export your data directly into raw, CSV, and Excel
  * Responsive design - compatible with all major browsers and devices

## Built with
  * Front-end: [Bootstrap](https://getbootstrap.com/), [Chart.js](https://www.chartjs.org/), and [DataTables](https://datatables.net/)
    * [Tendietracker.com](https://www.tendietracker.com) uses [Webflow](https://www.webflow.com) and stills / mock ups from [Pixabay](https://pixabay.com) and [Burst](https://burst.shopify.com). Images are created with [Gimp](https://www.gimp.org/), [Figma](https://www.figma.com), and [ScreenToGif](https://www.screentogif.com/)
  * Back-end: [Flask](https://flask.palletsprojects.com)
  * Hosting: [Heroku](https://www.heroku.com)

## Run it locally (written for Windows and VSCode)
1) Create a directory and clone the repo in it:
```
git clone https://github.com/eddyharrington/Tendie-Tracker
```
2) Create your virtual environment:
```
python -m venv env
```
3) Activate your virtual environment:
```
env\Scripts\activate
```
4) Install the dependencies:
```
pip install -r requirements.txt
```
5) Create the DB in Postgres (schema in repo [here](./dbCreateStatements-Postgres.txt))

6) Set your environment variables in .env file (otherwise hard code the string ```app.secret_key``` in app.py and ```engine``` in all of the ```.py``` files):
7) Build and run the Flask app in VSCode
=======
# Expense-Tracker
A comprehensive expense tracking application that  enabled users to categorize transactions
>>>>>>> ec9d8d152326f9b7becc28ddeca989edbc457683
