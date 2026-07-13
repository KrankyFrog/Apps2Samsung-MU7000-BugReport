# Apps2Samsung bug report evidence — Samsung UN65MU7000

This package supports the issue filed for Apps2Samsung v2.6.0.

## Failing device
- Samsung UN65MU7000
- Firmware: T-KTMAKUC-1410.1
- Developer mode enabled

## Working comparison device
- Samsung UN50TU7000FXZC
- Firmware: T-KTSU2AKUC-2740.1

## Test environment
- Windows 11 Pro
- PC address: 192.168.1.155
- TV address: 192.168.1.138
- Jellyfin endpoint entered in Apps2Samsung: http://192.168.1.253:8096
- Apps2Samsung v2.6.0

## Observed behaviour
The MU7000 is discovered and TCP port 26101 is reachable. Samsung authentication and package re-signing complete, but the TV closes the connection during installation. Jellyfin and AudioRecorder both fail, so the behaviour is not Jellyfin-specific. The newer TU7000 works from the same PC and network.

## Sanitization
Serial numbers, TVKey Device IDs, unique/device status IDs, MAC addresses, Netflix ESN, Jellyfin usernames and user IDs, server IDs, browser URLs/session information, account credentials and local Windows username displays were removed or obscured. Model numbers, firmware versions, application versions and error messages were retained.
