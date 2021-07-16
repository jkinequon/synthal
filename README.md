# Synthal

Synthal is an automatic synthetic user testing platform which enables developers to build automatic testing for APIs. Synthal recreates users actions without needing a web interface to continuously verify the state of the application even when there is no user traffic.

The key features for Synthal is:
- Implement your tests in Golang and let Sytnhal schedule your tests to run during an interval!
- Synthal tests contain other information to get a deeper insight such as SuccessPercent, Duration, 2XX, 4XX, 5XX
  - Synthal tests that use `runHttpStep()` will also contain SuccessPercent and Duration with an overall view and each Step as well.
- Send these monitors to Datadog to create monitors that will alert on whatever query you do! 
- Store the stacktrace on why the test failed!

## Repository
This repository contains the source code of the Synthal server.

## License

[MIT License](https://github.com/jkinequon/synthal/blob/main/LICENSE)
