# JWST Python Dev Container Project

## Why?

Python can be difficult to work with in environments where multiple versions of python are being used. Some tools attempt to resolve this by having lots of python interpreters installed locally and trying to use the correct one where needed. This project aims to build sterile dev containers based on specific python versions and jwst python library releases to provide a clean container environment with just the relevant python and libraries.

Additionally this setup should allow windows users to run JWST python code in a clean Linux environment from their local machine.

## Prerequisites

1. Docker
1. VSCode
1. Dev Containers Extension for VSCode

## Intended use

1. Clone this project to your local machine `git clone <url for github project>`
1. Copy your own source/batch/scripts into the `src` directory
1. Configure `.devcontainer/devcontainer.json` mounts so that it can mount the location with the desired data (input and output)
1. Launch VSCode
1. Use the popup or the command pallet to launch inside the Dev Container
1. Run/debug as usual