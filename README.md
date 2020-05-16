# Hackathon--The-Marauders
Webhook endpoint which ETLs incoming  data to CleverTap Ingestion API.
Webhooks at CleverTap enable you to extract data to your server on a defined segment. This data can then be used to make event or user profile updates across any CleverTap account, using API.
This makes data transfer and upload feasible and can be achieved in real-time. 

Steps:
Design & create a working Webhook Endpoint.
Use the endpoint in webhook campaigns to ingest data.
Use this script to extract, transform this data and load it into events/ user profiles API 
Note: 
The event name and the user properties to be uploaded should be present in the key-value of the webhook payload. Eg:
event_name: Booking confirmed
user_property: gold
These values will be used in the API payload against a user profile. 


Working POC Notes:
Webhook Target Profile: https://eu1.dashboard.clevertap.com/W44-Z4K-K65Z/j346220/profile-view.html
Mobile Target profile: https://eu1.dashboard.clevertap.com/W44-Z4K-K65Z/j65990/profile-view.html
