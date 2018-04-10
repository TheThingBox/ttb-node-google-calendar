# google calendar node

## Function

There is  3 google calendar nodes:

- The google calendar input sends event information when an event in coming soon or is finished in your google calendar.
- The google calendar input/output searchs an event in your google calendar and returns its informations. You can filter events with msg.payload, or search everything with a blank payload.
- The google calendar output creates an event in your google calendar.

## Authentication

To use these nodes, you have to be authenticated first, authentication is managed by the google-auth node.

##Dependencies

To use this node you need to have the google-auth node on your thingbox too. No NPM package is needed here.
