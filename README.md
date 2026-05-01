 # Dark Web Crawler

A Flask-based web application for crawling and analyzing .onion sites on the Tor network.

## Features

- Crawl .onion sites with configurable depth
- Search for .onion sites using keywords
- View discovered links with pagination
- Export crawl results in various formats
- Network graph visualization
- Search and crawl history tracking
- Tor network integration with simulation mode

## Requirements

- Python 3.8+
- Flask
- SQLAlchemy
- Tor Browser or Tor service
- Other dependencies listed in requirements.txt

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/darkwebcrawler2.git
cd darkwebcrawler2
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure the database:
- The application uses SQLite by default
- For production, set the DATABASE_URL environment variable

5. Run the application:
```bash
python app.py
```

## Usage

1. Access the application at `http://localhost:5000`
2. Login with default credentials (admin/admin123)
3. Start crawling by providing a target URL or search keyword
4. View results in the dashboard

## Security Notes

- This tool is for educational and research purposes only
- Always use with caution and respect privacy
- Consider using a VPN in addition to Tor
- Keep your system and dependencies updated

## License

MIT License
