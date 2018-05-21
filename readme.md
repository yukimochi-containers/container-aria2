# aria2 - The next generation download utility.

Extremely small footprint aria2 container.

## Build status

- amd64 image - ![AMD64 image Build status](https://img.shields.io/docker/build/yukimochi/container-aria2.svg)
- arm64v8 image - ![arm64v8 image Build status](https://ci.yukimochi.com/api/badges/yukimochi-containers/container-aria2/status.svg?branch=master)
- windows-amd64.sac2016 image - ![windows-amd64.sac2016 image Build status](https://ci.appveyor.com/api/projects/status/04avi3jmmr052ato/branch/master?svg=true)

## Usage

````
docker run --name aria2 -d -p 6800:6800 -v /home/yukimochi/data:/data yukimochi/container-aria2
````

## Supported architectures
[`amd64`](https://github.com/yukimochi-containers/container-aria2/blob/master/Dockerfile),  [`arm64v8`](https://github.com/yukimochi-containers/container-aria2/blob/master/Dockerfile), [`windows-amd64.sac2016`](https://github.com/yukimochi-containers/container-aria2/blob/master/Dockerfile.sac2016)
