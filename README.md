# Rust warp deadpool postgres REST API
This is a learning exercise to create a simple REST TODO list API in Rust using warp, deadpool and postgres.

## Aim
The primary aim of this repo is to demonstrate one possible way of creating a REST API in Rust with good performance which persists data in PostgreSQL and uses async code throughout.

It should demonstrate how to create, read, update and delete data and also to provide liveness and readiness endpoints which could be used by e.g. kubernetes. We won't deal with authentication (authn) and authorization (authz).

I hope you find this useful :-)

Contributions and corrections by pull request are very welcome.
