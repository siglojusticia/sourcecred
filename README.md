# [SourceCred](https://sourcecred.io)

[![Build Status](https://circleci.com/gh/sourcecred/sourcecred.svg?style=svg)](https://circleci.com/gh/sourcecred/sourcecred)
[![Discourse topics](https://img.shields.io/discourse/https/discourse.sourcecred.io/topics.svg)](https://discourse.sourcecred.io)
[![Discord](https://img.shields.io/discord/453243919774253079.svg)](https://sourcecred.io/discord)

SourceCred allows communities to assign Cred scores, which measure the value that contributors have brought to the community.
The community can then use the scores to distribute rewards (e.g. project-specific Grain tokens) to their contributors.

Cred is computed by constructing a Cred Graph showing every contribution to a project, and then running a version of the PageRank
algorithm to assign scores to every contribution and contributor.

We currently support loading data from GitHub, Discourse, Discord, and via custom "initiatives".

Please check out [our website] for more information. If you'd like to get involved as a contributor, please drop by [our Discord]
and say "hi"!

[our website]: https://sourcecred.io/
[our Discord]: https://sourcecred.io/discord

## Current Status

SourceCred is still in alpha; as such, the interfaces are in flux and the documentation is spotty.
We're working on a polished beta release which will include more documentation, and more maintainable instances. We expect this to land
by early July.

For now, if you want to use SourceCred, you might start by forking [MetaGame's Cred Instance].

Note that our next release (v0.7.0) will totally revamp how SourceCred instances are setup, and replace the CLI. As such,
expect that migrating from v0.6.0 to v0.7.0 will involve making changes to your configuration.

[MetaGame's Cred Instance]: https://github.com/MetaFam/TheSource

## License

SourceCred is dual-licensed under Apache 2.0 and MIT terms:

  * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or <https://www.apache.org/licenses/LICENSE-2.0>)
  * MIT License ([LICENSE-MIT](LICENSE-MIT) or <https://opensource.org/licenses/MIT>)

## Acknowledgements

We’d like to thank [Protocol Labs] for funding and support of SourceCred.

[Protocol Labs]: https://protocol.ai
