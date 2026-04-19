# Architecture

## Overview

This project describes a private LoRaWAN sensing network using ChirpStack.

## Logical Flow

Sensor Nodes
↓
LoRaWAN Radio Links
↓
LoRaWAN Gateway
↓
ChirpStack Network Server
↓
MQTT Broker
↓
Applications / Dashboards / Storage

## Main Components

### End Devices

Battery-powered sensor nodes transmitting uplink telemetry.

Examples:

- temperature
- humidity
- soil moisture
- GPS
- metering

### Gateway

Bridges LoRa radio traffic to IP backhaul.

Typical forms:

- indoor gateway
- outdoor gateway
- Raspberry Pi concentrator gateway

### ChirpStack

Provides:

- device registry
- OTAA joins
- frame processing
- integrations
- administration UI

### MQTT Layer

Used to deliver decoded telemetry to external systems.

Examples:

- Node-RED
- Grafana pipelines
- Python apps
- alert engines

## Security Model

- unique device credentials
- segmented network access
- protected admin access
- secured MQTT credentials

## Deployment Models

### Single Host Lab

Gateway + ChirpStack + MQTT in one local environment.

### Distributed Field Model

Remote gateways forwarding traffic to centralized ChirpStack.

## Expansion Ideas

- multiple gateways
- geolocation
- long-term storage
- AI anomaly detection
- smart agriculture dashboards
