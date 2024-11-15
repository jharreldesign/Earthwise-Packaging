# EARTHWISE PACKAGING

## Front-End

- Developers
- Jason, Jessica, & Pedro

## Back-End

- Developers
- Jason & Jessica

## Endpoints Chart

### Endpoint for Users

| HTTP Method | URI                    | Description                                        |
| ----------- | ---------------------- | -------------------------------------------------- |
| `GET`       | `/products`            | **Get** all `Products`                             |
| `GET(ID)`   | `/products/:productId` | **Get** a single `Product`                         |
| `GET`       | `/cart`                | **Get** all `Products` inside the cart             |
| `PUT`       | `/cart/:CardId`        | **Update** a single `Product` amount from the cart |
| `DELETE`    | `/cart/:cartId`        | **Delete** a single `Product` from the cart        |

### Endpoints for Admins

| HTTP Method | URI                    | Description                                        |
| ----------- | ---------------------- | -------------------------------------------------- |
| `POST`      | `/products`            | **Create** a `Product` listing into the data base  |
| `PUT`       | `/products/:productId` | **Update** a single `Product` from the data base   |
| `DELETE`    | `/products/:productId` | **Delete** a single `Product` from the data base   |
| `PUT`       | `/cart/:CardId`        | **Update** a single `Product` amount from the cart |
| `DELETE`    | `/cart/:cartId`        | **Delete** a single `Product` from the cart        |
