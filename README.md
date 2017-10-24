# bind

Installs a Bind/DNS server with TSIG keys and python-dns for dynamic updates

## Development
### Tests with docker

ruby install
bundle install
docker build -t local/ansible:2.4.0 .
kitchen test