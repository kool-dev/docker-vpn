# Docker images for VPN connection

## Available Tags

### FortiVPN

- [fortivpn](https://github.com/kool-dev/docker-vpn/blob/main/fortivpn/Dockerfile)

## Usage

Example using `kooldev/vpn:fortivpn`:

```console
$ docker run --rm -d --volume=path/to/my/config/file:/etc/openfortivpn/config kooldev/vpn:fortivpn
```

## Configuration file

For `kooldev/vpn:fortivpn`:

```
# ### config file for openfortivpn, see man openfortivpn(1) ###
host =
port =
username =
password =
trusted-cert =
```
