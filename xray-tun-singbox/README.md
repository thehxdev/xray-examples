# Xray VPN Mode with Sing-Box


Combining Xray with Sing-Box core to tunnel all traffic with tun/tap interface.


## Xray

Modify `xray.json` file and add your proxy server to `outbounds` section.


## Sing-Box

The Sing-Box config file does not need modification.


## Run

You should run Xray first and then run Sing-Box core.

