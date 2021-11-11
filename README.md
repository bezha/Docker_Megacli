# Docker-MegaCli

Based on https://github.com/kamermans/docker-megacli

Used following scripts:
- https://bench.sh/
- https://github.com/glensc/nagios-plugin-check_raid
- https://github.com/Napsty/check_smart
- https://github.com/thomas-krenn/check_ipmi_sensor_v3

### Running the container
You can run this container without installing anything except Docker:

    docker run --rm -ti --privileged bezhav/megacli:v1

> Note that the `--rm` will delete the container for you when you exit it, and
> `privileged` mode is required so the container can talk directly to the hardware.
