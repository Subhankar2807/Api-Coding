# Api-Coding
# My First Api Code 

from flask import Flask, jsonify

app = Flask(__name__)

@app.route('/')

def index():
    return "Welcome!! Hi,This is my First API code, I hope I will give more Output by learning"

if __name__ == "__main__":
    app.run(debug=True)
