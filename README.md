# Containerized version of MVS Tk5 on Hercules 

To run, simply:

    docker compose up

After waiting a bit for the system to (install and) star up, use a 3270-terminal to connect to the service running in `localhost:3720`. For example, I use [x3270](https://x3270.bgp.nu/) as it is open source.

Data stored in DASD is persisted.

