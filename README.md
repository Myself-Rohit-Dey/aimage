# Aimage: *An image genrating App using MERN stack and OPEN AI API.*
-- **Tech stacks :** MERN Stack 
-- **Frontend :** react.js, javascript, node.js, tailwind.css
-- **Backend :** cloudinary, cors, dotenv, express.js, mongoose, nodemon, openai

## Installation & Setup:
###FRONTEND:
** For Frontend Go to client directory in terminal then: **
```bash
npm install
npm run dev
```
###BACKEND:
For some backend dependencies which includes api keys and secret keys:
*Create a `.env` file*

*`.env` file code:*
```html
OPENAI_API_KEY="<OpenAI secret API key>"
MONGODB_URL="<mongodb database url>"
CLOUDINARY_CLOUD_NAME="<cloudinary cloud name>"
CLOUDINARY_API_KEY="<cloudinary api key>"
CLOUDINARY_API_SECRET="<cloudinary api secret>"
```

**How to get the api and secret keys:**
**Cloudinary:** Create an account in cloudinary and add the cloud name, API key and API secret into the .env file of root folder.
**mongodb:** Create an account in mogodb atlas -> create a project -> create a username and password for the project -> add a database to connect with your website -> and the code to your .env file.(add your ip address in the network access) 
**OpenAI:** Create an account in OpenAI -> Click on your profile -> Go to `View API keys` and create a secret API key and add to your .env file.

** For Backend Go to server and directory in terminal then **
```bash
npm start
```
![image](https://user-images.githubusercontent.com/75258734/215357318-739cd600-2acc-49bd-8f27-67eb7d4b531d.png)

