Container build for a telegraph agent to run on Resin.io managed devices.

# Configuration

The telegraf config will look for the following environment variables to publish data:

 - `INFLUX_URL`: URL to InfluxDB
 - `INFLUX_USER`: Username for InfluxDB
 - `INFLUX_PASS`: Password for InfluxDB
