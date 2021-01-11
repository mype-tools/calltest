# Videoconference Tool by MYPE

---

⚠️ **Currently in build** ⚠️ This is a project witch is in build, please use MYPE or MYPE BIG CALL!

---



## Architecture

Videoconference uses WebRTC to power all video/data communication between peers. Each Videoconference room creates a unique WebRTC swarm, using [webrtc-swarm](https://github.com/mafintosh/webrtc-swarm). This means all peers communicate to all other peers directly, without the need to pass data between any kind of centralized server. This ensures that all video data is end-to-end encrypted.

A [signalhub](https://github.com/mafintosh/signalhub) is used as a signalling server to initially connect the peers together.


