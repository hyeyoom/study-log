# WebRTC on RPI4

자료:  
- [https://github.com/mpromonet/webrtc-streamer](https://github.com/mpromonet/webrtc-streamer)
- fully supported browser: chrome


# Installation

```bash
git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git
export PATH=$PATH:`realpath depot_tools`
fetch --no-history webrtc 
cmake . && make 
cmake -j
```
