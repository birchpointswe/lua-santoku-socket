<p align="center">
  <img src="https://santoku.dev/logo-santoku-socket.png" height="64" alt="santoku-socket">
</p>

# santoku-socket

An HTTP(S) client. Wraps luasec and ltn12 in a small request and response shape, with a
cancelable async handle and a millisecond `sleep`. A non-2xx status comes back as a
result rather than an error. `santoku.socket.stream` sits below it as a raw TLS stream driver,
the contract santoku-imap consumes.

## Documentation

Runnable examples and the full API: [santoku.dev](https://santoku.dev/#santoku-socket).

For agents and LLM tooling: [llms.txt](https://santoku.dev/llms.txt) for the index,
[llms-full.txt](https://santoku.dev/llms-full.txt) for every documented example.

## License

MIT, see [LICENSE](LICENSE).
