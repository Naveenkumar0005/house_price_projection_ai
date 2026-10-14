# House Price projection AI
A machine learning web application built with FastAPI, Scikit-learn, and Joblib, containerised with Docker and deployed to the cloud. It provides REST APIs,  health monitoring, and a responsive user interface.

## Training data

The model trains from a CSV in `ml/data/`. Supported formats:

### Place house Price Prediction Dataset file 

Place your file at `ml/data/house_prices_data.csv`.

```bash
pip install -r requirements.txt
python -m ml.download_data
```

### Train the model
```bash
python -m ml.train
```

The saved model is written to `ml/artifacts/house_price_model.joblib`.

