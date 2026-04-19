# Gateway Setup

## Goal

Connect a LoRaWAN gateway to ChirpStack.

## Supported Models

- Raspberry Pi based gateway
- Semtech packet-forwarder gateways
- Basic Station compatible gateways

## Required Parameters

- Gateway EUI
- Server address
- MQTT credentials (if used)
- Frequency plan
- Region

## Typical Workflow

1. Install gateway software
2. Configure server address
3. Configure region plan
4. Set Gateway EUI
5. Start gateway service

## Validation

- Gateway appears online in ChirpStack
- Uplink packets visible
- Gateway statistics updating

## Notes

Use the correct regional LoRaWAN frequency plan.

