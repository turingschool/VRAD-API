## VRAD API
![VRAD](https://media.giphy.com/media/3yFr6ODcNHhrW/giphy.gif)

You will be consuming this API as part of your VRAD project. Setup instructions are below.

### Deployed Server:
The deployed server is live at https://vrad-api.herokuapp.com/api/v1/
Its endpoints are as follows:

### Hosted API Endpoints

| url | verb | options | sample response |
| ----|------|---------|---------------- |
| `https://vrad-api.herokuapp.com/api/v1/areas` | GET | not needed | Array of all areas available to rent |
| `https://vrad-api.herokuapp.com/api/v1/areas/:id` | GET | not needed | Object with detailed information for a specific area, including listings for that area |
| `https://vrad-api.herokuapp.com/api/v1/listings/:id` | GET | not needed | Object with detailed information for a specific listing |

Note: All of these endpoints will return semantic errors if something is wrong with the request.

### Local Set Up
You shouldn't need to build locally, but if you choose to, follow these instructions:

1. Clone down this repo
2. Run `npm install` from within the directory
3. Start the server by running `npm start`

You  will need to have this server running on `localhost:3001`

Be sure that you have this server running before starting up your frontend React app on `localhost:3000`


### Local API Endpoints (same as above with a different domain)

| url | verb | options | sample response |
| ----|------|---------|---------------- |
| `http://localhost:3001/api/v1/areas` | GET | not needed | Array of all areas available to rent |
| `http://localhost:3001/api/v1/areas/:id` | GET | not needed | Object with detailed information for a specific area, including listings for that area |
| `http://localhost:3001/api/v1/listings/:id` | GET | not needed | Object with detailed information for a specific listing |

Note: All of these endpoints will return semantic errors if something is wrong with the request.
