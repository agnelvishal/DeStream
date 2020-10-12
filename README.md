

# DeStreams : Decentralized video streaming

DeStreams is a decentralized video streaming application using modern WebRTC, [GunDB](http://gun.eco) , [MediaSoup](https://mediasoup.org/) and [IPFS](https://ipfs.io) to produce a hybrid MESH-SFU with strong privacy, zero user data retention and powerful off-grid capabilities.

<img src="https://user-images.githubusercontent.com/1423657/78457103-3260a800-76a8-11ea-8c7a-c909c88ba716.png" width=500>


<br/>



### Installation


* Clone the repository and install using `npm`
```
npm install
```

* Paste the ```src``` folder in an IPFS pinning service like [Textile Buckets](https://textile.io) or [Pinata](https://pinata.cloud)

#### Configuration
* Copy the example `meething.config.example.js` to `meething.config.js`
* Customize `meething.config.js` to set the desired port and other environment variables
* Configure your SSL certificate &amp; key in `certs/` by either copying `certs/fullchain.pem.example` to `certs/fullchain.pem` and `certs/privkey.pem.example` to `certs/privkey.pem` or using your own certificate &amp; key


### Features and Usage
* Browse to the configured HTTPS port _(default 3443)_
* Choose a Room and User name
* Share link with other participants
* Password protect room if needed

The DeStreams  application will connect to community Gun nodes for user discovery. All room data/audio/video is p2p.


#### SuperPeers
SuperPeers can provide the network with services such as STUN/TURN/RELAY and in the future SFU/MCU features. 


