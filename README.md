you can run this file using  <mark> nodemon index.js</mark>

### Authentication Endpoints

| Method | Route        | Description                  |
|--------|--------------|------------------------------|
| POST   | /register     | Register a new user          |
| POST   | /login        | Log in as an existing user   |
| GET    | /logout       | Log out the current user     |

##
### Project Endpoints

| Method | Route            | Description                    |
|--------|------------------|--------------------------------|
| POST   | /project/           | Create a new project        |
| GET    | /project/           | Fetch all project           |
| PUT    | /project/:id        | Update project by id        |
| DELETE |/project/:id         | Delete project project by id |
| GET    |/project/export      | Get csv file                |
| POST   |/project/import      | Post csv file               |

##
### Payment Endpoints

| Method | Route            | Description                    |
|--------|------------------|--------------------------------|
| POST   | /payment/mark-paid| mark-paid by using id        |
