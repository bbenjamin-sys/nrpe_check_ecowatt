# checkicinga_ecowatt
## Account Information
- Create an account on RTE API website (https://data.rte-france.com/)
- Register to the Ecowatt API (https://data.rte-france.com/catalog/-/api/consumption/Ecowatt/v4.0) and click on "Abonnez-vous à l'API" 
- Create a new application
- copy .env_sample file to .env
- Copy the base64 encoded id and secret in .env file

## Required tool
- jq

## API quota restriction 
- The quota value is one call every 15 minutes

## todo
- filter by region (not yet implemented in the api)
