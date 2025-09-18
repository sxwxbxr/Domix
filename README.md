# Domix
Ein Smart Home Dashboard mit Regeln und MQTT Integration.

## Ziel
Zentrale Steuerung fuer mehrere Systeme mit Uebersicht und Automationen.

## Features
* MQTT Client und Broker Anbindung
* Adapter fuer Home Assistant Loxone Hue LG TV
* Regel Editor Wenn Dann
* Mobile freundliche UI

## Tech Stack
* Next.js 14
* TypeScript
* MQTT.js
* Node RED optional
* Postgres Prisma
* Websockets

## Kritische Packages
* mqtt
* socket io
* zod
* prisma
* next auth optional

## Env Variablen
* MQTT_URL
* DATABASE_URL

## API
* devices topics rules
* ws live updates

## Setup
* pnpm i
* pnpm dev

## Tests
* Simulierter Broker fuer Integration

## CI
* Docker Build und Compose Test

## Security
* TLS fuer MQTT
* RBAC pro Raum

## Roadmap
* Mobile App
* Regel Vorlagen

## Lizenz
Apache 2
