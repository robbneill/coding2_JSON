# coding2_JSON
JSON Repository
This is the code for a test JSON file.


import json
import requests

response = requests.get("https://jsonplaceholder.typicode.com/todos")
todos = json.loads(response.text)

print(todos[:2])
