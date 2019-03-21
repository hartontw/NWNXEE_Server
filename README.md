# NWNX:EE Linux dedicated server middleware in Node.js

### Install

i386 architecture and libs are required:
```bash
sudo dpkg --add-architecture i386
sudo apt install lib32stdc++6 libc6-i386
```

Download repository and install node_modules:
```bash
git clone https://github.com/hartontw/NWNXEE_Server.git
cd NWNXEE_Server
npm install
```

Create a ```config.json``` file in the root folder. If you want to override the server parameters located in ```nwnplayer.ini``` you can fill parameters object.