# Dockerfile for motion image

This is a **Dockerfile** to build a docker image for **motion** based on **debian**:9.5.

[![Docker Automated build](https://img.shields.io/docker/automated/carlomendola85/motion.svg)](https://hub.docker.com/r/carlomendola85/motion/)
[![Docker Build Status](https://img.shields.io/docker/build/carlomendola85/motion.svg)](https://hub.docker.com/r/carlomendola85/motion/)

# Docker run example
`docker run -d --name motion --restart=unless-stopped --device /dev/video0 -p8080:8080 -p8081:8081 carlomendola85/motion:latest`

