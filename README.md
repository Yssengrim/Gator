# Gator

## Prerequisites
- Go 1.19 or higher installed on your system
- PostgreSQL installed and running

## Installation

To install the `gator` command-line tool, run:

```bash
go install github.com/Yssengrim/Gator@latest

## Setup

Set up the config file -
Before using Gator you need to create a configuration file:

gator register <your-name>

Database setup -
Make sure PostgresSQL is running, then initialize the database:

gator reset

## Usage

Here are some of the available commands -

gator register <name> - Register yourself as a user
gator addfeed <name> <url> - Add an RSS feed to follow
gator feeds - List all feeds
gator follow <feed-name> - Follow a specific feed
gator browse [limit] - Browse recent posts from your followed feeds

