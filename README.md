# Running locally

`cd frontend; npm start`
`cd backend; nodemon .`

# On the server

### Backend

I've got the backend running using `pm2`. This is good because it doesn't fail when node crashes. It just reboots automatically.

Helpful `pm2` commands are...

-   `pm2 monit`
-   `pm2 stop all`
-   `cd backend; pm2 start index.js`

### Frontend

I've got the frontend building into frontend/build.
Apache is exposing that folder to the world.
