# carenvideo-frontend

## Install
```javascript
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run serve
```

## Variables File
Add a `variables.js` file in the `/src` folder with the following structure.

```javascript
const variables = {
  baseURL: // URL of the application, not the server
  applicationServerKey: // Vapid public key,
  clientId: // Caren Zorgt public key,
  userEndpoint: // Carenzorgt user endpoint ('https://www.carenzorgt.nl/api/v1/user') ,
  peopleEndpoint: // Carenzorgt people endpoint ('https://www.carenzorgt.nl/api/v1/people'),
  redirectUri: // Redirect URI for oauth,
  pushSubEndpoint: // Push Subscription Endpoint (See carenvideo-server),
  pushTriggerEndpoint: // Trigger Push Notification Endpoint (See carenvideo-server),
  pusherPublicKey: // Pusher Public Key (See https://pusher.com),
  pusherPresence: // Pusher Presence Channel Endpoint (See carenvideo-server),
  pusherPrivate: // Pusher Private Channel Endpoint (See carenvideo-server),
  icalEndpoint: // Ical endpoint on the server (See carenvideo-server),
  getCalendarItemsEndpoint: // Endpoint to get calendar items for a user id (See carenvideo-server),
  updateCalendarItemEndpoint: // Update a calendar item for a user id (See carenvideo-server),
  deleteCalendarItemEndpoint: // Delete a calendar item for a certain user (See carenvideo-server),
}

export default variables
```
