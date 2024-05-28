## Working

The model used is an ensemble of Random Forest Classifier, XgBoost Classifier and LightGBM Classifier and achieves an AUC score of 0.804 on the test dataset.
The web application is deployed with Flask as backend and the frontend was built using Bootstrap and some custom CSS.

## Usage

1. Create a Virtual Environment preferably with Anaconda

```bash
conda create -n myenv
```

2. Activate the virtual environment

```bash
conda activate myenv
```

2. Install the Requirements file

```bash
pip install -r requirements.txt
```

3. Change directory to the cloned directory

4. Run the app.py file using the following command

```bash
python app.py
```
