This auxiliary part for running simple backend part
It's set for simple Blog expo application
https://github.com/oldrefery/blog-expo

1. **npm install**
2. Run server: **npm run db** (in json-server folder)
3. Create tunnel: **npm run tunnel** (local server will be available on the internet)
4. Get backend address and change baseURL in expo part
You will see logs and address from “Forwarding” is the address for API available through internet outside.
Forwarding address will expire in 8 hours. And you should restart command for creating tunnel and get new Internet address
