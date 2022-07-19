# DKF Tech Stack

## Site

* Simple Machines Forum.
* Hosted on a DigitalOcean droplet.
* There are recurring backups that should be accessible through the DigitalOcean admin panel.

## Active Streamers List

* It's an iframe that's actually a React app.
* Code repository [here](https://github.com/donkey-kong-forum/streamers-list).
* Hosted on Railway but can be deployed anywhere you can host a Next.js app such as Vercel, Netlify, etc.

## Email

* DigitalOcean blocks SMF's built-in email capabilities, so we have to use a third-party service.
* Currently running through a free-tier Mailjet account.
* DigitalOcean blocks most SMTP ports, thankfully Mailjet allows email from port 2525.
* Email is configured via SMF admin pages.
