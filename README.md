# Backend Instructions

We recently switched to postgresql
1. Install Postgres (Remember Password You Created)
2. Open psql Shell (use the password you created)
3. You'll be prompted database stuff upon opening the terminal
4. Press enter for everything until you get to password then use the password you signed in with
## copy and paste into terminal

4. `CREATE DATABASE weatherapp;`
5. `\c weatherapp;`

6. Run code from `sql/schemas` in the WeatherAppBack repo
7. Create .env file in the root of the repo
8. Paste this code into .env file

- `DB_HOST="127.0.0.1"`
- `DB_USER="postgres"`
- `DB_password="Password you used when installing postgres and signing into terminal"`
- `DB_NAME="weatherapp"`
- `DB_PORT=5432`
- `JWT_TOKEN="Random numbers"` give this to chatgpt for it to generate you a new one (`e84f3a7b9d4c291e4a81c74f5b6c2f90`)
## In terminal
1. npm install (to install the dependencies)
2. npm run dev for the backend
## Optional Scripts
- npm run lint to run the eslint linter to search for errors

### Backend endpoints
`RequestType         Function                    Path`\
`GET.................GetClothingItems............/clothing-items`\
`POST................CreateClothingItem........../clothing-items`\
`DELETE..............deleteClothingItem........../clothing-items/:itemId`\
`GET.................getCurrentUser............../user/me`\
`PATCH...............updateCurrentUser.........../user/me`\
`POST................createUser................../user/signup`\
`POST................signInUser................../user/signin`\
`PUT.................likeItem..................../clothing-items/:itemId/likes`\
`DELETE..............dislikeItem................./clothing-items/:itemId/likes`\

### Any Questions send me a message on slack
