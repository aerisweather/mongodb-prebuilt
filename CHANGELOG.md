# v6.0.1

* FIX: Throw error with `stderr` message, when `mongod` fails
* FIX: Do not invoke callback multiple times, when `mongod` fails

# v6.0.0

* MOD: **BREAKING** `start_server` always resolves/errors using the provided callback function (see #12)
* MOD: Improve error handling for a bug in mongodb-download (see e1b0386)
* FIX: Fix "on-the-fly" MongoDB server installation, when requesting a custom MongoDB version (see #30)