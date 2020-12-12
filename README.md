# gns3
Simple examples of network configs demonstrated in GNS3. Some project uses
docker containers that are pulled from my docker hub. Those containers can be
vulnerable, buggy and are not updated. There were build just for testing
specific functions. Do not use them in production!

## DHCP

- [dhcp/simple-dhcp-server](dhcp/simple-dhcp-server) - example of ISC DHCP server runinig as a docker container
- [dhcp/failover](dhcp/failover) - two ISC DHCP servers using failover to synchronise each other
