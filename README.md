# Basil
Simple building of any library. Requires minimal effort to consume any project. 

## Aims
- Deterministic and repeatable builds.
- Takes lessons learnt from Bazel but aims to simplify them.
- Doesn't sandbox itself, rather reuses existing sandboxes such as Docker.
- Consumes Starlark as the configuration language of choice.
- No local deamon.
- Action graph should be calculated, if possible, over a distributed network of nodes.
- Proper handling of transitive dependencies.
- Greatly simplify toolchain consumption.

## Language
- Go

## Important libraries
- Starlark Interpreter - For reading configuration files
- Buildbarn - For reusing CAS logic

## Configuration
- Starlark

## Supported OS
- Linux
- Windows
- MacOs