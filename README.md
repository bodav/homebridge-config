# Homebridge Setup

All the things needed to bootstrap my current homebridge setup

# Install

To install docker, docker-compose and homebridge see:  
https://github.com/oznu/docker-homebridge/wiki/Homebridge-on-Raspberry-Pi

# Setup

### Clone

```
git clone <thisrepo> ~/homebridge or .
```

### Run

```
docker-compose up -d
```

### Logs

```
docker-compose logs -f
```

# Upgrade

```
docker-compose pull homebridge
```