
You need setup prerequisites: 
*   [NodeJS - v14.17](https://nodejs.org/dist/v14.17.0/node-v14.17.0-x64.msi)
*   [Visual studio code](https://code.visualstudio.com/)

* npm
  ```sh
  npm install npm@latest -g
  ```
* nodemon
  ```sh
  npm i nodemon -g
  ```
  
### Installation

1. Get connection of MongoDB at [https://www.mongodb.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/Linhnv1997/wedding.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Rename and edit file in `Exemple.env` to `.env`

   ```env
   PORT = 3001
   URI_MONGO = 'URI'
   DOMAIN = 'http://localhost:3001'
   SITE_KEY = 'SITE_KEY'
   SECRET_KEY = 'SECRET_KEY'
   ```
5. Start server
    for dev using nodemon
   ```sh
   npm run dev
   ```


