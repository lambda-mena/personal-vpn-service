# Personal VPN

Project to deploy a personal VPN on any Cloud Service Provider you have,
this Personal VPN is composed of 2 major projects.

- Wireguard
- PiHole

Wireguard is the on in charge of the VPN connection and tunneling while PiHole
is the one in charge of ad & tracking blocking, you just need to change the docker-compose
SERVERURL with the public address of your machine to make it work, other parameters are optional
and are up to you to change if you wish.