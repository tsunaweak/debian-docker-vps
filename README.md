# Debian Docker VPS

## Clone Debian Docker VPS
    - git clone https://github.com/tsunaweak/debian-docker-vps.git
    - cd debian-docker-vps

## Build Debian Docker VPS
    - docker build -t debian-vps -f Dockerfile .

## Run Debian Docker VPS
    - docker run -it --privileged --cap-add=ALL debian-vps