## Install

### Window + Docker
1. build container
```
docker run -it --name ros_ -e DISPLAY=host.docker.internal=0.0 ros1 bash
```
2. connect bash
```
docker exec -it ros_ bash
```
3. read ros env
```
source /opt/ros/<ros_version>/setup.bash
```

### Window + WSL


