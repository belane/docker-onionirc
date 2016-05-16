# docker-onionirc

Docker image to connect to Onion IRC.
When run, starts Tor and connect Weechat to onionirchubx5363.onion.  


### To build using the Dockerfile

```bash
$ git clone https://github.com/belane/docker-onionirc.git
$ cd docker-onionirc
$ docker build -t belane/onionirc .
```

### Or pull the image from the Docker repository

```bash
$ docker pull belane/onionirc
```

### To run

```bash
$ docker run -it belane/onionirc
```

### Use

See [Weechat Quick Start](https://weechat.org/files/doc/stable/weechat_quickstart.en.html#join_part_irc_channels) for usage and shortcuts.

Use __/list__ to show channels list, __/join #channelname__ to join and __/quit__ to exit.


