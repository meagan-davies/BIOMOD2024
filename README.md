# BIOMOD2024

#### Building/Using Frozen Flask

* To freeze the website such that it can be deployed using github pages download then following dependencies:
```bash
pip install frozen-flask
pip install flask_flatpages
```
* Reference app.py for building features using frozen-flask and flatpages to freeze the webpages.
* To build/freeze the webpage run:
```bash
python app.py build
```
* Then rename the generated folder "docs".
* In the github repository configure the settings under pages such that it builds/deploys from the docs/ folder.