# bind

Installs a Bind/DNS server with TSIG keys and python-dns for dynamic updates

## Development
### Tests with docker

Ansible doesn't like that we're deep in a repo so we need to copy this role to a temp directory and run tests there. This script will prep your system and run tests:

`./test.sh`