ERRORS: Container is marked for removal and cannot be started.
sudo service docker stop
sudo thin_check /var/lib/docker/devicemapper/devicemapper/metadata
sudo thin_check  --clear-needs-check-flag   /var/lib/docker/devicemapper/devicemapper/metadata
sudo service docker start
