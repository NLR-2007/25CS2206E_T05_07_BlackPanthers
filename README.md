# Early Detection of Fungal Crop Disease using Microclimate Leaf-Wetness Modelling

**Team Number:** 03 (Team 3)  
**Team Name:** Black Panthers

| Student ID | Full name |
| --- | --- |
| 2520030366 | Nimma Lokesh Reddy |
| 2520030333 | Ramagiri Rishik Rao |
| 2520030351 | U. Pranav Varma |

## Project overview

This project is a proposed IoT and AWS prototype for monitoring crop conditions associated with fungal disease. An ESP32 will collect air temperature and humidity from a DHT22, soil temperature from a DS18B20, and an experimental estimate of leaf wetness from a rain-sensor plate. Readings will travel through AWS IoT Core and AWS Lambda to Amazon DynamoDB. A responsive dashboard will use Amazon API Gateway and Lambda to show recent readings, trends, and basic risk indicators. Amazon CloudWatch will monitor the cloud components.

The rain-sensor plate is not a dedicated leaf-wetness sensor; its readings will need calibration against observed leaf conditions.

## Repository structure

```text
.
├── .gitignore           # Local secrets, dependencies, and generated files
├── README.md            # Project and team information
├── src/                 # Application and device source code
│   ├── assets/          # Images, media, and icons
│   └── components/      # Core code modules
├── docs/                # Diagrams, wireframes, and project reports
└── tests/               # Test scripts and QA files
```

## Getting started

The repository currently contains the requested starter structure. Application code and executable setup instructions will be added as the prototype is developed. Do not upload AWS credentials, API keys, device certificates, or private keys; use local environment variables or a secrets manager.
