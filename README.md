



### Features
- Multi-thread (100 attempts at once)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/thelinuxchoice/instainsane
cd instainsane
chmod +x instainsane.sh
sudo ./instainsane.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
./install.sh
```

### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR instances to avoid blocking. 
The script uses Instagram-py algorithm (Python), see the project at: https://github.com/antony-jr/instagram-py
Thanks to: @antony-jy https://github.com/antony-jr

