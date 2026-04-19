# Troubleshooting

## Gateway Offline

Check:

- internet or LAN connectivity
- correct server address
- Gateway EUI
- firewall rules

## Device Not Joining

Check:

- DevEUI
- AppKey
- JoinEUI
- frequency plan
- gateway coverage

## No Telemetry in MQTT

Check:

- MQTT broker running
- topic subscription
- credentials
- ChirpStack integrations enabled

## Poor RF Coverage

Check:

- antenna placement
- gateway height
- region settings
- local interference

## Useful Checks

docker ps
docker compose logs
ping gateway_ip
