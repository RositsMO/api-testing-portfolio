# API Testing Portfolio

## Overview

This project demonstrates API testing using Postman and the JSONPlaceholder REST API.

The goal was to validate API endpoints, verify responses, execute CRUD operations, and perform both positive and negative testing scenarios.

## Tools Used

- Postman
- JSONPlaceholder API
- GitHub

## Test Scenarios

### GET All Posts
- Verified status code 200 OK
- Validated response structure

### GET Single Post
- Verified status code 200 OK
- Validated post ID
- Validated title field
- Automated validations using Postman scripts

### POST Create Post
- Verified status code 201 Created
- Validated title
- Validated userId
- Validated generated ID

### PUT Update Post
- Verified status code 200 OK
- Validated updated title
- Validated updated body
- Validated ID consistency

### DELETE Post
- Verified successful deletion response
- Verified status code 200 OK

### Negative Testing
- Tested non-existing resource
- Verified status code 404 Not Found
- Verified empty response body

## Skills Demonstrated

- API Testing
- Functional Testing
- CRUD Operations
- Positive Testing
- Negative Testing
- Response Validation
- Postman Test Scripts
- REST API Testing

## Screenshots

### GET All Posts
![GET All Posts](screenshots/get-all-posts.png)

### GET Single Post
![GET Single Post](screenshots/get-single-post.png)

### POST Create Post
![POST Create Post](screenshots/post-create-post.png)

### PUT Update Post
![PUT Update Post](screenshots/put-update-post.png)

### DELETE Post
![DELETE Post](screenshots/delete-post.png)

### Negative Test - 404
![Negative Test](screenshots/negative-test-404.png)
