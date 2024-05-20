# Onafrig API Automation Exercise

## Overview
This project demonstrates API automation by using the restful-booker API. The following actions were performed: create, retrieve, and update bookings.


## Installation and Run Collection

### Open Postman:
- Launch the Postman app.

### Import the Collection:
- Click Import and upload your collection file (Onafrig_API_automation_exercise.postman_collection.json).

### Import Environment Variables:
- Click Import and upload your environment variables file (Onafriq_.postman_environment.json).

### Run manually with Postman:
- Click on the collection name Onafrig_API_automation_exercise.
- Click ... (three dots) and select Run.
- Configure options (environment, iterations, delay, data).
- Click Run [Onafriq_API_automation_exercise].

### View Results:
- Check results in the Collection Runner window.

## Run via CLI [Newman]

### Prerequisites:
- Ensure Node.js and newman are installed.
  ```sh
  npm install -g newman
  ```

### Run the Collection:
- Open terminal.
- Navigate to the collection file's directory.
- Run Newman:
  ```sh
  newman run path/to/your-collection.json
  ```

### Optional: Specify Environment:
- Run Newman with environment variables:
  ```sh
  newman run path/to/Onafrig_API_automation_exercise.postman_collection.json -e path/to/Onafriq_.postman_environment.json
  ```

### View Results:
- Check terminal output or open results.html for detailed report.
