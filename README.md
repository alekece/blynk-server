# Blynk server

* [Requirements](#requirements)
* [How to use it](#how-to-use-it)
  * [Known issues](#known-issues)
* [License](#license)

[Blynk Server](https://github.com/blynkkk/blynk-server) is an open-source java server, responsible for forwarding messages between Blynk mobile application and various microcontroller boards and SBCs (i.e. Arduino, Raspberry Pi. etc).

## Requirements

* docker v18+
* docker-compose v1.2+

## How to use it

`server.properties` at the root directory exposes the server configuration; modify it depending on your needs then run :

``` sh
docker-compose up
```

And you're done !

### Known issues

If you modify port values in the `server.properties` file, you should reflect that change into `docker-compose.yml` file as well.

## License

Copyright © 2020 Alexis Le Provost. See LICENSE for details.

