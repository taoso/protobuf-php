# protobuf-php

This is a mirror for [google/protobuf](https://github.com/google/protobuf).

And features you may like:
- small package, only contain php source code
- use unicode for json_encode
- export compiler plugin, so you can write your plugin in PHP

Please see patches from [this](https://github.com/lvht/protobuf-php/compare/b8824d322bb9ef504506d0bb0ea24095295a1dd6...19b3b02b6c36b12550237986c33ac078b03f73b0).

# version
Only mirror stable tag from the offical repo.

# install

	composer require lvht/protobuf

# update from upstream

	git archive v3.5.1|tar --extract -C path/to/protobuf composer.json php/src
