# TOTK Countdown RPC

This is a Discord Rich Presence client that displays the time left until the release of Tears of the Kingdom.

## Prerequisites

Before you can run this program, you need to have the following installed:

- [Node.js](https://nodejs.org/en/) (v14.0.0 or later)

## Installation

1. Clone this repository or download the ZIP file and extract its contents.
2. Open a terminal or command prompt and navigate to the project directory.
3. Install the required dependencies by running the following command:

```
npm install discord-rpc
```

4. Set up the Discord application by following these steps:
- Go to the [Discord Developer Portal](https://discord.com/developers/applications).
- Click on "New Application" and give it a name.
- Click on "Create" to create the application.
- Under "Rich Presence", click on "Art Assets" and upload the `totk.png` and `clock.png` files from the `assets` folder.
- Note down the "Client ID" at the top of the page.
5. Replace the `clientId` variable in `index.js` with the client ID you just noted down.
6. Run the program by executing the following command:

```
node rpc.js
```

That's it! The TOTK Countdown RPC should now be running and displaying your Rich Presence status in Discord.
