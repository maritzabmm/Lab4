# Create venv in windows

python -m venv lab4

# Create venv in linux

python3 -m venv lab4

# Activate venv in windows

.\lab4\Scripts\Activate

# Activate venv in linux

source lab4/bin/activate

# Install from requirements.txt (Virtual environment must be active before this)

pip install -r requirements.txt

# Add dependencies to requirements.txt

pip freeze > requirements.txt
