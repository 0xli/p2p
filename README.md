# p2p
p2p is the future, move from b/s or c/s to peer-to-peer development
- 比特币使用的是gossip protocol, 以太坊和Cardano(ADA)使用的是Kademlia DHT。
- gossip protocol是一种非结构化的p2p网络，基本上是随机连上一些节点就可以了，网络拓扑会呈现更随机的形状， 比特币的参数是每个节点最多主动连8个节点，最多接受117个外来连接。
- Kademlia DHT是一种结构化的p2p网络，这也是根据文件分享应用的需求来的。 完美的网络结构当然是最好按照物理距离来，每个节点连接和它物理距离最近的节点。 
  - https://zhuanlan.zhihu.com/p/34543023
  - https://yangzhe1991.org/blog/2015/10/cassandra-gossip-dht-wrn/
- 以太是devp2p,而不是libp2p. devp2p is an integrated system definition that wants to serve Ethereum's needs well (although it may be a good fit for other applications, too) while libp2p is a collection of programming library parts serving no single application in particular.
- https://blog.keep.network/introduction-to-libp2p-57ce6527babe
- https://medium.com/@mycoralhealth/code-a-simple-p2p-blockchain-in-go-46662601f417
- https://github.com/libp2p/js-libp2p/tree/master/examples
## DHT
https://www.bittorrent.org/beps/bep_0005.html

https://www.npmjs.com/package/webtorrent-dht/v/0.10.0

https://github.com/webtorrent/bittorrent-dht

# ICE 

https://webrtc.github.io/samples/src/content/peerconnection/trickle-ice/

# Skype
https://wiki.p2pfoundation.net/Skype

# P2P sip
https://www.gnu.org/software/gnucomm/freecall-gui.html

https://rocket.chat/

https://github.com/Pimm/GNU-Free-Call-prototype

https://www.gnu.org/software/sipwitch/

https://github.com/tychosoft/sipwitchqt
