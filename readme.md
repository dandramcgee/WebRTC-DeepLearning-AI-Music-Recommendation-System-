# 🚀 About project 💖

# 🕔 ⚙ Music Recommendation System(WebRTC+AI+ML)  ✌🏻 ⭐

### 🙏 Welcome to Musition 🙏 - Your personal musician! 🎶

### Our Music 🎵 Recommendation System leverages Emotion😀 Recognition 💽 powered by deep learning, 🤖 AI, and machine learning for personalized music suggestions. ✅

## 📸 Screenshots 📷🎥

<p align="center">
  <b> 🌴🎄🌳🌲 ⭐💖 - User's Choice - 💖⭐ 🌲🌳🎄🌴 </b>
</p>



<p align="center">
  <b> 🌴🎄🌳🌲 ⭐💖 - Music Suggestions - 💖⭐ 🌲🌳🎄🌴 </b>
</p>



## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Color Reference

| Color   | Hex                                                              |
| ------- | ---------------------------------------------------------------- |
| Black   | ![#000000](https://via.placeholder.com/10/0a192f?text=+) #000000 |
| White   | ![#FFFFFF](https://via.placeholder.com/10/FFFFFF?text=+) #FFFFFF |
| Red     | ![#FF0000](https://via.placeholder.com/10/FF0000?text=+) #FF0000 |
| Green   | ![#008000](https://via.placeholder.com/10/008000?text=+) #008000 |
| Blue    | ![#0000FF](https://via.placeholder.com/10/00b48a?text=+) #0000FF |
| Yellow  | ![#FFFF00](https://via.placeholder.com/10/FFFF00?text=+) #FFFF00 |
| Cyan    | ![#00FFFF](https://via.placeholder.com/10/00FFFF?text=+) #00FFFF |
| Magenta | ![#FF00FF](https://via.placeholder.com/10/FF00FF?text=+) #FF00FF |
| Gray    | ![#808080](https://via.placeholder.com/10/808080?text=+) #808080 |
| Orange  | ![#FFA500](https://via.placeholder.com/10/FFA500?text=+) #FFA500 |

- [Checkout Uicolorpicker - to get more hands-on ](https://uicolorpicker.com/)

## Contributing

Contributions are always welcome!

## Appendix

Any additional information goes here

## 📃 Documentation 📄

[Documentation](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_getting_started)

## Tech Stack

**Client:** React, JavaScript, React Router, Redux, Axios, UI Framework( Material-UI ) and Components, Core CSS, TailwindCSS, Webpack, Babel, and Build Tools,

**Server:** Node.js, Express.js, MongoDB, Mongoose, RESTful API, JSON Web Tokens (JWT), Middleware, Database Hosting( MongoDB Atlas )

## API Reference

#### Create User

```http
  POST /user/create/
```

| Parameter  | Type     | Description                 |
| :--------- | :------- | :-------------------------- |
| `api_keys` | `string` | **Required**. Your API keys |

#### Get User

```http
  GET /user/getUser/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### Get user todos

```http
  GET /user/todos/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### Get user events

```http
  GET /user/events/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### Create todo

```http
  POST /todo/create/
```

| Parameter  | Type     | Description                 |
| :--------- | :------- | :-------------------------- |
| `api_keys` | `string` | **Required**. Your API keys |

#### Get all todos

```http
  GET /todo/getAll/
```

| Parameter | Type | Description |
| :-------- | :--- | :---------- |
| `-`       | `-`  | -           |

#### Get search todo

```http
  GET /todo/search/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get a todo

```http
  GET /todo/:userId/:todoId/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Update a todo

```http
  PUT /todo/:userId/:todoId/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Delete a todo

```http
  DELETE /todo/:userId/:todoId/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Create event

```http
  POST /event/create/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get all events

```http
  GET /event/getAll/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### sendOtp

```http
  POST /event/sendOtp/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Update user IsVerified field

```http
  POST /event/updateIsVerified/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get a event

```http
  GET /event/:userId/:eventId/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Delete a event

```http
  DELETE /event/:userId/:eventId/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### **\*\***\*\***\*\***\*\***\*\***\*\***\*\***

#### add(num1, num2)

Takes two numbers and returns the sum.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PORT`

`MONGO_URL`

`ACCOUNT_SID`

`AUTH_TOKEN`

## Run Locally

Clone the project

```bash
  git clone https://github.com/Pavankumar-Mhaske/SmaDuleX.git/
```

Go to the project directory

```bash
  cd SmaDuleX
```

set proxy in package.json file

```bash
  "proxy": "http://localhost:4000",
```

add script to package.json file (server side)

```bash
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index.js",
    "dev": "nodemon index.js"
  }
```

Install dependencies

server side -

```bash
  npm install express mongoose dotenv twilio cors
  npm install -D nodemon
```

client side -

```bash
  npm install express mongoose dotenv twilio cors
```

Start the server

```bash
  npm run dev
```

```bash
  npm start
```

## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform

## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility

## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

## FAQ

#### Question 1

Answer 1

#### Question 2

Answer 2

## License

[MIT](https://choosealicense.com/licenses/mit/)

![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

## Related

Here are some related projects

[Awesome README](https://github.com/matiassingers/awesome-readme)

## Roadmap

- Additional browser support

- Add more integrations

## Usage/Examples

```javascript
import Component from "components"; /* Use the components which are required */

function App() {
  return <Component />;
}
```




