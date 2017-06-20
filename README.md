## sandbox-go

A docker container based on alpine for running perl6 unittests in a sandbox.

It includes:

* perl6, prove
* sandbox worker

## Working with this container

Build
`docker build -t mariosky/sandbox-perl6 sandbox-perl6/`

Run Interactively
`docker run -t -i mariosky/sandbox-perl6 /bin/sh`
