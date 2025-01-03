# The Cassandra Integration Squad Project

This project utilizes [npm workspaces](https://docs.npmjs.com/cli/v7/using-npm/workspaces?v=true), [Docker Compose](https://docs.docker.com/compose/) and [Cassandra](https://cassandra.apache.org/_/index.html).

## Development and Testing

Simply run

```shell
$ npm run dev --workspaces
```
To run the whole thing in full-stack locally. To test only a specific project (be it frontend or backend):

```shell
$ npm run dev --workspace=frontend
```
Additionally, you may test the whole stack via Docker Compose. Simply do the following:

```shell
$ docker compose up
```
