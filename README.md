# Build a Custom API in Python and Flask
## Overview
A common, and important, component in a data application stack is an API layer that exposes 
data in a safe, predictable way. By exposing a data API, backend developers can restrict data
access to specific patterns, limiting security exposure and allowing for configuring Snowflake
virtual warehouses to be propertly sized, and frontend developers are not required to understand
SQL or the data modeling of the data in the database and focus on the frontend logic.

## Step-by-Step Guide
For prerequisites, environment setup, step-by-step guide and instructions, please refer to the 
[QuickStart Guide](https://quickstarts.snowflake.com/guide/build_a_custom_api_in_python/index.html).

docker build -t dataapi . --platform linux/amd64