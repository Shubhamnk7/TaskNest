- Configure mongodb connection url
Go to backend directory and create .env file 
and put into `MONGODB_PATH=your-mongodb-connection-url`

- Change server port and cors origin (Optional)
by default your server running in port `http://localhost:9000` and cors origin/frontend url is`http://localhost:3000` , you can change port and cors, simply put this key into your .env
`SERVER_PORT=your-port` and` CORS_ORIGIN=-your-client-origin`
