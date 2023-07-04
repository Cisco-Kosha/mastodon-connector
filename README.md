# Kosha Mastodon Connector

Mastodon is an open-source, decentralized social networking platform that you can use to build your own federated social media applications, allowing users to connect and interact across multiple instances while maintaining control over their data and community guidelines.

The Kosha Mastodon connector enables you to perform REST API operations from the Mastodon API in your Kosha workflow or custom application. Using the Kosha Mastodon connector, you can directly access the Mastodon platform to:

* Get statuses from an account
* Get details about an account
* Post a status

## Useful Actions

You can use the Kosha Mastodon connector to get account details, statuses, and timelines, and post new statuses. 

Refer to the Kosha Mastodon connector [API specification](openapi.json) for details.

### Accounts

Use the accounts API to:

* Verify account credentials
* Get statuses posted a specific account
* Get details about a specific account
* Get all followers for a specific account

### Statuses

Use the statuses API to post statuses. 

### Timelines

Use the timelines API to get details about a user's timeline 

## Authentication

Kosha uses OAuth 2.0 to connect to Mastodon. If you already have an application registered with Mastodon, you can use your client_id and client_secret when provisioning the connector.

If you don’t want to use those credentials when provisioning the Spotify connector, Kosha provides bootstrap credentials. After you sign in to your Mastodon app, Mastodon gives Kosha an access token and your connector is provisioned. Kosha automatically refreshes your access token before it expires to ensure there’s no disruption in use.

## Kosha Connector Open Source Development

All connectors Kosha shares on the marketplace are open source. We believe in fostering collaboration and open development. Everyone is welcome to contribute their ideas, improvements, and feedback for any Kosha connector. We encourage community engagement and appreciate any contributions that align with our goals of an open and collaborative API management platform.

Refer to the contribution guidelines for details.