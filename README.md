# streamlit-dockerized
Example of a basic dockerized streamlit app

# How to run ?
## Without docker 
```bash
pip install -r requirements.txt
streamlit run app.py
```
## With docker 
```bash
docker build --tag streamlit-dockerized .
docker run --port 8501:8501 streamlit-dockerized
```
