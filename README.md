# Hackathon--The-Marauders
Webhook endpoint which ETLs incoming  data to CleverTap Ingestion API.

Steps:
Design & create a working Webhook Endpoint.
Use the endpoint in webhook campaigns to ingest data.
Use this script to extract, transform this data and load it into events/ user profiles API 
Note: 
The event name and the user properties to be uploaded should be present in the key-value of the webhook payload. Eg:
event_name: Booking confirmed
user_property: gold
These values will be used in the API payload against a user profile. 
