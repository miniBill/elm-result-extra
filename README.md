This is a fork and drop-in replacement of [elm-community/result-extra](https://github.com/elm-community/result-extra). It has the same API but it's faster.

# Convenience functions for working with Result

This package contains convenience functions for working with the `Result` type.

You may want to import this module directly into the `Result` namespace:

```elm
import Result.Extra as Result
```

Then you can use the included functions similarly to the `Result` module in
`elm/core`. E.g., `Result.singleton 5` or `Result.isOk someResultValue`.

Feedback and contributions are very welcome.

## Contributing

Pull requests are welcome. If you want to talk to us, join us on the
`#elm-community` channel on the [Elm Slack](https://elmlang.slack.com). You can
reach the maintainer at @miniBill on slack and github.

## License

The source code for this package is released under the terms of the MIT
license. See the `LICENSE` file.
