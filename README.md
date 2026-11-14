# Customer and Order Integration Platform

A fictional company uses separate systems to manage customer information
and orders. Employees currently need to search both systems manually to
connect an order with the relevant customer details.

This project will build an integration that links the systems using a
shared customer ID. When an order is received, the integration retrieves
the associated customer information and makes a combined order and
customer record available through an API. This gives staff a consistent
view of the information without manually searching both systems.

## Setup

On Ubuntu 24.04, install the virtual environment package if needed:

```bash
sudo apt install python3.12-venv
```

Create and activate the environment from the project directory:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

To leave the environment:

```bash
deactivate
```