This is a simple chat web application built using Go and React.

To run this application, you will need to run an instance of both the backend and frontend.

To run the backend server, perform the following command in backend folder.

```
go run main.go hub.go room.go client.go
```

To run the frontend, perform the following in the frontend folder.

```
yarn start
```

The frontend can also be ran with npm or other package managers.

The backend server is currently set to run in localhost:8000, and the frontend is set to run in localhost:3000.

To begin using the chat application, simply go to localhost:3000 and login!