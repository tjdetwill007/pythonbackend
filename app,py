from flask import Flask
from flask_cors import CORS
import json

app = Flask(__name__)
CORS(app)

@app.route('/api/v1/greet')
def api_v1_base():
    print("hello")
    return {"statuscode":200, "body":"Hello from backend"}

if __name__ == '__main__':
    app.run(debug=True, port=5000, host='0.0.0.0')


