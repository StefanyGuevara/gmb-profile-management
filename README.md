#GMB Profile Management
Description
GMB Profile Management is a comprehensive tool designed to manage and analyze Google My Business (GMB) profiles. This project scrapes competitor data, performs analysis, and provides insights to enhance your GMB profile's performance.

Project Structure 
GMB-PROFILE-MANAGEMENT/
├── api_integration/    # Flask backend for API integration
│   └── app.py
├── data_analysis/      # Scripts for analyzing scraped data
├── scraping/           # Web scraping scripts for GMB profiles
├── web_app/            # React frontend application
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   └── .gitignore
├── node_modules/       # Auto-generated Node.js dependencies
├── venv/               # Python virtual environment
├── .gitignore
├── LICENSE
└── README.md           # Project documentation (this file)

Running the Flask Server:

Start the backend server by navigating to api_integration/ and running:
bash
Copy code
python app.py
Running the React App:

Navigate to web_app/ and start the frontend:
bash
Copy code
npm start
Access the application in your browser at http://localhost:3000/.

Sprint/Task 2: Web Scraping and Data Collection
Research target websites for competitor GMB profiles.
Implement and test web scraping scripts using BeautifulSoup and Scrapy.
Store the data in a local SQLite database.


Stefany Guevara - Project Lead and Developer


