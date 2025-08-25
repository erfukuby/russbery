# Raspberry Pi Flask Web Server

This project contains a simple Python Flask web server that can run on a Raspberry Pi.

## Requirements

- Raspberry Pi (any model with Python 3.x)
- Python 3.x
- pip

## Setup

1. Clone this repository or copy the files to your Raspberry Pi.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the web server:
   ```
   python app.py
   ```
4. Open your browser and go to `http://<raspberry-pi-ip>:5000`

## Project Structure

- `app.py` - Main Flask application
- `requirements.txt` - Python dependencies

## Customization

You can modify `app.py` to add more routes and functionality.

## Notes

- For external access, you may need to configure your Pi's firewall or port forwarding.
