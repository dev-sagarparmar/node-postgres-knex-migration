First add .env file in root folder with below mentioned keys

NODE_ENV= <add your environment name here>
PORT=<add your port>
PGHOST=<postgres host ip or url>
PGPORT=<postgres port>
DB_NAME=<postgres dbName>
PGUSER=<postgres username>>
PGPASS=<postgres password>>
DEBUG_SQL= false
JWT_SECRET=<your JWT secret>
JWT_EXPIRATION=<JWT expiration hrs>


Use "npm install" to install dependencies

Use "npm run dev" to run development server

To add new migration "migrate-create" script is added. Update your file name at end of script.
