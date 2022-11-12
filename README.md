# liveSync


## Transmission

### Protocols
* data over udp
* checksums over tcp

### Preparing Transmission
* prepare blocks of 64byte
* compress block (zlib?)
* encrypt block (3DES?)

### Prepare Received Block
* decrypt block
* decompress block
