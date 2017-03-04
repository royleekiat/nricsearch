# Roy Lee Kiat - Dummy NRIC Search implementation in Python

This is a Dummy NRIC Search implementation that gets Api.ai classification JSON (i.e. a JSON output of Api.ai /query endpoint) and returns a fulfillment response.

# What does the service do?
It's a NRIC Search fulfillment service that uses hard code.
The services takes the `NRIC` parameter from the action, are returns a fake citizen status to Api.ai.

The service packs the result in the Api.ai webhook-compatible response JSON and returns it to Api.ai.

