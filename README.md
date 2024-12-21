# React Router v6 Nested Route and Wildcard Path Conflict

This repository demonstrates a bug encountered when using nested routes with wildcard paths ('*') in React Router v6. The wildcard route seems to interfere with other route definitions, causing unexpected rendering behavior.

## Bug Description

The application uses nested routes. A wildcard route ('/contact/*') is intended to match any subpath under '/contact', however it is causing issues in rendering components.

## Reproduction Steps

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the app: `npm start`
4. Navigate to different routes and observe the rendering behavior.

## Solution

The solution involves carefully reviewing and reorganizing route definitions to avoid conflicts between the wildcard route and other routes, ensuring the correct route matching priorities.
