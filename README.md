# sails-ub-poc

A project demonstrating a bug inside SailsJS sockets that a native node client can't connect to the server.

## How to Use

1. Run `sails lift` inside the socket-server project.
2. Run `node index.js` inside the socket-client project.
3. The server will refuse connection to the client without a handshake.