# Social-media-app
1. Install pip (if not already installed)
sudo apt update
sudo apt install python3-pip

3. Create and activate a virtual environment
On Linux / macOS:
python3 -m pip install virtualenv
python3 -m venv ./venv
source ./venv/bin/activate
On Windows:
python3 -m pip install virtualenv
python3 -m venv ./venv
.\venv\Scripts\Activate.ps1

5. Install required Python libraries
Create a requirements.txt file with the following:
pymongo
cassandra-driver
requests
chromadb
sentence-transformers

Then run:
pip install -r requirements.txt
