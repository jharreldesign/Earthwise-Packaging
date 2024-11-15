<!-- Here we can also have a image/banner of our project. Either a logo or just anything that gives the read me some flare -->

# 🌍 EARTHWISE PACKAGING

## Project Description

<!-- We give a small & short introduction for what our site provides/does -->

## 🛠️ Tech Stack

| Section       | Technology Used  |
| ------------- | ---------------- |
| **Frontend:** | React, CSS       |
| **Backend:**  | Node.js, Express |
| **Database:** | MongoDB          |

## How to Download & Run the Project

<!-- Here we just show how any other developers want to download this project -->

### Prerequisites

1. Node.js v14+
2. npm v6+
3. MongoDB Account

### Fork & Clone

1. Clone the repository: `git clone https://github.com/<yourusername>/earthwise-packaging.git`
2. Navigate into the directory: `cd earthwise-packaging`
3. Install dependencies: `npm install`

### Starting the Development Server

- Run `npm run dev` to launch the local server.
- Visit `http://localhost:3000` in your browser to see the project.

## 🚀 Features

<!-- Here we will list all features that the site will provide so like that we can list off the: AAUS (As a user stories)  -->

### 📜 Endpoints Chart

#### Endpoint for Users

| HTTP Method | URI                    | Description                                        | Is it an _MVP_? |
| ----------- | ---------------------- | -------------------------------------------------- | --------------- |
| `GET`       | `/products`            | **Get** all `Products`                             | Yes             |
| `GET(ID)`   | `/products/:productId` | **Get** a single `Product`                         | Yes             |
| `GET`       | `/cart`                | **Get** all `Products` inside the cart             | No              |
| `PUT`       | `/cart/:CardId`        | **Update** a single `Product` amount from the cart | No              |
| `DELETE`    | `/cart/:cartId`        | **Delete** a single `Product` from the cart        | No              |

#### Endpoints for Admins

| HTTP Method | URI                    | Description                                        | Is it an _MVP_? |
| ----------- | ---------------------- | -------------------------------------------------- | --------------- |
| `POST`      | `/products`            | **Create** a `Product` listing into the data base  | Yes             |
| `PUT`       | `/products/:productId` | **Update** a single `Product` from the data base   | Yes             |
| `DELETE`    | `/products/:productId` | **Delete** a single `Product` from the data base   | Yes             |
| `PUT`       | `/cart/:CardId`        | **Update** a single `Product` amount from the cart | No              |
| `DELETE`    | `/cart/:cartId`        | **Delete** a single `Product` from the cart        | No              |

## Who created this Project?

| Developers | _What Part?_               |
| ---------- | -------------------------- |
| `Jason`    | **Back** & **Front** - End |
| `Jessica`  | **Back** & **Front** - End |
| `Pedro`    | CSS & **Front** - End      |

## Credits

<!-- Having credits is optional but it's good practice to give credits to other developers for using their code/product/or anything else that should be credited to them. -->
