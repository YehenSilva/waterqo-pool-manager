# Waterqo Pool Manager

A pool management service built with Python. This project provides a simple way to manage and process pool-related data through an application service layer.

## Features

* Manage pool service information
* Process pool-related records
* Use spreadsheet-based pool data
* Deploy using Render configuration
* Lightweight Python service architecture

## Project Structure

```
waterqo-pool-manager/
│
├── service.py             # Main application service
├── pool_service.xlsx      # Pool service data
├── requirements.txt       # Python dependencies
├── render.yaml            # Render deployment configuration
└── README.md              # Project documentation
```

## Requirements

Make sure you have Python installed.

Recommended:

* Python 3.10+
* pip package manager

## Installation

Clone the repository:

```bash
git clone https://github.com/YehenSilva/waterqo-pool-manager.git
```

Move into the project folder:

```bash
cd waterqo-pool-manager
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the service:

```bash
python service.py
```

The application will start based on the configuration defined in the project.

## Data Management

The project uses `pool_service.xlsx` as the pool data source.

You can update this file with new pool records while keeping the existing structure required by the application.

## Deployment

This project includes a `render.yaml` file for deployment with Render.

To deploy:

1. Connect your GitHub repository to Render.
2. Select the project repository.
3. Use the provided Render configuration.
4. Deploy the service.

## Configuration

Update application settings inside the project files before deployment.

Check:

* Environment variables
* Data file paths
* Service configuration

## Contributing

Contributions are welcome.

Steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.


```
```
