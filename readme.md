## TrueLayer Data API for Consequence Test Project

### Overview
This test project was made in coordination with Consequence, whereby the end goal is to provide a working
client that utilizes the TrueLayer Data API. This client will make use of the available interfaces for 
getting banking data, specifically transactions and their related details.

Since this is a test project, storage of data is very crude and is not recommended at all for production
environments. Please be aware of this fact. Note, however, that no login data and/or credentials are being
stored on the server.

### `client_id` and `client_secret`
Visit <https://console.truelayer.com> and sign up: you need to get your `client_id` and `client_secret` - 
these are the keys that will be required to authenticate and interact with the TrueLayer Data API. On
signing up, remember to enable Data API service for your account.

### Installation

#### Requirements
System requirements:
- python 3.7
- pip

#### Test Project Requirements
The test requires:

A working integration with TrueLayer, where on a webpage we are able to:

- authorise access for UK bank accounts and cards 
- view all the transactions for each
- View all the data associated with each transaction