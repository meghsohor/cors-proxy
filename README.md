### _CORS Proxy_ is a NodeJS proxy which adds CORS headers to the proxied request.

This is a clone repo from [CORS Anywhere](https://github.com/Rob--W/cors-anywhere)

You can use this reverse-proxy server to send API request to bypass cors issue.

**How to use:** `https://cors-proxy-node-server.netlify.app/`**your_api_endpoint**

**Example:** `https://cors-proxy-node-server.netlify.app/https://jobs.github.com/positions.json`

### Important note: You can't use this proxy server in the browser directly. You need to add headers to the request, or you will get an error response. It has been enabled to prevent users from using the proxy for normal browsing.
