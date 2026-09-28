from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return """
    <!DOCTYPE html>
    <html>
    <head>
        <title>My Simple Web Page</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                text-align: center;
                background-color: #f2f2f2;
                padding-top: 100px;
            }

            h1 {
                color: #333;
            }

            p {
                color: #666;
                font-size: 18px;
            }

            button {
                padding: 12px 25px;
                background-color: #007bff;
                color: white;
                border: none;
                border-radius: 5px;
                cursor: pointer;
            }

            button:hover {
                background-color: #0056b3;
            }
        </style>
    </head>

    <body>
        <h1>Welcome to My Web Page</h1>
        <p>This is a simple web page created using Python Flask.</p>

        <button onclick="alert('Hello! Welcome to my website.')">
            Click Me
        </button>
    </body>
    </html>
    """

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=5000, debug=True)