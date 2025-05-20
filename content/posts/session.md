+++
date = '2025-05-20T13:13:11+09:00'
draft = false
title = 'Session-based Authentication'
+++

## Session

A session is a connection that is
- time-delimited
- bidirectional
- high-level
- used for interactive expression or information exchange

A session is typically stateful, and allows state to persist
during multiple messages.

[Source](https://en.wikipedia.org/wiki/Session_(computer_science))

## Cookie

[Definition](https://en.wikipedia.org/wiki/HTTP_cookie)

## Token

[Definition](https://en.wikipedia.org/wiki/Token#Computing)

## Session-based authentication

Typically, in session-based authentication,
- The **session state** is stored in the server.
- A **session token** is sent from the server as a cookie and stored in the client.
    - The client can use the session token for authentication without
      explicitly logging in every time it requests the web page until the cookie expires.