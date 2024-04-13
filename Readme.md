# Phishing Classifier Project

#### Dataset is taken from Kaggle and stored in mongodb


💿 Installing
1. Environment setup.
```
conda create --prefix venv python==3.8 -y
```
```
conda activate venv/
````
2. Install Requirements and setup
```
pip install -r requirements.txt
```
3. Set Environment Variables
 - Set `MONGO_DB_URL` in your environment. 

4. Upload data in mongodb
 - Go to the `upload_data_to_db` folder 
 - Change the `MONGO_DB_URL` with your connection string
 - Run the notebook 
 
5. Run Application
```
python app.py
```

🔧 Built with
- flask
- Python 3.8
- Machine learning
- Scikit learn
- 🏦 Industrial Use Cases

