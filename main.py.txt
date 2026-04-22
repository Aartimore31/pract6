from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Hello from PaaS (Google App Engine)!"