## Deploy postap application on multihosts environment

The network topology is pretty simple 

### Host1

CA
Orderer
peep0
peer1
couchdb0
couchdb1

### Host2
peer2
couchdb2 (scripts should by start in different terminal windows)

### Host3 
peer3
couchdb3

### Acknowledgements

The roadmap article with details how install docker swarm and own overlay network:
https://medium.com/@wahabjawed/hyperledger-fabric-on-multiple-hosts-a33b08ef24f

