# capextract
Quickly extract particular packet numbers from an enourmsly large pcap files

### Why not editcap?
Too slow

### How
By sharding the large files into equal size chunks you are able to quickly jump to the offset of the packet.

### Note
There are some hardcodes stuff, maybe will make them configurable in the future
