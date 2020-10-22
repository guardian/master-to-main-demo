# master-to-main-demo

This repository is used to test and demo the [master-to-main](https://github.com/guardian/master-to-main) CLI tool.

## Features

The following things are included to test:

- Two files (one nested) that contain a reference to `master`. 
- Two pull requests to the `master` branch
- Branch protection on the `master` branch
- A `riff-raff.yaml` file

## Usage

Follow the instructions in the [master-to-main README](https://github.com/guardian/master-to-main/blob/main/README.md) to test out the CLI tool.

To make life easier, you can provide the `-f` and `-t` options to alternate between migrating `master` to `main` and then back to `master`. This saves having to manually put to repo back into the original state each time.

