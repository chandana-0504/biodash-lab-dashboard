# biodash-lab-dashboard

# BioDash – Laboratory Experiment Dashboard

BioDash is a web-based dashboard for storing, managing, and visualizing laboratory experiment data.

## Features

- Experiment registry
- CSV / TSV / Excel data import
- Spreadsheet-style editing
- Dynamic parameters
- Threshold-based alerts
- Interactive data visualization

## Tech Stack

- FastAPI
- MySQL
- JavaScript
- Chart.js
- HTML/CSS

## Installation

Clone repository

git clone https://github.com/chandana-0504/biodash-lab-dashboard.git
cd biodash-lab-dashboard

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt

uvicorn main:app --reload

#Open any browser and go to:

http://127.0.0.1:8000

Requires MySQL database named "biodash"

## Project Structure

main.py – FastAPI backend  
templates/ – HTML templates  
static/ – CSS and JavaScript  

## License

MIT License
