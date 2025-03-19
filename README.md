
# Full Stack Chat App

This is a full stack chat application. You can chat privately or in a group and send images if you wish.

## :bulb: Features

- Dark Theme
- Responsive UI
- JWT Authentication
- Private or Group Chat
- Sending Text and Image
- Creating Profile
- Adding Friend or Blocking

## :hammer_and_wrench: Built With

- [Typescript](https://www.typescriptlang.org/) - Main Language
- [React](https://reactjs.org/) - JavaScript library for UI
- [Redux](https://redux-toolkit.js.org/) - Global State Management
- [Nest.js](https://nestjs.com/) - Node.js Framework
- [Socket.IO](https://socket.io/) - Web Socket
- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- [PostgreSQL](https://www.postgresql.org/) - SQL Database
- [Sequelize](https://sequelize.org/) - Database ORM
- [React Icons](https://react-icons.github.io/react-icons/) - Icon Library
- [Moment](https://momentjs.com/) - Date Formatting
- [Bcrypt](https://www.npmjs.com/package/bcryptjs) - Encryption
- [JS Cookie](https://www.npmjs.com/package/js-cookie) - Cookie
- [Cloudinary](https://www.cloudinary.com/) - Image Storage

## :triangular_flag_on_post: Getting Started

First of all you need to clone the repository and install the dependencies

```shell

git clone https://github.com/ahmedsemih/fullstack-chat-app.git
cd client
npm install
cd ..
cd server
npm install

```

After doing this you must assign the following environment variables

```shell

--- CLIENT ---
REACT_APP_API_BASE_URL
REACT_APP_CLOUD_NAME
REACT_APP_UPLOAD_PRESET

--- SERVER ---
DB_PASSWORD
CLIENT_BASE_URL
JWT_SECRET

```

And run dev servers for both

```shell

--- CLIENT ---
npm start

--- SERVER ---
npm run start:dev

```
