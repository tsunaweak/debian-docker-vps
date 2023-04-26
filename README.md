# Debian Docker VPS


## Build Debian Docker VPS
    - docker build -t debian-vps -f Dockerfile .

## Run Debian Docker VPS
    - docker run -it --privileged --cap-add=ALL debian-vps