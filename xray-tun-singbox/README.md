# Xray VPN Mode with Sing-Box


Combining Xray with Sing-Box core to tunnel all traffic with tun/tap interface.


## Xray

Modify `xray.json` file and add your proxy server to `outbounds` section.

### IR routing rules

To route Iran traffic directly, download and replace `geoip.dat` and `geosite.dat`.
Then use `xray-rules.json` instead of `xray.json` as your main Xray config file.

> [!NOTE]
> Download Iran `.dat` files from [Iran-v2ray-rules repository](https://github.com/Chocolate4U/Iran-v2ray-rules/releases/latest)


## Sing-Box

The Sing-Box config file does not need modification.


## Run

You should run Xray first and then run Sing-Box core.

