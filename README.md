# gd-ws
A Geometry Dash Hostable Workaround Server For Applications that have been IP banned or 429'd or want to evade/avoid Cloudflare's Unknown Telemetry Practices
This will have the same routes as the boomlings server and act as a mirror so that it's extremely easy to migrate to...

# Inspiration For this project
- Invidious
- Nitter
- Libreddit
- gdbrowser

# Reasons For Making this exist
- Tor and Geometry Dash never work together they are always banned making them useless this can become a major/real privacy concern
- Very few Proxies including free ones manage to Bypass Boomling's WAF
- gdbrowser has a few google trackers because it's using google as parts of it's backends...

I took the name of the repository and will be working on this very soon.
This tool is made to be dynamically configured for any http server libraries in python like flask, qwart , fastapi and aiohttp
This also will come as a compiled executable for windows and includes tools such as __stem__ for hosting a workaround server as an onionsite with 
configurable rate-limits.
