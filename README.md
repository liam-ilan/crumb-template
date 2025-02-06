# Crumb Template
This repo will help you start your own Crumb project and build it as a standalone binary.

> The Crumb interpreter is built for POSIX compliant systems, and utilizes `ioctl.h` and `unistd.h`. To use Crumb on windows, either use WSL, or use a Linux container.

## Getting Started

To get started, create a new repository based off of this template by clicking the green "Use this template" button at the top right corner.

Then clone your repository, cd into the repo root directory, and run:
```bash
chmod +x setup.sh && ./setup.sh
```
This will build the Crumb interpreter and Loaf bundler from source.

Now you're all set! 

To run `app.crumb` do:
```bash
./crumb app.crumb
```

To build `app` as a standalone executable do:
```bash
./loaf app.crumb app
```

## Crumb Language Basics
See https://github.com/liam-ilan/crumb#basics.

## Crumb Docs
- See https://github.com/liam-ilan/crumb#standard-library for more info on the standard libary.
- See https://github.com/liam-ilan/crumb#syntax for a syntax reference.

## Source Repos
- Crumb https://github.com/liam-ilan/crumb. 
- Loaf https://github.com/liam-ilan/loaf
