# OperationHK Development

## Architecture
- DB: MongoDB
- post.xxx.com: Nodejs Express
- get.xxx.com: Nodejs Express
- xxx.com: ReactJS
Why seperating post and get? Easier scaling. The post server may deal with lots of spamming and DDOS, while get server will have lots of real traffic.

## Backend structure
- Nodejs
- MongoDB

## Frontend structure
- UI: Smart and dumb components
- Redux: reducers, action creators
- Plan to use Material-UI

## Notes:
- Please don't commit IDE files !!!
- Code Review must be done
- Use Docker to simplify deployment
- Use prettier for formatting