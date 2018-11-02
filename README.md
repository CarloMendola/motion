# motion
docker run -d --name motion --restart=unless-stopped --device /dev/video0 -p8080:8080 -p8081:8081 carlomendola85/motion:latest
