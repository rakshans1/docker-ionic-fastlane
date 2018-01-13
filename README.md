[![Travis](https://img.shields.io/travis/rakshans1/docker-ionic-fastlane.svg)](https://travis-ci.org/rakshans1/docker-ionic-fastlane)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/ionic-fastlane.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/ionic-fastlane/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/ionic-fastlane/latest.svg)]()


![rakshans1/ionic](/icon.png?raw=true)
# Latest Ionic and Fastlane
### based on [latest Ionic with the latest Android and the latest Node.js](https://github.com/rakshans1/docker-ionic)
----
### Pull from Docker Hub
```
docker pull rakshans1/ionic-fastlane:latest
```

### Build from GitHub
```
docker build -t rakshans1/ionic github.com/rakshans1/docker-ionic-fastlane
```

### Run image
```
docker run -it rakshans1/ionic-fastlane bash
```

### Use as base image
```Dockerfile
FROM rakshans1/ionic-fastlane:latest
```