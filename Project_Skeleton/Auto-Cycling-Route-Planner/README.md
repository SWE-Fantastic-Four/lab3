## SWE Backend (Lucky)

The SWE I'm Feeling Lucky Backend is built using Flask and various Python geospatial libraries. To run the server locally, use a python virtual environment manager like conda / virtualenv / pipenv and install requirements.txt

```bash
conda env create -n SWE-Lucky
conda install pip
pip install -r requirements.txt
python3 main.py
```

The webapp will be running on [http://127.0.0.1:8080/](http://127.0.0.1:8080/) by default

### File Structure
- `main.py`:
Entry point of the I'm feeling lucky API application backend

- `requirements.txt`:
Python dependencies
