# API Project: Request Header Parser Microservice for freeCodeCamp

## To Run Project
1. Go to https://amitp88-request-header-parser-microservice.glitch.me/
2. At the end of the URL, add /api/whoami
3. The page will load and you should see a JSON object with three pieces of information regarding your computer - your IP address, your preferred language (according to your browsers' header settings), and your system info

### User stories:
1. I can get the IP address, preferred languages (from header `Accept-Language`) and system infos (from header `User-Agent`) for my device.

#### Example usage:
* [base_url]/api/whoami

#### Example output:
* `{"ipaddress":"159.20.14.100","language":"en-US,en;q=0.5","software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}`
