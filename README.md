# Simple-WebSocket-Server-C-


Features

    RFC 6455 mostly supported: text/binary frames, ping-pong, connection close with status and reason.
    Thread pool
    Platform independent
    WebSocket Secure support
    Timeouts, if any of Server::timeout_request and Server::timeout_idle are >0 (default: Server::timeout_request=5 seconds, and Server::timeout_idle=0 seconds; no timeout on idle connections)
    Simple way to add WebSocket endpoints using regex for path, and anonymous functions
    An easy to use WebSocket and WebSocket Secure client library
    C++ bindings to the following OpenSSL methods: Base64, MD5, SHA1, SHA256 and SHA512 (found in crypto.hpp)

