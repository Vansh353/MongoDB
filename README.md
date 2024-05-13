# Mongo Bridge

Mongo Bridge is a Python package that simplifies the process of connecting to MongoDB databases. It provides a high-level API to connect to your MongoDB databases and perform various operations.

## Installation

Install Mongo Bridge via pip:

```bash
pip install mongo-bridge


Usage
Here's a basic example of how to use Mongo Bridge:

from mongo_bridge import MongoDBConnector

# Create a connector
mongo=MongoDBConnector(client_url, database, collection_name)

# Connect to the database
connector.connect()

# Perform a query
mongo.insert_record({"name":"xyz","designation":"student","pass":"yes"},collection_name)

# Print the results



Features
  -Easy connection to MongoDB databases
  -High-level API for performing queries

