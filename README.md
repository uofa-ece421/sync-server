# Async Server

- uses the reqwest crate to make http requests on behalf of a client
- simultaneously performs a periodic task
- handles multiple simultaneous client requests

1. Uses tokio and async/await for concurrency
2. Isn't actually concurrent :-(

