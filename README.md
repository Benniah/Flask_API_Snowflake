# FLASK API for Fetching Data from SNOWFLAKE

This repository contains a simple python script that will allow us to build an API for fetching customer data from SNOWFLAKE'S sample Data Warehouse / Database

## Dependencies

- Flask
```bash
pip install flask
```
- Snowflake Python Conncetor
```bash
pip install snowflake-connector-python==<version>
```
- Pandas
```bash
pip install pandas
```

# How to use

The file "snowflake_flask_api.py" contains the API script and relies on certain libraries to function . Kindly ensure you have a Snowflake account setup and credentials ready.

Export the following SNOWFLAKE credntials as Environmental Variables to be able to run the Flask App locally :

```bash

export SNOWFLAKE_USERNAME ='your username'
export SNOWFLAKE_PASSWORD ='your password'
export SNOWFLAKE_ACCOUNT ='your snowflake account'

```

# How to run ?

Kindly execute the code when all the conditions above have been satified :

```bash

python snowflake_flask_api.py

```

# Test Api ?

On postman , make a post request using :

```bash
{
  "market_segment": "BUILDING"
}

```