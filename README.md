# DecodeLabs Project 1 - FastAPI REST API

## Overview

This project is a simple REST API built using FastAPI. It demonstrates the implementation of basic API endpoints, request validation using Pydantic, and proper HTTP methods.

## Features

* Home endpoint
* Get all products
* Create a new product
* Request validation with Pydantic
* Interactive API documentation with Swagger UI

## Technologies Used

* Python 3.x
* FastAPI
* Uvicorn
* Pydantic

## Project Structure

```text
project1-api/
│
├── main.py
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone git clone https://github.com/omar2301433/DecodeLabs-Internship-Project-1.git
cd DecodeLabs-Internship-Project-1 or porject-1
```

2. Create a virtual environment:

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the server using:

```bash
uvicorn main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```


## API Documentation

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

## Author

Omar Ahmed
