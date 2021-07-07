# Plugin-Download-ShortBOL
A very small test plugin to test the download interface is working for SynBioHub. Could be the basis for python based download plugins.

# Install
## Using docker
Run `docker run --publish 8096:5000 --detach --name python-plug-shortbol synbiohub/plugin-download-shortbol:snapshot`
Check it is up using localhost:8089.

## Using Python
Run `pip install -r requirements.txt` to install the requirements. Then run `FLASK_APP=app python -m flask run`. A flask module will run at localhost:5000/.
