# aria2 - The next generation download utility.

Extremely small footprint aria2 container.

## Supported tags

 - `windowsnanoserver` - aria2 for Windows container.
 - `amd64` - aria2 for AMD64 Linux.

## Usage

````
docker run --name aria2 -d -p 6800:6800 -v /home/yukimochi/data:/data yukimochi/container-aria2:amd64
````