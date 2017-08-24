# Pterodactyl Panel

Pterodactyl Panel is the free, open-source, game agnostic, self-hosted control panel for users, networks, and game service providers.

[![Docker Build Status](https://img.shields.io/docker/build/sfoxdev/pterodactyl-panel.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/automated/sfoxdev/pterodactyl-panel.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/pulls/sfoxdev/pterodactyl-panel.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/stars/sfoxdev/pterodactyl-panel.svg?style=flat-square)]()

## Usage

The Pterodactyl Daemon needs to have access to the docker host filesystem and the daemon to work correctly. Refer to the main repository link for all information regarding running the pterodactyl panel within docker.

## Configuration

Copy and modify the contents of *.env.example* to *.env*

## Required Mounts

`/data` - Server Data

`/certs` - SSL certificates

All mounts are recommended to be mirrored exactly.
