# ErrorcountMiddleware

A simple Express.js error-handling middleware that tracks the total number of errors that occur in your application.

## Features

- Automatically counts errors caught by the error handler
- Provides an `/errorCount` endpoint to retrieve the current error count
- Easy to integrate with existing Express applications

## Usage

The middleware catches all errors thrown in your routes and increments an error counter. Access the current error count via the `/errorCount` endpoint.
