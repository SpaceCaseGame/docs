# Infrastructure

## Repository Layout

All code will be hosted on github in the SpaceCaseGame repository.  For the moment, all repos are open although it is possible that some closed repos will be added if needed in the future.

The following repos will be used:

1. docs - general documentation about the code and game.
2. server - the backend server, written in go.
3. cli - a very basic client for the game written in go.  This will be the reference client for the communications with the server.
4. webui - the main ui, most likely written in node or python.
5. assets - the machine and human readable card descriptions in json

## Servers

Initially the server component and associated database (postgres) will reside on a single Debian (or possibly OpenBSD) VPS hosted on [vultr.com](https://www.vultr.com/?ref=7130880).

The initial testing URL will be hosted as spacecase.netpurgatory.com until a real domain has been purchased.

DNS and registration will be done with namecheap.com

## Blockchain compinents

Certain parts of the game will need to interact with smart contracts on a EVM-like blockchain.  Ethereum and QTUM are likely candidates.

