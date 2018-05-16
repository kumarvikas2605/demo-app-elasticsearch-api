# demo-app-elasticsearch-api

This script is a simple introduction to the python elasticsearch API.

This script will populate an elasticsearch index from a file and then give a simple command line query interface. 
Each line of the input file will be mapped into a JSON document of the form { "text": "my file line..." } and added to the index.
