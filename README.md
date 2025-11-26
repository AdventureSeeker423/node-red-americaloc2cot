<h1 align='center'>node-red-americaloc2cot</h1>

<p align='center'>A node red flow to query Americaloc's API service in order to generate COT messages to be sent to a TAK server.</p>

## Pre-Requisites / Setup

1. Purchase and activate tracking devices from [https://us.americaloc.com/](https://us.americaloc.com/)
2. Contact Americaloc's customer service and request an API Key with the Documentation for your account.

## Deployment

1. Install [node-red-contrib-tak](https://flows.nodered.org/node/node-red-contrib-tak) if not already installed.
2. Import the node red flow.
3. Open the "Fetch Americaloc" function and fill in your API KEY and API URL inside the quotations.
4. Edit your server connections by editing the "Americaloc" node.  You will need to replace your host, port, and import your certificate/key files for the TLS connection.
