# geoip

Fresh geoip files for Tor Expert Bundle.

[![build](https://github.com/icebluey/torgeoip/actions/workflows/build.yml/badge.svg)](https://github.com/icebluey/torgeoip/actions/workflows/build.yml)

## Download

Permanent link to latest release data.

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/icebluey/torgeoip?style=flat)](https://github.com/icebluey/torgeoip/releases)

`https://github.com/icebluey/torgeoip/releases/latest/download/geoip.tar.xz`
```
rm -vf geoip geoip6 geoip-plus-asn geoip6-plus-asn && wget https://github.com/icebluey/torgeoip/releases/latest/download/geoip.tar.xz && tar -xof geoip.tar.xz && sleep 1 && rm -vf geoip.tar* asn.txt version && systemctl restart tor
```

## Original project

https://gitlab.torproject.org/tpo/network-health/metrics/geoip-data/
