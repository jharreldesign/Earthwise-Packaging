<!-- Here we can also have a image/banner of our project. Either a logo or just anything that gives the read me some flare -->

# EARTHWISE PACKAGING

## Project Description

Welcome to **Earthwise Packaging**, where we’re on a mission to help the food industry go green!
<br /> Our site offers eco-friendly essentials, from compostable cups to biodegradable utensils.
<br />Think of us as an eco-supplier, making it easy for businesses to browse, buy, and breathe easier knowing they’re reducing waste.
<br />Together, we’re packing up pollution and unboxing a greener future one compostable fork at a time!

## Table of Contexts

<!-- We give a small & short introduction for what our site provides/does -->

- **_[Tech-Stack](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#tech-stack)_**
- **_[Download-&-Run](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#how-to-download--run-the-project)_**
- **_[Features](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#features)_**
  - **_[End-Point-Charts](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#endpoints-chart)_**
  - **_[Portals](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#portals)_**
  - **_[Models](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#models)_**
  - **_[Product-Ideas](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#items-listed-for-now-idea)_**
- **_[Developers](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#who-created-this-project)_**
- **_[Credits](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#credits)_**
- **_[Stretch-Goals](https://github.com/jharreldesign/Earthwise-Packaging/tree/PedroCr05#stretch-goals)_**

## Tech Stack

| Section       | Technology Used           |
| ------------- | ------------------------- |
| **Database:** | MongoDB                   |
| **Backend:**  | Node.js, Express, _&_ JWT |
| **Frontend:** | Axios, CSS, _&_ React     |

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

1. Run `npm run dev` to launch the local server.
2. Visit `http://localhost:3000` in your browser to see the project.
3. It is advised to run **both** the **_Back End_** _&_ **_Front End_** Simiulatiously.

## Features

<!-- Here we will list all features that the site will provide so like that we can list off the: AAUS (As a user stories)  -->

### Endpoints Chart

#### Endpoint for Users/Customers

| HTTP Method | URI                    | Description                                        | Is it an _MVP_? |
| ----------- | ---------------------- | -------------------------------------------------- | --------------- |
| `GET:`      | `/products`            | **Get** all `Products`                             | _Yes_           |
| `GET(ID):`  | `/products/:productId` | **Get** a single `Product`                         | _Yes_           |
| `GET:`      | `/cart`                | **Get** all `Products` inside the cart             | **_No_**        |
| `PUT:`      | `/cart/:CardId`        | **Update** a single `Product` amount from the cart | **_No_**        |
| `DELETE:`   | `/cart/:cartId`        | **Delete** a single `Product` from the cart        | **_No_**        |

#### Endpoints for Admins

| HTTP Method | URI                    | Description                                        | Is it an _MVP_? |
| ----------- | ---------------------- | -------------------------------------------------- | --------------- |
| `POST:`     | `/products`            | **Create** a `Product` listing into the data base  | _Yes_           |
| `PUT:`      | `/products/:productId` | **Update** a single `Product` from the data base   | _Yes_           |
| `DELETE:`   | `/products/:productId` | **Delete** a single `Product` from the data base   | _Yes_           |
| `PUT:`      | `/cart/:CardId`        | **Update** a single `Product` amount from the cart | **_No_**        |
| `DELETE:`   | `/cart/:cartId`        | **Delete** a single `Product` from the cart        | **_No_**        |

### Portals

- Customer Only Portal/Access -> MVP
- Admin Only Portal/Access -> Post MVP

### Models

---

#### 1. User/Customer Model

| Tag Name               | Syntax     | _Required_? |
| ---------------------- | ---------- | ----------- |
| `Email:`               | **String** | _Yes_       |
| `Full-Address:`        | **String** | _Yes_       |
| `Name:`                | **String** | _Yes_       |
| `Password:`            | **String** | _Yes_       |
| `Payment-Information:` | **String** | _Yes_       |
| `Company-Name:`        | **String** | **_No_**    |
| `Username:`            | **String** | **_No_**    |
| `Phone-Number:`        | **Number** | _Yes_       |

#### 2. Inventory/Product Options

| Tag Name                        | Syntax                 | _Required_? |
| ------------------------------- | ---------------------- | ----------- |
| `Product-Description:`          | **String**             | _Yes_       |
| `Product-Image:`                | **String**             | _Yes_       |
| `Product-Name:`                 | **String**             | _Yes_       |
| `Product-Quick-Facts:`          | **String**             | **_No_**    |
| `Reviews:`                      | **String (_Embeded_)** | **_No_**    |
| `In-Stock-Status:`              | **Number**             | _Yes_       |
| `Product-Price:`                | **Number**             | _Yes_       |
| `Product-SKU/Manufacturer-SKU:` | **Number**             | _Yes_       |
| `Quantity:`                     | **Number**             | _Yes_       |

---

### Items listed for now (_idea_)

| Category                  | Products                                                                |
| ------------------------- | ----------------------------------------------------------------------- |
| `Food & Eating Supplies:` | Plates, Straws, Utensils, & Cups (hot, cold, & multiple sizes)          |
| `Kitchen Essentials:`     | Catering boxes/items, Liner sheets, To-go containers, & Carry-out boxes |

<!-- Decided to remove the rest and comment them just in case if we want to add them later but for now. I think I'll leave the first four. -->

<!--
| | paper bags, Kitchen hardware (spatulas, knives), Eco-friendly tape, |
| | Food trays, Trash bags, & lastly Gloves                             |
-->

## Who created this Project?

| Developers | _What Part?_                 |
| ---------- | ---------------------------- |
| `Jason:`   | **Back** _&_ **Front** - End |
| `Jessica:` | **Back** _&_ **Front** - End |
| `Pedro:`   | CSS _&_ **Front** - End      |

## Credits

<!-- Having credits is optional but it's good practice to give credits to other developers for using their code/product/or anything else that should be credited to them. -->

## Stretch Goals

| By who?     | _On what exactly_?                                                    | _Where_?                   |
| ----------- | --------------------------------------------------------------------- | -------------------------- |
| `Pedro:`    | The ability of the site prefetching data before the user even clicks. | **Front** End              |
| `Jason:`    | Shipping options with shipping progress.                              | **Back** End               |
| `Everyone:` | Being able to implement a search/filter feature.                      | **Back** _&_ **Front** End |
