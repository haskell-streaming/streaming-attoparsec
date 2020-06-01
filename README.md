# streaming-attoparsec

[![Tests](https://github.com/haskell-streaming/streaming-attoparsec/workflows/Tests/badge.svg)](https://github.com/haskell-streaming/streaming-attoparsec/actions)

`Data.Attoparsec.ByteString.Streaming` replicates Renzo Carbonara's
[`Pipes.Attoparsec` module](https://hackage.haskell.org/package/pipes-attoparsec-0.5.1.2/docs/Pipes-Attoparsec.html).
It permits parsing an effectful bytestring with an attoparsec parser, and also
the conversion of an effectful bytestring into stream of parsed values.

See the Haddock documentation for usage examples.
