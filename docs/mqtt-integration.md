# MQTT Integration

## Goal

Consume LoRaWAN telemetry from ChirpStack using MQTT.

## Typical Uses

- Home Assistant
- Node-RED
- Grafana pipelines
- Custom Python applications
- Alerting systems

## Example Broker

Mosquitto

## Typical Topics

application/+/device/+/event/up

## Example Subscribe

mosquitto_sub -h SERVER_IP -t "application/+/device/+/event/up" -v

## Validation

- Uplink messages received
- JSON payload visible
- Device identifiers included

## Notes

Protect MQTT credentials and use network segmentation where possible.
