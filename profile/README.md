<p align="center">
  <img src="cover.png" alt="Svitlochas" width="720">
</p>

# Svitlochas

**Svitlochas** (Світлочас) shows the power outage schedule for a specific address in Ukraine and reminds people before the power goes off.

[Українською](README.uk.md)

## What it is

Scheduled and emergency power cuts are part of everyday life in Ukraine. Each regional distribution company publishes its schedules in its own way: a web page, an image, a PDF or a chat bot. Svitlochas collects this information in one place and turns it into a simple answer to one question: *when will the power be off at my address?*

## Who it is for

- people living in Ukraine who plan their day, work and device charging around outages
- Ukrainians abroad who look after relatives and homes in Ukraine
- anyone who needs the schedule for several places at once, such as home, office and parents

## How it works

1. The backend regularly reads public sources of the regional power distribution companies and brings the schedules to one format.
2. A user picks a region and an address, or an outage queue if they already know it.
3. The app shows the schedule for today and tomorrow hour by hour, with a countdown to the next power cut or restoration.
4. Reminders are scheduled on the device itself, so they arrive even when the app is closed.
5. When a schedule changes during the day, the app shows what changed.

No registration is required. The list of addresses is stored only on the user's device.

## What is available

| | |
|---|---|
| Android app | schedule by address, countdown, reminders, change history, home screen widget |
| Web version | schedule by address or queue with live updates |
| Coverage | 19 regions of Ukraine, address search in most of them |

The project is in active development and has not been published in app stores yet.

## Repositories

| Repository | Purpose |
|---|---|
| `api` | backend: data collection, REST API and live updates |
| `app` | Android app built with Flutter |
| `web` | web client |
| `docs` | documentation and store materials |
| `utils` | research tools |

## Disclaimer

Svitlochas is an unofficial service. It is not affiliated with DTEK, Ukrenergo or any other energy company. Data comes from public sources of distribution system operators and may be delayed. Actual outage times may differ from the published schedule.

## Publisher

Korysnyk LTD, England and Wales, company number 16942523
Website: [svitlochas.care](https://svitlochas.care)
Contact: admin@korysnyk.care
