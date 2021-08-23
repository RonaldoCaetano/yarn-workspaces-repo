# Simple MonoRepo using Yarn workspaces with Docker

A simple project to demonstrate a way to use yarn workspaces and docker to manage a monorepo containing two react apps.

### Scripts

- admin - To run the `admin` app in the localhost:3000
- build:admin - Build the files from the `admin` app
- product - To run the `producy` app in the localhost:3000
- build:product - Build the files from the `product` app

If you want to use the docker-compose command to run both files, you can run:

`docker-compose build && docker-compose up`
