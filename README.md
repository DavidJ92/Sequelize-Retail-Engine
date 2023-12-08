# Sequelize-Retail-Engine

This project implements a RESTful API for an e-commerce application using Sequelize ORM, Express.js, and MySQL. It provides endpoints for managing categories, products, and tags, allowing users to perform CRUD operations for these entities. The API offers structured endpoints for retrieving, creating, updating, and deleting data related to the e-commerce store's inventory.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [API Endpoints](#api-endpoints)
- [Testing](#testing)


## Introduction

Welcome to the E-commerce API using Sequelize ORM readme! This project implements a robust RESTful API for an e-commerce application using Sequelize ORM, Express.js, and MySQL. The API offers endpoints to manage categories, products, and tags, enabling CRUD operations for an e-commerce store's inventory.

## Features

* User authentication
* CRUD operations for categories, products, and tags
* Search functionality
* Pagination and filtering options

## Usage

### Prerequisites

Before starting, ensure you have the following installed:

- Node.js
- npm or yarn
- MySQL

### Installation

1. Clone the repository:

   ```bash
   git clone git@github.com:DavidJ92/Sequelize-Retail-Engine.git
   ```

## Demo
[Video](https://drive.google.com/file/d/1bxIoCDIlReztKy24BZ8GBkbKwOfyAQme/view?usp=sharing)


## API Endpoints

### Categories

| Endpoint               | Method | Description             |
|------------------------|--------|-------------------------|
| `/api/categories`      | GET    | Get all categories      |
| `/api/categories/:id`  | GET    | Get a specific category |
| ...

### Products

| Endpoint                | Method | Description              |
|-------------------------|--------|--------------------------|
| `/api/products`         | GET    | Get all products         |
| `/api/products/:id`     | GET    | Get a specific product   |
| ...

### Tags

| Endpoint            | Method | Description          |
|---------------------|--------|----------------------|
| `/api/tags`         | GET    | Get all tags         |
| `/api/tags/:id`     | GET    | Get a specific tag   |
| ...


## Testing

### Methodologies

- **Unit Tests**: Jest for JavaScript code.
- **Integration Tests**: Validate component interactions.
- **API Tests**: Postman/Insomnia for HTTP requests.

### Execution

1. Run `npm test` in the terminal to execute all tests.
2. Follow specific instructions for each test suite or category.



