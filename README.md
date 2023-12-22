# CurrenSync - Currency Converter

CurrenSync is a currency converter built with Python Flask.

## Quick Start

```bash
# Clone the repository
git clone https://github.com/your-username/CurrenSync.git
cd CurrenSync

# Set up the virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set environment variables
echo "FLASK_APP=app.py" > .env
echo "FLASK_ENV=development" >> .env

# Run the application
flask run || python app.py

Open http://127.0.0.1:5000/ in your browser and start converting currencies!