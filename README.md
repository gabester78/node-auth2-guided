# Node Auth 2 Guided Project

Guided project for **Node Auth 2** Module.

## Prerequisites

- [SQLite Studio](https://sqlitestudio.pl/index.rvt?act=download) installed.
- Optional: PostgreSQL and pgAdmin 4 installed.

## Project Setup

- [ ] fork and clone this repository.
- [ ] **CD into the folder** where you cloned **your fork**.
- [ ] type`npm i` to download dependencies.
- [ ] type `npm run server` to start the API.

Please follow along as the instructor adds support for `JSON Web Tokens (JWT)` to the API.

Server Side

1 - validate credentials
2 - produce a token
3 - send the token as part of the response
4 - On requests that require the authentication - read the token (commonly inside an authorization header.) - decode the token > verify it's valid and hasn't been modified - make the decode token data available for the rest of the api

Client Side

1 - store the token (local storage, memory, etc.)
2 - send the token (commonly as the auth header) with every request
3 - destroy the token on logout
