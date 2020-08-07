# Deno REST API

> This is a simple REST API using Deno and Oak.

> I will be adding database functionality and JWT to it in the near future

## Installation

### Windows:

```
iwr https://deno.land/x/install/install.ps1 -useb | iex
```

### macOS:

```
brew install deno
```

## Run

```
deno run --allow-net server.ts
```

## Routes

```
GET      /api/v1/products
GET      /api/v1/products/:id
POST     /api/v1/products
PUT      /api/v1/products/:id
DELETE   /api/v1/products/:id
```
