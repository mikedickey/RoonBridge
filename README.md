# RoonBridge
Dockerfile for RoonBridge on Linux x86_64

Roon data files are stored in /var/roon.

You currently must use the "host" networking driver with this.

Note: I have not tested this, but seems like it should work =)

Example:

    docker run --name RoonBridge --net=host -v /home/roon:/var/roon mikedickey/roonbridge
