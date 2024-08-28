# Tally Prime Sales order integration with Mysql

## Overview

This project provides an API for integrating sales orders with the Tally accounting system. It enables seamless synchronization between your sales order management system and Tally by allowing you to fetch and insert sales orders.

[Postman](https://documenter.getpostman.com/view/8809593/2sAXjJ6D7E "Visit Postman documentation")

## API Endpoints

### 1. Get Sales Orders

- **Endpoint:** `GET https://tallyapi.vupcloud.com/api/getSalesOrders`
- **Description:** Retrieves a list of sales orders from the Tally system.
- **Response:**
  - **Content-Type:** `application/json`
  - **Status Code:** `200 OK`

### 2. Post Sales Order

- **Endpoint:** `POST https://tallyapi.vupcloud.com/api/postSalesOrder`
- **Description:** Insert new sales orders into the Tally system.
- **Headers:**
  - **Content-Type:** `application/json`
  - **Authorization:** Bearer {token}
- **Response:**
  - **Content-Type:** `application/json`
  - **Status Code:** `200 OK`

