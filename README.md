# Blog App

## Requirements

- A user a can post a blog and publish blog content
- A user can see their blog
- Authentication system
- User can see their profile

## Tables

- Post

  - id
  - title
  - content
  - authorId
  - createdAt
  - updatedAt
  - publishedAt
  - published

- User

  - id
  - name
  - email
  - password
  - profile
  - createdAt
  - updatedAt

- Profile
  - id
  - bio
  - userId
  - createdAt
  - updatedAt

## Technologies Stack

- GraphQL
- TypeScript
- NodeJS
- ExpressJS
- PostgreSQL
- Prisma
