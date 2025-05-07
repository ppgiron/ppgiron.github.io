# GitHub User Search Web Application

A web-based interface for searching GitHub users by email address or full name.

## Features

- Search GitHub users by email or full name
- View user profiles with avatars
- Track search history
- Download search results as an Excel file (.xlsx) with a maximum of 10,000 results
- Optional GitHub API token support for higher rate limits

## Running in GitHub Codespaces

1. Open the repository in GitHub Codespaces
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   python app.py
   ```
4. The application will be available at the port forwarded URL, which is displayed in the terminal output or in the "PORTS" tab in GitHub Codespaces.

### Port Forwarding

Codespaces should automatically detect and forward port 5000. If not, you can manually forward the port using the "PORTS" tab in VS Code. For more details, refer to the [VS Code documentation on port forwarding](https://code.visualstudio.com/docs/remote/ports).
1. In VS Code, go to the "PORTS" tab at the bottom
2. Click "Forward a Port" 
3. Enter port 5000
4. Make it public if you want to share access

## Running Locally

1. Clone this repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   python app.py
   ```
4. Open your browser and go to http://localhost:5000/

## Requirements

- Python 3.7+
- Flask>=2.0
- Flask-Bootstrap (Note: This package is no longer actively maintained. Consider using alternatives like Flask-Bootstrap4 or Flask-Bootstrap5.)
- Pandas>=1.3
- Requests>=2.25
