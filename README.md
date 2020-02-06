# Track App

Track App is a web app for tracking business shipments and saving your tracks.

## Login

It will use a single authentication login for users who wish to save their tracks

## API

It will use Node.js + Express to post and fetch user and saved tracks information to and from a MySQL database. It will use a Sequelize ORM.

## UI

A React UI with Bootstrap for styling.

## API Dependencies

It will connect to the following APIs:

- FedEx for fetching FedEx tracking results
- UPS for fetching UPS tracking results
- DHL for fetching DHL tracking results
- USPS for fetching USPS tracking results
- BitLy for shortening links
