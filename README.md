# grid-print: a simple 3d print file sender

`grid-print` is a simple 3d print sender with optional gcode
translation. this is primarily intended as a print target for
KIRI:MOTO to enable sending of files to FlashAir SD cards over
WIFI networks.

## Usage:

    bin/grid-print [options]

## Options:

    `--port` Port to listen on (defaults to 8081)

    `--https-port` Port for HTTPS (defaults to none)

    `--ssl-cert` File path for SSL server cert

    `--ssl-key` File path for SSL server key

    `--config` path to config file

    `--target` print target in the form [name:ip-address]