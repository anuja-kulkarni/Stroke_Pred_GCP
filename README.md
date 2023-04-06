# Stroke-Prediction1

To run the app in local environment:

1. Open Terminal on Computer
2. Perform git clone of the repository , change directory: cd repo
3. Create virtual environment
4. Execute the following:
export FLASK_APP=app.py 
flask run
5. Run in browser: http://127.0.0.1:5000

To run the app on google app engine:

Open Activate CloudShell, change current directory to project dir then Run:
gcloud auth list
virtualenv -p python3 env
source env/bin/activate
gcloud init
pip install -r requirements.txt
export PROJECT_ID=[YOUR_PROJECT_ID]

gcloud config set app/cloud_build_timeout 1000
gcloud app deploy --version 11

