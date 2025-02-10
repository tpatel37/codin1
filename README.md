# Dockerized React Application

## Overview

In this I have configured a development environment using Docker containers to deploy a basic web application built with Vite and React. The application features an <h1> tag displaying the text "Codin 1".

## Repository

[GitHub Repository](https://github.com/tpatel37/tiyaben_patel.git)


## React Installation with Vite

To create a new React project using Vite, I used the following commands:

npm create vite@latest my-app --template react
cd my-app
npm install
npm run dev


This sets up a new React project with Vite and starts the development server.

## Setup Instructions

### 1. Build the Docker Image
  docker build -t patel_tiyaben_coding_assignment11 .


### Run the Docker Container
  docker run -d -p 7775:3000 --name patel_tiyaben_coding_assignment11 patel_tiyaben_coding_assignment11


### Access the Application

http://127.0.0.1:7775

### Display the text
<h1>Codin 1</h1>


## Stopping the Container
  docker stop patel_tiyaben_coding_assignment11


## Removing the Container
  docker rm patel_tiyaben_coding_assignment11


## Removing the Docker Image
  docker rmi patel_tiyaben_coding_assignment11

