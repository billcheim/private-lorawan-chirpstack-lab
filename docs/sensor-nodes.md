# Sensor Nodes

## Goal

Register LoRaWAN sensor devices and receive telemetry.

## Typical Devices

- Temperature sensors
- Humidity sensors
- Soil sensors
- GPS trackers
- Industrial telemetry nodes

## Required Parameters

- DevEUI
- AppEUI / JoinEUI
- AppKey
- Device profile
- Application assignment

## Typical Workflow

1. Create application in ChirpStack
2. Add device profile
3. Register end device
4. Enter join credentials
5. Power on node
6. Wait for OTAA join

## Validation

- Join request accepted
- Uplink payloads received
- Device shown online
